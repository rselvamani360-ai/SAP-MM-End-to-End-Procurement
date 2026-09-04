# Request for Quotation (RFQ)

## Overview

A Request for Quotation (RFQ) is a purchasing document used to invite vendors to submit quotations for required materials or services.

In SAP MM, the RFQ process is used to request pricing and delivery information from multiple vendors.

## Transaction Code

**T-Code:** `ME41`

## Purpose

The RFQ is created and sent to selected vendors so that their quotation details can be collected and compared.

## RFQ Process

1. Identify the material or purchasing requirement.
2. Execute transaction code `ME41`.
3. Enter the required RFQ details.
4. Enter the material and required quantity.
5. Maintain the delivery date.
6. Enter the purchasing organization and purchasing group.
7. Select or maintain the required vendors.
8. Save the RFQ.

## Key Information

- RFQ Number
- Vendor
- Material
- Quantity
- Delivery Date
- Purchasing Organization
- Purchasing Group
- RFQ Validity / Quotation Deadline

## Vendor RFQ Details

RFQs were created for multiple vendors as part of the procurement process.

### Vendor 1

![Vendor 1 RFQ](./vendor%201%20Rfq%20Display.png)

### Vendor 2

![Vendor 2 RFQ](./vendor%202%20Rfq%20Display.png)

### Vendor 3

![Vendor 3 RFQ](./Vendor%203%20Rfq%20Display.png)

## Procurement Flow

```text
Purchase Requirement
        ↓
RFQ
        ↓
Quotation
        ↓
Vendor Comparison
        ↓
Purchase Order
