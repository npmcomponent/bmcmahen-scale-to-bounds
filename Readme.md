*This repository is a mirror of the [component](http://component.io) module [bmcmahen/scale-to-bounds](http://github.com/bmcmahen/scale-to-bounds). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/bmcmahen-scale-to-bounds`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# scale-to-bounds

  given an original width, height, and a max width and height, scale to the maximum size while maintaining original ratio

## Installation

  Install with [component(1)](http://component.io):

    $ component install bmcmahen/scale-to-bounds

## Use

### scale(originalWidth, originalHeight, maxWidth, maxHeight);

### Example

```javascript
var scale = require('scale-to-bounds');
var dimensions = scale(100, 200, 800, 600);
// dimensions.width = maxwidth
// dimensions.height = maxheight
```

## License

  MIT
