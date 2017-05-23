# rolldice
A script for simulating rolling dice.

    ./rolldice -h
    usage: rolldice [-h] [N]dM [[N]dM ...]

    Roll dice from the command line Roll N M-sided die where N: number of dice to
    roll (implicitly N=1 if omitted) M: the maximum value on the die (must be at
    least 1) e.g.: 'd6' -> roll one six-sided die '3d20' -> roll three twenty-
    sided dice 'd2 d3 d4' -> roll a two-, three-, and four-sided die

    positional arguments:
      [N]dM       roll N M-sided dice

    optional arguments:
      -h, --help  show this help message and exit