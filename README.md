[![Java CI with Gradle](https://github.com/timakden/sudoku-validator/actions/workflows/gradle.yml/badge.svg)](https://github.com/timakden/sudoku-validator/actions/workflows/gradle.yml)

# Sudoku validator

Create a command line tool (running on jvm) for validating a standard 9x9 Sudoku puzzle.

Command line: validate.bat puzzleName.txt

File format: csv format each line representing a row e.g.:

```
4,3,5,2,6,9,7,8,1
6,8,2,5,7,1,4,9,3
1,9,7,8,3,4,5,6,2
8,2,6,1,9,5,3,4,7
3,7,4,6,8,2,9,1,5
9,5,1,7,4,3,6,2,8
5,1,9,3,2,6,8,7,4
2,4,8,9,5,7,1,3,6
7,6,3,4,1,8,2,5,9
```

The program should return 0 (VALID) or non-zero (INVALID) value with an error text on stdout (in case of an invalid solution or file).

There should be unit tests covering a range of error conditions, and the project should be maven or gradle based.

It should be possible to unpack the code from a zip, generate test report, build it and use a batch file to call the code from a packaged jar.
