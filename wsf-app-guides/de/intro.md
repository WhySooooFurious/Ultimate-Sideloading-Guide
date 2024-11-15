Wilkommen zur WSF Sideloading Guide für Apple Geräte!
Vorteile dieser Methode:
- Kostenlos

- Kein PC benötigt

- Einfach zu nutzen!

- Kein App Limit!

- Signing auf dem Gerät selbst!

- Privatsphäre

- Benötigt nur 5 Minuten deiner Zeit

- Apps bleiben bis zu einem Jahr installiert

- Kompatibel mit Scarlet/Feather/ESign/GBox

Wenn du Probleme, Anfragen oder Ideen hast mache eine Issue auf GitHub auf oder schreibe uns auf Discord!


### [Wie funktioniert diese Methode?](accent://)
Durch die Verwendung von geleakten Unternehmenszertifikaten können wir Apps mit deren Anmeldeinformationen signieren, was bedeutet, dass Apple uns die Installation der Apps ohne Probleme ermöglicht. Allerdings widerruft Apple nach einer gewissen Zeit das Zertifikat, was leicht umgangen werden kann, indem man unsere Methode verwendet.

### [Bevor wir anfangen](accent://)

- Dies könnte für dich nicht funktionieren, wenn du bereits andere Enterprise-Sideloader verwendet hast, da die Zertifikate auf deinem Gerät revoked worden sein könnten!

- Falls du revoked wurdest, musst du der Revoked Anleitung folgen!
- Es wird funktionieren, solange du alle Schritte korrekt liest und machst!

### [Kompatibilität](accent://)
Dies sollte für alle iOS- und iPadOS-Geräte mit den neuesten iOS-Versionen funktionieren, jedoch nicht für iOS 15 und älter. Die Anleitung ist mit anderen Sideloading-Diensten kompatibel, solange sie auf Unternehmenszertifikaten zur Installation basieren.

### [Privatsphäre](accent://)
Wenn du Bedenken hinsichtlich der Privatsphäre des madNS Config-Profils hast, eröffne ein Issue auf GitHub mit deiner E-Mail-Adresse und ich werde dir eine Einladung zur Ansicht senden, damit du die Einstellungen selbst einsehen kannst.

Stelle sicher, dass du genau den Namen des madNS-Profils angibst:

z.B.:

madNS Config Profile + Update Blocker

Das WSF Config Profile ist kein DNS, da es nur Apple-Server auf https://localhost.direct umleitet, welches dein lokales Netzwerk ist, also keine Bedenken hinsichtlich der Privatsphäre. Du kannst es selbst überprüfen, indem du das Profil auf einem PC öffnest.


### [FAQ](accent://)

--

Q - Kann ich ein VPN verwenden?

A - Du kannst es verwenden, wenn du das madNS Config Profile nutzt. Stelle sicher, dass du der VPN-Anleitung gefolgt bist.

--

Q - Wird ein Neustart dies umgehen und meine Apps widerrufen?

A - Einige Benutzer haben herausgefunden, dass auf älteren Geräten deine Apps widerrufen werden könnten. Deaktiviere WiFi und aktiviere den Flugmodus, wenn du neu startest oder das Gerät herunterfährst.

--

Q - Werden Dienste wie AltStore, Sideloadly und Sidestore diese Anleitung beeinflussen?

A - Nein, die genannten Dienste verwenden Entwickler-Signaturen anstelle von Enterprise-Signaturen, daher kannst du sie problemlos zusammen verwenden! Du musst jedoch SideStore’s WireGuard einrichten, stelle sicher, dass du der VPN-Anleitung folgst.

--
