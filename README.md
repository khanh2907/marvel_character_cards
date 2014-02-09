Marvel Character Cards
===========

Live demo: http://khanh.info/marvel_character_cards/

Playing with the Marvel API: http://developer.marvel.com/

Loads up all the characters it can fetch from the API and displays them. When the user clicks on a card, it will show who this character has met (been in a event/series/story together).

## Features

- Who has this character met? By 'met' I mean if the characters have been in any other stories, events or series with another.
- Quick search is available. Just type something and the javascript magic will find stuff for you. (Inspired by the character selection of DOTA2.)
- Press ESC key to reset the cards.
- It now uses a pre-fetched json file if we run out of API calls or if the API service is down.

## Screenshots

![alt tag](screenshots/1.png)
![alt tag](screenshots/2.png)

## Setup

Well it's just HTML and JS at the moment so you don't really need to set anything up except for providing your own API key which you can get from the developer gateway. (This can still be done if you go back to the older commits)

Look at the first two lines of the marvel_service.js file and replace the gibberish with your public and private key. Will implement a PHP wrapper of some sorts in future - if bothered.

USES PHP NOW - I GUESS I WAS BOTHERED...

## TO DO

- ~~Add caching so that we don't exceed our limit of calls~~
- Add lines to connect characters
- Add more stlying to make it look nicer and more visible

## Thanks to:
- [mezdef](https://github.com/mezdef) for helping me with the CSS
  
  
