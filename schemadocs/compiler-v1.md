# compiler schema version 1.0 Schema

```txt
https://buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json
```

The compiler schema is of `type: compiler` in sub-schema which is used for compiling and running programs


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                           |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [compiler-v1.0.schema.json](../out/compiler-v1.0.schema.json "open original schema") |

## compiler schema version 1.0 Type

`object` ([compiler schema version 1.0](compiler-v1.md))

# compiler schema version 1.0 Properties

| Property                    | Type      | Required | Nullable       | Defined by                                                                                                                                                                   |
| :-------------------------- | --------- | -------- | -------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)               | `string`  | Required | cannot be null | [compiler schema version 1.0](compiler-v1-properties-type.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/type")               |
| [description](#description) | `string`  | Optional | cannot be null | [compiler schema version 1.0](compiler-v1-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/description") |
| [module](#module)           | `array`   | Optional | cannot be null | [compiler schema version 1.0](compiler-v1-properties-module.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/module")           |
| [executor](#executor)       | `string`  | Required | cannot be null | [compiler schema version 1.0](compiler-v1-properties-executor.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/executor")       |
| [sbatch](#sbatch)           | `array`   | Optional | cannot be null | [compiler schema version 1.0](global-definitions-sbatch.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/sbatch")               |
| [bsub](#bsub)               | `array`   | Optional | cannot be null | [compiler schema version 1.0](global-definitions-bsub.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/bsub")                   |
| [env](#env)                 | `object`  | Optional | cannot be null | [compiler schema version 1.0](global-definitions-env.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/env")                     |
| [vars](#vars)               | `object`  | Optional | cannot be null | [compiler schema version 1.0](global-definitions-env.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/vars")                    |
| [status](#status)           | `object`  | Optional | cannot be null | [compiler schema version 1.0](global-definitions-status.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/status")               |
| [skip](#skip)               | `boolean` | Optional | cannot be null | [compiler schema version 1.0](compiler-v1-properties-skip.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/skip")               |
| [tags](#tags)               | `array`   | Optional | cannot be null | [compiler schema version 1.0](global-definitions-tags.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/tags")                   |
| [pre_build](#pre_build)     | `string`  | Optional | cannot be null | [compiler schema version 1.0](compiler-v1-properties-pre_build.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/pre_build")     |
| [post_build](#post_build)   | `string`  | Optional | cannot be null | [compiler schema version 1.0](compiler-v1-properties-post_build.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/post_build")   |
| [build](#build)             | `object`  | Required | cannot be null | [compiler schema version 1.0](compiler-v1-properties-build.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/build")             |
| [pre_run](#pre_run)         | `string`  | Optional | cannot be null | [compiler schema version 1.0](compiler-v1-properties-pre_run.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/pre_run")         |
| [post_run](#post_run)       | `string`  | Optional | cannot be null | [compiler schema version 1.0](compiler-v1-properties-post_run.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/post_run")       |
| [run](#run)                 | `object`  | Optional | cannot be null | [compiler schema version 1.0](compiler-v1-properties-run.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/run")                 |

## type

Select schema type to use when validating buildspec. This must be of set to `compiler`


`type`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [compiler schema version 1.0](compiler-v1-properties-type.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/type")

### type Type

`string`

### type Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^compiler$
```

[try pattern](https://regexr.com/?expression=%5Ecompiler%24 "try regular expression with regexr.com")

## description

The `description` field is used to document what the test is doing


`description`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [compiler schema version 1.0](compiler-v1-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/description")

### description Type

`string`

### description Constraints

**maximum length**: the maximum number of characters for this string is: `80`

## module

A list of modules to load into test script


`module`

-   is optional
-   Type: `string[]`
-   cannot be null
-   defined in: [compiler schema version 1.0](compiler-v1-properties-module.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/module")

### module Type

`string[]`

## executor

Select one of the executor name defined in your configuration file (`config.yml`). Every buildspec must have an executor which is responsible for running job. 


`executor`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [compiler schema version 1.0](compiler-v1-properties-executor.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/executor")

### executor Type

`string`

## sbatch

This field is used for specifying #SBATCH options in test script. buildtest will insert #SBATCH in front of each value


`sbatch`

-   is optional
-   Type: `string[]`
-   cannot be null
-   defined in: [compiler schema version 1.0](global-definitions-sbatch.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/sbatch")

### sbatch Type

`string[]`

## bsub

This field is used for specifying #BSUB options in test script. buildtest will insert #BSUB in front of each value


`bsub`

-   is optional
-   Type: `string[]`
-   cannot be null
-   defined in: [compiler schema version 1.0](global-definitions-bsub.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/bsub")

### bsub Type

`string[]`

## env

One or more key value pairs for an environment (key=value)


`env`

-   is optional
-   Type: `object` ([Details](global-definitions-env.md))
-   cannot be null
-   defined in: [compiler schema version 1.0](global-definitions-env.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/env")

### env Type

`object` ([Details](global-definitions-env.md))

### env Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

## vars

One or more key value pairs for an environment (key=value)


`vars`

-   is optional
-   Type: `object` ([Details](global-definitions-env.md))
-   cannot be null
-   defined in: [compiler schema version 1.0](global-definitions-env.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/vars")

### vars Type

`object` ([Details](global-definitions-env.md))

### vars Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

## status

The status section describes how buildtest detects PASS/FAIL on test. By default returncode 0 is a PASS and anything else is a FAIL, however buildtest can support other types of PASS/FAIL conditions.


`status`

-   is optional
-   Type: `object` ([Details](global-definitions-status.md))
-   cannot be null
-   defined in: [compiler schema version 1.0](global-definitions-status.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/status")

### status Type

`object` ([Details](global-definitions-status.md))

## skip

The `skip` is a boolean field that can be used to skip tests during builds. By default buildtest will build and run all tests in your buildspec file, if `skip: True` is set it will skip the buildspec.


`skip`

-   is optional
-   Type: `boolean`
-   cannot be null
-   defined in: [compiler schema version 1.0](compiler-v1-properties-skip.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/skip")

### skip Type

`boolean`

## tags

Classify tests using a tag name, this can be used for categorizing test and building tests using `--tags` option


`tags`

-   is optional
-   Type: `string[]`
-   cannot be null
-   defined in: [compiler schema version 1.0](global-definitions-tags.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/tags")

### tags Type

`string[]`

### tags Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

## pre_build

Run commands before building program


`pre_build`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [compiler schema version 1.0](compiler-v1-properties-pre_build.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/pre_build")

### pre_build Type

`string`

## post_build

Run commands after building program


`post_build`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [compiler schema version 1.0](compiler-v1-properties-post_build.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/post_build")

### post_build Type

`string`

## build

The `build` section is used for compiling a single program, this section specifies fields for setting C, C++, Fortran compiler and flags including CPP flags and linker flags


`build`

-   is required
-   Type: `object` ([Details](compiler-v1-properties-build.md))
-   cannot be null
-   defined in: [compiler schema version 1.0](compiler-v1-properties-build.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/build")

### build Type

`object` ([Details](compiler-v1-properties-build.md))

## pre_run

Run commands before running program


`pre_run`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [compiler schema version 1.0](compiler-v1-properties-pre_run.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/pre_run")

### pre_run Type

`string`

## post_run

Run commands after running program


`post_run`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [compiler schema version 1.0](compiler-v1-properties-post_run.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/post_run")

### post_run Type

`string`

## run

The `run` section is used for specifying launch configuration of executable


`run`

-   is optional
-   Type: `object` ([Details](compiler-v1-properties-run.md))
-   cannot be null
-   defined in: [compiler schema version 1.0](compiler-v1-properties-run.md "https&#x3A;//buildtesters.github.io/schemas/schemas/compiler-v1.0.schema.json#/properties/run")

### run Type

`object` ([Details](compiler-v1-properties-run.md))
