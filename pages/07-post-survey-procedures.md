---
layout: home
permalink: /post-survey-procedures
title: "Post Survey Procedures"
excerpt: "<br>"
image:
  feature: /banners/banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=3 %}

## Sample curation


1. Lodge all specimens in an internationally recognised and routinely maintained specimen collection (e.g. museum) for curation and public accessibility _[Recommended]_.
35. If all specimens are unable to be lodged at a museum due to lack of resources or need for destructive analyses (e.g. biochemical analyses), voucher specimens must be lodged (i.e. at least one animal per OTU). 


## Data release	 

All data should be publicly released, unless circumstances require otherwise (e.g. confidentiality clause or embargo for commercial work). Even in situations when data cannot be shared, the metadata and deployment information should be made available (Steps 1-2 below). Poor scientific data management and lack of data sharing has been shown to hamper scientific progress (Stocks et al. 2016).

Traditionally, data related to biological specimens have been delivered as presence-only taxonomic identifications. These are often managed by individual museum scientists or curators and subsequently harvested by the Atlas of Living Australia (ALA). ALA does not yet include absences or information related to sampling effort, thus reducing the applicability of such databases to monitoring purposes. 

OBIS is using the data structure described in the project called OBIS-ENV-DATA that allows the linking of species data to other related information (e.g. environmental data, images, sampling effort) (De Pooter et al. 2017). It now has the capacity to store absence records and sampling effort, and is working to include this information in data downloads.

In the meantime, the steps listed below will ensure appropriate and timely release of both metadata and data:



1. Create a metadata record describing the data collection. Provide as much detail as possible on the collection/deployment (either directly in the metadata record itself, or in the form of attached field sheets as .csv, .txt or similar). This should include sampling locations and dates, equipment used, level of sorting applied, etc. All collection/deployment information must be QC-d before inclusion.
2. Publish metadata record(s) to the [Australian Ocean Data Network (AODN) catalogue](http://catalogue.aodn.org.au/geonetwork/srv/eng/main.home) as soon as possible after metadata has been QC-d. This can be done in one of two ways:
    1. If metadata from your agency is regularly harvested by the AODN, follow agency-specific protocols for metadata and data release. 
    2. Otherwise, metadata records can be created and submitted via the [AODN Data Submission Tool](https://metadataentry.aodn.org.au/submit). Note that this tool requires user registration, but this is free and immediate. 

    This step provides immediate documentation of the methods and location of the collection of biological material. This stage may also include links to field reports or data sheets.

3. Produce a technical or post-survey report documenting the purpose of the survey, survey design, sampling locations, sampling equipment specifications, and any challenges or limitations encountered (Appendix C). Provide links to this report in all associated metadata records _[Recommended]_
4. Complete the species identifications and associated abundance or biomass for targeted groups identified. This can take quite some time, depending on sample size and available resources. It is not unusual for taxonomic identifications to lag years behind survey completion, but this should not delay publication of initial metadata and deployment information. Care must be taken to ensure consistent nomenclature is used and documented for undescribed or unnamed species (e.g. defined Operational Taxonomic Units, OTUs). Ideally photographic catalogues of OTUs are established such that subsequent surveys may use consistent OTU classification, thereby ensuring comparability of data between surveys.
5. QC the data. This includes checking for spelling errors, missing data, consistent nomenclature and use of OTUs, and confirmation that outliers are not data entry errors (e.g. 100 individuals really were collected, not just 10). 
6. Attach or link the full data spreadsheet (including absences and abundances/biomass) to the metadata record previously created and published to the AODN. This will ensure public discoverability and accessibility of the complete data, including absences.

  To then publish data to OBIS, inform OBIS Australia (OBISAU) using the contact details and information on [http://www.obis.org.au](http://www.obis.org.au).


  OBISAU will download the data from AODN or any other site and apply the following procedures.

*   OBISAU provides a taxa matching service using WoRMS web services and will validate the dataset as best as possible.
*   The data is tested for any temporal or spatial outliers.
*   Any observed parameters (biotic and abiotic) are matched where possible to vocabularies maintained by AODN and BODC.
*   Metadata is authored from any existing metadata or publications.
*   Finally the datasets are published via the OBIS Australia data node[ http://ogc-act.csiro.au/ipt/](http://ogc-act.csiro.au/ipt/)

OBISAU has the option to publish the data at the same time directly to GBIF, and it has developed a service to inform ALA that a new dataset is available to be harvested for inclusion into ALA.

