Website Content Extractor
Ein benutzerfreundliches Browser-Tool zum Extrahieren und Herunterladen von Website-Inhalten als HTML oder PDF.

🎯 Funktionsumfang
Hauptfunktionen
URL-Eingabe: Beliebige Website-URLs können eingegeben werden

Format-Auswahl: Wähle zwischen HTML-Rohdaten oder formatiertem PDF-Export

Content-Extraktion: Lädt den vollständigen Inhalt einer Website

Live-Vorschau: Zeigt eine Vorschau des extrahierten Inhalts direkt im Browser

Download-Funktion: Speichere den Inhalt lokal als Datei

Technische Features
Multi-Proxy-System: Nutzt automatisch 3 verschiedene Proxy-Dienste für maximale Zuverlässigkeit

Timeout-Schutz: 15-Sekunden-Timeout pro Versuch mit automatischem Fallback

Progress-Feedback: Zeigt den aktuellen Verbindungsversuch an (1/3, 2/3, 3/3)

CORS-Umgehung: Verwendet Proxy-Services um Cross-Origin-Beschränkungen zu umgehen

Fehlerbehandlung: Intelligentes Retry-System bei fehlgeschlagenen Verbindungen

Link-Kopieren: Kopiert die verarbeitete URL direkt in die Zwischenablage

Unterstützte Formate
HTML-Export
Vollständiger Quellcode der Website

Erhält alle Tags, Attribute und Strukturen

Ideal für Entwickler und Code-Analyse

Download als .html-Datei

PDF-Export
Sauber formatierter Textinhalt

Automatische Seitenumbrüche

Enthält Website-Titel und URL

Mehrseitige Dokumente bei längeren Inhalten

Download als .pdf-Datei mit jsPDF-Bibliothek

🚀 Verwendung
URL eingeben: Trage die Website-URL in das Eingabefeld ein

Format wählen: Wähle zwischen HTML oder PDF

Extrahieren: Klicke auf "Inhalt extrahieren"

Vorschau prüfen: Überprüfe den extrahierten Inhalt

Herunterladen: Klicke auf "Herunterladen" um die Datei zu speichern

Optional: Nutze "Link kopieren" um die URL in deine Zwischenablage zu kopieren.

⚙️ Technische Details
Verwendete Proxy-Dienste
AllOrigins API (api.allorigins.win)

CORS Proxy (corsproxy.io)

CodeTabs Proxy (api.codetabs.com)

Browser-Kompatibilität
✅ Chrome/Edge (empfohlen)

✅ Firefox

✅ Safari

✅ Opera

Abhängigkeiten
jsPDF (v2.5.1) - PDF-Generierung

⚠️ Einschränkungen
CORS-geschützte Websites: Websites mit strengem CORS-Schutz können möglicherweise nicht extrahiert werden

Captcha-Systeme: Websites mit Captcha-Schutz sind nicht zugänglich

JavaScript-generierte Inhalte: Dynamisch geladene Inhalte werden möglicherweise nicht vollständig erfasst

Timeout: Bei sehr langsamen Servern kann die Extraktion nach 15 Sekunden pro Proxy fehlschlagen

Datenschutz: Keine Daten werden serverseitig gespeichert - alles läuft im Browser

🛠️ Installation & Hosting
Lokale Nutzung
Speichere den HTML-Code als index.html

Öffne die Datei direkt im Browser

GitHub Pages
Erstelle ein GitHub Repository

Lade index.html hoch

Aktiviere GitHub Pages in den Settings

Zugriff über: https://username.github.io/repository-name/

Netlify
Besuche drop.netlify.com

Ziehe die HTML-Datei per Drag & Drop

Erhalte sofort eine öffentliche URL

📝 Lizenz
Freie Nutzung für private und kommerzielle Zwecke.

🤝 Support
Bei Problemen oder Fragen:

Überprüfe die Browser-Konsole für detaillierte Fehlermeldungen

Stelle sicher, dass die Ziel-Website öffentlich zugänglich ist

Teste alternative URLs bei wiederholten Fehlern

Version: 1.0
Letzte Aktualisierung: März 2026
