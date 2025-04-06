# Metasploit

msfconsole um das Terminal zu starten

Exploits - Ausnutzen von Sicherheitslücken
Payloads - Schadcode, der nach einem Exploit ausgeführt wird
Auxiliary - Hilfd-Module für Scans und Tests
Meterpreter - Interaktive Shell für kompromittierte Systeme

## Nach Verfügbaren Exploits, Payloads oder Modulen suchen

search type:exploit name:apache

## Module auswählen

use exploit/windows/smb/...

## Detaillierte Informationen über das ausgewählte Modul

info exploit/windows/smb/...

## Konfigurations Optionen des ausgewählten Moduls anzeigen

show options

## Werte setzen

set oder gset für Global

## Liste der unterstützten Zielplattformen für das Modul

show targets

## Payload-Modul für ein Exploit setzen

set PAYLOAD windows/meterpreter/...

## Angriff starten

exploit

## Zurück

back

## Liste aller laufenden Sessions

sessions

## Zu einer bestimmten Session wechseln

sessions -i 1

## Beendet die aktuelle Sitzung

exit

## Passworthashes von Benutzern aus der SAM-Datenbank ausgeben

hashdump
