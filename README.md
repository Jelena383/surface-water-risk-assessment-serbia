# Spatial Risk Assessment of Heavy Metal Pollution in Serbia’s Surface Waters Using an Integrated GIS–AHP Framework

This repository presents a GIS-based multicriteria spatial risk assessment framework developed for the evaluation of heavy metal pollution in surface waters across the Republic of Serbia.

The project integrates environmental monitoring data, Geographic Information Systems (GIS), multicriteria decision analysis (MCDA), Analytic Hierarchy Process (AHP), temporal trend analysis, and spatial statistics in order to identify locations with elevated environmental risk and detect significant spatial clustering patterns.

The framework was developed as part of a research study focused on transforming environmental monitoring data into spatial decision-support information for environmental risk interpretation and water resource management.

---

# Project Objective

The primary objective of the study was to develop an integrated spatial framework capable of evaluating multiple dimensions of heavy metal pollution risk within Serbia’s national surface water monitoring network.

The analysis aimed to:

- identify monitoring locations with elevated environmental risk,
- integrate heterogeneous environmental indicators into a unified spatial model,
- evaluate temporal pollution dynamics,
- detect statistically significant spatial clustering patterns,
- and support GIS-based environmental decision-making.

---

# Study Area and Monitoring Network

The analysis was based on data collected from 54 surface water monitoring locations distributed across the Republic of Serbia during the 2019–2023 period.

The monitoring network included rivers and water bodies influenced by different:

- industrial pressures,
- urban impacts,
- agricultural activities,
- hydrological conditions,
- and regional environmental characteristics.

The spatial distribution of monitoring locations enabled the assessment of both localized pollution patterns and broader regional environmental trends.

---

# Integrated GIS–AHP Methodology

The spatial risk assessment framework was developed through the integration of four complementary environmental risk indicators:

- Total Pollution Intensity (TPI),
- Bioavailability Indicator (BI),
- Temporal Trend Indicator (IT),
- and Regulatory Risk Indicator (RRI).

Each indicator represented a different dimension of environmental pressure associated with heavy metal pollution.

All indicators were normalized using min–max normalization and integrated into a final Integrated Risk Index (IIR) using the Analytic Hierarchy Process (AHP).

---

# Risk Indicators

## 1. Total Pollution Intensity (TPI)

The Total Pollution Intensity Index represents the cumulative intensity of heavy metal contamination at each monitoring location.

The indicator integrates concentrations of:

- cadmium (Cd),
- lead (Pb),
- and nickel (Ni),

allowing comparative evaluation of overall pollution burden across the monitoring network.

### TPI interpretation logic

- higher TPI → greater cumulative pollution pressure,
- lower TPI → reduced pollution intensity.

---

## 2. Bioavailability Indicator (BI)

The Bioavailability Indicator evaluates the dissolved fraction of heavy metals within the aquatic environment.

This indicator was included because dissolved metal fractions are more biologically available and potentially more ecologically harmful than total concentrations alone.

### BI interpretation logic

- higher dissolved fraction → greater ecological availability,
- increased potential biological impact,
- and elevated environmental sensitivity.

---

## 3. Temporal Trend Indicator (IT)

The Temporal Trend Indicator was derived using Theil–Sen trend analysis in order to evaluate long-term concentration dynamics during the 2019–2023 monitoring period.

The indicator enabled identification of:

- increasing pollution trends,
- decreasing pollution trends,
- and relatively stable environmental conditions.

### Temporal analysis significance

This component allowed the framework to move beyond static pollution assessment and incorporate temporal environmental behavior into the final spatial risk model.

---

## 4. Regulatory Risk Indicator (RRI)

The Regulatory Risk Indicator evaluates the frequency and severity of exceedances of regulatory threshold values for heavy metals.

The indicator represents the regulatory dimension of environmental risk and directly reflects compliance pressure within the monitoring network.

### RRI interpretation logic

- more frequent exceedances → higher regulatory risk,
- lower exceedance frequency → more favorable environmental status.

The analysis demonstrated that the Regulatory Risk Indicator had the dominant influence within the final integrated model.

---

# Analytic Hierarchy Process (AHP)

The relative importance of all indicators was evaluated using the Analytic Hierarchy Process (AHP).

Pairwise comparison matrices were developed in order to define the contribution of each environmental indicator within the final Integrated Risk Index.

The weighting process enabled systematic integration of multiple environmental dimensions into a unified multicriteria framework.

## Final AHP Weights

| Indicator | Weight |
|---|---|
| Regulatory Risk Indicator (RRI) | 52.2% |
| Total Pollution Intensity (TPI) | 20.1% |
| Bioavailability Indicator (BI) | 16.4% |
| Temporal Trend Indicator (IT) | 11.3% |

The weighting process demonstrated the dominant influence of regulatory exceedance frequency within the final integrated environmental risk model, emphasizing the importance of regulatory compliance pressure in spatial environmental assessment.

---

# Integrated Risk Index (IIR)

The final Integrated Risk Index (IIR) was generated through weighted integration of all normalized indicators.

The index represents a synthetic spatial indicator of environmental risk associated with heavy metal pollution.

### IIR interpretation

- lower IIR values → higher environmental risk,
- higher IIR values → lower environmental risk and more favorable environmental conditions.

Monitoring locations were classified into five environmental risk categories ranging from very high risk to very low risk.

---

# Spatial Statistical Analysis

Spatial clustering analysis was performed using:

# Getis-Ord Gi* hotspot analysis

in order to identify statistically significant spatial patterns of environmental risk.

Due to the definition of the Integrated Risk Index:

- statistically significant cold spots represent clusters of elevated environmental risk,
- while hot spots represent clusters of relatively favorable environmental conditions.

The analysis enabled identification of regional environmental risk concentrations rather than isolated monitoring anomalies.

---

# Key Findings

The study identified several spatially significant clusters of elevated environmental risk, particularly within northern parts of Serbia associated with long-term anthropogenic pressures.

The results demonstrated that:

- only a limited number of monitoring locations belonged to the highest-risk categories,
- while most monitoring locations showed relatively favorable environmental conditions,
- although several localized high-risk areas remained clearly distinguishable.

The analysis also demonstrated the methodological value of integrating:

- GIS,
- environmental monitoring data,
- MCDA,
- AHP,
- temporal trend analysis,
- and spatial statistics

within a unified environmental risk assessment framework.

---

# Software and Methods

## GIS and Spatial Analysis

- QGIS
- ArcGIS Pro
- Spatial interpolation
- Geospatial database organization
- Environmental cartography
- Spatial statistics
- Hotspot analysis

## Analytical Methods

- MCDA
- AHP
- Min–max normalization
- Theil–Sen trend analysis
- Getis-Ord Gi*
- Environmental risk modeling

---

# Repository Contents

- Integrated risk assessment maps
- Hotspot analysis maps
- Environmental monitoring visualizations
- Spatial analysis outputs
- Indicator ranking charts
- GIS cartographic layouts
- Spatial risk interpretation outputs

---

# Scientific and Practical Relevance

This repository demonstrates how GIS-based spatial intelligence approaches can support:

- environmental monitoring interpretation,
- multicriteria environmental risk assessment,
- spatial decision support,
- environmental management prioritization,
- and identification of critical environmental pressure zones.

The framework may also serve as a methodological basis for future GIS-based environmental monitoring studies integrating multicriteria analysis and spatial statistics.

---

# Contact

For additional methodological details, collaboration opportunities, or GIS-related research inquiries, feel free to connect with me on LinkedIn.

[LinkedIn Profile](https://linkedin.com/in/jelena-lukic-bb84232b5)

---

# Author

Jelena Lukić  
Environmental Monitoring Specialist | GIS & Spatial Analytics
