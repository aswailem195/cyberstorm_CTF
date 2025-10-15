# 🌪️ CyberStorm CTF 2025 - Organisation & Création de Challenges

![CyberStorm CTF Banner](./1.jpg)

## 📋 Vue d'ensemble du projet

**CyberStorm CTF** est la première compétition Capture The Flag organisée par les étudiants de Master 1 en cybersécurité. Cet événement pédagogique avait pour objectif de rassembler étudiants débutants et confirmés autour de défis concrets en cybersécurité, tout en créant une communauté durable autour de la pratique offensive.

### 🎯 Objectif principal
Concevoir de A à Z un événement CTF pédagogique et stimulant qui permette aux participants de tous niveaux d'apprendre, de pratiquer et de progresser dans différents domaines de la cybersécurité offensive.

---

## 📊 Chiffres clés de l'événement

| Métrique | Valeur |
|----------|--------|
| 👥 **Participants** | ~60 étudiants |
| 👨‍💼 **Organisateurs** | 9 membres coordonnés |
| 🎯 **Catégories** | 8 domaines techniques |
| 🚩 **Challenges** | 25+ défis créés |
| ⏱️ **Durée** | Journée complète (8h) |
| 🤝 **Sponsors** | CyberSchool (principal) |
| 📈 **Taux de satisfaction** | 95% (feedback positif) |

---

## 🎪 L'événement en images

### 📸 Galerie photos

![Équipe d'organisation](./2.jpg)
*L'équipe d'organisation de CyberStorm CTF 2025*

![Participants en action](./3.jpg)
*Les participants concentrés sur les challenges*

![Plateforme CTF](./4.jpg)
*Interface de la plateforme CTFd personnalisée*

![Cérémonie de remise des prix](./5.jpg)
*Remise des prix aux équipes gagnantes*

---

## 🎯 Les 8 catégories du CTF

### 1. 🌐 Web Security
- Exploitation de vulnérabilités web classiques et modernes
- SQLi, XSS, CSRF, SSRF, XXE
- Challenges progressifs du niveau débutant à avancé

### 2. 💣 PWN (Binary Exploitation)
- Exploitation de binaires vulnérables
- Buffer overflow, format strings, ROP
- Introduction aux protections modernes (ASLR, PIE, Canaries)

### 3. 🔍 OSINT (Open Source Intelligence)
- Techniques de reconnaissance et collecte d'informations
- Analyse de réseaux sociaux et métadonnées
- Géolocalisation et corrélation de données

### 4. 🔄 Reverse Engineering
- Analyse statique et dynamique de binaires
- Désobfuscation de code
- Cracking de programmes

### 5. 🌐 Réseau (Network Security)
- Analyse de captures réseau (PCAP)
- Exploitation de protocoles vulnérables
- Reconnaissance et énumération réseau

### 6. 🔬 Forensics
- Analyse de fichiers corrompus ou cachés
- Investigation numérique
- Récupération de données et steganographie

### 7. 🔐 Cryptographie
- Cryptanalyse de systèmes faibles
- Attaques sur algorithmes classiques
- Challenges de décryptage créatifs

### 8. 💻 Programmation
- Résolution algorithmique de problèmes
- Scripting et automatisation
- Défis logiques et mathématiques

---

## 🛠️ Mes responsabilités et contributions

### 🎨 Création de Challenges Techniques

#### 🔍 Catégorie OSINT

##### Challenge 1 : "Digital Footprint" 
**Niveau : Facile (100 points)**

**Description :**
Un challenge d'introduction à la reconnaissance passive via les réseaux sociaux et l'analyse de métadonnées d'images.

**Objectifs pédagogiques :**
- Comprendre l'importance des métadonnées EXIF
- Initiation à la recherche sur les réseaux sociaux
- Sensibilisation à l'empreinte numérique personnelle

**Compétences requises :**
- Utilisation d'outils d'analyse EXIF (exiftool)
- Recherche basique sur réseaux sociaux
- Navigation web et observation

**Taux de résolution : 78%**

---

##### Challenge 2 : "Ghost Hunter"
**Niveau : Moyen (250 points)**

**Description :**
Investigation complexe nécessitant la corrélation d'informations provenant de multiples sources pour identifier une cible mystérieuse.

**Objectifs pédagogiques :**
- Maîtriser la corrélation d'informations multi-sources
- Utiliser des techniques OSINT avancées
- Développer une méthodologie d'investigation structurée

**Compétences requises :**
- Recherche avancée (Google Dorking)
- Analyse de profils sur multiples plateformes
- Croisement de données temporelles et géographiques
- Utilisation d'outils OSINT (Maltego, theHarvester)

**Taux de résolution : 42%**

---

##### Challenge 3 : "Shadow Trace"
**Niveau : Difficile (400 points)**

**Description :**
Investigation d'élite combinant OSINT avancé, analyse de données publiques, géolocalisation précise et techniques de corrélation complexes pour traquer une organisation fictive.

**Objectifs pédagogiques :**
- Maîtriser les techniques OSINT de niveau professionnel
- Développer une approche méthodique face à la complexité
- Comprendre les limites éthiques et légales de l'OSINT

**Compétences requises :**
- Géolocalisation avancée (Google Earth, Yandex)
- Analyse de métadonnées complexes
- Reconnaissance d'infrastructures
- Corrélation temporelle et spatiale de données
- Utilisation d'APIs et de scripts personnalisés

**Taux de résolution : 15%**

---

#### 💣 Catégorie PWN

##### Challenge 1 : "Stack Overflow 101"
**Niveau : Facile (100 points)**

**Description :**
Introduction pratique aux buffer overflows avec un binaire 32 bits sans protections, conçu pour les débutants en exploitation binaire.

**Objectifs pédagogiques :**
- Comprendre le fonctionnement de la stack
- Identifier une vulnérabilité de buffer overflow
- Réaliser une première exploitation simple

**Compétences requises :**
- Lecture de code C basique
- Utilisation de GDB pour le debugging
- Concepts de mémoire (stack, registres)
- Écriture de payload simple en Python

**Protections : Aucune (NX, ASLR, PIE désactivés)**
**Taux de résolution : 65%**

---

##### Challenge 2 : "Return to Victory"
**Niveau : Moyen (300 points)**

**Description :**
Challenge d'exploitation intermédiaire introduisant les techniques de Return-Oriented Programming (ROP) avec NX activé.

**Objectifs pédagogiques :**
- Comprendre la protection NX/DEP
- Maîtriser les gadgets ROP
- Construire une ROP chain fonctionnelle

**Compétences requises :**
- Analyse de binaires avec Ghidra/IDA
- Identification de gadgets ROP (ROPgadget, ropper)
- Construction de chaînes d'exploitation
- Scripting Python avec pwntools

**Protections : NX activé, ASLR désactivé**
**Taux de résolution : 28%**

---

##### Challenge 3 : "Heap Havoc"
**Niveau : Difficile (450 points)**

**Description :**
Challenge avancé d'exploitation du heap avec vulnérabilité use-after-free, nécessitant la compréhension des allocateurs mémoire.

**Objectifs pédagogiques :**
- Comprendre le fonctionnement du heap (malloc/free)
- Exploiter des vulnérabilités use-after-free
- Contourner les protections modernes

**Compétences requises :**
- Connaissance approfondie du heap (glibc malloc)
- Analyse dynamique avec GDB + pwndbg
- Techniques d'exploitation heap avancées
- Développement d'exploits complexes

**Protections : NX + Partial RELRO**
**Taux de résolution : 8%**

---

---

### 👥 Coordination d'équipe

#### Structure organisationnelle

**Équipe de 9 organisateurs répartis en pôles :**

**Pôle Technique (4 personnes, dont moi) :**
- Création de challenges
- Infrastructure et déploiement
- Support technique pendant l'événement
- Résolution de bugs en temps réel

**Pôle Logistique (2 personnes) :**
- Réservation de salles
- Matériel informatique
- Restauration et pauses
- Gestion des accès

**Pôle Communication (2 personnes) :**
- Promotion de l'événement
- Gestion des inscriptions
- Réseaux sociaux
- Relations avec les sponsors

**Coordination générale (1 personne) :**
- Synchronisation entre les pôles
- Gestion du planning
- Prise de décisions stratégiques
- Interface avec l'administration

#### Outils de collaboration utilisés

- **Discord** : Communication temps réel, channels par pôle
- **Notion** : Documentation, planning, suivi des tâches
- **GitHub** : Gestion du code et des challenges
- **Google Drive** : Partage de documents et ressources
- **Trello** : Board Kanban pour le suivi d'avancement

#### Réunions et planification

**Timeline de préparation (3 mois) :**
- **Mois 1** : Brainstorming, définition du concept, constitution des équipes
- **Mois 2** : Création des challenges, tests, développement de la plateforme
- **Mois 3** : Déploiement, communication, répétitions, logistique finale

**Réunions hebdomadaires :**
- Point d'avancement de chaque pôle
- Résolution de problèmes
- Ajustements du planning
- Validation des challenges créés

---

### 🚨 Support en direct pendant l'événement

#### Jour J : Gestion opérationnelle

**Horaires de l'événement :**
- **08h00** : Installation et derniers tests
- **09h00** : Accueil des participants et briefing
- **09h30** : Lancement officiel du CTF
- **12h30** : Pause déjeuner
- **17h30** : Fin des épreuves
- **18h00** : Cérémonie de remise des prix et débriefing

#### Incidents gérés en temps réel

**Incident 1 : Surcharge serveur (10h15)**
- **Problème** : Pic de connexions causant des ralentissements
- **Action** : Ajout d'une instance CTFd supplémentaire en 15 minutes
- **Résultat** : Service restauré sans perte de données

**Incident 2 : Challenge PWN inaccessible (11h30)**
- **Problème** : Container Docker crashé suite à trop de connexions
- **Action** : Redémarrage et augmentation des ressources allouées
- **Résultat** : Challenge en ligne en 5 minutes, temps compensé

**Incident 3 : Flag incorrect signalé (14h20)**
- **Problème** : Typo dans un flag OSINT
- **Action** : Correction immédiate et validation rétroactive des soumissions
- **Résultat** : Participants impactés crédités avec des excuses publiques

#### Support aux participants

**Channels de support :**
- **Discord #support** : Questions générales et techniques
- **Sur place** : Stand d'aide avec 2 organisateurs en permanence
- **Hints système** : Indices progressifs débloquables sur la plateforme

**Questions fréquentes traitées :**
- Problèmes de connexion aux challenges
- Clarifications sur les énoncés
- Aide au debugging (sans donner la solution)
- Conseils méthodologiques pour les débutants

**Statistiques de support :**
- 47 tickets Discord traités
- 35 interventions en présentiel
- 12 hints débloqués par les équipes
- Temps de réponse moyen : 3 minutes

---

## 🤝 Partenariats et sponsors

### 🎓 CyberSchool (Sponsor principal)

**Contribution :**
- Financement des serveurs et infrastructure
- Dotations pour les équipes gagnantes (licences logicielles, formations)
- Promotion de l'événement auprès de leur réseau
- Présence d'intervenants professionnels

**Contreparties :**
- Logo visible sur la plateforme et communication
- Stand de présentation lors de l'événement
- Session de recrutement pour stages et alternances

### 🏫 Support institutionnel

**Université/École :**
- Mise à disposition de salles et matériel
- Autorisation d'utilisation des réseaux informatiques
- Couverture assurance de l'événement
- Promotion via les canaux officiels

**Encadrants académiques :**
- Validation pédagogique du projet
- Conseils sur la conception des challenges
- Présence lors de l'événement
- Évaluation du projet dans le cadre du Master

---

## 📈 Résultats et impact

### 🏆 Classement final

**Podium :**
1. **🥇 Team ByteBusters** - 3250 points
2. **🥈 Team Shadow Ninjas** - 2980 points
3. **🥉 Team CyberPunks** - 2750 points

**Répartition des participants :**
- 15 équipes constituées (3-5 personnes par équipe)
- 8 participants individuels
- Niveau : 40% débutants, 45% intermédiaires, 15% avancés

### 📊 Statistiques de participation

**Engagement :**
- **Taux de completion** : 72% des participants ont résolu au moins 5 challenges
- **First bloods** : 18 challenges résolus dans la première heure
- **Catégorie la plus populaire** : Web (85% de participation)
- **Catégorie la plus difficile** : PWN (28% de taux de résolution moyen)

**Progression pédagogique :**
- 92% des débutants ont résolu au moins 1 challenge de chaque catégorie
- 67% ont déclaré avoir appris de nouvelles techniques
- 89% souhaitent participer à une future édition

### 💬 Retours et feedbacks

#### Feedback des participants

**Points positifs (enquête post-événement) :**
- ⭐ **Qualité des challenges** : 4.7/5
- ⭐ **Organisation générale** : 4.8/5
- ⭐ **Support et accompagnement** : 4.9/5
- ⭐ **Plateforme technique** : 4.6/5
- ⭐ **Ambiance** : 4.9/5
