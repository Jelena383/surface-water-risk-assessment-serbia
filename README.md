# Spatial Risk Assessment of Heavy Metal Pollution in Serbia’s Surface Waters Using an Integrated GIS–AHP Framework

This repository presents a GIS-based multicriteria spatial risk assessment framework developed for the evaluation of heavy metal pollution in surface waters across the Republic of Serbia.

The project integrates environmental monitoring data, Geographic Information Systems (GIS), multicriteria decision analysis (MCDA), Analytic Hierarchy Process (AHP), and spatial statistics in order to identify locations with elevated environmental risk and detect significant spatial clustering patterns.

The framework was developed as part of a Master’s research project focused on transforming environmental monitoring data into spatial decision-support information for environmental risk interpretation and water resource management.

## Project Overview

The analysis was based on data from 54 surface water monitoring locations distributed across Serbia during the 2019–2023 period.

The study integrates multiple dimensions of environmental risk associated with heavy metal pollution, including:

- pollution intensity,
- metal bioavailability,
- temporal concentration trends,
- regulatory exceedance frequency,
- and spatial clustering behavior.

The workflow was designed to support:

- spatial identification of high-risk monitoring locations,
- interpretation of regional pollution patterns,
- multicriteria environmental assessment,
- and GIS-based environmental decision support.

## Integrated GIS–AHP Methodology

The spatial risk assessment framework integrates four complementary environmental risk indicators:

### Risk Indicators

- **TPI – Total Pollution Intensity Index**  
  Relative indicator of cumulative heavy metal pollution intensity.

- **BI – Bioavailability Index**  
  Indicator of potential ecological pressure based on dissolved metal fractions.

- **IT – Temporal Trend Index**  
  Indicator derived from Theil–Sen trend analysis used to evaluate temporal dynamics of heavy metal concentrations.

- **RRI – Regulatory Risk Index**  
  Indicator based on the frequency and severity of exceedances of regulatory threshold values.

All indicators were normalized using min–max normalization and integrated into a final:

## Integrated Risk Index (IIR)

using the Analytic Hierarchy Process (AHP).

## Spatial Statistical Analysis

Spatial clustering analysis was performed using:

## Getis-Ord Gi* hotspot analysis

to identify statistically significant spatial clusters of elevated and reduced environmental risk.

Due to the definition of the Integrated Risk Index:

- lower IIR values indicate higher environmental risk,
- therefore statistically significant cold spots represent clusters of elevated environmental risk,
- while hot spots represent areas of relatively favorable environmental conditions.

## Key Findings

The analysis identified spatially significant clusters of elevated environmental risk, particularly within northern parts of Serbia associated with long-term anthropogenic pressures.

The results demonstrated that:

- only a limited number of monitoring locations belonged to the highest-risk categories,
- while most locations showed relatively favorable environmental conditions,
- although several localized high-risk areas remained clearly distinguishable.

The study also demonstrated the methodological value of integrating:

- GIS,
- MCDA,
- AHP,
- environmental monitoring data,
- and spatial statistics

within a unified environmental risk assessment framework.

## Software and Methods

### GIS and Spatial Analysis

- QGIS
- ArcGIS Pro
- Spatial interpolation
- Geospatial database organization
- Thematic environmental mapping

### Statistical and Analytical Methods

- MCDA
- AHP
- Min–max normalization
- Theil–Sen trend analysis
- Getis-Ord Gi*
- Spatial cluster analysis

## Repository Contents

- GIS project files
- Environmental monitoring datasets
- Spatial analysis outputs
- Integrated risk assessment maps
- Hotspot analysis maps
- Methodological documentation
- Cartographic visualizations

## Scientific and Practical Relevance

This repository demonstrates how GIS-based spatial intelligence approaches can support:

- environmental monitoring interpretation,
- multicriteria environmental risk assessment,
- spatial decision support,
- and identification of priority monitoring and management areas.

The framework may also serve as a methodological basis for future environmental monitoring studies integrating spatial statistics and multicriteria analysis.

## Author

Jelena Lukić  
Environmental Monitoring Specialist | GIS & Spatial Analytics
