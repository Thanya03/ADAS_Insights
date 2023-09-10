# ADAS_Insights
---
This Repository contains Python scripts written to analyse and find Insights and Patterns from the Mobility dataset presented by **Intel Unnati Challenge**.

The Mobility dataset is based on the alerts produced from the **ADAS system** attached to 5 different vehicles for time span of 30 days.

---
#### Contents
```
This repo contains three IPYNB files of different level of analysis and geographical visualization of the data
```
- Insights_1.ipynb
- Insights_2.ipynb
- Insights_3.ipynb
- Geo - Viz
---

## Insights_1.ipynb
This python notebook contains-
- Global analysis of the data to obtain swallow insights such as
  - The highest recorded alert
  - The vehicle that recorded the highest alert
- Filtered the data based on the vehicle code using the geo-spatial tool [Kepler GL](https://kepler.gl/) to analyse the data on the basis of the vehicle
- Further filtered the data based on the time when most of records are produced.
---

## Insights_2.ipynb
This python notebook contains - 
- Analysis of the data to find pattern between the occurence of different alerts by correlating eachother.
- Analyse and study about the anomaly exhibited by the vehicle code 1995 is conducted.
- Identification of Medical centres near the black spots (locations which are more prone to accidents) located using the visualizations from the geo-spatial tool [Kepler GL](https://kepler.gl/)
---

## Insights_3.ipynb
This python notebook contains - 
- Analysis on the distribution of the alerts over different days and time and produce insights on the observed variations.
- Statistical Testing `ANOVA` is conducted between the alerts and the vehicle types.
- The relation between the speed and the alerts are analyzed.
- Analysis on the Accident prone areas and driver behaviour based on the alerts is conducted.
---

## Geo - Viz
This folder contains the Geograhical visualization of the data at different levels such as -
- Complete data
- Data filtered based on the vehicle type
- Data filtered based on the rush hours

