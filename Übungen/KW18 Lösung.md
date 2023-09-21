# Kapitel 2
## 1) Erläutern Sie, welche Techniken zur Anforderungsermittlung Sie einsetzen würden. Begründen Sie Ihre Auswahl.  
**Befragungen:** Interview, um Erwartungen an Funktionen von Nutzer zu erhalten  
**Kreativität:** Interaction Room, um durch persönliche Kommunikation interdisziplinäres Verständnis zu fördern  
**Dokumente:** Systemarchäologie, um notwendige Funktionen aus Altbeständen zu finden 
**Prototyping:** Analog, als einfache Methode um Benutzeroberflächen zu designen  

## 2) Was sind die Hauptaktivitäten im Requirements Engineering? Erläutern Sie diese und geben Sie jeweils ein Beispiel dafür.  
**Ermittlung:** Anforderungsquellen identifizieren und deren Anforderungen im Systemkontext sammeln. Dazu kann man sich z.B. mit den Auftraggebern und zukünftigen Nutzern unterhalten, den aktuellen Zustand ermitteln und welche Änderungen erhofft sind.  
**Dokumentation:** Anforderungen müssen klar, deutlich und permanent verzeichnet werden, damit diese in der weiteren Entwicklung immer überprüft und referenziert werden können. Solche Dokumente sind auch rechtlich relevant und komplex. Ein Beispiel ist   
**Abstimmung:** Gemeinsames Verständnis über Anforderungen erlangen. Konflikte müssen identifiziert, analysiert und gelöst werden. Diese Lösungen müssen dokumentiert werden. Bei mangelnder Abstimmung wird die Akzeptanz des Systems gefährdet, Stakeholder könnten weitere Kooperation verweigern. Ein Beispiel wären Meetings bei denen das Projektteam mit einigen Stakeholdern und Nutzern exakte Details zu Anforderungen klärt.  
**Prüfung:** Überprüfungen ob Anforderungen erfüllt werden. Inspektionen, bei denen Anforderungen formell und gründlich durchgetestet werden. Walkthrough, bei denen Testfälle und Beispiele durchgespielt werden. Stellungnahme, bei der unabhängige dritte herangezogen werden um das Produkt zu testen. Ein Beispiel wären Modultests, wo einzelne Systemkomponenten ausgiebig durch allerlei Testfälle geprüft werden.  
**Verwaltung:** Attributieren von Anforderungen, Sichten auf Anforderungen definieren, Priorisieren von Anforderungen, Verfolgbarkeit von Anforderungen, Versionierung von Anforderungen, Verwaltung von Anforderungsänderungen.  

## 3) Warum ist es wichtig, Anforderungen schriftlich zu dokumentieren? Überlegen Sie, was passieren kann, wenn Anforderungen nicht oder nur unzureichend dokumentiert werden.  
Undeokumentierte Anforderungen werden nicht umgesetzt.  Unzureichende Dokumentation sorgen für Interpretationsspielraum und Ungenauigkeiten zwischen Entwicklern und Stakeholdern.  

## 4a) Was versteht man unter einer User Story? Wozu werden User Stories eingesetzt?  
Eine User Story ist eine mit ID versehene Karte. Sie stellt eine informelle Erklörung eines Software-Features aus der Sicht eines Endbenutzers dar. User Stories sind lediglich Platzhaler für detailliertere Anforderungen.

## 4b) Erläutern Sie den Aufbau von User Stories sowie die verschiedenen Elemente auf der Vorder- und Rückseite der Karten.  
Auf der Vorderseite ist ein Satz, welcher die Rolle und die Funktion festlegt welche erfüllt werden muss. Dies kann mit einer optionalen Erklärung des Nutzen erweitert werden. Außerdem ist eine Priorität und eine Einschätzung der Schwierigkeit notiert. Die Rückseite enthält ein Akzeptanzkriterium. Ist dieses erfüllt, gilt die Anforderung der User Story als umgesetzt.  

## 4c) Was ist beim Schreiben von User Stories zu beachten? Was unterscheidet gute User Stories von schlechten User Stories?  
User Stories werden aus den unterschiedlichen Perspektiven verschiedener Anwender in deren Worten verfasst. Sie sollen lediglich Anforderungen und keine Lösungen darstellen. Es wird stets die Rolle und geforderte Funktion angegeben.  

## 4d) Erstellen Sie drei User Stories auf Basis der Fallstudie. Überprüfen Sie diese User Stories mit dem INVEST Modell.  
1. Als Initiator eines Treffens muss ich potenzielle Teilnehmer über ein notwendiges Treffen informieren können. ID:01 Prio:3 Diff:01 - Das System benachrichtigt gewünschte Teilnehmer über die Notwendigkeit derer Anwesenheit bei einem Treffen.  
2. Als Initiator eines Treffens muss ich Teilnehmer mit aktiveren Rollen für spezielle Bedürfnisse kontaktieren können. ID:02 Prio:2 Diff:01 - Das System muss eine Methode bereitstellen um sich bei aktiveren Teilnehmern nach der Notwendigkeit für spezielles Equipment zu erkundigen.  
3. Als Organisator eines Treffens muss ich die Verfügbarkeit potenzieller Teilnehmer herausfinden können, ohne diese bei denen einzeln anfragen zu müssen. ID:03 Prio:3 Diff:01 - Das System muss automatisch Zeitslots finden in welchen potenzielle Teilnehmer zeitlich verfügbar sind.  

## 5) Überlegen Sie sich zwei mögliche Epics für die Fallstudie und ordnen Sie ihre User Stories jeweils einem der Epics zu.  
1. Epic: Koordinierung mit Teilnehmern: US1, US2  
2. Epic: Automatische Zeitplanung: US3 

## 6a) Welche Quellen für Anforderungen gibt es? Welche Quellen könnten Sie für die Fallstudie nutzen?  
1. Stakeholder: Nutzbar, WWS Inc.  
2. Dokumente: Nicht existent, daher nicht nutzbar  
3. Systeme im Betrieb: Nicht existent, daher nicht nutzbar  

## 6b) Nennen Sie für jede Quellenart mindestens zwei Vor- und Nachteile für deren Verwendung zur Anforderungsermittlung.  
**1. Stakeholder:**  
    \+ Beschreiben gewünschte Funktionen aus unterschiedlichen Perspektiven  
    \+ Steuern das Projekt  
    \- Potenziell mangelhaftes Fachwissen sorgt für Ungenauigkeiten  
    \- Änderungswünsche im Projekt sehr wahrscheinlich  
**2. Dokumente:**  
    \+ Genaue Angaben, klare Informationen  
    \+ Abbildung der gewünschten Prozesse  
    \- Wissen im Fachbereich ist Vorraussetzung  
    \- Unvollständigkeiten möglich  
**3. Systeme im Betrieb:**  
    \+ Demonstrieren einen bisherigen Ablauf und eine gewohnte Art der Interaktion  
    \+ Eingliederung in Umgebung kann verbessert werden  
    \- Können dazu verleiten sich zu sehr an Altlasten zu orientieren  
    \-   

## 7a) Was sind Prototypen und wozu werden diese eingesetzt?  
Prototypen sind Entwürfe mit denen Konzepte und Ideen veranschaulicht werden bevor diese vollständig ausentwickelt sind. Damit lassen sich recht früh Reaktionen und konkrete Vorstellungen für das fertige Produkt finden.  

## 7b) Welche beiden Arten von Prototypen unterscheidet man? Nennen Sie jeweils zwei Vor- und Nachteile für beide Typen.  
**1. Analog**  
\+ Intuitive Technik für Anfertigung, jeder kann Stift und Papier nutzen  
\+ Gewinnung zusätzlicher funktionaler Anforderungen  
\- Keine Weiterentwicklung möglich  
\- Ggf. schwer verständlich wenn bei Erstellung auf mündliche Erklärung gesetzt wurde  
**2. Digital**  
\+ Mock-Ups zum ermitteln welches Erscheinungsbild die Anwendung am Ende haben soll  
\+ Vom Mock-Up aus kann weiterentwickelt werden  
\- Erstellung ist zeitlich und finanziell aufwändig  
\-   

## 7c) Welche Art des Prototypings würden Sie für die Fallstudie verwenden und warum?  
Ich würde horizontale Protoypen im Bereich der Oberfläche anfertigen, es eignen sich sowohl analoge als auch digitale Prototypen. Ich würde wohl einen digitalen Prototypen verwenden.

## 8a) Im Hinblick auf welche Aspekte sollten Anforderungen geprüft werden? Erläutern Sie diese Aspekte und überprüfen Sie Ihre Antwort auf Aufgabe 4.  
- **Inhalt**  
Inhaltliche Prüfung der dokumentierten Anforderung  
Sind Prüfkriterien definiert?  
Notwendigkeit  
- **Dokumentation**  
Formale Prüfung der Anforderung  
Konformität der einzelnen Anforderung  
Konformität des Anforderungsdokuments  
Verständlichkeit  
Eindeutigkeit  
- **Abgestimmtheit**  
Abstimmung der Anforderungen mit Stellern und Stakeholdern  
Abstimmung und Abstimmung nach Änderung  
Konflikte aufgelöst  

## 8b) Warum ist es wichtig, Fehler in Anforderungen möglichst früh zu identifizieren?  
Wenn Fehler nicht früh identifiziert werden, und die Entwicklung schon fortgeschritten ist, kann es zu Verzögerungen kommen wenn z.B. Softwaremodule nicht miteinenader kompatibel sind, weil Fehler und Konflikte in den Anforderungen nicht rechtzeitig gefunden wurden.  

## 8c) Welche Techniken zur Prüfung von Anforderungen kennen Sie? Erläutern Sie diese.  
1. **Inspektion**  
Gemeinsames, intensives, formelles Durcharbeiten der Anforderungen  
2. **Walkthrough**  
Gemeinsames Durchlesen und Durchspielen anhand von Testfällen und Beispielen  
3. **Stellungnahme**  
Unabhängige Dritte werden zur Prüfung herangezogen  

## 9a) Was versteht man unter der Verfolgbarkeit von Anforderungen?  
Verfolgbarkeit beinhaltet den Ursprung einer Anforderung, Abhängigkeiten zu anderen Anforderungen und die Entwicklung von Anforderungen  

## 9b) Warum ist es wichtig und sinnvoll, Anforderungen verfolgen zu können?  
Unnötig gewordene oder unmachbare Anforderungen können so identifiziert werden.  

## 10) Welche Arten von Konflikten können zwischen Stakeholdern auftreten? Erläutern Sie diese und nennen Sie jeweils zwei konkrete Beispiele.  
  - **Sachkonflikt:** mangelnde Informationen, Fehlinformationen, unterschiedliche Interpretationen  
  - **Interessenkonflikt:** subjektiv/objektiv verschiedene Ziele oder Interpretationen  
  - **Wertekonflikt:** unterschiedliche Bewertung von Sachverhalten  
  - **Beziehungskonflikt:** negatives zwischenmenschliches Verhalten
  - **Strukturkonflikt:** ungleiche Macht- und Autoritätsverhältnisse  

## 11a) Welche Techniken zur Konfliktauflösung kennen Sie? Erläutern Sie diese.  
- **Einigung:** Konfliktparteien eignen sich auf gemeinsamen Standpunkt  
- **Kompromiss:** Konfliktparteien treffen sich in der Mitte  
- **Abstimmung:** Konfliktentscheidung durch Abstimmung  
- **Variantenbildung:** Konfliktlösung durch Umsetzung mehrerer Varianten im System  
- **Ober-Sticht-Unter:** Übergeordnete Instanz trifft Entscheidung  
- **Weitere Techniken:** Consider-All-Facts, Plus-Minus-Interesting, Entscheidungsmatrix  

## 11b) Mit welchen Techniken würden Sie die selbstgewählten Beispiel-Konflikte aus der vorherigen Aufgabe lösen? Begründen Sie Ihre Entscheidung.  
  - **Sachkonflikt:** Variantenbildung, da so mehrere Sachverhalte abgedeckt werden können, ohne dass eine Seite explizit auf ihre Anforderungen verzichten muss.  
  - **Interessenkonflikt:** Kompromiss, da so beide Seiten Teile ihrer Anforderungen erfüllt haben können.  
  - **Wertekonflikt:** Kompromiss oder Abstimmung, da diese Methoden erlauben beide Seiten teilweise zu befriedigen oder die Bedürfnisse einer Seite einfach überstimmt werden.  
  - **Beziehungskonflikt:** Ober-Sticht-Unter, da man bei negativen zwischenmenschlichen Verhalten nie ganz sicher sein kann ob eine Einigung zwischen den Seiten nicht noch zu mehr persönlichen Problemen führt.  
  - **Strukturkonflikt:** Ober-Sticht-Unter, da dies ohnehin die einzige Lösung ist auf die man sich bei einem Stukturkonflikt wirklich verlassen kann, wenn das Machtverhältnis bereits ein Problem darstellt.  

## 11c) Wieso ist es wichtig, die Konfliktauflösung zu dokumentieren?  
Bereits gelöste Konflikte können so als Vorlagen für andere Konflikte verwendet werden. Außerdem ist eine klar verzeichnete Konfliktlösung eine einfache Methode Entwickler über erreichte Lösungen zu informieren.  

## 12a) Skizzieren Sie auf Basis der Fallstudie einen Prozess mittels der Prozesslandkarte des Interaction Room (z.B. „Terminvereinbarung erstellen“).  
siehe KW18 Lösung_gincl.pdf  

## 12b) Stellen Sie außerdem den Systemkontext mittels der Integrationslandkarte des Interaction Room dar. Achtung: Die Umsysteme werden in der Fallstudie nur angedeutet! Überlegen Sie sich, welche Umsysteme in Frage kommen könnten.  
siehe KW18 Lösung_gincl.pdf  

## 12c) Erstellen Sie auf Basis der Fallstudie eine Objektlandkarte.  
siehe KW18 Lösung_gincl.pdf  

## 12d) Wählen Sie einen Werttreiber, einen Aufwandstreiber und einen Risikotreiber aus den Annotationen aus. Analysieren Sie die von Ihnen skizzierten Landkarten hinsichtlich dieser Aspekte und markieren Sie Elemente auf den Landkarten, an denen Sie Werttreiber, Aufwandstreiber oder Risikotreiber erkennen mit dem entsprechenden Symbol. Nummerieren Sie die Symbole durch und notieren Sie sich unter der entsprechenden Nummer eine Erläuterung zur Annotation.  
siehe KW18 Lösung_gincl.pdf  
