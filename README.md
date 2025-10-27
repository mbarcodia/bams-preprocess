# bams-preprocess
Case study for BAMS submission highlighting skill differences from preprocessing steps

## Requirements & Specifications

### Code

Code is written in pytorch. Code can by run in Google Colab via [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/github/username/repo/blob/main/notebook.ipynb](https://colab.research.google.com/github/mbarcodia/bams-preprocess/blob/main/code/CONUS_temp_prediction_r2.ipynb)


### Data
Data is obtained from <https://berkeleyearth.org/data/>. Under the "National and Regional Temperature Data" tab, the 1.0x1.0 gridded monthly average temperature for North America was downloaded then directly read into the .ipynb. 

### Environment

Code was tested on local machines using the following environment.
```
conda create --name env-bams-preprocessing python=3.12.0
conda activate env-bams-preprocessing
conda install numpy scipy pandas matplotlib xarray scikit-learn netCDF4 cartopy pytorch
conda install  palettable flake8  jupyterlab black jupyterlab_code_formatter
pip install ipykernel seaborn cartopy fsspec requests aiohttp h5netcdf wget
```

## Additional Information

### Credits

These tools were built by Marybeth Arcodia for a publication to be submitted to the Bulletin of the American Meteorological Society. The full citation for the article will be listed upon acceptance. 

### License

This project is licensed under an MIT license.
MIT © [Marybeth C. Arcodia](https://github.com/mbarcodia)
