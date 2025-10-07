# Simulation de Réseau Local en C (SAE2.3 - Réseaux)

## Description  
Application en langage C permettant de modéliser et simuler le fonctionnement d’un réseau local à l’aide de structures de données (stations, switchs, trames Ethernet). Tentative de reproduire le comportement du protocole Ethernet et du protocole STP (Spanning Tree Protocol).

## Fonctionnalités  
- Création de structures de données pour représenter :
  - des **stations** (adresses MAC et IP)  
  - des **switchs** (MAC, nombre de ports, priorité, table de commutation)  
  - un **réseau local** sous forme de **graphe**  
- Lecture et écriture d’un **fichier de configuration** décrivant l’architecture réseau  
- Affichage détaillé des **adresses MAC/IP** et des **tables de commutation**  
- Simulation de la **commutation de trames Ethernet** :
  - représentation fidèle d’une trame  
  - affichage des trames en format lisible et en hexadécimal  
- Implémentation du **protocole STP** (Spanning Tree Protocol) :
  - échanges automatiques de **BPDU** entre switchs  
  - détermination des ports racines, désignés ou bloqués  
  - convergence automatique du réseau sans boucle  
