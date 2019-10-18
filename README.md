# awesome-atmos
A curated list of awesome Python libraries, software and resources in Atmosphere, Environment and Machine Learning

Inspired by [awesome-python](https://github.com/vinta/awesome-python)

* Awesome Atmosphere
  * Numerical Model
  * Data Assimilation
  * Radar
  * Satellite
  * Calculating Index  
  * Data Processing/Analysis
  * Machine Learning
  * Visualization
  * Resources

---

## Numerical Model
  * [wrf-python](https://wrf-python.readthedocs.io/en/latest/): WRF results postprocessing
  * [CAMxtools](https://github.com/jaegunjung/CAMxtools): CAMx and CMAQ results postprocessing
  * [salem](https://salem.readthedocs.io/en/latest/): Model results post-processing, including WRF pre/post processing
  * [geos2cmaq](https://github.com/barronh/geos2cmaq): Map GEOS-Chem results to CMAQ boundary condition
  * [ingest_cm1](https://github.com/cwebster2/ingest_cm1): A Fortran library to read CM1 output files
  * [CESM_postprocessing](https://github.com/NCAR/CESM_postprocessing): Project repository for the CESM python based post-processing code, documentation and issues tracking.
  * [SuPy](https://github.com/sunt05/SuPy): a Python-enhanced urban climate model with [SUEWS](https://github.com/Urban-Meteorology-Reading/SUEWS) as its computation core.
  * [xskillscore](https://github.com/raybellwaves/xskillscore): xskillscore is an open source project and Python package that provides verification metrics of deterministic (and probabilistic from properscoring) forecasts with xarray.
  * [climpred](https://climpred.readthedocs.io/): An xarray wrapper for analysis of ensemble forecast models for climate prediction.
  * [esmlab](https://esmlab.readthedocs.io/): Tools for working with earth system multi-model analyses with xarray.

## Data Assimilation
  * [DAPPER](https://github.com/nansencenter/DAPPER): Data Assimilation with Python: a Package for Experimental Research (DAPPER). DAPPER enables the numerical investigation of DA methods through a variety of typical test cases and statistics.
  * [pyWRFDART](https://github.com/lmadaus/pyWRFDART): A collection of Python scripts for running WRF with the DART data assimilation system
  * [PSU_WRF_EnKF](https://github.com/myying/PSU_WRF_EnKF): PSU WRF Ensemble-Variational Data Assimilation System

## Radar
  * [PyART](https://github.com/ARM-DOE/pyart): A data model driven interactive toolkit for working with weather radar data.
  * [wradlib](https://wradlib.org/): An open source library for weather radar data processing.
  * [DualPol](https://github.com/nasa/DualPol): Python Interface to Dual-Pol Radar Algorithms.
  * [SingleDop](https://github.com/nasa/DualPol): Single Doppler Retrieval Toolkit.
  * [ARTView](https://github.com/nguy/artview): Interactive radar viewing browser.
  * [PyCINRAD](https://github.com/CyanideCN/PyCINRAD):Decode CINRAD radar data and visualize.

## Satellite
  * [satpy](https://github.com/pytroll/satpy): For Multiple sattlelite data product
  * [PyCAMA](https://dev.knmi.nl/projects/pycama): For TROPOMI Sentinel-5P Level2 product
  * [pys5p](https://github.com/rmvanhees/pys5p): For TROPOMI Sentinel-5P Level1B product
  * [pyresample](https://pyresample.readthedocs.io/en/latest/): resample sattlelite image

## Calculating Index
  * [Metpy](https://unidata.github.io/MetPy/latest/index.html): To calculate many of atmos index
  * [Sharppy](https://github.com/sharppy/SHARPpy): Sounding/Hodograph Analysis and Research Program
  * [atmos](https://github.com/atmos-python/atmos): An atmospheric sciences library for Python
  * [GeoCAT-comp](https://github.com/NCAR/geocat-comp): GeoCAT-comp is the computational component of the GeoCAT project. GeoCAT-comp wraps NCL's non-WRF Fortran routines into Python.

## Data Processing/Anslysis
  * [siphon](https://unidata.github.io/siphon/latest/index.html): Siphon is a collection of Python utilities for downloading data from remote data services
  * [cfgrib](https://github.com/ecmwf/cfgrib): processing grib format file
  * [h5netcdf](https://github.com/shoyer/h5netcdf): Pythonic interface to netCDF4 via h5py
  * [PseudoNetcdf](https://github.com/barronh/pseudonetcdf): PseudoNetCDF like NetCDF except for many scientific format backends
  * [netcdf4-python](https://github.com/Unidata/netcdf4-python): python/numpy interface to the netCDF C library
  * [xarray](http://xarray.pydata.org/en/stable/): N-D labeled arrays and datasets in Python
  * [iris](https://scitools.org.uk/iris/docs/v1.9.0/html/index.html): in- memory manipulation of labeled arrays supported by the UK Met office
  * [PyNio](https://github.com/NCAR/pynio): PyNIO is a multi-format data I/O package with a NetCDF-style interface
  * [xESMF](https://github.com/JiaweiZhuang/xESMF): Universal Regridder for Geospatial Data 
  * [esmlab-regrid](https://github.com/NCAR/esmlab-regrid): a lightweight library for regridding in Python.
  * [geopandas](https://github.com/geopandas/geopandas): Python tools for geographic data
  * [Pandas](https://pandas.pydata.org/):Data structures and computational tools for working with tabular datasets
  * [PySAL](https://github.com/pysal/PySAL): Python spatial analysis library
  * [cdat](https://github.com/CDAT/cdat): Community Data Analysis Tools  
  * [aospy](https://github.com/spencerahill/aospy): Python package for automated analysis and management of gridded climate data
  * [climlab](https://climlab.readthedocs.io/en/latest/):Process-oriented climate modeling
  * [CDMS](https://cdms.readthedocs.io/en/latest/index.html):Python Object-oriented data management system for multidimensional, gridded data used in climate analysis and simulation
  * [eof2](https://github.com/ajdawson/eof2):EOF analysis in Python
  * [statsmodels](http://www.statsmodels.org/devel/):statsmodels is a Python module that provides classes and functions for the estimation of many different statistical models
  * [Pysteps](https://pysteps.readthedocs.io/en/latest/auto_examples/index.html):an open-source Python library for probabilistic precipitation nowcasting
  * [QGIS](https://qgis.org/):C++ GIS platform to visualize, manage, edit, analyse data, and compose printable maps

## Machine Learning
  * [hageleslag](https://github.com/djgagne/hagelslag): Hagelslag is an object-based severe storm hazard forecasting system
  * [IDEA Lab](http://www.mcgovern-fagg.org/idea/index.html): Research in data science and applied artificial intelligence/machine learning with a focus on high-impact real-world applications
  * [EarthML](https://github.com/pyviz-topics/EarthML): Tools for working with machine learning in earth science
  * [sklearn](https://scikit-learn.org/stable/index.html): A Python module for machine learning built on top of SciPy.
  * [keras](https://github.com/keras-team/keras) - High-level neural networks frontend for [TensorFlow](https://github.com/tensorflow/tensorflow), [CNTK](https://github.com/Microsoft/CNTK) and [Theano](https://github.com/Theano/Theano).
  * [TensorFlow](https://github.com/tensorflow/tensorflow/) - Open source software library for numerical computation using data flow graphs.
  * [PyTorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration
  * [MXNet](https://github.com/apache/incubator-mxnet) - Lightweight, Portable, Flexible Distributed/Mobile Deep Learning with Dynamic, Mutation-aware Dataflow Dep Scheduler; for Python, R, Julia, Go, Javascript and more.
  * [XGBoost](https://github.com/dmlc/xgboost) - A parallelized optimized general purpose gradient boosting library.
  * [CatBoost](https://github.com/catboost/catboost) - General purpose gradient boosting on decision trees library with categorical features support out of the box for R.
  * [LightGBM](https://github.com/Microsoft/LightGBM) - Microsoft's fast, distributed, high performance gradient boosting (GBDT, GBRT, GBM or MART) framework based on decision tree algorithms, used for ranking, classification and many other machine learning tasks.
  * [hur-detect](https://github.com/eracah/hur-detect): Deep Semi-Supervised Object Detection for Extreme Weather Events.
  * [pyod](https://github.com/yzhao062/pyod): A Python Toolbox for Scalable Outlier Detection (Anomaly Detection) 

## Visualization
  * [matplotlib](https://github.com/matplotlib/matplotlib): plotting with Python
  * [PyNGL](https://github.com/NCAR/pyngl): PyNGL ("pingle") is a Python module built on top of NCL's graphics library.
  * [Seaborn](https://github.com/mwaskom/seaborn): Statistical data visualization using matplotlib
  * [Basemap](https://matplotlib.org/basemap/): Plot on map projections (with coastlines and political boundaries) using matplotlib.
  * [Cartopy](https://scitools.org.uk/cartopy/docs/latest/): Cartopy is a Python package designed to make drawing maps for data analysis and visualisation easy.
  * [cmaps](https://github.com/hhuangwx/cmaps):Make it easier to use user defined colormaps in matplotlib.Default colormaps are from [NCL](http://www.ncl.ucar.edu/Document/Graphics/color_table_gallery.shtml) website.
  * [holoviews](https://github.com/pyviz/holoviews): make data analysis and visualization seamless and simple
  * [earth wind map](https://github.com/cambecc/earth): a project to visualize global weather conditions [http://earth.nullschool.net](http://earth.nullschool.net/)

---

## Resources
  * [pangeo](https://pangeo.io/): A community platform for Big Data geoscience
  * [ECCO](https://ecco-v4-python-tutorial.readthedocs.io/index.html): global ocean and sea-ice state estimate tutorial. 
  * [NMC-WFT](https://github.com/nmcdev): The R & D Center for Weather Forecasting Technology in NMC, CMA
  * [Python & Practical Application on Climate Variability Studies](https://github.com/royalosyin/Python-Practical-Application-on-Climate-Variability-Studies): Main objective of this tutorial is the transference of know-how in practical applications and management of statistical tools commonly used to explore meteorological time series, focusing on applications to study issues related with the climate variability and climate change. 
  * [Python for Climate and Meteorological Data Analysis and Visualisation](https://github.com/nicolasfauchereau/Auckland_Python_Workshop): Python for Climate and Meteorological Data Analysis and Visualisation.
  * [Example notebooks showing how to work with ECMWF services and data](https://github.com/ecmwf/notebook-examples)

