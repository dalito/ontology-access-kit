

# Slot: non_deprecated_object_property_count


_Number of non-deprecated (non-obsoleted) object properties in the ontology or subset_



URI: [summary_statistics:non_deprecated_object_property_count](https://w3id.org/oaklib/summary_statistics.non_deprecated_object_property_count)




## Inheritance

* [count_statistic](count_statistic.md)
    * **non_deprecated_object_property_count**






## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UngroupedStatistics](UngroupedStatistics.md) | A summary statistics report object |  no  |







## Properties

* Range: [Integer](Integer.md)





## Identifier and Mapping Information





### Annotations

| property | value |
| --- | --- |
| filter | ObjectProperty, NotDeprecated |



### Schema Source


* from schema: https://w3id.org/oak/summary_statistics




## LinkML Source

<details>
```yaml
name: non_deprecated_object_property_count
annotations:
  filter:
    tag: filter
    value: ObjectProperty, NotDeprecated
description: Number of non-deprecated (non-obsoleted) object properties in the ontology
  or subset
from_schema: https://w3id.org/oak/summary_statistics
rank: 1000
is_a: count_statistic
alias: non_deprecated_object_property_count
owner: UngroupedStatistics
domain_of:
- UngroupedStatistics
slot_group: property_statistic_group
range: integer

```
</details>