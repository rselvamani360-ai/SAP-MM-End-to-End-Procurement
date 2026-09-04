# Vendor Comparison

## Definition

Vendor Comparison in SAP MM is the process of comparing quotations received from different vendors based on price and other purchasing conditions.

## Transaction Code

**T-Code:** `ME49`

## Procurement Flow

**Purchase Requirement → RFQ → Vendor Quotations → Vendor Comparison → Vendor Selection → Purchase Order**

## Purpose

Vendor Comparison is used to evaluate quotations received from multiple vendors and identify the most suitable vendor for the purchasing requirement.

## Process

1. Create an RFQ for the required material or service.
2. Send the RFQ to multiple vendors.
3. Receive quotations from the vendors.
4. Maintain the vendor quotation details in SAP.
5. Execute transaction code `ME49`.
6. Enter the relevant RFQ or purchasing information.
7. Compare the vendor quotations.
8. Evaluate the offered prices and other purchasing conditions.
9. Select the suitable vendor.
10. Proceed with Purchase Order creation.

## Comparison Criteria

Vendor quotations can be compared based on:

- Quoted Price
- Quantity
- Delivery Date
- Currency
- Purchasing Conditions
- Overall Vendor Offer

## Practical Example

In this practice scenario, three vendors submitted quotations for the same material.

**Material:** `RM01 – Steel Sheet`

**Quantity:** `100 EA`

The quotation values were compared to identify the most suitable vendor before creating the Purchase Order.

## Screenshots

### Vendor Comparison

![Vendor Comparison](./Vendor%20Comparison.png)

