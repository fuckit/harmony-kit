#[the harmony module loader and some ES6 Polyfill nonsense is here!]

# Harmony JavaScript Kit

This repo is for figuring out ECMAScript 6 Harmony JavaScript code. Not that many places or browsers appreciate its powerful syntax yet but we're cracking into it right now, no problem. Inspiration for this effort is primarily <a href='//en.wikipedia.org/wiki/Lars_Bak_(computer_programmer)' target='_blank'>Lars Bak</a>, Ryan Dahl, Isaacs, tj, substack and many others. 

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

[The Yehuda Katz Article](https://gist.github.com/wycats/51c96e3adcdb3a68cbc3), March 2013, 

[Tracking V8, Chromium Code Review](https://codereview.chromium.org/all)
