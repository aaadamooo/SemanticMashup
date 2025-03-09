# Entity Information Fetcher and HTML Generator

A Jupyter Notebook Python script that retrieves entity data (logos, flags, abstracts, images) from **DBpedia** and **Wikidata** using SPARQL queries, then generates a styled HTML page with the collected information.

## Features
- Fetches Wikidata URI and English abstract from DBpedia.
- Retrieves entity logo and manufacturer's country flag from Wikidata.
- Searches for car model images (if applicable).
- Generates a responsive HTML page with collapsible abstract section.

## Usage
1. Run the notebook form colab and enter an entity name (e.g., `Volkswagen_Golf`).
2. The script generates an HTML file with the entity name as the filename.

## Sample output
![Sample output](sample.png)
