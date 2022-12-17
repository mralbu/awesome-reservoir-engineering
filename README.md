# Awesome Reservoir Engineering
> Reservoir Engineering is [awesome](awesome.md).

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![License](https://img.shields.io/github/license/softwareunderground/awesome-open-geoscience.svg)](LICENSE)

Open reservoir engineering is even more awesome, so we made a list. This list is curated from repositories that make our lives as reservoir engineers, hackers and data wranglers easier or just more awesome. In accordance with the awesome manifesto, we add awesome repositories. We are open to [contributions](contributing.md) of course, this is a community effort after all.

## Contents

- [Awesome Reservoir Engineering](#awesome-reservoir-engineering)
  - [Contents](#contents)
  - [Related Awesome](#related-awesome)
  - [Software](#software)
    - [Reservoir Simulation](#reservoir-simulation)
    - [History Matching and Uncertainty Analysis](#history-matching-and-uncertainty-analysis)
    - [Petrophysics](#petrophysics)
    - [PVT Analysis](#pvt-analysis)
    - [Rock-Fluid Interaction](#rock-fluid-interaction)
    - [Geology and Geophysics](#geology-and-geophysics)
    - [Geostatistics](#geostatistics)
    - [Geomechanics](#geomechanics)
  - [Data Repositories](#data-repositories)
  - [Tutorials and Cheat Sheets](#tutorials-and-cheat-sheets)
  - [Miscellaneous](#miscellaneous)
  - [How to Contribute](#how-to-contribute)
  - [License](#license)

## Related Awesome
- [Awesome Open Geoscience](https://github.com/softwareunderground/awesome-open-geoscience) - ![Awesome](media/icon/awesome.png) ![](media/icon/fork.png) Awesome list for open source geoscience tools   
- [Awesome Python Chemistry](https://github.com/lmmentel/awesome-python-chemistry) - ![Awesome](media/icon/awesome.png) Awesome list for chemistry open software in python

| ▲ [Top](#awesome-reservoir-engineering) |
| --- |

## Software
Awesome software projects sub-categorized by focus.
### Reservoir Simulation
- [libres](https://github.com/equinor/libres) - ![Python](media/icon/python.png) Tool for managing an ensemble of reservoir models
- [libecl](https://github.com/equinor/libecl) - ![Python](media/icon/python.png) Reading and writing Eclipse reservoir simulator files
- [MRST](https://www.sintef.no/projectweb/mrst) - ![matlab](media/icon/matlab.png) Rapid prototyping and demonstration of new simulation methods in reservoir modelling and simulation
- [DuMu<sup>x</sup>](https://dumux.org) - ![C++](media/icon/cplusplus.png) Simulator for flow and transport processes in porous media
- [Fesapi](https://github.com/F2I-Consulting/fesapi) - ![C++](media/icon/cplusplus.png) ![C++](media/icon/java.png) ![C++](media/icon/csharp.png) Reading and writing [RESQML2](https://www.energistics.org/portfolio/resqml-data-standards/) files
- [PyGRDECL](https://github.com/BinWang0213/PyGRDECL) - ![Python](media/icon/python.png) ![Paraview](media/icon/paraview.png) Visualize Eclipse/Petrel outputs Grid File (GRDECL) using Paraview(VTK)
- [TPFA-ResSim](https://github.com/patnr/TPFA-ResSim) - ![Python](media/icon/python.png) ![Matlab](media/icon/matlab.png) Toy, 2D black-oil petroleum reservoir simulator
### History Matching and Uncertainty Analysis
- [ert](https://github.com/equinor/ert) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Tool for history matching and updating using Ensemble Kalman Filters and Ensemble Smoothers.
- [pyhum](https://github.com/juliohm/HUM) - ![Python](media/icon/python.png) Probabilistic Framework for Reservoir Characterization and Real Time Updating
### Petrophysics
- [pyscal](https://github.com/equinor/pyscal) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Python module for relative permeability/SCAL support in reservoir simulation
- [lasio](https://github.com/kinverarity1/lasio/) - ![Python](media/icon/python.png) Reading and writing well data using Log ASCII Standard (LAS) files
- [Welly](https://github.com/agile-geoscience/welly) - ![Python](media/icon/python.png) Analyzing and processing well log data
- [Striplog](https://github.com/agile-geoscience/striplog) - ![Python](media/icon/python.png) Display lithological and stratigraphic logs for wells and outcrop
- [FuzzyLAS](http://fuzzylas.appspot.com/) - Web app for looking up curve mnemonics
- [dlisio](https://github.com/equinor/dlisio) - ![Equinor](media/icon/equinor.png) ![C++](media/icon/cplusplus.png) ![Python](media/icon/python.png) dlisio is an LGPL licensed library for working with well logs in Digital Log Interchange Standard (DLIS V1) 
- [porespy](https://github.com/PMEAL/porespy) - ![Python](media/icon/python.png) A set of tools for characterizing and analying 3D images of porous materials
- [porepy](https://github.com/pmgbergen/porepy) - ![Python](media/icon/python.png) Simulation Tool for Fractured and Deformable Porous Media
- [OpenPNM](https://github.com/PMEAL/OpenPNM) - ![Python](media/icon/python.png) Pore network modeling of porous media
- [drd](https://github.com/LukasMosser/digital_rocks_data) - ![Python](media/icon/python.png) Download and load digital rocks datasets
### PVT Analysis
- [neqsim](https://equinor.github.io/neqsimhome/) - ![Equinor](media/icon/equinor.png) ![Java](media/icon/java.png) ![Matlab](media/icon/matlab.png) ![Python](media/icon/python.png) Estimation of phase behaviour and properties for oil and gas fluids
- [PREOS](https://github.com/CorySimon/PREOS) - ![Python](media/icon/python.png) Computes the fugacity coefficient, compressibility, and density of a gas at a particular temperature and pressure using the Peng-Robinson EoS
- [zFactor](https://github.com/f0nzie/zFactor) - ![R](media/icon/r.png) Calculates the error measures or deviation between different correlations for gas compressibility compared to the original Standing-Katz chart
### Rock-Fluid Interaction
- [arxim](https://www.emse.fr/~moutte/arxim/) - ![Fortran](media/icon/fortran.png) Calculations of multiphase (fluid, mineral, gas) interactions
- [PhreeQC](https://www.usgs.gov/software/phreeqc-version-3) - ![C++](media/icon/cplusplus.png) Reactions in water and between water and rocks and sediments (speciation, batch-reaction, one-dimensional transport, and inverse geochemical calculations)
- [Reaktoro](https://reaktoro.org/) - ![C++](media/icon/cplusplus.png) ![Python](media/icon/python.png) Unified framework for modelling chemically reactive systems
- [GeoPyTool](https://github.com/GeoPyTool/GeoPyTool) - ![Python](media/icon/python.png) Application with geochemical plotting capabilities
- [pyrolite](https://github.com/morganjwilliams/pyrolite) - ![Python](media/icon/python.png) Geochemical transformation and visualisation
### Geology and Geophysics
- [GemPy](https://github.com/cgre-aachen/gempy) - ![Python](media/icon/python.png) 3-D structural geological modelling software with implicit modelling and support for stochastic modelling
- [pyGeoPressure](https://pygeopressure.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) Pore pressure prediction using well log data and seismic velocity data
- [mplStereonet](https://github.com/joferkington/mplstereonet) - ![Python](media/icon/python.png) Stereonets on python based on Matplotlib
- [apsg](https://github.com/ondrolexa/apsg) - ![Python](media/icon/python.png) Advanced structural geology analysis and visualisation based on Matplotlib
-  [segyio](https://github.com/equinor/segyio) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Fast Python library for SEGY files.

### Geostatistics
- [pyKriging](https://github.com/capaulson/pyKriging) - ![Python](media/icon/python.png) N-dimensional kriging
- [SGeMS](http://sgems.sourceforge.net/) - ![CUDA](media/icon/cuda.png) Stanford geostatistical modelling software
- [HPGL](https://github.com/hpgl/hpgl) - ![Python](media/icon/python.png) High perfomance geostatistics library
- [gstat](https://github.com/r-spatial/gstat/) - ![R](media/icon/r.png) Geostatistical modelling, prediction and simulation
- [PyGSLIB](https://opengeostat.github.io/pygslib/index.html) - ![Python](media/icon/python.png) Mineral resource estimations
- [GeoStats.jl](https://github.com/juliohm/GeoStats.jl) - ![Julia](media/icon/julia.png) High-performance geostatistics in Julia
- [GeostatsPy](https://github.com/GeostatsGuy/GeostatsPy) - ![Python](media/icon/python.png) GSLIB reimplimented in Python
- [GeoStat-Framework](https://github.com/GeoStat-Framework) - ![Python](media/icon/python.png) Framework for geostatistical simulations
### Geomechanics
- [Geomechanics.jl](https://github.com/scuervo91/Geomechanics.jl) - ![julia](media/icon/julia.png) Geomechanics analysis focused on the Unconventional Resources evaluation 

| ▲ [Top](#awesome-reservoir-engineering) |
| --- |

## Data Repositories
- [ANP](http://www.anp.gov.br/dados-abertos-anp) - Brazil's national oil agency open data repository.
- [Volve Dataset](https://www.equinor.com/en/how-and-why/digitalisation-in-our-dna/volve-field-data-village-download.html) - Volve field data set download
- [Unisim](https://www.unisim.cepetro.unicamp.br/benchmarks/br/) - CMG and Eclipse reservoir simulation datasets. 
- [Athabasca Oil Sands Well Dataset McMurray/Wabiskaw](https://ags.aer.ca/publications/SPE_006.html) - Well logs and stratigraphic picks for 2193 wells, including 750 with lithofacies, from Alberta, Canada
- [Digital Rocks Portal](https://www.digitalrocksportal.org/) - Data portal for fast storage and retrieval, sharing, organization and analysis of images of varied porous micro-structures

| ▲ [Top](#awesome-reservoir-engineering) |
| --- |

## Tutorials and Cheat Sheets

- [Petroleum Science Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed96019e/1323808738753/Cheatsheet_petroleum.pdf) - Cheat Sheet for Petroleum Science
- [Basic Geoscience Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed95fff0/1295033898443/Cheatsheet_basic.pdf) - Cheat Sheet for Basic Geoscience
- [Geophysics Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d70e4b0d158ed9603f5/1350658645407/Cheatsheet_geophysics.pdf) - Cheat Sheet for Geophysics
- [Rock Physics Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed960042/1374593568367/Cheatsheet_Rock_Physics.pdf) -  Cheat Sheet for Rock Physics
- [History Matching tutorial](https://github.com/patricknraanes/HistoryMatching) - ![Python](media/icon/python.png)
  Tutorial on history matching with ensembles.
  Interactive, using Jupyter notebooks.
  Can be run in the cloud (no installation required).

| ▲ [Top](#awesome-reservoir-engineering) |
| --- |

## Miscellaneous

- [Software Underground Slack](https://softwareunderground.org/) - ![slack](media/icon/slack.png) Community connecting geo\computing researchers
- [gio](https://github.com/agile-geoscience/gio) - ![Python](media/icon/python.png) Geoscience file input and output functions for less-than standard data formats
- [Comparison of free geophysics software](https://en.wikipedia.org/wiki/Comparison_of_free_geophysics_software) - List of geophysics software on Wikipedia

| ▲ [Top](#awesome-reservoir-engineering) |
| --- |

## How to Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

| ▲ [Top](#awesome-reservoir-engineering) |
| --- |

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, all contributors have waived all copyright and
related or neighboring rights to this work.
