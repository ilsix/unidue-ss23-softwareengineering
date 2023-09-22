# Kapitel 5
## 1a) Erläutern Sie den Begriff Architektur.  
Aus der Baukunst abgeleitet, beschreibt der Begriff Softwarearchitktur die Struktur in welcher Systemkomponenten, Verbindungen, Beschränkungen und Anforderungen angeordnet sind. Sie bildet die Beziehungen von Softwarekomponenten zueinander und zur Umgebung ab.  

## 1b) Warum ist es wichtig, für komplexe Softwareprojekte eine gute Architektur zu entwerfen und zu verwenden?   
Während es möglich wäre sämtlichen Code einer Anwendung in einer Datei zu haben, erhöht das den Entwicklungs- und Pflegeaufwand enorm. Teilkomponenten und Teilsysteme sinnvoll strukturiert auszulagern macht den Quellcode übersichtlicher, einfacher zu verstehen und einfacher zu bearbeiten. Ebenfalls muss nicht der gesamte Quellcode bei einer kleinen Änderung neu kompiliert werden, sondern nur das jeweilige Modul.  

## 1c) Was sind die grundlegenden Unterschiede zwischen Softwarearchitekturen und anderen Architekturen für physische Projekte?  
Im Bereich Softwarearchitektur gibt es, entgegen der realen Architektur, keinerlei Naturgesetze die man beachten muss. Da es keine Materiellen Bezüge gibt, kann Softwarearchitektur schwer zu visualisieren sein. Und je nach Menge der Komponenten, kann die Anzahl möglicher Zustände explodieren.  

## 2) Welche Rolle spielt der Architekturbegriff im Kontext Anforderungsanalyse und Software Design?  
Softwarearchitektur betrachtet Elemente aus dem Requirements Engineering und der Entwurfsphase. Technisch widersprüchliche Anforderungen weden durch Kompromisse gelöst, es werden die Bedürfnisse aller Interessenten bestmöglich verstanden.  

## 3) Erläutern Sie die Bedeutung der Modellpyramide und ihrer einzelnen Stufen.  
- **Unternehmensarchitektur:** Geschäftsprozesse, Systemlandschaft, Anwendungslandschaft, Unternehmensziele,...  
- **Facharchitektur:** Softwaresysteme und deren Schnittstellen aus Anwendersicht  
- **Softwaretechnische Architektur:** Komponenten, Module und deren Aufrufbeziehungen  
- **Systemtechnische Architektur:** Rechner, DBMS, Betriebssysteme, Middleware, Kommunikationsprotokolle, Netzwerke  

## 4) Erläutern Sie, was man unter einer fachlichen Architektur versteht.  
Die fachliche Architketur beschreibt fachliche Komponenten aus der Sicht eines Nutzers. Sie beschreibt welche Schnittstellen zum System einem Nutzer zur Verfügung stehen und wie diese sich in den Datenhaushalt und die Geschäftsprozesse eingliedern.  

## 5a) Was versteht man unter einer Unternehmensarchitektur (Enterprise Architecture, EA)?  
Die Unternehmensarchitektur beschreibt die Zusammenarbeit verschiedener Softwaresysteme eines Unternehmens und wird auch oft als Unternehmenslandschaft bezeichnet. Beschrieben wird der Datenaustausch zwischen einzelnen Systemen und Anwendungen.  

## 5b) Grenzen Sie die Begriffe Unternehmensarchitektur und Softwarearchitektur voneinander ab.  
Die Softwarearchitektur behandelt nur ein einziges Softwaresystem. Ein solches System kann Teil der Unternehmensarchtektur sein. Die Unternehmensarchitektur hat eine strategische Bedeutung für das Unternehmen, während einzelne Systeme theoretisch durch andere ausgetauscht werden können ohne das Gesamtbild der Unternehmenslandschaft zu verändern. Eine Unternehmenslandschaft ändert sich mit der Zeit, während einzelne Softwaresysteme in dieser nicht ausgiebig oder einfach verändert werden können.  

## 6a) Was versteht man unter der Abkürzung EAM/UAM? Erläutern Sie den Begriff.  
**U**nternehmens**a**rchitektur**m**anagement beschreibt die Ausrichtung der IT am für das Unternehmen zutreffenden Geschäftsmodell. Dazu gehört das Analysieren, Konzipieren, Dokumentieren, Planen und Durchsetzen einer Unternehmensarchitektur. Beobachtet wird die Wechselwirkung der einzelnen Fachbereiche wie Personal oder Buchhaltung.  

## 6b) Was sind die typischen Aufgaben eines IT-Unternehmensarchitekten? Nennen und erläutern Sie diese.  
Ein Unternehmensarchitekt analysiert die Abläufe und Bedürfnisse eines Unternehmens um daraus eine angepasste IT-Systemarchtektur zu entwickeln. Informationsverwaltung wird optimiert, es wird eine gemeinsam genutzte Infrastuktur für Informationsaustausch geschaffen um Kosten zu minimieren. Standards und Richtlinien zum Einsatz von IT-Ressourcen werden zusammengestellt und Mitarbeiter werden im Einsatz von zur Verfügung stehenden Systemen und Anwendungen geschult. Vorhandene Systeme werden auf Schwachstellen geprüft welche die Sicherheit oder Leistungsfähigkeit negativ beeinflussen könnten.  

## 7) In der Vorlesung haben Sie die die Bebauungsplanung als Instrument des Enterprise Architecture Managements kennengelernt. Zeichnen Sie schematisch eine einfache Bebauungsplanung für ein fiktives Unternehmen Ihrer Wahl. Erläutern Sie anhand dieser Skizze die Bestandteile der Bebauungsplanung.  
siehe KW21 Lösung_gincl.pdf