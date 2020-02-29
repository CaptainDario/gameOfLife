# gameOfLife

ModSim2019/2020 Projekt

Mitglieder:
* Louis Donath 798279
* Dario Klepoch 793525


Eine Implementierung von Conway's "Game of Life".

Ziele:

* Spiel:
    * Spielbrett: ✓
        * Grid (unedliche Generieung, wenn die Objekte sich bewegen) ✓
        * auswaelbarer Startkonfig ✓
    * Regeln (wikipedia): ✓
        * Eine tote Zelle mit genau drei lebenden Nachbarn wird in der Folgegeneration neu geboren. ✓
        * Lebende Zellen mit weniger als zwei lebenden Nachbarn sterben in der Folgegeneration an Einsamkeit. ✓
        * Eine lebende Zelle mit zwei oder drei lebenden Nachbarn bleibt in der Folgegeneration am Leben. ✓
        * Lebende Zellen mit mehr als drei lebenden Nachbarn sterben in der Folgegeneration an Überbevölkerung. ✓
    * Zoomen (Raster vergroessern/verkleinern) ✓
    * bewegen (auf dem Raster hin und her bewegen): ✓
        * auf dem spielfeld hin- und her bewegen ✓
        * ~~unedliche Spielbrett Generierung (wenn Grenzen erreicht?)~~ (nur wenn objekte die Grenzen erreichen)
    * Randbedingungen:
        * reflektierend
        * absorbierend ✓
        * periodisch
        * (erweiternd)

* UI (_grafische Benutzeroberflaeche_):
    * Main menu:
        * neues board:   ✓
        * board laden:
            * defaults (_interessante Beispiele_) ✓
            * eigenes board
            * zufaelliges board         ✓
        * selber board erstellen:
            * Systemgroesse ✓
            * Randbedingungen ✓
            * Anfangsbedingungen
            * ~~Regel-string~~
        * Tutorial:
            * Erklaerung der Tastenbelegungen
    * Menubar (_event gesteuerte Programmierung_):
        * play/pause ✓
        * neues Spiel button 
        * einen Schritt-weiter-button ✓
        * zoom in/out button ✓
        * zurück zum Hauptmenü button
        * board speichern
 
* Performance (_Geschwindigkeitsoptimierung_):
    * Multithreaded Generationsberechnung
    * grosse Bereiche in denen keine lebenden Zellen vorkommen ueberspringen
    * nur Zellen neu zeichnen welche auch veraendert wurden ✓
 
* PyInstaller executable:
    * windows
    * Linux 
    * MacOS
     
* Abgabe:
    * Demonstration mit interessanten Beispielen
    
* optional:
    * Hintergrundmusik
