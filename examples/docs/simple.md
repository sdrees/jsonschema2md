# Simple Schema

```txt
https://example.com/schemas/simple
```

This is a _very_ simple example of a JSON schema. There is only one property.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                           |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [simple.schema.json](../generated-schemas/simple.schema.json "open original schema") |

## Simple Type

`object` ([Simple](simple.md))

# Simple Properties

| Property  | Type     | Required | Nullable       | Defined by                                                                                                                                              |
| :-------- | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [id](#id) | `string` | Optional | cannot be null | [Simple](complex-properties-refnestedobj-properties-refobj-properties-simple-properties-id.md "https&#x3A;//example.com/schemas/simple#/properties/id") |

## id

A unique identifier given to every addressable thing.


`id`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [Simple](complex-properties-refnestedobj-properties-refobj-properties-simple-properties-id.md "https&#x3A;//example.com/schemas/simple#/properties/id")

### id Type

`string`

### id Constraints

**URI**: the string must be a URI, according to [RFC 3986](https://tools.ietf.org/html/rfc4291 "check the specification")
