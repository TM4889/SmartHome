
# SmartHome
**Various SmartHome Projects, Devices, Information and Examples including AskSinPP usage**


## AddOn Kompatibilität

| |AddOn|Status|
|---|---|---|
|:heavy_check_mark:|HB-UNI-Sensor1|lauffähig unter CCU / RaspberryMatic Firmware 2.31.x - 2.45.6 / 3.37.x - 3.45.7|
|:heavy_check_mark:|HB-SEN-LJet|lauffähig unter CCU / RaspberryMatic Firmware 2.31.x - 2.45.6 / 3.37.x - 3.45.7|
|:heavy_check_mark:|HB-DIS-EP-42BW|lauffähig unter CCU / RaspberryMatic Firmware 2.31.x - 2.45.6 / 3.37.x - 3.45.7|

[comment]: # (:large_blue_circle:)

## Universalsensor HB-UNI-Sensor1

- Demonstriert einen HomeMatic/RaspberryMatic/FHEM Universalsensor für Temperatur, Luftdruck, Luftfeuchte, Helligkeit usw.
- modifizierbar für andere Sensoren
- konfigurierbares Sendeintervall über WebUI
- konfigurierbare Höhe (für Berechnung des Luftdrucks auf Meeresniveau/Normaldruck) über WebUI
- Der Status eines digitalen Eingangs kann mit übertragen werden.

<p align="center"><img src="Images/HB-UNI-Sensor1_HW1_small.jpg?raw=true"/></p>

-> [Projektseite HB-UNI-Sensor1](https://github.com/TomMajor/SmartHome/tree/master/HB-UNI-Sensor1)


## Wassermelder HB-SEC-WDS-2

- Wassermelder mit Leitfähigkeitsmessung zwischen den Elektroden
- Demonstriert die Verwendung vom 'ThreeStateSensor' device type aus der AskSinPP Bibliothek mit einer anpassbaren Messroutine, in diesem Fall die Leitfähigkeitsmessung mit dem integrierten ADC

<p align="center"><img src="Images/Prototyp_Wassermelder_small.jpg?raw=true"/></p>

-> [Projektseite HB-SEC-WDS-2](https://github.com/TomMajor/SmartHome/tree/master/HB-SEC-WDS-2)


## Füllstandsanzeige Öltank/Wassertank HB-SEN-LJet

- Kopplung der Projet LevelJET Ultraschall-Füllstandsanzeige mit HomeMatic für Rotex-Öltanks
- Anpassung an beliebige Tankformen durch Einsatz einer Peiltabelle möglich

<p align="center"><img src="Images/LevelJet_small.jpg?raw=true"/></p>

-> [Projektseite HB-SEN-LJet](https://github.com/TomMajor/SmartHome/tree/master/HB-SEN-LJet)


## Infos und AddOn zum 4,2" ePaper Display HB-DIS-EP-42BW

- Sketch für DisplayTest, AddOn, Fuses, Bootloader

<p align="center"><img src="Images/EP42_small.jpg?raw=true"/></p>

-> [Projektseite HB-DIS-EP-42BW](https://github.com/TomMajor/SmartHome/tree/master/HB-Dis-EP-42BW)


## 3-Kanal Kontakt-Interface für Öffner und Schließerkontake HB-SCI-3-FM

- Nachbau HM-SCI-3-FM mit AskSinPP Library

<p align="center"><img src="Images/HB_SCI_3_FM_small.jpg?raw=true"/></p>

-> [Projektseite HB-SCI-3-FM](https://github.com/TomMajor/SmartHome/tree/master/HB-SCI-3-FM)


## Schutz vor "Babbling Idiot" (BI)

- Betrachtungen und Lösungen zum Schutz gegen einen "Babbling Idiot" (Dauersender) im HomeMatic Netzwerk bei Selbstbaugeräten

<p align="center"><img src="Images/BI_small.jpg?raw=true"/></p>

-> [Projektseite BI Schutz](https://github.com/TomMajor/SmartHome/tree/master/Info/Babbling%20Idiot%20Protection)


## PLHT Sensor

- Redesign von Dirks/PeMue's Universalsensor-Platinen für Außen- oder Innenanwendungen

<p align="center"><img src="Images/PLHT_small.png?raw=true"/></p>

-> [Projektseite PLHT Sensor](https://github.com/TomMajor/SmartHome/tree/master/PCB/Sensor_PLHT)


## Ruhestrom

- Hinweise zur Verringerung des Ruhestromverbrauchs
- Entfernen des LDOs bei Sensor-Boards
- Sketch (SleepTest.ino) zur Überprüfung von Aktiv- und power-down Strom eines Arduino Pro Mini 328 (3.3V/8MHz) mit angeschlossenem CC1101 (das wäre ein Basis-AskSinPP Gerät ohne angeschlossene Sensoren oder andere Zusatz-HW)
- Sketch (SleepTestRTC.ino) zur Überprüfung des AVR power-save Mode mit 32,768kHz RTC, damit kann man weniger als 1µA Ruhestrom erreichen.

<p align="center"><img src="Images/SensorBreakoutBoards_small.jpg?raw=true"/></p>

-> [Projektseite Ruhestrom](https://github.com/TomMajor/SmartHome/tree/master/Info/Ruhestrom)


## Bootloader & Fuses

- diverse Informationen zu Bootloadern, Fuses, Flashen

<p align="center"><img src="Images/fuses_small.jpg?raw=true"/></p>

-> [Projektseite Bootloader & Fuses](https://github.com/TomMajor/SmartHome/tree/master/Info/Bootloader)


## HomeMatic AddOn Entwicklung und Dokumentation

- Diverse Infos und Dokumentationen für die RaspberryMatic/CCU AddOn-Entwicklung

<p align="center"><img src="Images/AddOn_small.jpg?raw=true"/></p>

-> [Projektseite HomeMatic AddOn Entwicklung und Dokumentation](https://github.com/TomMajor/SmartHome/tree/master/Info/RaspberryMatic_CCU_AddOn)


## SensorTest_Lux

- Messungen und Betrachtungen zu den Helligkeitssensoren TSL2561 und MAX44009

<p align="center"><img src="Images/SensorTest_Lux_small.jpg?raw=true"/></p>

-> [Projektseite SensorTest_Lux](https://github.com/TomMajor/SmartHome/tree/master/Info/SensorTest_Lux)


## WDT_Frequenz

- Misst die Abweichung der Watchdog-Timer Frequenz bei einen ATmega328 in Bezug zur Quarzfrequenz, wichtig für das Aufwach-Intervall

<p align="center"><img src="Images/WDT_Frequenz_small.jpg?raw=true"/></p>

-> [Projektseite WDT_Frequenz](https://github.com/TomMajor/SmartHome/tree/master/Info/WDT_Frequenz)
