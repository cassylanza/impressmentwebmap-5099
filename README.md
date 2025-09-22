# impressmentwebmap-5099
# Mapping Freedom: Impressment Web Map (Second Iteration)

This repository contains the second complete iteration of the *Mapping Freedom* research web map (also the first interactive QGIS web map) by Cassandra Lanza. 
The map visualizes reasons given by enslavers in Mississippi for opposition to impressment during the Civil War era, overlaid on a basemap 
showing the concentration of slaveholding families (with 50-99 enslaved persons) in 1860.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [Data & Sources](#data--sources)  
4. [Repository Structure](#repository-structure)  
5. [Usage](#usage)  
6. [Development](#development)  
7. [Credits](#credits)  
8. [Contact](#contact)  

---

## Project Overview

- Part of the *Mapping Freedom REU 2024* project.  
- Explores patterns in letters from the **Civil War & Reconstruction Governors of Mississippi (CWRGM)** project that discuss **impressment**, particularly how enslavers opposed it.  
- The map uses a base layer showing the 1860 distribution of slaveholding families in Mississippi owning **50-99 enslaved persons**.  
- Interactive points link to source documents and highlight the geographic spread of opposition.  

Learn more about the program here: [Mapping Freedom 2024](https://www.mappingfreedomreu.org/)
Learn more about my individual project here: [Deliverables and Blog](https://cassalanza.wixsite.com/mappingfreedom2024)

---

## Features

- **Interactive map**: click on points to view linked primary source documents.  
- **Color-coded points**: represent different reasons for opposition to impressment.  
- **Historical basemap**: county-level data of slaveholding families (50–99 enslaved persons) in 1860.  
- **54 mapped sources**: each geolocated and connected to a corresponding letter.  

---

## Data & Sources

- **Primary Sources**: Letters from the CWRGM archive that mention impressment.  
- **Basemap Data**: County-level slaveholding families (50–99 enslaved persons, 1860), provided by Bucknell GIS & Spatial Thinking.  
- **Coordinates**: Derived from locations cited in source letters.  
- **Tools**: QGIS for spatial processing; HTML, CSS, JavaScript for the web map.  

---

## Repository Structure
```
impressmentwebmap-5099/
│
├── index.html # Main web page for the interactive map
├── README.md # Project documentation (this file)
├── css/ # Stylesheets (map layout, legend, fonts, etc.)
├── js/ # JavaScript (map behavior, interactivity)
├── data/ # Spatial data (GeoJSON, attribute tables)
├── legend/ # Legend assets (images or HTML fragments)
└── webfonts/ # Custom fonts
```
---

## Usage

Visit: [Project Deliverables Page](https://cassalanza.wixsite.com/mappingfreedom2024/s-projects-basic)
OR
To view the map locally:

1. Clone or download this repository.  
2. Run a local HTTP server (browsers often block local JSON/GeoJSON loading). Example with Python:  
   ```bash
   python3 -m http.server 8000
3. Open http://localhost:8000/index.html in your browser.
4. Explore the interactive points and basemap.

---

## Development

- **Adding points**: Update the data files in data/ with new coordinates and metadata.
- **Basemap updates**: Replace/update county-level data and adjust styling in CSS/JS.
- **Customization**: Edit js/ for interactivity and css/ for styling.

---

## Credits

**Author**: Cassy Lanza
**Affiliation**: Mapping Freedom REU 2024
**Data Providers**: CWRGM Letters, Bucknell GIS & Spatial Thinking (slaveholding family data)

---

## Contact

For questions, feedback, or further information:
Author: Cassy Lanza
Project Website: [Mapping Freedom 2024](https://cassalanza.wixsite.com/mappingfreedom2024)
Research Draft: Relocation Reshaping Relationships: Impressment in Civil War Mississippi
