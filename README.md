# keys-in

[![codecov](https://codecov.io/gh/potato4d/keys-in/branch/master/graph/badge.svg?token=LefazPba8y)](https://codecov.io/gh/potato4d/keys-in)

Simple object key existence check Library

<center>
  <img src="https://user-images.githubusercontent.com/6993514/42135816-86b91738-7d8b-11e8-9f2f-25171043fdef.png" alt="">
</center>

## Installation

```bash
# use NPM
$ npm install -S keys-in

# use Yarn
$ yarn add keys-in
```

## Usage

keysIn(payload: object, keys: string[]): boolean

```js
import keysIn from 'keys-in'

const payload = { name: 'potato4d' }
const keys = ['name', 'email']

console.log(keysIn(payload, keys))
// false

payload.email = 'mail@potato4d.me'

console.log(keysIn(payload, keys))
// true
```

## Contribution

```bash
# Install package
$ yarn

# Run test
$ yarn test

# Run test with coverage
$ yarn test:coverage
```

## LICENSE

MIT
