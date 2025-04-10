# Code 
Die Skripte wurden mit ArcGIS Pro 3.0.2 und Python 3.9.11 erstellt. Die Skripte können direkt mit der Python-Konsole von ArcGIS Pro oder einer anderen Python Umgebung geöffnet werden.
## Statistical Index (01_Statistical_Index.ipynb)
Berechnet den Statistical Index für jede Klasse jedes Eingangsparameters. In einem zweiten Schritt wird eine Gesamtgefährdung durch die Addition der SI-Werte für jedes Pixel berechnet. In einem letzten Schritt werden die Werte durch eine Min-Max-Normalisierung auf einen Wertebereich von 0 - 1 normiert. 
## Weighting Factor (02_Weighting_Faktor.ipynb)
Berechnet Gewichte für die einzelnen Parameter, welche bei der Summierung der SI-Werte berücksichtigt werden. In einem letzten Schritt werden die Werte durch eine Min-Max-Normalisierung auf einen Wertebereich von 0 - 1 normiert.
## Validierung (03_ROC.ipynb)
Die Ergebnisraster aus Schritt 1 und 2 wird mit den Hangrutschungen kombiniert und die Receiver Operating Characteristic (ROC) berechnet und dargestellt. Für eine quantitative Validierung wird außerdem die Area under the Curve (AUC) berechnet und ausgegeben. 
