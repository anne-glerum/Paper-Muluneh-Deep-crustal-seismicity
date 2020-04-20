# paper-Muluneh-Deep-crustal-seismicity

This repository belongs to the paper

    Mechanism for deep crustal seismicity: 
    Insight from modeling of deformation process at the Main Ethiopian Rift
    by
    Ameha A. Muluneh, Sascha Brune, Finnigan Illsley-Kemp, Giacomo Corti, 
    Derek Keir6, Anne Glerum, Tesfaye Kidane and Jim Mori

and contains an input file and code to reproduce the computations in the paper.

Contents
--------
``aspect_plugins``

The ASPECT plugins created specifically for this paper. They should be build as shared libraries in conjunction with ASPECT 2.0.0-pre commit 585d1c3c99de259057408ea90aab5dbe963ecb40, see the supplied installation instructions. A full ASPECT branch including these plugins is available at ``https://github.com/anne-glerum/aspect/tree/paper-Muluneh-Deep-crustal-seismicity``.

``input_file.prm``

The commented ASPECT input file used to create the main computation in the paper. Please set the parameter ``Additional shared libaries`` to the library created from the supplied ASPECT plugins. The input file is also provided as Supplementary Material to the manuscript.

``ASPECT_install_configuration.txt``

The specific installation configurations for ASPECT and deal.ii as used for the paper.
