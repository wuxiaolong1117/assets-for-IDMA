# B&H Partner Setup Guide

[Back to resource center](../README.md) · [Product overview](PRODUCT_OVERVIEW.md)

September 8, 2026

Use the [B&H procurement item master, version 1.0](IDMA_BH_Item_Master_2026_v1.0.xlsx) for the 21 listed records and their setup status. Product and marketing materials in this repository do not clear the workbook's open items.

## Which file to use

| Resource | Purpose |
| --- | --- |
| [Product overview](PRODUCT_OVERVIEW.md) | Readable comparison of the supplied product descriptions |
| [Specification workbook](IDMA_BH_Product_Spec_Sheet%2020260908.xlsx) | Original product descriptions, images, and accessory lists for six products |
| [Item master workbook](IDMA_BH_Item_Master_2026_v1.0.xlsx) | B&H assortment, identifiers, pricing status, bundle components, logistics, compliance, and warranty/RMA setup |

The specification workbook lists GW-500 / Max, which is absent from the item master. The item master includes HEM-100, software, and bundles that are not detailed in the specification workbook. Confirm changes to assortment explicitly rather than combining the two lists automatically.

## Review sequence

| Step | Workbook tab | Review |
| --- | --- | --- |
| 1 | `00_Instructions` | Operating rules, contacts, and current holds |
| 2 | `01_Item_Master` | Vendor SKU, MPN, UPC/GTIN, unit of measure, and sellable status |
| 3 | `02_Pricing` | Price source, notice evidence, effective date, and program acceptance |
| 4 | `03_Bundle_BOM` | Components, quantities, packaging model, and software entitlements |
| 5 | `04_Logistics` | Dimensions, weights, case pack, lead time, and shipping details |
| 6 | `05_Compliance` | Country of origin, classification, and product-specific evidence |
| 7 | `06_Warranty_RMA` | Warranty duration, service contacts, and return implementation |
| 8 | `07_Terms_Approvals` and `99_Lists_QA` | Remaining approvals, evidence, and workbook checks |

## Open items recorded in the supplied workbook

| Area | Recorded status | Next action |
| --- | --- | --- |
| Price effective date | August 17, 2026 remains on hold pending notice evidence | Supply the notice-sent date and verify the workbook's 30-day notice requirement |
| MAP and quarterly rebate programs | Acceptance evidence not supplied | Confirm authorized written acceptance before treating the programs as active |
| Item identifiers and setup | Required fields remain TBD | Complete missing identifiers and verify ownership, units, and item attributes |
| Software | Digital item setup on hold | Confirm license model/term, activation, fulfillment, and return treatment |
| Bundles | Packaging and entitlement details remain open | Confirm factory versus virtual kits, identifiers, contents, and software rights |
| Logistics and compliance | Required data remains TBD | Provide product-specific data and supporting documents |
| Warranty and RMA | Product warranty and operating details remain TBD | Provide warranty terms, support/RMA contacts, and return address |
| Insurance | Certificate evidence marked Action Required | Supply the insurance evidence requested in `07_Terms_Approvals`, row 26 |

These statuses summarize `00_Instructions`, `01_Item_Master`, and `07_Terms_Approvals` in the supplied workbook. They have not been independently updated by a new approval or supporting document.

## Source documents and updates

The item master references the signed vendor agreement, controlled price schedule `IDMA-BH-PS-2026-01 v3.5`, and proposed addenda. Those source documents are not included in this repository. Obtain the relevant controlled copies from the existing partner contact when completing the review. The workbook states that signed agreement terms take precedence over conflicting price-list language.

Preserve unknown values and status fields. **TBD** means information is still required, **Hold** means an activation dependency remains, and **Not Accepted** means acceptance is not evidenced in the supplied workbook. A `PASS` check alone does not establish full item readiness.

Send corrections with the SKU, tab name, field, proposed value, and supporting evidence. General correspondence: [contact@idma.ai](mailto:contact@idma.ai). Existing B&H contacts are recorded in `00_Instructions`; the U.S. correspondence address is not confirmed as a ship-from or RMA address.
