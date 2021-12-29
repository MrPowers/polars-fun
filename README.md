# polars-fun

[Polars](https://github.com/pola-rs/polars/) is an awesome Rust DataFrame library with Python language bindings.

This repo makes it easy to run Polars code on your local machine.

## Setup & installation

* Clone this repo
* Run `conda env create -f envs/polars-fun.yml` to create a virtual environment
* Run `conda activate polars-fun` to activate the virtual environment
* Optionally create synthetic datasets on your local machine to run some of the examples that use larger datasets.  Specifically, clone [coiled-datasets](https://github.com/coiled/coiled-datasets) and run `python create-scripts/timeseries.py` from the coiled-datasets directory.

## Notebook usage

Run `jupyter lab` to open a browser window where you can easily peruse the notebooks.

## Thanks

The Polars team has done a wonderful job creating an exiting DataFrame library and they should be celebrated for this excellent open source contribution.

