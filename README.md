# LaTeX Vorlage - Abschlussarbeit 

### Einführung

Zum Schreiben einer Abschlussarbeit sollte [LaTeX](https://www.latex-project.org/) bei der 
Toolauswahl in Betracht gezogen werden. Die Vor- und Nachteile werden in zahlreichen Foren 
ausführlich diskutieret, weshalb ich hier nicht explizit darauf eingehen will. 

Die Erfahrung zeigt, dass die ursprüngliche Skepsis aller Studenten, die mit dieser Vorlage ihre
Abschlussarbeit geschrieben haben, innerhalb von wenigen Tagen verflogen ist und sie die Vorteile 
erkannt haben. Ab diesem Zeitpunkt habe ich nur noch positives Feedback bekommen.

Diese Vorlage bietet eine strukturierte Vorlage, die sich auch für sehr umfangreiche Arbeiten 
entsprechend skalieren lässt. Auf der Grundlage meiner eigenen Erfahrungen sowie den Rückmeldungen 
zahlreicher Studenten enthält diese Vorlage eine sehr große Zahl notwendiger und nützlicher 
Fremdbibliotheken. 

Diese Vorlage hat folgende Ziele:
1. Einfache Einführung in LaTeX durch viele Beispiele zur korrekten Verwendung von Referenzen, 
Tabellen, Acronymen, etc.
2. Anpassung der Vorlage an die spezifischen Vorlagen der Uni/Hochschule


### Vorbereitungen

Es gibt eine initiale Entscheidung bevor auf die Installation eingegangen werden kann. Soll die 
Abschlussarbeit lokal in einem Editor oder in einem Online-Editor durchgeführt werden? Letzterer 
ist für Einsteiger aus meiner Sicht einfacher zu verwenden, weil man sich zum einen nicht um das 
lokale Setup von Compiler und Editor sowie zum anderen die Vielzahl von erstellen Dateien kümmern 
muss.

* Ein möglicher Online-Editor ist [Overleaf](https://www.overleaf.com), in den man auch ein gesamtes 
Projekt im `.zip` Format hochladen kann.

* Alternativ muss ein lokaler Editor wie [TexStudio](https://www.texstudio.org/) sowie eine 
betriebssystemabhängige TeX Implementierung wie [MiKTeX](https://miktex.org/) oder 
[MacTeX](https://tug.org/mactex/) eingerichtet werden.


### Getting Started

Lade die Vorlage herunter und binde das Projekt in deinen bevorzugten Editor ein.

```sh
$ git clone https://github.com/sw1ld/latex-theses-template.git
```

Als erste Schritte würde ich folgende Vorgehensweise empfehlen:

* Versuche die Beispiele zu verstehen
* Ändere den allgemeine Daten wie Vor- und Nachnamen, Titel, Ort etc.
* Binde die Dateien `Einleitung.tex` und `Schlussbetrachtung.tex` anstelle der Datei `Beispiele.tex`
ein
* Kommentiere alles aus, was du nicht brauchen wirst (z.B. Quellcodeverzeichnis)
