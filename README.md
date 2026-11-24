# Störfall im Schulnetz

Lernspiel zum Abschluss des Netzwerkteils (Q2 Informatik GK, Abitur 2027 NRW).
Läuft komplett im Browser, ohne Login und ohne Internetverbindung nach dem Laden.

**Spielen:** https://nb-gsn.github.io/Netzwerke/

## Inhalt (ca. 30 Minuten, 17 Aufgaben, 59 Punkte)

1. **Der Netzplan:** Topologien erkennen, Ausfall im Baumnetz beurteilen, n(n−1)/2, Teilvermaschung
2. **Die Notfall-Pizza:** Bestellung live über das Protokoll PIZZA, Zustände, Zustandsdiagramm, Fehlersuche im Dialog
3. **Die Störungsmeldung:** SMTP-Sequenzdiagramm, Zustellung bei 550, Statuscodes und Ports, DNS
4. **Der Weg durch die Schichten:** Kapselung, OSI-Zuordnung, Router bis Schicht 3, Vorteil von Schichtenmodellen

Jede Station liefert einen Buchstaben des Lösungsworts. Am Ende zeigt die Urkunde Punkte, Zeit und einen Prüfcode.

## Für die Lehrkraft

- Rangliste: meiste Punkte gewinnt, bei Gleichstand die kürzere Zeit.
- Prüfcode kontrollieren: https://nb-gsn.github.io/Netzwerke/#pruefen
- Falsche Versuche kosten je 1 Punkt (mindestens 1 Punkt pro gelöster Aufgabe).
- QR-Code: `qr-plakat.png` (Beamer/Aushang) und `qr-code.png`.

---

# SpionCamp: Tatort Schulnetz

Fortsetzung des Störfalls: Jemand hat sich Zugang zum Notenserver verschafft. Der Kurs ermittelt als Forensik-Team in sechs Missionen (je ca. 45 Minuten) zu symmetrischen, asymmetrischen und hybriden Verfahren.

**Camp-Seite:** https://nb-gsn.github.io/Netzwerke/spioncamp/

1. Die abgefangene Nachricht: Fachbegriffe, Caesar von Hand, Kerckhoffs
2. Das Java-Labor: Caesar in BlueJ programmieren (Basis, Standard, Experte)
3. Angriff auf Caesar: Brute Force, Häufigkeitsanalyse, Vigenère
4. Das Schlüsselproblem: Schlüsselaustausch, n(n−1)/2, Farbmisch-Experiment
5. Echt oder gefälscht? Schlüsselpaar, Signatur, Man-in-the-Middle, Zertifikate
6. Finale: Angriff rekonstruieren, Täter überführen, Sicherheitskonzept, Abschlussquiz

**BlueJ-Projekt:** `spioncamp/SpionCamp_Caesar.zip` (in BlueJ über Projekt → ZIP/JAR öffnen). Klassen: `Caesar` (Lückencode), `Beweismittel` (abgefangene Nachrichten), `Pruefstand` (Selbsttest je Stufe).

## Für die Lehrkraft

- Alle Missionen offen: https://nb-gsn.github.io/Netzwerke/spioncamp/#lehrkraft (dort auch Prüfcodes kontrollieren)
- Missionen öffnen sich nacheinander, sobald das Ermittlungsergebnis der vorherigen stimmt. Fortschritt bleibt im Browser des Teams.
- Quiz: 10 Fragen, bis zu 20 Punkte, Prüfcode für die Rangliste.
