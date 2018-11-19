# Bio-Track-Schema
DBIx::Class schema for pathogens tracking databases

[![Build Status](https://travis-ci.org/sanger-pathogens/seroba.svg?branch=master)](https://travis-ci.org/sanger-pathogens/Bio-Track-Schema)   
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-brightgreen.svg)](https://github.com/sanger-pathogens/Bio-Track-Schema/blob/master/software-license)   

## Contents
  * [Introduction](#introduction)
  * [Installation](#installation)
    * [From Source](#from-source)
    * [Running the tests](#running-the-tests)
  * [Usage](#usage)
  * [License](#license)
  * [Feedback/Issues](#feedbackissues)

## Introduction
Dumps the two HICF schemata as DBIC models.

## Installation
Details for installing Bio-Track-Schema are provided below. If you encounter an issue when installing Bio-Track-Schema please contact your local system administrator. If you encounter a bug please log it [here](https://github.com/sanger-pathogens/Bio-Track-Schema/issues) or email us at path-help@sanger.ac.uk.

### From Source
Clone the repository:   
   
`git clone https://github.com/sanger-pathogens/Bio-Track-Schema.git`   
   
Move into the directory and install all dependencies using [DistZilla](http://dzil.org/):   
  
```
cd Bio-Track-Schema
dzil authordeps --missing | cpanm
dzil listdeps --missing | cpanm
```
  
Run the tests:   
  
`dzil test`   
If the tests pass, install Bio-Track-Schema:   
  
`dzil install`   

### Running the tests
The test can be run with dzil from the top level directory:  
  
`dzil test`  

## Usage
```
build_schemata.pl
```
## License
Bio-Track-Schema is free software, licensed under [GPLv3](https://github.com/sanger-pathogens/Bio-Track-Schema/blob/master/software-license).

## Feedback/Issues
Please report any issues to the [issues page](https://github.com/sanger-pathogens/Bio-Track-Schema/issues) or email path-help@sanger.ac.uk.
