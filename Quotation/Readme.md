
# Quotation

## Overview

A quotation in SAP MM represents the vendor's response to a Request for Quotation (RFQ), including the offered price and other relevant purchasing conditions.

![Quotation](./Maintain%20Quotation%201.png)
![Quotation](./Maintain%20Quotation%202%20.png)
![Quotation](./Maintain%20Quotation%203.png)
## Transaction Code

**T-Code:** `ME47`

## Purpose

The quotation is maintained in SAP based on the vendor's response to the RFQ. The submitted prices can later be compared to identify the suitable vendor.

## Quotation Process

1. Receive the RFQ from the purchasing organization.
2. Receive quotation details from the vendor.
3. Execute transaction code `ME47`.
4. Enter the RFQ number.
5. Select the relevant vendor.
6. Maintain the vendor's quoted price and other details.
7. Save the quotation.

## Key Information

- RFQ Number
- Vendor
- Material
- RFQ Quantity
- Quoted Price
- Delivery Information
- Currency
- Vendor-specific quotation details

## Procurement Flow

```text
Purchase Requisition
        ↓
RFQ
        ↓
Quotation
        ↓
Vendor Comparison
        ↓
Purchase Order
