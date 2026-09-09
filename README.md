# atelier-mura — hébergement des visuels print (Mura)

Ce dépôt **public** héberge les fichiers d'impression des affiches Mura pour que
**Gelato** puisse les télécharger par URL (API `create-from-template`).

## Structure
```
<SÉRIE>/<TAILLE>/<nom>.png
```
- Séries : `A` (minimaliste), puis `C`, `D`, `E` à venir.
- Tailles : `30x40`, `50x70`, `70x100` (cm) — PNG **300 DPI**.

Exemple : `A/50x70/A1-01-cercle-solaire.png`

## URL publique (raw)
Base à utiliser comme `IMAGE_BASE_URL` dans le script Gelato :
```
https://raw.githubusercontent.com/GuillaumeBeYourself/atelier-mura/main
```
→ une image = `https://raw.githubusercontent.com/GuillaumeBeYourself/atelier-mura/main/A/50x70/A1-01-cercle-solaire.png`

## Note
Fichiers HD volontairement publics (nécessaire pour l'ingestion Gelato).
Dépôt supprimable à tout moment. Ne pas committer d'infos sensibles ici.
