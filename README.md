# Docker image for pycodestyle checker

[pycodestyle](https://pypi.python.org/pypi/pycodestyle) is a Python style guide checker


## Usage

```console
$ docker run --rm -v /path/to/python/code:/code omercnet/pycodestyle
```

## Advanced usage

Exclude files or directories:

```console
$ docker run --rm -v /path/to/python/code:/code \ 
         omercnet/pycodestyle --exclude=skins /code
```

See pycodestyle `--help` for more options:

```console
$ docker run --rm omercnet/pycodestyle --help
```
