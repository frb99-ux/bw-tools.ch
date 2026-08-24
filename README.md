# bw-tools.ch – Container-Ladeplan-Tool (Prototyp 1)

Web-Version des BrogleWorks Container-Ladeplan-Tools, gehostet unter
www.bw-tools.ch (Firebase Hosting).

## Struktur

- `public/index.html` – die App (aktuell: 1:1 Kopie des bestehenden
  Offline-Tools als Ausgangsbasis für Prototyp 1)

## Deployment (Firebase Hosting)

```bash
npm install -g firebase-tools
firebase login
firebase init hosting   # "public" als Public-Directory wählen
firebase deploy
```

## Status

Ausgangsbasis kopiert aus `CONTAINER LADEPLAN SOFTWARE/Prototyp 1/`.
Neue Funktionen für Prototyp 1: siehe Projekt-Notizen (folgt).
