# kjlog
log analyzer with extras

Ich denke mal, wir schreiben ein JavaFX Programm, und setzen Java8u40 vorraus.
Build-Tool ist denke ich mal Maven.
Maven ist zwar ein wenig Overkill aber man will ja später wachsen.



Hier kommen noch Ideen

* Riesige Dateien lesen mit wenig Ressourceneinsatz
* Aufteilung von Logfiles in Spalten (wie in Excel?)
* Fixierung mehrer Zeilen während des Scrollens.
* Remote Execution (mit Hilfsprogramm - cut, cat, head, tail, ...)
* Daten Export in eine Datenbank. (mit SQL selektiere)
* Einlesen von Ordnern (meherere Dateien untereinander, nicht nebeneinander, nicht in Tabs (aber Tabs möglich))
* PDF Generieren
* Screenshoot Funktion (ein Bild sagt mehr als ...)
* Clipboard was niemals Vergisst (Option aktivierbar) hier will ich eine 'unendlichen' zyklichen Buffer haben, der Soriert je nach dem was ich mit STRG-C/STRG-V so mache. 
* Pluginfähigkeit um fertige Log-Schablonen für gängige Logfiles zur Verfügung zu stellen
* Liveansicht von Logfiles (vgl. tail -f)


-----
Links: 
* http://jfxtras.org/ - Framework um einige weitere GUI Komponenten zu haben.
* JPA - eclipseLink oder OpenJPA (Apache)
* SSH - Apache SSHD
* http://docs.oracle.com/javase/8/javase-clienttechnologies.htm
