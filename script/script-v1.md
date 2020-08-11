# BuildTest Test Configuration for Script Schema

```txt
https://buildtesters.github.io/schemas/script/script-v1.0.schema.json
```




| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                          |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ----------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [script-v1.0.schema.json](../../out/script-v1.0.schema.json "open original schema") |

## BuildTest Test Configuration for Script Type

`object` ([BuildTest Test Configuration for Script](script-v1.md))

# BuildTest Test Configuration for Script Properties

| Property                    | Type          | Required | Nullable       | Defined by                                                                                                                                                                          |
| :-------------------------- | ------------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)               | `string`      | Required | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-type.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/type")               |
| [description](#description) | `string`      | Optional | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/description") |
| [sbatch](#sbatch)           | Not specified | Optional | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-sbatch.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/sbatch")           |
| [bsub](#bsub)               | Not specified | Optional | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-bsub.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/bsub")               |
| [env](#env)                 | Not specified | Optional | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-env.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/env")                 |
| [vars](#vars)               | Not specified | Optional | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-vars.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/vars")               |
| [executor](#executor)       | Not specified | Required | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-executor.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/executor")       |
| [shell](#shell)             | `string`      | Optional | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-shell.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/shell")             |
| [shebang](#shebang)         | `string`      | Optional | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-shebang.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/shebang")         |
| [run](#run)                 | `string`      | Required | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-run.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/run")                 |
| [status](#status)           | Not specified | Optional | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-status.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/status")           |
| [skip](#skip)               | Not specified | Optional | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-skip.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/skip")               |
| [tags](#tags)               | Not specified | Optional | cannot be null | [BuildTest Test Configuration for Script](script-v1-properties-tags.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/tags")               |

## type




`type`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-type.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/type")

### type Type

`string`

### type Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^script$
```

[try pattern](https://regexr.com/?expression=%5Escript%24 "try regular expression with regexr.com")

## description

A description for the build recipe.


`description`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/description")

### description Type

`string`

## sbatch




`sbatch`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-sbatch.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/sbatch")

### sbatch Type

unknown

## bsub




`bsub`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-bsub.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/bsub")

### bsub Type

unknown

## env




`env`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-env.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/env")

### env Type

unknown

## vars




`vars`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-vars.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/vars")

### vars Type

unknown

## executor




`executor`

-   is required
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-executor.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/executor")

### executor Type

unknown

## shell




`shell`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-shell.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/shell")

### shell Type

`string`

### shell Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^(/bin/bash|/bin/sh|sh|bash|python).*
```

[try pattern](https://regexr.com/?expression=%5E(%2Fbin%2Fbash%7C%2Fbin%2Fsh%7Csh%7Cbash%7Cpython).* "try regular expression with regexr.com")

## shebang




`shebang`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-shebang.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/shebang")

### shebang Type

`string`

## run

A script to run using the default shell.


`run`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-run.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/run")

### run Type

`string`

## status




`status`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-status.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/status")

### status Type

unknown

## skip




`skip`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-skip.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/skip")

### skip Type

unknown

## tags




`tags`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Test Configuration for Script](script-v1-properties-tags.md "https&#x3A;//buildtesters.github.io/schemas/script/script-v1.0.schema.json#/properties/tags")

### tags Type

unknown