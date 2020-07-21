# Mandelbrot
A program for create Mandelbrot set image

### Badges: 
[![Build Status](https://github.com/murka/mandelbrot/workflows/Rust/badge.svg)](https://github.com/murka/mandelbrot/actions?query=workflow%3ARust) [![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://opensource.org/licenses/MIT)

### Dependencies

Dillinger uses a number of open source projects to work properly:

* [num](https://crates.io/crates/num)
* [image](https://crates.io/crates/image)
* [crossbeam](https://crates.io/crates/crossbeam)

### Example
```sh
$ ./mandebrot mandelbrot.png 1000x750 -1.20,0.35 -1,0.20
```
### Output
![](http://static.mur.st/mandelbrot/mandelbrot.png)
