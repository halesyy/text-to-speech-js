# text-to-speech-js [![PayPal](https://img.shields.io/badge/%24-paypal-f39c12.svg)][paypal-donations] [![Version](https://img.shields.io/npm/v/text-to-speech-js.svg)](https://www.npmjs.com/package/text-to-speech-js) [![Downloads](https://img.shields.io/npm/dt/text-to-speech-js.svg)](https://www.npmjs.com/package/text-to-speech-js) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

> A small JavaScript library that provides a text to speech conversion using tts-api.com service.

## How to use

[![text-to-speech-js](http://i.imgur.com/Q0uMnvD.png)](http://ionicabizau.github.io/text-to-speech-js/)

## Installation

```sh
$ npm i --save text-to-speech-js
```

## Example

```js
TextToSpeech.talk("Hello Beautiful World!");
```

## Documentation

### `talk(options, notNow)`
Convert the provided text into speech.

#### Params
- **Object** `options`: An object containing:
  - text: a string that must be converted in speech
  - notNow (default: false): don't play it now
- **Boolean** `notNow`: Autoplay or not.

#### Return
- **Audio** The `Audio` instance.

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:

## License

[MIT][license] © [Ionică Bizău][website]

[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2014#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md