# aniworld-popup-blocker

![Tampermonkey](https://img.shields.io/badge/Tampermonkey-00485B?style=for-the-badge&logo=tampermonkey&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chrome](https://img.shields.io/badge/Chrome-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![uBlock Origin](https://img.shields.io/badge/uBlock_Origin-800000?style=for-the-badge&logo=ublockorigin&logoColor=white)

![Aniworld](https://img.shields.io/badge/aniworld.to-popups_blocked-e91e63?style=flat-square)
![Version](https://img.shields.io/badge/version-2.0-success?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Type](https://img.shields.io/badge/type-userscript-orange?style=flat-square)

Userscript gegen die Popup-Tabs, die beim Klick auf Play in den Aniworld-Playern aufgehen.

Die Hoster (VOE usw.) rufen beim Klick `window.open` auf. Das Script ersetzt `window.open` in allen Frames, die unter aniworld.to hängen, und blockt zusätzlich Script-Klicks auf Fremdlinks und ein paar Werbe-Domains (Liste `BAD` im Script).

## Installation

1. Tampermonkey installieren
2. `aniworld-popup-blocker.user.js` hinzufügen
3. Aniworld neu laden

Blocks stehen mit `[Blocker]` in der Konsole. Zusätzlich uBlock Origin zu nutzen schadet nicht.

## Hinweise

- Die Werbung öffnet nur alle 5 Minuten einen Tab, zum Testen also kurz warten
- Läuft nur im Aniworld-Kontext, nicht wenn ein Hoster direkt im eigenen Tab offen ist
- Neue Werbedomains einfach in `BAD` eintragen
