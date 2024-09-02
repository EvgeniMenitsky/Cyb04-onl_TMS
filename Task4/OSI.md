# OSI Model 

| Уровень | Протоколы | Атаки |
|---------|-----------|-------|
| 1. Физический | Ethernet, USB, WI-FI, Bluetooth, xDSL  | Физическое вмешательство (tampering), Сниффинг на физическом уровне, Электромагнитное излучение (TEMPEST атаки) |
| 2. Канальный |  PPP, IEEE, DSL, ARP, сетевая карта  | Атака на дерево STP, MAC-spoofing, MAC-Flooding, ARP Spoofing, Switch Spoofing |
| 3. Сетевой | IPv4, IPv6, ICMP, AppleTalk  |  IP Spoofing, Route Injection, Ping of Death, Fragmentation Attack|
| 4. Транспортный | TCP, UDP, SCTP, ATP | UDP Flood, TCP Reset Attack, Port Scanning, TCP Session Hijacking |
| 5. Сеансовый | RPC, NetBIOS, PPTP, L2TP, ASP  | Session Hijacking, Session Replay, Timeout Manipulation |
| 6. Представления | XDR, AFP, TLS, SSL | Man-in-the-Middle,  SSL/TLS Downgrade Attack, Malware Injection, Certificate Forgery|
| 7. Прикладной | HTTP, SMTP, FTP, Telnet, SSH | DOS, DDOS, SQL Injection, XSS, Phishing, Buffer Overflow | 
