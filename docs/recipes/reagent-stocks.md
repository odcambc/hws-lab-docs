---
title: Reagent stock solutions
tags:
  - Draft
  - Recipes
  - Reagents
---

# Reagent stock solutions

<div class="protocol-meta" markdown>

| | |
|---|---|
| **Status** | <span class="status draft">Needs review</span> |
| **Owner** | Unassigned |
| **Version** | 0.1 |
| **Reformatted** | 27 July 2026 |

</div>

!!! danger "Unvalidated recipes"
    Confirm chemical form, formula weight, hazards, pH, sterility requirement,
    aliquot size, storage condition, and expiration before preparation.

## DTT - 1 M

Example preparation for 20 mL:

| Component | Amount |
|---|---:|
| DTT | 3.09 g |
| 10-20 mM sodium acetate, pH 5.2 | To 20 mL |

- **Legacy sterilization:** 0.22 µm filtration
- **Legacy aliquot:** 0.5-1 mL
- **Legacy storage:** −20 °C
- **Notes:** Minimize freeze-thaw cycles, oxidation, and headspace.

## IPTG - 1 M

| Component | Amount |
|---|---:|
| IPTG | 2.4 g |
| Water | To 10 mL |

- **Legacy sterilization:** 0.22 µm filtration
- **Legacy handling:** Aliquot
- **Legacy storage:** −20 °C

## Glycerol - 10-50% v/v

Measure glycerol by volume and bring to the final volume with water. The legacy
notes also suggest gravimetric preparation using a density of **1.26 g/mL**.

Example recorded for 1 L of 50% v/v glycerol:

| Component | Amount |
|---|---:|
| Water | 500 mL |
| Glycerol | 630 g, equivalent to approximately 500 mL at the recorded density |

- **Legacy sterilization:** Autoclaving
- **Legacy storage:** Room temperature

!!! note
    Verify glycerol density at the relevant grade and temperature before using
    a mass-based preparation.

## TCEP - 0.5 M

1. Confirm whether the reagent is TCEP·HCl and use the formula weight printed
   on the bottle.
2. Dissolve in less than the final volume of water.
3. Adjust to approximately pH 7 if required by the application.
4. Bring to final volume.

- **Legacy sterilization:** 0.22 µm filtration
- **Legacy aliquot:** 0.5-1 mL
- **Legacy storage:** −20 °C
- **Notes:** Avoid repeated freeze-thaw cycles.

## L-arginine - 1 M, pH 8.5

| Component | Amount for 1 L |
|---|---:|
| L-arginine free base, formula weight 174.20 g/mol | 174.2 g |

1. Dissolve in approximately 800 mL water.
2. Adjust to pH 8.5 using the locally approved titrant and procedure.
3. Bring to 1 L.

- **Legacy sterilization:** Autoclaving
- **Legacy storage:** Room temperature

!!! warning
    Do not substitute arginine hydrochloride without recalculating the recipe.

## DNase I stock

The legacy document contains only “TBD.”

!!! question "Recipe needed"
    Define enzyme source, activity units, buffer, concentration, aliquot size,
    storage, freeze-thaw limit, and application-specific working concentration.

## Lysozyme - 10 mg/mL, fresh

| Component | Amount |
|---|---:|
| Lysozyme | 10 mg per mL final solution |
| 10 mM Tris, pH ≥8 | To final volume |

- **Legacy sterilization:** Not filtered because protein may bind the membrane
- **Legacy storage:** Prepare immediately before use

## Phosphate-buffered saline

The legacy file includes 10× and 1× formulations that require reconciliation
with the existing [PBS recipe](pbs.md).

### 10× PBS, pH 7.4 - 1 L

| Component | Legacy amount |
|---|---:|
| NaCl | 80 g |
| KCl | 2 g |
| Na₂HPO₄ | 17.8 g |
| KH₂PO₄ | 2.4 g |
| Water | To 1 L after pH adjustment |

- **Legacy sterilization:** Autoclaving
- **Legacy storage:** Room temperature

### 1× PBS, pH 7.4 - 1 L

| Component | Legacy amount |
|---|---:|
| NaCl | 8.00 g |
| KCl | 0.20 g |
| KH₂PO₄ | 0.27 g |
| Na₂HPO₄ | Depends on hydrate form |
| Water | To 1 L after pH adjustment |

The target composition recorded for 1× PBS is 137 mM NaCl, 2.7 mM KCl,
10 mM sodium phosphate, and 2 mM potassium phosphate at pH 7.4.

!!! warning "PBS discrepancy"
    The 10× and 1× legacy formulations do not identify the Na₂HPO₄ hydrate
    form, and their phosphate masses are not a simple ten-fold scaling. Resolve
    the formulation and update the dedicated PBS page before approval.

## Guanidine hydrochloride - 6 M

| Component | Amount for 1 L |
|---|---:|
| Guanidine hydrochloride | 573.18 g |

- **Legacy sterilization:** 0.22 µm filtration
- **Legacy storage:** Room temperature
- **Notes:** This is not guanidine thiocyanate. The legacy notes suggest
  warming to approximately 37 °C with mixing to redissolve precipitate.

## Imidazole - 1 M, pH 8.0

| Component | Amount for 1 L |
|---|---:|
| Imidazole | 68.08 g |

1. Dissolve in approximately 800 mL water.
2. Adjust to pH 8.0 using the locally approved titrant and procedure.
3. Bring to 1 L.

- **Legacy sterilization:** 0.22 µm filtration
- **Legacy storage:** Room temperature

## Approval checklist

- [ ] Independently verify every calculation and chemical form
- [ ] Resolve PBS formulations and hydrate states
- [ ] Define the DNase I stock
- [ ] Define storage periods and thaw limits
- [ ] Validate pH adjustment and sterilization methods
- [ ] Add preparation safety controls and acceptance criteria
- [ ] Link each stock to the protocols that consume it

## Source history

Reformatted from the reagent-stock section of `docs/recipes/reformat.txt`. The
legacy file remains as the source record pending review and archival.

