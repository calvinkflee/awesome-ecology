# Awesome Ecology
A curated list of awesome ecology packages and tools. Inspired by [awesome-r](https://github.com/qinwf/awesome-R).

- [R packages](#r-packages)
  - [Essentials](#essentials)
  - [Spatial Analysis](#spatial-analysis)
  - [Modelling](#modelling)
  - [Bayesian](#bayesian)
  - [Meta-analysis](#meta-analysis)
  - [Remote Sensing](#remote-sensing)
  - [Data Access](#data-access)


- [Python modules](#python-modules)
  - [Essentials](#py-essentials)
  - [Imagery](#imagery)
  - [Machine Learning](#machine-learning)
  - [Spatial Analysis](#py-sp)


- [Standalone software](#standalone-software)

- [Contributing](#contributing)

- [License](#license)

## R Packages
*See also: [awesome-R](https://github.com/qinwf/awesome-R)*
### Essentials
- [tidyverse](https://github.com/tidyverse/tidyverse) - Easily install and load packages from the tidyverse
  - [dplyr](https://github.com/hadley/dplyr) - Fast data frames manipulation and database query.
  - [ggplot2](https://github.com/hadley/ggplot2) - An implementation of the Grammar of Graphics.
  - [readr](https://github.com/hadley/readr) - A fast and friendly way to read tabular data into R.
  - [tidyr](https://github.com/hadley/tidyr) - Easily tidy data with spread and gather functions.
  - [lubridate](http://cran.r-project.org/web/packages/lubridate/index.html) - A set of functions to work with dates and times.
- [RStudio](http://www.rstudio.org/) - A powerful and productive user interface for R. Works great on Windows, Mac, and Linux.
- [data.table](https://github.com/Rdatatable/data.table) - Fast data manipulation in a short and flexible syntax. Alternative to [dplyr](https://github.com/hadley/dplyr).

### Spatial Analysis
- [ggmap](https://github.com/dkahle/ggmap) -  Plotting maps in R with ggplot2.
- [raster](https://cran.r-project.org/web/packages/raster/vignettes/Raster.pdf) - Package to read, write, and manipulate raster files in R.
- [redlistr](https://github.com/red-list-ecosystem/redlistr) - Tools for performing IUCN Red List classifications
- [rgeos](https://cran.r-project.org/web/packages/rgeos/index.html) - Interface to Geometry Engine - Open Source.
- [rgdal](https://cran.r-project.org/web/packages/rgdal/index.html) - R bindings for the Geospatial Data Abstraction Library.
- [sp](https://edzer.github.io/sp/) - Classes and Methods for Spatial Data.

### Modelling
- [caret](http://cran.r-project.org/web/packages/caret/index.html) - Classification and Regression Training. Provides tools for creating training and testing sets.
- [lme4](https://github.com/lme4/lme4) - Mixed-effects models.
- [xgboost](https://github.com/tqchen/xgboost/tree/master/R-package) - eXtreme Gradient Boosting Tree model, well known for its speed and performance.

#### Species distribution Modelling
- [biomod2](https://www.rdocumentation.org/packages/biomod2/versions/3.3-7) - Ensemble species distribution modelling.

### Bayesian
- [R2WinBUGS](http://cran.r-project.org/web/packages/R2WinBUGS/index.html) - Running WinBUGS and OpenBUGS from R / S-PLUS.
- [rjags](http://cran.r-project.org/web/packages/rjags/index.html) - R interface to the JAGS MCMC library.
- [rstan](http://mc-stan.org/interfaces/rstan.html) - R interface to the Stan MCMC software.

### Meta-analysis
- [metafor](http://www.metafor-project.org/doku.php) - R package for conducting meta analyses.

### Remote Sensing
- [RStoolbox](http://bleutner.github.io/RStoolbox/) - Tools for remote sensing data analysis in R.

### Parallel
- [parallel](http://cran.r-project.org/web/views/HighPerformanceComputing.html) - R started with release 2.14.0 which includes a new package parallel incorporating (slightly revised) copies of packages [multicore](http://cran.r-project.org/web/packages/multicore/index.html) and [snow](http://cran.r-project.org/web/packages/snow/index.html).
- [foreach](http://cran.r-project.org/web/packages/foreach/index.html) - Executing for loops in parallel.

### Data Access
- [rfishbase](https://github.com/ropensci/rfishbase) - Access to [FishBase](http://www.fishbase.org/) API via R.
- [rgbif](https://github.com/ropensci/rgbif) - Access to data from [GBIF](http://www.gbif.org/).
- [rredlist](https://github.com/ropensci/rredlist) - Access to [IUCN Red List of Threatened Species API](http://apiv3.iucnredlist.org/) via R.


## Python Modules
*See also: [awesome-python](https://github.com/vinta/awesome-python)*
<a name="py-essentials"></a>
### Essentials
- [Jupyter Notebook (IPython)](https://jupyter.org) - A rich toolkit to help you make the most out of using Python interactively.
- [Matplotlib](http://matplotlib.org/) - A Python 2D plotting library.
- [NumPy](http://www.numpy.org/) - A fundamental package for scientific computing with Python.
- [Pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.
- [SciPy](https://www.scipy.org/) - A Python-based ecosystem of open-source software for mathematics, science, and engineering.

### Imagery
- [pillow](https://github.com/python-pillow/Pillow) - Pillow is the friendly [PIL](http://www.pythonware.com/products/pil/) fork.
- [scikit-image](http://scikit-image.org/) - A Python library for (scientific) image processing.

### Machine Learning
- [keras](https://github.com/fchollet/keras) - Deep Learning library for Python. Runs on [TensorFlow](https://github.com/tensorflow/tensorflow/), [Theano](https://github.com/Theano/Theano/), or [CNTK](https://github.com/Microsoft/CNTK).
- [scikit-learn](http://scikit-learn.org/) - Machine learning module built on top of SciPy.
- [TensorFlow](https://github.com/tensorflow/tensorflow/) - Open source software library for numerical computation using data flow graphs for scalable machine learning.

<a name="py-sp"></a>
### Spatial Analysis
- [gdal](https://pypi.python.org/pypi/GDAL) - Python bindings for the Geospatial Data Abstraction Library.

## Standalone software
- [gdal](http://www.gdal.org/) - Translator library for raster and vector geospatial data formats.
- [maxent](https://biodiversityinformatics.amnh.org/open_source/maxent/) - Software for modelling species niches and distribution by using MAXiumum ENTropy modelling.
- [QGIS](http://www.qgis.org/en/site/) - Free open source Geographic Information System.

## Contributing
Your contributions are always welcome! Please feel free to post suggestions in the issues tab.

## License
[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
