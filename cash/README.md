#CASH

## Goal : Convert one currency to other ones in real time

First step :
<ol>
<li>Fork the project via `github` and clone it

![fork](C:/Users/maxim/IdeaProjects/3-musketeers/fork.png)
</li>

In the cmd :

$ cd path_to_workspace $ node cash.js

Several commands :

First you need to install the dependencies "chalk", "conf", "got", "meow", "money", "ora" with the instruction 
❯ cd /path/to/workspace/3-musketeers/cash

The most important library is money.js :
money.js is a simple library with one function: to convert a money value from any currency to any other currency.

                      
2nd step : run the programm

To run the program, there is an example bellow :

$ cash 500 usd eur pln
$ cash --set usd aud

How does it work ?

The program is looking to the API adress in the constants.js file.
After checking the actual currencie rate on internet, the programset the currency goal in an array.
With the convert methode from the libraries, the prgram convert 1 USD into Euro, British Pound or Japense Yen depending which one you have stated.
             



                                                       