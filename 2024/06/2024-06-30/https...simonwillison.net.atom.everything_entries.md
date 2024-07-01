# Source:Simon Willison's Weblog, URL:https://simonwillison.net/atom/everything, language:en-us

## The Super Effectiveness of Pokémon Embeddings Using Only Raw JSON and Images
 - [https://simonwillison.net/2024/Jun/30/pokemon-embeddings/#atom-everything](https://simonwillison.net/2024/Jun/30/pokemon-embeddings/#atom-everything)
 - RSS feed: https://simonwillison.net/atom/everything
 - date published: 2024-06-30T21:22:52+00:00

<p><a href="https://minimaxir.com/2024/06/pokemon-embeddings/">The Super Effectiveness of Pokémon Embeddings Using Only Raw JSON and Images</a></p>
A deep dive into embeddings from Max Woolf, exploring 1,000 different Pokémon (loaded from <a href="https://pokeapi.co/">PokéAPI</a> using <a href="https://github.com/minimaxir/pokemon-embeddings/blob/main/query.gql">this epic GraphQL query</a>) and then embedding the cleaned up JSON data using <code>nomic-embed-text-v1.5</code> and the official Pokémon image representations using <code>nomic-embed-vision-v1.5</code>.</p>
<p>I hadn't seen <a href="https://huggingface.co/nomic-ai/nomic-embed-vision-v1.5">nomic-embed-vision-v1.5</a> before: it brings multimodality to Nomic embeddings snd operates in the same embedding space as <code>nomic-embed-text-v1.5</code> which means you can use it to perform CLIP-style tricks comparing text and images. Here's <a href="https://blog.nomic.ai/posts/nomic-embed-vision">their announcement from June 5th</a>

