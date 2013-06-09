# Harmony JavaScript Standards

This is a guide for writing and understanding ECMAScript 6 Harmony JavaScript code. Not that many places or browsers appreciate its powerful syntax yet but we're cracking into it right now, no problem. Inspiration for this effort is primarily <a href='//en.wikipedia.org/wiki/Lars_Bak_(computer_programmer)' target='_blank'>Lars Bak</a>, Ryan Dahl, Isaacs, tj, substack and many others. 

You are encouraged to fork this repository and make adjustments according to your preferences.

## How we're using Harmony right now

run node .11.x and use any combo of the following on your js file:

block scope:
`--allow-natives-syntax` 
`--harmony-scoping`

getters and setters: 
`--allow-natives-syntax`
`--harmony-collections` 
`--expose-gc`

typof:
`--harmony-typeof`

proxy:
`--harmony-proxies --allow-natives-syntax`

generator iteration:
`--harmony-generators --expose-gc`

generator objects:
`--harmony-generators --harmony-scoping --allow-natives-syntax`

or just generator parsing:
`--harmony-generators`

## Understanding Syntax

next thing i want throw down some definitions and examples, especially yield. plus there's a bunch of other stuff that needs to go up here.

## No License. Cut that shit out.

This software is unlicensed. There's no need to write MIT on your repos.