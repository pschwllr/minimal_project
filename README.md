![Project Logo](assets/banner.png)

[![Code style: ruff-format](https://img.shields.io/badge/code%20style-ruff_format-6340ac.svg)](https://github.com/astral-sh/ruff)
![Coverage Status](https://raw.githubusercontent.com/pschwllr/ch200/main/coverage-badge.svg)

<h1 align="center">
ch200
</h1>

<br>


Just a short project test

## 🔥 Usage

> TODO show in a very small amount of space the **MOST** useful thing your package can do.
> Make it as short as possible! You have an entire set of docs for later.

## 👩‍💻 Installation

Create a new environment, you may also give the environment a different name. 

```
conda create -n ch200 python=3.10 
```

```
conda activate ch200
```

If you need jupyter lab, install it 

```
(ch200) $ pip install jupyterlab
```


## 🛠️ Development installation

Initialize Git (only for the first time). 

Note: You should have create an empty repository on `https://github.com:pschwllr/ch200`.

```
git init
git add * 
git add .*
git commit -m "Initial commit" 
git branch -M main
git remote add origin git@github.com:pschwllr/ch200.git 
git push -u origin main
```

Then add and commit changes as usual. 

To install the package, run

```
(ch200) $ pip install -e ".[test,doc]"
```

### Run tests and coverage

```
(conda_env) $ pip install tox
(conda_env) $ tox
```

### Generate coverage badge

Works after running `tox`

```
(conda_env) $ pip install "genbadge[coverage]"
(conda_env) $ genbadge coverage -i coverage.xml
```


