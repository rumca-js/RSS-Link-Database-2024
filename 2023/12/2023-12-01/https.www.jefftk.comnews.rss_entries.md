# Source:Jeff Kaufmann, URL:https://www.jefftk.com/news.rss, language:en-US

## Benchmarking Bowtie2 Threading
 - [https://www.jefftk.com/p/benchmarking-bowtie2-threading](https://www.jefftk.com/p/benchmarking-bowtie2-threading)
 - RSS feed: https://www.jefftk.com/news.rss
 - date published: 2023-12-01T08:00:00+00:00

<p><span>

I've been using Bowtie2 to align reads to genomes, and one of it's
many settings is the number of threads.  While sometimes people advise
using about as many threads as your machine has cores, but if I'm
running on a big machine are there diminishing returns or a point at
which more threads are counterproductive? Am I better off running more
samples in parallel with more threads each, or fewer with fewer?

</span>

<p>

I decided to run a few tests on an AWS EC2 with a
<code>c6a.8xlarge</code> 32-core AMD machine. The test consisted of
running one 7.2Gb 48M read-pair sample (<a href="https://www.ebi.ac.uk/ena/browser/view/SRR23998356">SRR23998356</a>)
from <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7845645/">Crits-Christoph
et. al 2021</a> through Bowtie2 2.5.2 with the "Human / CHM13plusY"
database from <a href="https://benlangmead.github.io/aws-indexes/bowtie">Langmead's
Index Zone</a>.  The files were streamed from AWS S3 and decompressed
in a separate proces

