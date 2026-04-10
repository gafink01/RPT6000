# RPT6000 - Year-To-Date Sales Report

A COBOL program that reads customer master records and produces a Year-To-Date Sales Report including customer, salesrep, branch, and grand totals.

# Table of Contents

- [Overview](#overview)
- [Program Features](#program-features)
- [Files Used](#files-used)
- [How It Works](#how-it-works)
- [Output](#output)
- [Author](#author)

# Overview

RPT6000 is a COBOL report program that reads customer sales data and produces a formatted Year-To-Date Sales Report. The report includes:

- Customer sales data
- Salesrep totals
- Branch totals
- Grand totals
- Change amount and percentage

# Program Features

- Reads Customer Master File
- Reads Sales Representative File
- Calculates sales changes
- Prints formatted report
- Displays totals at multiple levels
- Handles page headings and pagination

# Files Used

| File Name | Description |
|-----------|-------------|
| CUSTMAST  | Customer master input file |
| SALESREP  | Sales representative input file |
| RPT6000   | Output report file |

# How It Works

1. Load Salesrep table
2. Read customer records
3. Calculate sales change
4. Print customer lines
5. Print salesrep totals
6. Print branch totals
7. Print grand totals

# Output

The program generates:

- Customer Detail Lines
- Salesrep Totals (*)
- Branch Totals (**)
- Grand Totals (***)

# Author

Garrett Finke  
CIS 352  
March 26, 2026  

GitHub Repository:  
https://github.com/gafink01/RPT6000
