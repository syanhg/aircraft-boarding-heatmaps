# Aircraft Boarding Strategy Heatmaps

This repository contains LaTeX code for visualizing different aircraft boarding strategies using heatmaps. The code creates visual representations for each step of a boarding process for a Boeing 737-800 aircraft with rows 28-48 in economy class (6 seats per row in A-F configuration).

## Boarding Strategies

The following boarding strategies are visualized:

1. **Back-to-Front**: Passengers board in groups from the back of the aircraft to the front
2. **Outside-In (Window-Middle-Aisle)**: Passengers board based on seat position rather than row
3. **Hybrid Strategy**: Combination of back-to-front and outside-in strategies
4. **Random Boarding**: For comparison purposes

Each strategy's visualization shows how the aircraft fills step by step, with heatmaps highlighting the current boarding group.

## Files

### Back-to-Front Strategy
- `group1_boarding.tex`: First boarding group (Rows 28-32)
- `group2_boarding.tex`: Second boarding group (Rows 33-37)
- `group3_boarding.tex`: Third boarding group (Rows 38-43)
- `group4_boarding.tex`: Fourth boarding group (Rows 44-48)

### Other Strategies
- `window_middle_aisle_boarding.tex`: Complete outside-in boarding strategy
- `hybrid_strategy.tex`: Combined back-to-front and outside-in boarding strategy

### Comparison
- `strategy_comparison.tex`: Visual and statistical comparison of all boarding strategies

## Compilation

To compile these LaTeX files:

1. Install a LaTeX distribution like TeX Live or MiKTeX
2. Compile each `.tex` file with `pdflatex`:
   ```
   pdflatex group1_boarding.tex
   ```
3. The resulting PDF will show the heatmap visualization

## Research Basis

This visualization is based on research from "Optimising Passenger Boarding in Aircraft Through a Mathematical Modeling" which analyzes different boarding strategies using mathematical models.

## Boarding Time Results

Strategy | Approximate Boarding Time
---------|---------------------------
Back-to-Front | 12 minutes
Outside-In (Window-Middle-Aisle) | 10 minutes
Hybrid Strategy | 10 minutes
Random | 22 minutes