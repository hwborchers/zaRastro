# Computational Astronomy

## Statistical Astronomy Links

The book [Modern Statistical Methods for Astronomy With R Applications](http://www.cambridge.org/de/academic/subjects/physics/astronomy-general/modern-statistical-methods-astronomy-r-applications) by Feigelson and Babu, Cambridge University Press 2012, provides an introduction to statistics for astronomers and an overview of the foremost methods being used in astrostatistical analysis, illustrated by examples in R. (See also their arXiv preprint [Statistical Methods in Astronomy](https://arxiv.org/abs/1205.2064).)

The Book [Statistics, Data Mining, and Machine Learning in Astronomy](https://press.princeton.edu/titles/10159.html): A Practical Python Guide for the Analysis of Survey Data, by Ivezic, Conolly, VanderPlas, and Gray, Princeton University Press 2014, presents a wealth of practical analysis problems, evaluates techniques for solving them, and explains how to use various approaches for different types ans sizes of data sets.

The Astrostatistics and Astroinformatics Portal (ASAIP) [Software Forum](https://asaip.psu.edu/forums/software-forum) is an R-centric collection of information and discussions regarding software for statistical analysis in astronomy. See especially their [Datasets](https://asaip.psu.edu/resources/datasets) page.

[VOStat](http://iopscience.iop.org/article/10.1086/670053/meta): "A Statistical Web Service for Astronomers", providing interactive statistical analysis of astronomical tabular datasets and integrated into the suite of analysis and visualization tools associated with the international Virtual Observatory (VO) through the SAMP communication system.

The Astrophysics Source Code Library [ASCL.net](http://ascl.net/) is a free online registry for source codes of interest to astronomers and astrophysicists and lists codes that have been used in research that has appeared in, or been submitted to, peer-reviewed publications.


## R Packages for Astronomy

- lira (2017)  
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
- ERFA.jl: Julia wrapper for liberfa
- EarthOrientation.jl: Calculate Earth orientation parameters from IERS tables in Julia
- FITSIO.jl: Flexible Image Transport System (FITS) file support for Julia
- WCS.jl: Astronomical World Coordinate Systems library for Julia
- Cosmology.jl: Cosmology library for Julia
- DustExtinction.jl: Models for the interstellar extinction due to dust

