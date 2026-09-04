# STAT163 — Week 2, before the lecture: DataFrames and profiling

Two notebooks to work through before the Week 2 lecture. Nothing to submit.

| Notebook | For whom | Time |
|---|---|---|
| `00-pandas-basics.ipynb` | New to notebooks or pandas, or a year away from Python | 45 min |
| `01-dataframes-and-profiling.ipynb` | Everyone | 50 min |

## Run them with nothing to install

[![Open the basics notebook in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stat163-2026t1/week2-pre-lecture/blob/main/00-pandas-basics.ipynb) `00-pandas-basics.ipynb`

[![Open the Week 2 notebook in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stat163-2026t1/week2-pre-lecture/blob/main/01-dataframes-and-profiling.ipynb) `01-dataframes-and-profiling.ipynb`

**What Colab is.** Google Colab is a Jupyter notebook that runs in your browser, on a
computer at Google, instead of on your laptop. The cells, the order you run them in, and
pandas all work the way they did in the notebook you ran last week.

Two differences from a notebook on your laptop:

- **The computer at Google is temporary.** When you close the tab, it is gone. The
  notebook file in this repository does not change. To keep your edits, use
  **File → Save a copy in Drive**.
- **It cannot see the files on your laptop.** These two notebooks read their data from the
  web and need no other file, so that does not matter here.

## Or run them on your machine

You need [`uv`](https://docs.astral.sh/uv/), the tool that installed pandas for Practice 1,
and Git.

```bash
git clone https://github.com/stat163-2026t1/week2-pre-lecture.git
cd week2-pre-lecture
uv sync
```

Then open a notebook in [Positron](https://positron.posit.co/) and, when it asks which
Python to use, choose the one inside `.venv`. Or run `uv run jupyter lab`.
