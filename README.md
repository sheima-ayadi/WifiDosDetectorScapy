# WiFi DoS Detector with Scapy

## Description

Ce projet utilise la bibliothèque Python `scapy` pour détecter des attaques de déni de service (DoS) sur un réseau WiFi. Il capture les paquets réseau et analyse le trafic pour identifier des volumes inhabituels de paquets, ce qui peut indiquer une attaque. Les adresses IP des paquets capturés sont également affichées pour identifier les sources potentielles d'une attaque.

## Prérequis

- **Python 3.7+** : Ce script est écrit en Python et nécessite une version 3.7 ou plus récente.
- **Scapy** : Une bibliothèque pour manipuler les paquets réseau. Installez-la avec :
  
  ```bash
  pip install scapy
## pour lancer le script 
python wifi_dos_detector.py
