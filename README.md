# Introduction

`bar` is a small POSIX shell script that displays a progress bar for any
program that prints progress updates to stderr. Each line on stderr should
contain two integers separated by a space, the first being the units complete
and the second being the total units.


# Usage

    hget http://example.com/file.ext 2>&1 > file.ext | bar
