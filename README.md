# math-extra

[![npm version](https://badge.fury.io/js/math-extra.svg)](https://badge.fury.io/js/math-extra)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A collection of additional mathematical utility functions for Kexra, built on top of the core `math` module.

## Features

- `clamp(x, min, max)` - Clamps a value between min and max
- `lerp(a, b, t)` - Linear interpolation between two values
- `sum(array)` - Calculates the sum of an array of numbers
- `mean(array)` - Calculates the arithmetic mean of an array
- `median(array)` - Calculates the median of an array
- `degToRad(x)` - Converts degrees to radians
- `radToDeg(x)` - Converts radians to degrees

## Installation

```bash
kex install math-extra
```

## Usage

```kx
use math-extra {
  mean,
  clamp
}

say mean([1, 2, 3])  // Output: 2
say clamp(15, 0, 10)  // Output: 10
```

## API Reference

### clamp(x, min, max)

Clamps the value `x` to be within the range `[min, max]`.

- `x`: The value to clamp
- `min`: The minimum value
- `max`: The maximum value
- Returns: The clamped value

### lerp(a, b, t)

Performs linear interpolation between `a` and `b` using parameter `t`.

- `a`: The start value
- `b`: The end value
- `t`: The interpolation parameter (0.0 to 1.0)
- Returns: The interpolated value

### sum(array)

Calculates the sum of all elements in the array.

- `array`: Array of numbers
- Returns: The sum of the array elements

### mean(array)

Calculates the arithmetic mean of the array elements.

- `array`: Array of numbers
- Returns: The mean value

### median(array)

Calculates the median of the array elements.

- `array`: Array of numbers (will be sorted internally)
- Returns: The median value

### degToRad(x)

Converts degrees to radians.

- `x`: Angle in degrees
- Returns: Angle in radians

### radToDeg(x)

Converts radians to degrees.

- `x`: Angle in radians
- Returns: Angle in degrees

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.