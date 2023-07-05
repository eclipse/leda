---
title: Sensor2

date: 2023-06-05T12:39:06.851860
no_list: true
---


| | |
|---|---|
| Full qualified VSS Path: | `Vehicle.OBD.O2WR.Sensor2` |
| Description: | Wide range/band oxygen sensors (PID 24 - 2B and PID 34 - 3B) |

## Navigation

```mermaid
flowchart LR



    Vehicle-->OBD

    OBD-->O2WR

    O2WR-->Sensor2

```


## Digital Auto: Playground

[playground.digital.auto](http://digital.auto) provides an in-browser, rapid prototyping environment utilizing the COVESA APIs for connected vehicles. 

| Vehicle Model | Direct link to Vehicle Signal |
|---|---|
| ACME Car (EV) v0.1 | [Vehicle.OBD.O2WR.Sensor2](https://digitalauto.netlify.app/model/STLWzk1WyqVVLbfymb4f/cvi/list/Vehicle.OBD.O2WR.Sensor2/) |


## Signal Information




The vehicle signal `Vehicle.OBD.O2WR.Sensor2` is a **Branch**.





## UUID

Each vehicle signal is identified by a [Universally Unique Identifier (UUID](https://en.wikipedia.org/wiki/Universally_unique_identifier))

The UUID for `Vehicle.OBD.O2WR.Sensor2` is `079f9960f75d5f399df7ff86fcea8f0c`

## Children

This vehicle signal is a branch or structure and thus has sub-pages:

- [Vehicle.OBD.O2WR.Sensor2.Current](current/) (PID 3x (byte CD) - Current for wide range/band oxygen sensor)
- [Vehicle.OBD.O2WR.Sensor2.Lambda](lambda/) (PID 2x (byte AB) and PID 3x (byte AB) - Lambda for wide range/band oxygen sensor)
- [Vehicle.OBD.O2WR.Sensor2.Voltage](voltage/) (PID 2x (byte CD) - Voltage for wide range/band oxygen sensor)


## Feedback

Do you think this Vehicle Signal specification needs enhancement? Do you want to discuss with experts? Try the following ressources to get in touch with the VSS community:

| | |
|---|---|
| Enhancement request | [Create COVESA GitHub Issue](https://github.com/COVESA/vehicle_signal_specification/issues/new?body=Please+describe+your+feedback&title=Signal+feedback+Vehicle.OBD.O2WR.Sensor2) |
| Join COVESA | [www.covesa.global](https://www.covesa.global/join?src=sidebar) |
| Discuss VSS on Slack | [w3cauto.slack.com](http://w3cauto.slack.com/) |
| VSS Data Experts on Google Groups | [covesa.global data-expert-group](https://groups.google.com/a/covesa.global/g/data-expert-group) |

## About VSS

The [Vehicle Signal Specification](https://covesa.github.io/vehicle_signal_specification/) (VSS)
is an initiative by COVESA to define a syntax and a catalog for vehicle signals.
The source code and releases can be found in the [VSS github repository](https://github.com/COVESA/vehicle_signal_specification).
