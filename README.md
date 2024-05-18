# Letterboxd-to-Trakt
A CLI tool to import watched movies and ratings from Letterboxd to Trakt

This script is a modified version of jensb89's [trakt---letterboxd-import](https://github.com/jensb89/trakt---letterboxd-import). Added features:
- ability to import data from ratings.csv file;
- implemented check to avoid uploading duplicates.

## Usage
Python 3 is required for the script to work. To setup the script and use the basic usage check [trakt---letterboxd-import](https://github.com/jensb89/trakt---letterboxd-import). For the script to work the **IMDB metadata download must be active**.

The file ratings.csv from Letterboxd data export can be used to add ratings to the movies when used with the watched.csv file. The usage is as follows:
```
$ python Letterboxd-to-Trakt.py --watched watched.csv --ratings ratings.csv
```

# Thanks
I thank jensb89 for making the base script which I expanded.