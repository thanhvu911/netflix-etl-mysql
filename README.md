# Netflix Titles ETL & Dashboard (Python, MySQL, Power BI)

## Introduction
An early data-engineering project: extract the public Netflix titles dataset from CSV, load it into a normalized MySQL schema (fact and dimension tables), and visualize it in Power BI.

## Contents
| File | Description |
|---|---|
| `extract.py` | Python ETL: reads `netflix_titles.csv` and loads dimension and fact tables with PyMySQL |
| `netflix_modle.mwb` | MySQL Workbench data model |
| `netflix_fun.pbix` | Power BI report |
| `netflix_titles.csv` | Source dataset |

## Setup
Create the schema from the `.mwb` model, set the database credentials as environment variables, and run `python extract.py`.
