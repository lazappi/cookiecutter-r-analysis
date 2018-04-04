R data analysis template
========================

My template for setting up an R analysis project. This template uses
[cookiecutter](https://github.com/audreyr/cookiecutter), a Python templating
tool, to setup a directory structure.

Requirements
------------

Install `cookiecutter` using `pip`:

```
pip install cookiecutter
```

OR

`homebrew`:

```
brew install cookiecutter
```

OR

`conda`:

```
conda install -c conda-forge cookiecutter
```

Usage
-----

Generate a new analysis directory using:

```
cookiecutter gh:lazappi/cookiecutter-r-analysis
```

If this doesn't work try using SSH with the full path:

```
cookiecutter git+ssh://git@github.com/lazappi/cookiecutter-r-analysis.git
```

You will then be asked some questions to set up your project. Leaving answers
blank will select the default (shown in [brackets]).

Structure
----------

The resulting analysis project will have the following structure.

* **R** - Resuable R code (functions etc.)
* **analysis** - R Markdown analysis files
* **docs** - Rendered analysis reports
* **data** - Raw data used for analysis
* **output** - Output files

License
-------

This project is licensed under the terms of the [MIT License](/LICENSE)

Acknowledgements
----------------

Much of this template is based on bdcaf's
[cookiecutter-r-data-analysis](https://github.com/bdcaf/cookiecutter-r-data-analysis)
template.

