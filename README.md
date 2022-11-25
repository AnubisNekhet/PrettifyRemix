# Prettify Remix

This repo contains templates inspired from [@pranavdeshai's](https://github.com/pranavdeshai) [Prettify](https://github.com/pranavdeshai/anki-prettify) deck for various uses.

## Index

| Note type | Link to apkg | Remarks |
| --------- | ------------ | ------- | 
| Reversed | | - |
| Reversed Optional | | - |
| Cloze | | Contains an extra parameter to align items left |
| Sequence | | Randomised item sequences using JS |
| Vanilla Sequence | | Sequence but with minimal css and html |
| Image Occlusion Enhanced | | - |
| Anking Overhaul | | WIP |

## CSS Compilation

You can build your own CSS as per your specifications.

### Prerequisites

- A sass interpreter, e.g. [dart sass](https://github.com/sass/dart-sass)
- Locally cloned repo

### Building

Run this code in the root folder of the repo:

<pre>
  <code>
    sass ./CSS/style.scss ./CSS/style.css
  </code>
</pre>

Copy the css to each note template manually.
