# gameOfLife

ModSim2019/2020 Projekt

Mitglieder:
* Louis Donath 798279
* Dario Klepoch 793525


Eine Implementierung von Conway's "Game of Life".

Ziele:

* Spiel:
    * Spielbrett:
        * Grid (unedliche Generieung, wenn die Objekte sich bewegen)
        * auswaelbarer Startkonfig ✓
    * Regeln (wikipedia): ✓
        * Eine tote Zelle mit genau drei lebenden Nachbarn wird in der Folgegeneration neu geboren. ✓
        * Lebende Zellen mit weniger als zwei lebenden Nachbarn sterben in der Folgegeneration an Einsamkeit. ✓
        * Eine lebende Zelle mit zwei oder drei lebenden Nachbarn bleibt in der Folgegeneration am Leben. ✓
        * Lebende Zellen mit mehr als drei lebenden Nachbarn sterben in der Folgegeneration an Überbevölkerung. ✓
    * Zoomen (Raster vergroessern/verkleinern) ✓
    * bewegen (auf dem Raster hin und her bewegen):
        * auf dem spielfeld hin- und her bewegen ✓
        * unedliche Spielbrett Generierung (wenn Grenzen erreicht?)
 
* UI (_grafische Benutzeroberflaeche_):
    * (Tutorial)
    * Main menu:
        * neues Spiel:   
            * board laden
            * zufaelliges board
            * selber board erstellen board:
                * Systemgroesse
                * Randbedingungen
                * Anfangsbedingungen
                * Regel-string
    * Menubar (_event gesteuerte Programmierung_):
        * play/pause ✓
        * neues Spiel button 
        * einen Schritt-weiter-button
        * zoom in/out button ✓
        * neues Spiel Button
 
* Performance (_Geschwindigkeitsoptimierung_):
    * Multithreaded Generationsberechnung
 
* PyInstaller executable:
    * windows
    * Linux 
    * MacOS
     
* Abgabe:
    * Demonstration mit interessanten Beispielen
