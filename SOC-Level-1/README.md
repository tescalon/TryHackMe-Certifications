# SOC Level 1
<img width="250" alt="image" src="https://github.com/user-attachments/assets/5233f7e8-31b9-4c78-893f-6e60bb466232" />

## Description
J'ai complété le module **SOC Level 1** sur TryHackMe pour acquérir les compétences nécessaires à travailler comme **SOC Level 1 Analyst**. Ce parcours m'a permis de comprendre les opérations d'un SOC, la surveillance et l'analyse des événements de sécurité, la détection et la réponse aux incidents, ainsi que l'utilisation des outils SIEM et EDR. L'objectif est d'être capable de triager les alertes, investiguer sur les incidents et contribuer activement à la défense de l'organisation.

---

## Contenu du module
<img width="170" alt="image" src="https://github.com/user-attachments/assets/2de9419b-ab29-4496-9f86-b7abfd489092" />

### 1. Introduction à la Blue Team
- **Présentation du rôle d’analyste SOC L1** : découverte du rôle et missions.  
- **Fonctionnement du SOC dans la Blue Team** : responsabilités quotidiennes.  
- **Vecteurs d’attaque humains et systèmes** : identification et impact.  

Ce module m'a aidé à comprendre pourquoi un analyste SOC L1 ne "répond" pas aux incidents — il triage, documente et escalade. La nuance est importante.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/f73bd35d-d296-47a8-838d-61a2368f280e" />

### 2. Internals SOC
- **Triage et reporting des alertes (SOC L1 Alert)** : triage, priorisation et documentation des alertes.  
- **SOC Workbooks and Lookups** : utilisation des workbooks et des lookups pour enrichir les données.  
- **KPIs et objectifs SOC** : compréhension des KPIs, SLA et indicateurs de performance.  
- Scénarios pratiques : phishing simulations pour l'analyse et le reporting.

Les workbooks et lookups m'ont montré comment enrichir une alerte brute avec du contexte — une IP interne qui communique vers un domaine enregistré il y a 48h, ça change l'évaluation du risque.

---
<img width="170" alt="image" src="https://tryhackme-images.s3.eu-west-1.amazonaws.com/modules/core-soc-solutions-1761836963983.svg" />

### 3. Solutions SOC
- **Introduction aux EDR** : déploiement, surveillance des endpoints et collecte de télémétrie.  
- **Introduction aux SIEM / Splunk / Elastic Stack** : ingestion de logs, recherche, corrélation et alerting.  
- **Introduction aux SOAR** : automatisation des tâches SOC et orchestration des réponses aux incidents.

Splunk et ELK côte à côte : les deux font le même travail mais avec une logique de requête différente. Pratiquer les deux dès le départ évite d'être perdu en arrivant dans une entreprise qui utilise l'un ou l'autre.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/786aacec-fa50-4ac9-acd4-f365b3c6d09c" />

### 4. Cyber Defence Frameworks
- **Pyramid of Pain** : priorisation des indicateurs de compromission (IOC).  
- **Cyber Kill Chain / Unified Kill Chain** : identification des phases d’attaque et points d’interruption.  
- **MITRE ATT&CK** : mapping des techniques et tactiques, création de règles et playbooks.

MITRE ATT&CK est le framework qui m'a le plus apporté concrètement : pouvoir mapper une alerte sur une technique T1xxx permet de savoir immédiatement quelles autres techniques sont susceptibles de suivre.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/c916669a-04b1-4fe7-85c4-0d701d7d0016" />

### 5. Analyse de phishing
- **Bases du trafic réseau / Wireshark / NetworkMiner** : analyse d'emails suspects, extraction des liens et fichiers.  
- **Prévention du phishing** : mesures préventives pour réduire les risques utilisateurs.  
- Scénarios pratiques : identification et mitigation de phishing simulés.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/e3451aa7-d187-4ab9-a84f-3cbefe3d6ced" />

### 6. Analyse du trafic réseau
- **Network Traffic Basics / Wireshark / NetworkMiner** : capture et analyse de trafic, détection d’anomalies.  
- **Opérations sur les paquets réseaux** : suivi de flux, filtrage et inspection approfondie.  

Ces labs m'ont permis de détecter des activités suspectes sur le réseau.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/d51a4b23-ed11-48fa-a830-e894a9440c6c" />

### 7. Monitoring réseau
- **Network Security Essentials & Discovery Detection** : surveillance de la topologie et détection d’intrusions.  
- **IDS / Snort** : déploiement et utilisation pour détecter les activités malveillantes.  
- **Exfiltration de données & MitM Detection** : identification des exfiltrations et attaques man-in-the-middle.

---
<img width="170" alt="image" src="https://tryhackme-images.s3.eu-west-1.amazonaws.com/modules/web-security-monitoring-1758288631299.svg" />

### 8. Monitoring Web
- **Sécurité Web et détection des attaques** : détection de web shells, uploads malveillants et DDoS.  
- Scénarios pratiques pour suivre et analyser les attaques web.

---
<img width="170" alt="image" src="https://tryhackme-images.s3.eu-west-1.amazonaws.com/modules/windows-security-monitoring-1753787914027.svg" />

### 9. Monitoring Windows
- **Logs Windows  et détection de menaces** : événements critiques et Sysmon, détection de persistence, d'injection et d'activités suspectes PowerShell.  

---
<img width="170" alt="image" src="https://tryhackme-images.s3.eu-west-1.amazonaws.com/modules/linux-security-monitoring-1761914648963.svg" />

### 10. Monitoring Linux
- **Logs Linux et détection de menaces** : auditd, journald et détection d’activités anormales.  
- Scénarios pratiques pour investigation Linux (ex : BlackCat).

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/8c441167-82fb-4404-83cf-9255d2ae1383" />

### 11. Concepts malware pour SOC
- **Classification des malwares** : types de malwares et techniques d'attaque.  
- **Living Off the Land Attacks / Shadow Trace** : exploitation d’outils natifs pour les attaques.  
- **Introduction à l’analyse de malware** : analyse statique et dynamique basique.

---
<img width="170" alt="image" src="https://tryhackme-images.s3.eu-west-1.amazonaws.com/modules/threat-analysis-tools-1757684500027.svg" />

### 12. Threat Analysis Tools
- **Cyber Threat Intel** : collecte et corrélation des IOCs (hash, IP, domaine).  
- Utilisation de plateformes comme VirusTotal, MISP, OpenCTI.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/f1d2dd9d-7866-48da-b78c-97d1b2ee16f2" />

### 13. SIEM Triage
- **Analyse des logs avec SIEM / Splunk / Elastic** : recherches, triage et dashboards.  
- Labs pratiques (ItsyBitsy, Benign) pour appliquer les techniques de triage.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/c93533d4-9b91-4a2b-847d-c07e5935f4d5" />

### 14. Capstone Challenges
- **Tempest / Boogeyman / Hidden Hooks / Open Door** : exercices complets intégrant logs, network forensics et incident response.  
- Mise en pratique de l’ensemble des compétences SOC L1.

---

## Travaux pratiques et laboratoires
- Triage et investigation d’alertes SIEM (Splunk / ELK).  
- Analyse de trafic réseau avec Wireshark et NetworkMiner.  
- Détection d’intrusions avec Snort et monitoring endpoint avec Sysmon/Wazuh.  
- Phishing simulations et extraction d’IOCs.  
- Analyse Linux et Windows pour détection de comportements suspects.  
- Capstone labs simulant incidents réels du SOC.

---

## Compétences clés acquises
- Triage et analyse d’alertes SIEM.  
- Network & endpoint forensics (Wireshark, Sysmon, Zeek).  
- Analyse basique de malwares et extraction d’IOCs.  
- Détection et réponse à des incidents SOC L1.  
- Application des frameworks MITRE ATT&CK, Pyramid of Pain et Kill Chain.  
- Reporting et playbooks SOC.

---

## Outils et technologies utilisés
`Wireshark` · `Snort` · `Zeek` · `TShark` · `Sysmon` · `Windows Event Logs` · `osquery` · `Wazuh` · `Splunk` · `ELK Stack (Elasticsearch, Logstash, Kibana)` · `Autopsy` · `Redline` · `KAPE` · `Volatility` · `Velociraptor` · `OpenCTI` · `MISP` · `Yara` · `VirusTotal` · `urlscan.io` · `CyberChef` · `PhishTool` · `Any.Run / Hybrid Analysis`

---

## Certificat
[Voir le certificat SOC Level 1](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-PKADBL7HD0.pdf)

