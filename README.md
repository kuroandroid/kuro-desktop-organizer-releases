# Kuro Release Center

Repository pubblico destinato esclusivamente alla distribuzione di Kuro Desktop Organizer.

## Contenuto

- `site/stable/appcast.xml` — feed Stable di Sparkle
- `site/beta/appcast.xml` — feed Beta
- `site/latest.json` — metadati leggibili dalla pagina
- GitHub Releases — archivi ZIP, DMG e checksum
- GitHub Pages — hosting HTTPS del centro aggiornamenti

Il codice sorgente dell'app non deve essere pubblicato in questo repository.

## Prima pubblicazione

Dal progetto principale:

```zsh
./Scripts/Updates/prepare-release.sh 1.0.0 100 stable
./Scripts/Updates/publish-release.sh 1.0.0 stable
```

La chiave privata Sparkle non deve mai essere copiata qui.
