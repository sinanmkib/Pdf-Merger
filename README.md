# 📄 PDF-Zusammenfüger

Ein einfaches Webtool, um mehrere PDF-Dateien direkt im Browser zusammenzuführen. Die PDFs werden serverseitig zusammengeführt und anschliessend sofort gelöscht – ideal für schnelles und sicheres Arbeiten.

<!-- Platzhalter für Screenshot -->
🔧 Funktionen

    Drag & Drop PDF-Dateien

    Visuelle Dateiliste mit Sortierung per Drag-and-Drop

    Zusammenfügen beliebiger Anzahl an PDFs

    Automatischer Download der zusammengeführten Datei

    Keine Speicherung auf dem Server

#  Vorschau
<!-- Füge hier Screenshots ein -->
Auswahl & Drag-and-Drop	Sortieren & Entfernen
	
# Schnellstart
1. Klone das Repository

git clone https://github.com/dein-benutzername/pdf-zusammenfueger.git
cd pdf-zusammenfueger

2. Installiere die Abhängigkeiten

pip install -r requirements.txt

3. Starte den Server

python app.py

Die Web-App läuft anschliessend unter http://localhost:5000.
📂 Projektstruktur

.
├── app.py               # Hauptserver (Flask)
├── requirements.txt     # Python-Abhängigkeiten
├── templates/
│   └── index.html       # HTML-Oberfläche
├── static/
   └── style.css        # CSS-Styling

# 🔒 Sicherheit & Datenschutz

    Alle hochgeladenen Dateien werden in einem temporären Verzeichnis verarbeitet.

    Nach dem Download werden die Dateien sofort gelöscht.

    Keine Daten werden gespeichert oder weitergegeben.

🛠 Verwendete Technologien

    Flask

    PyPDF2

    SortableJS
