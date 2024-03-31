# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## textract-cli
 - [https://simonwillison.net/2024/Mar/30/textract-cli/#atom-everything](https://simonwillison.net/2024/Mar/30/textract-cli/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-30T19:01:13+00:00

<p><a href="https://github.com/simonw/textract-cli">textract-cli</a></p>
<p>This is my other OCR project from yesterday: I built the thinnest possible CLI wrapper around Amazon Textract, out of frustration at how hard that tool is to use on an ad-hoc basis.</p>

<p>It only works with JPEGs and PNGs (not PDFs) up to 5MB in size, reflecting limitations in Textract&#x27;s synchronous API: it can handle PDFs amazingly well but you have to upload them to an S3 bucket yet and I decided to keep the scope tight for the first version of this tool.</p>

<p>Assuming you&#x27;ve configured AWS credentials already, this is all you need to know:</p>

<p>pipx install textract-cli<br />textract-cli image.jpeg &gt; output.txt</p>

## Running OCR against PDFs and images directly in your browser
 - [https://simonwillison.net/2024/Mar/30/ocr-pdfs-images/#atom-everything](https://simonwillison.net/2024/Mar/30/ocr-pdfs-images/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-30T17:59:56+00:00

<p>I attended the <a href="https://biglocalnews.org/content/events/">Story Discovery At Scale</a> data journalism conference at Stanford this week. One of the perennial hot topics at any journalism conference concerns data extraction: how can we best get data out of PDFs and images?</p>
<p>I've been having some very promising results with Gemini Pro 1.5, Claude 3 and GPT-4 Vision recently - I'll write more about that soon. But those tools are still inconvenient for most people to use.</p>
<p>Meanwhile, older tools like <a href="https://github.com/tesseract-ocr/tesseract">Tesseract OCR</a> are still extremely useful - if only they were easier to use as well.</p>
<p>Then I remembered that Tesseract runs happily in a browser these days thanks to the excellent <a href="https://tesseract.projectnaptha.com/">Tesseract.js</a> project. And PDFs can be processed using JavaScript too thanks to Mozilla's extremely mature and well-tested <a href="https://mozilla.github.io/pdf.js/">PDF.js</a> libr

