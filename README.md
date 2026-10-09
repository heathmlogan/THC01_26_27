# THC01_26_27

# Data Visualization Workshop

**Thematic Course 1 (THC01)**  
**Governance of Sustainability MSc Programme**  
**Leiden University**  
**Academic Year 2026–2027**

## Overview

This repository contains teaching materials developed for the Data Visualization Workshop in Thematic Course 1 of the Governance of Sustainability Master's programme at Leiden University.

The workshop introduces students to the use of Python for data visualization and sustainability data analysis. Through a combination of guided notebooks and a curated sustainability dataset, students learn how to import, structure, visualize, and communicate data effectively.

The materials are designed for a full-day hands-on workshop and may be adapted for use in other sustainability, environmental studies, public policy, or social science courses.

---

## Learning Objectives

Upon completion of this workshop, students should be able to:

- Import data from Excel files into Python.
- Understand and work with tabular data structures.
- Clean and transform datasets for visualization.
- Create effective figures.
- Select visualization types that support a clear analytical narrative.
- Explore relationships between sustainability indicators.
- Build simple interactive dashboards.
- Critically evaluate the strengths and limitations of data visualizations.

---

## Repository Contents

### `DVWs_notebook1_THC01_2627_v1_2.ipynb`

**Introduction to Data Visualization with Python**

Topics include:

- Introduction to dataset structure
- Loading Excel data into Python
- Basic data exploration
- Data cleaning and transformation
- Creating simple visualizations
- Visualization design principles
- Introduction to storytelling with data

This notebook serves as the foundation for subsequent dashboard development activities.

---

### `DVWs_notebook2_THC01_2627_v1_2.ipynb`

**Dashboard Development**

Topics include:

- Advanced figure construction
- Combining multiple visualizations
- Interactive visualization techniques
- Dashboard design principles
- Building simple sustainability dashboards using Plotly and Dash
- Data storytelling through dashboards

---

### `dataviz.xlsx`

Workshop dataset used throughout both notebooks.

The workbook contains sustainability-related indicators compiled from multiple international sources and is intended to support data visualization and dashboard construction exercises.

Worksheet names are intentionally preserved because they are referenced directly within the accompanying notebooks.

#### Worksheets

##### `EFP`

Ecological Footprint data (2023).

##### `HDI`

Human Development Index (HDI) data (2023).

##### `MF`

Material Footprint (Raw Material Consumption, RMC) data (2023).

##### `dataviz`

Integrated dataset combining variables from:

- Ecological Footprint (EFP)
- Human Development Index (HDI)
- Material Footprint (MF)

This worksheet serves as the primary dataset for workshop exercises and sustainability dashboard development.

##### `simpledataviz`

Simplified dataset derived from:

- EFP
- MF

This worksheet is intended for introductory visualization exercises.

##### `EU MF`

European material footprint time-series data derived from the same source as the `MF` worksheet.

---

## Software Requirements

The workshop materials were developed using:

- Python
- NumPy
- Plotly
- Dash
- Jupyter Notebook

---

## Workshop Structure

The materials are intended for a single full-day workshop session.

Recommended workflow:

1. Open and complete `DVWs_notebook1_THC01_2627_v1_2.ipynb`
2. Explore the structure and contents of `dataviz.xlsx`
3. Develop visualizations using the provided exercises
4. Continue to `DVWs_notebook2_THC01_2627_v1_2.ipynb`
5. Build an interactive sustainability dashboard

---

## Data Sources

### Ecological Footprint

Lo, K., Basnet, N., Miller, E., Van Berkum, J. L., Srikanthalingam, B., Foley, B., Long, A., Toneva, P. D., Ermina, M., & Klinkenberg, C. (2026). National Ecological Footprint and Biocapacity Accounts, 2026 Edition (1961-2025), Results and Metadata Version 1.0. Produced for the Footprint Data Foundation by researchers at York University and the University of Iceland. Available at https://fodafo.org/data/

### Material Footprint (RMC)

Eurostat. (2026). Material Footprint (Raw Material Consumption), dataset sdg_12_21. European Commission. DOI: 10.2908/sdg_12_21. Available at: https://ec.europa.eu/eurostat/databrowser/view/sdg_12_21/default/table?lang=en

### Human Development Index (HDI)

United Nations Development Programme (UNDP). (2025). Human Development Index (HDI) Dataset. Human Development Report Office. Available at: https://hdr.undp.org/data-center/human-development-index

---

## Reuse and Adaptation

These materials were created to support teaching and learning within the Governance of Sustainability Master's programme at Leiden University.

Educators are encouraged to adapt, modify, and extend these materials for their own teaching activities, provided appropriate attribution is given.

---

## Citation

If you use these notebooks, the accompanying Excel workbook, or derivative teaching materials, please cite:

> Logan, H.M. (2026). *Data Visualization Workshop – Thematic Course 1. Governance of Sustainability, Master's Programme, 2026–2027*. Leiden University, Leiden, The Netherlands.

---

## License

This repository is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** License.

You are free to:

- Share
- Copy
- Redistribute
- Adapt
- Remix
- Build upon the material

for any purpose, provided appropriate attribution is given.

For full license details see:

<https://creativecommons.org/licenses/by/4.0/>

Users should independently verify any licensing requirements associated with the original data sources.

---

## AI Use Statement

Generative AI tools were not used to create the educational content, exercises, analyses, or visualizations contained in these workshop materials.

AI-assisted tools were used solely during software development to support debugging and troubleshooting of Python code.

Responsibility for all instructional content, code, documentation, and educational design remains with the author.

Generative AI was also used to assist in drafting repository documentation and README materials. Final review, editing, and approval of all documentation were completed by H.M.Logan.

---

## Contact

For questions regarding these materials, please contact the heathmlogan through GitHub.

---
