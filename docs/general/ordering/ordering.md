---
title: Ordering and receiving
tags:
  - Draft
  - Lab operations
  - Purchasing
---

# Ordering and receiving

<div class="protocol-meta" markdown>

|                               |                                                |
| ----------------------------- | ---------------------------------------------- |
| **Status**                    | <span class="status draft">Needs review</span> |
| **Owner**                     | Unassigned                                     |
| **Version**                   | 0.1                                            |
| **Reformatted**               | 27 July 2026                                   |
| **Funding information dated** | 10 June 2026                                   |

</div>

!!! warning "Internal purchasing information"
    This page contains internal addresses, program IDs, and a purchase-order
    number. Do not publish the site publicly without reviewing access controls
    and redacting sensitive purchasing information.

## Quick guide

| What are you ordering?                                    | What to do                                                               |
| --------------------------------------------------------- | ------------------------------------------------------------------------ |
| Pens, printer paper, notebooks, or similar basics         | Check the Biochemistry office stock room first                           |
| Department-managed office supplies, such as printer toner | Order through the Biochemistry department using program ID `PG000019893` |
| A routine research item costing less than $1,000          | Place the order using the current funding allocation                     |
| An item costing $1,000 or more                            | Check with Chris on Slack before ordering                                |
| Plasmidsaurus sequencing                                  | Follow the [standing-PO workflow](#plasmidsaurus)                        |
| An Addgene construct                                      | Follow the [non-catalog workflow](#addgene-constructs)                   |
| Anything unclear                                          | Ask Chris on Slack or contact Biochemistry Purchasing                    |

See the
[Biochemistry purchasing intranet](https://uwprod.sharepoint.com/sites/biochem/purchasing)
for department-wide purchasing information.

## Delivery information

| Field                  | Value                                                  |
| ---------------------- | ------------------------------------------------------ |
| **Ship-to address**    | BSB, 440 Henry Mall                                    |
| **Deliver-to address** | Biochemical Sciences, DeLuca, Hector, `F-0204-02-2208` |

Confirm that these addresses are still current before approving this page.

## Funding allocation

The source document records the following split as current on **10 June 2026**:

| Program ID    | Allocation |
| ------------- | ---------: |
| `PG000032603` |        50% |
| `PG000036118` |        50% |

!!! warning "Verify before submitting"
    Funding assignments can change. Confirm the current allocation before
    submitting a requisition, especially after the date shown above.

### Create a Workday worktags template

1. In Workday, search for **Create Requisition Worktags Template**.
2. Give the template a descriptive name.
3. Select **Create split allocations template**.
4. Enter the current program IDs and percentages.
5. Use the saved template as the funding information for requisitions.

### Set purchasing defaults

The legacy document does not explain how to set the defaults.

!!! question "Documentation needed"
    Add verified steps for setting the default ship-to address, deliver-to
    address, requester, and worktags template in Workday.

## Special ordering workflows

### Plasmidsaurus

The lab has a standing purchase order.

1. Submit the order through your own Plasmidsaurus account.
2. Select purchase order as the payment method and use **PO `PO-00183342`**.
3. Follow Plasmidsaurus instructions for preparing the sample.
4. Place the sample in the designated drop box.
5. Monitor your account or email for sequencing results.

Ask for help before submitting if your account is not configured for the lab.

### Addgene constructs

Addgene constructs require a non-catalog purchasing workflow.

1. Find the required construct on Addgene.
2. Submit a **non-catalog order** for the construct.
3. Biochemistry Purchasing will place the order and coordinate the required
   logistics.
4. Watch for forwarded documents requiring your signature and complete them
   promptly.
5. If an additional lab approval is required, the request may be emailed to
   Hannah.

Contact Biochemistry Purchasing if the required form, agreement, or approval is
unclear.

## Receiving deliveries

### Non-chemical items

If you receive an item ordered by someone else, give it to that person. If it
is your order:

1. Open the package.
2. Compare the contents with the packing slip and confirm that the order is
   complete and undamaged.
3. Place the packing slip in the drawer labeled **Packing slips**.
4. Break down cardboard boxes and place them in the appropriate recycling
   location.
5. Store the item in its designated location.

!!! note
    The packing-slip location was last recorded on **5 February 2026**. Update
    this page if the location changes.

### Chemicals ordered through ChemManager

These packages should arrive with inventory barcodes already attached.

1. Confirm the chemical and container match the order.
2. Open ChemManager and select **Receiving Actions**.
3. Find the ordered item.
4. Receive the container using the barcode attached to that specific
   container.
5. Store the chemical according to its approved storage requirements.

!!! danger "Chemical receiving"
    Do not accept or store a leaking, damaged, incorrectly labeled, or
    temperature-compromised chemical. Follow the lab's incident and escalation
    procedure.

### Chemicals ordered outside ChemManager

Create an inventory container record before storing the item:

1. Open **Material Search** in ChemManager.
2. Search for the compound. Searching by CAS number is usually the most
   specific method.
3. Verify that the result represents the correct material.
4. Select **Add Container**.
5. Enter the container details and assign its barcode.
6. Confirm the record, labeling, and storage location.

## Commonly ordered supplies

The legacy page names gloves, pipette tips, and serological supplies but does
not include verified vendors, catalog numbers, sizes, or reorder thresholds.

!!! question "Documentation needed"
    Add a maintained table containing the preferred item, vendor, catalog
    number, package size, storage location, and reorder point. Do not rely on
    an informal list when product compatibility matters.

## Review checklist

- [ ] Assign an owner for purchasing documentation
- [ ] Confirm the $1,000 approval threshold and point of contact
- [ ] Confirm ship-to and deliver-to addresses
- [ ] Confirm the dated funding split
- [ ] Document Workday default settings
- [ ] Confirm the Plasmidsaurus purchase order and drop-box location
- [ ] Confirm the current Addgene approval workflow and named approver
- [ ] Confirm packing-slip and recycling locations
- [ ] Review ChemManager terminology against the current interface
- [ ] Complete the common-supplies table
- [ ] Decide whether this page requires authenticated hosting or redaction

## Source history

Reformatted from `docs/general/ordering.txt`. The legacy file remains in the
repository as the source record until the lab approves this page and decides
how legacy documents should be archived.

