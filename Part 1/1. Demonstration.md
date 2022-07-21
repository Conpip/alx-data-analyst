[Anaconda][1] is a distribution of packages built for data science. It comes with conda, a package and environment manager. You'll be using conda to create environments for isolating your projects that use different versions of Python and/or different packages. You'll also use it to install, uninstall, and update packages in your environments. Using Anaconda has made my life working with data much more pleasant.

The list of commands used are:

```conda create -n tea_facts python=3```

```source activate tea_facts```

```conda list```

```conda install numpy pandas matplotlib``` 

Note that more recent versions of conda use ```conda activate {environment}``` instead of ```source activate```.

Anaconda comes with the Jupyter notebook package. If you are using Miniconda, you can install [Jupyter notebook][2] as:

```conda install jupyter notebook```

[1]:https://anaconda.org/
[2]:https://jupyter.org/install
