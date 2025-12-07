# Tesi – Struttura progetto

## Compilazione
Usare **XeLaTeX**:

latexmk -pdf main.tex

Oppure da VS Code premere `Ctrl+Shift+B` / Command Palette.

Il PDF viene generato in `build/`.

## Struttura
- `settings/` → configurazioni LaTeX
- `chapters/` → ogni capitolo in un file separato
- `appendices/` → appendici
- `figures/` → immagini
- `tables/` → tabelle complesse
- `bibliography/references.bib` → gestito con Zotero + Better BibTeX

## Requisiti
- XeLaTeX
- BibLaTeX + Biber
- VS Code + LaTeX Workshop (consigliato)