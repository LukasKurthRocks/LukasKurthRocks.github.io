---
title: Mein eigenes Windows Notfall Image
published: true
---

⚠ WIRD NOCH ERWEITERT ⚠

Ich entschuldige mich schon einmal im Vorfeld über eventuell falsch formatierte oder fehlerhafte Informationen. Dieser Post soll der erste richtige auf GitHub sein, da ich hier meine Projekte laden und verlinken kann. Dann kann ich das private auf meinem Blog lassen, aber ich werde sehen wie sich das am besten verwalten lässt.

Ich habe die letzten Tage noch einmal meine c't-Hefte durchgeblättert. Dabei habe ich noch einmal die c't-Notfall-Windows Beträge angeschaut (Aktuell: [Heise.de - c't-Notfall-Windows 2021](https://www.heise.de/select/ct/2020/26/2030219513398904310)). Dabei handelt es sich um ein Windows-PE-Bastel-System. Mit dabei das [PEBakery](https://github.com/pebakery/pebakery), was scheinbar auf [Win10XPE](https://github.com/ChrisRfr/Win10XPE) basiert oder ähnlich.

# Aktuelle Schritte

## 2021-03-23 Unterschiedliche Stände
Mein Problem aktuell ist noch, dass ich ein System basteln möchte, welches sich nicht nur für Privatanwender, sondern eventuell auch für speziellere Einsätze eignet.

Der Stand von c't ist aber eher speziell. Komisch finde ich auch, dass heise.de scheinbar die MoScripts-Sachen ausblendet. Vielleicht kann ich da mal herausfinden warum. Wie viel Zeit müsste ich dafür aufwenden? Beim aktuellen Stand müsste ich die Win10XPE laden, dann die von c't. Über Win10XPE lade ich alle Date die ich brauche (MEGA Download), dann kopiert ich die PEBakery-Version von c't in den Ordner mit rein und kopiere alle Daten von MoScripts\Apps in MyScripts\Apps\MoApps (kann auch anders heißen). Dann tauchen die auch in der Liste links mit auf (Screenshots könnten folgen).

### Wofür MoScripts stehen soll?
[TenForums - Win10XPE - Build Your Own Rescure Media (Page 83, KYHI)](https://www.tenforums.com/software-apps/117664-win10xpe-build-your-own-rescue-media-83.html)\
MyPlugins are part of the Release - this keeps it small, simple, and just the basics..
MoPlugins are **Member Optional Additional Plugins (Apps)** as synced with my PC (via a Mega Download Utility) to enhance the project... 

# Anderes
- Dateien ... https://github.com/LukasKurthRocks/Windows-10-Custom-ISO/tree/main/Data

## Desktop Shortcuts
==> [TenForums - Win10XPE - Build Your Own Rescure Media (Page 83, KYHI)](https://www.tenforums.com/software-apps/117664-win10xpe-build-your-own-rescue-media-104.html)\
In "D:\Win10XPE\Custom\Pecmdini\pecmd.ini", under the line "_SUB Shortcuts", add the following line:
LINK %Desktop%\App name,"X:\The file path\Application.exe"

# Zu Erledigen
- [ ] \Downloads zu D:\Users\Lukas\Desktop\WindowsBakery