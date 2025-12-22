# telc Deutsch B1-B2 Pflege - Übungstest

## 🏥 EnjoyYourSchool UG

Vollständiger Online-Übungstest für die telc B1-B2 Pflege Prüfung.

### 📋 Testübersicht

| Modul | Teile | Aufgaben | Zeit |
|-------|-------|----------|------|
| 📖 Lesen | 5 | 35 | 55 Min |
| 🎧 Hören | 4 | 25 | 30 Min |
| ✍️ Zusatz | 4 | 58 | 55 Min |
| **Gesamt** | **13** | **118** | **140 Min** |

### ✨ Features

- ✅ Split-View Layout (Text links, Aufgaben rechts)
- ✅ Registrierung mit Name, Email, Herkunftsland
- ✅ Einmal-Test-Zugang (verhindert Wiederholung)
- ✅ Audio-Player für Hörverständnis mit Abspiellimit
- ✅ Automatischer Timer mit Auto-Submit
- ✅ Fortschrittsanzeige
- ✅ Sofortige Auswertung
- ✅ Airtable-Integration für Ergebnisspeicherung

### 🚀 Deployment

#### GitHub Pages (Empfohlen)

1. Repository Settings → Pages
2. Source: Deploy from branch
3. Branch: main / (root)
4. Save

Website wird verfügbar unter: `https://USERNAME.github.io/telc-gesamttest/`

#### Vercel

1. Import Repository auf vercel.com
2. Deploy

### 🔧 Airtable-Integration

Um Ergebnisse in Airtable zu speichern:

1. Erstelle einen Personal Access Token in Airtable
2. Füge ihn in `index.html` ein:

```javascript
const AIRTABLE_CONFIG = {
    baseId: 'app5dhxQ3aDALoEgu',
    tableId: 'tblMiu73WlkOEiaKE',
    apiKey: 'pat...' // Dein Token hier
};
```

### 📁 Tabelle: telc B1-B2 Test Ergebnisse

Felder:
- Name, Email, Herkunft
- Lesen/Hören/Zusatz Punkte & Prozent
- Gesamt Punkte & Prozent
- Bestanden (Checkbox)
- Verbrauchte Zeit
- Test Datum

### 📝 Lizenz

© 2024 EnjoyYourSchool UG - Alle Rechte vorbehalten
