# sdcTools
sdcTools is an organization dedicated to tools for Statistical Disclosure Control.

Events, new releases and other news about sdcTools will be announced on [sdctools.github.io/UserSupport](https://sdctools.github.io/UserSupport). At that website you can also [apply for membership of the User Group on SDCTools](https://sdctools.github.io/UserSupport/ContactForm).

A dedicated repository [UserSupport](https://github.com/sdcTools/UserSupport) is available for interaction between users and developers. Using its [issues](https://github.com/sdcTools/UserSupport/issues) mechanism, questions can be asked and (possible) bugs can be reported.

## Overview of tools
### &tau;-ARGUS
&tau;-ARGUS is a tool to apply Statistical Disclosure Control to tabulated (aggregated) data. It can apply several sensitivity rules to find unsafe table cells and it can apply several methods to protect tabulated data containing unsafe cells. 
It was designed to be used via a GUI but can also be called commandline using a batch-file (script-file).

The repositories related to &tau;-ARGUS are:
- [tauargus](https://github.com/sdcTools/tauargus): Java Graphical User Interface
- [arguslibrary](https://github.com/sdcTools/arguslibrary): Library with general utilities for the argus twins (&mu;- and &tau;-ARGUS)
- [libtauargus](https://github.com/sdcTools/libtauargus): Library with general calculations to construct tabulated data
- [CSP](https://github.com/sdcTools/CSP): Library with Cell Suppression following Fischetti-Salazar approach
- [CRP](https://github.com/sdcTools/CRP): Library with Controlled Rounding following Fischetti-Salazar approach
- [tauhitas](https://github.com/sdcTools/tauhitas): Library with Modular and Optimal approaches, using CSP
- [taurounder](https://github.com/sdcTools/taurounder): Library to connect CRP to Java interface
- [hypercube](https://github.com/sdcTools/hypercube): Hypercube approach to cell suppression, a.k.a. GHMIter
- [network](https://github.com/sdcTools/network): Network approach to cell suppression 
- [CTA](https://github.com/sdcTools/CTA): Controlled Tabular Adjustment
- [intervalle](https://github.com/sdcTools/intervalle): Method to calculate feasibility intervals

### &mu;-ARGUS
&mu;-ARGUS is a tool to apply Statistical Disclosure Control to microdata (individual level data). It can apply several sensitivity rules to find unsafe records and it can apply several methods to protect microdata containing unsafe records. 
It was designed to be used via a GUI.

The repositories related to &mu;-ARGUS are:
- [muargus](https://github.com/sdcTools/muargus): Java Graphical User Interface
- [arguslibrary](https://github.com/sdcTools/arguslibrary): Library with general utilities for the argus twins (&mu;- and &tau;-ARGUS)
- [libmuargus](https://github.com/sdcTools/libmuargus): Library with calculations underlying &mu;-ARGUS, including methods for categorical variables
- [libnumericalmu](https://github.com/sdcTools/libnumericalmu): Library with methods for numerical variables

### sdcTable
[sdcTable](https://github.com/sdcTools/sdcTable) is an R-package to apply Statistical Disclosure Control to tabulated (aggregated) data. It can apply several sensitivity rules to find unsafe table cells and it can apply several methods to protect tabulated data containing unsafe cells. 
It can also call &tau;-ARGUS to apply protection methods in the background, thereby giving the possibility to integrated &tau;-ARGUS in an R-environment. sdcTable can also be fount on [CRAN](https://cran.r-project.org/web/packages/sdcTable).

### sdcMicro
[sdcMicro](https://github.com/sdcTools/sdcMicro) is an R-package to apply Statistical Disclosure Control to microdata (individual level data). It can apply several sensitivity rules to find unsafe records and it can apply several methods to protect microdata containing unsafe records. The package
includes a R-shiny GUI. sdcMicro can also be found on [CRAN](https://cran.r-project.org/web/packages/sdcMicro).

### rtauargus
[rtauargus](https://github.com/sdcTools/rtauargus) provides an R interface for &tau;-ARGUS. It allows to integrate &tau;-ARGUS into a production chain in R.

### cellKey
[cellKey](https://github.com/sdcTools/cellKey) is an R-package to apply Cell Key Method to tabulated (aggregated) data. cellKey can also be found on [CRAN](https://cran.r-project.org/web/packages/cellKey).

### sdcSpatial
[sdcSpatial](https://github.com/sdcTools/sdcSpatial) is an R-package to apply Statistical Disclosure Control methods to spatial data. In particular it offers methods for creating spatial density (raster) maps from (unprotected) point data. 

### AI-SDC 
[AI-SDC](https://github.com/AI-SDC) is the ACRO-family of tools for disclosure control of statistical outputs and of machine learning models

