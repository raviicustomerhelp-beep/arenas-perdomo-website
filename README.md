# Arenas Perdomo – Deploy auf Vercel

Dieser Ordner ist die fertige, statische Website. Kein Build nötig.

Dateien
- index.html – Hauptseite (alles inklusive: Schrift, Logo, Runtime)
- impressum.html, datenschutz.html – Unterseiten (erreichbar als /impressum und /datenschutz)
- logo.png – Favicon
- vercel.json – saubere URLs und Weiterleitungen

## Variante A: Vercel CLI (2 Minuten)
1. Node.js installieren (nodejs.org), falls nicht vorhanden
2. Terminal in diesem Ordner öffnen
3. `npx vercel login` (mit dem Vercel-Konto einloggen)
4. `npx vercel --prod`
   Fragen mit Enter bestätigen (Project name z. B. arenas-perdomo, kein Build-Command, Output-Directory `.`)
5. Die URL erscheint im Terminal, z. B. https://arenas-perdomo.vercel.app

## Variante B: GitHub
1. Neues Repository auf github.com anlegen (z. B. arenas-perdomo-website)
2. Diese Dateien hochladen (Drag & Drop auf github.com funktioniert)
3. vercel.com → Add New → Project → Repository importieren → Deploy
4. Jede Änderung im Repo wird automatisch veröffentlicht

## Eigene Domain
Vercel → Projekt → Settings → Domains → Domain eintragen und die angezeigten DNS-Einträge beim Domain-Anbieter setzen.
