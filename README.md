# BlackLedger

**Your money, organized.**

BlackLedger is an in-development, privacy-focused personal finance application for Windows. It aims to give individuals and households a clear view of their budgets, accounts, transactions, bills, and savings in one desktop dashboard.

## Project overview

BlackLedger is being designed around a unified household budget that can include multiple financial accounts. Planned features include:

- Checking, savings, and credit-card account management
- Monthly budgeting organized by pay period
- Planned income, expense tracking, and percentage-based savings allocations
- Account-specific transaction lists and household-level reporting
- CSV transaction imports from supported institutions, with a configurable column mapper for other formats
- Merchant keyword categorization and manual transaction review
- Recurring bills, financial reports, and interactive visualizations
- Optional Plaid-based account connectivity, subject to integration testing and applicable access requirements

## Current status

**In active development.** BlackLedger V6 is being designed as a native Windows desktop application. The Plaid integration is planned; it is **not live** and this repository is currently a public project overview, not a production application.

## Plaid integration goal

If implemented, Plaid would be used for authorized connections to supported financial institutions and access to account and transaction data with the user's consent. Manual CSV imports would remain an alternative. Credentials and access tokens must not be committed to GitHub or embedded in public desktop builds.

## Privacy and security

This public repository contains project information only. It does not contain personal financial data, bank exports, credentials, access tokens, or private application databases.

## Repository scope

This README introduces the project. Source code and packaged builds are not published here at this stage.
