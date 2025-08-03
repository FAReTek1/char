# char.gs

> utilities for single chars 

This is a library for chars which is built for [goboscript](https://github.com/aspizu/goboscript).
It is designed to be used with [inflator](https://github.com/faretek1/inflator).

## Credits

- Unicode list: https://scratch.mit.edu/projects/616351443/

## Installation

Make sure you have inflator installed

`inflate install https://github.com/FAReTek1/char`

add char to your `inflator.toml` config:
```toml
[dependencies]
# ...
char = "https://github.com/FAReTek1/char"
```

## Development

use `inflate install -e .`:

1. clone the respository: `git clone https://github.com/FAReTek1/char`
2. `cd char`
3. `inflate install -e .`
4. `cd test`
5. `inflate`
6. `goboscript build`
7. open `test.sb3`
