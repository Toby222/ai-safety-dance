# AI Safety for Fleshy Humans

**[READ HERE!](AISafety.dance)**

Made by [Nicky Case](https://ncase.me) in collaboration with teens @ [Hack Club](https://hackclub.com)

License for all original words & art: [Creative Commons Attribution-NonCommercial (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)

## How to contribute

Found inaccuracies? Make an Issue! Then (time & spoons permitting) I'll figure out what if anything to do about it, and how to re-write.

Found a typo / weird phrasing / dead or incorrect links? Also make an Issue! But if you want to be more direct, you can also make a Pull Request

## How to translate

Oh god there is *no* easy way to translate this 20,000-word thing. I am so sorry.

First, FORK AND MAKE YOUR OWN REPO for any translations. There is no way in heck any of that will fit easily in here. Here's what to translate:

* The words: Translate the Markdowns
* The webpages: Translate the relevant words in `templates/page_template.html` and in `build.js`
* The images: Use your image editor of choice to edit the words in the images in `media`. Peruse Google Fonts for a good replacement font.

## The janky-as-heck "build process"

Make edits to the Markdowns:

* Introduction is at `index.md`
* Part One is at `p1/p1.md`

To build them into a static site, run the `build.js` Node script

(There's also another build script in `anki/all-orbits-to-anki.js` that converts all the Orbit flashcards in the above markdowns into .txt files that you can then import into Anki. You, dear contributor, probably won't personally need this.)

## Anyway good luck have fun