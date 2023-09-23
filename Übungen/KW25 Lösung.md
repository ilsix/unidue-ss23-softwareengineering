# Kapitel 6  
## 14) Erläutern Sie, was man unter kontrollflussbezogenen Testverfahren versteht und welche Ziele man dabei verfolgt.  
Kontrollflussbezogene Testverfahren sind White-box verfahren, da sich Kenntnis der Programmstruktur zu Nutzen gemacht wird. Diese Tests sind dynamischer Natur, da sie auf der Ausführung des Programms mit verschiedenen Testdaten aufbauen. Ziel ist es durch geschicktes wählen der Testdaten die höchste Anzahl von Durchläufen des Kontrollflusses in den wenigsten Testdurchläufen zu erhalten.  

## 15a) Was versteht man unter einem Entscheidungs-Entscheidungsweg in einem Kontrollflussgraphen?  
Der Entscheidungs-Entscheidungsweg ist ein Wegstück im Graphen, welches bei einem Entscheidungsknoten oder dem Anfangsknoten beginnt und beim nächsten Entscheidungsknoten oder dem Endknoten des Graphen geht.  

## 15b) Was versteht man unter einem Segment in einem Kontrollflussgraphen?  
Ein Segment ist ein Wegstück im Kontrollflussgraphen mit folgenden Eigenschaften:
1. Der erste Knoten ist der Anfangsknoten oder ein Entscheidungsknoten oder ein Vereinigungsknoten  
2. Der letzte Knoten ist der Endknoten oder ein Entscheidungsknoten oder ein Vereinigungsknoten  
3. Alle anderen Knoten haben nur eine Eingangs- und Ausgangskante  

## 16) Welche Arten von Fehlern können mit kontrollflussbezogenen Verfahren aufgedeckt werden?  
- **Berechnungsfehler:** Der richtige Kontrollflussweg wurde zwar gewählt, dennoch ist mindestens ein berechneter Variablenwert falsch  
- **Bereichsfehler:** Es wurde der falsche Kontrollsflussweg gewählt. Die Menge der Eingaben welche der Kontrollflussweg abdeckt stimmt nicht mit der Menge der in der korrekten Spezifikation angegebenen Eingaben überein.    
- **Unterbereichsfehler:** Spezieller Bereichsfehler, bei denen ein Kontrollfluss zu viel oder wenig im System vorkommt, wodurch entweder eine Abfrage fehlt oder eine überflüssige Abfrage im Kontrollflussweg vorhanden ist.  

## 17a) Was versteht man unter einer Anweisungsüberdeckung?  
Die Anweisungsüberdeckung beschreibt welcher Anteil aller möglichen Anweisungen welche durch die Testdatenmenge abgedeckt werden.  

## 17b) Nennen Sie zwei Fehler, die bei einem Anweisungsüberdeckungstest nicht zuverlässig erkannt werden und erläutern Sie jeweils, welche kontrollflussbezogenen Verfahren für diese Fehler herangezogen werden können.  
- **Fehler in Verzweigungen oder Schleifen:** Zweigüberdeckungstests bieten eine strengere Überdeckung. Diesmal müssen alle Kanten die von bedingten Anweisungen ausgehen abgedeckt werden.  
- **Fehler aus zusammengesetzten Entscheidungen:** Bei zusammengesetzten Bedingungen reichen nicht Prüfungen auf die zusammengesetzte Bedingung. Stattdessen muss jede Teilbedingung einzeln variiert werden.  

## 18a) Java Kontrollflussgraph:  
siehe KW23 Lösung_gincl.pdf  

## 18b) Java Testfälle für die Zweigüberdeckung:  
siehe KW23 Lösung_gincl.pdf  

## 19a)  Bilden Sie unter Verwendung der in der Vorlesung angegebenen Regeln gültige und ungültige Äquivalenzklassen. Tragen Sie die Äquivalenzklassen in die folgende Tabelle ein und verwenden sie dabei eine sinnvolle Nummerierung.  
siehe KW23 Lösung_gincl.pdf  

## 19b) Bilden Sie unter Verwendung der in der Vorlesung angegebenen Regeln gültige und ungültige Äquivalenzklassen. Tragen Sie sie in die folgende Tabelle ein und verwenden sie dabei eine sinnvolle Nummerierung.  
siehe KW23 Lösung_gincl.pdf  

## 20a) Erläutern Sie, was man unter dem Begriff Test-Driven Development versteht.  
TDD basiert darauf, dass Tests geschrieben werden bevor die eigentliche Funktion existiert. Dadurch das Tests so schnell durchgeführt werden können, kann der Anwender früher in die Entwicklung einbezogen werden.  

## 20b) Das Prinzip des TDD lässt sich als Zyklus mit mehreren Aktivitäten darstellen. Zeichnen Sie diesen Zyklus und erläutern Sie die vorkommenden Aktivitäten.  
1. **Test erstellen der fehlschlägt:** Der Testfall wird durch mangelnden Code nicht bestanden.  
2. **Code anpassen, dass Test bestanden wird:** Der Code wird angepasst und erweitern um den Testfall zu bestehen.  
3. **Refactoring zu sauberem Code:** Der Code wird bereinigt und aufgehübscht um Codeduplikationen zu vermeiden.  

## 21) Das TDD Mantra beschreibt, wie man in mehreren Schritten von der Erstellung eines Testfalls zur Refaktorisierung des Codes gelangt. Erläutern Sie diesen Prozess und seine einzelnen Schritte.  
1. **Rot:** Fehlschläge im Test durch erweiterung des Codes solange anpassen bis der Rest bestanden ist  
2. **Grün:** Erfolgreiche Ausführung des Tests  
3. **Refactor:** Der Code wird neu strukturiert, ohne die Funktion zu ändern  

## 22) Nennen und erläutern Sie drei Vorteile, die sich durch die Vorgehensweise des Test-Driven Developments ergeben können.  
1. **Klare Vorstellung des Ergebnis:** Durch das vorangehende Schreiben von Tests werden als erstes immer erwünschte Verhaltensweisen definiert.  
2. **Weniger Fehler im Code:** Durch weniger Codefehler fallen zusätzliche Debugging-Sessions weg und Aufwände können exakter eingeschätzt werden.  
3. **Kontrollgefühl:** Kleine, in sich einfach zu pflegende Tests bilden einen Überblick und vermitteln gut den Fortschritt im Projekt.  

## 23a) Welche Art von Test wird hauptsächlich beim Test-Driven Development verwendet?  
Hauptbestandteil von TDD sind Modultests.  

## 23b) Erläutern Sie, was man unter Mock-Objekten versteht und wozu diese beim TDD eingesetzt werden.  
Mock-Objekte simulieren Abhängigkeiten des zu testenden Moduls an andere Objekte oder stellen Testdaten bereit.  

## 24) Erstellen Sie in der Sprache Gherkin drei Szenarien für eine User Story, die Sie für die Fallstudie aus Übungsblatt 2 definiert haben.  

