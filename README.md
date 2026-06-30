# LeetCode Practice

A personal collection of solutions to algorithmic problems, written in Python for
practice. It gathers worked solutions to selected LeetCode problems alongside a
set of Codewars katas and small coding exercises.

Author: Molena Huynh, North Carolina State University (`molena.huynh@jmp.com`)

## Contents

- `LeetCode_Practice.ipynb` — a Jupyter notebook with solved LeetCode problems.
  Each solution is annotated with step-by-step print statements that trace the
  algorithm's intermediate state, followed by a block of test cases. Problems
  currently included:
  - **303. Range Sum Query - Immutable** — answered with a prefix-sum array so
    that each range query runs in constant time.
  - **525. Contiguous Array** — answered by mapping cumulative sums (treating `0`
    as `-1`) to their first index to find the longest balanced subarray.
- `Codewars/` — standalone Python scripts from Codewars katas and small exercises:
  - `Sum-of-Digits-Digital-Root-(Python).py` — computes the digital root of a
    number by repeatedly summing its digits.
  - `Asking_for_a_list.py`, `Answer#1.py` — interactive list-building exercises
    that read elements from input.
  - `Bar_graph.py` — draws a simple bar graph using the `turtle` module.
  - `Exercise #1` — scratch work for a list-processing exercise.
- `LICENSE` — MIT License.

## Requirements

- Python 3
- Jupyter (JupyterLab or the classic Notebook) to open `LeetCode_Practice.ipynb`

The `turtle`-based script uses the standard library only and requires a display
environment with Tk support.

## Usage

Open the notebook to read and run the LeetCode solutions:

```bash
jupyter notebook LeetCode_Practice.ipynb
```

Run a Codewars script directly with Python:

```bash
python3 "Codewars/Sum-of-Digits-Digital-Root-(Python).py"
```

The interactive scripts prompt for input on the command line. The notebook
solutions print their intermediate steps when executed, which is intended to make
each algorithm easy to follow.

## Purpose

This repository is a learning log for practicing data structures and algorithms.
The solutions favor readability and explicit tracing over brevity, so the focus is
on understanding how each approach works rather than on producing the shortest
possible code.

## License

This project is released under the MIT License. See [`LICENSE`](LICENSE) for the
full text.
