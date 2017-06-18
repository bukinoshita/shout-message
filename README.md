# shout-message [![Build Status](https://travis-ci.org/bukinoshita/shout-message.svg?branch=master)](https://travis-ci.org/bukinoshita/shout-message)

> An opinionated message

## Install

```
$ npm install --save shout-message
```


## Usage
```js
const shoutMessage = require('shout-message')

shoutMessage('This is a message')
//=> > This is a message
```

_Uses [chalk](https://github.com/chalk/chalk), will return a message with a nice color._

## API

### shoutMessage(message)

Returns a `console.log`.

#### message

Type: `string`<br>
Required


## Related
- [shout-success](https://github.com/bukinoshita/shout-success) — An opinionated success message
- [shout-error](https://github.com/bukinoshita/shout-error) — An opinionated error message


## License

MIT © [Bu Kinoshita](https://bukinoshita.io)
