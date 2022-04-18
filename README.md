Von der Fläche zur Form

2 Tage Workshop im Semesterprojekt "Get Up!" bei Prof. Zänsler an der BURG Kunsthochschule Halle 

Sommersemester 2022

____

# Vorbereitung

## Software

Als Vorbereitung für unseren Workshop installiert euch bitte das CAD-Programm Autodesk Fusion 360. Fusion ist in der Education-Version kostenlos und läuft sowohl auf Windows als auch auf MAC. 

## Vorwissen 
Ihr solltet für den Workshop ein Grundverständnis von Fusion360 haben. Falls du die Software noch nie genutzt hast arbeite bitte dieses Tutorial durch: 
XXXXX Link Tutorial 

Wir werden in Fusion die Funktionen der Blechbearbeitung nutzen. Bitte arbeite dazu dieses Tutorial durch, in dem ich die Blechbearbeitung kurz erkläre und die Grundfunktionen zeige. 

XXXXXX Link Tutorial 

______

# Workshopinhalte 

## Intro Präsentation

Von der Fläche zur Form in Design und Industrie 

### Wieso Warum Weshalb 

Flache Materialien sind viel einfacher zu bearbeiten, trennen, und um- zu formen als von Anfang an Volumenkörper zu nutzen. 
Entwicklungen in (digitalen) Fabrikationsmethoden machen es einfacher direkt in dreidimensionalen Formen zu denkein und zu gestalten, jedoch sind diese Herstellungsmethoden nur in wenigen Kontexten anwendbar und bezahlbar. 



### Konstruktionsmethoden

Falten 
Abkanten und Biegen 
Origami

Zusammenstecken
Rechtwinklige Schnitte 
Gewinkelte Schnitte
Verbindungsmethoden: 
  - slots
  - Joinery
    - Fingerjoints 
    - Dovetail Joints 
    - Dowels and Biskets

### Nesting 

Der Begriff Nesting beschreibt das Anordnen von Einzelteilen, die aus einer Fläche oder Volumen ausgeschnitten werden sollen, sodass möglichst wenig Verschnitt entsteht. 
Die Menge an Verschnitt ist abhängig von der Form der Einzelteile, ihrer Größe, Anzahl und Anordnung sowie den Maßen der Plattem aus der sie geschnitten werden. Je nach Material und Herstellungsprozess kommen noch weitere 
Um dies Zeitsparend und so effizient wie möglich zu machen nutzen wir Software-tools die diese Berechnung übernehmen 


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