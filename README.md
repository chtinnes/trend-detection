# trend-detection
Stock market trend detection code.

# Installation

## Prerequisite

To get started, you need `git`, `python`, `poetry`, and an IDE of your choice (I would recommend VSCode.)

- Git: [Get it here](https://git-scm.com/downloads)
- Python: [Get it here](https://www.python.org/downloads/) (3.11 recommended)
- Poetry: [Get it here](https://python-poetry.org)
- VSCode: [Get it here](https://code.visualstudio.com/download)

## Download the repository
To download repository use git. Use a shell of your choice (on a Windows system I would recommend git bash, on Linux-based systems bash, on Mac zsh).

Navigate to a folder where you want to manage your code, then clone the repository:

```bash
git clone git@github.com:chtinnes/trend-detection.git
```

Then navigate into the folder (or check it out with your IDE).

## Installation
We use `Python Poetry` to manage the dependencies.
To install all necessary python dependencies, you can open a shell (as above) in the folder you just downloaded.
Then, execute the command:

```bash
poetry update
```

This should install all dependencies you need, and you are ready to get started.

# Getting started
There is a folder `notebooks` inside the repository.
If you installed all dependencies (using poetry), you should be all set to run the notebooks in that folder.

There is one notebook called `playground.ipynb`. This notebook can be executed to understand the basic ideas of the trend detection approach.

After running `poetry update`, there should be a (hidden) folder `.venv`in your folder. You can use this environment for Jupyter. It has all required dependencies.


