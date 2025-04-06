# HASHCAT

Ist ein leistungsstarkes Passwort-Cracking-Tool, das verschiedene Hash-Algorithmen entschlüsseln kann, indem es Brute-Force-, Wörterbuch- und hybride Angriffe verwendet.

## 1. Grundlegender Aufbau

hashcat Optionen Hash-Datei Wörterbuch-Datei

## 2. Hash-Algorithmus vorgeben

hashcat -m 0 -a 0 hash.txt rockyou.txt
-m steht für Hash-Modus

## 3. Output in einer Datei speichern

hashcat -m 0 -a 0 -o output.txt hash.txt rockyou.txt

## 4. Hash-Modus rausfinden

Mit dem tool hashid (Python-Skript) im Terminal
Auf der Seite hashcat.net
