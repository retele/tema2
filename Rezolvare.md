# Tema 2

- [1. Controlul congestiei (25%)](#congestion)
- 2. Exercițiu la alegere (25%)
  - [Rutare](#rutare)
  - [HTTP API](#http)
- [3. ARP Spoofing (25%)](#arp_spoof)
- [4. TCP Hijacking (25%)](#tcp_hij)


## 1. Controlul congestiei (25%)

### 1.1 Diagrama pentru RENO este:

![alt text](https://www.networkers-online.com/blog/wp-content/uploads/2016/10/STEVENS2-1024x552.jpg)

- Slow Start
- Congestion Avoidance
- Fast Retransmit 
- Fast Recovery

### 1.2 Diagrame pentru ...

- A
- B
- C

## 2. Exercițiu la alegere

### Rutare

- Forwarding vs. Routing 
- Link State Routing 
- Distance Vector Routing 
- Open Shortest Path First 
- Border Gateway Protocol Routing 

### HTTP API

Aplicația poate fi accesata la adresa:
```
http://ec2-34-34-34-34.compute-1.amazonaws.com/subnetting
```


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
