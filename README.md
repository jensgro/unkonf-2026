# Vortrag für die uinkonf 2026 in Mannheim

Anbei ein Vortrag über die View Transitions API und deren Anwendung mit Reveal.js.
Ich verwende eine angepasste Version von Reveal.js, die ich "Reveal-Jens" nenne. Der Quellcode und die Anpassungen sind in diesem Repository enthalten. Wichtig ist dabei die Erstellung der Präsentation mit Markdown innerhalb der HTML-Datei.

## Reveal-Jens

Das Ganze basiert auf einem Ergebnis von reveal-md (das nicht mehr weiterentwickelt wird).

Alles ist so vorbereitet, dass mit normalem Markdown innerhalb der HTML-Datei geschrieben werden kann.

Neue Seiten werden mit ``<!--s-->`` für neue Kapitel und ``<!--v-->`` für neue Seiten innerhalb der Kapitel erstellt.

Alle notwendigen Dateien existieren lokal. Die beiden persönlichen CSS-Dateien könnten evtl. noch einmal überarbeitet werden. Theoretisch könnte daraus ein darkmode-Theme werden.

### Sonderlösung

Eine zweigeteilte Ansicht erzeugen wir mit HTML:

````html
<div class="splitted">
  <div>
  links
  </div>
  <div>
    rechts
  </div>
</div>
````