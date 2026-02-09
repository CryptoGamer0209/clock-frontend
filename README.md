# Digitale Raumuhren – Frontend

Dieses Repository enthält das Frontend für das Projekt **„Digitale Raumuhren mit zentraler Steuerung“**.

Das Frontend besteht aus:
- einer **Administrationsoberfläche** zur zentralen Planung und Verwaltung von Inhalten
- einem **Display-Frontend** zur passiven Anzeige auf digitalen Raumuhren

Die Kommunikation mit dem Backend erfolgt in nahezu Echtzeit über WebSockets.

---

## Funktionen

### Admin-Frontend
- Auswahl und Verwaltung von Räumen
- Kalenderbasierte Planung von:
  - Nachrichten
  - Timern
  - Weckern
  - Bildern und Dokumenten
- Medien-Upload
- Vorschau geplanter Inhalte

### Display-Frontend (Raumuhren)
- Anzeige der Uhrzeit
- Countdown-Timer und Wecker
- Geplante Nachrichten und Hinweise
- Bilder-Slideshows
- Dokumenthinweise (z. B. PDFs, Links)
- Vollbild- / Kiosk-Modus
- Keine Benutzereingaben

---

## Technologie-Stack

- React
- TypeScript
- Tailwind CSS
- WebSockets

---

## Architektur

- Das Frontend verbindet sich über eine REST-API und WebSockets mit dem Backend
- Änderungen werden in Echtzeit an die Raumuhren übertragen
- Modularer Aufbau durch wiederverwendbare Komponenten

---

## Installation & Entwicklung

```bash
npm install
npm run dev
