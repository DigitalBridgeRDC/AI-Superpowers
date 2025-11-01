## 🧠 Concepts Clés — Approfondis

### L'IA n'est pas de la magie — ce sont des motifs dans les nombres

**Ce que ça signifie :** Les ordinateurs transforment tout en nombres (pixels, mots, échantillons audio, valeurs de capteurs), puis repèrent des motifs dans ces nombres.

**Au quotidien :** Votre téléphone « reconnaît » un visage en comparant les motifs numériques des pixels ; la traduction mappe des vecteurs de mots (nombres) d'une langue à l'autre.

**Mini-exercice :** Prenez n'importe quel objet (ex: une photo). Demandez-vous : « Comment transformer ceci en nombres ? » (valeurs RVB par pixel ; tableau hauteur × largeur × 3).

**À retenir :** Si vous pouvez le représenter en nombres, vous pouvez y appliquer l'IA.

---

### Apprentissage Automatique (ML) — apprendre à partir d'exemples

**Ce que ça signifie :** Au lieu d'écrire des règles à la main, nous fournissons des exemples et laissons le modèle apprendre la règle.

**Principaux types :**
* Supervisé : exemples étiquetés (email → spam/pas spam).
* Non supervisé : trouver une structure sans étiquettes (regrouper des étudiants par habitudes d'étude).
* Auto-supervisé : apprendre à partir des données elles-mêmes (prédire le mot suivant dans une phrase).
* Apprentissage par renforcement : apprendre par essais et récompenses (un robot apprend à marcher).

**Mini-exercice :** Utilisez Teachable Machine pour entraîner un classificateur d'images à 2 classes en quelques minutes (webcam).

---

### IA Générative — créer du nouveau contenu à partir de motifs

**Ce que ça signifie :** Les modèles apprennent la distribution des données (texte, images, musique) et y piochent pour produire de nouveaux textes, images, sons ou vidéos.

**Au quotidien :** Des réponses de chat qui semblent humaines ; des images « dans le style de… » ; de la musique qui correspond à une ambiance.

**Conseil :** Les bons résultats proviennent d'instructions claires + contraintes (style, longueur, public).

**Essayez :** Texte (ChatGPT/Claude), Images (DALL·E/Midjourney), Musique (Suno/Udio), Vidéo (Veo/Kling).

---

### La formulation de prompts (Prompting) — parler à l'IA pour qu'elle vous aide mieux

**Compétences clés :**
* Rôle : « Agis en tant que tuteur de maths pour un enfant de 12 ans. »
* Tâche : « Explique les fractions avec une analogie de pizza, en 5 points. »
* Contraintes : « Reste sous 120 mots ; inclus 1 exemple. »
* Itérer : Affiner avec « simplifie », « maintenant, fais-moi un quiz. »

**Cadre (Framework) :** RATC → Rôle, Audience (Public), Tâche, Contraintes.

**Astuce de pro :** Donnez du contexte (données d'entrée, exemples, guide de style) et demandez des checklists ou des grilles d'évaluation pour vous auto-évaluer.

---

### Hallucinations — des réponses fluides mais erronées

**Ce que c'est :** Le modèle « complète » avec les mots les plus probables, pas des faits garantis. Il peut donc sembler confiant tout en étant incorrect ou en inventant des sources.

**Comment réduire le risque :**
* Demandez des sources / citations.
* Fournissez un contexte fiable (documents, données).
* Utilisez la récupération (RAG) ou des outils avec des données réelles.
* Vérifiez les affirmations critiques avec un second outil (ex: Perplexity pour les citations).

**Bon ajout au prompt :** « Si tu n'es pas sûr, dis-le. »

---

### RAG (Génération Augmentée par Récupération)

**Ce que ça signifie :** Avant de répondre, le système cherche dans votre base de connaissances (PDF, sites, BDD), extrait les passages pertinents, puis le modèle rédige en utilisant ces extraits.

**Pourquoi c'est puissant :** Moins d'hallucinations, des réponses ancrées dans vos données, et des mises à jour faciles (changez les documents, pas le modèle).

**Modèle mental :** Chercher → Sélectionner → Synthétiser.

**Idée de départ :** Créez un bot de Q&R sur vos règlements ou notes de cours ; comparez les réponses avec/sans récupération.

---

### Agents IA — des assistants orientés objectifs et utilisant des outils

**Ce qu'ils font :** Ils décomposent les objectifs en étapes, appellent des outils (web, code, tableurs, API), vérifient les résultats, et continuent jusqu'à ce que ce soit fait.

**Exemple :** « Planifie un atelier de 2 jours à Kinshasa, rédige des slides et envoie une checklist par email. » L'agent cherche des lieux, génère des plans et compose des emails (avec approbation humaine).

**Attention :** C'est excellent pour l'automatisation des workflows, mais nécessite toujours une supervision (gardes-fous, budgets et révision).

---

### Utiliser l'IA : « Super Google » vs « Système d'Exploitation »

**Super Google (moteur de réponse) :** Posez des questions, obtenez des réponses synthétisées et citées (hybride chat + recherche). Idéal pour la recherche et les explications. (Essayez Perplexity/Copilot.)

**Système d'Exploitation (couche copilote) :** L'IA intégrée partout — documents, slides, IDE, navigateurs — pour rédiger, vérifier, résumer, automatiser. Pensez à l'IA comme une appli d'aide universelle qui se superpose à vos outils.

---

### Progrès exponentiel — pourquoi c'est si soudain

**Intuition :** Les capacités se cumulent : de petites améliorations mensuelles s'empilent rapidement. Ce qui semblait « impossible » l'an dernier devient normal.

**Analogie du stade (prospective) :** Si l'eau double chaque minute, vous ne voyez que quelques flaques pendant longtemps, puis — soudainement — le stade est inondé vers la fin. Avec la tech, la plupart de l'impact arrive tardivement et rapidement.

**Comment s'adapter :** Apprenez les fondamentaux, continuez à expérimenter, et suivez les mises à jour de manière rythmée (ex: mensuellement). Une petite pratique régulière vaut mieux que de gros rattrapages occasionnels.

---

### Éthique & sécurité — le pouvoir implique la responsabilité

**Transparence :** Dites quand l'IA a aidé (« Rédigé avec l'IA »).

**Confidentialité :** Minimisez ou anonymisez les données personnelles ; ne collez pas de secrets dans les outils publics.

**Légalité :** Respectez les droits d'auteur, les licences et les réglementations locales.

**Biais & équité :** Testez les résultats sur divers cas ; évitez les stéréotypes nuisibles.

**Attribution :** Lorsque vous utilisez des sources ou entraînez sur vos données, citez/créditez de manière appropriée.

**Règle d'or :** Si cela vous embarrasserait sur un projecteur, ne le faites pas.

---

### Menu de pratique rapide (à faire maintenant)
* **Démo de motifs (Concept 1) :** Chargez une photo et listez 3 façons de la représenter numériquement (pixels, "embeddings", cartes de contours).
* **ML en minutes (Concept 2) :** Entraînez un classificateur webcam avec Teachable Machine et testez avec différents objets.
* **Escalade de prompt (Concept 4) :** Écrivez un prompt faible → améliorez-le avec Rôle/Public/Tâche/Contraintes → ajoutez des exemples → ajoutez une grille d'évaluation.
* **Test de RAG (Concept 6) :** Interrogez une IA sur votre propre document avec et sans récupération ; comparez la spécificité et les citations.
* **Contrôle de sécurité (Concept 10) :** Prenez un résultat généré et passez-le à une checklist éthique rapide : transparence ? confidentialité ? droits ? biais nuisible ?

---

### Outils pratiques de votre mémo
Texte/chat (ChatGPT, Claude, Gemini, Copilot, Perplexity), image (DALL·E, Midjourney, OpenArt), musique (Suno, Udio), vidéo (Veo, Kling), 3D (Meshy, Zoo), et Teachable Machine pour des démos rapides — tous dans votre mémo.
