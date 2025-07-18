# julseb_lib_python_utils

A collection of Python utility functions for string manipulation, date handling, random generation, formatting, and more. Inspired by common JavaScript/TypeScript utility libraries, this package provides a wide range of helpers for everyday development tasks.

## Features
- String case conversion (camelCase, snake_case, kebab-case, etc.)
- Date and time utilities (get_today, get_tomorrow, add_day, etc.)
- Random generators (numbers, strings, avatars, dates, etc.)
- Formatting helpers (format_date, format_hour, stringify_px, etc.)
- Array and object utilities (delete_duplicates, filter_object, sort_by_frequency, etc.)
- Color conversion (hex to RGB, RGB to hex)
- Regex patterns for password and email validation

## Installation

```bash
pip install julseb_lib_python_utils
```

## Usage

Import and use any function:

```python
from julseb_lib_python_utils import get_today, to_camel_case, get_random_number

print(get_today())
print(to_camel_case('Hello world!'))
print(get_random_number(1, 10))
```

## API Reference

Each function is documented with a Python docstring. See the source code for details on arguments and return values.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

MIT © [Julien Sebag](https://julien-sebag.com)
