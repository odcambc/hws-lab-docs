---
title: Autoinduction media
tags:
  - Draft
  - Recipes
  - Media
---

# Autoinduction media

<div class="protocol-meta" markdown>

| | |
|---|---|
| **Status** | <span class="status draft">Needs review</span> |
| **Owner** | Unassigned |
| **Version** | 0.1 |
| **Reformatted** | 29 July 2026 |

</div>

!!! danger "Unvalidated recipe"
    Confirm reagent grades, sterilization methods, storage conditions, and final
    media formulations before preparing or using these recipes.

## Purpose

These recipes describe stock solutions and media combinations for
autoinduction media based on Studier-style formulations.

## Stock solutions

### ZY base

| Component | Final amount |
|---|---:|
| Tryptone or N-Z-Amine AS | 10 g/L |
| Yeast extract | 5 g/L |

Dissolve in the water volume required for the final medium, such as 958 mL for
ZYM-5052. Autoclave and cool before adding sterile stocks.

### 50× M

| Component | Concentration |
|---|---:|
| Na₂HPO₄·7H₂O | 1.25 M |
| KH₂PO₄ | 1.25 M |
| NH₄Cl | 2.5 M |
| Na₂SO₄ | 0.25 M |

Add salts sequentially to 700 mL water and stir to dissolve. Crystals may be
redissolved by microwaving. The recorded pH of a 20× dilution is approximately
6.75.

### 20× P

| Component | Concentration |
|---|---:|
| Na₂HPO₄·7H₂O | 1.0 M |
| KH₂PO₄ | 1.0 M |
| (NH₄)₂SO₄ | 0.5 M |

Add salts sequentially to 770 mL water and stir to dissolve. The recorded pH of
a 20× dilution is approximately 6.75.

### 100× 505

| Component | Concentration |
|---|---:|
| Glycerol | 50% |
| Glucose | 5% |

Add components sequentially to 570 mL water and stir until dissolved.

### 50× 5052

| Component | Concentration |
|---|---:|
| Glycerol | 25% |
| Glucose | 2.5% |
| α-lactose | 10% |

Add components sequentially to 730 mL water. Lactose dissolves slowly, often
taking more than 2 hours at room temperature; microwaving may speed dissolution.

### 500× MgSO₄, 1 M

| Component | Amount |
|---|---:|
| MgSO₄·7H₂O | 24.65 g |
| Water | To 100 mL |

Dissolve MgSO₄·7H₂O in approximately 87 mL water, then bring to 100 mL.

### 80× G

| Component | Amount |
|---|---:|
| Glucose | 40 g |
| Water | 74 mL |

Stir until dissolved. The legacy note reports that this may take more than 45
minutes at room temperature and that microwaving may speed dissolution. Use for
MDG only.

### 100× D

| Component | Amount |
|---|---:|
| Aspartic acid | 25 g |
| NaOH | 8 g |
| Water | 84 mL |

Dissolve aspartic acid in water and neutralize with NaOH to approximately pH 7.
Use for MDG only.

### 1000× trace elements

The legacy note recommends purchasing this stock.

!!! question "Specification needed"
    Define the approved trace-element source, catalog number, storage condition,
    and expiration before approval.

## Media combinations

| Medium | Use | Required stocks |
|---|---|---|
| ZYM-5052 | Typical expression medium | ZY, 50× M, 50× 5052, 500× MgSO₄, trace elements |
| ZYP-5052 | Expression medium with higher buffering capacity | ZY, 20× P, 50× 5052, 500× MgSO₄, trace elements |
| ZYM-505 | Non-inducing medium for high-density growth | ZY, 50× M, 100× 505, 500× MgSO₄, trace elements |
| MDG | Non-inducing medium for overnight growths or glycerol stocks | 50× M, 80× G, 100× D, 500× MgSO₄, trace elements |

!!! warning "Legacy ambiguity"
    The source note listed `50× M` twice for MDG. This page records it once;
    verify the final MDG formulation before approval.

## Preparation outline

1. Prepare and sterilize stock solutions according to approved lab practice.
2. Autoclave the ZY base separately.
3. Cool the base medium before adding sterile stocks.
4. Add the stock solutions required for the target medium.
5. Label the finished medium with name, preparation date, expiration date,
   preparer, and any antibiotic or additive added later.

## Approval checklist

- [ ] Verify all stock concentrations and final media compositions
- [ ] Define sterilization method for each stock
- [ ] Define storage conditions and expiration dates
- [ ] Confirm the approved trace-element product
- [ ] Add citation or source details for the Studier formulation
- [ ] Link protocols that use each medium

## Source history

Reformatted from `docs/recipes/autoinduction`. The legacy file remains as the
source record pending review and archival.
