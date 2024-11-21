# 2023aoc - COBOL
2023 Advent of Code (https://adventofcode.com/2023/)

## Environment

Install curl

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Install gnucobol

```bash
brew info gnucobol
```

Compile solution code `day1.1.cob` to executable `Day1Silver`

```bash
cobc -x -free -o Day1Silver day1.1.cob
```

EOF
