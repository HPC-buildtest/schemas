# Untitled string in buildtest configuration schema Schema

```txt
https://buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/local/properties/shell
```

Specify the shell launcher you want to use when running tests locally


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                   |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ---------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [settings.schema.json\*](../out/settings.schema.json "open original schema") |

## shell Type

`string`

## shell Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^(/bin/bash|/bin/sh|sh|bash|python).*
```

[try pattern](https://regexr.com/?expression=%5E(%2Fbin%2Fbash%7C%2Fbin%2Fsh%7Csh%7Cbash%7Cpython).* "try regular expression with regexr.com")
