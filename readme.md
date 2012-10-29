#A fork of Crockford's JSON2 library

See [douglascrockford/JSON-js](https://github.com/douglascrockford/JSON-js) for more details and original code.

This fork takes care not to extend built-in object prototypes and includes fixes for Date serialization and
primitives wrapped as objects. It is also modified to support CommonJS environments using `module.exports`.

##From the original README

JSON is a light-weight, language independent, data interchange format.
See http://www.JSON.org/

The files in this collection implement JSON encoders/decoders in JavaScript.

JSON became a built-in feature of JavaScript when the ECMAScript Programming
Language Standard - Fifth Edition was adopted by the ECMA General Assembly
in December 2009. This library (json2.js) is for applications that are expected
to run in obsolete browsers or JavaScript environments.
