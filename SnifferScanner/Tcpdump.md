# TCPDUMP (Netzwerk-Sniffer)

Ist ein Netzwerk-Analyse-Tool, mit dem der Netzwerkverkehr in Echtzeit erfasst und detailliert angezeigt werden kann, um Probleme zu diagnostizieren und die Kommunikation zwischen Geräten zu überwachen.

## 1. Schnittstelle angeben

sudo tcpdump -i eth

## 2. Nur 10 Pakete anzeigen

sudo tcpdump -c 10

## 3. Nur Pakete einese bestimmten Hosts

sudo tcpdump host 192.168.0.1

## 4. Nur TCP anzeigen

sudo tcpdump tcp

## 5. Nur Verkehr auf einem bestimmten Port

sudo tcpdump port 80
sudo tcpdump tcp port 443

## 6. In eine Datei mitschreiben

sudo tcpdump -i eth0 -w capture.pcap

## 7. Aufzeichnung lesen

tcpdump -r capture.pcap
