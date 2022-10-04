# App crashing with Arabic numbers

## Issue
The app would crash when selecting certain chapters of of some books.

## Problem solving

- In Paratext Run Basic Checks > chapter/verse numbers
- If Paratext not avialable run a RegEx on each book: \\[cv] [^1-9]

## Issue found
- In one book, in one chapter, in one verse, Arabic numbers were found after a \v instead of Latin numbers.