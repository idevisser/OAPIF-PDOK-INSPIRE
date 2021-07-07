## Results

### Resulting findings

The following findings were encountered during the High5 session: 
1. GML as output is difficult and would not be realistic in the time available for this research. One could also discuss if it is realy useful, because it is not in line with the aim of OGI API Feautures: easy to use for developers.
2. Complex GML as input needs a flattening of the data. This is needed for the software that publishes the features. It can only work with simple features, with one value per attribute and without relations to other objects. This often not the case with the more complex INSPIRE models.
3. PDOK preferes flattened data as input in geopackages, so the dataprividers have to do this flattening by themself.
4. In the case of the Dutch addresses the choice has finaly been made, not to use the harmonized GML, but the AS-Is-data, because in this harmonized GML file, the addresses don't contain the actual address, but links to sub elements via the componants tag. As a result of this choice the Inspire-ID is missing, because that was no part of the AS-Is data.
5. Much time is needed for the mapping to json. This was one of the reasons for using addresses, because for this them, this work was already done: https://github.com/INSPIRE-MIF/2017.2/blob/master/GeoJSON/ads
6. We need a centralized defineing of json schema's for all the INSPIRE feature types, otherwise member states will all do this in their own way and we will never reach the goal of INSPIRE to be able to do cross boarder mapping.
7. The HIGH5 session has given a lot of insight for PDOK for future implementations of INSPIRE OAPIF for their dataproviders
8. The dataprovider (Kadaster) was happy with the overview the collection request gave
9. We could consider leaving out the empty fields, or use an option not to show them
10. ..


### Resulting services

The resulting OGC API Feature service can be found here:

The root: 
https://api.pdok.nl/geonovum/oaf/v1_0/

The collections:
https://api.pdok.nl/geonovum/oaf/v1_0/collections?f=html

<figure id="Figuur_1">
<img src="media/collections.jpg" alt="">
<figcaption>Result from collection request.</figcaption>
</figure>

The items:
https://api.pdok.nl/geonovum/oaf/v1_0/collections/addresses/items?f=html

### Posible improvements
The following improvements could still be made after the high5 seesion:

1. implementation of ETRS89 as CRS
2. adding the INSPIRE ID
3. give a result for https://api.pdok.nl/geonovum/oaf/v1_0/collections/addresses/queryables?f=html
4. implement filters other than bbox and items
5. metadata of the service and link to the service in the metadata of the dataset
6. ..


### Resulting documentation

A presentation in Dutch on the first results of the High5 can be found here: https://github.com/Geonovum/OAPIF-PDOK-INSPIRE/tree/main/docs/2021-06-25-OAPIF-PDOK-INSPIRE-High5_0.2.pptx
