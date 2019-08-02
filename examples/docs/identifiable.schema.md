---
template: reference
foo: bar
---

# Identifiable Schema

```
https://example.com/schemas/identifiable
```

This is a _very_ simple example of a JSON schema. There is only one property.

| [Abstract](../abstract.md) | Extensible | [Status](../status.md) | Identifiable | Custom Properties | Additional Properties | Defined In                                           |
| -------------------------- | ---------- | ---------------------- | ------------ | ----------------- | --------------------- | ---------------------------------------------------- |
| Can be instantiated        | No         | Experimental           | Yes          | Forbidden         | Permitted             | [identifiable.schema.json](identifiable.schema.json) |

# Identifiable Properties

| Property   | Type     | Required   | Nullable | Defined by                                 |
| ---------- | -------- | ---------- | -------- | ------------------------------------------ |
| [@id](#id) | `string` | Optional   | No       | Identifiable (this schema)                 |
| `*`        | any      | Additional | Yes      | this schema _allows_ additional properties |

## @id

A unique identifier given to every addressable thing.

`@id`

- is optional
- type: `string`
- defined in this schema

### @id Type

`string`

- format: `uri` – Uniformous Resource Identifier (according to [RFC3986](http://tools.ietf.org/html/rfc3986))

**All** of the following _requirements_ need to be fulfilled.

#### Requirement 1

- []() – `#/definitions/id`
