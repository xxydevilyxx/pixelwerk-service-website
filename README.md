# PixelWerk – Website Template

Premium, responsive One-Page-Website für einen Bildbearbeitungs-, Foto- oder Creative-Service.

Dieses Projekt ist als **verkaufsfertiges Template** gedacht. Der neue Besitzer muss vor dem produktiven Einsatz noch seine eigenen Inhalte, Kontaktdaten, Rechtstexte und ggf. Zahlungs-/Upload-Prozesse einrichten.

---

## 1. Dateien und Struktur

```
pixelwerk-service-website/
├── index.html
├── styles.css
├── assets/
│   ├── pixelwerk-logo.svg
│   ├── pixelwerk-mark.svg
│   └── portfolio-showcase.png
└── README.md
```

Die Website ist **statisch** und benötigt keinen Build-Prozess und kein Backend.

---

# Einrichtung – Schritt für Schritt

## Schritt 1 – Projekt kopieren

1. Lade das Template herunter oder kopiere das GitHub-Repository.
2. Entpacke die Dateien.
3. Öffne das Projekt lokal in einem Browser oder starte es über einen einfachen lokalen Webserver.

Es gibt keine `npm install`- oder Build-Schritte.

---

## Schritt 2 – Name und Branding ändern

In `index.html` nach **PixelWerk** suchen.

Anpassen:

- Firmen-/Markenname
- Claim
- Beschreibung
- Navigation
- Footer

### Logo

Die beiden Dateien:

- `assets/pixelwerk-logo.svg`
- `assets/pixelwerk-mark.svg`

durch das eigene Logo ersetzen.

Wenn andere Dateinamen verwendet werden, müssen die Bildpfade in `index.html` angepasst werden.

---

## Schritt 3 – Kontaktdaten ersetzen

In `index.html` nach:

```
DEINE-EMAIL@BEISPIEL.DE
```

suchen und durch die echte Geschäftsadresse ersetzen.

Aktuell verwendet das Template ein einfaches `mailto:`-Formular.

**Wichtig:** Für einen professionellen Produktiveinsatz sollte das Formular später besser über einen echten Formular-/Backend-Dienst laufen. Ein reines `mailto:`-Formular hängt vom Mailprogramm des Besuchers ab.

---

## Schritt 4 – Portfolio austauschen

Das aktuelle Beispielbild:

```
assets/portfolio-showcase.png
```

ist nur Demo-Material.

Für einen echten Kunden sollte es durch eigene Arbeiten ersetzt werden.

Empfehlung:

1. Nur eigene Arbeiten oder zur Nutzung freigegebene Bilder verwenden.
2. Vorher/Nachher-Beispiele klar kennzeichnen.
3. Keine erfundenen Kunden, Bewertungen oder Ergebnisse veröffentlichen.
4. Bilder für Mobile optimieren.
5. Dateigröße möglichst klein halten, damit die Website schnell lädt.

---

## Schritt 5 – Leistungen anpassen

In `index.html` den Bereich:

```
LEISTUNGEN
```

bearbeiten.

Anpassen:

- Leistungsnamen
- Beschreibungen
- Preise
- Reihenfolge
- Icons

Beispiele:

- Bildbearbeitung
- Webdesign
- Social-Media-Design
- Fotografie
- Video
- Übersetzung
- Marketing

---

## Schritt 6 – Preise anpassen

Im Bereich `PREISE` die Beispielpreise durch die eigenen Preise ersetzen.

Besonders prüfen:

- Währung
- Leistungsumfang
- Anzahl der Korrekturen
- Lieferzeit
- Mengenrabatte
- individuelle Angebote

Keine Preise versprechen, die tatsächlich nicht eingehalten werden können.

---

## Schritt 7 – Texte und SEO anpassen

Im `<head>` von `index.html` ändern:

- `<title>`
- `meta description`
- `theme-color`

Zusätzlich empfehlenswert:

- Open-Graph-Tags für Social Media
- eigenes Favicon
- eindeutige Seitentexte
- passende Suchbegriffe
- Ortsangabe, falls lokal gearbeitet wird

---

## Schritt 8 – Rechtliche Seiten ergänzen

**Vor dem kommerziellen Livegang unbedingt prüfen.**

Je nach Land, Geschäftsmodell und Zielgruppe können insbesondere erforderlich sein:

- Impressum
- Datenschutzerklärung
- Cookie-/Consent-Lösung, falls entsprechende Technologien eingesetzt werden
- Widerrufs-/Verbraucherinformationen, falls relevant
- Gewerbe-/Unternehmensangaben
- AGB, falls benötigt

Die vorhandenen Texte sind **keine Rechtsberatung**.

---

## Schritt 9 – Formular testen

Nach dem Eintragen der eigenen E-Mail:

1. Website öffnen.
2. Kontaktformular ausfüllen.
3. Testanfrage senden.
4. Prüfen, ob die Nachricht tatsächlich ankommt.
5. Auf Mobile testen.
6. Prüfen, ob die E-Mail-Adresse korrekt angezeigt bzw. verarbeitet wird.

---

## Schritt 10 – Mobile testen

Mindestens testen auf:

- iPhone Safari
- Android Chrome
- Desktop Chrome
- Desktop Safari/Firefox/Edge

Besonders prüfen:

- Navigation
- Menü öffnen/schließen
- Buttons
- Kontaktformular
- Preise
- Bilder
- horizontales Scrollen
- fixierten CTA
- Ladegeschwindigkeit

---

## Schritt 11 – Website veröffentlichen

### Option A: GitHub Pages

1. Repository auf GitHub erstellen.
2. Dateien in den Repository-Root laden.
3. **Settings → Pages** öffnen.
4. Als Quelle den Branch `main` und den Root-Ordner auswählen.
5. Speichern.
6. Die von GitHub angezeigte Website-URL öffnen.

### Option B: Vercel

1. Repository mit Vercel verbinden.
2. Projekt importieren.
3. Framework/Build-Command nicht erforderlich.
4. Root-Verzeichnis verwenden.
5. Deploy starten.
6. Eigene Domain verbinden, falls vorhanden.

---

## Schritt 12 – Eigene Domain verbinden

Für einen professionellen Auftritt empfiehlt sich eine eigene Domain.

Beispiel:

```
www.deine-domain.de
```

Danach:

1. Domain beim Registrar kaufen.
2. DNS-Einstellungen gemäß Hosting-Anbieter setzen.
3. Domain im Hosting hinterlegen.
4. HTTPS/SSL aktivieren.
5. Website über die eigene Domain testen.

---

## Schritt 13 – Performance prüfen

Vor dem endgültigen Launch:

- Bilder komprimieren
- unnötige Dateien entfernen
- große Videos vermeiden
- Mobile Ladezeit prüfen
- Browser-Konsole auf Fehler prüfen
- alle Links testen

---

## Schritt 14 – Vor dem Verkauf/Launch Checkliste

- [ ] Markenname geändert
- [ ] Logo ersetzt
- [ ] E-Mail-Adresse ersetzt
- [ ] Portfolio ersetzt
- [ ] Leistungen angepasst
- [ ] Preise angepasst
- [ ] Texte angepasst
- [ ] SEO-Titel angepasst
- [ ] Meta Description angepasst
- [ ] Favicon hinzugefügt
- [ ] Impressum ergänzt
- [ ] Datenschutzerklärung ergänzt
- [ ] Kontaktformular getestet
- [ ] Mobile Navigation getestet
- [ ] Mobile Darstellung getestet
- [ ] Desktop getestet
- [ ] Links getestet
- [ ] eigene Domain verbunden
- [ ] HTTPS geprüft
- [ ] echte Inhalte statt Demo-Inhalte verwendet

---

# Technische Hinweise

## Keine Abhängigkeit von einem Framework

Das Template besteht aus:

- HTML
- CSS
- minimalem JavaScript
- SVG
- PNG

Es benötigt kein React, Next.js, WordPress oder PHP.

## Fonts

Die Website lädt **DM Sans** und **Space Grotesk** über Google Fonts.

Wenn externe Font-Requests vermieden werden sollen, können die Fonts lokal eingebunden oder durch Systemfonts ersetzt werden.

## Mobile CTA

Der Button **„Projekt anfragen“** am unteren Bildschirmrand erscheint erst, wenn der primäre CTA im Hero-Bereich aus dem sichtbaren Bereich gescrollt wurde.

---

# Anpassung für einen anderen Geschäftstyp

Das Template eignet sich nicht nur für Bildbearbeitung.

Die Struktur kann beispielsweise für folgende Angebote verwendet werden:

- Fotograf
- Grafikdesigner
- Webdesigner
- Freelancer
- Social-Media-Agentur
- Videobearbeitung
- Marketing-Service
- virtuelle Assistenz
- lokale Dienstleister
- digitale Produkte

Dafür hauptsächlich ändern:

1. Branding
2. Hero-Text
3. Leistungen
4. Portfolio
5. Preise
6. FAQ
7. Kontakt
8. Rechtstexte

---

# Lizenz / Weiterverkauf

Vor einem kommerziellen Weiterverkauf muss der neue Besitzer prüfen, dass **alle verwendeten Bilder, Fonts, Icons und sonstigen Assets entsprechend lizenziert sind**.

Die Demo-Portfolio-Bilder dürfen nicht automatisch als eigene Kundenarbeiten ausgegeben werden.

---

## Status

**Template:** einsatzbereit als statische Website  
**Backend:** keines enthalten  
**Kontaktformular:** `mailto:` – vor Livegang konfigurieren  
**Rechtstexte:** nicht enthalten  
**Demo-Inhalte:** vor produktivem Einsatz ersetzen
