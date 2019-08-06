---
layout: page
title: Working groups
permalink: /groups/
---

The CMSO consists of three working groups, each covering a specific topic of interest in the standardisation of the field of cell migration.

These three working groups are:

- Minimal reporting requirements working group
- Controlled vocabularies working group
- Data formats and API standards working group

Of course, there needs to be considerable interaction between the different working groups, but this split along topical lines allows the working groups to focus on a specific standardisation aspect internally.


## Minimal reporting requirements

Minimal reporting requirements are crucial in order to ensure that sufficient information is reported on a study to allow correct interpretation of the results, but also to allow reproduction of the study itself, if desired.

Minimal reporting requirements typically take the form of a document with guidelines or rules that state which information is considered essential when reporting on a given procedure, technique or analysis.

This working group has delivered increasingly refined and tested versions of 
the Minimal Information About a Cell Migration Experiment (MIACME).

The outcomes of this working group are:
- [the MIACME specifications](MIACME) that describe what is required for the reporting 
of cell migration experiments both in a narrative document as well as in machine-readable and
actionable schemas (in the form of JSON schemas for JSON-LD instances); the specifications also describe the process followed to define the guidelines in an incremental way and by engaging the cell migration community
- [a set of datasets](https://github.com/CellMigStandOrg/CMSO-datasets) that demonstrate the use
of the MIACME guidelines and their relation to the other CMSO outcomes  

### Process

The process to derive the MIACME guidelines is described in the specifications. 

One of the elements of this process was to design a community driven survey with a draft 
draft of minimal reporting guidelines. The purpose was to gain input on the quality and the
necessity of the proposed requirements to take into account during further
discussion.

The survey can be found [here](https://goo.gl/3YlAu1).

## Controlled vocabularies

A controlled vocabulary is a key element to ensure unambiguous annotation of data and results. Controlled vocabularies are designed to be both human as well as machine readable.

The goal of this working group was to examine existing controlled vocabularies (CVs) for re-use where possible and to propose the addition of terms to an existing CV where appropriate. The working group worked closely with the Minimal reporting requirements working group to select appropriate vocabularies for the annnotation of MIACME elements.


## Data formats and API standards 

Standards formats and standard software APIs are instrumental tools to ensure
that all data, results and associated metadata in a field can be readily read
and correctly interpreted by any relevant software package.

This working group focused on identifying standard formats and software libraries that could be combined and applied to the field of cell migration.

The selected components selected were:
- the existing [ISA model](http://isa-tools.org), or Investigation/Study/Assay model,  for a rich description of the experimental metadata, following the MIACME guidelines
- the existing [OME data model](http://www.openmicroscopy.org/), the Open Microscopy Environment, for the exchange of image data and metadata
- the newly developed [BioTracks specification](http://cmso.science/Tracks/) and [software library](https://github.com/cellmigstandorg/biotracks) for the cell migration analytical results.
