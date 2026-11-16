# 🎮 CodeBot Gaming Hub (v4.8)

Een educatieve en interactieve spelling-gaminghub voor het web (GitHub Pages) en Android (via Capacitor), speciaal ontworpen om kinderen op een leuke, uitdagende manier spellingwoorden te laten oefenen door middel van gamification, verschillende thema-werelden en online klassementen.

---

## 🌟 Belangrijkste Kenmerken

- **4 Unieke Werelden & Stijlen:**
  - 🤖 **CodeBot Arena:** Strijd met cyber-lasers tegen Glitch-Bots.
  - 🧪 **Bio-Chem Lab:** Brouw formules en bestrijd mutanten.
  - 🚀 **Star-Blaster Galaxy:** Space-shooter tegen aliens en meteoren.
  - 🦄 **Kawaii Droomwereld:** Tover met schattige knuffels en glitters!
- **🏆 Online Klassement (Firebase):** Strijd mee om de hoogste score per woordenlijst, beveiligd met server-side validatie en deduplicatie per speler.
- **🎖️ 32 Thema-Badges:** 8 unieke, themagebonden badges per wereld te verzamelen in de Trofeeënkast (totaal 32 stuks).
- **📚 Slimme Woordenlijsten:** Automatische synchronisatie via `woorden.json` en lokaal behoud van de laatst gekozen lijst (inclusief ondersteuning voor eigen ingevoerde lijsten).
- **📲 Automatische APK & Web Distributie:** Dankzij GitHub Actions wordt de Android-APK bij elke update automatisch gebouwd, ondertekend en klaargezet voor download (zowel via GitHub Releases als via een slimme knop in de web-app).
- **🔒 Privacygericht:** Volledig transparante privacyverklaring. Er worden geen persoonsgegevens of tracking-cookies verzameld; highscores slaan uitsluitend een gekozen bijnaam en score op.

---

## 🚀 Tech Stack

- **Framework:** HTML5, Tailwind CSS, Vanilla JavaScript (Single-Page App)
- **Mobile Bridge:** Capacitor 6 (Android)
- **Backend & Database:** Firebase Realtime Database (Online Klassement)
- **CI/CD & Hosting:** GitHub Actions & GitHub Pages
- **Spraak & Audio:** Web Speech API / Capacitor Text-To-Speech plugin + Web Audio API (synthesizer)

---

## 📲 Installatie & Download

### Voor Android-tablets en telefoons:
1. Open de online webversie via [GitHub Pages](https://JOUW_GITHUB_NAAM.github.io/codebot-arena/).
2. Tik op de knop **"📲 Download Android App"** om de kant-en-klare APK direct te installeren.
3. Of download de nieuwste `.apk` direct via de [GitHub Releases](../../releases/latest) pagina van deze repository.

---

## ⚙️ Lokale Ontwikkeling

Om het project lokaal te draaien of aan te passen:

1. Kloon de repository:
   ```bash
   git clone [https://github.com/JOUW_GITHUB_NAAM/codebot-arena.git](https://github.com/JOUW_GITHUB_NAAM/codebot-arena.git)
   cd codebot-arena
