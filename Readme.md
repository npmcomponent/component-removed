*This repository is a mirror of the [component](http://component.io) module [component/removed](http://github.com/component/removed). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-removed`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# removed

  Invoke a callback when a DOM element is removed.

## Installation

    $ component install component/removed

## Example

```js
var removed = require('removed');
removed(el, function(){
  console.log('element was removed!');
});
```

## API

### removed(el, fn)

  Invokes `fn` when `el` is removed from the DOM.

### .interval

  The `setInterval` fallback uses `removed.interval`, defaulting to 200ms.

# License

  MIT
