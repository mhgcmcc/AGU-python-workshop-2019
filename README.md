# Getting Started with Python for Earth Sciences
### By [Eviatar Bach](http://eviatarbach.com/)
---

A four hour crash course in Python focusing on reading and visualizing data-sets used in Earth sciences. The material here has been modified from the courses taught earlier by [Rebekah Esmaili](http://www.rebekahesmaili.com), [Kriti Bhargava](https://cisess.umd.edu/meet-our-scientists/kriti-bhargava/), and Eviatar Bach.

---

This course covers the following:

1. Basics of Jupyter Notebooks and Numpy and masked Arrays.
2. Reading tabular files using pandas, basic plotting using matplotlib and reading NetCDF files.
3. Xarrays
4. Geopgraphical mapping plotiing using cartopy.

<b> Packages covered include </b>:

1. [numpy](https://numpy.org/)
2. [pandas](https://pandas.pydata.org/)
3. [matplotlib.pyplot](https://matplotlib.org/api/pyplot_api.html)
4. [netCDF4](https://unidata.github.io/netcdf4-python/netCDF4/index.html)
5. [xarray](http://xarray.pydata.org/en/stable/)
6. [Cartopy](https://pypi.org/project/Cartopy/)
7. [pyresample](https://pyresample.readthedocs.io/en/latest/)

---
<b> Installation requirement </b>
* To run this you need Anaconda installed on the computer
* Installation instructions are provided for Mac, Windows, and Linux [here](https://github.com/modern-tools-workshop/ncep-workshop/tree/master/Installation_instructions).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/modern-tools-workshop/NCWCP-python-workshop/master)

---
## Resources

### Packages and Tutorials

<b> Pandas </b>
* Short Introduction: https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html
* Cookbook for more details: https://pandas.pydata.org/pandas-docs/stable/user_guide/cookbook.html#cookbook

---
<b> Matplotlib </b>
* Pyplot Tutorial: https://matplotlib.org/3.1.1/tutorials/introductory/pyplot.html

---
<b> Reading self describing file </b>
* <b> NETCDF </b>
    * Detailed tutorial https://unidata.github.io/netcdf4-python/netCDF4/index.html.
* <b> HDF files </b>
    * The package [h5py](https://www.h5py.org/) is similar to netcdf4.
    * User manual at http://docs.h5py.org/en/stable/.
* <b> GRIB/GRIB2 files </b>
    * World Meteorology Association standard format, e.g. commonly used with weather-related models like ECMWF and GFS.
    * Can be opened using [pygrib](https://github.com/jswhit/pygrib).
    * Example usage at https://jswhit.github.io/pygrib/docs/.
* <b> BUFR </b>
    * Another common model format.
    * Open with [python-bufr](https://github.com/pytroll/python-bufr), part of the pytroll project.
---    
    
### General Python resources    
<b> Free online Tutorials</b>
   * Youtube series for absolute beginners [CS Dojo](https://www.youtube.com/watch?v=Z1Yd7upQsXY&list=PLBZBJbE_rGRWeh5mIBhD-hhDwSEDxogDg)
   * Enhance your workflow [Automate Boring Stuff](https://automatetheboringstuff.com/)
