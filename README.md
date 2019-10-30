# Date String Parser

Should take a string representing a period of time and return a number of milliseconds representing the amount of time.

The string should be of the form

`1y 2w 3d 4m`

Where `y` is year, `w` is week, `d` is day and `m` is minute (if that isn't obvious)

Should
- accept the arguments in any order i.e. `1d 3w` is valid
- accept decimal points i.e. `1.3w` weeks

Should not
- accept more than one of each denomination i.e. '1y 1y' is invalid
- accept minus numbers i.e.


## Bonus Points
A function which takes the output of the original function and returns a string of the format shown above.
