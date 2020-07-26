# pharmacoepi-repo-public

This repository contains the public packages released by the Pharmacoepidemiology Unit of Agenzia regionale di sanità della Toscana.

The main package currently supported is **MDBSTools**.

## MDBSTools

This R package is designed to contain multiple functions meant to be included in R scripts that execute data management for Multi-DataBase Studies. The functions follow the design depicted in [Gini et al, eGEMs 2016](https://egems.academyhealth.org/articles/abstract/10.13063/2327-9214.1189/).

The functions are designed to manage data structured in a Common Data Model (CDM), according to strategies C or D depicted in [Gini et al, CPT 2020](https://ascpt.onlinelibrary.wiley.com/doi/full/10.1002/cpt.1833). 

The design and development of this package was partly supported by IMI-ConcePTION (EU/EFPIA Innovative Medicines Initiative Joint Undertaking ConcePTION grant n° 821520). Functions have been tested for use with several CDMs, and notably with the [ConcePTION CDM](https://docs.google.com/spreadsheets/d/1hc-TBOfEzRBthGP78ZWIa13C0RdhU7bK/edit#gid=413205035).

Functions currently released are listed below. Full documentation is contained in the package.

- **CreateConceptSetDatasets** inspects a set of input tables af data and creates a group of datasets, each corresponding to a concept set. Each dataset contains the records of the input tables that match the corresponding concept set and is named out of it

- **MergeFilterAndCollapse** performs the merge between a dataset with one row per unit of observation and a dataset with multiple rows while filtering by a condition. Furthermore it is possibile to collapse and compute summary statistics across strata of a categorical variable.

