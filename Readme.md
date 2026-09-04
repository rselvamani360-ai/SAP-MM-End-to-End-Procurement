# SAP MM End-to-End Procurement

## Overview

This repository documents a hands-on SAP MM End-to-End Procurement process performed in an SAP practice environment.

The project covers the major procurement activities from material creation and vendor creation through RFQ, quotation, vendor comparison, G/L accounting, purchase order, goods receipt, stock checking, and invoice verification.

## End-to-End Procurement Flow

**Material Creation → Vendor Creation → RFQ → Quotation → Vendor Comparison → G/L Accounting → Purchase Order → Goods Receipt (MIGO) → Stock Check (MMBE) → Invoice Verification (MIRO)**

## Project Modules

### [1. Material Creation](./Material%20Creation/Readme.md)

Material Creation is the process of creating and maintaining a material master record in SAP MM.

**Transaction Code:** `MM01`

The material master contains the information required for procurement and inventory-related activities.

---

### [2. Vendor Creation](./Vendor%20Creation/Readme.md)

Vendor Creation is the process of creating and maintaining supplier master data required for procurement activities.

Business Partner functionality is used to maintain the supplier information.

**Transaction Code:** `BP`

The vendor information is required for subsequent purchasing activities such as RFQ, quotation, and Purchase Order processing.

---

### [3. RFQ](./RFQ/Readme.md)

A Request for Quotation (RFQ) is a purchasing document used to invite vendors to submit their prices and purchasing conditions for required materials or services.

**Transaction Code:** `ME41`

The RFQ is created and sent to the selected vendors.

---

### [4. Quotation](./Quotation/Readme.md)

A quotation in SAP MM represents a vendor's response to an RFQ, containing the price and other details offered for the required material or service.

**Transaction Code:** `ME47`

Quotation details are maintained for the vendors who respond to the RFQ.

---

### [5. Vendor Comparison](./Vendor%20Comparison/Readme.md)

Vendor Comparison is the process of comparing quotations received from different vendors based on price and other purchasing conditions.

**Transaction Code:** `ME49`

The quotations are compared to identify the most suitable vendor before creating the Purchase Order.

---

### [6. G/L Accounting](./GL%20Accounting/Readme.md)

G/L Accounting activities support the accounting side of the procurement process.

The project includes:

- G/L Account Creation
- G/L Account Display
- G/L Account Line Item Display
- Tax Code Creation
- Automatic Account Assignment

Relevant transaction codes used in the practice include:

**G/L Account Creation:** `FS00`

**Tax Code Creation:** `FTXP`

**Automatic Account Assignment:** `OB40`

These activities support the required G/L account and tax-related configuration used during procurement accounting postings.

---

### [7. Purchase Order](./Purchase%20order/Readme.md)

A Purchase Order is a formal purchasing document issued to the selected vendor for the required material or service.

**Transaction Code:** `ME21N`

The Purchase Order contains the vendor, material, quantity, price, delivery information, and other purchasing details.

---

### [8. Goods Receipt (MIGO)](./MIGO/Readme.md)
Goods Receipt is the process of recording the receipt of materials against a Purchase Order.

**Transaction Code:** `MIGO`

After the Goods Receipt is posted, SAP generates a Material Document for the goods movement.

---

### [9. Stock Check (MMBE)](./Stock%20Check/Readme.md)
Stock Check is used to review the current stock quantity and availability of a material.

**Transaction Code:** `MMBE`

The stock overview can be used to verify the material quantity after Goods Receipt.

---

### [10. Invoice Verification (MIRO)](./MIRO/Readme.md)

Invoice Verification is the process of checking and posting the vendor invoice against the relevant purchasing documents.

**Transaction Code:** `MIRO`

The invoice is verified against the Purchase Order and Goods Receipt before posting.

After successful invoice posting, SAP generates the relevant Accounting Document.

---

## Key SAP Transaction Codes

| Process | Transaction Code |
|---|---|
| Material Creation | `MM01` |
| Vendor / Business Partner | `BP` |
| Create RFQ | `ME41` |
| Maintain Quotation | `ME47` |
| Vendor Comparison | `ME49` |
| G/L Account Creation | `FS00` |
| Tax Code Creation | `FTXP` |
| Automatic Account Assignment | `OB40` |
| Create Purchase Order | `ME21N` |
| Goods Receipt | `MIGO` |
| Stock Overview | `MMBE` |
| Invoice Verification | `MIRO` |

## Procurement Process Summary

The complete practice process follows the sequence below:

**Material Creation**

↓  

**Vendor Creation**

↓  

**Request for Quotation (RFQ)**

↓

**Quotation**

↓

**Vendor Comparison**

↓

**G/L Accounting**

↓

**Purchase Order**

↓

**Goods Receipt (MIGO)**

↓

**Stock Check (MMBE)**

↓

**Invoice Verification (MIRO)**

## Project Scope

This repository focuses on practical SAP MM procurement activities performed in a practice environment.

The documentation includes transaction codes, process descriptions, procurement flow, configuration activities, and SAP system screenshots for the completed steps.

## Learning Objectives

Through this project, the following SAP MM concepts are practiced:

- Material Master Creation
- Vendor / Business Partner Creation
- Request for Quotation
- Vendor Quotation
- Vendor Comparison
- G/L Accounting Basics
- Tax Code Configuration
- Automatic Account Assignment
- Purchase Order Processing
- Goods Receipt
- Stock Monitoring
- Invoice Verification
- Basic MM-FI Integration

## Documentation Structure

Each process is documented in its respective folder with relevant screenshots and `Readme.md` documentation.

```text
SAP-MM-End-to-End-Procurement/
│
├── GL Accounting/
│   ├── Automatic Account Assignment/
│   ├── GL Account Display/
│   ├── GL Account Line Item Display/
│   └── Tax Code Creation/
│
├── MIGO/
│
├── MIRO/
│
├── Material Creation/
│
├── Purchase order/
│
├── Quotation/
│
├── RFQ/
│
├── Stock Check/
│
├── Vendor Comparison/
│
└── Vendor Creation/
    └── BP Creation/
