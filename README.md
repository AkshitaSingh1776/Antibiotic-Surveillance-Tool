# Antibiotic Resistance Surveillance-Tool
This project is a simple Python-based surveillance tool designed to analyze antimicrobial resistance (AMR) data from laboratory isolates. Using a CSV dataset containing organisms, antibiotics, and susceptibility results, the program performs exploratory analysis and generates visual insights into resistance patterns.

Features
Loads and analyzes AMR datasets using Pandas.
Displays dataset information, including:
Total number of entries
Available columns
Unique organisms
Unique antibiotics
Sample count per organism
Identifies and counts resistant isolates.
Calculates resistant samples for each antibiotic.
Determines which organisms show the highest resistance.
Computes resistance percentages for individual organisms.
Generates a heatmap visualization of organism-antibiotic resistance relationships using Seaborn and Matplotlib.
Technologies Used
Python
Pandas
Seaborn
Matplotlib
Dataset Format

The input CSV file should contain the following columns:

Column	Description
Organism	Name of the bacterial organism
Antibiotic	Antibiotic tested
Result	Susceptibility result (e.g., R, S, I)

Example:

Organism	Antibiotic	Result
E. coli	Ciprofloxacin	R
S. aureus	Vancomycin	S
Outputs

The tool provides:

Dataset summary statistics
Resistant isolate counts
Resistance frequency by antibiotic
Resistance percentage by organism
Antibiotic Resistance Heatmap
Purpose

Antimicrobial resistance is a growing global health challenge. This project demonstrates how basic data analysis techniques can be used to monitor resistance trends and support evidence-based decision-making in microbiology and public health settings.

Future Improvements
Interactive dashboards using Plotly or Streamlit
Time-series resistance trend analysis
Geographic AMR surveillance
Machine learning models for resistance prediction
Automated report generation
