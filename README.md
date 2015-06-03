# RPS Challenge
[![Build Status](https://travis-ci.org/armi1189/rps-challenge.svg?branch=master)](https://travis-ci.org/armi1189/rps-challenge) [![Coverage Status](https://coveralls.io/repos/armi1189/rps-challenge/badge.svg)](https://coveralls.io/r/armi1189/rps-challenge) [![Code Climate](https://codeclimate.com/github/armi1189/rps-challenge/badges/gpa.svg)](https://codeclimate.com/github/armi1189/rps-challenge)
-------
###[Try it on Heroku!](https://safe-caverns-7925.herokuapp.com/)
-------
![HomePage](https://github.com/armi1189/rps-challenge/blob/master/public/img/rp1.jpg)
-------
Tools
-------
Develop: Ruby, Sinatra
Testing: Cucumber, RSpec

How To Run
-------
* Follow [heroku link](https://safe-caverns-7925.herokuapp.com/) and play the game!
* For run locally, clone the repo, run `bundle`, and start sinatra server by typing `ruby server.rb` in the main folder.


What it Is?
----
A simple Rock Paper Scissors game playable from the browser.
The home page requires you to insert your name and choose your game type, normal or lizard/spock variation.
The second page let you choose your weapon, based on the game type, and your opponent, CPU or Human Player (yes.. it's multiplayer!)

VS CPU  
----
Choosing to play against CPU the system will randomly choose a weapon and return the result of the match.

![GamePage VS CPU](https://github.com/armi1189/rps-challenge/blob/master/public/img/rps2.jpg)

VS Human Player
----
Choosing to play against Human Player you will be randomly paired with other players that wants to play in that moment. Then the system will verify the players choiches and returns the winner.

![GamePage VS CPU](https://github.com/armi1189/rps-challenge/blob/master/public/img/rps3.jpg)

Lizard/Spock Variation
----
The game provides also a Lizard/Spock game type, adding two new kind of weapons to the classic game.

[Check the rules on Wikipedia](http://en.wikipedia.org/wiki/Rock-paper-scissors#Additional_weapons)
