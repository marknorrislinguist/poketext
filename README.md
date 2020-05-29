# poketext

I am using text from Pokédex entries from main Pokémon games to practice text processing, web scraping, and using [spaCy](http://spacy.io) for NLP/NLU phenomena.

## Notebooks present:
* `scrape_pokedex_text_simple.ipynb`: scrapes text from [Bulbapedia](https://bulbapedia.bulbagarden.net/wiki/Main_Page) Pokémon by Pokémon and pulls text from Pokédex entries from main series games, writing each entry to a text file.
* `scrape_pokedex_text_bolstered.ipynb`: does the same as above, but it scans the entries to check whether they actually use the name of the Pokémon. If they don't, the program replaces a suitable referring expression with the Pokémon's name.

## Gratitude to:
* [`pokemon.json`](https://github.com/fanzeyi/pokemon.json) for the excellent Pokémon dataset that I pulled names from.

## Copyright Notice

Please note the materials this project is based on are copyrighted by the Pokémon Company
and its affiliates. All data gathered by the editors of 
[Bulbapedia](https://bulbapedia.bulbagarden.net/wiki/Main_Page).
