

# Slot: deprecated

URI: [owl:deprecated](http://www.w3.org/2002/07/owl#deprecated)




## Inheritance

* [obsoletion_related_property](obsoletion_related_property.md)
    * **deprecated**






## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Class](Class.md) |  |  no  |
| [TransitiveProperty](TransitiveProperty.md) | An ObjectProperty with the property of transitivity |  no  |
| [NamedIndividual](NamedIndividual.md) | An instance that has a IRI |  no  |
| [HasLifeCycle](HasLifeCycle.md) |  |  no  |
| [Image](Image.md) |  |  no  |
| [Agent](Agent.md) |  |  no  |
| [Property](Property.md) |  |  no  |
| [ObjectProperty](ObjectProperty.md) | A property that connects two objects in logical axioms |  no  |
| [Subset](Subset.md) | A collection of terms grouped for some purpose |  no  |
| [HomoSapiens](HomoSapiens.md) | An individual human being |  no  |
| [Term](Term.md) | A NamedThing that includes classes, properties, but not ontologies |  no  |
| [AnnotationProperty](AnnotationProperty.md) | A property used in non-logical axioms |  no  |







## Properties

* Range: [Boolean](Boolean.md)



## Aliases


* is obsolete



## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/oak/ontology-metadata




## LinkML Source

<details>
```yaml
name: deprecated
in_subset:
- allotrope permitted profile
- go permitted profile
- obi permitted profile
from_schema: https://w3id.org/oak/ontology-metadata
aliases:
- is obsolete
rank: 1000
is_a: obsoletion_related_property
domain: ObsoleteAspect
slot_uri: owl:deprecated
alias: deprecated
domain_of:
- HasLifeCycle
range: boolean

```
</details>