# git add

## Nutzen

Das Subcommand `add` fügt eine oder mehrere Änderungen an Dateien dem Index hinzu.

Der Index spiegelt stets den kompletten Projektstand wider, es ist also
NICHT nur die Menge der festzuschreibenden Änderungen.

## Beispiele
_git add datei.txt_

Die Datei datei.txt wird dem Index hinzugefügt, d. h., sie ist jetzt bereit, in den nächsten Commit aufgenommen zu werden.

_git add datei1.txt datei2.txt_

Beide Dateien werden gleichzeitig zum Index hinzugefügt.
`git add test.txt`
`git add :/*.csv`
`git add README.md /src/main/java src/main/resources/*.csv`

_git add ._

Das . steht für das aktuelle Verzeichnis und fügt alle geänderten oder neuen Dateien zum Index hinzu.
## Verweise

* [git-status](git-status.md)
