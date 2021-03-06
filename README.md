# zyaml

[![CI](https://github.com/hemtjanst/zyaml/workflows/CI/badge.svg)](https://github.com/hemtjanst/zyaml/actions?query=workflow%3ACI)

This repository contains a YAML representation of the set of Zigbee™
specifications for the purposes of generating a Zigbee protocol stack
implementation.

> ZigBee is an IEEE 802.15.4-based specification for a suite of high-level
> communication protocols used to create personal area networks with small,
> low-power digital radios, such as for home automation, medical device
> data collection, and other low-power low-bandwidth needs, designed for
> small scale projects which need wireless connection.
>
> <cite>https://en.wikipedia.org/wiki/ZigBee</cite>

## Libraries

| Language | Repository | Auto-update on merge |
| --- | --- | -- |
| Go | [hemtjanst/zcl] | ✔️ |
| TypeScript | [hemtjanst/zcl] | ✔️ |

[hemtjanst/zcl]: https://github.com/hemtjanst/zcl

## Source material

The specification can be retrieved from the Zigbee Alliance
[Developer portal](https://zigbeealliance.org/developer_resources/?file_type%5B%5D=specification)

## Reserved names

These names are reserved for functions related to attributes and commands, 
they should not be used as a attribute/argument names:

* AddValues
* Arguments
* ArrayTypeID
* ArrayValues
* Cluster
* Description
* Direction
* Handle
* ID
* MarshalZcl
* MnfCode
* Name
* Readable
* Reportable
* Required
* SceneIndex
* SetValue
* SetValues
* String
* TypeID
* UnmarshalZcl
* Value
* Values
* Writable

## Attribution

A number of definitions were originally sourced from Dresden Elektronik's
[deconz-rest-plugin](https://github.com/dresden-elektronik/deconz-rest-plugin).
These are licensed under the [3-clause BSD License](https://github.com/dresden-elektronik/deconz-rest-plugin/blob/bb47cdbc19c257e3000fdb8475aa456830e6df94/LICENSE.txt).

Zigbee is a trademark of the Zigbee Alliance.
