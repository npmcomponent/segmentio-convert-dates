*This repository is a mirror of the [component](http://component.io) module [segmentio/convert-dates](http://github.com/segmentio/convert-dates). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/segmentio-convert-dates`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# convert-dates

  Convert all Date instances in an object.

## Installation

    $ component install segmentio/convert-dates

## Example

```js
var convert = require('convert-dates');
var obj = { date: new Date() };

obj = convert(obj, function (date) { return 'string'; });

obj.date; // "string"
```

## API

### convertDates(object, converter)
  
  Passes all of the `Date` values in an `object` through the `converter` function.

## License

  MIT
