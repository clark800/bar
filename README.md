# Introduction

`bar` is a small POSIX shell script that displays a progress bar for any
program that prints progress updates. Each line piped to bar should
contain two integers separated by a space, the first being the units complete
and the second being the total units.


# Usage

    download http://example.com/file.ext | bar
