# Tema 2

- [Controlul congestiei (25%)](#congestion)
- Exercițiu la alegere (25%)
  - [Rutare](#rutare)
  - [HTTP API](#http)
- [ARP Spoofing (25%)](#arp_spoof)
- [TCP Hijacking (25%)](#tcp_hij)


<a name="congestion"></a> 
## 1. Controlul congestiei (25%)

### 1.1 Diagrama pentru RENO este:

![alt text](![plot1](https://user-images.githubusercontent.com/61222782/121704885-d4fe8d00-cadc-11eb-87e6-d70caf0de779.png)


- Slow Start
- Congestion Avoidance
- Fast Retransmit 
- Fast Recovery

### 1.2 Diagrame pentru ...

- A
- B
- C


<a name="rutare"></a> 
## 2. Exercițiu la alegere (25%)

<a name="rutare"></a> 
### Rutare

- Forwarding vs. Routing 
- Link State Routing 
- Distance Vector Routing 
- Open Shortest Path First 
- Border Gateway Protocol Routing 

<a name="http"></a> 
### HTTP API

Aplicația poate fi accesata la adresa:
```
http://ec2-34-34-34-34.compute-1.amazonaws.com/subnetting
```

<a name="arp_spoof"></a> 
## 3. ARP Spoofing (25%)

Scrieție mesajele primite de server, client și printați acțiunile pe care le face middle.
```
logs din aplicația voastră
```

Rulați pe `middle` comanda `tcpdump -SntvXX -i any` și salvați log-urile aici. Încercați să salvați doar cateva care conțin HTML-ul de la request-ul din server.
```
logs de tcpdump
```
Puteți pune și capturi de ecran din wireshark prin orice alte metode de prezentare.

<a name="tcp_hij"></a> 
## 4. TCP Hijacking (25%)
Scrieție mesajele primite de server, client și printați acțiunile pe care le face middle.
```
logs din aplicația voastră
```

Rulați pe `middle` comanda `tcpdump -SntvXX -i any` și salvați log-urile aici. Încercați să salvați doar cateva care conțin HTML-ul de la request-ul din server.
```
logs de tcpdump
```
Puteți pune și capturi de ecran din wireshark prin orice alte metode de prezentare.
