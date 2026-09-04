# Purchase Order

## Overview

A Purchase Order (PO) is a formal document created to procure materials or services from a vendor.

In SAP MM, the Purchase Order is a key document in the procurement process and contains vendor, material, quantity, price, delivery, and other purchasing information.

![Purchase Order](./Purchase%20Order.png)

## Transaction Code

**T-Code:** `ME21N`

## Purpose

The Purchase Order is used to formally place an order with a selected vendor based on the purchasing requirement and quotation evaluation.

## Purchase Order Process

1. Select the appropriate vendor.
2. Enter the required material.
3. Enter the purchase order quantity.
4. Maintain the delivery date.
5. Enter the net price.
6. Maintain the required plant and storage location.
7. Check the purchase order details.
8. Save the Purchase Order.

## Key Information

- Vendor
- Material
- PO Quantity
- Net Price
- Currency
- Delivery Date
- Plant
- Storage Location
- Purchasing Organization
- Purchasing Group

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
        ↓
Goods Receipt (MIGO)
        ↓
Invoice Verification (MIRO)
