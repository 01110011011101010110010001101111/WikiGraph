# WikiGraph
TigerGraph Wikipedia Sample Graph — Useful for Searching

## Data

This data was scraped from Wikipedia via BeautifulSoup (as shown in the notebook).

## Schema

The schema consists of Wikipedia articles (`Doc`) linking to each other (`LINKS_TO`) (with a weight of links_referenced_article / total_links_in_article). In addition, entities (`Entity`) (keywords) are linked to the `Doc` vertices with a weighted edge (`DOC_ENTITY`) with the score from a keyword extraction algorithm.
