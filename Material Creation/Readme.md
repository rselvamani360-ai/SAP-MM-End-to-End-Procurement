# Material Creation

## Overview

Material Creation is the process of creating a new material master record in SAP MM.

A material master contains important information about a material that is used throughout the procurement and inventory processes.

![Material Creation - MM01](Material%20creation%20MM01.png)


## Transaction Code

**T-Code:** `MM01`

## Purpose

The MM01 transaction is used to create a new material master record in SAP.

## Material Creation Process

1. Execute transaction code `MM01`.
2. Enter the required material information.
3. Select the required **Industry Sector**.
4. Select the appropriate **Material Type**.
5. Select the required views for the material.
6. Enter the required organizational levels such as Plant and Storage Location.
7. Maintain the required material master data.
8. Save the material.

## Key Information Maintained

The material master can contain information related to:

- Basic Data
- Purchasing
- MRP
- Accounting
- Storage
- Plant-specific information

## SAP MM Flow

```text
Material Requirement
        ↓
Material Creation
        ↓
Material Master Record
        ↓
Purchase Requisition
        ↓
RFQ / Quotation
        ↓
Purchase Order
        ↓
Goods Receipt
        ↓
Invoice Verification
