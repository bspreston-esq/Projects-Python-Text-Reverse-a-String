# Reverse a String

**Category:** Text

## Problem

Enter a string and the program will reverse it and print it out.

## Solution

Ships two implementations: Python's slice idiom `text[::-1]` and an explicit index-walking loop, cross-checked in demo mode. Both handle Unicode code points.

## How to run

Requires Python 3.8+ and no third-party packages.

```bash
python3 main.py "hello world"
python3 main.py --demo
```

## Example

```text
'hello' -> 'olleh'
           'racecar' -> 'racecar'
      'A man, a plan!' -> '!nalp a ,nam A'
            'éclair' -> 'rialcé'
                '' -> ''
Both implementations agree on every sample.
```

## Attribution

The problem statement is from [karan/Projects](https://github.com/karan/Projects), a list of practical projects that anyone can solve in any programming language (MIT License, Copyright (c) 2013 Karan Goel). The Python solution in this repository was implemented by [bspreston-esq](https://github.com/bspreston-esq).

This repository is part of the [Projects-Python-All](https://github.com/bspreston-esq/Projects-Python-All) collection.
