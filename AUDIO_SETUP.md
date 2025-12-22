# 🎧 MP3-Dateien für den telc B1-B2 Pflege Test

## Download-Anleitung

Die MP3-Dateien müssen manuell aus Airtable heruntergeladen und in das Repository hochgeladen werden.

### Schritt 1: MP3-Dateien herunterladen

Öffne jeden Link in deinem Browser und lade die Datei herunter. Benenne sie entsprechend um:

| Teil | Dateiname | Airtable Record |
|------|-----------|-----------------|
| Hören Teil 1 | `hoeren_teil1.mp3` | recxqT2nq21ME9ReI |
| Hören Teil 2 | `hoeren_teil2.mp3` | recKAKv6q18jRzbTB |
| Hören Teil 3 | `hoeren_teil3.mp3` | recJd9FYdyuD5s7Nw |
| Hören Teil 4 | `hoeren_teil4.mp3` | recbPRtZr680SmXmk |

### Schritt 2: In Airtable die MP3s finden

1. Gehe zu: https://airtable.com/app5dhxQ3aDALoEgu/tblsdn7C7MISWiOcL
2. Filtere nach Modul = "Hören"
3. Klicke auf jeden Record und lade die MP3 aus dem Feld "Mp3 Neu" herunter

### Schritt 3: In GitHub hochladen

1. Erstelle einen Ordner `audio/` im Repository
2. Lade die 4 MP3-Dateien hoch:
   - `audio/hoeren_teil1.mp3`
   - `audio/hoeren_teil2.mp3`
   - `audio/hoeren_teil3.mp3`
   - `audio/hoeren_teil4.mp3`

### Erwartete Dateigrößen

- Teil 1: ca. 248 KB (5 kurze Gespräche)
- Teil 2: ca. 251 KB (längeres Übergabegespräch)
- Teil 3: ca. 854 KB (5 Durchsagen)
- Teil 4: ca. 388 KB (Gespräch mit 3 Personen)

### Nach dem Upload

Die `index.html` ist bereits konfiguriert, um die Dateien aus dem `audio/` Ordner zu laden:
- `audio/hoeren_teil1.mp3`
- `audio/hoeren_teil2.mp3`
- `audio/hoeren_teil3.mp3`
- `audio/hoeren_teil4.mp3`

GitHub Pages wird die Dateien automatisch bereitstellen.

---

## Alternative: Eigenes Hosting

Du kannst die MP3s auch auf anderen Plattformen hosten:
- **Cloudflare R2** (kostenlos bis 10GB)
- **AWS S3**
- **Google Cloud Storage**

Dann musst du die URLs in `index.html` anpassen.
