# 🌐 Googlometer

**Wie tief steckst du im Google-Ökosystem?**

Googlometer ist ein kleiner, unabhängiger Web-Test, der anhand einfacher Fragen
ermittelt, wie stark du im Alltag von Google-Produkten und -Diensten abhängig
bist – von Gmail über Android bis Google Maps. Am Ende bekommst du einen
**Score von 0–100** sowie eine Aufschlüsselung nach Kategorien.

🔗 **[Live-Demo ansehen](#)** *(Link nach Deployment einfügen, z. B. via GitHub Pages)*

---

## ✨ Features

- 📋 15–20 kurze Fragen zu Suche, Browser, Mobilgerät, Cloud, Entertainment u. v. m.
- 📊 Score-Berechnung (0–100) mit fünf Auswertungsstufen
- 🧩 Kategorie-Breakdown, damit du siehst, *wo* genau du am tiefsten drin steckst
- 🌗 Dark-Mode-Unterstützung
- 🔒 100 % clientseitig – keine Daten verlassen deinen Browser
- 🚫 Keine Google-Dienste, kein Tracking, keine Cookies (ironiefrei, versprochen)
- 📱 Responsive, funktioniert auf Mobilgeräten und Desktop

---

## 🧠 Warum dieses Projekt?

Google-Dienste sind praktisch, kostenlos und überall integriert – genau deshalb
merken viele Menschen gar nicht mehr, wie viele Bereiche ihres digitalen Lebens
an ein einziges Unternehmen gebunden sind. Googlometer soll das auf spielerische
Weise sichtbar machen, ohne moralischen Zeigefinger. Am Ende jeder Auswertung
gibt es außerdem ein paar Vorschläge für alternative, datenschutzfreundlichere
Tools, falls du deine Abhängigkeit reduzieren möchtest.

---

## 🚀 Nutzung

### Lokal öffnen
```bash
git clone https://github.com/<dein-username>/googlometer.git
cd googlometer
open index.html   # oder Doppelklick im Dateibrowser
```

Es wird kein Build-Prozess, kein Node.js und kein Server benötigt.

### Mit GitHub Pages hosten
1. Repository-Einstellungen → **Pages**
2. Branch `main`, Ordner `/ (root)` auswählen
3. Fertig – die Seite ist unter `https://<dein-username>.github.io/googlometer/` erreichbar

---

## 🛠️ Projektstruktur

```
googlometer/
├── index.html        # Grundgerüst der Seite
├── style.css         # Styling, Dark-Mode, Animationen
├── script.js          # App-Logik, Rendering, Navigation
├── questions.js       # Fragenkatalog + Scoring-Definition
└── README.md
```

---

## 🤝 Mitmachen

Contributions sind willkommen! Besonders gefragt:

- Neue oder aktualisierte Fragen (Google bringt ständig neue Produkte)
- Übersetzungen in weitere Sprachen
- Verbesserte Barrierefreiheit
- Vorschläge für datenschutzfreundliche Alternativ-Tools in der Auswertung

Bitte einen Pull Request mit kurzer Beschreibung der Änderung eröffnen.

---

## ⚠️ Haftungsausschluss

Dieses Projekt steht in **keiner Verbindung zu Google LLC** und ist eine
unabhängige, nicht-kommerzielle Anwendung zu Awareness- und Unterhaltungszwecken.
Alle Produktnamen sind Eigentum ihrer jeweiligen Rechteinhaber.

---

## 📄 Lizenz

[MIT](LICENSE) – frei nutzbar, veränderbar und weiterverbreitbar.
