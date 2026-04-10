# Auckland CBD Pedestrian Weather Resilience Analysis

This repository contains an investigation into the relationship between Auckland's volatile weather patterns and pedestrian footfall in the Central Business District (CBD) during 2024.

## Project Overview
When it rains or becomes windy, does the Auckland CBD turns into ghost town? By merging Heart of the City pedestrian sensor data with the Open-Meteo Historical Weather API, this project tests the question.

Key Finding: Aucklanders are remarkably "stubborn". While extreme weather dampens "peak" activity (outliers), the average pedestrian counts remain stable.

## Getting Started
### Prerequisites:
Python: 3.13+
Install uv: pip install uv
Install Quarto: http://quarto.org/

### Installation & Reproduction:
To replicate this analysis locally, run the following commands in your terminal:
```bash
# Clone the repository
git clone https://github.com/jhe482-uoa/Auckland-CBD-Pedestrian-Analysis
cd Auckland-CBD-Pedestrian-Analysis

# Sync dependencies and activate virtual environment
uv sync
source .venv/bin/activate

# Render the report to PDF
quarto render GISCI343_A1_He_jhe482.qmd
```
