

# Class: Precondition


_A pattern to be matched against an individual SSSOM mapping_





URI: [mappingrules:Precondition](https://w3id.org/oak/mapping-rules-datamodel/Precondition)




```{mermaid}
 classDiagram
    class Precondition
      Precondition : mapping_source_one_of
        
      Precondition : object_match_field_one_of
        
      Precondition : object_source_one_of
        
      Precondition : predicate_id_one_of
        
      Precondition : subject_match_field_one_of
        
      Precondition : subject_source_one_of
        
      Precondition : transformations_included_in
        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [subject_source_one_of](subject_source_one_of.md) | 0..* <br/> [String](String.md) | The source of the subject to be matched | direct |
| [object_source_one_of](object_source_one_of.md) | 0..* <br/> [String](String.md) | The source of the object to be matched | direct |
| [mapping_source_one_of](mapping_source_one_of.md) | 0..* <br/> [String](String.md) | The source of the mapping to be matched | direct |
| [subject_match_field_one_of](subject_match_field_one_of.md) | 0..* <br/> [String](String.md) | The field in the subject to be matched | direct |
| [object_match_field_one_of](object_match_field_one_of.md) | 0..* <br/> [String](String.md) | The field in the object to be matched | direct |
| [transformations_included_in](transformations_included_in.md) | 0..* <br/> [String](String.md) |  | direct |
| [predicate_id_one_of](predicate_id_one_of.md) | 0..* <br/> [String](String.md) | The predicate to be matched | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [MappingRule](MappingRule.md) | [preconditions](preconditions.md) | range | [Precondition](Precondition.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/oak/mapping-rules-datamodel





## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | mappingrules:Precondition |
| native | mappingrules:Precondition |





## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: Precondition
description: A pattern to be matched against an individual SSSOM mapping
from_schema: https://w3id.org/oak/mapping-rules-datamodel
attributes:
  subject_source_one_of:
    name: subject_source_one_of
    description: The source of the subject to be matched. Multiple values can be provided,
      it must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    domain_of:
    - Precondition
  object_source_one_of:
    name: object_source_one_of
    description: The source of the object to be matched. Multiple values can be provided,
      it must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    domain_of:
    - Precondition
  mapping_source_one_of:
    name: mapping_source_one_of
    description: The source of the mapping to be matched. Multiple values can be provided,
      it must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    domain_of:
    - Precondition
  subject_match_field_one_of:
    name: subject_match_field_one_of
    description: The field in the subject to be matched. Multiple values can be provided,
      it must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    domain_of:
    - Precondition
  object_match_field_one_of:
    name: object_match_field_one_of
    description: The field in the object to be matched. Multiple values can be provided,
      it must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    domain_of:
    - Precondition
  transformations_included_in:
    name: transformations_included_in
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    domain_of:
    - Precondition
  predicate_id_one_of:
    name: predicate_id_one_of
    description: The predicate to be matched. Multiple values can be provided, it
      must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    domain_of:
    - Precondition

```
</details>

### Induced

<details>
```yaml
name: Precondition
description: A pattern to be matched against an individual SSSOM mapping
from_schema: https://w3id.org/oak/mapping-rules-datamodel
attributes:
  subject_source_one_of:
    name: subject_source_one_of
    description: The source of the subject to be matched. Multiple values can be provided,
      it must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    alias: subject_source_one_of
    owner: Precondition
    domain_of:
    - Precondition
    range: string
  object_source_one_of:
    name: object_source_one_of
    description: The source of the object to be matched. Multiple values can be provided,
      it must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    alias: object_source_one_of
    owner: Precondition
    domain_of:
    - Precondition
    range: string
  mapping_source_one_of:
    name: mapping_source_one_of
    description: The source of the mapping to be matched. Multiple values can be provided,
      it must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    alias: mapping_source_one_of
    owner: Precondition
    domain_of:
    - Precondition
    range: string
  subject_match_field_one_of:
    name: subject_match_field_one_of
    description: The field in the subject to be matched. Multiple values can be provided,
      it must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    alias: subject_match_field_one_of
    owner: Precondition
    domain_of:
    - Precondition
    range: string
  object_match_field_one_of:
    name: object_match_field_one_of
    description: The field in the object to be matched. Multiple values can be provided,
      it must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    alias: object_match_field_one_of
    owner: Precondition
    domain_of:
    - Precondition
    range: string
  transformations_included_in:
    name: transformations_included_in
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    alias: transformations_included_in
    owner: Precondition
    domain_of:
    - Precondition
    range: string
  predicate_id_one_of:
    name: predicate_id_one_of
    description: The predicate to be matched. Multiple values can be provided, it
      must match at least one.
    from_schema: https://w3id.org/oak/mapping-rules-datamodel
    rank: 1000
    multivalued: true
    alias: predicate_id_one_of
    owner: Precondition
    domain_of:
    - Precondition
    range: string

```
</details>