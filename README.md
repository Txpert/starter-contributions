# starter-contributions

### Neues Repository erstellen

1. Melde dich bei GitHub an und klicke auf das Plus-Symbol (+) in der oberen rechten Ecke der Seite.
2. Wähle "New repository" aus.
3. Gib deinem Repository einen Namen, zum Beispiel `about-me` oder `lebenslauf`.
4. Optional: Füge eine Beschreibung hinzu, z.B. "Mein Lebenslauf und Über mich Seite".
5. Setze ein Häkchen bei "Initialize this repository with a README".
6. Klicke auf "Create repository".

### Repository klonen

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="Repository klonen" />

Klone das Repository auf deinen Computer. Klicke auf die Schaltfläche "Clone or download" und anschließend auf das "copy to clipboard"-Symbol.

Öffne eine Kommandozeile und gib den folgenden git-Befehl ein:

```
git clone "Deine kopierte URL"
```

Statt 'Deine kopierte URL' (ohne Anführungszeichen) füge die Repository-URL aus dem vorherigen Schritt ein.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="URL kopieren" />

Beispiel:

```
git clone https://github.com/dein-Name/first-contributions.git
```

An der Stelle 'dein-Name' muss dein GitHub-Nutzername stehen. Mit diesem Befehl kopierst du den Inhalt deines first-contributions-Repository von GitHub auf deinen Computer.

### Dateien erstellen und bearbeiten

Navigiere in das Verzeichnis des geklonten Repositories:

```sh
cd about-me
```

Erstelle eine Datei namens `LEBENSLAUF.md`:

```sh
touch LEBENSLAUF.md
```

Bearbeite die `LEBENSLAUF.md` Datei und füge deinen Lebenslauf in Markdown hinzu:

Bearbeite die `README.md` Datei und füge einen Verweis auf die `LEBENSLAUF.md` hinzu:

```markdown
# Über mich

Willkommen auf meiner GitHub-Seite! Hier finden Sie Informationen über mich und meinen Lebenslauf.

## Lebenslauf

Mein vollständiger Lebenslauf ist [hier](LEBENSLAUF.md) verfügbar.

## Projekte

Hier sind einige meiner bisherigen Arbeiten:

- [Projekt 1](https://github.com/DEIN-NUTZERNAME/projekt1)
- [Projekt 2](https://github.com/DEIN-NUTZERNAME/projekt2)
- [Projekt 3](https://github.com/DEIN-NUTZERNAME/projekt3)

Schauen Sie sich gerne meine Repositories an, um mehr über meine Arbeit zu erfahren.
```

### Änderungen committen und pushen

Füge die Dateien zum Git-Index hinzu, committe die Änderungen und pushe sie zum Remote-Repository:

```sh
git add README.md LEBENSLAUF.md
git commit -m "Added CV and updated README with links"
git push origin main
```

### Betrachte dein Repository auf GitHub

Navigiere zu deinem Repository auf GitHub (z.B. `https://github.com/DEIN-NUTZERNAME/about-me`). Du solltest nun deine `README.md` Datei sehen, die auf die `LEBENSLAUF.md` verweist und Links zu deinen Projekten enthält.

---
