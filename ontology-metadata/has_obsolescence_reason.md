

# Slot: has_obsolescence_reason

URI: [IAO:0000231](http://purl.obolibrary.org/obo/IAO_0000231)




## Inheritance

* [obsoletion_related_property](obsoletion_related_property.md)
    * **has_obsolescence_reason**






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

* Range: [String](String.md)





## Comments

* {'RULE': 'subject must be deprecated'}

## TODOs

* restrict range

## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/oak/ontology-metadata




## LinkML Source

<details>
```yaml
name: has_obsolescence_reason
todos:
- restrict range
comments:
- '{''RULE'': ''subject must be deprecated''}'
from_schema: https://w3id.org/oak/ontology-metadata
rank: 1000
is_a: obsoletion_related_property
domain: ObsoleteAspect
slot_uri: IAO:0000231
alias: has_obsolescence_reason
domain_of:
- HasLifeCycle
range: string

```
</details>