# lte-coverage-ambato-analysis
# Radio Coverage Analysis of a 4G Network in Ambato’s Center

## Submission ID
IEEE LATAM Manuscript Submission ID: [9922]

## Authors
- Bryan Manzano
- Robert Rodríguez
- David Moreno
- Jefferson Ribadeneira

## Afiliation:
- Facultad de Informática y Electrónica
- Escuela Superior Politécnica de Chimborazo (ESPOCH)
- Riobamba - Ecuador

## Project Overview
This repository contains the datasets, figures, and analysis files used in the article *"Radio Coverage Analysis of a 4G Network in Ambato’s Center"*, submitted to **IEEE Latin America Transactions**. The study evaluates LTE network performance in a dense urban area using field measurements and simulation data, with comparisons against Ecuador’s ARCOTEL quality standard.

## Repository Structure

- `/data/`:  
  Contains `.csv` files of RSRP measurements collected over **7 days** in **pedestrian and vehicular** scenarios.
  
- `/figures/`:  
  Contains field photographs of the transmission stations used as input for simulation tools.

- `Radiobases coordenadas.xlsx`:  
  Contains geographic coordinates of all base stations (latitude, longitude, height, azimuth, and power). Used for configuring the LTE simulation environment.

- `Average RSRP.xlsx`:  
  Includes average RSRP values per street and scenario (pedestrian and vehicular), as used in the statistical analysis.

- `Average ARCOTEL.xlsx`:  
  Presents compliance comparison between measured RSRP values and ARCOTEL’s regulatory threshold (≥ −100 dBm, 95% coverage).

- `Analysis RSRP.xlsx`:  
  Contains statistical processing and classification of RSRP data (Excellent, Good, Fair, Poor) following 3GPP TR 36.942 categories. Includes summary tables and histograms.

## Requirements

- Microsoft Excel (or LibreOffice)  
- (Optional) Python or MATLAB if you plan to replicate figures programmatically.

## Reproducibility

To reproduce the results presented in the article:

1. Review the `.xlsx` files for:
   - Measurement averages
   - Regulatory compliance
   - Statistical classification

2. Use the coordinate data (`Radiobases coordenadas.xlsx`) to replicate the LTE simulation in a propagation software (COST-231 Hata model).

3. Figures used in the paper can be generated using data from `/figures/` and processed tables in `Analysis RSRP.xlsx`.

# Contact

For more information or questions regarding this dataset, please contact:  
📩 robert.rodriguez@espoch.edu.ec


