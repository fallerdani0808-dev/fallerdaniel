# fallerdaniel
# RezeptFinder 🍳

Ein einfaches und übersichtliches Python-Desktop-Programm, das bei der täglichen Frage hilft: „Was koche ich heute?“ 

Das Programm ermöglicht es dem Anwender, anhand von zwei Kriterien (Kategorie und Zubereitungszeit) schnell einen passenden Rezeptvorschlag zu erhalten.

---
🌟 Funktionen

 **Kategorieauswahl:** Wählen Sie zwischen Gerichten mit Fleisch oder vegetarischen Rezepten.
 **Zeitfilter:** Filtern Sie nach schnellen Gerichten (< 30 Min.) oder Rezepten mit mehr Zubereitungszeit.
 **Grafische Benutzeroberfläche (GUI):** Einfache Bedienung per Mausklick über Tkinter.
 **Fehlertoleranz:** Robuste Abfangen-Logik bei unvollständigen Eingaben.

---

 🛠️ Technologien & Architektur

* **Programmiersprache:** Python 3.x
* **GUI-Bibliothek:** `tkinter` (Standardbibliothek)
* **Zufallsauswahl:** `random`-Modul
* **Architektur:** Objektorientierter Aufbau (OOP) mit drei Hauptklassen:
  * `Rezept`: Datenmodell für ein einzelnes Gericht.
  * `RezeptFinder`: Filter- und Auswahl-Logik.
  * `RezeptApp`: Grafische Benutzeroberfläche und Ereignissteuerung.

---

 🚀 Installation & Ausführung

 Voraussetzungen
* Python 3.x muss auf Ihrem Computer installiert sein.
* Es werden keine zusätzlichen externen Bibliotheken benötigt.

 Schritt-für-Schritt-Anleitung
1. Repository klonen oder herunterladen:
   git clone [https://github.com/fallerdani0808-dev/fallerdani0808.git](https://github.com/fallerdani0808-dev/fallerdani0808.git)
2. In den Projektordner wechseln:
  cd fallerdani0808
3. Programm starten:
  python main.py

 Bedienung
Öffnen Sie die Anwendung.

Wählen Sie Ihre gewünschte Kategorie (Fleisch oder Vegetarisch) sowie den verfügbaren Zeitrahmen aus.

Klicken Sie auf den Button „Rezept finden“.

Das passende Gericht wird direkt im Ausgabefenster angezeigt.
