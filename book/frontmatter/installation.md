# Installation

A `environment.yml` are provided to install packages using the conda package manager

## Avoid installation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JesperDramsch/skillshare-data-science/HEAD)

You can run these notebooks in cloud computing. This button to binder will automagically install the dependencies for you and let you explore online!

Simply launch Binder: https://mybinder.org/v2/gh/JesperDramsch/skillshare-data-science/HEAD

In addition, every notebook below also has a link to Colab, Paperspace Gradient, and AWS Studio that can run your notebooks in the cloud. These might not have the requirements installed (but honestly they often have the standard ML stack, so you should be good.)

## Using Conda

You can create an `skillshare-data-science` conda environment executing:

![Gif showing installation of environment in conda](/img/set-up-environment.gif)

```
$ conda env create -f notebooks/environment.yml
```

and later activate the environment:

```
$ conda activate skillshare-data-science
```

You might also only update your current environment using:

```
$ conda env update --prefix ./env --file environment.yml  --prune
```
