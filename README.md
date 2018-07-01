# pluralize-util
A Node.js module that returns the plural form of any noun
## Installation 
```sh
npm install pluralize-util --save
yarn add pluralize-util
bower install pluralize --save
```
## Usage
### Javascript
```javascript
var pluralise = require('pluralize-util');
var boys = pluralise.getPlural('Boy');
```
```sh
Output should be 'Boys'
```
### TypeScript
```typescript
import { getPlural } from 'pluralize-util';
console.log(getPlural('Goose'))
```
```sh
Output should be 'Geese'
```
### AMD
```javascript
define(function(require,exports,module){
  var pluralise = require('pluralize-util');
});
```
## Test 
```sh
npm run test
```