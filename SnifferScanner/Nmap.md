# NMAP (Portscanner)

Ist ein Open-Source-Tool zur Netzwerkerkennung und Sicherheitsüberprüfung, das Netzwerke scannt, Hosts identifiziert und offene Ports sowie Dienste auf einem Zielsystem ermittelt.

## 1. Einfacher Scan einer IP oder Domain

nmap 192.168.0.1

## 2. Schneller Scan

nmap -sS 192.168.0.1

## 3. Mehrere Ziele scannen

nmap 192.168.0.1 192.168.0.2

## 4. IP-Bereich scannen

nmap 192.168.0.0/24

## 5. Offene Ports anzeigen

nmap -p 22,80, 443 192.168.0.1

## 6. Alle Ports scannen

nmap -p- 102.168.0.1

## 7. Service- und Versionserkennung

nmap -sV 192.168.0.1

## 8. Betriebssystem-Erkennung

sudo nmap -O 192.168.0.1
