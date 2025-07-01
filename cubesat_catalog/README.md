# CubeSat Catalog

This folder contains a curated reference of real CubeSats used or explored in this orbital analysis project. It is designed to complement the orbital simulations by providing mission context and metadata for each satellite.

## Contents

- `cubesats.csv`: A table of selected CubeSats with mission type, inclination, and descriptions.
- Optional Markdown profiles (coming soon) with mission summaries and reference links.

## Fields in `cubesats.csv`

| Column           | Description |
|------------------|-------------|
| `Name`           | The common or catalog name of the CubeSat |
| `NORAD ID`       | Unique identifier from the NORAD satellite catalog |
| `Inclination (°)`| Orbital inclination in degrees (converted from TLE) |
| `Mission Type`   | The scientific or technical focus of the satellite |
| `Description`    | Brief summary of the mission objective |

## Purpose

This catalog helps contextualize the CubeSats used in orbital modeling. By tagging satellites with their mission types, users can explore how different scientific objectives relate to orbital parameters like inclination and altitude.

## Future Plans

- Add profiles for each CubeSat (`.md` files) with links and visualizations
- Include links to real-time tracking and mission docs
- Integrate with a future CubeSat dashboard

---
