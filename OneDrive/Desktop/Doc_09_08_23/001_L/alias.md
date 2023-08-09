Alias
Was ist ein Alias?
In Linux ist ein Alias eine Funktion der Shell, die es ermöglicht, kurze benutzerdefinierte Befehle oder Abkürzungen für längere Befehle oder Befehlsketten zu erstellen. Ein Alias ist im Wesentlichen eine Zuordnung eines bestimmten Namens zu einem Befehl oder einer Befehlskette.

Wie erstelle ich einen Alias?
Um einen Alias in der Linux Bash zu erstellen, kannst du die folgende Syntax verwenden:

alias aliasname='Befehlszeile'
Ersetze dabei "aliasname" durch den gewünschten Alias-Namen und "Befehlszeile" durch den Befehl oder die Befehlskette, die du mit diesem Alias verknüpfen möchtest.

Hier ist ein Beispiel:

alias ll='ls -alF'
Mit diesem Alias kannst du nun "ll" anstelle von "ls -alF" verwenden, um das erweiterte Inhaltsverzeichnis des aktuellen Verzeichnisses anzuzeigen.

Um sicherzustellen, dass deine Aliase bei jedem Start der Bash-Sitzung verfügbar sind, füge sie in deine Bash-Konfigurationsdatei (z. B. ~/.bashrc oder ~/.bash_aliases) hinzu. Öffne einfach die Datei in einem Texteditor und füge die Alias-Zuweisungen am Ende der Datei hinzu. Nachdem du die Datei gespeichert hast, werden die Aliase bei jedem Start einer neuen Bash-Sitzung automatisch geladen.

Um deine Bash-Konfiguration sofort neu zu laden, damit die neuen Aliase verfügbar sind, führe den folgenden Befehl aus:

source ~/.bashrc
Oder falls du die Aliase in der Datei ~/.bash_aliases gespeichert hast:

source ~/.bash_aliases
Danach sind deine Aliase einsatzbereit. Du kannst sie einfach eingeben, ohne sie jedes Mal neu zu definieren.