# Security Engineer
<img width="230" alt="image" src="https://github.com/user-attachments/assets/d9e47916-ad6a-4e6b-bddc-358740ba1423" />

## Description
J'ai complété le module **Security Engineer** sur TryHackMe pour acquérir les compétences nécessaires à la conception, l'évaluation et la protection d'infrastructures, de systèmes et d'applications. Ce parcours m'a permis de comprendre l'ingénierie de la sécurité sous plusieurs angles : architecture sécurisée, durcissement, gestion des risques, sécurité logicielle et réponse aux incidents. L'objectif est d'être capable d'identifier proactivement les risques, de proposer des mesures techniques et organisationnelles et d'intervenir comme premier répondant en cas d'incident.

---

## Contenu du module
<img width="170"  alt="image" src="https://github.com/user-attachments/assets/7f881358-c072-4e5f-a439-88420db4782d" />

### 1. Introduction à l'ingénierie de la sécurité
- **Introduction à l’ingénierie sécurité** : panorama des missions et du rôle d'ingénieur sécurité en entreprise.  
- **Principes de sécurité** : principes fondamentaux (sécurité par défaut, principe du moindre privilège, défense en profondeur).  
- **Introduction à la cryptographie** : rappels sur chiffrement symétrique/asymétrique, certificats, PKI et signatures.  
- **Gestion des identités et des accès (IAM)** : gestion des identités, authentification, autorisation, MFA et lifecycle des comptes.

Le principe du moindre privilège et la défense en profondeur reviennent dans absolument chaque section qui suit — autant les avoir bien en tête dès le début.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/c69e7968-db62-4cd3-91f2-739a18c55675" />

### 2. Menaces et gestion des risques
- **Gouvernance et réglementation** : compréhension des exigences réglementaires, normes et rôles GRC.  
- **Modélisation des menaces** : techniques de modélisation des menaces (STRIDE, DREAD, attaque surface analysis) pour prioriser les mitigations.  
- **Gestion des risques** : identification, évaluation et traitement des risques (accept, mitigate, transfer, avoid).  
- **Gestion des vulnérabilités** : cycle de vie des vulnérabilités : discovery, triage, patching, exceptions et reporting.

Ce module m'a forcé à penser au-delà du technique : une vulnérabilité critique sur un système non-critique n'a pas la même priorité qu'une vulnérabilité moyenne sur un asset exposé. C'est basique, mais ça change vraiment l'approche.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/cb3f5a2a-7796-48c9-80f7-b719edd9bdd7" />

### 3. Sécurité réseau et système
- **Architecture réseau sécurisée** : segmentation, firewalling, conception défensive.  
- **Durcissement Linux** : sécurité des services, permissions, audit et automatisation.  
- **Durcissement Windows** : GPO, baselines, surveillance et sécurité des comptes.  
- **Durcissement Active Directory** : protection des DC, délégations et prévention des élévations de privilèges.  
- **Durcissement des équipements réseau** : sécurité des routeurs, switches et VPN.  
- **Protocoles de sécurité réseau** : TLS, IPsec, 802.1X.  
- **Virtualisation et conteneurs** : bonnes pratiques d’isolation et de réduction de surface d’attaque.  
- **Introduction à la sécurité Cloud** : IAM cloud, responsabilité partagée, logging et encryption.  
- **Audit et supervision** : logs critiques, corrélation et indicateurs de sécurité.  

Le durcissement Active Directory a été le plus exigeant — délégations, protection des DC, prévention des Kerberoasting... c'est dense mais utile.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/7663ff5d-418d-49e9-9e4a-4d972365b7c7" />

### 4. Sécurité logicielle
- **OWASP Top 10 / Sécurité des API** : prévention des vulnérabilités web et API (injections, auth flaws, etc.).  
- **SSDLC (Secure Software Development Life Cycle)** : intégration de la sécurité dans les phases de développement.  
- **SAST / DAST** : analyses statiques et dynamiques, intégration dans CI/CD.  
- **Exploitation des vulnérabilités** : comprendre l’impact pour prioriser les correctifs.  
- **Introduction au DevSecOps** : automatisation, secret management et sécurité des pipelines.      
- Labs spécifiques (Mother's Secret, Traverse) : exercices pratiques sur sécurisation et test d'environnements.

Ce module m'a forcé à penser au-delà du technique : une vulnérabilité critique sur un système non-critique n'a pas la même priorité qu'une vulnérabilité moyenne sur un asset exposé. C'est basique, mais ça change vraiment l'approche.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/3b21e5c8-5605-48bb-a1df-48ce554ecc5f" />

### 5. Gestion des incidents
- **Introduction à la réponse aux incidents** : phases IR, rôles et coordination.  
- **Journalisation et traçabilité** : logs critiques, rétention et preuves numériques.  
- **Premier intervenant** : containment, acquisition d’artefacts, escalade.  
- **Gestion de crise cyber** : coordination inter-équipes, communication et plan d’action.  

Les simulations IR m'ont appris une chose importante : dans les premières minutes d'un incident, la priorité c'est le confinement, pas l'investigation. Collecter des preuves sur un système toujours compromis ne sert à rien.

---

## Travaux pratiques et laboratoires
- Durcissement d'instances Linux et Windows via checklist et GPO.  
- Architecture réseau sécurisée et segmentation de zones.  
- Scans SAST/DAST sur applications d'exemple, triage et remédiation.  
- Scénarios de threat modelling et exercices de gestion des risques.  
- Simulations IR : collecte d'artefacts, logs, snapshots et génération de rapports d'incident.  
- Intégration de contrôles DevSecOps dans pipelines CI/CD (exemples de checks SAST, secrets scanning).

Ces travaux m'ont apporté de l'expérience concrète dans la conception et l'opération d'environnements sécurisés.

---

## Compétences clés acquises
- Conception d'architectures réseau et systèmes sécurisées.  
- Durcissement Windows, Linux et Active Directory.  
- Mise en place et gouvernance de pipelines DevSecOps sécurisés (SAST/DAST, secrets).  
- Modélisation des menaces et gestion des risques.  
- Développement et exécution de playbooks d'incident et première réponse.  
- Compréhension opérationnelle des contrôles cloud et des dispositifs de monitoring.

---

## Outils et technologies utilisés
`GPO` · `SAST/DAST tools` · `Docker` · `Kubernetes (intro)` · `Nmap` · `Burp Suite` · `Wireshark` · `PowerShell` · `Bash` · `ELK` · `Wazuh` · `Sysmon` · `Cloud IAM concepts`

---

## Certificat
[Voir le certificat Security Engineer](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-RABDLXREIO.pdf)

---

