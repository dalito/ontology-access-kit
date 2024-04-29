

# Slot: has_related_synonym

URI: [oio:hasRelatedSynonym](http://www.geneontology.org/formats/oboInOwl#hasRelatedSynonym)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Class](Class.md) |  |  no  |
| [TransitiveProperty](TransitiveProperty.md) | An ObjectProperty with the property of transitivity |  no  |
| [NamedIndividual](NamedIndividual.md) | An instance that has a IRI |  no  |
| [Image](Image.md) |  |  no  |
| [Agent](Agent.md) |  |  no  |
| [HasSynonyms](HasSynonyms.md) | a mixin for a class whose members can have synonyms |  no  |
| [Property](Property.md) |  |  no  |
| [ObjectProperty](ObjectProperty.md) | A property that connects two objects in logical axioms |  no  |
| [Subset](Subset.md) | A collection of terms grouped for some purpose |  no  |
| [HomoSapiens](HomoSapiens.md) | An individual human being |  no  |
| [Term](Term.md) | A NamedThing that includes classes, properties, but not ontologies |  no  |
| [AnnotationProperty](AnnotationProperty.md) | A property used in non-logical axioms |  no  |







## Properties

* Range: [LabelType](LabelType.md)

* Multivalued: True





## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/oak/ontology-metadata




## LinkML Source

<details>
```yaml
name: has_related_synonym
from_schema: https://w3id.org/oak/ontology-metadata
rank: 1000
slot_uri: oio:hasRelatedSynonym
multivalued: true
alias: has_related_synonym
domain_of:
- HasSynonyms
range: label type

```
</details>