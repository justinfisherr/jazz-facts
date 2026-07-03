# Jazz Facts

## What this is
A retro classic-Mac themed static site collecting all the jazz facts Claude told Justin. Pure HTML/CSS/JS, no build step. Facts live in `facts.js` as a `FACTS` array of `{t: subject, f: fact}`. Each rendered card auto-appends a 🍸.

## Live site
https://justinfisherr.github.io/jazz-facts

## Structure
- index.html — System 7 UI (menu bar, pinstriped title bars, rainbow Apple, shuffle + search)
- facts.js — the data (append new facts here; count updates automatically)

## What's next
- Append new facts to facts.js as Claude serves them
