#country.js

Introduces new global object: Country.

Now it's only possible to get ISO-3166-1 code for each country using it's full name.

Mapping was taken from Wikipedia (http://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements)

on Aug 4, 2011.


However it's better to synchronize this with http://www.iso.org/iso/list-en1-semic-3.txt.


Library can be used both in browser or on server as NPM module.

```
  npm install country
```

How to use:

```javascript
var country = require('country');
console.log(country['Ukraine']);//should print UA
```

