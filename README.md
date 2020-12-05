# Awesome earthobservation code 

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/elasticlabs/awesome-earthobservation-code)](https://github.com/elasticlabs/awesome-earthobservation-code/stargazers)
![GitHub contributors](https://img.shields.io/github/contributors/elasticlabs/awesome-earthobservation-code)
![GitHub last commit](https://img.shields.io/github/last-commit/elasticlabs/awesome-earthobservation-code)
[![GitHub license](https://img.shields.io/github/license/elasticlabs/awesome-earthobservation-code)](https://github.com/elasticlabs/awesome-earthobservation-code/blob/master/LICENSE)

> A curated list of awesome resources on Earth observation coding libraries and open data

**Please contribute to make this guide better!** Please follow the [Contributing Guidelines](https://github.com/elasticlabs/awesome-earthobservation-code/blob/master/ContributingGuidelines.md). 
Inspired by [Awesome Python](https://github.com/vinta/awesome-python) and [Awesome GIS](https://github.com/elasticlabs/awesome-gis)

<p>
  <img src="https://raw.githubusercontent.com/elasticlabs/awesome-earthobservation-code/main/header.png" alt="Awesome GIS" height="300px">
</p>

**Table Of Contents:**
  - [Learning resources and platforms](#learning-resources-and-platforms)
    - [Data formats](#data-formats)
    - [MOOC](#mooc)
    - [Youtube channels](#youtube-channels)
  - [Software & SaaS](#software-and-saas)
    - [Jupyter based training resources](#jupyter-based-training-resources)
    - [Web Map Servers](#web-map-servers)
    - [Spatial Databases](#spatial-databases)
  - [Language based EO Libraries](#language-based-geospatial-libraries)
    - [Jupyter notebooks](#jupyter-notebooks-librairies)
    - [Python](#python)
    - [C++](#c++)
  - [Data and Utilities ](#data-and-utilities)
  - [Open Forums and communities](#open-forums-and-communities)
  - [Awesome-Awesomeness](#awesome-awesomeness)

----

## Learning resources and platforms
| ▲ [Top](#awesome-earthobservation-code) |
| --- |
### Data formats
- [NetCDF and CF - the basics](https://unidata.github.io/python-training/workshop/CF%20Conventions/netcdf-and-cf-the-basics/) - This workshop will teach some of the basics of Climate and Forecasting metadata for netCDF data files with some hands-on work available in Jupyter Notebooks using Python.

### MOOC
- [Coursera's GIS Specialization](https://www.coursera.org/specializations/gis) - Including `Fundamentals of GIS`, `GIS Data Formats, Design and Quality`, `Geospatial and Environmental Analysis`, `Imagery, Automation, and Applications` and `Capstone: Geospatial Analysis`.
- [EUMetLab training portal](https://training.eumetsat.int/course/view.php?id=158) - The European Space Agency (ESA), the European Organisation for the Exploitation of Meteorological Satellites (EUMETSAT), and the European Center for Medium-Range Weather Forecast (ECMWF) with the Copernicus Atmosphere Monitoring Service (CAMS) organize joint training webinars sessions.
- [Monitoring Atmospheric Composition](https://www.atmospheremooc.org/) - A MOOC about atmospheric monitoring using satellites, in-situ data, and models.
- [Unidata training workshop](https://docs.google.com/presentation/d/1OImxWBNxyj-zdreIarH5GSIuDyREGB62rDah19g6M94/edit#slide=id.p) - Unidata training workshop on CF conventions and data manipulation.
- [Unidata python workshop](https://unidata.github.io/python-training/workshop/workshop-intro/) - Would you like some in-depth training on the scientific Python ecosystem for atmospheric science and meteorology? Work through our workshop materials at your own pace to learn and practice the syntax, functionality, and utility of this powerful programming language, or return to the material after taking the workshop in-person to further your understanding of the material you were taught.
- [Use Open source EO data with python](https://www.earthdatascience.org/courses/use-data-open-source-python/) - Use Data for Earth and Environmental Science in Open Source Python. Intermediate workshop course.

### Youtube channels
- [metPy mondays](https://www.unidata.ucar.edu/blogs/developer/en/tags/metpymonday) - metPy mondays youtube videos
- [Unidata youtube channel](https://www.youtube.com/user/unidatanews) - Unidata youtube channel on Integrated Data Viewer (IDV) and metPy

## Software and saas
| ▲ [Top](#awesome-earthobservation-code) |
| --- |

### Jupyter based training resources
| ▲ [Top](#awesome-earthobservation-code) |
| --- |

Many [Jupyter based](https://jupyter.org/) ![Python](resources/icon/python.png) notebooks involve data access using free or paid API services. For more information, jump to the [EO data services](#data-and-utilities) section of this guide.
- [Kaggle](https://www.kaggle.com/) ![Python](resources/icon/python.png) - Inside Kaggle you’ll find all the code & data you need to do your data science work. Use over 50,000 public datasets and 400,000 public notebooks to conquer any analysis in no time.
- [LTPy](https://gitlab.eumetsat.int/eumetlab/atmosphere/atmosphere/-/blob/master/00_index_ltpy.ipynb) ![Python](resources/icon/python.png) - LTPy, a learning Tool for Python on Atmospheric Composition Data.
- [ECMWF : introduction to Magics](https://github.com/ecmwf/notebook-examples/tree/master/visualisation) - Magics is the latest generation of the ECMWF's meteorological plotting software. It offers an easy way to visualise data coded in meteorological formats such as GRIB, NetCDF and BUFR. The same resource, in [ECMWF Atlassian Confluence collaboration site](https://confluence.ecmwf.int/display/MAGP/Jupyter+notebooks+examples).
- [ECMWF examples](https://github.com/ecmwf/notebook-examples) ![Python](resources/icon/python.png) - The examples in this space should give you a good starting point how you can work with ECMWF services and data through Python using Jupyter notebooks. A [Binder space](https://mybinder.org/v2/gh/ecmwf/notebook-examples/master?filepath=%2Fhome%2Fjovyan) is also available for immediate playground access.
  * [Visualisation meteorological data](https://github.com/ecmwf/notebook-examples/visualisation) using ECMWF's [Magics](https://software.ecmwf.int/magics) plotting package for meteorological data.
  * [Retrieving and processing meteorological data](https://github.com/ecmwf/notebook-examples/processing) using [Metview](https://software.ecmwf.int/metview) and related Python packages.
- [Kaggle MeteoNet North-West France](https://www.kaggle.com/katerpillar/meteonet) ![Python](resources/icon/python.png) - MeteoNet is a meteorological dataset developed and made available by METEO FRANCE, the French national meteorological service. Let’s start playing with the dataset! You can find playful introductory [Notebooks](https://www.kaggle.com/katerpillar/meteonet/notebooks) and in the [Tasks](https://www.kaggle.com/katerpillar/meteonet/tasks) tab some challenges proposals! 
- [MeteoNet : Data exploration toolbox](https://github.com/meteofrance/meteonet) - This repository is intended as a toolbox to handle the MeteoNet dataset. It's also a communication interface with MeteoNet's users : if you have a request or a problem concerning MeteoNet, you can post an issue on this project. 
- [Unidata python training resources](https://unidata.github.io/python-training/) - This site is meant to be a one-stop website for learning how to use Python for earth-science education and research for any experience level.
- [Unidata python examples gallery](https://unidata.github.io/python-training/gallery/gallery-home/) - Check out detailed examples for atmospheric science and meteorology, from data analysis to publication-quality figures. Feel free to use code from these examples in your own work. 
- [Working with Spatio-temporal data in Python](https://annefou.github.io/metos_python/) - With Software Carpentry lessons and Data Carpentry lessons you learn the fundamental data skills needed to conduct research in your field and learn to write simple programs. This one-day workshop will introduce you to Python for analyzing and visualizing spatial-temporal data. We will be using datasets from the environmental sciences that are freely available.

### Web Map Servers
| ▲ [Top](#awesome-earthobservation-code) |
| --- |

### Spatial Databases
| ▲ [Top](#awesome-earthobservation-code) |
| --- |

## Language based EO Libraries
| ▲ [Top](#awesome-earthobservation-code) |
| --- |
### Jupyter notebooks librairies
- [appmode](https://github.com/oschuett/appmode) ![Python](resources/icon/python.png) - A Jupyter extensions that turns notebooks into web applications.
- [ipywidgets](https://ipywidgets.readthedocs.io/en/stable/examples/Widget%20List.html) ![Python](resources/icon/python.png) - Widgets are eventful python objects that have a representation in the browser, often as a control like a slider, textbox, etc. 
- [ipyleaflet](https://ipyleaflet.readthedocs.io/en/latest/) ![Python](resources/icon/python.png) - Interactive maps in the Jupyter notebook.
- [jupyterlab-manager](https://github.com/jupyter-widgets/ipywidgets/tree/master/packages/jupyterlab-manager) ![Python](resources/icon/python.png) - A JupyterLab extension for Jupyter/IPython widgets. 
- [jupyter_bokeh](https://bokeh.org/) ![Python](resources/icon/python.png) - An extension for rendering Bokeh content in JupyterLab notebooks.
- [jupyter-matplotlib](https://matplotlib.org/ ) ![Python](resources/icon/python.png) - An extension for rendering Matplotlib content in JupyterLab notebooks.
- [jupyterlab-plotly](https://plotly.com/python/getting-started/) ![Python](resources/icon/python.png) - The plotly Python library is an interactive, open-source plotting library that supports over 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases.
- [jupyterlab-voyager ](https://data-voyager.gitbook.io/voyager/) ![Python](resources/icon/python.png) - JupyterLab extension visualize data with Voyager.

### Python
| ▲ [Top](#awesome-earthobservation-code) |
| --- |

**Interactive notebooks**
- [binder](https://mybinder.org/) ![Python](resources/icon/python.png) - Have a repository full of Jupyter notebooks? With Binder, open those notebooks in an executable environment, making your code immediately reproducible by anyone, anywhere.
- [Jupyter](https://jupyter.org/) ![Python](resources/icon/python.png) - JupyterLab is a web-based interactive development environment for Jupyter notebooks, code, and data.
- [papermill](https://papermill.readthedocs.io/en/latest/) ![Python](resources/icon/python.png) - Papermill is a tool for parameterizing and executing Jupyter Notebooks.

**Visualization librairies** 
- [bokeh]( https://bokeh.org/) ![Python](resources/icon/python.png) - The Bokeh Visualization Library
- [cmocean](https://matplotlib.org/cmocean/) ![Python](resources/icon/python.png) - This package contains colormaps for commonly-used oceanographic variables.  
- [matplotlib-base](https://matplotlib.org/) ![Python](resources/icon/python.png) - Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.
- [panel](https://panel.holoviz.org/index.html) ![Python](resources/icon/python.png) - A high-level app and dashboarding solution for Python.
- [seaborn](http://seaborn.pydata.org/) ![Python](resources/icon/python.png) - Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

**EO data access & computations**
- [cartopy](https://scitools.org.uk/cartopy/docs/latest/) ![Python](resources/icon/python.png) - Cartopy is a Python package designed for geospatial data processing in order to produce maps and other geospatial data analyses.  
- [ecwmf-api-client]( https://confluence.ecmwf.int/display/WEBAPI/ECMWF+Web+API+Home) ![Python](resources/icon/python.png) - ECMWF WebAPI is a set of services developed by ECMWF to allow users from the outside to access some internal features and data of the centre. 
- [iris](https://scitools.org.uk/iris/docs/latest/) ![Python](resources/icon/python.png) - A powerful, format-agnostic, community-driven Python library for analysing and visualising Earth science data. 
- [iris-grib](https://iris-grib.readthedocs.io/en/stable/) ![Python](resources/icon/python.png) - The library iris-grib provides functionality for converting between weather and climate datasets that are stored as GRIB files and Iris cubes. 
- [magics](https://github.com/ecmwf/magics-python) ![Python](resources/icon/python.png) - Python interface to Magics meteorological plotting package. 
- [metpy](https://unidata.github.io/MetPy/latest/index.html) ![Python](resources/icon/python.png) - MetPy is a collection of tools in Python for reading, visualizing, and performing calculations with weather data.
- [metview](https://software.ecmwf.int/metview) ![Python](resources/icon/python.png) - Python interface to Metview meteorological workstation and batch system.
- [netcdf4](http://unidata.github.io/netcdf4-python/netCDF4/index.html) ![Python](resources/icon/python.png) - netcdf4-python is a Python interface to the netCDF C library.
- [pynio](http://www.pyngl.ucar.edu/Nio.shtml) ![Python](resources/icon/python.png) - PyNIO is a multi-format data I/O package with a NetCDF-style interface. 
- [scipy](https://www.scipy.org/) ![Python](resources/icon/python.png) - SciPy (pronounced “Sigh Pie”) is a Python-based ecosystem of open-source software for mathematics, science, and engineering. In particular [scikit-image](https://scikit-image.org/) for Image processing in Python and [scikit-learn](https://scikit-learn.org/stable/ ) for Machine Learning in Python
- [siphon](https://unidata.github.io/siphon/latest/examples/index.html ) ![Python](resources/icon/python.png) - A collection of Python utilities for retrieving atmospheric and oceanic data from remote sources, focusing on being able to retrieve data from Unidata data technologies, such as the THREDDS data server.

**Generic useful librairies**
- [bottleneck](https://github.com/pydata/bottleneck) ![Python](resources/icon/python.png) - Bottleneck is a collection of fast, NaN-aware NumPy array functions written in C. Working with `pandas` and `xarray`
- [dask](https://dask.org/) ![Python](resources/icon/python.png) - Dask provides advanced parallelism for analytics, enabling performance at scale for the tools you love.
- [descartes](https://pypi.org/project/descartes/ ) ![Python](resources/icon/python.png) - Use Shapely or GeoJSON-like geometric objects as matplotlib paths and patches  
- [numpy]( https://numpy.org/) ![Python](resources/icon/python.png) - The fundamental package for scientific computing with Python.
- [protobuf](https://developers.google.com/protocol-buffers/) ![Python](resources/icon/python.png) - Protocol buffers are a language-neutral, platform-neutral extensible mechanism for serializing structured data. 
- [psycopg2](https://www.psycopg.org/docs/) ![Python](resources/icon/python.png) - Psycopg is the most popular PostgreSQL database adapter for the Python programming language.
- [pygrib](https://github.com/jswhit/pygrib) - `pyGrib` provides a high-level interface to the ECWMF [ECCODES](https://confluence.ecmwf.int/display/ECC) C library for reading GRIB files.
- [pytables](https://www.pytables.org/) ![Python](resources/icon/python.png) - PyTables is a package for managing hierarchical datasets and designed to efficiently and easily cope with extremely large amounts of data.
- [shapely](https://shapely.readthedocs.io/en/stable/project.html) ![Python](resources/icon/python.png) - Manipulation and analysis of geometric objects in the Cartesian plane. 
- [xarray](http://xarray.pydata.org/en/stable/) ![Python](resources/icon/python.png) - xarray (formerly xray) is an open source project and Python package that makes working with labelled multi-dimensional arrays simple, efficient, and fun!


### C++
| ▲ [Top](#awesome-earthobservation-code) |
| --- |
- [GEOS](https://trac.osgeo.org/geos/) ![C++](resources/icon/cplusplus.png) -  GEOS (Geometry Engine - Open Source) is a C++ port of the ​JTS Topology Suite (JTS). It aims to contain the complete functionality of JTS in C++.
- [GeoPandas]( https://geopandas.org/) ![C++](resources/icon/cplusplus.png) - GeoPandas is an open source project to make working with geospatial data in python easier. GeoPandas extends the datatypes used by pandas to allow spatial operations on geometric types.


## Data and Utilities
| ▲ [Top](#awesome-earthobservation-code) |
| --- |
| ▲ [Jupyter based training resources](#jupyter-based-training-resources) |

**Utilities**
 - [BBox finder](http://bboxfinder.com/) - Select an area and get BBox information in vairous projections and formats.
 - [epsg.io](http://epsg.io/) - Coordinate systems worldwide
 - [ecwmf-api-client]( https://confluence.ecmwf.int/display/WEBAPI/ECMWF+Web+API+Home) ![Python](resources/icon/python.png) - ECMWF WebAPI is a set of services developed by ECMWF to allow users from the outside to access some internal features and data of the centre. 

**Data download services**
  - [Climate Data Online](https://www.ncdc.noaa.gov/cdo-web/datasets) - NOAA Climate Data Online is a collection of climatic data that offers public access and consumption via discovery and ordering services. The data available through CDO is available at no charge and can be viewed online or ordered and delivered to your email inbox.
  - [ECMWF public datasets](https://apps.ecmwf.int/datasets/) - Access to these datasets is provided free of charge. Terms and conditions may apply, please check with each individual dataset.
  - [ECMWF Web API](https://confluence.ecmwf.int/display/WEBAPI) - ECMWF WebAPI is a set of services developed by ECMWF to allow users from the outside to access some internal features and data of the centre. 
  - [GEBCO Gridded Bathymetry Data](https://www.gebco.net/data_and_products/gridded_bathymetry_data/) - The GEBCO_2020 grid is a global terrain model for ocean and land at 15 arc-second intervals. 
  - [Natural Earth](https://www.naturalearthdata.com/) - A public domain dataset available at 1:10m, 1:50m, and 1:110 million scales. Featuring tightly integrated vector and raster data, with Natural Earth you can make a variety of visually pleasing, well-crafted maps with cartography or GIS software.
  - [NCEI Integrated Surface Dataset (Global)](https://www.ncei.noaa.gov/metadata/geoportal/rest/metadata/item/gov.noaa.ncdc%3AC00532/html) - The ISD is composed of worldwide surface weather observations from over 35,000 stations, though the best spatial coverage is evident in North America, Europe, Australia, and parts of Asia. Parameters included are: air quality, atmospheric pressure, atmospheric temperature/dew point, atmospheric winds, clouds, precipitation, ocean waves, tides and more. 
  - [Open Weather Map](https://openweathermap.org/api/weathermaps) - OpenWeatherMap provides many kinds of weather maps including Precipitation, Clouds, Pressure, Temperature, Wind. You can connect them to mobile and web apps.
  - [Worldclim](https://www.worldclim.org/) - WorldClim is a database of high spatial resolution global weather and climate data. These data can be used for mapping and spatial modeling. 

**EO data API and web services** 
  - [Climate Data Online : Web Services](https://www.ncdc.noaa.gov/cdo-web/webservices/v2) - NCDC's Climate Data Online (CDO) offers web services that provide access to current data. This API is for developers looking to create their own scripts or programs that use the CDO database of weather and climate data.
  - [Copernicus Sentinel-5 Precursor (Sentinel-5P)](https://sentinels.copernicus.eu/web/sentinel/missions/sentinel-5p)
  - [ECWMF Datasets](https://apps.ecmwf.int/datasets/) - ECWMF offcial public datasets (Global/Regional Reanalyses, Multi-model, Atmospheric composition, Observation Feedback, etc.)
  - [ECWF Datasets Web API](https://confluence.ecmwf.int/display/WEBAPI/Access+ECMWF+Public+Datasets) - Access ECMWF Public Datasets through the official API, using the [ecwmf-api-client](https://confluence.ecmwf.int/display/WEBAPI/ECMWF+Web+API+Home) ![Python](resources/icon/python.png) toolkit.
  - [EUMETSAT AC SAF](https://acsaf.org/) - EUMETSAT Satellite Application Facility on Atmospheric Composition Monitoring
  - [EUMETSAT EO Portal](https://eoportal.eumetsat.int/) - Free of charge access to EUMETSAT datasets.
  - [Copernicus Open Access hub](https://scihub.copernicus.eu/) - The Copernicus Open Access Hub (previously known as Sentinels Scientific Data Hub) provides complete, free and open access to [Sentinel-1](https://sentinels.copernicus.eu/web/sentinel/missions/sentinel-1), [Sentinel-2](https://sentinels.copernicus.eu/web/sentinel/missions/sentinel-2), -[Sentinel-3](https://sentinels.copernicus.eu/web/sentinel/missions/sentinel-3) and [Sentinel-5P](https://sentinels.copernicus.eu/web/sentinel/missions/sentinel-5p) user products, starting from the In-Orbit Commissioning Review (IOCR).
  - [OpenWeatherMap API](https://openweathermap.org/api) - Historical, Current & Forecast worldwide weather data collection. Includes Maps collections.
  - [WEkEO's Harmonized Data Access API](https://www.wekeo.eu/) - Copernicus and Sentinel data at your fingertips alongside cloud computing resources and tools. A REST API allows users to subset data using a programming interface.

## Open Forums and communities
| ▲ [Top](#awesome-earthobservation-code) |
| --- |
- [EUMETSAT](https://www.eumetsat.int/about-us/who-we-are) - European Organisation for the Exploitation of Meteorological Satellites (EUMETSAT)

## Awesome Awesomeness
| ▲ [Top](#awesome-earthobservation-code) |
| --- |