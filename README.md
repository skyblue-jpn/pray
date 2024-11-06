# pray-python

<!-- badges: start -->
<!-- badges: end -->

This is the "Branch Shrine" version of the `pray` package for python. The original R version of the package was created by [YutoriSpine](https://github.com/YutoriSpine/pray).
The goal of `pray-python` is to display ASCII art of objects for prayer not only in python console but also in terminal by using pip.
This package currently includes a function to display a Shinto shrine as ASCII art, providing a unique and visually interesting way to bring symbolic representations to the console.

## Installation

You can install the development version of `pray-python` from [GitHub](https://github.com/skyblue-jpn/pray-python) with:

```sh
pip install git+https://github.com/skyblue-jpn/pray-python.git
```

or you can install via pipx:

```sh
pipx install git+https://github.com/skyblue-jpn/pray-python.git
```

## Example

This is a basic example which shows you how to solve a common problem:

```python
from pray import shinto

# Display the Shinto shrine ASCII art in the console
shinto()
```

or you can use the command line interface:

```sh
shinto
```
