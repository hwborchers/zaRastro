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

- [Nature Astronomy](https://xxx.nature.com/natastron) is a monthly, online-only journal (launched in January 2017) publishing research, review and comment at the cutting edge of astronomy, astrophysics, and planetary science. -- [Space and Astronomy News](https://www.technology.org/category/space/astronomy/) from Technology.org -- [Universe Today](https://www.universetoday.com/) with space and astronomy news..

- [SIMBAD](https://simbad.u-strasbg.fr/simbad/) Astronomical Database: The purpose of Simbad is to provide information on astronomical objects of interest which have been studied in scientific articles.

### Research Groups with Software

- [Cosmology Research Group](http://www.cosmology.ethz.ch/) at the ETH Zürich with [Software Lab](http://www.cosmology.ethz.ch/research/software-lab.html). For instance PyCosmo, a Python-based framework to numerically solve the Einstein-Boltzmann equations governing the evolution of linear perturbations in the Universe.

- [Zentrum für Astronomie]() (ZAH) of Heidelberg University with research and teaching activities ranging from planet formation and galaxy evolution to cosmology and state of the art computer physics. It provides downloads for [Gaia Sky](https://zah.uni-heidelberg.de/gaia/outreach/gaiasky), a real-time, 3D, astronomy visualisation software developed in the framework of ESA's Gaia mission to chart about 1 billion stars of our Galaxy.


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

- The [Extrasolar Planets Encyclopaedia](http://exoplanet.eu/catalog) 
  catalogue and plotting tool.

- The [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/) 
  of the NASA Exoplanet Science Institute is an online astronomical 
  exoplanet and stellar catalog and data service.

- The [Habitable Zone Gallery](http://www.hzgallery.org/)
  and [SETI@home](https://setiathome.berkeley.edu/)
  (see also [Fermi's Paradox](http://fermisparadox.com/)).

Michael Perryman's [The Exoplanet Handbook](https://www.cambridge.org/de/academic/subjects/physics/computational-science-and-modelling/exoplanet-handbook-2nd-edition), Second Edition, Cambridge University Press, UK 2011/2018.


## R Packages for Astronomy

- [**astrochron**](https://cran.r-project.org/package=astrochron):
  *A Computational Tool for Astrochronology* (2024).  
  Routines for astrochronologic testing, astronomical time scale construction, and time series analysis. Also included are a range of statistical analysis and modeling routines that are relevant to time scale development and paleoclimate analysis.

- [**astrodatR**](https://cran.r-project.org/package=astrodatR):
  *Astronomical Data* (2014).  
  A collection of 19 datasets from contemporary astronomical research. They are described the textbook "Modern Statistical Methods for Astronomy with R Applications" by Feigelson and Babu (see above). These datasets can be used to exercise methodology involving: density estimation; heteroscedastic measurement errors; contingency tables; two-sample hypothesis tests; spatial point processes; nonlinear regression; mixture models; censoring and truncation; multivariate analysis; classification and clustering; inhomogeneous Poisson processes; periodic and stochastic time series analysis. 

- [**astroFns**](https://cran.r-project.org/package=astroFns):
  *Astronomy: Time and Position Functions, Misc. Utilities* (2022).  
  Miscellaneous astronomy functions, utilities, and data.

- [**cosmoFns**](https://cran.r-project.org/package=cosmoFns):
  *Functions for Cosmological Distances, Times, Luminosities, Etc.* (2022).  
  Package encapsulates standard expressions for distances, times, luminosities, and other quantities useful in observational cosmology, including molecular line observations. Currently coded for a flat universe only.

- [**celestial**](https://cran.r-project.org/package=celestial):
  *Collection of Common Astronomical Conversion Routines and Functions* (2018).  
  Contains a number of common astronomy conversion routines, particularly the HMS and degrees schemes, which can be fiddly to convert between on mass due to the textural nature of the former. It allows users to coordinate match datasets quickly. It also contains functions for various cosmological calculations.

- [**extraterrestrial**](https://cran.r-project.org/package=extraterrestrial):
  *Astrobiology Equations Estimating Extraterrestrial Life* (2020).  
  Finding life outside the planet Earth several is the ultimate goal of an astrobiologist. Using known astronomical measurements and assumptions the probability of extraterrestrial life existence could be estimated. Equations such as the Drake equation (1961) as stated in the paper of Molina "Searching for a standard Drake equation" (2019), Seager "The Drake equation revisited" (2013) and Foucher et al. "A Statistical Approach to Illustrate the Challenge of Astrobiology for Public Outreach" (2017) are included in the 'extraterrestrial' package.


- [**FITSio**](https://cran.r-project.org/package=FITSio):
  *FITS (Flexible Image Transport System) Utilities* (2021).  
  Utilities to read and write files in the 
  [FITS](https://en.wikipedia.org/wiki/FITS) (Flexible Image Transport System) format, a standard format in astronomy. Present low-level routines allow: reading, parsing, and modifying FITS headers; reading FITS images (multi-dimensional arrays); reading FITS binary and ASCII tables; and writing FITS images (multi-dimensional arrays).

- [**lira**](https://cran.r-project.org/package=lira):
  *LInear Regression in Astronomy* (2018).  
  Performs Bayesian linear regression and forecasting in astronomy. The method accounts for heteroscedastic errors in both the independent and the dependent variables, intrinsic scatters (in both variables) and scatter correlation, time evolution of slopes, normalization, scatters, Malmquist and Eddington bias, upper limits and break of linearity. The posterior distribution of the regression parameters is sampled with a Gibbs method exploiting the JAGS library.

- [**SCEPtER**](https://CRAN.R-project.org/package=SCEPtER) and
  [**SCEPtERbinary**](https://CRAN.R-project.org/package=SCEPtERbinary):
  *Stellar CharactEristics Pisa Estimation gRid* (2022).  
  A pipeline for estimating the stellar age, mass, and radius given observational effective temperature, [Fe/H], and astroseismic parameters. The results are obtained adopting a maximum likelihood technique over a grid of pre-computed stellar models, as described in "Uncertainties in grid-based estimates of stellar mass and radius" by Valle et al.  
  'SCEPtERbinary' (2013) is an extension of these ideas to binary systems.

- [**snapshot**](https://cran.r-project.org/package=snapshot):
  *Gadget N-body cosmological simulation code snapshot I/O utilities* (2013).  
  Functions for reading and writing Gadget N-body snapshots. The Gadget code is popular in astronomy for running N-body / hydrodynamical cosmological and merger simulations. To find out more about Gadget see the main distribution page at [gadget-2](https://www.mpa-garching.mpg.de/gadget/) resp.
  [gadget-4](https://wwwmpa.mpa-garching.mpg.de/gadget4/).
  [[Does 'snapshot' run correctly with Gadget-4 from 2020?]]

- [**SPADAR**](https://cran.r-project.org/package=SPADAR):
  *Spherical Projections of Astronomical Data* (2017).  
  Provides easy to use functions to create all-sky grid plots of widely used astronomical coordinate systems (equatorial, ecliptic, galactic) and scatter plots of data on any of these systems including on-the-fly system conversion. It supports any type of spherical projection to the plane defined by the 'mapproj' package.

- [**stellaR**](https://cran.r-project.org/package=stellaR):
  *Evolutionary Tracks and Isochrones from Pisa Stellar Evolution Database* (2022).  
  Manages and display[s] stellar tracks and isochrones from Pisa low-mass database. Includes tools for isochrones construction and tracks interpolation. 

- [**suncalc**](https://cran.r-project.org/package=suncalc): *Compute Sun 
  Position, Sunlight Phases, Moon Position and Lunar Phase* (2022).  
  Get sun position, sunlight phases (times for sunrise, sunset, dusk, etc.), moon position and lunar phase for the given location and time. Most calculations are based on the formulas given in 
  [Astronomy Answers](https://www.aa.quae.nl/en/reken/zonpositie.html) articles about position of the sun and the planets. See also the
  [SunCalc.net](<http://suncalc.net>) project.

- [**suntools**](https://cran.r-project.org/package=suntools):
  *Calculate Sun Position, Sunrise, Sunset, Solar Noon and Twilight* (2023).  
  Provides a set of convenient functions for calculating sun-related information, including the sun's position (elevation and azimuth), and the times of sunrise, sunset, solar noon, and twilight for any given geographical location on Earth. See "Astronomical Algorithms" by Jean Meeus (1991).


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
