# PicScore
## 1. Gesamtkonzept des Spiels
## 2. Gameplay
Bevor ein User die App nutzen kann, muss er einen Account erstellen. Hier werden folgende Punkte abgefragt:
* Name
* Vorname
* Alter
* Adresse
* Benutzername
* Passwort
* E-Mail Adresse

Wurde der Account aktiviert, wird der User seiner Community zugeordnet.

### 2.1 Punktesystem
1. Jedes Bild bringt zunächst einen Punkt.
2. Freunde oder Community können dem Bild Punkte von 1 bis 10 geben. Der
Durchschnitt wird auf die Punktzahl des Bildes aufgerechnet.
3. Ist ein Tier auf dem Bild ersichtlich, gibt dies 10 Extrapunkte auf die Zwischenpunktzahl. Jedoch kann eine Tierart nur einmal pro Jahr benannt werden.
3. Je seltener Bilder von einem Ort aufgenommen werden, desto höher ist sein
Multiplikator. Dieser liegt in einem Bereich von 1 bis 5 und wird auf den Punkt für
das Bild und des Punkten für die Bewertung angewendet.
4. Ein Bild wird nach 30 Tagen für die Bewertung geschlossen und der
Endpunktestand steht fest.

### 2.2 Bilder
Ein Spot im Umkreis von 20m wird für 30 Tage nach Aufnahme gesperrt.

### 2.3 Rankingliste
1. Es existieren 2 Listen, das Freunderanking und das Communityranking.
2. Punkte für das Freunderanking können nur von Freunde gegeben werden.
3. Punkte für das Communityranking kann jeder im Umkreis von 50km vom Spot
gegeben werden, fallt der User das Bild freigegeben hat.

## 3. Schnittstellen / Kontrollelemente
## 4. Leveldesign
PicScor wird in einerm Ligasystem gespielt hierzu werden alle Nutzer in 4 Ligen unterteilt. Nach erfolgter Erstellung eines Accounts beginnt jeder Nutzer zunächst in der Beginner-League.
Jede Liga hat ihre eigenen Rankinglisten und je nachdem an welcher Position sich der User befindet, kann er sich in diser halten, aufsteigen oder absteigen. Die gesammelten Punkte werden dann am 30. Dezember des Jahres gelöscht.

### 4.1 Beginner-League
In der Beginner-League wird ein Land in einzelne Sektoren, genannt Communitys, unterteilt. Eine Community umfasst dabei eine Mitgliederzahl von circa 100 Personen. Diese stehen im direkten Wettbewerb zueinander, geben sich aber auch untereinander die Bewertungen für die Bilder.
Am 30. Dezember des aktuellen Jahres steht die Rangliste einer jeden Community fest und die besten 5 Nutzer steigen in die nächst höhere Liga auf.

### 4.2 Advanced-Leage
In die Advanced-Leage gelangt man auf zwei Wege. Entweder durch Aufstieg aus der Beginner-League, oder durch Abstieg aus der State-League.
Auch hier bilden 100 Personen jeweils eine Community und stehen im direkten Wettbewerb.
Am 30. Dezember des aktuellen Jahres stehen die Ranglisten der Communitys fest. Die 5 User mit der höchsten Punktzahl steigen dann in die State-League auf. Zusätzlich erhalten die besten 3 kleinere Preise.
Die 5 User mit der geringsten Punktzahl hingegen steigen wieder in die Beginner-League ab.

### 4.3 State-League
Anders als in den anderen beiden Ligen unterteilt sich die State-League nicht nach der Anzahl der Nutzer in einem Gebiet, sondern hier werden ganze Länder zu einer Community zusammengefasst.
Jedoch auch hier erfolgt ein auf- bzw. abstieg der 5 Besten und Schlechtesten in die entsprechende Liga.
Die Preise für die besten 3 entsprechen hier jedoch eiem Wert von etwa 150 - 200 Euro.

### 4.4 World-League
In der World-League befinden sich nun alle Nutzer, die sich in der State-League durchsetzen konnten. Hier ist die Community weltweit angesetzt. Auch hier steigen die 5 Personen mit der geringsten Punktzahl in die State-League ab.
Der Warenwert für die besten 3 entspricht in dieser Liga nun einen Geldwert von 600 - 1200 Euro.

## 5. Grafik und Animation
Da PicScore eine Application für Smartphones ist, ist die Darstellung optimiert für kleine Displays und die Steuerung erfolgt über Gestensteuerung.

Allgemein wird durch wischen nach rechts und links die Navigation zwischen den Bildschirmen realisiert.

### 5.1 Startbildschirm
Im startbildschirm werden Bilder der Community angezeigt, welche noch keine Bewertung vom User erhalten haben. Diese werden untereinander angezeigt. Ein scrollen durch die Bilder wird durch wischen nach oben oder unten realisiert.

### 5.2 Bildschirm - Fotoaufnahme
In der Fotoaufnahme wird die Kamera des Smartphones aktiviert.
Der Nutzer kann nun eine Aufnahme tätigen und nach Auslösung dieses weiter bearbeiten. Nun kann das Bild in eine der Rankinglisten geladen werden. Dabei werden auch die GPS-Koordinaten mit gesendet.

### 5.3 Rankingbildschirm
Hier sieht der Nutzer seine aktuelle Positin in der Rankingliste. Hier kann er zwischen Freundesliste und der Communityliste wechseln.

### 5.4 Bildschirm - Eigene Bilder
Die Ansicht der eigenen Bilder kann auf verschiedene Varianten erfolgen. Entweder als Liste von Bildern, oder in einer Kartenansicht.
Tippt ein Nutzer auf ein Bild, so wird dieses vergrößert angezeigt mit Informationen wie Bewertungsstand und Kommentaren.

## 6. Benötigte Assets
