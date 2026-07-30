# Column Rust Calculator

**Column Rust Calculator** is a Python-based GUI tool for analyzing corrosion (rusting) effects on RCC (Reinforced Cement Concrete) column reinforcement bars and ties. The tool calculates yield strength reduction, cross-sectional area loss, and regional corrosion distribution along column height, with visual profile graphs.

<p>
  <strong>Cite this Tool:</strong>
  <a href="https://doi.org/10.5281/zenodo.21669917">
    <img src="https://img.shields.io/badge/DOI-10.5281/zenodo.21669917-blue" alt="DOI">
  </a>
</p>

## Project Overview

In structural engineering, rusting of reinforcement bars is a critical factor affecting the durability and safety of RCC columns. Assessing the extent of corrosion and its impact on structural capacity requires systematic analysis of various rust levels and their distribution along the column height. This tool automates the rust assessment process by providing a user-friendly interface for structural engineers to quickly evaluate corrosion effects without complex calculations. For a complete demonstration of the features and setup, see the video below:

<div align="center">

[![Project Demo](https://img.youtube.com/vi/8TmJJth8Uik/0.jpg)](https://www.youtube.com/watch?v=8TmJJth8Uik)

</div>

The tool implements standard rust formulas and random bar assignment to simulate realistic rust patterns, making it valuable for parametric studies and structural health assessment.

The following diagram illustrates the step-by-step workflow of the RCC Column Corrosion Calculator, from user inputs to the final results and visualization.

<p align="center">
  <img src="https://raw.githubusercontent.com/tufailmab/RCC-Column-Corrosion-Calculator/main/Conceptual%20Workflow.png" alt="Conceptual Workflow of the RCC Column Corrosion Calculator">
  <br>
  <em>Conceptual workflow diagram showing the main calculation and visualization steps.</em>
</p>

## Workflow Integration

This tool is designed for standalone use in structural assessment workflows. It can be used alongside other structural analysis tools to evaluate column deterioration. The generated results can be used for:

- Structural capacity assessment
- Rehabilitation planning
- Parametric rust studies
- Research and academic work

## Features

- **GUI-Based Interface:** User-friendly graphical interface for easy data input and results visualization.
- **Rust Analysis:** Calculates effects at multiple rust levels.
- **Visual Profile Graphs:** Generates stepped rust distribution graphs along column height.
- **Random Bar Assignment:** Each bar gets random rust level for realistic analysis.
- **Comprehensive Results:** Detailed tables showing yield strength, area, and percentage losses.
- **Standalone EXE:** No Python installation required for end users.

## File Information

- **EXE Name:** `Column Rust Calculator.exe`
- **Target Files:** Self-contained application
- **Language:** Python
- **GUI Framework:** Tkinter
- **Graphing Library:** Matplotlib

## Usage Instructions

### Option 1: Using the Standalone EXE (Recommended for Users)

1. Download the latest **`Column Rust Calculator.exe`** from the [Releases](https://github.com/tufailmab/rcc-column-corrosion-calculator/releases) page.
2. Double-click the `.exe` file to launch the application (no installation required).
3. Enter the required input parameters:
   - Bar Diameter (mm)
   - Yield Strength (MPa)
   - Number of Bars
   - Reinforcement Type
   - Corrosion Rate (β_y)
   - Rust Levels (%)
   - Regional Intervals
   - Column Height (mm)
4. Click **"Calculate Corrosion Effects"** to run the analysis.
5. View the results and rust profile graph.

### Option 2: Running from Source (For Developers)

```bash
# Clone the repository
git clone https://github.com/tufailmab/rcc-column-corrosion-calculator.git

# Navigate to the project directory
cd rcc-column-corrosion-calculator

# Install dependencies
pip install -r requirements.txt

# Run the application
python corrosion_calculator.py
```

## Requirements

- Python 3.9 or later
- Tkinter
- Matplotlib

Install the required packages with:

```bash
pip install -r requirements.txt
```

## License

This project is open-source and is available under the MIT License (or the license included in this repository).

## Developer Information

- **Developer:** Tufail Mabood
- **Contact:** [WhatsApp](https://wa.me/923440907874)
- **GitHub:** https://github.com/tufailmab
- **Note:** This tool is open-source. Contributions, improvements, bug reports, and validation studies are welcome.
