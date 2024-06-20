# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Civic Band
 - [https://simonwillison.net/2024/Jun/19/civic-band/#atom-everything](https://simonwillison.net/2024/Jun/19/civic-band/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-19T21:30:46+00:00

<p><a href="https://civic.band/">Civic Band</a></p>
Exciting new civic tech project from Philip James: 30 (and counting) Datasette instances serving full-text search enabled collections of OCRd meeting minutes for different civic governments. Includes <a href="https://alameda.ca.civic.band/civic_minutes/pages">20,000 pages for Alameda</a>, <a href="https://pittsburgh.pa.civic.band/civic_minutes/pages">17,000 for Pittsburgh</a>, <a href="https://baltimore.md.civic.band/civic_minutes/pages">3,567 for Baltimore</a> and an enormous <a href="https://maui-county.hi.civic.band/civic_minutes/pages">117,000 for Maui County</a>.</p>
<p>Philip includes <a href="https://civic.band/how.html">some notes</a> on how they're doing it. They gather PDF minute notes from anywhere that provides API access to them, then run local Tesseract for OCR (the cost of cloud-based OCR proving prohibitive given the volume of data). The collection is then deployed to a single VPS running multiple instances of Dataset

## Weeknotes: Datasette Studio and a whole lot of blogging
 - [https://simonwillison.net/2024/Jun/19/datasette-studio/#atom-everything](https://simonwillison.net/2024/Jun/19/datasette-studio/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-19T04:30:26+00:00

<p>I'm still spinning back up after my trip back to the UK, so actual time spent building things has been less than I'd like. I presented <a href="https://simonwillison.net/2024/Jun/17/cli-language-models/">an hour long workshop on command-line LLM usage</a>, wrote five full blog entries (since my last weeknotes) and I've also been leaning more into short-form link blogging - a lot more prominent on this site now since my <a href="https://simonwillison.net/2024/Jun/12/homepage-redesign/">homepage redesign</a> last week.</p>
<h4 id="datasette-studio">Datasette Studio</h4>
<p>I ran a workshop for a data journalism class recently which included having students try running structured data extraction using <a href="https://github.com/datasette/datasette-extract">datasette-extract</a>. I didn't want to talk them through installing Python etc on their own machines, so I instead took advantage of a project I've been tinkering with for a little while called <strong>Datasette Studio</strong>.</

## About the Lawrence Times
 - [https://simonwillison.net/2024/Jun/19/the-lawrence-times/#atom-everything](https://simonwillison.net/2024/Jun/19/the-lawrence-times/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-19T03:53:49+00:00

<p><a href="https://lawrencekstimes.com/about/">About the Lawrence Times</a></p>
The town of Lawrence, Kansas is where <a href="https://simonwillison.net/2010/Aug/24/what-is-the-history/">Django was born</a>. I'm delighted to learn that it has a new independent online news publication as-of March 2021 - the Lawrence Times.</p>
<p>It's always exciting to see local media startups like this one, and they've been publishing for three years now supported by both advertiser revenue and optional paid subscriptions.

    <p>Via <a href="https://jacobian.org/2024/jun/11/paying-more-for-media/">Jacob Kaplan-Moss</a></p>

## I’ve stopped using box plots. Should you?
 - [https://simonwillison.net/2024/Jun/19/box-plots/#atom-everything](https://simonwillison.net/2024/Jun/19/box-plots/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-19T00:22:55+00:00

<p><a href="https://nightingaledvs.com/ive-stopped-using-box-plots-should-you/">I’ve stopped using box plots. Should you?</a></p>
Nick Desbarats explains box plots (including with <a href="https://www.youtube.com/watch?v=iBq23-eQhp8">this excellent short YouTube video</a>) and then discusses why he thinks "typically less than 20 percent" of participants in his workshops already understand how to read them.</p>
<p>A key problem is that they are unintuitive: a box plot has four sections, two thin lines (the top and bottom whisker segments) and two larger boxes, joined around the median. Each of these elements represents the same number of samples (one quartile each) but the thin lines v.s. thick boxes imply that the whiskers contain less samples than the boxes.

    <p>Via <a href="https://lobste.rs/s/io4aui/i_ve_stopped_using_box_plots_should_you">lobste.rs</a></p>

