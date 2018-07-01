# Notebooks used for experiments

In this `notebooks/` directory you find Jupyter notebooks containing notes,
visualizations and results of multiple experiments described in the main thesis
document. The `data/` directory should contain the CSV data files used by the
notebooks, see below for how to access these files, most of them were extracted
from the [Yahoo! Finance](https://finance.yahoo.com/) service.

In order to use these notebooks correctly you need to have Python 3 and all the
dependencies installed on your system.

## Setup

I recommend creating a virtual environment specific for this repository, if you
choose to do so, dependencies will not clash with packages of the same name you
may have in other projects.

### Virtualenv (optional)

```sh
$ pip install virtualenv
$ virtualenv .venv
```

### Install dependencies

Refer to the `Dependencies` section of
[mrjbq7/ta-lib](https://github.com/mrjbq7/ta-lib) to install
[TA-Lib](http://ta-lib.org/hdr_dw.html) on your system, after that install the
project requirements like this:

```sh
$ pip install -r requirements.txt
```

### Download data

You're free to provide your own data and just hook it up in the notebooks, but
you can also access the data used in this research
[here](https://drive.google.com/open?id=1ykvfPR25Wg33hLEPv-X-ywfKEOQjOBPH), for
access tracking purposes you'll be asked to submit an access request which will
be granted shortly.

Once you have access to the shared folder, download all the `*.csv` files and
place them in the `data/` folder.

If you have trouble setting up or accessing the data just [open up a new issue](https://github.com/ZzAntares/is-thesis/issues/new).

### Run the Jupyter notebook server

Finally you can explore the noteboks with Jupyter:

```sh
$ jupyter notebook
```
