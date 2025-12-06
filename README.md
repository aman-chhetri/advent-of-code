# Advent of Code 🎄

> This repository contains my solutions for Advent of Code puzzles. Each day's puzzle is stored in a separate folder under the year (for example, `2025/day-01`). Solutions are implemented in Python and include the puzzle input file where applicable.

### About AOC
---

[Advent of Code](https://adventofcode.com/) is an Advent calendar of small programming puzzles for a variety of skill sets and skill levels that can be solved in any programming language you like. One programming puzzle a day is released from 1st to 25th December, divided in two parts (the second of which is unlocked after solving the first). Advent of Code is created by [Eric Wastl](https://was.tl/), and is 100% free.



### Project Structure

```
advent-of-code/
├── 2025/
│   ├── day_1/
│   │   ├── part-1.py
│   │   ├── part-2.py
│   │   └── input.txt
│   ├── day_2/
│   │   ├── part-1.py
│   │   ├── part-2.py
│   │   └── input.txt
│   └── day_X/
│       ├── part-1.py
│       ├── part-2.py
│       └── input.txt
└── README.md
```

- Each day folder typically contains:
  - `part-1.py` — solution for part 1
  - `part-2.py` — solution for part 2 (optional)
  - `input.txt` — the puzzle input for the day

### How to run a solution
---

Run a day's solution using your Python interpreter. Example (PowerShell / Windows):

```powershell
python .\2025\day-01\part-1.py
python .\2025\day-01\part-2.py
```

If a solution reads from `input.txt` in the same folder it will use that file by default. Ensure you run the command from the repository root or provide the correct path.

### Days / Completed solutions
---

### ❄️ [Day 1: Secret Entrance](https://adventofcode.com/2025/day/1)

  - **Part 1**: Count the number of times the dial points at 0 after each rotation
  - **Part 2**: Count every time the dial passes through 0 during any rotation

    click  here for solutions: [part-1](/2025/day-01/part-1.py) , [part-2](/2025/day-01/part-2.py)

<!-- ### ☃︎ [Day 2: Gift Shop ](https://adventofcode.com/2025/day/2)

- **Part 1**: Find invalid product IDs that are a pattern repeated exactly twice
- **Part 2**: Find invalid product IDs where any sequence of digits is repeated at least twice

  click  here for [solution!](/2025/day-02/part-1.py) -->

### Contribution
---

- Add a new `day-XX` folder under the appropriate year and include `input.txt`, `part-1.py`, and `part-2.py` as needed.
- Open a pull request with a short description of the approach and any notable performance/algorithm details.