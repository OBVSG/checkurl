# checkurl utility

Check HTTP responses (including redirects) from given URL(s) 

## Getting started

This utility program `checkurl` uses the following interpreter directive

`#!/usr/bin/env python3`

Also, the third-party library [httpx](https://github.com/encode/httpx) is utilized by this script and should be installed.

## Usage

It is recommended to create a symlink within a (local) `bin/` directory for this file to use the command globally:

```shell
(base) pk2@grace:~/.local/bin$ ln -s /home/pk2/checkurl/checkurl
```

Also, there is a `-h` switch to print a usage:

```shell
(base) pk2@grace:~$ checkurl -h
usage: checkurl [-h] [-i INPUT_FILE] [-o OUTPUT_FILE]

Check URLs including follow_redirects.

options:
  -h, --help            show this help message and exit
  -i INPUT_FILE, --input_file INPUT_FILE
                        Source: Inputfile with URLs to check. If no input file is given, read from stdin
  -o OUTPUT_FILE, --output_file OUTPUT_FILE
                        Output: Outputfile to write checked URLs to, if no output file is given, write to stdout
```
