# OSI Model 

| Уровень | Применение | Протоколы | Атаки |
|---------|-----------|-------|
| 1. Физический | Бинарная передача данных и сигналов по кабелю | Ethernet, USB, WI-FI, Bluetooth, xDSL  | |

| 2. Канальный | Бинарная передача данных и сигналов по кабелю | PPP, IEEE, DSL, ARP, сетевая карта  | Атака на дерево STP, MAC-spoofing, MAC-Flooding, ARP Spoofing, Switch Spoofing |

| 3. Сетевой | Бинарная передача данных и сигналов по кабелю | IPv4, IPv6, ICMP, AppleTalk  |  IP Spoofing, Route Injection, Ping of Death, Fragmentation Attack|

| 4. Транспортный | Бинарная передача данных и сигналов по кабелю | TCP, UDP, SCTP, ATP | UDP Flood, TCP Reset Attack, Port Scanning, TCP Session Hijacking |

| 5. Сеансовый | Бинарная передача данных и сигналов по кабелю | RPC, NetBIOS, PPTP, L2TP, ASP  | Session Hijacking, Session Replay, Timeout Manipulation |

| 6. Представления | Бинарная передача данных и сигналов по кабелю | XDR, AFP, TLS, SSL | Man-in-the-Middle,  SSL/TLS Downgrade Attack, Malware Injection, Certificate Forgery|

| 7. Прикладной | Бинарная передача данных и сигналов по кабелю | HTTP, SMTP, FTP, Telnet, SSH | DOS, DDOS, SQL Injection, XSS, Phishing, Buffer Overflow | 