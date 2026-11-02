# Music Store Data Analysis with SQL

A relational SQL project exploring customer behaviour, invoices, music purchases, artists, genres, and track performance in a music-store dataset.

**Project type:** SQL Analytics · Relational Data  
**Primary tool:** MySQL  
**Main script:** [SQL_PROJECT_1.sql](./SQL_PROJECT_1.sql)  
**Presentation:** [Music_Store.pptx](./Music_Store.pptx)

## Overview

This project uses SQL to answer business questions from a music-store database. It creates a relational schema and uses joins, aggregations, subqueries, common table expressions (CTEs), and window functions to turn transactional data into useful analysis.

The focus is on writing queries that connect customer, invoice, track, album, artist, and genre information—not just retrieving rows from individual tables.

## Business questions explored

The SQL script includes queries to investigate:

- Which employees are most senior based on their level?
- Which countries generate the most invoices?
- Which invoices have the highest totals?
- Which billing city generates the highest invoice revenue?
- Which customer has spent the most overall?
- Which customers have purchased Rock music?
- Which artists have the most Rock tracks in the dataset?
- Which tracks are longer than the average track duration?
- How much do customers spend on individual artists?
- Which genre is most purchased in each country, including ties?
- Who is the highest-spending customer in each country, including ties?

These questions demonstrate how transactional data can be used to explore revenue, customer value, music preferences, and catalogue patterns.

## Database structure

The script defines tables for:

- Customers and employees
- Invoices and invoice lines
- Artists, albums, and tracks
- Genres and media types
- Playlists and playlist tracks

Primary keys and foreign-key relationships connect the tables and support multi-table analysis.

## SQL techniques demonstrated

| Technique | How it is used |
|---|---|
| Filtering and sorting | Identify records that match a business question |
| GROUP BY and aggregates | Calculate invoice counts, revenue, and purchase totals |
| JOIN operations | Connect customer, invoice, track, album, artist, and genre data |
| Subqueries | Compare track durations against the average |
| CTEs | Organise multi-step analytical queries |
| Window functions | Rank genres and customers within each country |
| DENSE_RANK() | Preserve ties when more than one result shares the top position |

## How to run

1. Install and open MySQL.
2. Review [SQL_PROJECT_1.sql](./SQL_PROJECT_1.sql).
3. Run the schema-creation section to create the MUSIC_STORE database and its tables.
4. Load the matching music-store dataset into the tables, respecting the primary-key and foreign-key relationships.
5. Run the analysis queries after the tables contain data.

**Important:** The repository currently includes the SQL script and a presentation, but does not include the source data files. Creating the tables alone will not produce analytical results; the matching dataset must be loaded first.

## Repository contents

- **SQL_PROJECT_1.sql** — table definitions and analysis queries.
- **Music_Store.pptx** — project presentation.

## Limitations and next improvements

- Add the source dataset or clear instructions for obtaining the compatible dataset.
- Separate schema setup from analytical queries for easier navigation.
- Add sample result tables and explain the most important findings.
- Validate revenue calculations and tie-handling against the loaded data before publishing quantified conclusions.

## Author

**Bodigadla Sarvendhra Vamsi** — BCA graduate building practical SQL and data analytics skills.

[View my GitHub profile](https://github.com/sarvendhra-vamsi)
