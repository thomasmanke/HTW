# ML2024

Course material for Maschine Learning 2024.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thomasmanke/ML2024/)

## Create and Activate Software Environment

Clone from git
```
git clone https://gitlab.gwdg.de/manke/ml2024.git
cd ml2024
```

Create software environment (mamba)
```
mamba create env -f env.yml
mamba activate ML20024
```

Create software environment (micromamba with Apple M1/M2)
```
CONDA_SUBDIR=osx-64 micromamba create -f env.yml
micromamba activate ML2024
```

## quarto rendering and 
```
quarto render
```

Open `docs/index.html` in a web browser