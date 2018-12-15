# Computational Astronomy

## Astronomy Links

### Books on Astronomy and Statistics

The book [Modern Statistical Methods for Astronomy With R Applications](http://www.cambridge.org/de/academic/subjects/physics/astronomy-general/modern-statistical-methods-astronomy-r-applications) by Feigelson and Babu, Cambridge University Press 2012, provides an introduction to statistics for astronomers and an overview of the foremost methods being used in astrostatistical analysis, illustrated by examples in R. (See their arXiv preprint [Statistical Methods in Astronomy](https://arxiv.org/abs/1205.2064) and Feigelson's [Tutorials on AstroStatistics](http://rmarkdown.rstudio.com/ioslides_presentation_format.html) and R.)

The book [Statistics, Data Mining, and Machine Learning in Astronomy](https://press.princeton.edu/titles/10159.html): A Practical Python Guide for the Analysis of Survey Data, by Ivezic, Conolly, VanderPlas, and Gray, Princeton University Press 2014, presents a wealth of practical analysis problems, evaluates techniques for solving them, and explains how to use various approaches for different types ans sizes of data sets.

The book [Bayesian Models for Astrophysical Data](https://www.bayesianmodelsforastrophysicaldata.com/): Using R, Jags, Python and Stan, by Hilbe, de Souza, and Ishida, Cambridge University Press 2017, is a comprehensive guide to Bayesian methods in astronomy,  enabling hands-on work by supplying complete R, JAGS, Python, and Stan code, to use directly or to adapt. It provides the reader with guidelines on how to develop code for modeling such data, as well as on how to evaluate a model as to its fit.

[Bayesian Models in Cosmology](https://arxiv.org/abs/1701.01467) presents an overview of Bayesian statistics, the underlying concepts and application methodology that will be useful to astronomers seeking to analyse and interpret a wide variety of data about the Universe. The level starts from elementary notions, without assuming any previous knowledge of statistical methods, and then progresses to more advanced, research-level topics.

### Software Libraries for Astronomy

The COsmostatistics INitiative (COIN), a working group built within the International Astrostatistics Association (IAA), aims to create a friendly environment where hands-on collaboration between astronomers, cosmologists, statisticians and machine learning experts can flourish. COIN is designed to promote the development of a new family of tools for data exploration in cosmology, see the [COINtoolbox](http://cointoolbox.github.io/).

[VOStat](http://iopscience.iop.org/article/10.1086/670053/meta): "A Statistical Web Service for Astronomers", providing interactive statistical analysis of astronomical tabular datasets and integrated into the suite of analysis and visualization tools associated with the international Virtual Observatory (VO) through the SAMP communication system.

The Astrophysics Source Code Library [ASCL.net](http://ascl.net/) is a free online registry for source codes of interest to astronomers and astrophysicists and lists codes that have been used in research that has appeared in, or been submitted to, peer-reviewed publications.

The Astrostatistics and Astroinformatics Portal (ASAIP) [Software Forum](https://asaip.psu.edu/forums/software-forum) is an R-centric collection of information and discussions regarding software for statistical analysis in astronomy. See especially their [Datasets](https://asaip.psu.edu/resources/datasets) page.

### Journals and News

- [Astronomy and Computing](https://www.journals.elsevier.com/astronomy-and-computing) is a peer-reviewed Elsevier journal that focuses on the broad area between astronomy, computer science and information technology. The journal aims to publish the work of scientists and (software) engineers in all aspects of astronomical computing, ...

- [SIMBAD](https://simbad.u-strasbg.fr/simbad/) Astronomical Database: The purpose of Simbad is to provide information on astronomical objects of interest which have been studied in scientific articles.

- [Space and Astronomy News](https://www.technology.org/category/space/astronomy/) and 
  [Universe Today](https://www.universetoday.com/).

### Research Groups with Software

- [Cosmology Research Group](http://www.cosmology.ethz.ch/) at the ETH Zürich with [Software Lab](http://www.cosmology.ethz.ch/research/software-lab.html). For instance PyCosmo, a Python-based framework to numerically solve the Einstein-Boltzmann equations governing the evolution of linear perturbations in the Universe.

### Astronomy Sites

- [NASA.org](https://www.nasa.gov/) and [Space.com](https://www.space.com/) websites:
  Space exploration and Astronomy News.

- Online Planetarium [The Sky Live](https://theskylive.com/planetarium)
  and [Astronomie.de](https://www.astronomie.de/) (in German).

- [Hubble Site](http://hubblesite.org/) and the [LIGO](https://www.ligo.caltech.edu/) Observatory
  (for gravitational waves).

- The [International Space Station](https://www.nasa.gov/mission_pages/station/main/) (ISS) and
  [where it is](http://www.esa.int/Our_Activities/Human_Spaceflight/International_Space_Station/Where_is_the_International_Space_Station) at this moment.

### Exoplanet Data and Graphs

- The [Exoplanet Data Explorer](http://exoplanets.org/) provides an 
  interactive table and plotter for exploring and displaying data from 
  the Exoplanet Orbit Database.

- See also the NASA [Exoplanet Exploration](https://exoplanets.nasa.gov/) 
  page and the search for life on planets beyond our solar system.

- The [Extrasolar Planets Encyclopaedia](exoplane.eu/catalog) catalogue 
  and plotting tool.

- The [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/) 
  of the NASA Exoplanet Science Institute is an online astronomical 
  exoplanet and stellar catalog and data service.

- The [Habitable Zone Gallery](http://www.hzgallery.org/)
  and [SETI@home](https://setiathome.berkeley.edu/)
  (see also [Fermi's Paradox](http://fermisparadox.com/)).


## R Packages for Astronomy

- suncalc (2018)  
  calculates sun position, sunlight phases (times for sunrise, sunset, dusk, etc.), moon position and lunar phase for the given location and time; interface to the 'suncalc.js' library, part of the [SunCalc.net](<http://suncalc.net>) project.

- lira (2018)  
  performs Bayesian linear regression and forecasting in Astronomy, accounting for all kinds of errors and correlations in the data.

- celestial (2017)  
  includes a collection of common astronomical functions and conversion routines, particularly the HMS and degrees schemes.

- astrochron (2017)  
  contains routines for astronomical time scale construction, time series analysis, time scale development, and paleoclimate analysis.

- UPMASK (2017)  
  performs unsupervised photometric membership assignment in stellar clusters using, e.g., photometry and spatial positions.

- SPADAR (2017)  
  provides functions to create all-sky grid plots of widely used astronomical coordinate systems (equatorial, ecliptic, galactic) and scatter plots of data on any of these systems, including on-the-fly system conversion.

- FITSio (2016)  
  provides utilities to read and write files in the FITS (Flexible Image Transport System) format, a standard format in Astronomy.

- solaR (2016)  
  provides functions to determine the movement of the sun from the earth and to determine incident solar radiation.

- RobPer (2016)  
  calculates periodograms based on (robustly) fitting periodic functions to light curves, i.e., irregularly observed time series, possibly with measurement accuracies, occurring in astroparticle Physics.

- SCEPtER (2015)  
  estimating stellar mass, age, and radius given observational data of effective temperature, [Fe/H], and astroseismic parameters, obtained from pre-computed stellar models.

- SCEPtERbinary (2014)  
  estimating the stellar age for double-lined detached binary systems, adopted from the effective temperature, the metallicity [Fe/H], the mass, and the radius of the two stars.

- astro (2014)  
  provides tools for astronomy; functions provided may be grouped into 4 main areas: cosmology, FITS file manipulation, the Sersic function and general plotting and scripting routines.

- astrodatR (2014)  
  collects 19 datasets from contemporary astronomy research, many of which are described in the textbook ‘Modern Statistical Methods for Astronomy with R Applications’.

- astrolibR (2014)  
  presents an R interface to low-level utilities and codes from the Interactive Data Language (IDL) Astronomy Users Library.

- CosmoPhotoz (2014)  
  performs photometric redshift estimation using generalized linear models.

- CRAC (2014)  
  collects R functions for cosmological research, with its main functions being similar to the python library, cosmolopy.

- moonsun (2013)  
  provides functions for basic astronomical calculations with R.

- snapshot (2013)  
  contains functions for reading and writing N-body snapshots from the GADGET code for cosmological N-body/SPH simulations.

- stellaR (2013)  
  manages and displays stellar evolution tracks and isochrones from the Pisa low-mass database.

- cosmoFns (2012)  
  contains standard expressions for cosmological distances, times, luminosities, etc., and other quantities useful in observational cosmology, including molecular line observations.

- astroFns (2012)
  provides miscellaneous Astronomy (time and position) functions, misc. utilities, and data.


## Python and Julia Packages for Astronomy

### Python

- [Astropy](http://www.astropy.org/)  
  The Astropy Project is a community effort to develop a common core package for Astronomy in Python and foster an ecosystem of interoperable astronomy packages.

- [AstroML](http://www.astroml.org/)  
  AstroML is a Python module for machine learning and data mining built on numpy, scipy, scikit-learn, matplotlib, and astropy,

- [Astrophysics](https://pythonhosted.org/Astropysics/) astrophysics utilities for Python:  
  Astropysics is a Python library containing a variety of utilities and algorithms for reducing, analyzing, and visualizing astronomical data.

[Python for Astronomers](http://www.astropython.org/):  
The purpose of this web site is to act as a community knowledge base for performing astronomy research with Python. It provides a variety of tutorials, code snippets, resources, lists of useful packages, general discussion, advice and also features news items, event information and announcements.

[astLib](http://astlib.sourceforge.net/) Python Astronomy modules:  
astLib is a set of Python modules that provides some tools for research astronomers. It can be used for astronomical plots, some statistics, common calculations, coordinate conversions, and manipulating FITS images with World Coordinate System (WCS).

[AstroPython](http://www.astropython.org/) (Python for Astronomers):  
The purpose of this web site is to act as a community knowledge base for performing astronomy research with Python. It provides a variety of tutorials, code snippets, resources, lists of useful packages, general discussion, advice and also features news items, event information and announcements.
(See their list of [packages](http://www.astropython.org/packages/)).  

[Practical Python for Astromomers](https://python4astronomers.github.io/)
is a series of hands-on workshops to explore the Python language and the powerful analysis tools it provides. The emphasis is on using Python to solve real-world problems that astronomers are likely to encounter in research.

Index of PyPi's [Packages Matching 'astronomy'](https://pypi.python.org/pypi?%3Aaction=search&term=astronomy). 

SIEpedia's [Python for astonomers](http://vivaldi.ll.iac.es/sieinvens/siepedia/pmwiki.php?n=HOWTOs.EmpezandoPython):
In this guide you will find which are the most common Python packages and documentation for astronomy.

### Julia

The [JuliaAstro](https://github.com/JuliaAstro) project lists the following Julia packages for use with astronomical problems:

- UnitfulAstro.jl: An extension of Unitful.jl for astronomers.
- AstronomicalTime.jl: Astronomical time keeping in Julia
- AstroLib.jl: Bundle of small astronomical and astrophysical routines.
- [Celeste.jl](https://github.com/jeff-regier/Celeste.jl): Scalable inference for a generative model of astronomical images  
  Finds and characterizes stars and galaxies in astronomical images. It implements variational inference for the generative model.
- ERFA.jl: Julia wrapper for liberfa
- EarthOrientation.jl: Calculate Earth orientation parameters from IERS tables in Julia
- FITSIO.jl: Flexible Image Transport System (FITS) file support for Julia
- WCS.jl: Astronomical World Coordinate Systems library for Julia
- Cosmology.jl: Cosmology library for Julia
- DustExtinction.jl: Models for the interstellar extinction due to dust
