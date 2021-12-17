# Pwnx-Console   

Simple Lightweight Console Style Logs.

## Installation
```
$ npm install pwnx-console.styles --save
```

## Usage
```javascript
// The Package
let styles = require('pwnx-console.styles');

// Vars
a = 'Hello';
b = 'World!';

// Logging
styles.log(a, b);
styles.log('This is a LOG message');
styles.debug('This is a DEBUG message');
styles.error('This is a ERROR message');
styles.warn('This is a WARN message');
styles.stress('This is a STRESS message');
styles.success('This is a SUCCESS message');

styles.red('This is a RED colored message');

```
## License

MIT © [Hacks52](https://github.com/Hacks52)
