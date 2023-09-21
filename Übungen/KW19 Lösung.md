# Kapitel 3
## 1a) Erläutern Sie die Begriffe „Abstraktion“ und „Modell“.  
Abstraktion beschreibt das Auslassen von irrelevanten Einzelheiten zur Überführung in eine einfachere, allgemeine Form.  
Ein Modell ist ein vereinfachtes Abbild der Realität.  

## 1b) Warum ist Abstraktion und Modellbildung im Software Engineering wichtig? Erläutern Sie dies anhand eines selbstgewählten Beispiels.  
Abstraktion und Modellbildung sind wichtig um die wichtigsten Merkmale in einem Modell zu entwickeln und sich nicht in unwichtigen oder effektlosen Details zu verlieren.  
**Beispiele:** Zug- und Bahnkarten zeigen nicht genaue Fahrtverläufe sondern nur die relative Position von größeren Bahnhöfen und Zwischenhalten.  

## 2) Erinnern Sie sich an das Termin-Verwaltungs-System, für das Sie im Übungsblatt zu Kapitel 2 eigene User Stories geschrieben haben. Wählen Sie drei passende und hinreichend komplexe User Stories aus und schreiben sie dafür jeweils eine geeignete Spezifikation im Umfang von jeweils etwa 50 – 100 Wörtern.  
Um sich am System anzumelden, muss der Anwender seinen Benutzernamen und Passwort eingeben und mit Enter bestätigen. Das Dialogfeld zur Eingabe des 2FA-Codes erscheint spätestens eine halbe Sekunde. Der Anwender erhält eine 5-stellige Nummer auf sein Telefon welche ins Feld eingetragen werden muss. Nach erneuter Bestätigung mit Enter wird der Benutzer nach maximal einer Sekunde auf seine Kontoseite weitergeleitet.  

## 3a) Bei der Modellierung eines Softwaresystems kann man dieses aus verschiedenen Sichten betrachten. Erläutern Sie diese Sichten.  
- **Daten:** Datenstrukturen, Entitätstypen und Beziehungen  
- **Funktionen:** Funktionshierarchie, Arbeitsablauf, Informationsfluss  
- **Dynamik:** Systemabläufe  
- **Benutzeroberfläche:** Erscheinung für Endanwender  

## 3b) Ist es Ihrer Meinung nach sinnvoll, die Sichten strikt getrennt voneinander zu betrachten?  
Nein, das ist nicht sinnvoll, da sich diese Sichten auch überschneiden können. In der Fallstudie überschneiden sich z.B. die Oberfläche und Dynamik, da der Ablauf der Bedienung intern nah am Systemablauf zur Authentifizierung liegt.  

## 4a) Erläutern Sie die Begriffe „Spezifikation“ und „Spezifizierer“.  
Der Spezifizierer ist der, der auf Anfoderungsdokumenten basierend die konkrete Spezifikation schreibt.  
Die Spezifikation beschreibt das Verhalten der Software. Eine Spezifikation enthält keine Details zur geplanten Umsetzung.  

## 4b) Worin liegt der wesentliche Unterschied zwischen Spezifikation und Anforderungsanalyse?  
Beide Aktivitäten sind eng miteinander verwandt aber an unterschiedliche Zielgruppen gerichtet. Die Anforderungsanalyse richtet sich eher an Kunden und Stakeholder um benötigte Features zu ermitteln. Spezifikation ist für Entwickler interessant, da diese das Verhalten der Software für die Umsetzung konkretisieren.  

## 4c) Ist es Ihrer Meinung nach sinnvoll, sich bei der Spezifikation auf das „WAS“ zu konzentrieren und nicht auf das „WIE“? Begründen Sie.  
Generell macht es Sinn sich auf das was zu konzentrieren. Entwicklern die vielleicht schon einiges Know-How haben einen Lösungsweg vorzuschreiben macht in den meisten Situationen nicht viel Sinn. Es kann aber durchaus hilfreich sein ein Wie zu erklären um das Was zu verstehen.  

## 5) Welche Modellierungssichten sind Ihrer Meinung nach für die Modellierung des Termin-Verwaltungs- Systems besonders wichtig? Welche Modellierungskonzepte würden Sie hierfür verwenden? Begründen Sie Ihre Entscheidung.  
- **Daten:** ER-Modelle  
- **Funktionen:** Aktivitätsdiagram, Geschäftsprozessmodell  
- **Benutzeroberfläche:** Grafikeditoren und UI-Mockup-Tools  

## 6) Was versteht man unter verkürzenden und erweiternden Eigenschaften? Nennen Sie Beispiele für jeweils eine verkürzende und eine erweiternde Eigenschaft für ein mögliches Modell zum Termin-Verwaltungs-System.  
- **Verkürzende Eigenschaften:** Eigenschaften die irrelevant für das Modell sind und ausgelassen werden. Beispiel: Nutzer werden auf Nutzername, Email und Passwort reduziert.  
- **Erweiternde Eigenschaften:** Eigenschaften die besonders wichtig sind. Beispiel: Nutzer erhalten eine TeilnehmerID

## 7) Überlegen Sie, welche Screens Sie für ein User Interface für das Termin-Verwaltungs-System erstellen müssten und wie die Navigation zwischen diesen Screens aussehen könnte. Nutzen Sie hierzu ein User interface flow Diagramm.  
1. **Login-Screen**  
2. **Kalenderübersicht**  
3. **Neuen Termin anlegen**  
4. **Ort und Nutzer auswählen**
5. **Erstellung bestätigen und Teilnehmer benachrichtigen**
siehe KW19 Lösung_gincl.pdf  

## 8) Modellieren Sie mittels eines BPMN-Diagramms den Prozess der Terminvereinbarung für das Termin-Verwaltungs-System aus dem Übungsblatt zu Kapitel 2.  
siehe KW19 Lösung_gincl.pdf  

## 9) Erstellen Sie für einen der Screens, die Sie in Aufgabe 7 modelliert haben, einen analogen Prototypen (z.B. Papier-Prototyp, Mockup). Überlegen Sie dabei besonders, wie Sie Interface-Elemente darstellen können, um sie in einer Nutzerstudie zu testen.  
siehe KW19 Lösung_gincl.pdf  
