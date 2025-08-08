# Hugo Multilingual Example

To build the site locally:

```sh
git clone https://github.com/jmooring/hugo-multilingual-example
cd hugo-multilingual-example
npm i
hugo server
```

## Term translations

Both the term path and term title are translated using the `translationKey`
field in front matter.

```text
content/tags/
├── blau/
│   └── _index.de.md  <-- translationKey: blue
├── blue/
│   └── _index.en.md  <-- translationKey: blue
├── green/
│   └── _index.en.md  <-- translationKey: green
├── grün/
│   └── _index.de.md  <-- translationKey: green
├── red/
│   └── _index.en.md  <-- translationKey: red
└── rot/
    └── _index.de.md  <-- translationKey: red
```
