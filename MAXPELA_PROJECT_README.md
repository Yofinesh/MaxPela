# MAXPELA --- PROJECT KNOWLEDGE & DEVELOPMENT README

> README de référence pour Codex/IA travaillant sur le site web, la
> roadmap, les devblogs, le lore, les actualités et la communication
> publique de MaxPela.

## 1. Règle principale

**Lire ce README avant toute modification importante du site.**

Avant de coder : 1. Lire ce README. 2. Lire `AGENTS.md` s'il existe. 3.
Inspecter la structure réelle du site. 4. Inspecter les composants,
pages, routes, styles, assets et systèmes de contenu existants. 5.
Chercher une implémentation existante avant d'en créer une nouvelle.

### Règles absolues

-   **Tout ce qui n'est pas explicitement demandé est HORS PÉRIMÈTRE.**
-   Ne pas supprimer du travail fonctionnel.
-   Ne pas réécrire toute l'architecture pour une petite modification.
-   Ne pas remplacer un fichier entier si une modification ciblée
    suffit.
-   Ne pas inventer de lore, de fonctionnalités, de dates, de versions
    ou de chiffres.
-   Ne pas casser les routes, liens, SEO, responsive ou contenus
    existants.
-   Si une modification hors périmètre devient nécessaire : **STOP et
    demander l'autorisation.**
-   Ne jamais prétendre qu'un test a été effectué s'il ne l'a pas été.

------------------------------------------------------------------------

# 2. Identité du projet

**MaxPela** est une aventure Minecraft originale centrée sur :

-   ⚔️ Action / combat
-   🗺️ Exploration
-   🧩 Énigmes
-   🏰 Donjons
-   📖 Narration
-   🌍 Monde ouvert
-   🔥 Ancienne légende
-   🖤 Mystères

Le projet doit donner une impression de jeu d'aventure complet,
mystérieux, premium et vivant.

Contexte technique actuel du jeu :

-   Minecraft Java Edition 26.3
-   Fabric
-   Java 25
-   Mod ID : `maxpela`
-   Package : `fr.maxpela.maxpela`

Le site est la vitrine officielle du projet. Il ne doit jamais présenter
une fonctionnalité comme sortie simplement parce qu'elle existe dans le
code de développement.

------------------------------------------------------------------------

# 3. Statuts à utiliser

Toujours distinguer :

-   **Terminé / Released** : réellement disponible.
-   **En développement / WIP** : actuellement développé.
-   **En préparation** : prévu et préparé.
-   **À venir / Planned** : prévu pour plus tard.
-   **Concept / Proposed** : idée, pas une fonctionnalité confirmée.
-   **Inconnu / Unknown** : information non établie.

Ne jamais transformer un concept en information officielle.

------------------------------------------------------------------------

# 4. Lore canonique connu

## Astralys

Astralys est le village natal du joueur et le point de départ de
l'aventure.

Le joueur commence dans une maison chaleureuse, puis découvre le village
et le monde autour de lui.

Astralys doit donner une impression de **chez-soi avant le début de
l'aventure**.

Un ancien bibliothécaire, **Aldren**, est lié au début de la découverte
de la légende et remet au joueur un livre lié à celle-ci.

## L'ancienne légende

Une ancienne légende raconte l'existence d'un héros capable de réunir
les fragments nécessaires pour ouvrir un mystérieux portail vers le
Nether.

Des héros du passé auraient enfermé une menace extrêmement dangereuse
dans cet autre monde.

Les fragments nécessaires à la réouverture du portail furent séparés et
cachés.

Des donjons anciens furent construits ou protégés par des gardiens liés
à ces héros.

La première version prévoit six donjons, dans un ordre établi. Chaque
donjon abrite une Pierre d'Obsidienne : six donjons, six pierres. Les
lieux sont la Vieille Tour, la Jungle, la Mangrove, le Désert, la
Montagne du Nord Gelé et les Caves.
La plupart des habitants pensent que tout cela n'est qu'une légende.

Certains chercheurs continuent toutefois à chercher la vérité.

Des traces semblent indiquer que le passé n'est peut-être pas aussi mort
qu'on le pensait.

Le joueur découvre progressivement qu'il pourrait être le héros annoncé
par la légende.

## Nether

Le Nether est considéré au départ comme une légende mystérieuse.

La vérité connue est qu'une menace dangereuse y a été enfermée par les
héros du passé.

Le portail a été fermé et les fragments nécessaires à sa réouverture ont
été séparés et cachés.

La première campagne conduit progressivement vers cette histoire.

Question centrale :

> **Pourquoi ce portail avait-il réellement été fermé ?**

Ne pas révéler une réponse qui n'est pas officiellement établie.

------------------------------------------------------------------------

# 5. Donjons

La première version prévoit **6 donjons**, dans l'ordre suivant :

1. **La Vieille Tour**
2. **Le donjon de la Jungle**
3. **Le donjon de la Mangrove**
4. **Le donjon du Désert**
5. **Le donjon de la Montagne du Nord Gelé**
6. **Les Caves**

Ces six lieux constituent les étapes de donjon prévues pour la première
version. Leurs noms et leur ordre sont établis ; les détails de leur
histoire, de leurs épreuves et de leurs récompenses restent à préciser
lorsqu'ils ne sont pas documentés ailleurs dans cette bible.

------------------------------------------------------------------------

# 6. Monde et régions

Régions connues :

-   Terres Sauvages
-   Montagnes du Nord
-   Plaine du Levant
-   Vallée Oubliée
-   Marais de l'Est
-   Collines Dorées
-   Désert des Vents
-   Jungle Perdue

Une région peut avoir : - identité visuelle ; - histoire locale ; -
habitants ; - secrets ; - lieux importants ; - chemins ; - points de
repère.

Le joueur peut apercevoir des lieux avant de pouvoir les atteindre.

Les objets obtenus dans les donjons permettent progressivement
d'explorer davantage le monde.

------------------------------------------------------------------------

# 7. Progression

Systèmes connus :

-   💰 Argent
-   📜 Quêtes
-   🗺️ Progression d'aventure
-   ⭐ XP
-   📈 Niveaux
-   ✨ Points de compétence
-   ⚔️ Compétences
-   🏰 Donjons
-   🪨 Pierres d'Obsidienne
-   🧰 Objets de progression

Ne pas inventer de valeurs numériques non confirmées.

------------------------------------------------------------------------

# 8. Compétences

Branches connues :

### ⚔️ Guerrier

-   Force I
-   Peau de fer
-   Rage du guerrier

### 🏹 Archer

-   Œil du chasseur
-   Agilité
-   Concentration

### 🧭 Explorateur

-   Pas légers
-   Souffle infini
-   Élan de l'aventurier

Les coûts et prérequis sont définis dans l'implémentation du jeu.

Le site doit refléter l'implémentation réelle, pas une ancienne version
de documentation.

------------------------------------------------------------------------

# 9. Site officiel

Le site doit être la maison officielle de MaxPela.

Il doit permettre de :

1.  présenter le projet ;
2.  présenter l'aventure ;
3.  présenter le lore ;
4.  présenter les nouveautés ;
5.  suivre le développement ;
6.  suivre la roadmap ;
7.  consulter les médias ;
8.  rejoindre la communauté ;
9.  expliquer comment jouer lorsqu'une version est disponible.

Navigation connue :

-   L'aventure
-   Lore
-   Jouer
-   Actualités
-   Médias
-   Communauté
-   Discord
-   JOUER

**Toujours vérifier les routes réellement présentes avant de modifier la
navigation.**

------------------------------------------------------------------------

# 10. Direction artistique du site

Style recherché :

-   dark fantasy ;
-   aventure médiévale ;
-   cinématique ;
-   mystérieux ;
-   ancien ;
-   parchemin ;
-   pierre ;
-   bois sombre ;
-   or ancien ;
-   bleu profond ;
-   tons naturels ;
-   ambiance premium.

Le site doit rappeler :

-   Astralys ;
-   ruines anciennes ;
-   donjons ;
-   légende ;
-   Pierres d'Obsidienne ;
-   exploration ;
-   Nether ;
-   mystère.

Éviter :

-   esthétique SaaS générique ;
-   néons excessifs ;
-   design enfantin ;
-   mélange de styles incohérents ;
-   images génériques sans rapport avec MaxPela.

------------------------------------------------------------------------

# 11. Roadmap

La roadmap indique la direction générale du projet.

Elle ne doit pas promettre de dates non confirmées.

## Fondations

-   Vision du projet
-   Bible du projet
-   Lore principal
-   Chronologie

## Monde

-   Carte globale
-   WorldPainter
-   Astralys
-   Régions

## Contenu

-   Les six donjons, voir la liste du chapitre 5

## Systèmes

-   Système de quêtes
-   Système de sauvegarde
-   Combat amélioré
-   Carte complète
-   Cinématiques

## Tests

-   Test interne
-   Alpha
-   Beta
-   Early Access

## Après sortie

-   Mises à jour
-   Nouveau contenu
-   Chapitre 2

### Statuts recommandés

-   🟢 Terminé
-   🔵 En cours
-   🟡 En préparation
-   ⚪ À venir
-   🔴 Bloqué

Ne jamais inventer une date de sortie.

Avant de changer un statut, vérifier le code, la documentation ou
l'instruction explicite du propriétaire.

------------------------------------------------------------------------

# 12. Devblog

Le devblog est essentiel pour donner l'impression que MaxPela est
vivant.

Chaque devblog doit raconter une vraie étape du développement.

Format recommandé :

# DEVLOG #\[NUMÉRO\] --- \[TITRE\]

Introduction courte.

## 🏗️ Construction

Ce qui a été construit ou modifié.

## ⚙️ Développement

Systèmes ou travail technique réellement réalisé.

## 📖 Histoire

Travail narratif/lore si pertinent.

## 🧪 Tests

Tests réellement effectués.

## 🎯 Prochaine étape

Travail prévu ensuite, clairement présenté comme prévu.

## 📸 Aperçu

Image, vidéo ou capture.

### Règles

Un devblog doit répondre à :

-   Qu'est-ce qui a changé ?
-   Pourquoi est-ce important ?
-   Qu'est-ce que cela apporte à MaxPela ?
-   Quelle est la prochaine étape ?

Ne jamais inventer : - progression ; - fonctionnalité ; - capture ; -
date ; - version ; - résultat de test.

------------------------------------------------------------------------

# 13. Gestion des devblogs

Lorsqu'un nouveau devblog est demandé :

1.  Inspecter les devblogs existants.
2.  Trouver le prochain numéro.
3.  Respecter la structure existante.
4.  Respecter les URLs/slugs existants.
5.  Utiliser le système de contenu déjà présent.
6.  Ajouter l'article à l'index/archive.
7.  Vérifier le responsive.
8.  Vérifier les liens.
9.  Ne pas casser les anciens articles.

Si le numéro ou la structure est ambiguë : demander au propriétaire.

------------------------------------------------------------------------

# 14. Actualités

Utiliser les actualités pour :

-   grandes annonces ;
-   sorties ;
-   grandes étapes ;
-   ouvertures de tests ;
-   informations importantes.

Utiliser les devblogs pour le développement quotidien et les coulisses.

Ne pas mélanger les deux inutilement.

------------------------------------------------------------------------

# 15. Teasers

Les teasers peuvent être mystérieux.

Ils peuvent montrer :

-   une image ;
-   un symbole ;
-   une zone ;
-   un objet ;
-   une phrase ;
-   un détail.

Ils ne doivent pas créer accidentellement de nouveau canon.

------------------------------------------------------------------------

# 16. Médias

Le site peut présenter :

-   screenshots ;
-   trailers ;
-   teasers ;
-   vidéos ;
-   captures de développement ;
-   concepts ;
-   présentations de donjons.

Une image conceptuelle générée ne doit pas être présentée comme une
capture du jeu final sans confirmation.

Toujours respecter les assets réellement présents dans le projet.

------------------------------------------------------------------------

# 17. Discord / communauté

Discord officiel :

https://discord.gg/DdwspU7JdT

La communauté publique peut contenir :

-   annonces ;
-   devblogs ;
-   roadmap ;
-   lore ;
-   mystères et théories ;
-   screenshots ;
-   fan art ;
-   suggestions ;
-   bugs ;
-   tests.

Les informations internes ne doivent jamais être publiées
automatiquement.

------------------------------------------------------------------------

# 18. Confidentialité

Ne jamais publier :

-   mots de passe ;
-   tokens ;
-   clés API ;
-   identifiants ;
-   informations personnelles ;
-   documents confidentiels ;
-   secrets internes ;
-   contenu non public.

Si un fichier ou contenu semble interne :

**ne pas le publier ; demander confirmation.**

------------------------------------------------------------------------

# 19. Source de vérité

Ordre de priorité :

1.  Instruction explicite du propriétaire.
2.  Implémentation actuelle du projet.
3.  Documentation officielle actuelle.
4.  Contenu officiel publié du site.
5.  Contenu officiel publié du Discord.
6.  Devblogs existants.
7.  Roadmap.
8.  Concepts / propositions.
9.  Hypothèses de l'IA.

En cas de conflit important : ne pas inventer de solution. Signaler le
conflit et demander.

------------------------------------------------------------------------

# 20. Workflow de développement web

Pour chaque tâche importante :

### Étape 1 --- Comprendre

Identifier précisément la demande.

### Étape 2 --- Inspecter

Lire ce README, `AGENTS.md` et les fichiers concernés.

### Étape 3 --- Chercher l'existant

Réutiliser les composants, données, styles et systèmes déjà présents.

### Étape 4 --- Planifier

Choisir le minimum de fichiers nécessaires.

### Étape 5 --- Implémenter

Faire des modifications ciblées.

### Étape 6 --- Tester

Utiliser les commandes de validation/build du projet.

### Étape 7 --- Vérifier

Tester notamment : - desktop ; - mobile ; - navigation ; - liens ; -
images ; - textes ; - responsive ; - SEO si concerné ; - accessibilité
si concernée.

### Étape 8 --- Rapporter

Donner : - fichiers modifiés ; - contenu ajouté ; - fonctionnalités
modifiées ; - tests effectués ; - problèmes restants.

------------------------------------------------------------------------

# 21. Architecture de contenu

Avant de créer un nouveau système de contenu :

-   inspecter l'architecture existante ;
-   identifier si le site utilise Markdown, MDX, JSON, CMS, base de
    données ou autre ;
-   réutiliser le système existant.

Ne pas créer plusieurs systèmes concurrents pour les devblogs,
actualités, roadmap ou lore.

Ne pas migrer l'architecture sans demande explicite.

------------------------------------------------------------------------

# 22. SEO

Préserver et améliorer progressivement :

-   titres de pages ;
-   descriptions ;
-   Open Graph ;
-   images de partage ;
-   URLs propres ;
-   headings ;
-   alt text ;
-   canonical si utilisé.

Ne jamais inventer des informations SEO.

------------------------------------------------------------------------

# 23. Performance

Les visuels doivent rester premium sans dégrader le site.

Avant d'ajouter un asset lourd :

-   vérifier ses dimensions ;
-   optimiser si nécessaire ;
-   éviter les doublons ;
-   utiliser des tailles adaptées ;
-   conserver le responsive.

Les animations doivent servir l'ambiance.

------------------------------------------------------------------------

# 24. Mobile

Toujours vérifier les modifications importantes sur mobile.

Contrôler :

-   navigation ;
-   hero ;
-   cartes ;
-   images ;
-   boutons ;
-   devblogs ;
-   roadmap ;
-   lore ;
-   médias ;
-   footer.

------------------------------------------------------------------------

# 25. Si le propriétaire demande un nouveau devblog

L'IA doit :

1.  vérifier la progression réelle du projet ;
2.  lire les anciens devblogs ;
3.  conserver le ton ;
4.  déterminer le prochain numéro ;
5.  écrire uniquement ce qui est réellement connu ;
6.  distinguer travail terminé et travail prévu ;
7.  intégrer le contenu avec le système existant ;
8.  mettre à jour l'archive ;
9.  vérifier la page.

------------------------------------------------------------------------

# 26. Si le propriétaire demande une roadmap

L'IA doit :

1.  lire la roadmap actuelle ;
2.  identifier exactement les éléments demandés ;
3.  modifier uniquement ces statuts ;
4.  ne pas inventer de dates ;
5.  ne pas déplacer les tâches non concernées ;
6.  préserver la structure ;
7.  tester le rendu.

------------------------------------------------------------------------

# 27. Si le propriétaire demande du lore

Le lore doit être traité comme du contenu sensible.

Avant publication :

-   vérifier si c'est canon ;
-   vérifier les sources existantes ;
-   distinguer canon, théorie et proposition ;
-   respecter les spoilers ;
-   ne jamais transformer une théorie en vérité officielle.

------------------------------------------------------------------------

# 28. Philosophie éditoriale

Le site doit transmettre l'idée :

> **Une aventure commence, et quelque chose d'ancien attend au-delà de
> l'horizon.**

Le visiteur doit ressentir :

-   curiosité ;
-   exploration ;
-   mystère ;
-   anticipation ;
-   découverte.

Le site ne doit pas tout révéler.

Il doit donner envie de découvrir MaxPela.

------------------------------------------------------------------------

# 29. Résumé rapide pour une nouvelle session IA

**Projet :** MaxPela\
**Type :** aventure Minecraft originale\
**Style :** fantasy médiévale / aventure / mystère\
**Village de départ :** Astralys\
**Mystère central :** ancienne légende + menace scellée dans le Nether\
**Progression :** exploration → donjons → Pierres d'Obsidienne → mystère
du portail\
**Première campagne :** environ 5 heures visées\
**Première version :** 6 donjons\
**Gameplay :** combat, énigmes, exploration, donjons, narration\
**Site :** vitrine officielle + actualités + devblogs + roadmap + lore +
médias + communauté\
**Discord :** https://discord.gg/DdwspU7JdT\
**Règle fondamentale :** préserver l'existant et demander avant toute
modification hors périmètre.

------------------------------------------------------------------------

# 30. Maintenance du README

Ce fichier doit évoluer avec MaxPela.

Quand une information importante change :

-   mettre à jour ce README ;
-   supprimer les informations devenues fausses ;
-   distinguer l'état actuel des plans futurs ;
-   éviter les contradictions avec le code et le site.

Le README documente le projet. Il ne donne pas automatiquement
l'autorisation de modifier le projet.

------------------------------------------------------------------------

# 31. RÈGLE FINALE

> **NE CASSE PAS LE TRAVAIL EXISTANT.**

Comprendre avant de modifier.

Modifier uniquement ce qui est demandé.

Tester après modification.

Rapporter précisément ce qui a été fait.

En cas de doute :

> **STOP --- DEMANDE AU PROPRIÉTAIRE.**







