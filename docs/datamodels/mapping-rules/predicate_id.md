# Slot: predicate_id

URI: [mappingrules:predicate_id](https://w3id.org/oak/mapping-rules-datamodel/predicate_id)



<!-- no inheritance hierarchy -->




## Applicable Classes

| Name | Description |
| --- | --- |
[Postcondition](Postcondition.md) | 






## Properties

* Range: [String](String.md)







## Comments

* if the rule is invertible, then the predicate is inverted, e.g. skos broad becomes narrow

## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/oak/mapping-rules-datamodel




## LinkML Source

<details>
```yaml
name: predicate_id
comments:
- if the rule is invertible, then the predicate is inverted, e.g. skos broad becomes
  narrow
from_schema: https://w3id.org/oak/mapping-rules-datamodel
rank: 1000
alias: predicate_id
owner: Postcondition
domain_of:
- Postcondition
range: string

```
</details>