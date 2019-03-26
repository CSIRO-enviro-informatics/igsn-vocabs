# igsn-vocabs
IGSN vocabs translated from XML codelists into SKOS vocabularies.

The XML codelists referenced are in GitHub:

* <https://github.com/IGSN/metadata/tree/master/description/include>


## Vocabularies
There is a single vocabulary (a single skos:ConceptScheme) per RDF (turtle) file in the top-level of this repository. The vocabularies are:

* [Access Type](access.ttl)
* [Collection Type](collection.ttl)
* [Contributor Type](contributor.ttl)
* [Feature Type](feature.ttl)
* [Geometry Type](geometry.ttl)
* [Identifier Type](identifier.ttl)
* [Material Type](material.ttl)
* [Method Type](method.ttl)
* [Registration Type](registration.ttl)
* [Resource Type](resource.ttl)
* [Sample Type](sample.ttl)
* [SRID Type](srid.ttl)


## Changes
### Unknowns
The only significant content change between these individual vocabularies and the original (see below) is the addition of *unknown* terms
to each list except Registration Type. This is to allow use of these vocabs where a term must be selected but where the value is unknown.

The [OGC nill types](http://www.opengis.net/def/nil/OGC/0/) -> *unknown* is used for "unknown" in all cases excpet for those list that already had an unknown value, such as *Sample Type* which already had [theSpecimenTypeIsUnknown](http://vocabulary.odm2.org/specimentype/theSpecimenTypeIsUnknown/).


## Supporting material
Some supporting information is contained in the [extras/](extras/) folder, such as a copy of the original Geoscience Australia SKOS version of these vocabularies.


## Rights and License
The contents of these vocabularies are licensed for use under the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by/4.0/). See the [license deed](LICENSE) all details.


## Contacts
*author*:  
**Nicholas Car**  
CSIRO Land & Water, Environmental Informatics Group  
<nicholas.car@csiro.au>
