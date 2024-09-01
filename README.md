# Premier-League

![2023-02-04_22h36_39](https://user-images.githubusercontent.com/18030121/216790586-91de0cdb-e93e-4717-a852-b4c97ef11fb9.png)


 [![author](https://img.shields.io/badge/author-wildt-red.svg)](https://www.linkedin.com/in/carlosfab) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/carlosfab/data_science/issues)


# Alexandre Wildt Graziani 
<sub>*Lead Data Scientist*</sub>

In diesem Projekt wurde ein Algorithmus entwickelt, um die mögliche Endplatzierung der Teams in einem Meisterschaftsturnier basierend auf deren Kaderzusammensetzung vorherzusagen. Unser Ziel ist es, die Platzierungen der Teams von Rang 1 bis Rang 20 in der Premier League zu prognostizieren. Dafür nutzen wir verschiedene Spielerattribute, wie Körpergröße, Gewicht, Nationalität, Anzahl der Tore, Vorlagen und Torwartparaden. Darüber hinaus analysieren wir, welche Kadermerkmale den größten Einfluss auf die Platzierung in der Meisterschaft haben.

Die Idee ist dass Mann nicht einzelner Spieler bewertete sondern eine Zentral Wert die repräsentiert eine Eigenschaften der gesamt Kaders. BZ Median von Gewicht , Alter und Grösser. Ich gehe davon aus, dass die Eigenschaften der gesamten Mannschaft wichtiger sind, um eine bessere Klassifikation zu erreichen, als die individuellen Merkmale einzelner Spieler.

**Links:**
* [Notebook](https://github.com/awildt01/Premier-League/blob/main/notebook/5.premier-model-final.ipynb)
* [Medium](https://medium.com/@alexandrewildtgraziani/premier-league-rangliste-von-fu%C3%9Fballmannschaften-vorhersagen-a23ee26f63bc)
* [Blog](https://sigmoidal.ai)

### Beschaffung der Daten:
Die Datensätze umfassen Informationen aus den Jahren 2003 bis 2021. Aus diesen Daten wurden zwei separate Dateien erstellt: eine, die sich auf die Mannschaften in der Liga konzentriert, und eine weitere, die sich auf die Kaderzusammensetzungen bezieht. Die Daten stammen von der Website footystats.org, einer Plattform, die umfassende Fußballstatistiken und -analysen für über 1.500 Fußballligen weltweit bereitstellt.

Die Daten stammen von der Website [footystats.org](https://footystats.org/de/england/premier-league) footystats.org. FootyStats ist eine Website für Fußballstatistiken und Analysen mit Datenabdeckung in über 1500 Fußballligen weltweit.

- daten_league.csv - Zusammenfassende Informationen und Kennzahlen einer Datei über die Mannschaften der Liga, einschließlich Tabellenplatzierung, Vereinsname, Anzahl der absolvierten Spiele, Anzahl der Siege und erzielten Tore etc.

  
- daten_squad.csv -  Zusammenfassende Informationen und Kennzahlen einer Datei über die Kader, einschließlich Spielername, Alter, Gewicht Größer Nationalität, Anzahl von Spielen etc.




### Projekt:

Ein Data-Science-Projekt durchläuft typischerweise mehrere Phasen, um aus Rohdaten ein verwertbares Modell oder eine aussagekräftige Analyse zu entwickeln. In diesem Projekt wurden diese Phasen mehrfach wiederholt. Beim ersten Durchlauf konnten keine zufriedenstellenden Ergebnisse erzielt werden, da die gewählten Features nicht geeignet waren, um brauchbare Resultate zu liefern. Um das Problem zu beheben, wurde die Datenaufbereitung für das Modell erneut durchgeführt, wobei neue Features ausgewählt und angepasst wurden, die das Modell besser unterstützen könnten. In diesem Projekt wurden die folgenden Phasen durchlaufen.

**1. Problem Definition**

- Zielsetzung: Klare Definition des Problems, das gelöst werden soll. Dies umfasst die Identifikation der Geschäftsanforderungen und das Festlegen der zu erreichenden Ziele.
- Erfolgskriterien: Festlegung von Kriterien, anhand derer der Erfolg des Projekts gemessen wird.

**2. Datenbeschaffung**

- Datenquellen identifizieren: Welche Daten sind erforderlich und woher können sie bezogen werden?
- Datenakquise: Extraktion der benötigten Daten aus den identifizierten Quellen.
- Datenzugang sichern: Sicherstellen, dass der Zugang zu den benötigten Datenquellen gegeben ist.

**3. Datenaufbereitung**

- Datenbereinigung: Entfernen von Rauschen, Duplikaten und Inkonsistenzen, Umgang mit fehlenden Werten und Outliers.
- Datenintegration: Zusammenführen von Daten aus verschiedenen Quellen und Formaten.
- Feature Engineering: Erstellen neuer Merkmale (Features) aus den vorhandenen Daten, um die Leistung des Modells zu verbessern.
- Datenformatierung: Vorbereitung der Daten für die Modellierung (Skalierung, Normalisierung, One-Hot-Encoding).

**4. Explorative Datenanalyse (EDA)**

- Datenvisualisierung: Verwendung von Diagrammen und Plots, um die Verteilungen, Zusammenhänge und Muster in den Daten zu verstehen.
- Statistische Analyse: Durchführung von Hypothesentests und Korrelationsanalysen, um tiefere Einblicke in die Daten zu gewinnen.

**5. Modellierung**

- Modellauswahl: Auswahl geeigneter Algorithmen basierend auf dem Problemtyp (z.B. Klassifikation, Regression).
- Modelltraining: Anpassung des Modells an die Trainingsdaten.
- Hyperparameter-Tuning: Feinabstimmung der Modellparameter, um die Leistung zu optimieren.
- Cross-Validation: Überprüfung der Modellleistung durch Aufteilung der Daten in Trainings- und Validierungssets.

**6. Evaluierung**

- Modellbewertung: Messung der Modellleistung anhand verschiedener Metriken wie Genauigkeit, Präzision, Recall, F1-Score etc.
- Modellvergleich: Vergleich der Leistung verschiedener Modelle und Auswahl des besten Modells.
- Überprüfung auf Überanpassung (Overfitting): Sicherstellen, dass das Modell gut generalisiert und nicht nur auf den Trainingsdaten gut abschneidet.

**7. Interpretation und Kommunikation**

- Modellergebnisse interpretieren: Ableitung von Erkenntnissen und Geschäftsempfehlungen basierend auf den Modellvorhersagen.
- Ergebnisse kommunizieren: Präsentation der Ergebnisse an Stakeholder in verständlicher Form, oft unterstützt durch Visualisierungen und Berichte.





### Ziel:

●  Beratung der technischen Abteilung bei der  Rekrutierung von neuen Spielern sowie die Aufstellungen der Mannschaft. 

● Mit den historische Daten von Spielern und der Klassifikation der Mannschaften in der Premier League wird ein Algorithmus entwickeln, der bestimmt, mit welcher Wahrscheinlichkeit eine bestimmte Position  in der  Premier Liga  mit den aktuell Kader erreicht werden kann.

● Definieren, welche  Eingenschaften der Kader die Mannschaftsplatzierung in der Premier League beeinflussen.


**Background in:** Python, Machine Learning and Mathematical Optimisation.




### Projetos:
Veja os tutoriais publicados do Sigmoidal:

* **Visualisierung von Daten aus der Fußball-Bundesliga 2011-2012:** http://bit.ly/3Smgnsn
* **Como Implementar Regressão Linear com Python:** https://bit.ly/2Li5pzY
* **Data Science: Investigando o naufrágio do Titanic:** https://bit.ly/2Ubr5SH
* **Como Tratar Dados Ausentes com Pandas:** https://bit.ly/31KWSMN
* **XGBoost: aprenda este algoritmo de Machine Learning em Python:** https://bit.ly/2UbRhws
* **Como criar uma Wordcloud em Python:** https://bit.ly/2OxsphM
* **Como lidar com dados desbalanceados:** https://bit.ly/2ZlaNsV

---

