[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thomasmanke/HTW/)

## Create and Activate Software Environment

Clone from git
```
git clone https://github.com/thomasmanke/HTW.git
cd HTW
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