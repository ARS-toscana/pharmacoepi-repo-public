# pharmacoepi-repo-public

This repository contains the public packages released by the Pharmacoepidemiology Unit of Agenzia regionale di sanità della Toscana.

The main package currently supported is **MDBStools**.

## MDBStools

This R package is designed to contain multiple functions meant to be included in R scripts that execute data management for Multi-DataBase Studies. The functions follow the design depicted in [Gini et al, eGEMs 2016](https://egems.academyhealth.org/articles/abstract/10.13063/2327-9214.1189/).

The functions are designed to manage data structured in a Common Data Model (CDM), according to strategies C or D depicted in [Gini et al, CPT 2020](https://ascpt.onlinelibrary.wiley.com/doi/full/10.1002/cpt.1833). 

The design and development of this package was partly supported by IMI-ConcePTION (EU/EFPIA Innovative Medicines Initiative Joint Undertaking ConcePTION grant n° 821520). Functions have been tested for use with several CDMs, and notably with the [ConcePTION CDM](https://docs.google.com/spreadsheets/d/1hc-TBOfEzRBthGP78ZWIa13C0RdhU7bK/edit#gid=413205035).

This package is going to be superseded by the [ConceptionTools](https://github.com/IMI-ConcePTION/ConceptionTools) package wrapping multiple functions of the [ConcePTION data pipeline](https://www.imi-conception.eu/wp-content/uploads/2020/10/ConcePTION-D7.5-Report-on-existing-common-data-models-and-proposals-for-ConcePTION.pdf)
* [CreateConceptSetDatasets](https://github.com/ARS-toscana/CreateConceptSetDatasets)
* [CreateSpells](https://github.com/ARS-toscana/CreateSpells)
* [MergeFilterAndCollapse](https://github.com/ARS-toscana/MergeFilterAndCollapse)
* [CreateFlowChart](https://github.com/ARS-toscana/CreateFlowChart)
* [ApplyComponentStrategy](https://github.com/ARS-toscana/ApplyComponentStrategy)
* [DescribeThisDataset](https://github.com/ARS-toscana/DescribeThisDataset)
* [CountPersonTime](https://github.com/IMI-ConcePTION/CountPersonTime)
