# Association Rule Generator – EECS 4412 Assignment 1 (Q4)

This project implements a custom algorithm to generate strong association rules from frequent itemsets, based on confidence and lift, without using any external libraries.

## 🔍 Overview

Given:
- A CSV file containing frequent itemsets with item IDs, their sizes, and support counts
- A second CSV file mapping item IDs to item names

This program:
- Generates all strong association rules using a minimum confidence threshold (default: 0.7)
- Computes confidence and lift for each rule
- Maps item IDs to item names
- Outputs the final rules in a specific required format to `rules.txt`

## ⚙️ Features
- No external libraries used (fully native Python)
- Input parameters:
  - `frequent_itemsets.csv`
  - `ID2name.csv`
  - Minimum confidence (default: 0.7)
- Clean, readable output with rule formatting:
