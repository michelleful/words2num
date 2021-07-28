# words2num

Inverse text normalization for numbers. Currently only supports en-US locale.

This fork allows for two additional functionalities:
- you can intersperse numeric values, e.g. "42 million" instead of only "forty-two million"
- you can use "dozen" as a unit

## Usage

Example: `w2n("forty-two hundred and forty-two")`

## Installation

`python -m pip install git+https://github.com/michelleful/words2num.git#egg=words2num`
