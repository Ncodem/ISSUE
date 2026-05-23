# Signalement de bugs — Serveur GTA-RP FiveM

Bienvenue sur le dépôt officiel de signalement des bugs de notre serveur GTA-RP sur FiveM.

Ce repository sert à centraliser les retours des bêta-testeurs afin de nous aider à corriger les problèmes, améliorer l'expérience de jeu et préparer une ouverture propre du serveur.

Même si vous ne connaissez pas GitHub, pas de panique : ce guide explique comment signaler correctement un bug.

## Créer un signalement en 3 étapes

1. Ouvrez l'onglet **Issues**.
2. Vérifiez rapidement que le bug n'a pas déjà été signalé.
3. Cliquez sur **New issue** puis remplissez le formulaire **Rapport de bug**.

Une issue est simplement un ticket de signalement.

## Ce que vous pouvez signaler

Vous pouvez ouvrir une issue pour tout comportement anormal pendant la bêta, par exemple :

- bug en jeu ;
- menu qui ne fonctionne pas ;
- problème de job ;
- souci d'inventaire ;
- erreur de traduction ou de texte ;
- problème d'interface ;
- crash ou déconnexion ;
- bug de véhicule ;
- incohérence RP ;
- problème de mapping ;
- baisse de performance, lag ou freeze ;
- comportement étrange constaté en jeu.

## Avant de créer une issue

Merci de vérifier rapidement si le bug existe déjà :

1. cliquez sur l'onglet **Issues** ;
2. regardez les bugs déjà ouverts ;
3. utilisez la barre de recherche si besoin ;
4. si le bug existe déjà, ajoutez un commentaire avec vos détails au lieu de créer une nouvelle issue.

Cela évite les doublons et nous permet de corriger plus efficacement.

## Bien choisir le titre

Le titre doit être clair, court et explicite. Il doit permettre de comprendre rapidement le type de bug et la fonctionnalité concernée.

Format recommandé :

```text
[TYPE] Sujet concerné — description courte du problème
```

Bons exemples :

- `[BUG] Inventaire — impossible d'utiliser un item`
- `[CRASH] Connexion serveur — crash après le chargement du personnage`
- `[AFFICHAGE] Téléphone — menu partiellement invisible`
- `[JOB] Police — impossible d'ouvrir le garage de service`
- `[ARGENT] Banque — retrait d'argent non pris en compte`
- `[VÉHICULE] Garage — véhicule disparu après rangement`
- `[MAPPING] Hôpital — porte bloquée à l'entrée principale`
- `[PERFORMANCE] Centre-ville — grosse chute de FPS`

Titres à éviter :

- `Bug`
- `Ça marche pas`
- `Problème`
- `Aidez-moi`
- `Bug serveur`

Ces titres ne donnent pas assez d'informations et ralentissent le traitement du problème.

## Informations attendues

Le formulaire d'issue vous demandera notamment :

- un résumé du bug ;
- les étapes pour le reproduire ;
- le résultat attendu ;
- le résultat obtenu ;
- la date et l'heure approximatives ;
- le lieu en jeu ;
- le personnage utilisé ;
- le niveau de gravité ;
- des captures d'écran, vidéos, logs ou messages d'erreur si vous en avez.

Plus vous donnez de détails, plus le bug sera facile à reproduire et à corriger.

## Captures d'écran et vidéos

Les captures d'écran sont très utiles, surtout pour :

- un message d'erreur ;
- un menu cassé ;
- une notification étrange ;
- une position bloquée ;
- un item buggué ;
- un véhicule invisible ou mal rangé ;
- un problème de mapping ;
- un comportement anormal visible.

Pour ajouter une image dans GitHub, glissez-la directement dans la zone de texte de l'issue, attendez la fin de l'envoi, puis publiez.

Pour les bugs difficiles à expliquer, une vidéo peut être encore plus utile. Vous pouvez ajouter un lien Discord, YouTube non répertorié, Google Drive ou équivalent.

## Bugs critiques et exploits

Si vous découvrez un bug permettant de dupliquer de l'argent ou des items, de tricher, de contourner l'anti-cheat, d'obtenir des permissions non prévues, de casser l'économie, de provoquer un crash volontaire ou d'exploiter une faille de sécurité, ne détaillez pas publiquement la méthode complète.

Dans ce cas :

1. créez une issue avec un titre vague mais clair, par exemple `[CRITIQUE] Faille économie — duplication possible` ;
2. indiquez simplement que vous avez trouvé une faille critique ;
3. contactez immédiatement le staff en privé sur Discord ;
4. envoyez les détails uniquement à un administrateur ou développeur.

Cela évite que d'autres joueurs utilisent la faille avant correction.

## Bien tester avant de signaler

Quand c'est possible, essayez de vérifier :

- si le bug se reproduit après une reconnexion ;
- si le bug arrive avec un autre personnage ;
- si le bug arrive à d'autres joueurs ;
- si le bug arrive seulement à un endroit précis ;
- si le bug arrive seulement avec un item, un véhicule ou un job précis.

Vous n'êtes pas obligé de tout tester, mais chaque détail supplémentaire peut nous faire gagner beaucoup de temps.

## Types de bugs recommandés

| Type | Utilisation |
| --- | --- |
| `[BUG]` | Bug général |
| `[CRASH]` | Crash du jeu ou déconnexion |
| `[AFFICHAGE]` | Problème visuel ou interface |
| `[JOB]` | Problème lié à un métier |
| `[INVENTAIRE]` | Problème d'items ou inventaire |
| `[ARGENT]` | Problème banque, cash, salaire, société |
| `[VÉHICULE]` | Problème véhicule, garage, fourrière |
| `[MAPPING]` | Problème de map, porte, collision, intérieur |
| `[PERFORMANCE]` | FPS, lag, freeze |
| `[AUDIO]` | Voix, radio, son, distance vocale |
| `[RP]` | Incohérence ou problème impactant le roleplay |
| `[CRITIQUE]` | Faille grave, duplication, sécurité |

## Gravité du bug

| Gravité | Signification |
| --- | --- |
| Mineur | Gênant mais pas bloquant |
| Moyen | Perturbe le gameplay |
| Important | Bloque une fonctionnalité |
| Critique | Crash, perte d'argent, duplication ou faille importante |

## Statuts possibles

Selon l'avancement, une issue pourra recevoir différents labels :

| Label | Signification |
| --- | --- |
| `à vérifier` | Le bug doit être confirmé |
| `confirmé` | Le bug est confirmé |
| `en cours` | Correction en cours |
| `corrigé` | Correction effectuée |
| `besoin d'informations` | Il manque des détails |
| `doublon` | Bug déjà signalé |
| `critique` | Bug prioritaire |
| `non reproductible` | Le bug n'a pas pu être reproduit |

## Exemples de signalements bien faits

### Exemple 1 — Bug inventaire

Titre :

```text
[BUG] Inventaire — impossible d'utiliser une bouteille d'eau
```

Résumé :

> Quand j'essaie d'utiliser une bouteille d'eau depuis mon inventaire, rien ne se passe.

Étapes :

1. Ouvrir l'inventaire.
2. Cliquer sur une bouteille d'eau.
3. Cliquer sur **Utiliser**.

Résultat attendu :

> Le personnage devrait boire et la soif devrait augmenter.

Résultat obtenu :

> Aucune animation ne se lance et la soif ne change pas.

### Exemple 2 — Bug véhicule

Titre :

```text
[VÉHICULE] Garage — véhicule disparu après rangement
```

Résumé :

> J'ai rangé mon véhicule dans le garage central, mais il n'apparaît plus dans la liste.

Étapes :

1. Sortir un véhicule du garage central.
2. Rouler quelques minutes.
3. Revenir au garage.
4. Ranger le véhicule.
5. Rouvrir le garage.

Résultat attendu :

> Le véhicule devrait apparaître dans la liste des véhicules stockés.

Résultat obtenu :

> Le véhicule n'apparaît plus.

### Exemple 3 — Performance

Titre :

```text
[PERFORMANCE] Centre-ville — grosse chute de FPS près de la banque
```

Résumé :

> J'ai une grosse chute de FPS quand je passe devant la banque centrale.

Étapes :

1. Aller devant la banque centrale.
2. Regarder vers la place principale.
3. Avancer vers le parking.

Résultat attendu :

> Le jeu devrait rester fluide.

Résultat obtenu :

> Les FPS chutent fortement pendant quelques secondes.

## Checklist avant publication

Avant de publier, vérifiez que votre signalement répond autant que possible à ces questions :

- Qu'est-ce qui ne fonctionne pas ?
- Où le bug s'est-il produit ?
- Quand le bug s'est-il produit ?
- Comment peut-on reproduire le bug ?
- Qu'est-ce qui aurait dû se passer ?
- Qu'est-ce qui s'est réellement passé ?
- Est-ce arrivé une seule fois ou plusieurs fois ?
- Avez-vous une capture d'écran ou une vidéo ?
- Le bug concerne-t-il un job, un item, un véhicule ou une zone précise ?
- Le bug bloque-t-il votre progression ?

## Ce qu'il ne faut pas faire

Merci d'éviter :

- les titres vagues comme `bug` ou `ça marche pas` ;
- les messages sans détail ;
- les doublons ;
- les insultes ou messages agressifs ;
- les accusations sans preuve ;
- les signalements de triche sans élément concret ;
- la publication publique d'une faille exploitable ;
- les captures contenant des informations personnelles.

## Suivre votre issue

Une fois votre issue créée, le staff pourra :

- vous poser des questions ;
- ajouter un label ;
- confirmer le bug ;
- fermer l'issue si le bug est corrigé ;
- fermer l'issue si le bug est déjà signalé ailleurs ;
- demander une capture ou une vidéo supplémentaire.

Merci de surveiller les réponses sur votre issue. Si un membre du staff demande une précision, répondez directement en commentaire.

## Merci aux bêta-testeurs

Chaque bug signalé correctement nous aide énormément.

Votre rôle est important pour construire un serveur plus stable, plus propre et plus agréable pour tout le monde.

Merci de prendre le temps de tester, de signaler les problèmes et de nous aider à améliorer le serveur.

Bon test à tous, et bon RP !
