FIX FÜR DIE WEISSE SEITE

1. In GitHub nur index.html durch diese neue index.html ersetzen.
2. Die vorhandenen Ordner images/ und icons/ NICHT löschen.
3. Die vorhandene Datei sw.js löschen. Diese Version verwendet bewusst keinen Service Worker, damit kein alter Cache die App blockiert.
4. manifest.webmanifest kann bestehen bleiben.
5. Commit auf main.
6. GitHub Pages baut automatisch neu.
7. Danach die GitHub-Pages-Adresse mit Strg+F5 oder in einem privaten Fenster öffnen.

Die App bleibt eine Single-HTML-App: alle fünf Ansichten wechseln ohne Seitenreload.
