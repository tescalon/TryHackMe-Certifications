# DevSecOps
<img width="250" alt="image" src="https://github.com/user-attachments/assets/f076312a-ca28-43fe-8505-3239b586f34b" />

## Description
J'ai complété le module **DevSecOps** sur TryHackMe pour acquérir les compétences nécessaires à la sécurisation des environnements de développement modernes, des pipelines CI/CD, des conteneurs et de l'Infrastructure as Code (IaC). Ce parcours m'a permis de comprendre comment intégrer la sécurité tout au long du cycle de développement logiciel (SDLC) et d'automatiser les contrôles de sécurité dans des workflows modernes.

---

## Contenu du module
<img width="170" alt="image" src="https://github.com/user-attachments/assets/ff6ba62c-2d7c-4e66-a25a-85abdd852b11" />

### 1. Développement logiciel sécurisé
- **Introduction à DevSecOps** : présentation de la culture DevSecOps, principes de *shift-left* et intégration de la sécurité dès la conception.  
- **Cycle de vie du développement logiciel (SDLC)** : compréhension du processus classique de développement et de l’importance d’intégrer la sécurité à chaque étape.  
- **Cycle de vie sécurisé du développement (SSDLC)** : application de politiques, revues de code et tests de sécurité automatisés.  

Le shift-left en pratique : détecter une injection SQL au moment du commit plutôt qu'en production, ça change tout en termes de coût et de délai de correction.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/32c8fcf4-a456-49f5-ab2c-8f45210e0a61" />

### 2. Sécurité des pipelines
- **Introduction à l’automatisation des pipelines** : compréhension des workflows et des chaînes CI/CD.  
- **Sécurité du code source** : contrôle d’accès, gestion des branches, *secret scanning* et protection des dépôts Git.  
- **Sécurité des builds CI/CD** : validation des artefacts, signature, intégrité et protection contre l’injection de dépendances malveillantes.  

Ces labs m'ont permis de comprendre comment sécuriser un pipeline automatisé et détecter les risques dès le build.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/e4cf6794-8c7f-4fac-8cdd-c2290c649a4a" />

### 3. Sécurité dans le pipeline
- **Gestion des dépendances** : analyse de vulnérabilités via des outils comme *OWASP Dependency-Check* ou *Snyk*.  
- **Analyse statique (SAST)** : détection de failles dans le code source avant le déploiement.  
- **Analyse dynamique (DAST)** : identification de vulnérabilités dans les applications en exécution.  
- **Mother’s Secret** : laboratoire pratique appliquant ces contrôles dans un environnement réel.  

Le lab Mother's Secret m'a montré comment une dépendance compromise peut contaminer tout un pipeline — OWASP Dependency-Check est devenu un réflexe.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/e4c82b17-3923-4721-b8f9-6c741cc699eb" />

### 4. Sécurité des conteneurs
- **Introduction à la conteneurisation** : principes de fonctionnement et avantages des architectures microservices.  
- **Sécurisation des conteneurs Docker** : bonnes pratiques sur les images, gestion des secrets et durcissement des configurations.  
- **Sécurité des clusters Kubernetes** : gestion des accès (RBAC), politiques réseau, *pod security policies* et *image scanning*.  
- **Vulnérabilités des conteneurs** : détection, analyse et remédiation.  
- **Durcissement des conteneurs** : réduction de la surface d’attaque et renforcement des configurations système.  

Kubernetes RBAC et les pod security policies sont les points qui m'ont demandé le plus de temps — l'orchestration ajoute une surface d'attaque qu'on sous-estime facilement.

---
<img width="170" alt="image" src="https://github.com/user-attachments/assets/9c584f6d-e3ac-4aa8-bd44-8ce0583afb1c" />

### 5. Infrastructure as Code (IaC)
- **Introduction à l’IaC** : principes de codage de l’infrastructure et automatisation de la configuration des environnements.  
- **IaC sur site (On-Premises IaC)** : sécurisation des playbooks et scripts locaux (Ansible, Terraform, etc.).  
- **IaC dans le Cloud** : bonnes pratiques pour AWS, GCP, Azure : gestion des secrets, contrôle d’accès, chiffrement et audit.  

Terraform et Ansible vus sous l'angle sécurité : un playbook mal configuré peut ouvrir des ports ou créer des comptes avec trop de droits aussi sûrement qu'un mauvais code applicatif.

---

## Travaux pratiques et laboratoires
- Sécurisation des pipelines CI/CD avec SAST, DAST et analyse des dépendances.  
- Durcissement d’images Docker et sécurisation de clusters Kubernetes.  
- Tests de sécurité sur environnements simulés pour identifier et corriger des vulnérabilités.  
- Déploiement d’IaC sécurisé sur on-prem et cloud, avec validation automatique des configurations.

Ces travaux pratiques m'ont permis d'appliquer concrètement les concepts de DevSecOps et de sécuriser des workflows de développement modernes.

---

## Compétences clés acquises
- Sécurisation du cycle de vie logiciel (SSDLC) et intégration de la sécurité dans les pipelines CI/CD.  
- Scanning de dépendances et gestion proactive des vulnérabilités.  
- Sécurisation des conteneurs et des orchestrateurs (Docker, Kubernetes).  
- Automatisation de la sécurité via Infrastructure as Code (IaC).  
- Analyse et correction proactive des vulnérabilités dans les environnements DevOps.  
- Compréhension des frameworks et bonnes pratiques DevSecOps.

---

## Outils et technologies utilisés
`Docker` · `Kubernetes` · `SAST tools` · `DAST tools` · `OWASP Dependency-Check` · `Snyk` · `CI/CD pipelines` · `GitHub Actions / GitLab CI` · `Terraform / Ansible` · `Secrets Management` · `Cloud Security (AWS/GCP/Azure)`  

---

## Certificat
[Voir le certificat DevSecOps](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-SB7SWDIXQ1.pdf)

---
