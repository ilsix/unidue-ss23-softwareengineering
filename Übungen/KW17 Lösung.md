# Kapitel 2  
## 1) Leiten Sie aus der Fallstudie jeweils zwei funktionale Anforderungen, zwei Qualitätsanforderungen, sowie eine Randbedingung ab.  
**Funktionale Anforderungen:**  
- Das neue System muss es Nutzern einen Login bereitstellen  
- Die Bedürfnisse der Ausschluss-Mengen aller Teilnehmer müssen überprüft werden damit Konflikte vermekt oder behoben werden können  

**Qualitätsanforderungen:**  
- Das neue System kann mehrere Aufgaben gleichzeitig behandeln  
- Das neue System soll möglichst genau abbilden, wie Treffen behandelt werden  

**Randbedingungen:**  
- DSGVO-Konformität  

## 2) Kennzeichnen Sie Passagen der Fallstudie, die das Problem, eine Anforderung oder die Lösung beschreiben. Erläutern Sie an einem Beispiel aus der Fallstudie, warum es problematisch ist, wenn Lösungen ohne Anforderung spezifiziert werden.  
Lösungen ohne Anforderungen implizieren Probleme die es zu lösen gilt ohne diese konkret zu nennen. Das erhöhrt den Aufwand später im Projekt, wenn es darum geht diese Lösung einzubauen, ohne das ein bestimmter Platz für diese existiert.  
**Beispiel Login:** Ist eine Login-Seite überhaupt nötig? Benutzt die Firma intern vielleicht ein SSO-System welches die Login-Seite ersetzen würde?  

## 3) Was versteht man unter einem Stakeholder? Wer sind die Stakeholder für die vorgestellte Fallstudie?  
Ein Stakeholder ist eine Instanz welche Anteile an einem Projekt hat und Interesse, dass dieses erfolgreich abgeschlossen wird. Der Stakeholder der Fallstudie ist WSS Inc., genauer die Manager welche Termine für Treffen bestimmen und planen müssen.  

## 4) Erläutern Sie den Unterschied zwischen funktionalen Anforderungen und nicht-funktionalen Anforderungen. Geben Sie hierzu eine geeignete Stelle in der Fallstudie an und diskutieren Sie, warum die betreffende Passage eine nicht-funktionale Anforderung beschreibt. Welche Fragen müssten Sie stellen, um die nicht-funktionale Anforderung in eine funktionale Anforderung zu überführen?  
Eine funktionale Anforderung definiert von System bereitgestellte Funktionen. Nicht-funktionale Anforderungen werden oft als Überbegriff für andere funktionale Anforderungen verwendet, welche nicht detailliert genug spezifiziert werden.  
**Bespiel:** "...die Daten sollten Sicher sein." - Inwiefern gesichert? Welche Art Sicherung ist hier von Nöten, welche Daten genau müssen gesichert werden?  

## 5a) Erläutern Sie die Begriffe System, Systemkontext und irrelevante Umgebung.  
**System:** Eine Zusammenstellung von Hard-, Software und Netzwerkkomponenten zur Lösung eines Anwendungsproblems.  
**Systemkontext:** Umgebung und Kontext in dem das System arbeiten können muss.  
**Irrelevante Umgebung:** Umgebung des Systems, welche keinen Einfluss darauf nimmt.    

## 5b) Wodurch wird das System vom Systemkontext getrennt?  
System und Systemkontext werden durch die **Systemgrenze** getrennt.  

## 5c) Wodurch wird der Systemkontext von der irrelevanten Umgebung getrennt?  
Systemkontext und irrelevante Umgebung werden durch die **Kontextgrenze** getrennt.

## 5d) Welche Quellen, Senken und Schnittstellen werden in der Fallstudie (implizit) genannt? Ordnen Sie diese dem Systemkontext oder der irrelevanten Umgebung zu oder begründen Sie, warum Sie diese nicht einordnen können.  
**Systemkontext:** Verwaltungsmitarbeiter, Auftraggeber, DSGVO, Teilnehmer  
**Irrelevante Umgebung:**  BDSG-Verordnung, Schnittstellen zu Abrechnungssystemen, Schnittstellen zum System für Lohnbescheinigungen