# word-generator
Generate a random word or password in javascript

## Usage
```js
const generator = require("./generator.js");
const word = new generator({ letters: true }).generate();
// random word
```

## Parameters
The constructor requires a few optionnal parameters :
```js
{
    letters: true,
    capitals: true,
    numbers: true,
    length: size of the word,
    includeSpaces: true,
    overflow: " any charact you want to add",
    specials: true
}
```

## In HTML
If you want to use it in a html document, take the `WordGenerator` class and put it in your document.

## Notice
A generator can be reused.
