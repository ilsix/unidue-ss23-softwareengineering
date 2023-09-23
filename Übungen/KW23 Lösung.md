# Kapitel 6
## 1) Nach welchen Kriterien kann man Softwarefehler klassifizieren? Wieso ist eine solche Klassifizierung sinnvoll?  
- **Fehlerursachen:** Woher kommt der Fehler?  
- **Phase der Entstehung:** In welcher Phase des Projekts ist der Fehler entstanden? (meist Anforderungsanalyse oder Entwurf)  
- **Fehlerart:** Auslassung (omission) oder Unkorrektheit (comission)?  
- **Fehlerverteilung:** Auf welche Module sind die Fehler verteilt? Dabei lässt sich oft das Pareto-Phänomen beobachten, wo 80% der Resultate mit 20% des Aufwands erreicht werden und andersrum.  

## 2) Erläutern Sie den Unterschied zwischen einem Fehler und einem Mangel. Wieso und für wen ist eine solche Unterscheidung wichtig?  
Ein Fehler beschreibt die Nichterfüllung einer festgelegten Forderung, insbesondere Qualitäts-oder Zuverlässigkeitsmerkmale. Ein Mangel hingegen beschreibt die Nichterfüllung einer Forderung oder angemessenen Erwartung. Das schließt z.B. Ladezeiten ein die angemessene Werte übersteigen. Mängel beziehen sich oft auf nicht genau spezifizierte Aspekte der Benutzerfreundlichkeit.  

## 3) Erklären Sie, wieso die Kosten einer Fehlerbeseitigung umso höher sind, je früher in der Entwicklungsphase dieser Fehler entsteht und je später in der Entwicklungsphase er entdeckt wird.  
Wird ein Fehler früh eingebracht aber erst spät entdeckt, muss jeder Teil des Programms der irgendwie von einer beispielsweise fehlerhaften Anforderung abhängt neu geprüft und repariert werden, zusammen mit sämtlichen Spezifikationen und Entwürfen auf dem Weg.  

## 4) Ist es aus Ihrer Sicht sinnvoll, jede Software zu testen, bis diese 100 % fehlerfrei ist? Begründen Sie Ihre Antwort.  
Testen bis zur 100%-igen Fehlerfreiheit würde die meisten, wenn nicht jedes Softwareprojekt unwirtschaftlich machen und die Entwicklungszeit übermäßig verlängern. Daher macht es höchstens Sinn nur die wichtigsten Komponenten wirklich 100% fehlerfrei zu machen und den Rest zufriedenstellend zu verbessern.  

## 5) Nennen Sie die Formel zur Berechnung des TestROI. Wie lässt sich der der ROI-Wert interpretieren?  
**RestROI = (Testnutzen - Testkosten) / Testkosten**  
Je höher der ROI-Wert über 0 ist, desto mehr lohnen sich weitere Tests. Bei 0 oder weniger sind Tests ungerechtfertigt und bringen kaum bis keine weiteren Vorteile.  

## 6a) Erläutern Sie die Begriffe Qualität, Qualitätsmanagement und Qualitätssicherung.  
**Qualität** beschreibt die Übereinstimmung mit Kundenanforderungen, genauer die tatsächlichen Anforderungen der beteiligten Personen.  
**Qualitätsmanagement** beschreibt die Tätigkeiten welche im Projekt stattfinden um die Erhöhung und Ausprägung der Softwarequalität zu kontrollieren.  
**Qualitätssicherung** beschreibt den Teil vom Qualitätsmanagement der Qualitätsanforderungen erfüllt. Dazu werden Dokumente wie ein QM-Handbuch, -Verfahrensanweisungen, Prüf- und Arbeitsanweisungen angelegt und verwendet.  

## 6b) Wofür steht die Abkürzung QMS? Erläutern Sie diesen Begriff.  
QMS steht für Qualitätsmanagementsystem. QMS fasst die Organisationsstruktur, Verfahren, Prozesse und Mittel zusammen, welche zur Umsetzung des Qualitätsmanagements notwendig sind.  

## 7a) Welche typischen Testarten werden im Softwarelebenszyklus unterschieden? Welche Ziele verfolgen diese Testarten jeweils?  
1. **Komponententests** testen einzelne Komponenten und finden nahe der Entwicklung statt. Dabei werden Testdaten und Stubs eingesetzt um eine Testumgebung für das Modul bereitzustellen.  
2. **Integrationstests** setzen Modultests vorraus. Bei diesen Tests wird das Zusammenspiel von Komponenten als Gruppe geprüft. Testumgebungen aus Komponententests können weiterverwendet werden. Fremdkomponenten werden ebenfalls eingeschlossen. Datenbewegungen zwischen Komponenten werden mitgelesen und ausgewertet. Gesucht werden Fehler in Schnittstellen und dem Zusammenspiel von Komponenten.  
3. **Systemtests** setzen Integrationstest vorraus. Die Testumgebung ist so nah wie möglich an der Produktivumgebung. Testdaten und Stubs sind zu vermeiden. Ziel sind die Validierung wie gut das System die gestellten Anforderungen erfüllt und das Feststellen von undokumentierten oder vergessenen Anforderungen.  
4. **Akzeptanztests** prüfen die Erfüllung der Anforderungen aus Anwendersicht. Getestet wird am integrierten Gesamtsystem. Überprüft wird die vertragliche Akzeptanz und die Akzeptanz von Benutzern.  

## 7b) Warum ist es wichtig, dass bei der Entwicklung von Software frühzeitig auf Benutzerakzeptanz getestet wird? Womit kann dies frühzeitig überprüft werden?  
Werden Akzeptanzprobleme erst spät festgestellt, bleibt unter Umständen nicht genug Zeit diese Probleme zu beheben, oder es entstehen enorme Kosten.  

## 8) Erläutern Sie, was man unter produktorientiertem Qualitätsmanagement und unter prozessorientiertem Qualitätsmanagement versteht und grenzen Sie diese beiden Begriffe voneinander ab.  
Produktiorientiertes QM beschreibt, dass das Produkt selbst während der Entwicklung auf Vervollständigung der Qualitätsmerkmale geprüft wird. Prozessorientiertes QM untersucht den Schaffungsprozess selbst, welche Werkzeuge und Methoden eingesetzt werden, welche Standards eingehalten werden.  

## 9a) Erläutern Sie, was man unter analytischem Qualitätsmanagement versteht. Worin besteht der wesentliche Unterschied zum konstruktiven Qualitätsmanagement?  
Das analytische QM trägt selbst nicht direkt zu Erhöhung der Qualität, sondern finden stattdessen nur Fehler oder Mängel und stellen das aktuelle Qualitätsniveau fest. Konstruktives QM hingegen besteht aus Methoden, Werkzeugen, Sprachen, Richtlinien und Standards die während der Entwicklung sicherstellen, dass sowohl Produkt als auch Entwicklungsprozess bestimmte Eigenschaften erhält.  

## 9b) Im analytischen Qualitätsmanagement gibt es drei Klassen von Prüfverfahren. Nennen und erläutern Sie diese Klassen.  
- **Verifikation:** Beweis der Korrektheit des Programms anhand von formaler Spezifikationen  
- **Validierung:** Eignung eines Produkts bezüglich des Einsatzzwecks anhand von Metriken, Graphen, Tabellen oder Anomalien  
- **Tests:** Aufdeckung und Suche von Fehlern  

## 9c) Worin besteht der wesentliche Unterschied zwischen statischen und dynamischen Testverfahren?  
- **Statisch:** Software wird nicht ausgeführt, stattdessen werden statische Programm-Checks oder Reviews ausgeführt  
- **Dynamisch:** Software wird ausgeführt, Kontroll- und Datenflüsse werden analysiert  

## 10a) Was versteht man unter einem Testfall?  
Testfälle beinhalten eine Menge von Eingabedaten und eine Menge von erwarteten Ausgaben und Verhaltensweisen. Testfälle stellen erlaubte und nicht erlaubte Eingaben dar. Testfälle werden protokolliert mit Ergebnis, Plattform, Tester, Version und Datum

## 10b) Erläutern Sie die Begriffe Testdatum, Eingabedatum, Istdatum und Solldatum.  
- **Testdatum:** Besteht aus einem Eingabe- und einem Solldatum  
- **Eingabedatum:** Ist die Menge aller Eingabevariablen, Komponenten des Eingabsdatums heißen Testwerte  
- **Istdatum:** Das Datum welches erzeugt wird, wenn das Programm mit einem Eingabedatum ausgeführt wird  
- **Solldatum:** Das in der Spezifikation gewünschte Ergebnis nach Eingabe eines bestimmten Eingabedatums. Werte werden mit einem Testorakel verglichen, welches sich typischerweise aus Menschen zusammensetzt, die die Anforderungsspezifikation verwenden.  

## 11) Erläutern Sie, was man unter Black-Box-Tests und White-Box-Tests versteht, grenzen Sie diese beiden Testansätze voneinander ab und nennen Sie jeweils Vor- und Nachteile.  
- **White-Box:** Testdaten werden durch strukturelle Analyse des Programms erzeugt. Informationsbasis bilden Kontroll- und Datenfluss. Automatische Tests sind möglich, da das Programm eine Testbasis mit wohldefiniertem Syntax und Semantik darstellt. Tests können ohne Spezifikation erfolgen. Implementierte, unspezifizierte Programmteile werden getestet. Spezifiziert aber nicht implementierte Teile werden nicht entdeckt.  
- **Black-Box:** Testfälle werden anhand der Spezifikation entwickelt, die interne programmstruktur fällt nicht ins Gewicht. Dadurch werde spezifizierte, nicht implementierte Programmteile gefunden, Testdaten können spezifisch zum Testen der formal definierten Bedingungen entworfen werden. Implementierte, nicht spezifizierte Programmteile werden nicht entdeckt oder getestet. Nicht aussagekräftige Sepzifikationen führen zu unrepräsentativen Testdaten.  

## 12) Erläutern Sie die Begriffe Defekt, Fehler und Ausfall und grenzen Sie diese voneinander ab.  
- **Defekt:** Merkmal der Beobachtungseinheit weicht von Sepzifikation ab, weisen aber nicht zwingend auf Fehler im Produkt hin. Es könnten auch Fehler in der Dokumentation sein.  
- **Fehler:** Ist immer auch ein Defekt. Ein Fehler passiert trotz korrekter Spezifikation, ist als ein Fehler im Programm. Ein beobachtetes, gemessenes Ergebnis weicht von Erwartungswert ab.  
- **Ausfall:** Die goforderte Funktion kann nicht länger ausgeführt werden, beispielsweise durch Absturz oder Deadlocks.  

## 13a) Was versteht man beim Testen unter dem Überdeckungsgrad?  
Der Überdeckungsgrad misst die Vollständigkeit eines Tests auf ein bestimmtes Prüfverfahren bezogen. Damit soll bestimmt werden wann ein zu Prüfendes Element ausreichend getestet ist.  

## 13b) Was sind Regressionstests?  
Regressionstests beschreiben die Wiederholung von Testfällen. Um nicht sämtliche Testfälle neu einzugeben, falls der prüfling verändert wurde, kommt ein Testwerkzeug zum Einsatz, welches Testfälle speichert und diese bei Bedarf neu auf den Prüfling anwenden kann und danach das Soll und Ist vergleicht.  
