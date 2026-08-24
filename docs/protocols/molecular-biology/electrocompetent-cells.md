---
title: Preparation of electrocompetent E. coli cells
tags:
  - Molecular biology
  - Bacterial culture
  - Electroporation
---

# Preparation of electrocompetent *E. coli* cells

## Purpose

Prepare concentrated, low-conductivity *E. coli* cells for electroporation by
growing cells to early log phase, keeping them cold, and performing sequential
water and glycerol washes.

## Source and scope

Adapted from the UConn Health Li Lab protocol,
[Preparation of electrocompetent cells](https://health.uconn.edu/li-lab/wp-content/uploads/sites/129/2017/06/electrocompetent_cells.pdf),
which states that it is based on Protocol 26 from *Molecular Cloning*.

The source discusses DH5α and possibly DH10B but does not define a validated
strain range. Confirm that this method is appropriate for the intended strain.

## Before starting

### Safety and training

- Follow the approved biosafety practices for the host strain and any
  introduced genetic material.
- Use suitable containment when handling live cultures and centrifuge bottles.
- Inspect and correctly balance all centrifuge vessels.
- Wear cryogenic PPE and follow local procedures when dispensing cells into
  liquid nitrogen.
- Complete training for the centrifuges, spectrophotometer, electroporator, and
  liquid-nitrogen equipment used.

!!! warning "Maintain the cold chain"
    After the culture reaches the target density, keep the cells and all wash
    solutions at **4 °C or colder**. The source identifies warming above 4 °C
    as detrimental to transformation efficiency.

### Reagents and solutions

| Item                   |       Amount needed | Preparation                             |
| ---------------------- | ------------------: | --------------------------------------- |
| LB medium              |         50 mL + 1 L | Pre-warm the 1 L portion to 37 °C       |
| Ultrapure water        |              500 mL | Sterile and ice-cold                    |
| 10% glycerol           |     At least 260 mL | Sterile and ice-cold                    |
| GYT medium             | At least several mL | Sterile and ice-cold; see formula below |
| Fresh *E. coli* colony |                   1 | From a fresh agar plate                 |

### GYT medium

| Component     | Final concentration |
| ------------- | ------------------: |
| Glycerol      |           10% (v/v) |
| Yeast extract |         0.12% (w/v) |
| Tryptone      |         0.25% (w/v) |

Pass the prepared medium through a pre-rinsed 0.22 µm filter. The source stores
it in 2.5 mL aliquots at 4 °C; the protocol owner must establish a local
expiration period.

### Equipment

- 250 mL culture flask for the overnight culture
- Two sterile 2 L baffled culture flasks
- Refrigerated centrifuge, rotor, and compatible bottles
- Refrigerated benchtop centrifuge compatible with a 50 mL tube
- Ice-water bath
- Spectrophotometer and cuvettes for OD600 measurements
- Electroporator and ice-chilled 0.2 cm-gap cuvettes
- Sterile, ice-cold 0.5 mL microcentrifuge tubes
- Liquid-nitrogen bath and approved cryogenic handling equipment

## Procedure

### Day 1 - Start the overnight culture

1. Inoculate one fresh colony into **50 mL LB medium**.
2. Incubate overnight at **37 °C with shaking at 250 rpm**.

### Day 2 - Grow cells to early log phase

1. Add **25 mL overnight culture** to each of two 2 L flasks containing
   **500 mL pre-warmed LB**.
2. Incubate at **37 °C with shaking at 300 rpm**.
3. Measure OD600 every **20 minutes**.
4. Proceed immediately when OD600 reaches **0.4**.

!!! danger "Do not overgrow"
    Do not allow OD600 to exceed **0.4**. The source reports approximately
    2.5 hours to reach this density for DH5α, but growth must be followed by
    measurement rather than elapsed time.

### Chill the culture

1. Transfer both flasks to an ice-water bath for **15-30 minutes**.
2. Swirl occasionally so the culture cools evenly.
3. Meanwhile, chill the centrifuge bottles in ice water and pre-cool the rotor
   and centrifuge chamber to **4 °C**.

### Harvest and wash

1. Divide the 1 L culture among four ice-cold 250 mL centrifuge bottles.
2. Centrifuge at **1,000 × g for 15 minutes at 4 °C**.
3. Decant the supernatant and gently resuspend the combined cell material in
   **500 mL ice-cold ultrapure water**, divided between two 250 mL bottles.
4. Centrifuge at **1,000 × g for 20 minutes at 4 °C**.
5. Decant and promptly resuspend the cell material in **250 mL ice-cold 10%
   glycerol** in one suitable bottle.

!!! warning "Pellet may detach"
    After glycerol washing, the pellet may adhere poorly. Decant carefully and
    begin resuspension as soon as centrifugation finishes.

6. Centrifuge at **1,000 × g for 20 minutes at 4 °C**.
7. Decant and resuspend the pellet in **10 mL ice-cold 10% glycerol**.
8. Transfer to a chilled 50 mL centrifuge tube.
9. Centrifuge at **1,000 × g for 20 minutes at 4 °C**.
10. Carefully decant, then remove residual liquid without disturbing the
    pellet.
11. Resuspend the pellet in **1 mL ice-cold GYT medium** by gentle swirling.
    Do not vortex.

### Adjust the cell concentration

1. Prepare a **1:100 dilution** of the cell suspension and measure OD600.
2. Estimate the undiluted cell concentration using the source conversion:

    ```text
    cells/mL ≈ OD600 of diluted sample × 100 × 2.5 × 10^8
    ```

3. Add ice-cold GYT medium to target **2 × 10^10 to 3 × 10^10 cells/mL**.

!!! note "Verify this estimate"
    The OD-to-cell-number conversion is approximate and may vary by strain,
    instrument, and growth conditions. Establish a locally validated method
    before approval.

### Check conductivity

1. Transfer **40 µL** suspension to an ice-chilled **0.2 cm-gap**
   electroporation cuvette.
2. Apply the locally validated electrical test setting and observe whether
   arcing occurs.
3. If arcing occurs, do not aliquot the preparation. The source instructs an
   additional wash with ice-cold GYT medium; the protocol owner must define
   that wash and the retest criteria.

### Aliquot and store

1. Dispense **40 µL** portions into sterile, ice-cold 0.5 mL tubes.
2. Freeze the closed tubes rapidly in a liquid-nitrogen bath using the approved
   local procedure.
3. Transfer the aliquots to the validated long-term storage temperature.

!!! warning "Storage temperature requires a decision"
    The source specifies **−70 °C**. Confirm whether the lab will retain that
    condition or validate its standard **−80 °C** storage workflow.

## Quality control

The source includes an arcing check but no direct transformation-efficiency
test. Before approval, define and validate:

| Check                            | Draft criterion                             |
| -------------------------------- | ------------------------------------------- |
| Growth phase                     | Harvested at OD600 0.4 and not above        |
| Cold chain                       | Maintained at or below 4 °C after harvest   |
| Conductivity                     | No arcing under the approved test condition |
| Cell concentration               | Estimated at 2-3 × 10^10 cells/mL           |
| Transformation efficiency        | **Not yet defined**                         |
| Sterility or contamination check | **Not yet defined**                         |
| Storage stability                | **Not yet defined**                         |

Record the strain, lot identifier, preparation date, operator, measured OD,
estimated concentration, number of aliquots, storage location, test conditions,
and all deviations.

## Troubleshooting

??? question "The culture passed OD600 0.4"
    Do not continue under this draft. Record the deviation and consult the
    protocol owner; the source treats the upper density limit as critical.

??? question "The pellet is loose after a glycerol wash"
    Keep the vessel cold and decant slowly. Do not add an improvised
    centrifugation step without approval.

??? question "The test cuvette arcs"
    Stop and retain the batch on ice. Review conductivity, residual wash
    solution, cuvette condition, and the approved electrical setting. The
    additional wash and retest procedure must be defined before this protocol
    can be approved.

<div class="protocol-meta" markdown>
|                  |              |
| ---------------- | ------------ |
| **Last updated** | 27 July 2026 |
| **Updated by**   | Chris        |
</div>
