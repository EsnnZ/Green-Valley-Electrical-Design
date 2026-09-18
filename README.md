# Green Valley Mining Site Office and Workshop Electrical Distribution Design

This is a self-directed electrical distribution design for a conceptual WA mining office and workshop. The purpose is to demonstrate my understanding of electrical distribution design and power system analysis in WA's mining context. Topics cover HV/LV topology, load analysis, cable sizing, power factory studies, etc..


## Project Objective

The objective of the project is to develop a electrical distribution design and demonstrate the application of:

- Australian electrical standards
- Electrical load and maximum-demand analysis
- LV cable selection and voltage-drop assessment
- Power system modelling
- Load-flow and short-circuit studies
- Protection coordination



## System Architecture

The preliminary distribution arrangement is:

```text
33 kV Supply
    │
33/11 kV Transformer
    │
11 kV Distribution Feeder
    │
RMU
    │
11/0.415 kV Transformer
    │
415 V Main Switchboard
    ├── Office DB
    ├── Workshop DB
    └── Spare / Future Feeder
```


## Major Equipment

* 33/11 kV transformer
* 11 kV distribution feeder
* Ring Main Unit (RMU)
* 11/0.415 kV transformer
* 415 V Main Switchboard (MSB)
* Office Distribution Board
* Workshop Distribution Board


## Current Progress

### Completed

* Preliminary electrical topology and single-line model
* Equipment and load schedule development
* Maximum demand analysis based on AS/NZS 3000

### In Progress

* LV cable sizing
* AS/NZS 3008 application
* Voltage-drop assessment

### Planned

* Load flow verification in power factory
* Short-circuit analysis
* Motor-starting analysis
* Preliminary protection coordination


## Site / Building Basis

The current design basis assumes:

* **Office:** 12 m × 6 m modular building, approximately 72 m²
* **Workshop:** 15 m × 18.3 m, approximately 275 m²
* **Office occupancy:** 8 persons
* **Main LV distribution:** 415/230 V
* **Distribution arrangement:** Office and workshop supplied from a common 415 V MSB

These assumptions are used as the basis for load estimation and preliminary electrical design, will be refined as the project develops.
## Tools

The project currently uses:

* DIgSILENT Power Factory
* Excel
* AutoCAD for SLD development
* Australian electrical standards and guidance documents