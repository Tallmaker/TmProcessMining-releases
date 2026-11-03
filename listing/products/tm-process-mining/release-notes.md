## New

- Two template apps. Template v4 is the simpler first app for flat event data. Template v5 runs four example data sets, including purchase-to-pay with Purchase Order and PO Item as Case perspectives.
- Two demo apps: Claims (where do claims lose time) and Freight (follow the goods across objects).
- A user manual as HTML and PDF, with a page for each visual, the settings and the data quality rules.
- Example data for the templates and the demo apps.
- A mapping check that reports which source column supplies each Event role.
- Data quality rules for source tables that load duplicate or empty values.

## Changed

- Derived Case and Transition values use the Event order to separate Events that share a timestamp. Values can differ from earlier releases for such Cases.

## Fixed

- Rework Map and Variant Braids labels read on a transparent background.
- Difference Map in Compare mode no longer drops Cases because of settings that belong to value mode.

## Before you upgrade

- Objects saved before this update keep their earlier expressions. Insert each object again to use the current expressions.
