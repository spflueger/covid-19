# covid-19
Small python based script for corona virus visualization

## Installation
1. Clone the repo with `git clone --recurse-submodules`
2. Setup a virtual environment for example via `python -m venv pyvenv`
   (This creates directory `pyvenv` inside current directory. You can choose any name you like though)
3. Activate the venv `. pyvenv/bin/activate`
3. Install the requirements via `pip install -r requirements.txt`

## Running
Simply run `jupyter notebook` with your venv activated. Navigate to the `corona-virus-vis.ipynb` notebook and run it.

## Updating the data (submodule)
To get the newest covid data run
```
git submodule update --recursive
```
