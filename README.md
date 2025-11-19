# Interactive LNP-stabilized Pickering Emulsions Data Explorer

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17648662.svg)](https://doi.org/10.5281/zenodo.17648662)

This repository contains the source code and curated dataset for the "Interactive LNP-stabilized Pickering Emulsions Data Explorer," a web-based tool designed to help researchers visualize and explore the scientific literature in the field of lignin nanoparticle-stabilized emulsions.

This work was developed by Ronald Marquez, Roberto J. Aguado, Quim Tarrés, Laura Tolosa, Blaise L. Tardy, Orlando J. Rojas, Martin A. Hubbe, and Marc Delgado Aguilar, and accompanies the critical review **Lignin Nanoparticles as Pickering Stabilizers: Emulsion Engineering through Physicochemical Design**.

## How to use

### Online (Recommended)

The easiest way to use the tool is to visit the live demo link: [https://marquezrn03.github.io/LNP-Pickering-Emulsions-Explorer/](https://marquezrn03.github.io/LNP-Pickering-Emulsions-Explorer/)

## The Dataset

The dataset was manually curated from peer-reviewed scientific articles and is embedded as a JSON object within the `index.html` file. It includes parameters such as:
* Lignin type (Kraft, Alkali, Organosolv, pH fractionated, etc.)
* Chemical modifications (Acetylation, Cationization, Sulfonation, Polymer-grafting, etc.)
* Particle properties (Size in nm, Zeta potential in mV)
* Formulation parameters (Oil type, Lignin concentration, pH)
* Emulsion outcomes (Droplet size and stability/lifetime of emulsions)

The data itself is licensed under a **Creative Commons Attribution 4.0 International License (CC BY 4.0)**. You are free to share and adapt the data for any purpose, provided you give appropriate credit.

---

## 📖 Project overview

Pickering emulsions stabilized by lignin nanoparticles (LNPs) represent a sustainable frontier in material science. However, the broad applicability of these systems depends on understanding complex physicochemical interactions. This tool supports a systematic review that examines key parameters influencing formation, stability, and properties.

It provides an interactive interface to a database manually curated from the literature. Researchers, students, and industry professionals can use this platform to:
* Identify trends and correlations in the existing data (e.g., effect of zeta potential on stability).
* Discover knowledge gaps for future research.
* Accelerate the design and development of new emulsion-based applications in agriculture, food, and energy.

![Screenshot of the Data Explorer](https://i.imgur.com/fwioHll.png)

## Key features

* **Interactive scatter plot:** Dynamically explore the relationship between any two numerical variables from the dataset. Data points can be colored by category (e.g., Lignin Type) and filtered to isolate subsets of interest.
* **Droplet size distribution analysis:** Compare emulsion droplet sizes across different categorical groups using box plots.
* **Correlation matrix:** A heatmap that visualizes the Pearson correlation coefficients between all numerical parameters in the database.
* **Direct article linking:** Click on any data point in the scatter plot to open the original scientific article via its DOI.
* **CSV Data download:** The complete, curated dataset is available for download as a CSV file directly from the user interface.

## 🛠️ Technology stack

* **Frontend:** HTML5, Tailwind CSS
* **Data Visualization:** Plotly.js
* **Logic:** Vanilla JavaScript

## ✍️ How to Cite

If you use this software or its dataset in your research, please cite it. This ensures that the work is properly credited and helps others find the tool.

#### Citing the Software/Tool:

#### BibTeX Entry:

```bibtex
@software{marquez_2025_lnp_explorer,
  author       = {Marquez, Ronald and
                  Aguado, Roberto J. and
                  Tarrés, Quim and
                  Tolosa, Laura and
                  Tardy, Blaise L. and
                  Rojas, Orlando J. and
                  Hubbe, Martin A. and
                  Delgado Aguilar, Marc},
  title        = {{Interactive LNP-stabilized Pickering Emulsions Data Explorer}},
  month        = jul,
  year         = 2025,
  publisher    = {Zenodo},
  version      = {v1.0.0},
  doi          = {10.5281/zenodo.XXXXXX},
  url          = {[https://doi.org/10.5281/zenodo.XXXXXX](https://doi.org/10.5281/zenodo.XXXXXX)}
}

📜 License
The source code of this project is licensed under the MIT License.
