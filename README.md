# Columbia Pike Business & Property Database

A unified relational database of businesses and properties along the **Columbia Pike corridor** in Arlington, Virginia, built during my internship at **Columbia Pike Partnership** (March 2026 – present).

> This repository documents the design of the project. The underlying records belong to Columbia Pike Partnership and are not published here.

## The Problem

Information about corridor businesses and properties was spread across six separate public and organizational data sources, with inconsistent fields and no single place for staff to look things up.

## What I Built

- **Consolidated 2,119 businesses and 13,062 property records** from six data sources into one Airtable base.
- **Standardized fields and improved record accuracy** across **779 commercial** and **145 multifamily** properties using Arlington County property and revenue datasets.
- **Designed linked issue-tracking and contact tables** that give staff a single reference point for corridor-wide business outreach.

## Data Model (high level)

```
Properties ──< Businesses >── Contacts
     │               │
     └──── Issues ───┘
```

- **Properties:** parcel-level records (commercial, multifamily)
- **Businesses:** businesses linked to the property they occupy
- **Contacts:** outreach contacts linked to businesses
- **Issues:** tracked issues linked to businesses and properties

## Tools

Airtable · Arlington County property and revenue data

## Author

**Clint Caccia**, Computer Information Systems, James Madison University
[LinkedIn](https://www.linkedin.com/in/clint-caccia/)
