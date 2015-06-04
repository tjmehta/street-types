# street-types
US street types/suffixes and abbreviations

## Install
```
$ npm install street-types
```

## API
```js
var streetTypes = require('street-types');

console.log(streetTypes);
/*
[
  {
    "suffix": "ALLEY",
    "abbrs": ["ALLEE", "ALLEY", "ALLY", "ALY"],
    "standardAbbr": "ALY"
  },
  {
    "suffix": "ANEX",
    "abbrs": ["ANEX", "ANNEX", "ANNX", "ANX"],
    "standardAbbr": "ANX"
  },
  {
    "suffix": "ARCADE",
    "abbrs": ["ARC", "ARCADE "],
    "standardAbbr": "ARC"
  },
  ...
]
*/
```

## Source
http://pe.usps.gov/text/pub28/28apc_002.htm

## License
MIT