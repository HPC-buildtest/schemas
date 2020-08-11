# BuildTest Schema for compiler Schema

```txt
https://buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json
```




| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                              |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | --------------------------------------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [compiler-v1.0.schema.json](../../out/compiler-v1.0.schema.json "open original schema") |

## BuildTest Schema for compiler Type

`object` ([BuildTest Schema for compiler](compiler-v1.md))

# BuildTest Schema for compiler Properties

| Property                    | Type          | Required | Nullable       | Defined by                                                                                                                                                                      |
| :-------------------------- | ------------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [type](#type)               | `string`      | Required | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-type.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/type")               |
| [description](#description) | `string`      | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/description") |
| [module](#module)           | `array`       | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-module.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/module")           |
| [executor](#executor)       | Not specified | Required | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-executor.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/executor")       |
| [sbatch](#sbatch)           | Not specified | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-sbatch.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/sbatch")           |
| [bsub](#bsub)               | Not specified | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-bsub.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/bsub")               |
| [env](#env)                 | Not specified | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-env.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/env")                 |
| [vars](#vars)               | Not specified | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-vars.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/vars")               |
| [status](#status)           | Not specified | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-status.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/status")           |
| [skip](#skip)               | Not specified | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-skip.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/skip")               |
| [tags](#tags)               | Not specified | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-tags.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/tags")               |
| [pre_build](#pre_build)     | `string`      | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-pre_build.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/pre_build")     |
| [post_build](#post_build)   | `string`      | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-post_build.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/post_build")   |
| [build](#build)             | `object`      | Required | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-build.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/build")             |
| [pre_run](#pre_run)         | `string`      | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-pre_run.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/pre_run")         |
| [post_run](#post_run)       | `string`      | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-post_run.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/post_run")       |
| [run](#run)                 | `object`      | Optional | cannot be null | [BuildTest Schema for compiler](compiler-v1-properties-run.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/run")                 |

## type




`type`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-type.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/type")

### type Type

`string`

### type Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^compiler$
```

[try pattern](https://regexr.com/?expression=%5Ecompiler%24 "try regular expression with regexr.com")

## description




`description`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/description")

### description Type

`string`

## module




`module`

-   is optional
-   Type: `string[]`
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-module.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/module")

### module Type

`string[]`

## executor




`executor`

-   is required
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-executor.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/executor")

### executor Type

unknown

## sbatch




`sbatch`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-sbatch.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/sbatch")

### sbatch Type

unknown

## bsub




`bsub`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-bsub.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/bsub")

### bsub Type

unknown

## env




`env`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-env.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/env")

### env Type

unknown

## vars




`vars`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-vars.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/vars")

### vars Type

unknown

## status




`status`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-status.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/status")

### status Type

unknown

## skip




`skip`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-skip.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/skip")

### skip Type

unknown

## tags




`tags`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-tags.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/tags")

### tags Type

unknown

## pre_build

Run commands before building program


`pre_build`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-pre_build.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/pre_build")

### pre_build Type

`string`

## post_build

Run commands after building program


`post_build`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-post_build.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/post_build")

### post_build Type

`string`

## build




`build`

-   is required
-   Type: `object` ([Details](compiler-v1-properties-build.md))
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-build.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/build")

### build Type

`object` ([Details](compiler-v1-properties-build.md))

## pre_run

Run commands before running program


`pre_run`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-pre_run.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/pre_run")

### pre_run Type

`string`

## post_run

Run commands after running program


`post_run`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-post_run.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/post_run")

### post_run Type

`string`

## run




`run`

-   is optional
-   Type: `object` ([Details](compiler-v1-properties-run.md))
-   cannot be null
-   defined in: [BuildTest Schema for compiler](compiler-v1-properties-run.md "https&#x3A;//buildtesters.github.io/schemas/compiler/compiler-v1.0.schema.json#/properties/run")

### run Type

`object` ([Details](compiler-v1-properties-run.md))
