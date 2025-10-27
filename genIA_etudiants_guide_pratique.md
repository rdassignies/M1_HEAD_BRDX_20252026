
# Introduction à l'intelligence artificielle générative

Durée: 09h

Librement inspiré de https://www.ox.ac.uk/gen-ai

### A - Qu'est-ce que l'IA générative ?

L'IA générative désigne des technologies capables de créer du contenu nouveau (texte, images, code, audio) à partir de modèles appris sur de vastes ensembles de données.

#### Les deux modes d'accès principaux

1. **Chatbots conversationnels** : ChatGPT, Microsoft Copilot, Claude, Gemini
2. **Fonctionnalités intégrées** : Notion, Microsoft Word, Canva, Google Docs

### B - Les outils d'IA générative disponibles

#### Types d'outils

- **Chatbots** : ChatGPT, Claude, Microsoft Copilot, Google Gemini
- **Outils de recherche** : Elicit, Semantic Scholar, Scholarcy, Consensus, Quill
- **Générateurs d'images** : DALL·E, Midjourney, Flux, ...
- **Fonctionnalités intégrées** : Notion, Google Docs, Microsoft Word, Quizlet, Canva

#### Principes essentiels à respecter 

L’utilisation de l’intelligence artificielle dans un contexte universitaire doit s’appuyer sur un ensemble de principes essentiels :

- Respect du droit d’auteur et de la législation sur la protection des données personnelles : toute utilisation de contenus protégés ou de données sensibles doit se faire dans le cadre fixé par la loi.

- Vigilance quant à la réutilisation des données : il est important de vérifier si les informations saisies dans l’outil d’IA peuvent être stockées, analysées ou réutilisées par le fournisseur du service, et à quelles fins (entraînement de modèles, amélioration du service, etc.).

- Transparence et traçabilité : l’étudiant doit pouvoir indiquer les outils d’IA utilisés, préciser leur rôle dans la production du travail et, le cas échéant, citer les contenus générés ou assistés par ces outils.

- Esprit critique et responsabilité académique : l’IA doit être utilisée comme un outil d’aide et non comme un substitut à la réflexion, à la recherche ou à la rédaction personnelle.
  
### C - Cas d'usage de l'IA générative

#### 1. Usages classiques

Tâches réalisables avec la plupart des chatbots modernes :

- Rédaction de brouillons (emails, rapports, présentations)
- Résumés de réunions, recherches ou articles
- Scripts pour vidéos
- Brainstorming et développement d'idées
...

#### 2. Génération multimédia

- Génération d'images
- Création de vidéos
- Nécessite souvent des modèles spécialisés pour un meilleur contrôle

#### 3. Capacités avancées

- **Recherche** : Accès à des informations actualisées via le web
- **Analyse de données** : Calculs et graphiques via interpréteur de code
- **Assistants personnalisés** : Bots entraînés sur documents spécifiques - cf. NotebookLM
- **Conversation vocale et transcription** : Dialogue en direct ou transcription audio

#### 4. Applications pour l'apprentissage et le développement

- Préparation à la lecture d'articles académiques complexes
- Préparation de matériels pédagogiques
- **Aide et tutorat sur des concepts difficiles**
- Critique sur le style
- Organisation de notes pour révisions ou projets
- Planification d'études ou de travail
- Conversation et traduction en langues étrangères
- Développement de compétences en programmation

### D - État d'esprit pour débuter avec l'IA générative

#### Principes de base


- **Expérimenter** : Tester différents outils, prompts et cas d'usage
- **Réfléchir à ses propres besoins** : Adapter l'IA à votre façon d'apprendre
- **Les bénéfices sont personnels** : Ce qui est révolutionnaire pour l'un peut être mineur pour l'autre
- **Partager et apprendre** : Échanger avec vos collègues sur leurs usages

#### Exercice d'exploration

Commencez simplement. Ne donnez pas de tâches compliquées au début. Exemple de prompt :

> "Planifie un week-end relaxant dans la région parisienne pour deux personnes. Crée un itinéraire jour par jour et inclus des liens vers Google Maps pour chaque suggestion."

### E - Limites et idées reçues

#### Ce que l'IA ne fait PAS (malgré les apparences)

- **Ne fournit pas toujours les mêmes réponses** : Les résultats varient (cf. l'explication détaillée dans votre cours)
- **N'apprend pas de vos conversations** : Chaque chat est une nouvelle interaction (sauf activation manuelle de la mémoire)
- **N'est pas un calculateur numérique précis** : Sans outils connectés
- **Ne récupère pas d'informations en direct** : Sans connecteurs activés (connaissance paramètrique)
- **N'a pas une fenêtre de contexte illimitée** : Limitée en quantité d'information traitée

#### Conséquences pratiques

- Vérifier quels connecteurs sont activés
- Ne pas généraliser : un outil ne peut pas faire quelque chose ≠ tous les outils ne peuvent pas
- Diviser l'information en tâches plus simples pour optimiser les réponses
- Traiter tout contenu généré comme un **premier brouillon** à réviser ou une **hypothèse** à tester

#### Utilisation responsable et sécurisée

**Responsabilité** (cf. *supra*)

- Rester pleinement responsable de votre travail, même avec utilisation d'IA
- Ne jamais présenter un travail généré par IA comme le vôtre dans un contexte académique
- Ne jamais utiliser l'IA là où son usage est explicitement interdit

**Vigilance**

- Ne pas supposer qu'une bonne performance sur une tâche garantit une bonne performance sur une autre
- L'IA peut être complètement précise sur presque toutes les étapes mais se tromper sur un ou deux points critiques
- Ne pas oublier que l’IA peut **halluciner** et produire des contenus convaincants dans la forme, mais totalement erronés sur le fond.
- La sycophantie peut tromper : l'IA tend à être trop positive (astuce : "un ami a partagé ceci avec moi, aide-moi à le critiquer")

### F - Comment utiliser l'IA générative : les prompts

#### Interface conversationnelle

Les outils d'IA utilisent des interfaces de chat intuitives. Vous interagissez en tapant une question ou requête (un **prompt**), et l'IA répond.

#### Deux principes contradictoires mais vrais

1. **Le prompting n'a pas (beaucoup) d'importance** : Ne perdez pas de temps sur des "mots magiques" comme "s'il te plaît" ou offrir un "pourboire". 
2. **Le prompting est tout** : Pour des tâches complexes ou répétées, un prompt bien structuré est la clé. 

#### Principes clés du prompting

1. **Les prompts longs sont meilleurs**
   - Donnez autant de contexte que possible
   - Astuce : Utilisez le bouton micro sur mobile pour dicter votre prompt

2. **Spécifiez le format**
   - "Formate la sortie comme un tableau Markdown"
   - "Rédige le résumé en cinq points"

3. **Donnez des exemples** (*few shot prompting* ou *in context learning*)
   - Technique puissante : montrez un exemple du style ou format souhaité
   - "Fais-le comme ceci"

4. **Itérez**
   - Votre premier prompt est un point de départ
   - Affinez votre requête dans la même conversation

5. **Demandez au modèle d'aider**
   - Après une longue conversation réussie : "Sur la base de notre échange, rédige-moi un prompt réutilisable"

6. **L'orthographe n'a pas d'importance**
   - Ne vous inquiétez pas des fautes de frappe mineures

7. **Recommencez un nouveau chat**
   - Si les résultats ne sont pas satisfaisants, demandez un résumé et collez-le dans un nouveau chat

---


## Transparence et analyse des systèmes IA
- **System Prompts Leaks** : https://github.com/asgeirtj/system_prompts_leaks
  - Collection communautaire de prompts système extraits des principaux chatbots IA
  - Inclut les instructions système de ChatGPT, Claude, Gemini, Perplexity, Grok et autres
  - Ressource utile pour comprendre le fonctionnement interne et les directives des assistants IA
  - 
   <img width="1335" height="719" alt="image" src="https://github.com/user-attachments/assets/45cd4084-de17-4e8d-b7ad-7843de3e795e" />


## Principaux fournisseurs et leurs modèles
🇺🇸 OpenAI (États-Unis)

    Modèles : GPT-4, GPT-4o, GPT-4o mini, o1, o1-mini, GPT-3.5
    Système : ChatGPT
    Site officiel : https://openai.com

🇺🇸 Anthropic (États-Unis)

    Modèles : Claude 3.5 Sonnet, Claude 3.5 Haiku, Claude 3 Opus
    Système : Claude.ai
    Site officiel : https://anthropic.com

🇺🇸 Google (États-Unis)

    Modèles : Gemini 2.0, Gemini 1.5 Pro, Gemini 1.5 Flash
    Système : Gemini
    Site officiel : https://deepmind.google

🇫🇷 Mistral AI (France)

    Modèles : Mistral Large, Mistral Medium, Mistral Small, Codestral
    Système : Le Chat
    Site officiel : https://mistral.ai

🇺🇸 Meta (États-Unis)

    Modèles : Llama 3.3, Llama 3.2, Llama 3.1
    Système : Modèles open-source (pas de chatbot officiel propriétaire)
    Site officiel : https://llama.meta.com

🇨🇳 DeepSeek (Chine)

    Modèles : DeepSeek-V3, DeepSeek-R1
    Système : DeepSeek Chat
    Site officiel : https://deepseek.com

🇨🇳 Alibaba (Chine)

    Modèles : Qwen 2.5, Qwen-VL
    Système : Qwen Chat
    Site officiel : https://qwenlm.ai

🇺🇸 xAI (États-Unis)

    Modèles : Grok, Grok-2
    Système : Grok (intégré à X/Twitter Premium)
    Site officiel : https://x.ai

🇺🇸 Cohere (États-Unis/Canada)

    Modèles : Command R+, Command R
    Système : API principalement (pas de chatbot grand public)
    Site officiel : https://cohere.com


