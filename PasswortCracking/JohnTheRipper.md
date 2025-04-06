# John the ripper

Ist ein populäres Passwort-Knacken-Tool, das auf Brute-Force- und Wörterbuchangriffen basiert.

## 1. Starten eines grundlegenden Angriffs

john --wordlist=path_to_wordlist hash_file

## 2. Hash-Algorithmen spezifizieren

john --format=raw-md5 --wordlist=path_to_wordlist hash_file

## 3. Status des laufenden Angriffs überprüfen

john --status

## 4. Brute-Force-Angriff

john --incremental --min-length=6 --max-length=6 hash_file
--incremental: Aktiviert den Brute-Force-Angriff

## 5. Wörterbuch-Angriff

john --wordlist=wordlist.txt --format=raw-md5 hash.txt

## 6. Ergebnisse anzeigen

john --show hash_file

## 7. Wortlist Kombinationen

john --wordlist=wordlist1.txt --wordlist=wordlist2.txt --rules hash_file

## 8. Unterstütze Formate anzeigen

john --list=formats
