Von der Fläche zur Form

2 Tage Workshop im Semesterprojekt "Get Up!" bei Prof. Zänsler an der BURG Kunsthochschule Halle 

Sommersemester 2022

______

# Zeitplan 
Dienstag 09:00 – 16:15

09:00 – 10:30  Intro Präsentation 
  - Begrüßung und Vorstellung 
  - 2D zu 3D generell 
    - Schnelldurchlauf Konstruktionsmethoden 
  - 2D zu 3D in der "Industrie"

10:30 – 11:00: Mini Präsentation Ergebnisse der letzten Woche 

11:00 – 11:30: 
  - 2D zu 3D als effiziente digitale Herstellungsmethode
    - Vergleich zu anderen Herstellungsmethoden 
    - Beispiel: The Lasery
    - 247 Taylorsteel 

12:00 – 13:00: Mittagspause 

13:00 – 14:00
Präsentation und Domos : CAD Programme 
  - Konstruktionsmethoden Wiederholung
  - CAD-Programme für bestimmte Konstruktionsmethoden:
    - Sheetmetal (Fusion)
    - Slicer for Fusion
    - Rhino Abwicklung 
    - Grasshopper Plugins 

14:00 – 15:00 :
  - Fokus auf digitale Methoden zum Entwurf 
  - konkrete Demos wie ich an die Mini-Projekte aus der Letzten Woche ran gehen würde
  - Zeit für Diskussion und Fragen
  - Kurze Nachbesprechung

Falls Zeit ist: Beispiel Parametrik bei Blechbearbeitung in Fusion 
16:00 – 16:15 Nachbesprechung, Diskussion

Mittwoch 09:00 – 12:00 

09:00 – 10:30 Präsentation: Material und Prozesseigenschaften in Schnittmusterkonstruktion 
  - Übersicht / Wiederholung Herstellungsprozesse 
  - Schnittbreite und Kerf
  - Dogbone Fillets und Relief-cuts

10:45 – 11:15 Nesting 
  - Opennest 
  - Fusion Nesting 
  - Andere Nesting Software 
  
11:15 – 11:45 Daten Vorbereiten zum Lasern und Schneiden
  - Demonstration: von Fusion zum Laser
    - Export aus Fusion 
    - Import in Illustrator
  - Biegetabellen 
  - (Zeichnungen ) 

11:45 – 12:05 Fragen, Nachbesprechung Feedback, Kritik


___

Link zum Miro-Board: https://miro.com/app/board/o9J_lY664nQ=/?share_link_id=263513794918 


# Workshopinhalte 

## Intro Präsentation

Von der Fläche zur Form in Design und Industrie 

### Wieso Warum Weshalb 

Flache Materialien sind deutlich einfacher zu bearbeiten, trennen, und um- zu formen als Volumenkörper. Viele Entwicklungen in (digitalen) Fabrikationsmethoden machen es einfacher direkt in dreidimensionalen Formen zu denkeen und zu gestalten, jedoch sind diese Herstellungsmethoden nur in wenigen Kontexten anwendbar und bezahlbar. In vielen Objekten werden deshalb flache Materialien durch verschiedene Prozesse geschnitten, umgeformt und zusammengesetzt um die dreidimensionale Form zu erzeugen. 


### CAD Programme / Plugins 
Fusion 360 Sheetmetal 
Fusion 360 Slicer:
  - Abwicklungen 
  - Slot construction 
  - Stacking 
  - 
Solidworks:
  - Sheetmetal 
  - Slot construction 
  - 
Rhino : 
- Abwickelungen 
- 
Rhino+Grasshopper: 
  - Mathematical Origami 
  - Kangaroo Origami
  - Kangaroo Inflatables
  - Flexhopper Inflatables
  - Plugin for Triangular structures
  - Bowerbird Plugin
  - 
Blender:
  - Blender Cloth Simulation 
Marvellous Designer Textile Schnittmuster

### Konstruktionsmethoden

#### Biegen und Abkanten
Abkanten und Biegen 
Falten / Origami
Unterscheidung: Reversibel und Umgeformt

#### Zusammenstecken
Rechtwinklige Schnitte 
Gewinkelte Schnitte

Verbindungsmethoden: 
  - slots
  - Joinery
    - Fingerjoints 
    - Dovetail Joints 
    - Dowels and Bisquits
    - Unconventional Joinery: 
      - Zip-Ties 
      - Rope and Yarn
      - ???? 
  - Verschweißen und Verkleben
  - 


#### Umformen 
- Tiefziehen 
- (Metall) Treiben 
- 

#### Textile Verbindungen 
Verbindungen zwischen Textilen bzw Flexiblen Materialien 
- Nähen 
- Inflatables 
- Verschweißen + Verkleben

### Nesting 

Der Begriff Nesting beschreibt das Anordnen von Einzelteilen, die aus einer Fläche oder Volumen ausgeschnitten werden sollen, sodass möglichst wenig Verschnitt entsteht. 
Die Menge an Verschnitt ist abhängig von der Form der Einzelteile, ihrer Größe, Anzahl und Anordnung sowie den Maßen der Plattem aus der sie geschnitten werden. Je nach Material und Herstellungsprozess kommen noch weitere 
Um dies Zeitsparend und so effizient wie möglich zu machen nutzen wir Software-tools die diese Berechnung übernehmen 

Es wird zwischen 1D, 2D und 3D-Nesting unterschieden. 
1D Nesting kommt beim schneiden von  Stangenmaterialien zum Einsatz. 
2D Nesting nutzt Konturen, die aus Plattenmaterialien geschnitten werden. 
3D Nesting findet beispielsweise beim Pulver oder Resin 3D-Druck eine Anwendung wenn 3d Formen Platzsparend in einem Volumen andgeordnet werden müssen. 

Opennest
Fusion Nesting
Andere Nesting-Software

#### Nestability als Konstruktionskriterium 

Wie gut unsere Einzelteile "Nestbar" sind, ist maßgeblich dafür, wie viel bzw. wenig Verschnitt und Restmaterial wir beim Herstellugsprozess produzieren. 
Wie gut Einzelteile in der Fläche zusammen passen ist Teil der Designkriterien die wir erfüllen müssen. Die "Nestability" sollte vom Beginn des Designprozess mitbedacht werden. 
Generell sind Rechteckige Formen besser Nestbar als Runde, jedoch spielt neben der Form der Einzelteile vor allem die Relation der Maße im Verhältnis zur Plattengröße eine Rolle. 
Nesting ist 

### Einschränkungen in Fertigungsmethoden und Materialien

Jedes Herstellungsverfahren hat Einschränkungen und Eigenheiten, die wir in der Gestaltung unserer Schnittmuster berücksichtigen müssen. 
Verschiedene Materialien haben ebenfalls Eigenheiten, die ein Schnittmuster beeinflussen können. 

#### Minimale Radien 
Kaum ein Schnittverfahren kann eine perfekte, innenliegende Ecke ausschneiden. Es kommt stattdessen zu einem kleinen Radius. Dieser Radius ist abhängig vom Schnittverfahren bzw. dem Verwendetem Werkzeug. Ein Fräser mit 5mm Durchmesser hat einen Radius von mindestens 5mm in jeder innenliegenden Ecke. 
Dies ist vor allem zu beachten, wenn die Einzelteile nach dem Schneiden ineinander gesteckt oder wenn andere Bauteile angebracht werden. 
Um diese Einschränkung zu umgehen können wir sogennante Dogbone-Fillets an innenliegenden Ecken nutzen, um den nötigen Platz aus zu sparen. 

#### Schnittbreite und Kerf
Die meissten Schneidprozesse haben eine Schnittbreite. Meist ist dies die Breite des Schnittwerkzeugs. Beim Sägen und (CNC-) Fräsen ist diese Breite deutlich größer als bei Laser- oder Wasserstrahlschnitt. 
Die Schnittbreite müssen wir beim [Nesting](#Nesting) beachten. 


#### Tabs . 
In manchen Schneidprozessen (z.B. CNC-Fräsen oder Wasserstrahlschneiden mit leichten Materialien) können wir die Einzelteile nicht direkt aus der Platte herausschneiden, da sie sonst vom Schneidewerkzeug umher geschleudert werden könnten. 
Stattdessen nutzen wir sogenannte "Tabs" entlang der Kontur, die das Einzelteil Während des Schneidprozesses halten und im Nachhinein manuell abgetrennt werden können. 