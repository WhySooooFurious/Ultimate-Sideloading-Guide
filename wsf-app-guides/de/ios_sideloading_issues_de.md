# Häufige Probleme und Lösungen :)

Dieses Dokument listet häufige Probleme beim Sideloaden von Apps auf iOS und deren Lösungen auf.

## 1. Fehler „Verifizierung nicht möglich“

- **Problem**: PPQ wird beim ersten Setup durch den DNS blockiert
- **Lösung**: Gehe zu **Einstellungen → Allgemein → VPN & Gerätemanagement** → **DNS** Ändere dies zu „INSTALL ONLY“ und versuche es erneut, es kann einige Sekunden dauern, bis es wirksam wird

## 2. App stürzt direkt nach dem Öffnen ab

- Wird oft durch abgelaufene Zertifikate/defekte .ipa verursacht
- **Lösung**: Entweder das Zertifikat auf ein anderes umstellen oder versuchen, eine andere .ipa zu installieren

## 3. Portal-Sänger sagt etwas anderes

- Kann durch ein Problem mit der API oder eine instabile WLAN-Verbindung verursacht werden
- **Lösung**: Du kannst 3 Optionen nutzen 
  1. [https://wsfteam.xyz/#signer](https://wsfteam.xyz/#signer)
  2. [https://sign.ipasign.cc/](https://sign.ipasign.cc/)
  3. [https://sign.kravasign.com](https://sign.kravasign.com)

## 4. Installation schlägt fehl

- Ursachen: nicht unterstützte iOS-Version, beschädigte .ipa
- **Lösung**: Stelle sicher, dass die .ipa mit deiner iOS-Version kompatibel ist und vergewissere dich, dass die .ipa funktioniert

## 5. Die Konfiguration wird als „nicht signiert“ angezeigt

- Das ist normal, da sie nicht von Apple signiert sind und wahrscheinlich auch nicht sein werden, also keine Sorge ;)

## 6. „Resident Evil 4“ kann nicht installiert werden. Bitte später erneut versuchen.

- Ursache: Auch wenn du alles richtig gemacht hast, merkt sich iOS manchmal eine fehlerhafte Validierung von einem vorherigen Versuch.
- Lösung: Starte dein Gerät neu und versuche die Installation erneut.