

# Slot: definition

URI: [IAO:0000115](http://purl.obolibrary.org/obo/IAO_0000115)




## Inheritance

* [core_property](core_property.md)
    * **definition**






## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Class](Class.md) |  |  yes  |
| [TransitiveProperty](TransitiveProperty.md) | An ObjectProperty with the property of transitivity |  no  |
| [NamedIndividual](NamedIndividual.md) | An instance that has a IRI |  no  |
| [Image](Image.md) |  |  no  |
| [HasMinimalMetadata](HasMinimalMetadata.md) | Absolute minimum metadata model |  no  |
| [Agent](Agent.md) |  |  no  |
| [Property](Property.md) |  |  yes  |
| [ObjectProperty](ObjectProperty.md) | A property that connects two objects in logical axioms |  no  |
| [Subset](Subset.md) | A collection of terms grouped for some purpose |  no  |
| [HomoSapiens](HomoSapiens.md) | An individual human being |  no  |
| [Term](Term.md) | A NamedThing that includes classes, properties, but not ontologies |  no  |
| [AnnotationProperty](AnnotationProperty.md) | A property used in non-logical axioms |  no  |







## Properties

* Range: [NarrativeText](NarrativeText.md)

* Multivalued: True





## Comments

* SHOULD be in Aristotelian (genus-differentia) form

## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/oak/ontology-metadata




## LinkML Source

<details>
```yaml
name: definition
comments:
- SHOULD be in Aristotelian (genus-differentia) form
in_subset:
- allotrope required profile
- go required profile
- obi required profile
from_schema: https://w3id.org/oak/ontology-metadata
exact_mappings:
- skos:definition
rank: 1000
is_a: core_property
slot_uri: IAO:0000115
multivalued: true
alias: definition
domain_of:
- HasMinimalMetadata
range: narrative text

```
</details>