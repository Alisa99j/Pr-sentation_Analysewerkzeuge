# Einführung 

Dieses Projekt beschäftigt sich mit den 100 beliebstesten Filmen von 2003 bis 2022. Es werden unterschiedliche Aspekte untersucht, welche anbei aufgeführt sind. Das Ziel dieses Projekts ist zu erkennen was einen Film populär macht. Dieses Ziel wird anhand von explorativer Datenanalyse erreicht werden. 

Verwendet wurde folgender Datensatz: Top 100 popular movies from 2003 to 2022 


# Informationen zum Datensatz
Das Datenset enthält die meisten 100 beliebten Filme für jedes Jahr im Zeitraum 2003-2022.
Jede einzelne Information wurde durch Web-Scraping gesammelt und ist auf iMDB zu finden.

Das Datenset enthält:

•	Titel
•	Bewertung
•	Jahr 
•	Monat
•	Zertifikat
•	Laufzeit
•	Regisseur/e
•	Stars
•	Genre/s
•	Drehort
•	Budget 
•	Einnahmen
•	Herkunftsland


# Rohdaten des Datensatzes

Die fehlenden Werte im Datensatz wurden entfernt

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/90e081b1-0c9a-4f1c-b11b-9d921c99630c)

•	Insgesamt gibt es 1965 Zeilen im Datensatz
•	Jede der 13 Spalten hat 1965 Nicht-Null-Werte.
•	Es gibt eine Spalte mit numerischen Daten (Dtype: float64), eine Spalte mit ganzzahligen Daten (Dtype: int64) und elf Spalten mit Objekten (Dtype: object).

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/94605448-30af-448c-a047-2b2567c9aa0b)

# Packages 
Das Projekt verwendet folgende Pakete: 
pandas: Zur Datenverarbeitung
black: Für die Code-Formatierung 

pandas 1.2.3 : zur Datenverarbeitung

numpy 1.24.3 : für Berechnungen

matplotlib 3.7.1 : für statistische Visualisierungen

seaborn 0.12.2: besonders gut geeignet für die Visualisierung von komplexen Datensätzen und unterstützt verschiedene Plottypen

black 22.3.0 : für die Code-Formatierung

sklearn 1.3.0 : für Regressionsanalyse 


# Welche Top-10 Genres sind am häufigsten in der Auswahl der Top-100-Filme pro Jahr vertreten?

Warum ist das wichtig? 
Die Identifikation beliebter Genres gibt Einblicke in Marktpräferenzen und hilft bei Entscheidungen über das Filmangebot.
Wirtschaftlicher Nutzen der Beantwortung dieser Frage: Investitionen in beliebte Genres können durchgeführt werden was dazu führt, dass sich die Einnahmen steigern. 

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/e3c73e2f-2ec8-4dee-9a37-248cbbe19f02)

Dieses Diagramm zeigt die zehn häufigsten Filmgenres. Die Genres "Action, Adventure, Sci-Fi" und "Animation, Adventure, Comedy" sind besonders prominent vertreten

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/d515ff71-bd0e-44f5-8003-b70074092ac2)

# Welches Genre war am beliebtesten im Verlauf der Jahre? 

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/0d8343ca-b05b-4c26-b794-37c95877d692)

Das beliebteste Genre über die Jahre war Action, Adventure, Comedy. 

# Wie haben sich die durchschnittlichen Filmbewertungen im Laufe der Jahre entwickelt?

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/e94afa28-bcc8-408a-9471-4598e8949486)

Es ist deutlich zu sehen, dass die Ratings für das Jahr 2020 am schwächsten sind. 

# Besonderheiten und Auffälligkeiten im Jahr 2020 

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/1556b9f8-923b-4c2c-9ec3-86a8939c7867)

Das obige Diagramm konzentriert sich auf das Jahr 2020 und zeigt, dass "Drama" das am häufigsten vorkommende Genre war, gefolgt von "Comedy" und "Action"

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/df616134-1776-4f70-8667-7af56ba74d2a)


  # Top 10 der Filme mit den schlechtesten Bewertungen im Jahr 2020 

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/1db9b0b9-9d02-4238-b18b-b586ce596b3f)

# Gibt es einen Zusammenhang zwischen der Länge eines Films und den Ratings von Filmen? 

Warum ist das wichtig?
Die Analyse der Laufzeitbewertungskorrelation hilft, das optimale Gleichgewicht zwischen einer ansprechenden Laufzeit und Zuschauerzufriedenheit zu verstehen. 

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/0f6c5090-a364-4f1e-8702-40f6cb6c44ee)

Die Korrelation von ungefähr 0.38 weist darauf hin, dass es eine positive Assoziation zwischen der Laufzeit eines Films und seiner Bewertung gibt das heißt, Filme mit einer längeren Laufzeit tendieren dazu, höhere Bewertungen zu haben.

Korrelation zwischen Laufzeit und Bewertung: 0.3785280720080518

# Gibt es einen Zusammenhang zwischen einem höheren Filmbudget und besseren Ratings von Filmen? 
Warum ist das wichtig? Diese Untersuchung bietet Einblicke, wie Finanzierungsentscheidungen den kommerziellen Erfolg von Filmen beeinflussen und kann Produktionsstrategien informieren.

Wirtschaftlicher Nutzen der Beantwortung dieser Frage: Filmproduzenten können durch die Analyse der Budget-Erfolg-Korrelation bessere Entscheidungen bei der Budgetierung treffen. Optimale Budgetierungsstrategien können zu maximierten Einnahmen bei minimierten Kosten führen, wodurch die Rentabilität gesteigert wird. 

Um die Korrelation zu messen wurde eine lineare Regression verwendet. 

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/1f350cd1-56c4-4649-adcb-fa512153585e)

Das Streudiagramm zeigt die Datenpunkte mit einer überlagerten Regressionslinie. Die Flachheit der Linie spiegelt die geringe Steigung wider, die aus der geringen Korrelation resultiert. Die Punkte liegen weit verstreut und zeigen keine deutliche Tendenz, der Linie zu folgen, was auf eine geringe Vorhersagekraft des Ratings für das Budget hindeutet.

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/5d9f032e-77ee-42da-8abc-f33056f8665a)

Die Heatmap zeigt eine Korrelationsmatrix, in der die Korrelation von 'Rating' zu sich selbst und von 'Budget' zu sich selbst jeweils 1 ist, was erwartet wird. Die Korrelation zwischen 'Rating' und 'Budget' wird als 0.053 angezeigt, was die sehr schwache Beziehung bestätigt.

Es besteht also keine starke lineare Beziehung zwischen dem Budget und dem Rating

# Diskussion der Ergebnisse & weiterer wissenschaftlicher Quellen 
Was ist besonders gewesen im Jahr 2020? Die Welt wurde von der Pandemie erschüttert. Dies hatte natürlich auch Auswirkungen auf die Filmindustrie. 

Die Auswirkungen sind nicht auf ein Land begrenzt, wie auch andere wissenschaftliche Quellen belegen. 

![gr-d-16 02 01 01-je](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/2bba1322-11c6-44e5-99de-ac3c42ae72ea)
Quelle: (Schweizer Bundesamt für Statistik , 2022)

Daten vom Bundesamt Statistik Schweiz zeigen ein ähnliches Ergebnis hinsichtlich 2020 wie der bearbeitete Datensatz. 
Die Kinoeintritte sackten 2020 auf 4,5 Millionen zusammen, 2021 zählte man 5,4 Millionen Besucher (Schweizer Bundesamt für Statistik , 2022)

Die Geschäftsberichte der Filmförderungsanstalt, FFA (nationale Filmförderung Deutschlands) zeigen ausführlich, wie sich die Einnahmen der FFA im jeweiligen Jahr gestalten. 

Auch in Deutschland sieht man einen markanten Einbruch im Umsatz im Jahr 2020. Dies deckt sich mit den Auswirkungen der Pandemie auf die Filmindustrie. 
Die ersten beiden Monate des Jahres 2020, Januar und Februar, zeigen nur einen leichten Rückgang bzw. eine leichte Zunahme im Vergleich zum Vorjahr, was darauf hindeutet, dass die pandemiebedingten Auswirkungen erst ab März spürbar wurden.

Wenn man 2020 mit 2018 vergleicht, ist der Rückgang noch dramatischer, da der Gesamtumsatz in 2020 nur ein Drittel von dem in 2018 beträgt. 

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/71b9bf38-00d0-4781-a91a-886606ad5b6a) 

Quelle: (Filmförderungsanstalt , 2022)
Im Jahr 2020 ist auch in Österreich ein drastischer Rückgang der Kinobesuche zu erkennen. Dieser Rückgang ist eine direkte Folge der globalen COVID-19-Pandemie, die zu weitreichenden Schließungen von öffentlichen Einrichtungen, darunter auch Kinos, geführt hat.

![image](https://github.com/Alisa99j/Pr-sentation_Top100Movies/assets/155681145/4bef1f8e-1ce3-4360-86a7-55b659d356b9)

Quelle: (STATISTIK AUSTRIA, 2023)

# Ausblick für zukünftige Untersuchungen 

Einfluss von Streaming-Plattformen - Wie verändert sich das Publikumsverhalten durch das Angebot an Streaming-Optionen?

Einfluss von technologischen Entwicklungen - Wie verändert sich das Publikumsverhalten durch den Einfluss von Technologien wie Virtual Reality? 

# Abschluss 

Dieses Projekt hat einen umfassenden Einblick in die Welt der populären Filme von 2003 bis 2022 gegeben, indem es verschiedene Faktoren untersuchte, die zur Popularität eines Films beitragen.

Durch die Analyse von Aspekten wie Genres, Bewertungen, Budgets und vielem mehr, konnten wir nicht nur verstehen, was einen Film populär macht, sondern auch, wie sich diese Faktoren im Laufe der Zeit verändert haben. Besonders bemerkenswert war der Einfluss der COVID-19-Pandemie auf die Filmindustrie im Jahr 2020, der einen deutlichen Einbruch in den Kinobesuchen, den damit verbundenen Einnahmen zeigte und auch den Ratings zeigte. 

Obwohl dieser Einblick wertvoll ist, bleibt die Filmwelt eine sich ständig verändernde Landschaft, beeinflusst von technologischen Fortschritten, globalen Ereignissen und sich wandelnden Zuschauerpräferenzen. Zukünftige Studien sollten daher die Rolle von Streaming-Diensten, die Evolution von Filmgenres , um ein noch vollständigeres Bild der Faktoren zu erhalten, die die Popularität von Filmen bestimmen. In dieser dynamischen Branche bleibt die einzige Konstante der Wandel selbst, und es ist spannend zu beobachten, wie sich zukünftige Trends entwickeln werden. 

# Literaturverzeichnis 

STATISTIK AUSTRIA
Titel: Mikrozensus-Arbeitskräfteerhebung 2021 (Jahresdurchschnitt über alle Wochen)
Erstellungsdatum: 02.03.2023
URL: [https://www.statistik.at/statistiken/bevoelkerung-und-soziales/kultur/museen-und-ausstellungen)]
Zitat: STATISTIK AUSTRIA. (2023). Mikrozensus-Arbeitskräfteerhebung 2021 (Jahresdurchschnitt über alle Wochen). Erstellt am 02.03.2023. Abgerufen von [https://www.statistik.at/statistiken/bevoelkerung-und-soziales/kultur/museen-und-ausstellungen]

Filmförderungsanstalt (FFA)
Titel: Marktdaten
URL: [https://www.ffa.de/marktdaten.html]
Zitat: Filmförderungsanstalt (FFA). (2022). Marktdaten. Abgerufen von [https://www.ffa.de/marktdaten.html]

Bundesamt für Statistik (BFS)
Titel: Kinobesuche und private Filmvorführungen
URL: [https://www.bfs.admin.ch/bfs/de/home/statistiken/kultur-medien-informationsgesellschaft-sport/kultur/film-kino/kinoeintritte-und-privat-filme.html]
Zitat: Bundesamt für Statistik (BFS). (2022). Kinobesuche und private Filmvorführungen. Abgerufen von [https://www.bfs.admin.ch/bfs/de/home/statistiken/kultur-medien-informationsgesellschaft-sport/kultur/film-kino/kinoeintritte-und-privat-filme.html]





