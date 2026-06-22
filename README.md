# 🤖 Capacités du Système V1 (Intelligence Artificielle JARVIS)

Bienvenue dans la documentation complète des capacités de **V1**, votre assistant d'Intelligence Artificielle inspiré de JARVIS.

---

## 🔒 Authentification & Sécurité
- **Connexion sécurisée** : Le système est protégé par un mot de passe haché en SHA-256. Le mot de passe en clair n'est jamais stocké dans le code ni dans ce document.

## 🌐 Deux Modes de Fonctionnement

V1 peut opérer sous deux modes distincts, basculables via le bouton en haut à droite (ou le raccourci `Ctrl+M`) :

### 1. Mode LOCAL (Sans clé API)
Un mode hors-ligne rapide basé sur des algorithmes de reconnaissance de texte et des intégrations web directes.
- **Aucune clé API requise.**
- Réponses programmées pour les interactions de base.
- Idéal pour les recherches rapides, lancer des sites, et les mathématiques.

### 2. Mode API (Intelligence Avancée)
Connectez V1 à des modèles d'IA mondiaux pour des conversations complexes, du code, et de la réflexion poussée.
- Supporte **OpenAI** (ChatGPT)
- Supporte **Anthropic** (Claude)
- Supporte **Google** (Gemini)
- Supporte **Groq** (Llama)
- Supporte **Mistral AI**
- Les requêtes sont envoyées avec un "System Prompt" spécifiant à V1 d'être concis et d'agir comme JARVIS.

---

## ⚡ Commandes Rapides (Disponibles dans les deux modes)

V1 intercepte certaines commandes vocales ou textuelles avant même d'interroger l'API pour une exécution instantanée :

* **Recherche Google** : 
  * *Exemples :* "Cherche sur google la recette des crêpes", "Google Météo Paris"
  * *Action :* Ouvre un nouvel onglet avec les résultats Google.
* **YouTube & Musique** :
  * *Exemples :* "Musique relaxante", "Youtube trailer GTA 6"
  * *Action :* Ouvre YouTube et lance la recherche correspondante.
* **Ouvrir des liens / Navigation** :
  * *Exemples :* "Ouvre netflix.com", "Va sur github"
  * *Action :* Détecte l'URL et l'ouvre instantanément.
* **Calculatrice** :
  * *Exemples :* "Calcule 15 * 8", "Combien font 45 divisé par 3"
  * *Action :* Calcule le résultat de manière sécurisée et l'affiche dans le chat.
* **Heure & Date** :
  * *Exemples :* "Quelle heure est-il ?", "Quel jour sommes-nous ?"
  * *Action :* Affiche la date et l'heure exactes en français.

---

## 📚 Base de connaissances (Wikipedia)

Si vous posez une question factuelle (surtout en mode Local), V1 cherchera directement l'information sur Wikipedia :
- *Mots déclencheurs :* "Cherche", "C'est quoi", "Qui est", "Définition de"
- *Action :* Récupère le résumé direct de Wikipedia (d'abord en Français, puis en Anglais si introuvable) et fournit le lien source.

---

## 🎤 Commandes Vocales & Synthèse

- **Reconnaissance Vocale** : Cliquez sur l'icône micro 🎤 pour parler directement à V1 au lieu de taper. V1 retranscrira votre voix et enverra le message automatiquement.
- **Synthèse Vocale (Voix)** : Activable dans les paramètres (⚙). Lorsque cette option est cochée, V1 lira ses réponses à voix haute avec une voix française de synthèse.

---

## ⌨️ Raccourcis Clavier

Pour une navigation plus fluide, digne d'un terminal holographique :
- `Entrée` : Valider le mot de passe ou envoyer un message.
- `Ctrl + K` : Mettre le focus instantanément sur le champ de saisie du chat.
- `Ctrl + M` : Basculer entre le Mode Local et le Mode API.
- `Echap` (Escape) : Fermer le menu des paramètres.

---

## 🎨 Interface & Design

- **Arc Reactor** : Une animation centrale composée d'anneaux holographiques et d'un noyau pulsant, réagissant à l'état du système.
- **Effet de frappe** : Les réponses de V1 s'affichent lettre par lettre, imitant l'affichage progressif d'un ordinateur futuriste.
- **Indicateur JARVIS** : Un "orb" rotatif dans la barre supérieure indiquant l'activité et le statut de V1.
- **Journal d'Activité** : Un panneau latéral à droite listant l'historique complet des actions effectuées par le système en temps réel (ouverture de sites, recherches, calculs).

---

## ⚙️ Paramètres

Le panneau de configuration permet de :
- Gérer vos clés API pour les différents fournisseurs.
- Renseigner des noms de modèles spécifiques (ex: `gpt-4o`, `claude-3-opus-20240229`).
- Activer/désactiver la lecture vocale des réponses.
- Effacer complètement l'historique de la conversation.
- Se déconnecter de la session (Verrouiller le système).
