# Premier-League

![2023-02-04_22h36_39](https://user-images.githubusercontent.com/18030121/216790586-91de0cdb-e93e-4717-a852-b4c97ef11fb9.png)


 

In diesem Blog möchte ich einen  Einblick auf mein Projekt verschaffen. In diesem Projekt werde ich mehrere überwachte Algorithmen testen, um die Rangliste von  Fußballmannschaften  aus der Premier League Anhang ihrer Kader vorhersagen. Ich werde den besten Kandidatenalgorithmus aus vorläufigen Ergebnissen auswählen und diesen Algorithmus weiter optimieren, um die Aufgabe zu lösen. Dabei werde ich die besten Features auswählen und die Hyperparameter  optimieren. 

Die Datensets beinhalten Daten aus dem Jahr 2003 bis 2021. Aus diesen Datensets wurden zwei Dateien erzeugt. Eine Datei über die Mannschaften aus der League und eine andere über die Kader.

Die Daten stammen  aus der  Website  https://footystats.org/download-stats-csv.  FootyStats ist eine Website für Fußballstatistiken und Analysen mit Datenabdeckung in über 1500 Fußballligen weltweit, einschließlich Großbritannien, Europa und Südamerika.

Ziel:

●  Beratung der technischen Abteilung bei der  Rekrutierung von neuen Spielern sowie die Aufstellungen der Mannschaft. 

● Mit den historische Daten von Spielern und der Klassifikation der Mannschaften in der Premier League wird ein Algorithmus entwickeln, der bestimmt, mit welcher Wahrscheinlichkeit eine bestimmte Position  in der  Premier Liga  mit den aktuell Kader erreicht werden kann.

● Definieren, welche  Eingenschaften der Kader die Mannschaftsplatzierung in der Premier League beeinflussen.
 
Lösung:

● Es handelt sich um ein klassifikationsproblem mit Ziel-Variable. Es gibt die Option mit überwachtem Lernen an Modellen zu arbeiten.

● Es wurden verschiedene Modelle getestet. Logistik Regression, Random Forest,  DecisionTreeClassifier, SVC und AdaBoostClassifier.

● Das Projekt wird in der Programmiersprache Python entwickelt.      






















 [![author](https://img.shields.io/badge/author-wildt-red.svg)](https://www.linkedin.com/in/carlosfab) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/carlosfab/data_science/issues)

<p align="center">
  <img src="ogteaser.jpg">
</p> 

# Alexandre Wildt Graziani 
<sub>*Lead Data Scientist*</sub>


Airbnb hat erfolgreich die traditionelle Hotelbranche gestört, da immer mehr Reisende sich entscheiden, Airbnb als ihren Hauptunterkunftsanbieter zu nutzen. Seit seinem Beginn im Jahr 2008 hat Airbnb ein enormes Wachstum verzeichnet, wobei die Anzahl der auf seiner Website gelisteten Mietobjekte jedes Jahr exponentiell zunimmt. In Deutschland ist keine Stadt beliebter als Berlin. Das bedeutet, dass Berlin einer der heißesten Märkte für Airbnb in Europa ist, mit über 9060 Angeboten im Januar 2021.

Die Analyse von Tausenden von Anzeigen, die über Airbnb bereitgestellt werden, ist ein entscheidender Faktor für das Unternehmen. Unser Hauptziel ist es, die wichtigsten Metriken zu ermitteln, die die Auflistung von Immobilien auf der Plattform beeinflussen. Zu diesem Zweck werden wir den Airbnb-Datensatz in Berlin mithilfe grundlegender Techniken der explorativen Datenanalyse (EDA) erkunden und visualisieren. Wir haben die Verteilung jeder Airbnb-Anzeige basierend auf ihrer Lage, einschließlich Preisbereich, Zimmertyp, Anzeigenname und anderen relevanten Faktoren, entdeckt. Wir haben diesen Datensatz aus verschiedenen Blickwinkeln analysiert und interessante Erkenntnisse gewonnen. Dies kann dem Marketingteam, dem Finanzteam und dem technischen Team von Airbnb bei datenbasierten strategischen Entscheidungen helfen.

**Links:**
* [Notebook](https://nbviewer.org/github/awildt01/Airbnb_Berlin-/blob/main/Airbnb_%28Berlin%29.ipynb)
* [Medium](https://medium.com/@alexandrewildtgraziani/analyse-der-airbnb-berlin-b002125a56f9)
* [Blog](https://sigmoidal.ai)

### Beschaffung der Daten
Alle hier verwendeten Daten wurden von der Website Inside Airbnb bezogen.

Für diese anfängliche explorative Analyse wird nur die folgende Datei heruntergeladen:

- listings.csv - Zusammenfassende Informationen und Metriken für Angebote in Berlin (geeignet für Visualisierungen).
Wichtig:  Die Website entwickelt sich ständig weiter, und es kann sein, dass zu einem bestimmten Zeitpunkt der genaue Datensatz, der in diesem Notebook verwendet wird, nicht mehr verfügbar ist, was unseren Code beeinträchtigen würde


### Projekt 

Das Ziel das Projekt ist eine explorative Datenanalyse (EDA) durchzuführen. Wir werden die ersten Einblick in der Daten erhalten, Muster identifizieren und Hypothesen aufstellen.
Die folgenden schritt werden in der Analyse durch durchgeführt

1. Data Laden 

2. Datenüberblick: Ersten Blick auf die Daten, um deren Struktur und Größe zu verstehen. Anzeigen der ersten Zeilen, Spaltennamen und Datentypen.

3. Datenbereinigung: Identifizieren und behandeln von fehlende Werte, Dubletten oder Ausreißer.

4. Deskriptive Statistiken: Berechnung grundlegender statistischer Maße wie Durchschnitt, Median, Standardabweichung und Quartile, um ein besseres Verständnis der Verteilung der Daten zu erhalten.
  
5. Datenvisualisierung: Erstellung vom Diagramme, Grafiken und Plots, um die Verteilung und Beziehungen zwischen den Variablen zu visualisieren.

6. Korrelationsanalyse: Untersuchung von Korrelationen zwischen verschiedenen Variablen, um festzustellen, ob starke Beziehungen vorhanden sind.

7. Hypothesenbildung: Auf der Grundlage von Beobachtungen und Analysen werden angenommen, wie verschiedene Faktoren miteinander in Beziehung stehen






### Analysis 


Folgende Fragen werde ich durch der Analyse  beantworten:

+ Die ursprüngliche Idee von Airbnb bestand darin, ein Zimmer oder ein Mehrbettzimmer im eigenen Zuhause anzubieten. Ist das immer noch so?
+ Welche Art von Immobilien wird auf Airbnb am häufigsten vermietet?
+ Sind die Angebote gleichmäßig über die Stadtteile verteilt oder gibt es Hotspots?
+ Welcher Viertel ist im Datensatz am teuersten?
+ Was ist der Durchschnittspreis für Mieten?
+ Welcher Host hat die meisten Anzeigen?
+ Was ist der Durchschnitt der Mindestaufenthaltsdauer für Mietwohnungen (minimum_nights)?
+ Sind Immobilien im Besitz einzelner Nutzer oder gibt es Nutzer mit mehreren Mietobjekten (d. h. potenziell für Spekulationen)?


**Background in:** Python, Machine Learning and Mathematical Optimisation.





### Insight


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

