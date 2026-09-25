# pyutils

A collection of handy Python utility scripts for everyday development tasks.

## Features

- File system helpers (batch rename, size calculator)
- String manipulation utilities
- Simple config parser
- Timer decorator for profiling

## Installation

```bash
git clone https://github.com/mzvuh0777/pyutils.git
cd pyutils
pip install -r requirements.txt
```

## Usage

```python
from pyutils import timer, file_size

@timer
def my_function():
    # Your code here
    pass

print(file_size("/path/to/file"))
```

## License

MIT
