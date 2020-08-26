# BioNetGen

Rule-based modeling framework
[![Build Status](https://travis-ci.org/RuleWorld/bionetgen.svg?branch=master)](https://travis-ci.org/RuleWorld/bionetgen)
[![Build status](https://ci.appveyor.com/api/projects/status/f7klreiao20ylwon?svg=true)](https://ci.appveyor.com/project/jczech/bionetgen)

## Overview

BioNetGen is software for the specification and simulation of rule-based models
of biochemical systems, including signal transduction, metabolic, and genetic
regulatory networks. The BioNetGen language has recently been extended to
include explicit representation of compartments. A recent review of methods for
rule-based modeling is available in L. A. Chylek et al. (2013) Wiley
Interdiscip. Rev. Syst. Biol. Med., 6, 13–36.

BioNetGen is presently a mixture of Perl, C++, and Python. Network generation
is currently implemented in Perl, the network simulator is C++, and a new
SBML-to-BNGL translator is implemented in Python. In addition, a new language
parser is currently being developed in ANTLR.

## Installation of Distribution 

Please note that this is the command line interface to BioNetGen and if you are 
new to using BioNetGen you are probably looking for the graphical user interface, 
[RuleBender](https://github.com/RuleWorld/rulebender). For more information please 
visit [bionetgen.org](https://bionetgen.org). 

Most users should simply download BioNetGen from the [releases page](https://github.com/RuleWorld/bionetgen/releases) 
and get the appropriate distribution for their OS. To install BioNetGen, unzip the
BioNetGen distribution file, e.g.  BioNetGen-2.3-MacOSX.tar.gz, in the directory 
where you would like BioNetGen installed. 

## Download Latest Test Builds

These builds are the from the head of master and are not guaranteed to be
stable. Use at your own risk.

* [Linux](https://github.com/RuleWorld/bionetgen/releases/download/BioNetGen-2.4.0%2Bwin-shared-libs/BioNetGen-2.4.0+win-shared-libs-Linux.tgz)
* [OSX](https://github.com/RuleWorld/bionetgen/releases/download/BioNetGen-2.4.0%2Bwin-shared-libs/BioNetGen-2.4.0+win-shared-libs-OSX.tgz)
* [Windows x64](https://github.com/RuleWorld/bionetgen/releases/download/BioNetGen-2.4.0%2Bwin-shared-libs/BioNetGen-2.4.0+win-shared-libs-Win.zip)

## Compilation from Source

Please see [compilation instructions here](https://github.com/RuleWorld/bionetgen/blob/master/compilation_instructions.md)

## BioNetGen History and Support

The BioNetGen software package was initially developed by the Cell Signaling
Team at Los Alamos National Laboratory. The current development team is based
in the Department of Computational and Systems Biology at the University of
Pittsburgh School of Medicine, with contributions from collaborators at the
Theoretical Division and Center for Nonlinear Studies at Los Alamos National
Laboratory, the Departments of Biology and Computer Science at the University
of New Mexico, the Center for Cell Analysis and Modeling at the University of
Connecticut Health Center, and the Department of Biological Chemistry at the
Johns Hopkins University School of Medicine.

BioNetGen development is currently supported under the auspices of the Center
for Multiscale Modeling of Biological Systems (MMBioS), a collaboration between
the University of Pittsburgh, the Pittsburgh Supercomputing Center, Carnegie
Mellon University, and the Salk Institute (NIH grant P41GM103712). BioNetGen
has been supported by NIH grant GM076570 and work has been performed under DOE
contract DE-AC52-06NA25396. Additional support for BioNetGen has been provided
by NIH grants GM085273, AI35997, and CA109552, NSF grant 0829788, the Arizona
Biomedical Research Commission, and the Department of Computational Biology at
the University of Pittsburgh School of Medicine.

## Distributions

The latest BioNetGen distributions, release notes, installation guides, 
tutorials, etc. are available at http://bionetgen.org.

RuleBender, a Java-based graphical front end for BioNetGen, is also available at
http://bionetgen.org. RuleBender is supported on Linux, Mac OS/X, and Windows
platforms. A compatible version of BioNetGen is included in the RuleBender
distribution. If you are not sure if your version of BNG is compatible with
RuleBender, please use the version distributed with RuleBender.

## Contact Us

Email the developers at bionetgen.help@gmail.com

## Troubleshooting

If you see the message `ABORT: Could not find executable run_network`, try
setting the environment variable "BNGPATH" to the root directory of your 
BioNetGen installation. Under bash-like shells, this is done by typing:
`export BNGPATH=<bngpath>`, where <bngpath> is the root directory of BNG.
