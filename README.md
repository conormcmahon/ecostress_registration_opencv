This package corrects spatial misregistration of ECOSTRESS imagery using the SIFT features in OpenCV. 

ECOSTRESS imagery is natively misregistered, often by 1 km or more, which makes it impossible to use for analyses requiring fine spatial information unless the misregistration is corrected. This can be done manually, but for users who are interested in understanding seasonal or diurnal patterns, an automated approach is necessary. 

I recommend creating a virtual environment to use this library. You can do so as follows, after you've installed Python, replacing the pathname with one of your choice. It doesn't matter where you choose, so long as you remember the location to load it again later.

```

python -m venv /path/to/your/desired/environment
path\to\your\desired\environment\activate

```

Please install the following using pip:

```

pip install opencv-python
pip install opencv_contrib-python
pip install geopandas
pip install rasterio
pip install rioxarray
pip install earthaccess
pip install hvplot
pip install holoviews

```

Note - I've tried to install OpenCV using Conda and have not had success, but that's another option you could consider if you'd like to avoid pip. 
