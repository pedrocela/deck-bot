This cog was made to help users build, store and search for Clash Royale decks made by other users on the server.

# Requirements
* Pillow (PIL Python3 fork)

# Usage

## Displaying a deck
Create an image of the deck with the 8 cards followed by a name surrounded in quotes. If no name is entered, the deck will be named simply as *Deck*.

`!deck get 3M knight log pump miner ig is skeletons "3M Cycle"`

![Deck](https://github.com/smlbiobot/SML-Cogs/blob/master/wiki/img/deck/deck-thr-kni-the-eli-min-ice-ice-ske.png)

## Saving a deck
Using the `!deck get` command will only display the deck. To actually save the deck to your personal collection, use the `!deck add` command.

`!deck add 3M knight log pump miner ig is skeletons "3M Cycle"`

As a default, you can store up to 5 decks in your personal collection on each server, but this setting can be changed by the admin (TODO).

## Listing decks from your collection
To display your stored decks, use the `!deck list` command.

`!deck list`

![Deck List output](https://github.com/smlbiobot/SML-Cogs/blob/master/wiki/img/deck/deck-list-sml.png)

To list the decks added by another user, add that to the last parameter.

`!deck list @6John`

![Deck list another user](https://github.com/smlbiobot/SML-Cogs/blob/master/wiki/img/deck/deck-list-6john.png)



