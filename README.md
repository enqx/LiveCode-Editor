# 🚀 LiveCode Editor

Ein leichter, direkt im Browser laufender Live-Code-Editor für HTML, CSS und JavaScript. Das Besondere: Ein integrierter, schwebender YouTube-Player in der Ecke, damit du beim Programmieren entspannt Musik hören oder Videos schauen kannst – ohne den Tab wechseln zu müssen!

## ✨ Features

* **Live Code Editor:** Drei separate Eingabefelder für HTML, CSS und JavaScript.
* **Syntax-Highlighting:** Angetrieben von *CodeMirror* im augenschonenden, dunklen *Dracula*-Theme.
* **Echtzeit-Vorschau:** Der Code wird direkt beim Tippen auf der rechten Seite gerendert.
* **Schwebender YouTube-Player:** Fest positioniert in der linken unteren Ecke (6cm breit).
* **Ausklappbares Menü:** Eine aufgeräumte obere Leiste. Mit einem Klick auf den Pfeil (➤) öffnen sich die YouTube-Einstellungen.
* **Lautstärkeregler:** Die Lautstärke des Videos kann direkt über einen Slider im Editor gesteuert werden, ohne im kleinen Video herumklicken zu müssen.

## 💻 Anwendung

### Option 1: Direkt im Browser nutzen (GitHub Pages)
Öffne einfach den Live-Link:
👉 **https://enqx.github.io/LiveCode-Editor/**

### Option 2: Lokal auf dem Computer ausführen
1. Lade das Repository als ZIP herunter (oder klone es).
2. Öffne die Datei `index.html` per Server in deinem Browser.
3. Fange an zu programmieren!

## 🎵 So steuerst du das YouTube-Video

1. Klicke oben in der dunklen Leiste auf den Pfeil **➤** neben "Live Code Editor".
2. **Neues Video laden:** 
   * Gehe auf YouTube und suche dir ein Video aus.
   * Kopiere die **Video-ID** aus der URL (das sind die Zeichen nach dem `v=`, z.B. bei `youtube.com/watch?v=jfKfPfyJRdk` ist die ID **`jfKfPfyJRdk`**).
   * Füge die ID in das Feld "Video ID:" ein und klicke auf **Laden**.
3. **Lautstärke ändern:** 
   * Nutze den Schieberegler `🔉 Lautstärke`, um das Video lauter oder leiser zu machen. Das Video startet standardmäßig bei angenehmen 20%.

## 💻 Verwendete Technologien

* **[Bootstrap 5](https://getbootstrap.com/):** Für das Layout und die obere Navigationsleiste.
* **[CodeMirror](https://codemirror.net/5/):** Für die Code-Eingabefelder und das Syntax-Highlighting.
* **[YouTube Iframe API](https://developers.google.com/youtube/iframe_api_reference):** Um das Video einzubetten und die Lautstärke über einen eigenen Slider steuern zu können.

## 💡 Tipp

Wenn du keine Werbung willst benutze einfach Ad-Blocker oder starte die Webseite über den localhost

---
*Viel Spaß beim Coden!* 🚀
