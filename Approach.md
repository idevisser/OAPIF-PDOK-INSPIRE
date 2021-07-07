## Approach

### Approach step by step

The approach consisted of the following steps:

- astablish requirements
- organize a High5 week with stakeholders
- Choose a data set (Dutch INSPIRE adsresses)
- start communication on Github 
- report to INSPIR community
- organize presentations

###	Stakeholders

Stakeholders are:
- Geonovum as initiator and author of this document (https://www.geonovum.nl)
- PDOK (Publieke Dienstverlening op de Kaart, http://www.pdok.nl) as hosting organization for geoservices
- Kadaster (https://www.kadaster.nl) as dataprovider

### Used tools

PDOK has used self developped software based on Go and Postgres.

###	Requirements

The requirements are listed in detail in https://github.com/Geonovum/OAPIF-PDOK-INSPIRE/tree/main/requirements
Below the most relevant requirements are listed:

| nr | requirement | priority | reference | 
|----|---------|---------|------------------| 
|  1 | [OGC API Features Core](https://docs.opengeospatial.org/is/17-069r3/17-069r3.html) | 1 | [[PUB-1]] |
|  3 | [INPSIRE-MIF document: Setting up an INSPIRE Download service based on the OGC API-Features standard](https://github.com/INSPIRE-MIF/gp-ogc-api-features/blob/master/spec/oapif-inspire-download.md) | 1 | [[PUB-2]] |
|  4 | [predefined download](https://github.com/INSPIRE-MIF/gp-ogc-api-features/blob/master/spec/oapif-inspire-download.md#req-pre-defined) | 1 | [[PUB-2]] #req-pre-defined |
|  5 | [Geojson](https://github.com/INSPIRE-MIF/gp-ogc-api-features/blob/master/spec/oapif-inspire-download.md#req-oapif-json) | 1 | [[PUB-2]] #req-oapif-json |
|  6 | [bulk download](https://github.com/INSPIRE-MIF/gp-ogc-api-features/blob/master/spec/oapif-inspire-download.md#req-bulk-download | 1 | [[PUB-2]] #req-bulk-download  |
|  7 | [CRS ETRS89 and WGS84](https://github.com/INSPIRE-MIF/gp-ogc-api-features/blob/master/spec/oapif-inspire-download.md#req-crs) | 2  | [[PUB-5]] and [[PUB-2]] #req-crs |
|  8 | [INSPIRE validated GML as input](https://inspire.ec.europa.eu/validator/about/) | 3  | https://inspire.ec.europa.eu/validator/about/ |
|  9 | [Dutch API designrules](https://www.geonovum.nl/over-geonovum/actueel/rest-api-design-rules-op-pas-toe-leg-uit-lijst) | 1 | [[PUB-3]] |
|  10 | [Descibing encoding](https://github.com/INSPIRE-MIF/2017.2/blob/master/GeoJSON/geojson-encoding-rule.md#inspire-requirements-for-encoding-rules) | 1 | [[PUB-4]] |
|  11 | [filtering](https://docs.ogc.org/DRAFTS/19-079r1.html) | 2 | [[PUB-6]] |
|  12 | [metadata links](http://docs.opengeospatial.org/is/17-069r3/17-069r3.html#rec_core_fc-md-descriptions) | 1 | [[PUB-1]] #rec_core_fc-md-descriptions |


###	Relevant documentation 

Relevant documentation is shown in appendix A


