# Source:Jeff Kaufmann, URL:https://www.jefftk.com/news.rss, language:en-US

## Process Substitution Without Shell?
 - [https://www.jefftk.com/p/process-substitution-without-shell](https://www.jefftk.com/p/process-substitution-without-shell)
 - RSS feed: https://www.jefftk.com/news.rss
 - date published: 2023-11-28T08:00:00+00:00

<p><span>

While I still write a decent amount of shell I generally try to avoid
it.  It's hard for others to read, has a lot of sharp edges, tends to
swallow errors, and handles the unusual situations poorly.  But one
thing that keeps me coming back to it is how easily I can set up trees
of processes.

</span>

<p>

Say I have a program that reads two files together in a single pass
[1] and writes something out.  The inputs you have are compressed, so
you'll need to decompress them, and the output needs to be compressed
before you write it out to storage.  You could do:

</p>

<p>


</p>

<pre>
# download the files
aws s3 cp "$path1" .
aws s3 cp "$path2" .

# decompress the files
gunzip "$file1"
gunzip "$file2"

# run the command
cmd -1 "$file1" -2 "$file2" &gt; "$fileOut"

# compress the output
gzip "$fileOut"

# upload the output
aws s3 cp "$fileOut.gz" "$pathOut"
</pre>



<p>

This works, but for large files it's slow and needs too much space.
We're waiting for each step to fini

