h1. Knowledgebase

Hier werden allgemeine Infos zur Nutzung der Tools gegeben. Es soll ein grober Überblick geschaffen werden um das gesamte Bild verstehen zu können.

h3. Howto github
Github ist eine Plattform für das Tool git. Git ist ein Tool zur Versionierung von Klartextdateien (z.B. .txt .rtf .html). Eine wesentliche Funktion ist der Abgleich zwischen Versionen (aka _Commit_).

h4. Wichtige Konzepte:
- Lokale Kopie ("Repository")
Zur Nutzung von Dateien wird eine komplette Kopie erstellt. Dies kann sowohl auf dem eigenen Rechner als auch auf dem eigenen Account einer Onlineplattform sein.
Praktisch bedeuted das: Alles wird in einem Ordner abgespeichert; Unterordner sind möglich.
- Dezentralität
Alle Kopien sind gleichwertig. Es gibt keinen zentralen "Master", der festlegt was "richtig" ist.
Praktisch bedeuted das: Welches _Repository_ "maßgeblich" ist entscheidet sich allein durch Übereinkunft der Nutzer

h4. Wichtige Begriffe:
- Commit (dt: Verpflichten)
Eine Momentaufnahme aller Dateien. Jeder _Commit_ stellt eine unabhängige Version dar. Commits können Teil von beliebig vielen _Branches_ und _Repositories_ sein.
- Branch (dt: Zweig)
_Commits_ werden in zeitlicher Abfolge hintereinander angeordnet. Gespeichert werden jeweils die durchgeführten Änderungen. Der Vorteil: Dateien die nicht verändert wurden müssen nicht erneut gespeichert werden.
- Merge (dt: Zusammenführen)
Zusammenführen von zwei _Branches_ in einem neuen _Commit_. Unterschiede müssen ggf manuell geprüft und aufgelöst werden.
- Fetch (dt: abrufen)
Prüfen eines entfernten _Repositories_ auf Änderungen.
- Pull (dt: ziehen)
Herunterladen von neueren _Commits_ aus einem entfernten Repository. Sinnvollerweise wird vor einem _Pull_ ein _Fetch_ ausgeführt.
- Push (dt: schieben)
Hochladen eines _Commits_ in ein entferntes _Repository_

h4. Anwendung
1. Fetch (um auf den aktuellen Stand zu kommen)
2. Pull (um eventuelle Änderungen herunter zu laden)
3. Änderungen lokal durchführen + speichern
4. _Commit_ im lokalen _Repository_ erstellen
5. _Push_ des lokalen _Commits_ in ein entferntes _Repository_

h.3 Howto html
html ist eine sogenannte Auszeichnungssprache. Solche Sprachen werden genutzt um Informationen (Text/ Zahlen/ Wochentage/ Preise/ Vornamen/ .... ) zu strukturieren. Eine html-Datei kann als reiner Text betrachtet werden ("Quellcode"). In einem Browser wird der Quellcode ausgewertet und die Informationen wie angegeben dargestellt um die Nutzung einfach und ansprechend zu ermöglichen.

h.4 Wichtige Konzepte
- Boxmodel
Informationen werden zusammengefasst wie Schuhe in einem Karton. Jede Box kann weitere Boxen enthalten.
- Tags (dt: Etikett)
Jede Box wird durch einen _öffnenden_Tag_ begonnen und durch einen _schließenden_Tag_ abgeschlossen. Der _Tag_ beschreibt möglichst genau die Art der enthaltenen Informationen (Überschrift/ Text/ Link/ Bild/ Tabelle/ Aufzählung/ Video.... ).  
- Attribute
Es können mit Hilfe von _Attributen_ weitere Angaben zur Darstellung gemacht werden wie z.B. Schriftfarbe, Hintergrundfarbe, Breite der Darstellung, Höhe der Darstellung, ...

h.4 Anwendung
1. Öffnende Tags haben immer folgendes Format:
<p>
<div>
<button>
2. Schließende _Tags_ haben immer folgendes Format:
</p>
</div>
</button>
3. Attribute werden immer im _öffnenden_Tag_ angegeben:
<link href="https://youtube.com/abc123">
  knuffiges Falkenvideo
</link>

h.4 Beispiel
<p>
  Dies ist eine Box die für Text ausgelegt ist. Dieser Text entspricht der Information die strukturiert werden soll.
</p>

h.4 Hilfreiche Nachschlagewerke
- https://developer.mozilla.org/en-US/docs/Web/HTML/Reference  // Auflistung und Erklärung aller verfügbaren Tags
