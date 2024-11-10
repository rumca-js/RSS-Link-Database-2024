# Source:Jeff Kaufmann, URL:https://www.jefftk.com/news.rss, language:en-US

## Force Sequential Output with SCP?
 - [https://www.jefftk.com/p/force-sequential-output-with-scp](https://www.jefftk.com/p/force-sequential-output-with-scp)
 - RSS feed: $source
 - date published: 2024-11-09T08:00:00+00:00

<p><span>

In my bioinformatics work I often stream files between linux hosts and
Amazon S3.  This could look like:

</span>

<p>

</p>

<pre>
$ scp host:/path/to/file /dev/stdout | \
    aws s3 cp - s3://bucket/path/to/file
</pre>



<p>

This recently stopped working after upgrading:

</p>

<p>

</p>

<pre>
ftruncate "/dev/stdout": Invalid argument
Couldn't write to "/dev/stdout": Illegal seek
</pre>



<p>

I think I figured out why this is happening:

</p>

<p>

</p>

<ul>

<li><p>New versions of <code>scp</code> use the SFTP protocol instead of
the SCP protocol. [1]

</p></li>
<li><p>SFTP <a href="https://superuser.com/questions/1637963/get-file-via-sftp-to-stdout">may
not download sequentially</a>

</p></li>
</ul>



<p>

With <code>scp</code> I can give the <code>-O</code> flag:

</p>

<p>

</p>

<blockquote>
 Use the legacy SCP protocol for file transfers instead of the SFTP
 protocol.  Forcing the use of the SCP protocol may be necessary for
 servers that do not implement SF

