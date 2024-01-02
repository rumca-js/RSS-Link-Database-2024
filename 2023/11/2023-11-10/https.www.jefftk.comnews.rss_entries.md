# Source:Jeff Kaufmann, URL:https://www.jefftk.com/news.rss, language:en-US

## Wastewater RNA Read Lengths
 - [https://www.jefftk.com/p/wastewater-rna-read-lengths](https://www.jefftk.com/p/wastewater-rna-read-lengths)
 - RSS feed: https://www.jefftk.com/news.rss
 - date published: 2023-11-10T08:00:00+00:00

<p><span>

Let's say you're collecting wastewater and running metagenomic RNA
sequencing, with a focus on human-infecting viruses.  For </span>

<a href="https://www.jefftk.com/p/computational-approaches-to-pathogen-detection">many kinds of
analysis</a> you want a combination of a low cost per base and more
bases per 

<a href="https://www.jefftk.com/p/what-is-a-sequencing-read">sequencing
read</a>. The lowest cost per base these days, by a lot, comes from
paired-end "short read" sequencing (also called "Next Generation
Sequencing", or "Illumina sequencing" after the main vendor), where
an observation looks like reading some number of bases (often 150)
from each end of a nucleic acid fragment:



<p>

</p>

<pre>
+------&gt;&gt;&gt;-----+
| forward read |
+------&gt;&gt;&gt;-----+
               ... gap ...
                         +------&lt;&lt;&lt;-----+
                         | reverse read |
                         +------&lt;&lt;&lt;-----+
</pre>



<p>

Now, if the fragment

