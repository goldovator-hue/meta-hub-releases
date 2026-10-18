# Goldovator META HUB

Eigenständiges Windows-Programm für interaktive Twitch-Metascreens mit OBS-Anbindung, lokaler Goldling World und Regiezentrale.

## Download

Den Windows-x64-Installer findest du unter [Releases](https://github.com/goldovator-hue/meta-hub-releases/releases). Version 0.1.1 richtet den öffentlichen Updatekanal ein; eine vorhandene Version 0.1.0 bitte einmalig mit dem neuen Installer aktualisieren.

## Automatische Updates

META HUB prüft beim Start und alle vier Stunden auf neue Versionen. Download und Prüfung erfolgen im Hintergrund. Installation erfolgt nach deiner Bestätigung, mit lokaler Datensicherung und gesperrt während aktiver META-Ausgabe. Beides lässt sich unter „Diagnose & Einstellungen“ einstellen.

`meta-hub-update.json` trägt eine Ed25519-Signatur über Version, Dateiname, Dateigröße und SHA-512 des Installers. Die App enthält den festgelegten öffentlichen Schlüssel. Unsigned/manipulierte Metadaten und beschädigte Dateien werden abgewiesen. Der private Schlüssel wird nicht veröffentlicht.

Die Update-Signatur ist unabhängig von Windows-Authenticode: Der erste Installer ist nicht Windows-codesigniert. Windows kann daher einen Hinweis auf einen unbekannten Herausgeber anzeigen.

## Freiwillig unterstützen

Alle Funktionen bleiben kostenlos. Eine [einmalige Unterstützung ab 5 €](https://donate.stripe.com/6oU6oI6Uf7SG0s57rNgMw04) ist freiwillig; höhere Beträge sind frei wählbar. Kein Abo und keine zusätzlichen Funktionen durch die Zahlung.

OBS und ein eigenes Twitch-Konto samt öffentlicher Twitch-Client-ID werden für die echten Verbindungen benötigt. Vor dem Live-Einsatz bitte OBS-Browserquelle, Freigabeszenen und Ton prüfen.
