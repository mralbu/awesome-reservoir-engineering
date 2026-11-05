# Awesome Reservoir Engineering
> Reservoir Engineering is [awesome](awesome.md).

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License](https://img.shields.io/github/license/mralbu/awesome-reservoir-engineering.svg)](LICENSE)

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
    - [Data Formats and I/O](#data-formats-and-io)
    - [Production Engineering and Well Performance](#production-engineering-and-well-performance)
    - [CO2 Storage and Geothermal](#co2-storage-and-geothermal)
    - [Machine Learning and Surrogate Models](#machine-learning-and-surrogate-models)
    - [Visualization and Workflows](#visualization-and-workflows)
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
- [MRST](https://www.sintef.no/projectweb/mrst) - ![matlab](media/icon/matlab.png) Rapid prototyping and demonstration of new simulation methods in reservoir modelling and simulation
- [DuMu<sup>x</sup>](https://dumux.org) - ![C++](media/icon/cplusplus.png) Simulator for flow and transport processes in porous media
- [MiniRes](https://github.com/patnr/MiniRes) - ![Python](media/icon/python.png) ![Matlab](media/icon/matlab.png) Toy, 2D black-oil petroleum reservoir simulator
- [porepy](https://github.com/pmgbergen/porepy) - ![Python](media/icon/python.png) Simulation Tool for Fractured and Deformable Porous Media
- [OPM Flow](https://github.com/OPM/opm-simulators) - ![C++](media/icon/cplusplus.png) Fully implicit black-oil reservoir simulator from the Open Porous Media initiative, reads Eclipse-format input
- [open-DARTS](https://gitlab.com/open-darts/open-darts) - ![C++](media/icon/cplusplus.png) ![Python](media/icon/python.png) Delft Advanced Research Terra Simulator for flow and transport in reservoirs, geothermal and CO2 storage
- [JutulDarcy.jl](https://github.com/sintefmath/JutulDarcy.jl) - ![Julia](media/icon/julia.png) Differentiable multiphase, multicomponent reservoir simulator in Julia
- [GEOS](https://github.com/GEOS-DEV/GEOS) - ![C++](media/icon/cplusplus.png) Multiphysics simulation framework for subsurface flow, geomechanics and CO2 storage
- [ResInsight](https://github.com/OPM/ResInsight) - ![C++](media/icon/cplusplus.png) 3D viewer and post-processing of reservoir models and simulation results
- [MOOSE](https://github.com/idaholab/moose) - ![C++](media/icon/cplusplus.png) Multiphysics finite-element framework whose porous flow module covers multiphase, thermal and geomechanical reservoir problems
- [PFLOTRAN](https://www.pflotran.org/) - Massively parallel Fortran simulator for subsurface flow and reactive transport
- [GeoChemFoam](https://github.com/GeoChemFoam/GeoChemFoam) - ![C++](media/icon/cplusplus.png) OpenFOAM-based pore-scale simulator for multiphase reactive flow and transport
- [dfnWorks](https://github.com/lanl/dfnWorks) - ![C++](media/icon/cplusplus.png) ![Python](media/icon/python.png) Generation of three-dimensional discrete fracture networks and simulation of flow and transport through them
### History Matching and Uncertainty Analysis
- [ert](https://github.com/equinor/ert) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Tool for history matching and updating using Ensemble Kalman Filters and Ensemble Smoothers, with Everest for ensemble-based well planning and production optimization (`pip install ert[everest]`)
- [iterative_ensemble_smoother](https://github.com/equinor/iterative_ensemble_smoother) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Standalone ES-MDA and subspace iterative ensemble smoother (SIES) algorithms for data assimilation
- [DAPPER](https://github.com/nansencenter/DAPPER) - ![Python](media/icon/python.png) Benchmarking of data assimilation methods such as EnKF variants, iterative ensemble smoothers and particle filters
- [pyhum](https://github.com/juliohm/HUM) - ![Python](media/icon/python.png) Probabilistic Framework for Reservoir Characterization and Real Time Updating
### Petrophysics
- [pyscal](https://github.com/equinor/pyscal) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Python module for relative permeability/SCAL support in reservoir simulation
- [Welly](https://github.com/agilescientific/welly) - ![Python](media/icon/python.png) Analyzing and processing well log data
- [Striplog](https://github.com/agilescientific/striplog) - ![Python](media/icon/python.png) Display lithological and stratigraphic logs for wells and outcrop
- [porespy](https://github.com/PMEAL/porespy) - ![Python](media/icon/python.png) A set of tools for characterizing and analyzing 3D images of porous materials
- [OpenPNM](https://github.com/PMEAL/OpenPNM) - ![Python](media/icon/python.png) Pore network modeling of porous media
- [drd](https://github.com/LukasMosser/digital_rocks_data) - ![Python](media/icon/python.png) Download and load digital rocks datasets
- [Core2Relperm](https://github.com/sede-open/Core2Relperm) - ![Shell](media/icon/shell.png) ![Python](media/icon/python.png) Core2Relperm project for inverse modelling of core flooding experiments
- [pydmd](https://github.com/cspurin/DMD-flow-in-porous-media) - ![Python](media/icon/python.png) Dynamic Mode Decomposition for Analyzing Dynamics in Multi-phase Flow in Porous Media
- [RockIR](https://github.com/sede-open/RockIR) - ![Shell](media/icon/shell.png) ![Python](media/icon/python.png) Rock Image Retrieval for rock samples
### PVT Analysis
- [neqsim](https://equinor.github.io/neqsimhome/) - ![Equinor](media/icon/equinor.png) ![Java](media/icon/java.png) ![Matlab](media/icon/matlab.png) ![Python](media/icon/python.png) Estimation of phase behaviour and properties for oil and gas fluids
- [PREOS](https://github.com/CorySimon/PREOS) - ![Python](media/icon/python.png) Computes the fugacity coefficient, compressibility, and density of a gas at a particular temperature and pressure using the Peng-Robinson EoS
- [zFactor](https://github.com/f0nzie/zFactor) - ![R](media/icon/r.png) Calculates the error measures or deviation between different correlations for gas compressibility compared to the original Standing-Katz chart
### Rock-Fluid Interaction
- [PhreeQC](https://www.usgs.gov/software/phreeqc-version-3) - ![C++](media/icon/cplusplus.png) Reactions in water and between water and rocks and sediments (speciation, batch-reaction, one-dimensional transport, and inverse geochemical calculations)
- [Reaktoro](https://reaktoro.org/) - ![C++](media/icon/cplusplus.png) ![Python](media/icon/python.png) Unified framework for modelling chemically reactive systems
- [GeoPyTool](https://github.com/GeoPyTool/GeoPyTool) - ![Python](media/icon/python.png) Application with geochemical plotting capabilities
- [pyrolite](https://github.com/morganjwilliams/pyrolite) - ![Python](media/icon/python.png) Geochemical transformation and visualisation
### Geology and Geophysics
- [GemPy](https://github.com/gempy-project/gempy) - ![Python](media/icon/python.png) 3-D structural geological modelling software with implicit modelling and support for stochastic modelling
- [pyGeoPressure](https://pygeopressure.readthedocs.io/en/latest/) - ![Python](media/icon/python.png) Pore pressure prediction using well log data and seismic velocity data
- [mplStereonet](https://github.com/joferkington/mplstereonet) - ![Python](media/icon/python.png) Stereonets on python based on Matplotlib
- [apsg](https://github.com/ondrolexa/apsg) - ![Python](media/icon/python.png) Advanced structural geology analysis and visualisation based on Matplotlib
### Geostatistics
- [pyKriging](https://github.com/capaulson/pyKriging) - ![Python](media/icon/python.png) N-dimensional kriging
- [SGeMS](http://sgems.sourceforge.net/) - ![C++](media/icon/cplusplus.png) Stanford geostatistical modelling software
- [HPGL](https://github.com/hpgl/hpgl) - ![Python](media/icon/python.png) High performance geostatistics library
- [gstat](https://github.com/r-spatial/gstat/) - ![R](media/icon/r.png) Geostatistical modelling, prediction and simulation
- [PyGSLIB](https://opengeostat.github.io/pygslib/index.html) - ![Python](media/icon/python.png) Mineral resource estimations
- [GeoStats.jl](https://github.com/JuliaEarth/GeoStats.jl) - ![Julia](media/icon/julia.png) High-performance geostatistics in Julia
- [GeostatsPy](https://github.com/GeostatsGuy/GeostatsPy) - ![Python](media/icon/python.png) GSLIB reimplemented in Python
- [GeoStat-Framework](https://github.com/GeoStat-Framework) - ![Python](media/icon/python.png) Framework for geostatistical simulations
### Geomechanics
- [Geomechanics.jl](https://github.com/scuervo91/Geomechanics.jl) - ![julia](media/icon/julia.png) Geomechanics analysis focused on the Unconventional Resources evaluation
### Data Formats and I/O
- [resdata](https://github.com/equinor/resdata) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Reading and writing Eclipse reservoir simulator files (formerly libecl)
- [Fesapi](https://github.com/F2I-Consulting/fesapi) - ![C++](media/icon/cplusplus.png) ![Java](media/icon/java.png) ![C#](media/icon/csharp.png) Reading and writing [RESQML2](https://www.energistics.org/resqml-data-standards) files
- [PyGRDECL](https://github.com/BinWang0213/PyGRDECL) - ![Python](media/icon/python.png) ![Paraview](media/icon/paraview.png) Visualize Eclipse/Petrel outputs Grid File (GRDECL) using Paraview(VTK)
- [lasio](https://github.com/kinverarity1/lasio/) - ![Python](media/icon/python.png) Reading and writing well data using Log ASCII Standard (LAS) files
- [dlisio](https://github.com/equinor/dlisio) - ![Equinor](media/icon/equinor.png) ![C++](media/icon/cplusplus.png) ![Python](media/icon/python.png) dlisio is an LGPL licensed library for working with well logs in Digital Log Interchange Standard (DLIS V1)
- [segyio](https://github.com/equinor/segyio) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Fast Python library for SEGY files
- [gio](https://github.com/softwareunderground/gio) - ![Python](media/icon/python.png) Geoscience file input and output functions for less-than standard data formats
- [xtgeo](https://github.com/equinor/xtgeo) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Subsurface surfaces, cubes, wells, grids and points with import/export for common formats
- [res2df](https://github.com/equinor/res2df) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Pandas DataFrame access to Eclipse input and output files
- [GeoEnergyIO.jl](https://github.com/sintefmath/GeoEnergyIO.jl) - ![Julia](media/icon/julia.png) Parsers and processing for Eclipse-format input decks and other geoenergy data files
- [pycopm](https://github.com/cssr-tools/pycopm) - ![Python](media/icon/python.png) Creation of OPM Flow models from existing input decks with grid refinement, coarsening and submodel extraction
- [plopm](https://github.com/cssr-tools/plopm) - ![Python](media/icon/python.png) Quick generation of PNGs, GIFs and VTKs from OPM Flow type models
### Production Engineering and Well Performance
- [petbox-dca](https://github.com/petbox-dev/dca) - ![Python](media/icon/python.png) Decline curve models including Modified and Transient Hyperbolic, Duong and Power-Law Exponential, plus secondary-phase GOR/CGR and WOR/WGR functions
- [pyResToolbox](https://github.com/mwburgoyne/pyResToolbox) - ![Python](media/icon/python.png) Reservoir engineering utilities for oil and gas PVT, black-oil table generation, material balance, IPR and VLP
- [pyreservoir](https://github.com/yohanesnuwara/pyreservoir) - ![Python](media/icon/python.png) Reservoir engineering calculations including well test analysis, material balance and decline curves (CC BY-NC-ND license)
### CO2 Storage and Geothermal
- [pyopmspe11](https://github.com/OPM/pyopmspe11) - ![Python](media/icon/python.png) Reproducible OPM Flow setups for the SPE11 CO2 storage comparative solution project
- [pyopmnearwell](https://github.com/cssr-tools/pyopmnearwell) - ![Python](media/icon/python.png) Near-well dynamics simulation using OPM Flow
- [expreccs](https://github.com/cssr-tools/expreccs) - ![Python](media/icon/python.png) Coupled regional and site reservoir simulation for CO2 storage using OPM Flow
- [Fimbul.jl](https://github.com/sintefmath/Fimbul.jl) - ![Julia](media/icon/julia.png) Geothermal reservoir and thermal energy storage simulation built on JutulDarcy.jl
- [Waiwera](https://github.com/waiwera/waiwera) - Parallel open-source geothermal flow simulator written in Fortran
- [GEOPHIRES-X](https://github.com/NatLabRockies/GEOPHIRES-X) - ![Python](media/icon/python.png) NREL's geothermal techno-economic simulator
### Machine Learning and Surrogate Models
- [U-FNO](https://github.com/gegewen/ufno) - ![Python](media/icon/python.png) Enhanced Fourier neural operator for fast multiphase flow prediction in CO2 storage
- [PhysicsNeMo](https://github.com/NVIDIA/physicsnemo) - ![Python](media/icon/python.png) NVIDIA's physics-ML framework (formerly Modulus) for neural operators and physics-informed surrogate models
### Visualization and Workflows
- [webviz](https://github.com/equinor/webviz) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Visualization of ensembles of subsurface models including seismic, reservoir grids and wells
- [webviz-subsurface](https://github.com/equinor/webviz-subsurface) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Webviz-config plugins for subsurface data
- [fmu-tools](https://github.com/equinor/fmu-tools) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Pre- and post-processing tools for Fast Model Update (FMU) workflows
- [subscript](https://github.com/equinor/subscript) - ![Equinor](media/icon/equinor.png) ![Python](media/icon/python.png) Collection of subsurface reservoir modelling scripts
- [PyVista](https://github.com/pyvista/pyvista) - ![Python](media/icon/python.png) 3D visualization and mesh analysis based on VTK

| ▲ [Top](#awesome-reservoir-engineering) |
| --- |

## Data Repositories
- [ANP](https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos) - Brazil's national oil agency open data repository
- [Volve Dataset](https://www.equinor.com/how-and-why/digitalisation-in-our-dna/volve-field-data-village-download) - Volve field data set download
- [Unisim](https://www.unisim.cepetro.unicamp.br/benchmarks/br/) - CMG and Eclipse reservoir simulation datasets
- [Athabasca Oil Sands Well Dataset McMurray/Wabiskaw](https://ags.aer.ca/publication/spe-006) - Well logs and stratigraphic picks for 2193 wells, including 750 with lithofacies, from Alberta, Canada
- [Digital Porous Media Portal](https://digitalporousmedia.org/) - Data portal (formerly Digital Rocks Portal) for fast storage and retrieval, sharing, organization and analysis of images of varied porous micro-structures
- [OPM Data](https://github.com/OPM/opm-data) - Norne field model and SPE benchmark decks (SPE1, 3, 5, 9, 10) in Eclipse format
- [SPE Comparative Solution Projects](https://www.spe.org/en/csp/) - Benchmark problems and datasets for reservoir simulation, including SPE10
- [Egg Model](https://data.4tu.nl/articles/dataset/The_Egg_Model_-_data_files/12707642) - Ensemble of 101 synthetic channelized reservoir models for waterflooding optimization and history matching studies
- [SPE11 Results](https://doi.org/10.18419/DARUS-4750) - Submitted results from the 11th SPE Comparative Solution Project on geological CO2 storage
- [Pore-Scale CO2-Water Benchmark](https://arxiv.org/abs/2503.17592) - 624 heterogeneous 2D pore-scale CO2 injection simulations for machine learning benchmarking

| ▲ [Top](#awesome-reservoir-engineering) |
| --- |

## Tutorials and Cheat Sheets

- [Petroleum Science Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed96019e/1323808738753/Cheatsheet_petroleum.pdf) - Cheat Sheet for Petroleum Science
- [Basic Geoscience Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed95fff0/1295033898443/Cheatsheet_basic.pdf) - Cheat Sheet for Basic Geoscience
- [Geophysics Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d70e4b0d158ed9603f5/1350658645407/Cheatsheet_geophysics.pdf) - Cheat Sheet for Geophysics
- [Rock Physics Cheat Sheet](https://static.squarespace.com/static/549dcda5e4b0a47d0ae1db1e/54a06d6ee4b0d158ed95f696/54a06d6fe4b0d158ed960042/1374593568367/Cheatsheet_Rock_Physics.pdf) -  Cheat Sheet for Rock Physics
- [History Matching tutorial](https://github.com/patnr/HistoryMatching) - ![Python](media/icon/python.png) Interactive Jupyter tutorial on ensemble history matching; runs in the cloud with no installation
- [DA-tutorials](https://github.com/nansencenter/DA-tutorials) - ![Python](media/icon/python.png) Jupyter tutorials on data assimilation and the Ensemble Kalman Filter
- [Python Numerical Demos](https://github.com/GeostatsGuy/PythonNumericalDemos) - ![Python](media/icon/python.png) Well-documented Python demonstrations for spatial data analytics, geostatistics and machine learning
- [Data Science Interactive Python](https://github.com/GeostatsGuy/DataScienceInteractivePython) - ![Python](media/icon/python.png) Interactive Python dashboards for learning data science and geostatistics

| ▲ [Top](#awesome-reservoir-engineering) |
| --- |

## Miscellaneous

- [Software Underground Slack](https://softwareunderground.org/) - ![slack](media/icon/slack.png) Community connecting geocomputing researchers

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
