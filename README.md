![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)
![Poliastro](https://img.shields.io/badge/Astro%20Library-Poliastro-blueviolet)
![STK](https://img.shields.io/badge/Simulation-STK-0052CC?logo=rocket)
![Matplotlib](https://img.shields.io/badge/Plots-Matplotlib-brightgreen?logo=plotly)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

# 🛰️ Orbital Decay and Ground Coverage Analysis of a CubeSat

## Overview
This project explores how a CubeSat's orbital parameters, specifically altitude and inclination, affect its mission profile. We simulate satellite orbits using Systems Tool Kit (STK) and analyze access windows, orbital decay, and ground track coverage with Python. The goal is to build a bridge between orbital mechanics, physics principles, and data analysis while producing visual, interpretable results.

## Motivation
Small satellite missions must carefully balance orbital lifespan, ground visibility, and energy efficiency. This project aims to simulate and visualize these trade-offs, offering a practical demonstration of how space mission planning integrates physics and data science.

## Objectives
- Simulate low Earth orbits (LEO) at various altitudes and inclinations
- Estimate orbital decay timeframes due to atmospheric drag
- Analyze satellite visibility over a ground station
- Compare revisit times and coverage for different orbital parameters
- Visualize ground tracks and coverage maps

## Tools and Technologies
- **Python**: data analysis, visualization
  - Libraries: `Skyfield`, `Poliastro`, `matplotlib`, `pandas`
- **STK (Systems Tool Kit)**: industry-standard simulation and visualization
- **Jupyter Notebook**: interactive data exploration

## File Structure
orbital-analysis-cubesat/
├── data/                  # Orbital elements and simulated outputs
├── notebooks/            # Jupyter Notebooks for exploration
├── scripts/              # Python modules for parsing and analysis
├── outputs/              # Graphs, coverage maps, decay charts
├── README.md             # Project overview and instructions
└── requirements.txt      # Python environment dependencies

## Getting Started
1. Clone this repository
2. Install required Python packages: pip install -r requirements.txt
3. Run notebooks in /notebooks to simulate and visualize orbital behavior

## Sample Research Questions
- How does orbital altitude affect the expected mission lifetime of a CubeSat?
- How often does a satellite in polar orbit pass over a specific city?
- What are the trade-offs between orbital inclination and global coverage?

## Skills Demonstrated
- Orbital mechanics and astrodynamics
- Physics of atmospheric drag
- Data analysis and storytelling with Python
- Aerospace simulation workflows

## Future Work
- Real-time ingestion of NORAD TLEs
- Thermal/radiation environment modeling
- LEO constellation performance comparison
- Satellite-to-satellite visibility simulation

⸻

## Author

Prudence Gemmell
Astrophysics-Inspired Data Analyst | Science Educator | Space Enthusiast | Math Geek

⸻

## License

MIT License
