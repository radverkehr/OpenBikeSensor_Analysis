# OpenBikeSensor_Analysis

Verschiedene Analyseskripte für [OpenBikeSensor](https://www.openbikesensor.org/) Daten.



#### Public Data

Auf den jeweiligen [Portalen](https://forum.openbikesensor.org/t/uebersicht-verfuegbarer-portale/688) stehen die anonymisierte Messdaten zur Verfügung

###### Code

- [Generelle Übersicht und zeitabhängige Analyse](https://nbviewer.org/github/radverkehr/OpenBikeSensor_Analysis/blob/gh-pages/code/publicdata_analysis/obs_publicData_overview_v03.ipynb)
- [Zusammenhang von Messwert nach links und rechts](https://nbviewer.org/github/radverkehr/OpenBikeSensor_Analysis/blob/gh-pages/code/publicdata_analysis/obs_publicData_leftRight_v03.ipynb) 
- [Verknüpfung und Analyse der OBS Daten mit OpenStreetMap Attributen](https://nbviewer.org/github/radverkehr/OpenBikeSensor_Analysis/blob/gh-pages/code/publicdata_analysis/obs_publicData_OSM_analysis_Germany_v03.ipynb)





#### Raw Data

Erste Schritte bei der Aufbereitung und Darstellung der Sensorsdaten aus dem OpenBikeSensor-Projekt [1].

Diese Analyse dient insbesondere zur Validierung der Daten/Geräte. Mittelfristig werden die Daten vermutlich im zentralen OBS-Portal [2], welches aktuell noch im Aufbau ist, dargestellt.  

###### Code

https://github.com/radverkehr/OpenBikeSensor_Analysis/blob/gh-pages/code/OBSanalysis_v03.ipynb

###### Viz

Um ein Gefühl für die Outputdaten zu bekommen, sind hier die Tracks einer Fahrt visualisiert, sofern der OBS links einen Messwert erfasst hat (layer: ueberholdaten_left_kontinuierlich). Diese Daten sind nur zu Validierungszwecken (und in Abstimmung mit dem Probanden) dargestellt. Für die Analyse sind nur bestätigte Überholvorgänge (layer: ueberholdaten_left) relevant.

current version: https://radverkehr.github.io/OpenBikeSensor_Analysis/viz/OBSanalysis_validation_v04.html

###### Quellen:

[1] https://www.openbikesensor.org/

[2] https://portal.openbikesensor.org/