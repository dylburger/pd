This repo contains a library of Node.js functions I need to reuse in a few places.

## Usage on Pipedream

```javascript
// No npm install required
const { random } = require("@dylburger/pd")
```

## Other Node projects

First,

```bash
npm i --save @dylburger/pd
```

Then `require` the function you'd like to use in the relevant file:

```javascript
const { random } = require("@dylburger/pd")
```
