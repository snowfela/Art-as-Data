# Mondrian Art Project

## Overview
This project explores how **art can be represented as structured data**. Inspired by the abstract, grid-based compositions of **Piet Mondrian**, the notebook demonstrates how visual art can be broken down into data features — enabling both **artistic analysis** and **data-driven insights**.

The dataset used contains geometric and color-based features of Mondrian's paintings, representing rectangles, lines, and color compositions as tabular data. The project investigates Mondrian's quest for artistic simplicity and explores techniques for identifying **forgeries** falsely attributed to him.

---

## Objectives
- Represent Mondrian’s paintings as structured data.
- Analyze geometric and color properties using pandas.
- Visualize artistic features programmatically.
- Explore how data science can interpret art.
- Experiment with **forgery detection** using feature patterns.

---

## Dataset Description
The dataset consists of **digitized features** from 136 Mondrian paintings created between **1920 and 1940**.  
Each entry includes details such as:
- `painting_id` – Unique identifier for each artwork.  
- `feature` – Shape type (rectangle, line, etc.).  
- `x, y, width, height` – Coordinates and dimensions.  
- `color` – Basic color of the shape.  
- `rgb` – Hexadecimal color value.

Example representation:

| painting_id | feature | x | y | width | height | color  | rgb      |
|--------------|----------|---|---|--------|---------|---------|----------|
| b219 | rect | 0 | 0 | 121 | 152 | white | #ffffff |
| b219 | rect | 132 | 0 | 378 | 365 | red | #e6151a |

---

## Implementation Steps
1. **Load and Explore the Data**  
   - Import `pandas` and load `mondrian-painting-features.csv`.  
   - Inspect the structure and relationships between features.  
   - Visualize sample paintings based on coordinate and color data.

2. **Feature Analysis**  
   - Use queries to extract features for individual paintings.  
   - Study spatial and chromatic compositions.  
   - Identify patterns that define Mondrian’s style.

3. **Forgery Detection Experimentation**  
   - Compare authentic paintings with simulated forgeries.  
   - Analyze deviations in color ratios, line thickness, and composition.

---

## Tools and Libraries
- **Python**
- **Pandas**
- **Matplotlib**
- **NumPy**

---

## Outcome
This project bridges **art and data science**, showing that creativity can be quantified and analyzed. By transforming art into datasets, it demonstrates the intersection between **aesthetics and analytics**, paving the way for computational art studies and AI-driven creativity.

---
