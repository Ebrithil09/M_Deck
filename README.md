:

🎚️ M_Deck - Dein persönlicher Audio-Mixer Controller für Streaming & Gaming
RP2040-basierter Hardware-Audio-Mixer mit 5 Drehreglern und 10 Tasten für präzise Gerätesteuerung

📸 Produkt-Übersicht
Das M_Deck ist ein eigen entwickeltes Audio-Mixer-Control Panel, das speziell für Streamer, Gamer und Audio-Enthusiasten entwickelt wurde. Mit einer eleganten Grau-Pink-Kombination und intuitiver Bedienung revolutioniert es die Gerätesteuerung auf deinem Desktop.

✨ Features
🎛️ 5 Präzisions-Drehregler
R1-R5: Individuelle Lautstärkekontrolle für verschiedene Audio-Sources
Taktile Drehgeber mit präziser Positionserkennung
Optimiert für glatte, natürliche Bedienung
⌨️ 10 Funktionstasten (B1-B10)
Jede Taste unterstützt multiple Funktionen:

🎤 Mute - Schnelles Stummschalten von Apps
🔊 Media Controls - Play/Pause/Next/Previous
⌨️ Hotkeys - F1-F24 Tasten & Alt+Tab
💻 App Launcher - Starte Chrome, Spotify oder andere Apps
🎮 Toggle Functions - Bluetooth, Discord Overlay usw.
🔌 Geräteverwaltung
Automatische Erkennung aller Audio-Geräte (Wiedergabe/Aufnahme)
Einfache Zuordnung von OUTPUTS und MICs

🛠️ Technische Details
Hardware:
Mikrocontroller: YD-Rp2040 oder Raspbarry Pi Pico
Kommunikation: USB-Seriell, 115200 baud
GPIO-Konfiguration: 5 Drehgeber + 10 Tasten
Versorgung: +3.3V mit optionaler Pullup-Schiene

GPIO Mapping:

Pin	Funktion	Beschreibung
GPIO0-9,14:	        Drehgeber 1-5	   CLK/DT Signale für Quadrature Encoders
GPIO10,11,12,13,14:	Drehgeber-Taster SW (Switch) für Druckerkennung
GPIO18-22:	        Tasten B6-B10	   GND-Geschaltete Tasten

🚀 Installation & Setup
1. Software Runterladen :
2. RP2040 Flashen:
In meinem Fall über Arduino IDE code kann auch Heruntergeladen werden
+ Board Wählen YD-RP2040 (https://github.com/earlephilhower/arduino-pico) 
3. Verbindung herstellen:
App startet sucht automatisch nach COM
Geräte in der GUI konfigurieren
"Speichern & Schließen" klicken

<img width="536" height="812" alt="Screenshot 2026-09-24 111959" src="https://github.com/user-attachments/assets/a0e7b6e3-02ab-430e-923a-aba657eacb17" />
<img width="538" height="808" alt="Screenshot 2026-09-24 110852" src="https://github.com/user-attachments/assets/c92c025a-13a4-48bd-b73d-00b9a8ad2518" />
<img width="536" height="806" alt="Screenshot 2026-09-24 111011" src="https://github.com/user-attachments/assets/364e935b-4d2a-4cea-8db1-0f6f9f9b4ca3" />
<img width="4032" height="3024" alt="M_Deck_Grau_pink" src="https://github.com/user-attachments/assets/6a6fac1c-abf4-4fcf-a740-5a93d0604e05" />

Nur für Windows 10/11
Hast du Fragen oder Verbesserungsvorschläge? Schreib mir einfach!
