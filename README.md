# Administration-Réseau-Supervision-Sécurité-Offensive

# Administration Réseau, Supervision & Sécurité Offensive

> Laboratoire « infos.ma Lab » simulant une infrastructure d'entreprise complète : routage dynamique OSPF, ACL et NAT sous Cisco, administration Windows Server (AD/DNS/DHCP), supervision Zabbix sur Ubuntu, et audit de sécurité offensive avec Kali Linux.

**Auteur :** Safae Kanbouh
**Année universitaire :** 2025 – 2026
**Outils de simulation :** GNS3 + VMware Workstation

---

## 📖 Description

Dans un contexte où les entreprises reposent sur des infrastructures réseau complexes et hétérogènes (Windows, Linux, équipements Cisco), assurer à la fois la disponibilité des services, la sécurité des accès et la détection rapide des incidents devient un enjeu majeur.

Ce laboratoire, baptisé **infos.ma Lab**, simule un environnement d'entreprise complet en couvrant toutes les étapes : configuration réseau multi-segmentée, déploiement des services d'annuaire, supervision continue de l'infrastructure, et audit de sécurité offensive pour évaluer les vulnérabilités présentes.

## 🎯 Objectifs

- Mettre en place un réseau multi-segmenté avec routage dynamique (OSPF) entre plusieurs routeurs Cisco
- Configurer des listes de contrôle d'accès (ACL) pour restreindre les flux entre les différents segments
- Implémenter le NAT pour permettre l'accès à Internet depuis le réseau interne
- Déployer un contrôleur de domaine Active Directory avec les services DNS et DHCP associés
- Administrer un serveur Linux (Ubuntu) et y installer les services nécessaires (Apache, Zabbix)
- Mettre en œuvre une solution de supervision centralisée (Zabbix) pour surveiller la disponibilité et les performances des équipements
- Réaliser des tests de vulnérabilité internes avec Kali Linux (Nmap, Nikto, Nessus) afin d'évaluer le niveau de sécurité de l'infrastructure

## 🛠️ Technologies utilisées

- **Réseau Cisco :** routage dynamique OSPF, ACL, NAT — simulation via GNS3
- **Virtualisation :** VMware Workstation (Windows Server 2019, Ubuntu Server, Kali Linux)
- **Protocoles & services réseau :** OSPF, NAT, DHCP, DNS, HTTP/HTTPS, ICMP, SNMP
- **Administration de domaine :** Active Directory, DNS, DHCP (Windows Server)
- **Supervision :** Zabbix (surveillance CPU, RAM, disponibilité des services) sur serveur Ubuntu
- **Sécurité offensive (pentest) :** Kali Linux — Nmap, Nikto, Nessus
