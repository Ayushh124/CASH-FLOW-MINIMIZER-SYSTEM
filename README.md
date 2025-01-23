# Cash Flow Minimizer System

## Introduction
The **Cash Flow Minimizer System** is a program designed to minimize the number of transactions among multiple banks located across different corners of the world. This system ensures that unnecessary transactions are avoided, and a **World Bank** acts as an intermediary when banks lack common payment modes.

---

## Features
- Calculates the net amounts owed by or owed to each bank.
- Reduces the total number of transactions required for settlement.
- Handles multiple payment modes between banks.
- Automatically routes transactions through the **World Bank** for banks with no common payment modes.
- Provides a detailed summary of optimized transactions.

---

## How It Works
1. **Input the Details**: The system asks for the number of banks, the names of the banks, their available payment modes, and the details of transactions.
2. **Net Calculation**: It calculates the net amount each bank owes or is owed.
3. **Transaction Minimization**: Based on the net amounts and payment modes, the system minimizes the number of transactions required.
4. **Output**: A detailed list of transactions showing which bank pays which, the amount, and the payment mode.

---

## Input Format
- **Number of Banks**: Total number of banks involved in the transaction.
- **Details for Each Bank**:
  - Name of the bank.
  - Number of payment modes it supports.
  - List of payment modes (without spaces in names).
- **Number of Transactions**: Total number of initial transactions.
- **Transaction Details**:
  - Name of the debtor bank.
  - Name of the creditor bank.
  - Transaction amount.

---

## Output
- The system outputs a detailed list of optimized transactions in the format:
