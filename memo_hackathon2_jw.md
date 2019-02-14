# Workgroup 1 - Aufgabe 1

## Website defacing erkennen

### Möglichkeiten/Schnittstellen zur möglichen Erkennung von Manipulation

* mySQL Fehlersuche
* iFrames (sehr auffällig)
* Wörterbuchsuche in html Dokument(Begriffe wie "hacked","pwned",etc.)
* javaSkript Anlayse
    * sind externe .js eingebunden
    * enthalten Skript-Tags kryptische Zeichenketten
    * Black/White List von js vergleichen (Krypto-Mining-Skripte)
    * wenn Möglich - Speicher- und Rechenzeitauslastung von Analysebrowser beobachten
    * remote/local file inclusion erkennen
    * ddos attack erkennen(Verfügbarkeit der Seite)
    * externe Verweise überprüfen soweit Möglich (ist IP/Domain gültig/plausibel)
     
### mögliche Präventionsmaßnahmen

* Website auf alle möglichen (bekannten) Schwachstellen prüfen


# Workgroup 2 - Aufgabe 1

## Wlan Accesspoint simulieren, und DNS Anfrage manipulieren auf gezielte (manipulierte) Webseite

* Angreifer erstellt einen Accesspoint mit identischer SSID
* empfängt der AP ein DNS Paket eines Mobilgeräts, antwortet der AP mit einem gezielten Paket(enthält Adresse/Aufruf der manipulierten Website)


# Workgroup 3 - Aufgabe 1

## Robots.txt einer beliebigen Webpage abfragen und wenn vorhanden durchscannen

### Vorgehen(skizziert)

* get Page ( domain/robots.txt
* if exists -> parse ("dissalow") Einträge -> collect values(url/name)
* iterate trough list -> call http.get(domain/*listElement*)
* if response available -> collect response(2**,4** , etc.)

### Ergebnis
* mit den gesammelten Informationen kann man gezielt domain Schnittstellen analysieren auf Schwachstellen/Lücken


# Workgroup 4 - Aufgabe 2

## verwende Interface von shodan.io, um beliebige domain zu untersuchen und die Ergebnisse entsprechend zu präsentieren

### Versuch/Vorgehen


* Verwendete python library 🐍
    [shodan - official Python library](https://github.com/achillean/shodan-python)

* Zugehörige Dokumentation 🐍
    [shodan - documentation of Python library](https://shodan.readthedocs.io/en/latest/)
    
* (GO Library für GO-Anwender ☺ )
    [shodan - go library](https://github.com/ns3777k/go-shodan)
    
    
# Résumé

* Die Veranstaltung war sehr gut geplant/durchdacht

* Die abwechselnde Struktur der Aufgaben und Team-Zusammensetzung hat sehr gut funktioniert

* Die vorbereiteten Aufgaben (Umfang/Themen/Bearbeitungszeit) waren sehr gut ausgesucht

* Großes Lob an das Team für die Bereitstellung der (digitalen) Infrastruktur und der großzügigen Verpflegung

* Gerne wieder :)
