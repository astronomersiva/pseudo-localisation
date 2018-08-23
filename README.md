### pseudo-localisation

Lightweight pseudo-localisation for Node.

### Installation

`npm install --save pseudo-localisation`

### Usage

```javascript
const pseudolocalisation = require('pseudo-localisation');

let message = 'Hello, World!';
console.log(message); // Ĥéééĺĺŏ, Ẇŏřĺḓ!
```

If you are using with React or Ember(with [ember-auto-import](https://github.com/ef4/ember-auto-import)),

```javascript
import pseudoLocalisation from 'pseudo-localisation';

// you can use it like
pseudoLocalisation('Hello, World!'); // Ĥéééĺĺŏ, Ẇŏřĺḓ!
```

### Credits

* This amazing [blog](https://medium.com/netflix-techblog/pseudo-localization-netflix-12fff76fbcbe) by Netflix.
* [pseudo-localization](https://github.com/tryggvigy/pseudo-localization) for the browser by tryggvigy.


### License

MIT
