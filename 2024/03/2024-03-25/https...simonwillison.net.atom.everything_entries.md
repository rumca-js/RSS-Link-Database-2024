# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## sqlite-schema-diagram.sql
 - [https://simonwillison.net/2024/Mar/25/sqlite-schema-diagramsql/#atom-everything](https://simonwillison.net/2024/Mar/25/sqlite-schema-diagramsql/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-03-25T05:12:47+00:00

<p><a href="https://gitlab.com/Screwtapello/sqlite-schema-diagram/-/blob/main/sqlite-schema-diagram.sql">sqlite-schema-diagram.sql</a></p>
<p>A SQLite SQL query that directly returns a GraphViz definition that renders a diagram of the database schema, by Tim Allen.</p>

<p>The SQL is beautifully commented. It works as a big set of UNION ALL statements against queries that join data from pragma_table_list(), pragma_table_info() and pragma_foreign_key_list().</p>

    <p>Via <a href="https://news.ycombinator.com/item?id=39798115">Hacker News</a></p>

