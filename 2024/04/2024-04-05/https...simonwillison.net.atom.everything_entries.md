# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## s3-credentials 0.16
 - [https://simonwillison.net/2024/Apr/5/s3-credentials-016/#atom-everything](https://simonwillison.net/2024/Apr/5/s3-credentials-016/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-05T05:35:57+00:00

<p><a href="https://github.com/simonw/s3-credentials/releases/tag/0.16">s3-credentials 0.16</a></p>
<p>I spent entirely too long this evening trying to figure out why files in my new supposedly public S3 bucket were unavailable to view. It turns out these days you need to set a PublicAccessBlockConfiguration of {&quot;BlockPublicAcls&quot;: false, &quot;IgnorePublicAcls&quot;: false, &quot;BlockPublicPolicy&quot;: false, &quot;RestrictPublicBuckets&quot;: false}.</p>

<p>The &quot;s3-credentials --create-bucket --public&quot; option now does that for you. I also added a &quot;s3-credentials debug-bucket name-of-bucket&quot; command to help figure out why a bucket isn&#x27;t working as expected.</p>

