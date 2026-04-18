# notepad
How to set up Notepad++ / Notepad Plus Plus

## Settings

### Part 1
- How to open settings / preferences (A):
  - Menu bar --> Settings --> Preferences
  - Menüleiste --> Einstellungen --> Optionen
- How to change keyboard shortcuts (B):
  - Menu bar --> Settings --> Shortcut Mapper
  - Menüleiste --> Einstellungen --> Tastenkombinationen verwalten

### Part 2
- Change tabs (go to right) by pressing `Ctrl` + `Tab`
  - Soll-Zuweisung (target): Nächster Tab (Next Tab) - Line 225
  - Standard-Zuweisung (default): Zum nächsten Dokument wechseln (Switch to next document) - Line 230
- Change tabs (go to left) by pressing `Ctrl` + `Shift` + `Tab`
  - Soll-Zuweisung (target): Vorheriger Tab (Previous Tab) - Line 226
  - Standard-Zuweisung (default): Zum vorherigen Dokument wechseln (Switch to previous document) - Line 229
- Open keyboard shortcuts (B) --> Search for "tab" --> Add desired shortcuts --> Remove default / conflicting shortcuts

### Part 3
- Show space characters
- Menüleiste --> Ansicht --> Symbole anzeigen --> Leerzeichen und Tabulatoren anzeigen (siehe unten)
- Menu bar --> View --> Show Symbol --> Show Space and Tab, Show Non-Printing Characters, Show Control Characters & Unicode EOL, Show Indent Guide, Show Wrap Symbol

### Part 4
- Automatic line breaks
- Menüleiste --> Ansicht --> Automatischer Zeilenumbruch
- Menu bar --> View --> Word wrap

### Part 5
- Disable/deactivate the orange highlight for changed rows (Change history feature)
- Settings --> Preferences --> Margins/Border/Edge --> uncheck "Change history"

### Part 6
- Disable the pinned tab feature
- Settings --> Preferences --> Tab Bar --> uncheck "Enable pin tab feature"

### Part 7
- Disable the shortcut `Ctrl` + `T` for transposing lines (Line 92 - SCI_LINETRANSPOSE).
- This shortcut sometimes interferes with the shortcut `Ctrl` + `Z` that is used to undo the last action (German keyboard layout).
- Open keyboard shortcuts (B) --> Section: Scintilla --> Change the existing shortcut to nothing
