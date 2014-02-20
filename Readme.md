*This repository is a mirror of the [component](http://component.io) module [yields/grow-width](http://github.com/yields/grow-width). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-grow-width`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# grow-width

  Grow the width of the given input.

## Installation

  Install with [component(1)](http://component.io):

    $ component install yields/grow-width

## Example

```js
grow(input);
```

## API

### Grow(el)

  Grow the input as the user types.

### update([str])

  Update the input size with `str` or the input own value.

### destroy()

  Unbind internal events and remove the shadow element.

## License

  MIT
