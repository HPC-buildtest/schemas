# buildtest configuration schema Schema

```txt
https://buildtesters.github.io/schemas/schemas/settings.schema.json
```




| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                 |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | -------------------------------------------------------------------------- |
| Can be instantiated | Yes        | Unknown status | No           | Forbidden         | Forbidden             | none                | [settings.schema.json](../out/settings.schema.json "open original schema") |

## buildtest configuration schema Type

`object` ([buildtest configuration schema](settings.md))

# buildtest configuration schema Properties

| Property                                      | Type          | Required | Nullable       | Defined by                                                                                                                                                          |
| :-------------------------------------------- | ------------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [executors](#executors)                       | `object`      | Required | cannot be null | [buildtest configuration schema](settings-properties-executors.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/properties/executors") |
| [config](#config)                             | `object`      | Required | cannot be null | [buildtest configuration schema](settings-properties-config.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/properties/config")       |
| [additionalProperties](#additionalProperties) | Not specified | Optional | cannot be null | [Untitled schema](undefined.md "undefined#undefined")                                                                                                               |

## executors

The executor section is used for declaring your executors that are responsible for running jobs. The executor section can be `local`, `lsf`, `slurm`, `ssh`. The executors are referenced in buildspec using `executor` field.


`executors`

-   is required
-   Type: `object` ([Details](settings-properties-executors.md))
-   cannot be null
-   defined in: [buildtest configuration schema](settings-properties-executors.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/properties/executors")

### executors Type

`object` ([Details](settings-properties-executors.md))

## config




`config`

-   is required
-   Type: `object` ([Details](settings-properties-config.md))
-   cannot be null
-   defined in: [buildtest configuration schema](settings-properties-config.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/properties/config")

### config Type

`object` ([Details](settings-properties-config.md))

## additionalProperties

no description

`additionalProperties`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [Untitled schema](undefined.md "undefined#undefined")

### Untitled schema Type

unknown

# buildtest configuration schema Definitions

## Definitions group modules

Reference this group by using

```json
{"$ref":"https://buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/modules"}
```

| Property        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                          |
| :-------------- | --------- | -------- | -------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [purge](#purge) | `boolean` | Optional | cannot be null | [buildtest configuration schema](settings-definitions-modules-properties-purge.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/modules/properties/purge") |
| [load](#load)   | `array`   | Optional | cannot be null | [buildtest configuration schema](settings-definitions-modules-properties-load.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/modules/properties/load")   |

### purge




`purge`

-   is optional
-   Type: `boolean`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-modules-properties-purge.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/modules/properties/purge")

#### purge Type

`boolean`

### load




`load`

-   is optional
-   Type: `string[]`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-modules-properties-load.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/modules/properties/load")

#### load Type

`string[]`

## Definitions group script

Reference this group by using

```json
{"$ref":"https://buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/script"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | ---- | -------- | -------- | :--------- |

## Definitions group local

Reference this group by using

```json
{"$ref":"https://buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/local"}
```

| Property                        | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                      |
| :------------------------------ | ------------- | -------- | -------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [description](#description)     | `string`      | Optional | cannot be null | [buildtest configuration schema](settings-definitions-local-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/local/properties/description")     |
| [shell](#shell)                 | `string`      | Required | cannot be null | [buildtest configuration schema](settings-definitions-local-properties-shell.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/local/properties/shell")                 |
| [before_script](#before_script) | Not specified | Optional | cannot be null | [buildtest configuration schema](settings-definitions-local-properties-before_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/local/properties/before_script") |
| [after_script](#after_script)   | Not specified | Optional | cannot be null | [buildtest configuration schema](settings-definitions-local-properties-after_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/local/properties/after_script")   |

### description

description field for documenting your executor


`description`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-local-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/local/properties/description")

#### description Type

`string`

### shell

Specify the shell launcher you want to use when running tests locally


`shell`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-local-properties-shell.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/local/properties/shell")

#### shell Type

`string`

#### shell Constraints

**pattern**: the string must match the following regular expression: 

```regexp
^(/bin/bash|/bin/sh|sh|bash|python).*
```

[try pattern](https://regexr.com/?expression=%5E(%2Fbin%2Fbash%7C%2Fbin%2Fsh%7Csh%7Cbash%7Cpython).* "try regular expression with regexr.com")

### before_script




`before_script`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-local-properties-before_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/local/properties/before_script")

#### before_script Type

unknown

### after_script




`after_script`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-local-properties-after_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/local/properties/after_script")

#### after_script Type

unknown

## Definitions group slurm

Reference this group by using

```json
{"$ref":"https://buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm"}
```

| Property                        | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                      |
| :------------------------------ | ------------- | -------- | -------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [description](#description)     | `string`      | Optional | cannot be null | [buildtest configuration schema](settings-definitions-slurm-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/description")     |
| [launcher](#launcher)           | `string`      | Optional | cannot be null | [buildtest configuration schema](settings-definitions-slurm-properties-launcher.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/launcher")           |
| [options](#options)             | `array`       | Optional | cannot be null | [buildtest configuration schema](settings-definitions-slurm-properties-options.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/options")             |
| [cluster](#cluster)             | `string`      | Optional | cannot be null | [buildtest configuration schema](settings-definitions-slurm-properties-cluster.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/cluster")             |
| [partition](#partition)         | `string`      | Optional | cannot be null | [buildtest configuration schema](settings-definitions-slurm-properties-partition.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/partition")         |
| [qos](#qos)                     | `string`      | Optional | cannot be null | [buildtest configuration schema](settings-definitions-slurm-properties-qos.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/qos")                     |
| [before_script](#before_script) | Not specified | Optional | cannot be null | [buildtest configuration schema](settings-definitions-slurm-properties-before_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/before_script") |
| [after_script](#after_script)   | Not specified | Optional | cannot be null | [buildtest configuration schema](settings-definitions-slurm-properties-after_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/after_script")   |

### description

description field for documenting your executor


`description`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-slurm-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/description")

#### description Type

`string`

### launcher

Specify the slurm batch scheduler to use. This overrides the default `launcher` field. This must be `sbatch`. 


`launcher`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-slurm-properties-launcher.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/launcher")

#### launcher Type

`string`

#### launcher Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | ----------- |
| `"sbatch"` |             |

### options

Specify any other options for `sbatch` used by this executor for running all jobs.


`options`

-   is optional
-   Type: `string[]`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-slurm-properties-options.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/options")

#### options Type

`string[]`

### cluster

Specify the slurm cluster you want to use `-M <cluster>`


`cluster`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-slurm-properties-cluster.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/cluster")

#### cluster Type

`string`

### partition

Specify the slurm partition you want to use `-p <partition>`


`partition`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-slurm-properties-partition.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/partition")

#### partition Type

`string`

### qos

Specify the slurm qos you want to use `-q <qos>`


`qos`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-slurm-properties-qos.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/qos")

#### qos Type

`string`

### before_script




`before_script`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-slurm-properties-before_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/before_script")

#### before_script Type

unknown

### after_script




`after_script`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-slurm-properties-after_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/slurm/properties/after_script")

#### after_script Type

unknown

## Definitions group lsf

Reference this group by using

```json
{"$ref":"https://buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf"}
```

| Property                        | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                  |
| :------------------------------ | ------------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [description](#description)     | `string`      | Optional | cannot be null | [buildtest configuration schema](settings-definitions-lsf-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/description")     |
| [launcher](#launcher)           | `string`      | Optional | cannot be null | [buildtest configuration schema](settings-definitions-lsf-properties-launcher.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/launcher")           |
| [options](#options)             | `array`       | Optional | cannot be null | [buildtest configuration schema](settings-definitions-lsf-properties-options.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/options")             |
| [queue](#queue)                 | `string`      | Optional | cannot be null | [buildtest configuration schema](settings-definitions-lsf-properties-queue.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/queue")                 |
| [before_script](#before_script) | Not specified | Optional | cannot be null | [buildtest configuration schema](settings-definitions-lsf-properties-before_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/before_script") |
| [after_script](#after_script)   | Not specified | Optional | cannot be null | [buildtest configuration schema](settings-definitions-lsf-properties-after_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/after_script")   |

### description

description field for documenting your executor


`description`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-lsf-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/description")

#### description Type

`string`

### launcher

Specify the lsf batch scheduler to use. This overrides the default `launcher` field. It must be `bsub`. 


`launcher`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-lsf-properties-launcher.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/launcher")

#### launcher Type

`string`

#### launcher Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value    | Explanation |
| :------- | ----------- |
| `"bsub"` |             |

### options

Specify any options for `bsub` for this executor when running all jobs associated to this executor


`options`

-   is optional
-   Type: `string[]`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-lsf-properties-options.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/options")

#### options Type

`string[]`

### queue

Specify the lsf queue you want to use `-q <queue>`


`queue`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-lsf-properties-queue.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/queue")

#### queue Type

`string`

### before_script




`before_script`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-lsf-properties-before_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/before_script")

#### before_script Type

unknown

### after_script




`after_script`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-lsf-properties-after_script.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/lsf/properties/after_script")

#### after_script Type

unknown

## Definitions group ssh

Reference this group by using

```json
{"$ref":"https://buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/ssh"}
```

| Property                        | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                  |
| :------------------------------ | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [description](#description)     | `string` | Optional | cannot be null | [buildtest configuration schema](settings-definitions-ssh-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/ssh/properties/description")     |
| [host](#host)                   | `string` | Required | cannot be null | [buildtest configuration schema](settings-definitions-ssh-properties-host.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/ssh/properties/host")                   |
| [user](#user)                   | `string` | Required | cannot be null | [buildtest configuration schema](settings-definitions-ssh-properties-user.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/ssh/properties/user")                   |
| [identity_file](#identity_file) | `string` | Required | cannot be null | [buildtest configuration schema](settings-definitions-ssh-properties-identity_file.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/ssh/properties/identity_file") |

### description




`description`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-ssh-properties-description.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/ssh/properties/description")

#### description Type

`string`

### host




`host`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-ssh-properties-host.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/ssh/properties/host")

#### host Type

`string`

### user




`user`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-ssh-properties-user.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/ssh/properties/user")

#### user Type

`string`

### identity_file




`identity_file`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [buildtest configuration schema](settings-definitions-ssh-properties-identity_file.md "https&#x3A;//buildtesters.github.io/schemas/schemas/settings.schema.json#/definitions/ssh/properties/identity_file")

#### identity_file Type

`string`
