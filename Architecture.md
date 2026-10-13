# Application Architecture

## Purpose

The Raffle Winner Picker assists with selecting winners from eligible raffle entrants stored in spreadsheet files.

---

## High-Level Process

Excel Spreadsheet
        │
        ▼
Entry Validation
        │
        ▼
Entrant Processing
        │
        ▼
Random Selection
        │
        ▼
Winner Generation
        │
        ▼
Results Output

---

## Components

### Input Layer

Accepts entrant spreadsheets and validates data

### Processing Layer

Builds an eligible entrant pool

### Selection Layer

Performs random winner selection from eligible entries

### Output Layer

Displays and records selected winners

---

## Data Handling

Entrant spreadsheets remain local to operator's computer and are not stored in this repository

---

## Security

Application source code and development assets are maintained separately in a private repository
