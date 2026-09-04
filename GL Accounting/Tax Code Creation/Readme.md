# Tax Code Creation

## Definition

Tax Code Creation in SAP is the process of creating and maintaining a tax code used to calculate and post the applicable tax during business transactions.

## Transaction Code

**T-Code:** `FTXP`

## Procurement Flow

**Purchase Order → Goods Receipt (MIGO) → Invoice Verification (MIRO) → Tax Calculation → Accounting Document**

## Purpose

Tax codes are used in SAP to determine the applicable tax percentage and support the correct calculation and posting of tax during relevant transactions.

## Tax Code Creation Process

1. Execute transaction code `FTXP`.
2. Select the required country.
3. Enter the tax code.
4. Maintain the tax code description.
5. Select the appropriate tax type.
6. Maintain the required tax percentage rates.
7. Maintain the relevant tax conditions.
8. Assign the required G/L accounts through account determination.
9. Save the tax code.

## Key Information

- Country
- Tax Code
- Tax Type
- Tax Description
- Tax Rate
- Tax Condition
- G/L Account
- Input Tax / Output Tax

## Practical Example

In this practice scenario, a tax code was maintained for India.

**Country:** `IN – India`

**Tax Code:** `V1`

The tax code contains the applicable tax components used for the relevant purchasing transaction.

## Tax Components

The tax configuration includes the required tax components such as:

- CGST
- SGST

The configured tax rates are used during invoice verification for tax calculation and accounting posting.

## Screenshot

### Tax Code Configuration

![Tax Code Creation](./Sgst%20and%20Cgst%205%20%25%20gst.png)
