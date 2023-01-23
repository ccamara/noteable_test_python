## Noteable test

This repository is designed for testing noteable environment.


## Virtual environments

Virtual environments are managed by `conda`, which means that you should have [Anaconda distribution](https://www.anaconda.com) installed (Read [installing instructions on their website](https://www.anaconda.com/distribution/))

**Activate virtual environment**

```
conda activate env/
```

**Deactivate virtual environment:**

```
conda deactivate
```

**Update virtual environment from  `environment.yml`:**

```
conda env update -f environment.yml
```

**Recreate virtual environment from `environment.yml`:**

```
conda env create --prefix env -f environment.yml
```