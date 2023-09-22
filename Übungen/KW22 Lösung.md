# Kapitel 5
## 8a) Was ist ein Projektportfolio?  
Ein Projektportfolie ist ein Verzeichnis aller Projekte welche ein Unternehmen durchgeführt hat oder durchführt. Das hilft dabei eine strategische Übersicht über geplante und laufende Projekte zu behalten.  

## 8b) Was versteht man unter dem Portfolio-Management?  
Portfoliomanagement ist ein Zyklus. Dieser beginnt mit einer Ist-Analyse welche den Status der Systeme eines Unternehmens festhält. Ein Minimum ist dabei ein Handbuch aller Anwendungen. In diesem wird für jede Anwendung beschrieben was diese fachlich leistet, welche Komponenten sie beinhaltet, wie mit anderen Anwendungen kommuniziert wird, weitere Daten zur administrativen Beschreibung. Diese Informationen müssen unbedingt konstant aktuell gehalten werden und mit eindeutigen IDs versehen werden.  

## 9) In der Vorlesung haben Sie die Boston Square Cards als Instrument zur Strukturierung des IT-Anwendungsportfolios kennengelernt. Erläutern Sie das Prinzip der Boston Square Cards, indem Sie das IT-Anwendungsportfolio eines fiktiven Unternehmens anhand selbstgewählter Anwendungen (min. 4) skizzieren und in die entsprechende Matrix einsortieren. Begründen Sie Ihre Sortierung.  
siehe KW22 Lösung_gincl.pdf

## 10a) Wozu werden im EAM Frameworks eingesetzt?  
EAM Frameworks helfen dabei die Komplexität und das Wachstum der Artchitektur zu strukturieren. Diese legen die Standards für Struktur und handhabung der Unternehmensarchitektur fest.  

## 10b) Erläutern Sie die Bestandteile eines typischen Enterprise Architektur-Frameworks.  
Typische Bestandteile eines Architektur-Frameworks sind:
- **Ziele und Strategie:** Die langfrstigen Ziele, die das Unternehmen mit der Unternehmensarchitektur verfolgen will  
- **Geschäftsarchitektur:** Beschreibung von Geschäftsprozessen der Oreganisation  
- **IT-Architektur:** Abbildung der Hard- und Software, Daten und Netzwerke  
- **Datenartchitektur:** Speicher- und Verarbeitungsmethoden für Daten innerhalb der Organisation  
- **Anwendungsarchitektur:** Awendungen, welche in der Organisation verwendet werden  
- **Technologiearchitektur:** Technische Plattformen, Infrastrukturen und Sicherheitsrichtlinien    

## 10c) Nennen Sie ein Beispiel für ein EA-Framework und beschreiben Sie kurz dessen Besonderheiten.  
Das Zachman-Framework teilt die unternehmensarchtektur in zwei Dimensionen, Fragestellungen auf einer Achse, die verschiedenen Perspektiven auf der anderen. Jede Zelle zeigt dabei einen Teil der Modells der Unternehmensarchitektur aus genau einer Perspektive zu einer bestimmten Fragestellung.

## 11)  Ordnen Sie die folgenden Artefakte jeweils einer Perspektive und einer Sichtweise im Zachman-Framework zu:...  
- **Zustandsübergangsdiagramm:** TIME-Processing Structure  
- **Geschäftsplan:** MOTIVATION-Business Model  
- **Klassendiagramm:** DATA-System Model  
- **BPMN-Diagramm:** FUNCTION-Business Model  
- **Data definition language / Schema:** WHAT-Detailed Representation  
- **Klassendiagramm aller geplanten Java-Klassen:** FUNCTION-Technology Model  
- **Definition von Geschäftsereignissen:** FUNCTION-Scope  

## 12) Erläutern Sie, was man beim Entwurf von Architekturen unter einem top-down- und bottom-up-Ansatz versteht.  
Für top-down werden Komponenten so lange dekompniert oder zerlegt bis man Arbeitspakete erhält die für einzelne Entwickler umsetzbar sind. Diese kleinsten Einheiten nennt man dann Module.  
Für bottom-up werden Komponenten so lange zusammengefügt bis weiteres Zusammenfügen keine weitere Übersicht mehr bringen würde.  

## 13) Erläutern Sie, was man unter einer softwaretechnischen Architektur versteht. Worin bestehen die wesentlichen Unterschiede zu einer fachlichen Architektur?  
Eine softwaretechnische Architektur baut auf fachlicher Architektur auf und verfeinert diese. Es werden softwaretechnische Komponenten hinzugefügt, Interfaces und Aufrufbeziehungen unter Verwendung eines Komponentenmodells verzeichnet. Die softwaretechnische Archtektur bildet damit die Grundlage des Softwareentwurfs.  

## 14a) Was versteht man unter einer Komponente?  
Eine Komponente ist eine abgeschlossene Einheit deren Leistung explizit definiert sind. Komponenten stellen Dienstleistungen bereit oder beanspruchen diese.  

## 14b) Wie können Beziehungen zwischen Komponenten charakterisiert werden?  
Komponenten die keine Dienstleistungen verwenden werden in Hierarchien als Blätter dargestellt. Die Importschnittstelle einer Komponente definiert welche Dienstleistungen von ihr beansprucht werden. Die Exportschnittstelle definiert welche Dienstleistungen eine Komponente bereitstellt.  

## 15a) Was versteht man unter einem Kontrakt?  
Ein Kontrakt stellt eine informelle Vereinbarung zwischen zwei Komponenten dar, sodass diese problemlos miteinander interagieren können.  

## 15b) Diskutieren Sie, warum es sinnvoll sein könnte, dass eine Softwarekomponente nur einen bestimmten Zweck erfüllt (und nicht mehrere).  
Je kleiner eine Komponente gehalten wird, desto höher ist ihr Potential für Wiederverwendung und die Einfachheit mit der Änderungen durchgeführt werden können. Allerdings erhöht die Teilung in mehrere kleine Teile auch die Verzögerungen die zur Laufzeit auftreten und vor allem den Verwaltungsaufwand zwischen all den Komponenten. Wie so oft kommt es darauf an, die Trennung zu einem adequaten Grad zu finden.  

## 16a) Erläutern Sie, was man unter Architekturmustern versteht. Grenzen Sie diese von Entwurfsmustern ab.  
Architekturmuster sind abstrakter als Entwurfsmuster. Sie legen Strukturen, Schnittstellen und Kommunikationswege fest. Architekturmuster werden früh im Projekt angewandt, während Entwurfsmuster während der Implementierungsphase zum Einsatz kommen. Architekturmuster legen die Gesamtstruktur fest, während Entwurfsmuster auf Ebene einzelner Komponenten eingesetzt werden um spezifische Probleme zu lösen.  

## 16b) Nennen und erläutern Sie ein Beispiel für ein bekanntes Architekturmuster.  
Model-View-Controller ist ein bekanntes Beispiel für Architekturmuster. Eine Nutzereingabe wird an den Controller gegeben. Dieser bereitet das Modell, die Daten, auf, welche dann an den View gegeben werden um dem Nutzer angezeigt zu werden. Von da aus beginnt der Zyklus erneut.  

## 17) Planen Sie auf Basis der fachlichen Architektur aus Aufgabe 6 die softwaretechnischen Komponenten. Berücksichtigen Sie dabei, dass Nutzer sich registrieren und authentifizieren müssen. Planen Sie die Komponenten möglichst so, dass sie die Prinzipien geringe Kopplung, hohe Kohäsion, sowie Information Hiding berücksichtigen. Welche Architekturen können Sie auf Basis Ihres Komponenten-Entwurfs umsetzen? Wählen Sie eine Architektur begründet aus.  


## 18) Was versteht man unter einer systemtechnischen Architektur? Worin bestehen die wesentlichen Unterschiede zu einer softwaretechnischen Architektur?  
Eine Systemartchitektur bezieht sich auf Struktur und Organisation eines gesamten IT-Systems. Dazu zählen Hardware, Software und Netzwerkkomponenten. Mit ihr wird das System als Ganzes betrachtet. Eine softwaretechnische Architektur bezieht sich nur auf Struktur, Organisation und Komponenten einer einzelnen Softwareanwendung. Entscheidungen in der systemtechnischen Architektur finden auf einer hohen Ebene im Projekt statt und beinhalten z.B. Serverkonfigurationen oder Netzwerktopologien.  

## 19a) Wie kann eine Architektur beschrieben werden?  
Architekturen werden mit einer Kombination aus grafischen und textuellen Elementen dargestellt. Diagramme wie Flussdiagramme oder UML-Diagramme können zur Veranschaulichung von Abläufen und Strukturen verwendet werden. Diese sollten durch Texte und Beschreibungen vervollständigt werden.  

## 19b) Was sind die Zwecke einer Architekturbeschreibung?  
Eine Architekturbeschreibung kann in vielen Aspekten hilfreich in einem Projekt sein. Sie verbessert die Kommunikation verschiedener Akteure im Projekt, kann das Schreiben und Instanthalten von Dokumentationen vereinfachen oder Entscheidungsfindungen erleichtern. Und wie wir bereits wissen, sind die Aspekte eines Projekts eng miteinander verwoben, womit eine gut geführte Architekturbeschreibung auch Einfluss auf Budget- oder Risikomanagement haben kann.  

## 20) Arc42  


## 21) Erläutern Sie, was man unter einem Entwurfsmuster (Design Pattern) versteht und aus welchen Teilen es in der Regel besteht.  
Ein Entwurfsmuster ist eine bewährte Lösung für ein bekanntes Problem oder einen bekannten Sachverhalt. Es ist meistens eine abstrakte Vorlage die auf Designprobleme in Softwareprojekten angewandt und angepasst werden kann. Häufig auftretende Probleme können so schnell und zuverlässig gelöst werden. Ein Muster hat einen Namen und beschreibt eine Problemstellung die es zu lösen gilt. Daraufhin wird die Lösung angegeben, in Form eines Diagramms, Pseudocode o.Ä. Neben verwandten Mustern können noch Vor- oder Nachteile gelistet werden die mit der Verwendung des Entwurfsmusters einhergehen.  
