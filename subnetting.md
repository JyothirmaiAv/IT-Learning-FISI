
# Subnetting – Grundlagen

##  Bedeutung
Subnetting ist die Aufteilung eines Netzwerks in kleinere Teilnetzwerke (Subnetze).  
Ziel ist eine bessere Organisation, Sicherheit und effizientere Nutzung von IP-Adressen.

# IPv4 Grundlagen
Eine IPv4-Adresse besteht aus 4 Zahlen (z. B. 192.168.1.1).

Sie besteht aus:
- Netzwerkanteil
- Hostanteil

##  Was ist Subnetting?
Beim Subnetting wird ein großes Netzwerk in mehrere kleine Netzwerke aufgeteilt.

 Beispiel:
192.168.1.0 /24  
→ wird unterteilt in mehrere Subnetze

##  Subnetzmaske

Die Subnetzmaske bestimmt:
- welcher Teil Netzwerk ist
- welcher Teil Host ist

Beispiel:
255.255.255.0 = /24

## CIDR-Notation
Die Schreibweise "/24" zeigt, wie viele Bits für das Netzwerk verwendet werden.

👉 Beispiele:
- /24 = 255.255.255.0
- /25 = 255.255.255.128
- /26 = 255.255.255.192

# 📊 Anzahl der Hosts berechnen

Formel:
2^n − 2

👉 n = Anzahl Hostbits

Beispiel:
/24 → 8 Hostbits  
2⁸ − 2 = 254 Hosts

##  Warum Subnetting wichtig ist

- Bessere Struktur im Netzwerk  
- Mehr Sicherheit (Isolation)  
- Weniger Broadcast-Traffic  
- Effiziente Nutzung von IP-Adressen  

##  Typische Fehler 

- Netzwerkadresse und Broadcastadresse vergessen  
- Falsche Subnetzmaske wählen  
- Hostanzahl falsch berechnen  

