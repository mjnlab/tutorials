# Applied ML: A Beginner's Guide to Supervised Learning

A neural network that reads handwritten digits (MNIST), written from scratch with nothing but NumPy.
This is the companion code for the MJNLAB blog post with the same title.

## Run it

You only need [uv](https://docs.astral.sh/uv/). It installs the right Python version and all packages for you.

```bash
uv run jupyter lab mnist_from_scratch.ipynb
```

The first run creates the environment, and the notebook downloads the MNIST dataset into `data/`.

## What's inside

- `mnist_from_scratch.ipynb`: the full walkthrough, from loading data to testing the model
- `pyproject.toml` and `uv.lock`: the packages, pinned so everyone gets the same versions
- `.python-version`: the Python version uv will use
