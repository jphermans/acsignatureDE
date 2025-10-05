# ✨ E-Mail-Signaturgenerator

<p align="center">
  <img src="https://img.shields.io/badge/version-1.1.0-0092BC?style=for-the-badge" />
  <img src="https://img.shields.io/badge/status-stable-2F363A?style=for-the-badge" />
</p>

---

## 🚀 Live-Demo
Teste den Generator hier:
👉 [Signaturgenerator](https://jphermans.github.io/acsignatureDE/)

---

## 📌 Über dieses Projekt
Ein einfaches Tool, mit dem sich professionelle E-Mail-Signaturen automatisch erstellen lassen – speziell abgestimmt auf den Einsatz in Deutschland. Entwickelt mit **HTML, CSS und JavaScript**.

Der Generator:
- ✅ Erstellt automatisch ein **ZIP** mit `.htm`, `.rtf`, `.txt` und `_files`-Ordner.
- ✅ Vergibt Dateinamen nach Outlook-Standard: `AtlasCopco(name@atlascopco.com).*`.
- ✅ Stellt sicher, dass Pflichtfelder (Name, Funktion, E-Mail, Mobil) ausgefüllt sind.
- ✅ Prüft, ob die E-Mail-Adresse auf `@atlascopco.com` endet.
- ✅ Zeigt klare Fehlermeldungen bei fehlenden Angaben.
- ✅ Hält die Buttons konsistent: **Felder zurücksetzen** nutzt denselben sekundären Stil wie der Download-Button.
- ✅ Bietet ein vollständig responsives Layout – inklusive Anleitung – für komfortable Nutzung auf Smartphone, Tablet und Desktop.

---

## 🎨 Layout & Farben
Das Interface setzt auf ein klares Design mit vertrauten Farbtönen:

| Farbton | Beispiel | Hex |
| --- | --- | --- |
| Akzentfarbe | <img src="assets/colors/0092BC.svg" width="20"/> | `#0092BC` |
| Dunkelgrau | <img src="assets/colors/2F363A.svg" width="20"/> | `#2F363A` |
| Hellgrau  | <img src="assets/colors/E1D6CE.svg" width="20"/> | `#E1D6CE` |

---

## ⚙️ Installation & Nutzung

### 1. Generator öffnen
Repository herunterladen oder klonen und die Datei **index.html** im Browser öffnen.

### 2. Eigene Daten eintragen
- Name
- Funktion
- E-Mail (muss auf `@atlascopco.com` enden)
- Mobil (Pflichtfeld)
- Telefon (optional)

### 3. Signatur erstellen
Auf **Signatur erstellen** klicken. Die Vorschau wird sofort aktualisiert.

### 4. Nach Outlook exportieren
Auf **Nach Outlook exportieren (ZIP)** klicken → es entsteht ein ZIP-Archiv mit:
- `AtlasCopco(name@atlascopco.com).htm`
- `AtlasCopco(name@atlascopco.com).rtf`
- `AtlasCopco(name@atlascopco.com).txt`
- `AtlasCopco(name@atlascopco.com)_files/`

### 5. Dateien in Outlook ablegen
- ZIP-Datei entpacken.
- Ordner öffnen:
  ```bash
  %appdata%\Microsoft\Signatures
  ```
- Die entpackten Dateien und den Ordner in dieses Verzeichnis kopieren.
- Outlook vollständig schließen (ggf. über den Task-Manager) und neu starten.
- Unter **Datei → Optionen → E-Mail → Signaturen** die neue Signatur als Standard festlegen.

![Signaturvorschau](assets/generator.png)
