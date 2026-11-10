# GameCheck AI – Windows-Vorschau 0.4.9

GameCheck AI erkennt lokale PC-Hardware, vergleicht sie nachvollziehbar mit dokumentierten Spieleanforderungen und bietet eine lokale Spielmessung. Dieses Repository ist für Windows-Releases und öffentliche Versionshinweise vorgesehen.

## Funktionsumfang

- Lokale Hardwareerkennung und ein Katalog mit **102 Spieleprofilen**, Quellenangaben und Datenständen.
- Nachvollziehbarer Hardwarevergleich: Unbekannte Modelle und unbelegte CPU-/GPU-Leistungsrelationen bleiben ausdrücklich offen. Aus Modellnummern oder Speichermengen werden keine erfundenen Leistungswerte abgeleitet.
- „Spiel 60 Sekunden messen“ mit lokaler Aufnahme, Auswertung, getrennt erhaltenen Berichten und Original-CSV, Messhistorie und gemeinsamem Supportexport.
- Automatische Prozesszuordnung für **Age of Mythology: Retold**, **Age of Empires III: Definitive Edition** und **Counter-Strike 2**. 102 Anforderungsprofile bedeuten keine automatische Messerkennung für 102 Spiele. Uneindeutige Prozesszuordnungen werden nicht geraten.
- Messung über PresentMon/ETW ohne Injektion in Spiele. Prozessidentität und erkannte ETW-Datenverluste bleiben Teil der Prüfung.

## Grenzen der Vorschau

Ein tatsächlicher Messlauf mit bedienter Spielszene ist für diese Vorschau noch nicht abschließend abgenommen. Technische Kontrollaufnahmen und simulierte Prüfungen sind keine Spielebenchmarks. Es werden keine FPS-Prognosen, erfundenen Messwerte oder garantierten Leistungssteigerungen versprochen. Eine breite belegte CPU-/GPU-Leistungsdatenbasis ist weiterhin unvollständig.

Treiber, BIOS und Windows-Systemeinstellungen werden nicht automatisch verändert. Hinweise sollen verständliche eigene Entscheidungen ermöglichen.

## Lokale Daten und manuelle Updates

Hardwaredaten, Messberichte und Original-CSV bleiben lokal. Es gibt keine automatische Übermittlung dieser Daten und keine automatische Telemetrie. Ein Supportexport erzeugt eine lokale Datei; das Weitergeben entscheidet der Nutzer selbst.

Updateprüfung und Updateinstallation werden ausdrücklich vom Nutzer gestartet. Dabei werden Netzwerkverbindungen zu GitHub verwendet. Auch bewusst geöffnete Quellen- und Herstellerlinks führen zu externen Websites. Der vollständige öffentliche HTTPS-Updatezyklus ist gesondert abzunehmen; ein lokaler Upgrade- oder Sicherungsnachweis ersetzt ihn nicht.

## Signierung und Dateiprüfung

Der vorbereitete Windows-x64-Installer 0.4.9 hat eine Tauri-Updatesignatur gegen die bisherige öffentliche Signierungsidentität. Eine Tauri-Updatesignatur ist von Windows-Authenticode zu unterscheiden. Der Installer ist **nicht Windows-Authenticode-signiert**; aus der Tauri-Signatur folgt keine SmartScreen-Reputation.

Installer-SHA-256:

`4B43FD5012FF493B5709B4B733764F12A93D9B8A340079A98542D7E6754EB8E8`

SHA-256 der bisherigen öffentlichen Tauri-Signierungsidentität:

`3E2E617034D8BB865F0BB04D8CFFC842202E739F0697C0D2E1D165695A3B1847`

Die zugehörigen Drittanbieter-Lizenzhinweise und erforderlichen Drittanbieterquellen gehören zur jeweiligen Releasebereitstellung. Dieser Text behauptet keine abgeschlossene rechtliche Gesamtfreigabe und keinen bereits ausgeführten öffentlichen Downloadnachweis.
