# Titanic: Exploring Survival Patterns

**Camila Lopez** · CPSC 4800 – Assignment 2

Exploratory analysis of the Titanic dataset (891 passengers) testing whether survival was associated
with **class**, **sex**, and **age**.

## Main findings

- **Sex:** 74.2% of women survived vs 18.9% of men.
- **Class:** survival fell from 63.0% in first class to 24.2% in third class.
- **Age:** same typical age (28) in both groups; only young children (0–12) stood out, at 58%.

The typical survivor was a woman in first or second class; the typical victim was an adult man in third class.

## Project structure

- `DATA/` – dataset (titanic.csv)
- `SRC/` – Jupyter notebook
- `DOCS/` – one-page PDF summary
- `RESULTS/` – charts

## How to run

Open the notebook in `SRC/` and run all cells. Requires pandas, numpy, matplotlib, seaborn, and scipy.
