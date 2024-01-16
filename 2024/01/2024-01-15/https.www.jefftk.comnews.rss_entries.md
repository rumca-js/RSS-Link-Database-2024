# Source:Jeff Kaufmann, URL:https://www.jefftk.com/news.rss, language:en-US

## Live Sound: Big-O Improvements
 - [https://www.jefftk.com/p/live-sound-big-o-improvements](https://www.jefftk.com/p/live-sound-big-o-improvements)
 - RSS feed: https://www.jefftk.com/news.rss
 - date published: 2024-01-15T08:00:00+00:00

<p><span>

In cost-conscious live sound scenes (ex: contra dance) for decades </span>

<a href="https://www.jefftk.com/p/farewell-to-the-entertainer">one monitor mix was standard</a>
and two was bonus.  Then two was standard.  Now it's common for even
relatively low end systems to be able to give you more mixes than you
need, and in some scenes a separate stereo mix for each each member's
in-ears is standard.  On the other hand, we generally haven't seen an
increase in the number of inputs.  What changed?  Asymptotic
complexity!



<p>

With a traditional analog mixing board, a large part of the cost is
proportional to the product of your inputs and your outputs.  For each
input you need to decide how much should go to each output, which
means at least a little knob.  If a board has <code>N</code> inputs, then every
additional output requires another <code>N</code> knobs.

</p>

<p>

With a digital board, however, it's all virtual.  You need hardware
for each input (<code>N</code>) a

