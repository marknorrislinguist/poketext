# poketext

I am using text from Pokédex entries from main Pokémon games to practice text processing, web scraping, and using [spaCy](http://spacy.io) for NLP/NLU phenomena.

## Notebooks present:

* `scrape_pokedex_text_simple.ipynb`: scrapes text from [Bulbapedia](https://bulbapedia.bulbagarden.net/wiki/Main_Page) Pokémon by Pokémon and pulls text from Pokédex entries from main series games, writing each entry to a text file.
* `scrape_pokedex_text_bolstered.ipynb`: does the same as above, but it scans the entries to check whether they actually use the name of the Pokémon. If they don't, the program replaces a suitable referring expression with the Pokémon's name.

## Why Pokémon?

The Pokémon universe has been growing for over 20 years, and with that comes a surprising number of characters. This means the potential for a good amount of unique data, esp. re: the Pokémon themselves. However, it can also be easily constrained by only collecting certain kinds of examples (vs., eg, pulling random examples from blogs, social media, or forums).

* The massive amount of information about Pokémon lends itself nicely to a chatbot, and in fact, there already are some Pokémon chatbots, so I'd have something to compare my work to.
* The popularity of the series means that some of the data has already been encoded in usable formats (eg, [`pokemon.json`](https://github.com/fanzeyi/pokemon.json), mentioned below, or [Bulbapedia](https://bulbapedia.bulbagarden.net/wiki/Main_Page), where information pages about the Pokémon are nicely regular.
* Also, it adds a touch of lightness to the practice of learning to manipulate language data with code, as I'm a fan of the games myself!

## Gratitude to:
* [`pokemon.json`](https://github.com/fanzeyi/pokemon.json) for the excellent Pokémon dataset that I pulled names from.

## Copyright Notice

Please note the materials this project is based on are copyrighted by the Pokémon Company
and its affiliates. All data gathered by the editors of 
[Bulbapedia](https://bulbapedia.bulbagarden.net/wiki/Main_Page).
