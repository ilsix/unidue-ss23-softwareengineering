# Kapitel 4  
## 1) Unsicherheit ist ein inhärenter Bestandteil von Software-Prozessen. Erläutern Sie, in welchen Bereichen eines Softwareentwicklungsprozesses Unsicherheiten herrschen. Was kann man dagegen unternehmen?  


## 2) Warum sind Änderungen ein notwendiger Bestandteil des Softwareentwicklungsprozesses? Worin unterscheidet sich ein Softwareentwicklungsprozess von einem typischen Fertigungsprozess?  


## 3) Erläutern Sie, was man unter dem „Cone of Uncertainty“ versteht.  
Cone of Uncertainty beschreibt die maximal erreichbare Genauigkeit von Schätzungen während des Projektverlaufs. Die Verengungen des Kegels passieren dabei nicht von alleine, sondern werden ausgelöst wenn bestimmte "Meilensteine" erreicht werden. Dazu zählen Produktdefinition, Anforderungen, UI-Designs, etc.  

## 4a) Was versteht man unter der MuSCoW-Priorisierung?  
**Mu**st-Have: Unerlässliche Features die umgesetzt werden müssen  
**S**hould-Have: Wichtige Features die umgesetzt werden sollten, diese machen einen Großteil des Endprodukts aus  
**Co**uld-Have: Mögliche Features die aber keinen immensen Einfluss auf die Vollständigkeit der Produkts haben  
**W**ont-Have-This-Time: Features die für den Erfolg des Projekts unwichtig sind und dieses mal nicht umgesetzt werden  

## 4b) Priorisieren Sie die folgenden User Stories für ein Nachrichtenportal. Begründen Sie für jede User Story Ihre Entscheidung.  
- **Als Mitglied möchte ich mein Passwort ändern können, damit mein Account sicher ist. ->**  
**Must-Have:** Kontosicherheit ist eigentlich auf jeder Plattform eine unglaublich hohe Priorität, hier also auch.  
- **Als Besucher möchte ich Kommentare schreiben können, um an der Diskussion teilhaben zu können. ->**  
**Must-Have:** Interaktion mit Inhalten ist oft der Hauptgrund ein Konto auf einer Seite anzulegen, da die meisten Seiten auch Konsum ohne Konto erlauben.  
- **Als Mitglied möchte ich Inhalte in sozialen Medien teilen können, damit ich Inhalte, die ich interessant finde, unterstützen kann. ->**  
**Should-Have:** Um die Interaktion auszuweiten ist ein Teilen-Feature ebenfalls relevant.  
- **Als Administrator möchte ich einen Last-Bericht generieren können, damit ich verstehen kann, woher Lastspitzen kommen. ->**  
**Should-Have:** Lastspitzen zu ermitteln ist wichtig, falls diese zu Unverfügbarkeiten des Service führen.  
- **Als Besucher möchte ich einen Account erstellen können, damit ich von Mitgliedsrabatten profitieren kann. ->**  
**Wont-have-this-time:** Mitgliederrabatte sind ein Nice-to-have die aber nicht zur Grundfunktion des Nachrichtenportals beitragen.  
- **Als Mitglied möchte ich meine Kontaktdaten aktualisieren können, damit ich vom Administrator kontaktiert werden kann. ->**  
**Should-Have:** Ein durchschnittlicher Nutzer interessiert sich oft nicht allzu sehr für das was Administratoren zu sagen haben. Kontosperrungen werde meist sowieso ohne Warnung oder Erklärungen durchgeführt und etwas wie aktualisierte Nutzungsbedingungen können auch über Popups auf der Seite vermittelt werden.  
- **Als Administrator möchte ich eine Liste der Mitglieder und Besucher sehen, damit ich die Seitenbesuche beobachten kann. ->**  
**Could-Have:** Die Seitenbesuche sind eher ein Nice-to-have, da diese wenig zur allgemeinen Quality-of-service beitragen.  

## 5) Ist es aus Ihrer Sicht vorteilhafter, Aufwände zu unter- oder zu überschätzen? Begründen Sie Ihre Aussage.  
In Maßen ist es wohl besser einen Aufwand zu überschätzen. Besser haben als nicht haben, wenn es um Zeit geht.  

## 6) Es gibt typische Aufwände, die häufig übersehen werden. Diskutieren Sie, warum diese Aufwände in einem komplexen Softwareentwicklungsprojekt leicht übersehen werden können.  


## 7) Was versteht man unter dem Ankereffekt? Illustrieren Sie diesen an einem selbstgewählten Beispiel.  
Der Ankereffekt beschreibt wie Schätzwerte von bereits bekannten Werten oder Werteräumen beeinflusst werden. **Beispiel:** Fährt eine Suzuki Hayabusa schneller oder langsamer als 250km/h? -> Der Wert 250 ist der Anker an dem sich bei der Antwort sehr wahrscheinlich orientiert wird, egal ob man höher oder niedriger schätzt.  
