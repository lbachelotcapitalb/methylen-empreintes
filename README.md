# methylen — empreintes publiées

Ce dépôt ne contient **aucun code**. Il publie, pour chaque version de methylen :

- `journal.json` — les signatures des mises à jour de l'app de bureau. L'app installée refuse une mise à jour qui n'y figure pas.
- `web/<version>/manifeste.json` — l'empreinte SHA-256 de chaque fichier de l'app web servie sur methylen.app.

Vérifier l'app web : comparer `https://methylen.app/accounting/manifeste.json` au manifeste de la même version ici.

L'historique git de ce dépôt est public : une entrée ajoutée ou modifiée se voit.
