---
title: Data Access
layout: page
nav_order: 3
---

# Data Access

The data can be access in multiple ways. The data are open, published under [Creative Commons Attribution 4.0 International license (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

## Query the SPARQL Endpoint

A public SPARQL endpoint is available at [w3id.org/hacid/cs/sparql](https://w3id.org/hacid/cs/sparql).
It can be queried both programmaticaly and via browser using the user interface available at the same URL.

You can start by checking the [example queries](example-queries).

## Navigate as Linked Data

All the URIs used in the knowledge graph can be dereferenced, either programmaticaly or via browser, in order to get information on that resource (namely, all triples having such resource as subject or object). This allows to navigate the knowledge graph going from one resource to another.

Example resource URIs:
- [air_temperature (CF variable)](https://w3id.org/hacid/data/cs/variable/cf/air_temperature);
- [tasmax (MIP variable)](https://w3id.org/hacid/data/cs/variable/mip/tasmax);
- [WSDI (Warm Spell Duration Indicator)](https://w3id.org/hacid/data/cs/climdex/index/WSDI);
- [HadCM3 (global climate model maintained by the MetOffice, UK)](https://w3id.org/hacid/data/cs/model/HadCM3);
- [CMIP5 global simulation using the model HadCM3 for the RCP4.5 scenario (realization 1)](https://keng.istc.cnr.it/hacid-cs-kg/id/simulation/cmip5.HadCM3.rcp45.r1i1p1.html);
- [CORDEX regional downscaling for south-america considering the RCP8.5 scenario, using the model CanESM2 for the global simulation and the model WRF341I for downscaling](https://w3id.org/hacid/data/cs/simulation/cordex.SAM-44.CanESM2.rcp85.WRF341I.v2.r1i1p1).

## Download the Dumps

At the DOI [10.6084/m9.figshare.29066711](https://dx.doi.org/10.6084/m9.figshare.29066711), snapshots of the entire knowledge graph will be periodically published.
