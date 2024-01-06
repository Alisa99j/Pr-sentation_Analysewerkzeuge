# 100 beliebteste Filme von 2003 bis 2022 
Dieses Projekt beschäftigt sich mit den 100 beliebstesten Filmen von 2003 bis 2022. Es werden unterschiedliche Aspekte untersucht, welche anbei aufgeführt sind. Das Ziel dieses Projekts ist zu erkennen was einen Film populär macht. Dieses Ziel wird anhand von explorativer Datenanalyse erreicht werden. 
Verwendet wurde dieser Datensatz: Top 100 popular movies from 2003 to 2022 
(iMDB)  https://www.kaggle.com/datasets/georgescutelnicu/top-100-popular-movies-from-2003-to-2022-imdb 

# Welche Genres sind am häufigsten in der Auswahl der Top-100-Filme pro Jahr vertreten?

Warum ist das wichtig? 
Die Identifikation beliebter Genres gibt Einblicke in Marktpräferenzen und hilft bei Entscheidungen über das Filmangebot.
Wirtschaftlicher Nutzen der Beantwortung dieser Frage: Investitionen in beliebte Genres können durchgeführt werden was dazu führt, dass sich die Einnahmen steigern. 

![image](https://github.com/Alisa99j/Pr-sentation_Analysewerkzeuge/assets/155681145/4863c681-656a-4d81-9f48-232152ab0043)

Das Genre mit dem höchsten Durchschnittsrating ist 'Biography' mit einem Rating von 7.28

Das durchschnittliche Rating für das Genre Drama liegt bei  6.925025853154085. Trotz dieser Tatsache ist Drama das Genre, welches am häufigsten in den Top-100-Filmen vorgekommen ist. 


# Wie haben sich die durchschnittlichen Filmbewertungen im Laufe der Jahre entwickelt?

![image](https://github.com/Alisa99j/Pr-sentation_Analysewerkzeuge/assets/155681145/47f3c620-203b-4bd0-a2f3-5a74545f5828)

![image](https://github.com/Alisa99j/Pr-sentation_Analysewerkzeuge/assets/155681145/9579784a-f55f-4440-aa7f-97a7f27d8541)

![image](https://github.com/Alisa99j/Pr-sentation_Analysewerkzeuge/assets/155681145/e8303573-4438-4763-a639-f0cbd566f484)

![image](https://github.com/Alisa99j/Pr-sentation_Analysewerkzeuge/assets/155681145/80ca4af1-63cc-4ca2-b639-d0747ec9a389)

Trotz der Tatsache, das im Jahr 2020 Drama, Comedy, Action und Thriller die am häufigsten vertretenen Genres waren waren die Ratings in diesem Jahr am niedrigsten. Ist möglicherweise das Interesse der Kund:innen an Filmen niedriger geworden? Kein Unterschied in Genres zu erkennen im Vergleich zu 2022.  

# Gibt es einen Zusammenhang zwischen einem höheren Filmbudget und besseren Ratings von Filmen? 
Warum ist das wichtig? Diese Untersuchung bietet Einblicke, wie Finanzierungsentscheidungen den kommerziellen Erfolg von Filmen beeinflussen und kann Produktionsstrategien informieren.

Wirtschaftlicher Nutzen der Beantwortung dieser Frage: Filmproduzenten können durch die Analyse der Budget-Erfolg-Korrelation bessere Entscheidungen bei der Budgetierung treffen. Optimale Budgetierungsstrategien können zu maximierten Einnahmen bei minimierten Kosten führen, wodurch die Rentabilität gesteigert wird. 

Um die Korrelation zu messen wurde der Pearson-Korrelationskoeffizient verwendet. 

![image](https://github.com/Alisa99j/Pr-sentation_Analysewerkzeuge/assets/155681145/fd68073b-02ee-4de6-9d6f-2db05f763c78)


Pearson-Korrelationskoeffizient: 0.41701207326490164
Der Pearson-Korrelationskoeffizient von 0.417 deutet darauf hin, dass es eine positive lineare Korrelation zwischen Filmbudget und Einkommen an der Kinokasse gibt, aber die Korrelation ist nicht sehr stark. Der Wert 0.417 liegt zwischen 0 und 1, wobei 1 eine perfekte positive Korrelation bedeutet. 
Eine positive Korrelation von 0.417 zeigt an, dass es tendenziell eine Zunahme des Einkommens an der Kinokasse mit steigendem Filmbudget gibt, aber die Beziehung ist nicht sehr ausgeprägt. Es könnte andere Faktoren geben, die das Einkommen beeinflussen, und das Filmbudget erklärt nur einen Teil der Variation im Einkommen.
Insgesamt gibt der Korrelationskoeffizient an, dass es einen positiven Trend gibt, aber es ist wichtig, auch andere Faktoren und die Stärke der Korrelation zu berücksichtigen, um fundiertere Schlussfolgerungen zu ziehen.


# Gibt es einen Zusammenhang zwischen der Länge eines Films und den Ratings von Filmen? 

Warum ist das wichtig?
Die Analyse der Laufzeitbewertungskorrelation hilft, das optimale Gleichgewicht zwischen einer ansprechenden Laufzeit und Zuschauerzufriedenheit zu verstehen. 

Auch hier wurde der Pearson-Korrelationskoeffizient um einen möglichen Zusammenhang festzustellen. 

![image](https://github.com/Alisa99j/Pr-sentation_Analysewerkzeuge/assets/155681145/cb9d2ea7-6274-4ec6-a2a9-8a4c9f701444)

Die Korrelation zwischen Laufzeit und Bewertung beträgt 0.38131891511592747

In diesem Fall deutet der positive Korrelationskoeffizient darauf hin, dass es eine gewisse positive Beziehung zwischen der Laufzeit eines Films und seiner Bewertung gibt. Das bedeutet, dass längere Filme tendenziell höhere Bewertungen erhalten könnten.  

# Abschluss 
