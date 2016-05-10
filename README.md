# Open Data Board Game

The Open Data Board Game is a board game built around the creation of tools using data.

This repo will contain all the things that are needed to create the game. It is a work in progress as we move from prototype to production.

To play the game you will need:

 - 9 role cards (see instruction on generating below).
 - 44 event cards (see instruction on generating below).
 - 63 tool cards (see instruction on generating below).
 - [Data tiles](tiles/Tilesforprint_A3/) (use black marker to add **personal data** dots or stripes to 2x data tiles in each colour).
 - World board - build and print using a spreadsheet with 3 columns ([social, envionmental and economic icons](world-board/)) and rows for the world scores 0-8.
 - Cones or counters for 4-5 players, each in a different colour (approximately 15 cones or counters per player).
 - Three black counters for the world board.

>Some elements of the game are difficult to print as presented (namely the data tiles).

## Game instructions

See [instuctions](instructions.md)

## How to create the cards

Assuming you already have rvm installed:

```
$ rvm use 2.2
$ bundle install
$ bundle exec rake
```

Look in the `_output` folder for the generated cards.
