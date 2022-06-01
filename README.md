# Mountain Nowcasting

Mountain nowcasting with deep learning.

## Setup

Conda is the recommended way to install everything, you may encounter errors with pip.

To install all the necessary libraries with conda, run:

`conda env create -f environment.yml`

`conda activate meteonet_toolbox`

To install with pip, run:

`python pip install -r requirements.txt`

## Meteonet package use

If errors while importing, either add relevant path in python script with a line like `sys.path.insert(0, os.getcwd())` or just add what you need from the `/meteonet_toolbox/constant.py` file which is very short.

## Testing

Testing project notebooks is in the `/testing` folder.
