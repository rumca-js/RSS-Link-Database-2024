# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## Ruff v0.4.0: a hand-written recursive descent parser for Python
 - [https://simonwillison.net/2024/Apr/19/ruff-v040/#atom-everything](https://simonwillison.net/2024/Apr/19/ruff-v040/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-19T05:00:26+00:00

<p><a href="https://astral.sh/blog/ruff-v0.4.0">Ruff v0.4.0: a hand-written recursive descent parser for Python</a></p>
<p>The latest release of Ruff - a Python linter and formatter, written in Rust - includes a complete rewrite of the core parser. Previously Ruff used a parser borrowed from RustPython, generated using the LALRPOP parser generator. Victor Hugo Gomes contributed a new parser written from scratch, which provided a 2x speedup and also added error recovery, allowing parsing of invalid Python - super-useful for a linter.</p>

<p>I tried Ruff 0.4.0 just now against Datasette - a reasonably large Python project - and it ran in less than 1/10th of a second. This thing is Fast.</p>

## A POI Database in One Line
 - [https://simonwillison.net/2024/Apr/19/a-poi-database-in-one-line/#atom-everything](https://simonwillison.net/2024/Apr/19/a-poi-database-in-one-line/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-04-19T02:44:58+00:00

<p><a href="https://www.dbreunig.com/2024/04/18/a-poi-database-in-one-line.html">A POI Database in One Line</a></p>
<p>Overture maps offer an extraordinarily useful freely licensed databases of POI (point of interest) listings, principally derived from partners such as Facebook and including restaurants, shops, museums and other locations from all around the world.</p>

<p>Their new &quot;overturemaps&quot; Python CLI utility makes it easy to quickly pull subsets of their data... but requires you to provide a bounding box to do so.</p>

<p>Drew Breunig came up with this delightful recipe for fetching data using LLM and gpt-3.5-turbo to fill in those bounding boxes:</p>

<p>overturemaps download --bbox=$(llm &#x27;Give me a bounding box for Alameda, California expressed as only four numbers delineated by commas, with no spaces, longitude preceding latitude.&#x27;) -f geojsonseq --type=place | geojson-to-sqlite alameda.db places - --nl --pk=id</p>

    <p>Via <a href="https://twitter.co

