# Kapitel 1 (Musterlösung gegeben)  
## A1) Literaturrecherche nach katastrophalen Softwarefehlern welche durch Software Engineering vermieden werden können (Außer Boeing 737 Max oder Toll Collect System)  
**Britische Familienbehörde 2004:** Umstrukturierung hat zu immensen Bugs im neuen IT-System geführt welches hastig angepasst wurde.  
**Knight Capital 2012:** Fehler in der Handelssoftware haben in 45 Minuten 440.000.000USD verloren. Der Fehler hat zu viele, zu teure Kauforder getätigt.  

## A2a) Erläutern Sie folgende Eigenschaften: Korrektheit, Zuverlässigkeit, Robustheit, Performanz, Benutzerfreundlichkeit, Wartbarkeit  
**Korrektheit:**  Wird das Programm entsprechend der gewünschten Spezifikation entwickelt?  
**Zuverlässigkeit:**  Ist das Programm dauerhaft verlässlich einzusetzen? Kann der Anwender sich guten Gewissens von der Software abhängig machen? Werden seine Vorstellungen dabei erfüllt?  
**Robustheit:** Wie schlägt sich das System bei fehlerhaften Eingaben seitens Nutzer oder Hardwarefehlern?  
**Performanz:** Erfüllt das System die Anforderungen hinsichtlich Antwortzeit, Durchsatz, Skalierbarkeit und Ressourcenverbrauch?  
**Benutzerfreundlichkeit:** Ist die Software einfach und intuitiv zu Bedienen?  
**Wartbarkeit:** Kann die Software auch nach Auslieferung gut instandgehalten und angepasst werden?  

## A2b) Überlegen Sie jeweils, wie man diese in einem Softwareprojekt nachprüfen kann.  
**Korrektheit:** Testfälle für die spezifischen Verwendungszwecke der Software  
**Zuverlässigkeit:** Beta-Tests und Belastungstests  
**Robustheit:** Testfälle für falsche Eingaben  
**Performanz:** Messungen, Berechnungen, Simulationen  
**Benutzerfreundlichkeit:** Beta-Tests durch unterschiedliche Tester, Observierung von Nutzern bei Verwendung.  
**Wartbarkeit:** Wartbarkeit hängt von Struktur der Software ab. Ist die Dokumentation vollständig und verständlich? Ist die Software modular aufgebaut?  

## A2c) Warum nimmt die Wartbarkeit einer Software mit ihrer zunehmenden Lebensdauer ab?
Software wird mit der Zeit größer. Der immer größere Aufwand die Dokumentation zu pflegen sorgt dafür, dass eben das nicht gründlich genug oder auch gar nicht gemacht wird. Auch wechselnde Entwicklerteams können problematisch werden, wenn diese die Arbeit ihrer Vorgänger nicht verstehen oder einfach andere Vorgehensweisen und Philosophien haben.  

## A3a) Erläutern Sie die folgenden Sichten und deren Nachteile: Produktionssicht, Ingenieurssicht, Kommunikationssicht, Juristensicht  
### Produktionssicht  
Entwurf -> Produktion des Entwurfs in strikter Arbeitsteilung | Kosten werden aus Produktionsmittel und Personalkosten bestimmt | Anpassung ausschließlich über fest definierte Parameter  
**Vorteile:** Spezialisten für einzelne Tätigkeiten, klare Fortschrittskontrollen, Management-Beruhigung, Anwendungswissen nur zu Beginn benötigt  
**Nachteile:** Unvollständiger Wissenstransfer über Phasengrenzen, fehlendes Anwendungswissen führt in späteren Phasen zu Fehlentscheidungen  
### Ingenieurssicht  
Planung und Produktion weniger strikt getrennt | Entwurfsanpassungen auch während Produktion in geringem Umfang möglich | Verwendung allgemein Bekannter Abstraktionen und Vorlagen | Kaum Anpassungsmöglichkeiten nach Abschluss der Produktion  
**Vorteile:** Handhabbarkeit, eingeschränkte Flexibilität, vorhersehbare Kosten  
**Nachteile:** Keine Abstraktionen für Software vorhanden, "weiche" Natur von Software verleitet zu übermäßiger Änderung  
### Kommunikationssicht  
Software als gemeinschaftliches Kunstwerk | Planung und Produktion nicht getrennt | Kreativität aller Beteiligten muss berücksichtigt werden | Wenig reglementierte und beliebig breite Kommunikation  
**Vorteile:** Freie Kommunikation verringert Missverständnisse, jeder hat Chance zum Endprodukt beizutragen  
**Nachteile:** Unplanbarkeit, unvorhersehbares Ende, unwirtschaftliches Vorgehen  
### Juristensicht  
Handhabung von Softwareentwicklung durch Verträge | Möglichst klare Teilaufgaben | Verzug muss bewertbar sein und Konsequenzen haben | Späte Anforderungen werden ausgeklammert  
**Vorteile:** Juristische Eindeutigkeit  
**Nachteile:** Entspricht nicht dem Erkenntnisgewinn während Entwicklung, Software selten wirklich nützlich  

## A3b) Warum ist es für die Organisation eines Softwareprozesses wichtig, alle vier Sichten zu berücksichtigen?  
Jede dieser Sichten betrachtet nur einen Teil aller zu beachtenden Aspekte eines Projekts. Ein wirklich vollständiges Bild kommt erst bei Betrachtung aller Sichten zustande:  
**Jurist:** Verträge müssen Eckdaten bestimmen  
**Künstler:** Grundlegende Entwürfe müssen von allen Beteiligten abgestimmt werden  
**Ingenieur:** Standardanteile müssen entworfen werden  
**Produktion:** Bestimmte Teile müssen recht Stur programmiert werden