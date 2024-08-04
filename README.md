## static-maker

Source code for [battlecatsinfo.github.io](https://github.com/battlecatsinfo/battlecatsinfo.github.io)

## Installation

static-maker use [Node.js](https://nodejs.org/) to generate static files.

```bash
$ git clone "https://github.com/battlecatsinfo/static-maker.git"
$ npm install
$ mkdir out
$ cd out
$ git clone "https://github.com/battlecatsinfo/battlecatsinfo.github.io"
```

## Running the local server

```bash
$ node server.js # or npm start
$ node.server.js --verbose
```

Note: To display images successfully, you may need to clone https://github.com/battlecatsinfo/img to `static-maker/img/`.

## Build

Use Node.js to run build scripts.

```bash
$ node js/foo.js
```

or

```bash
$ cd js
$ node foo.js
```

* `copy-assets.js`: copy files at `staic-maker/static/` folder.
* `copy-data.js`: copy files at `static-maker/data/` folder.
* `combo.js`: produces `combos.html`.
* `rank.js`: produces `rank.html`.
* `medal.js`: produces `medal.html`
* `collab.js`: produces `collabs.html`, `collab/`
* `gacha.js`: produces `gachas.html`, `gacha/`
* `material.js`: produces `material.js`
* `crown.js`: produces `crown.js`
* `gamatoto.js`: produces `gamatoto.html`
* `esearch.js`: produces `esearch.html`

## Publish to Github Pages

```bash
$ cd out
$ git add .
$ git commit -m "commit message"
$ git push
```

## Codding style

* Always indent using tabs
* Always use LF line ending
* Use `require` not `import` in JavaScript files

## Resouces

* Cat obtain/involve: https://docs.google.com/spreadsheets/d/1AOId2OhHT59WgpVtgvUylh_9_l-mf2qWvUqyB2cbm0g/edit?usp=sharing
* Enemy Species: https://docs.google.com/spreadsheets/d/1pVSY0EkiBolHCtoj15JW_T0ih9prya6q_9HCmJ5Jo0k/edit?usp=sharing
* Gacha history: https://home.gamer.com.tw/artwork.php?sn=5349275
* Collab History(Taiwan): https://forum.gamer.com.tw/C.php?bsn=23772&snA=19806
* Collab History(Japan): https://forum.gamer.com.tw/C.php?bsn=23772&snA=20642
* Stage schedule(Taiwan): https://forum.gamer.com.tw/C.php?bsn=23772&snA=20534

※ All resources are reproduced with the permission of the author
