<div align="center">

# PROJET Le Temps C’EST de l’Argent

Une initiative de programmation visant à construire un programme expérimental avec un algorithme unique appelé AVC (Automatisation/Valorisation/Monnaie).

---
</div>

## L’IDÉE

L’idée est de créer un actif qui indique exactement où il atteindra son sommet, quand il s’effondrera et combien de fois il atteindra un sommet historique. Cela permet aux investisseurs de savoir **exactement** quand investir, combien de temps conserver l’actif et quand vendre, avec un **risque minimal**. Cet actif est valorisé automatiquement grâce à un algorithme qui utilise **le temps** pour augmenter la valeur par paliers, avec **le bitcoin comme référence**.

Actuellement, **tous les actifs échangeables** dans le monde sont valorisés selon le **sentiment du marché ou les conditions économiques**. Nous passons nos journées à analyser des graphiques et à espérer le meilleur.

Avec l’**AVC**, l’actif (**Tokenmobiles**) sera **auto-valorisé**, une **première mondiale**.

Pour mener ce projet à bien, des **programmeurs expérimentés** sont nécessaires pour développer **leur propre version du programme**. (**Au moins 100 versions différentes** sont requises pour un lancement sécurisé et durable).

Une fois lancé le **JOUR D’IGNITION**, le programme **devra fonctionner sans interruption pendant plus de 200 ans** et **NE POURRA JAMAIS ÊTRE ARRÊTÉ**.

Le programme doit fonctionner comme **l’heure mondiale**, avec **plusieurs versions** fonctionnant sur **différents serveurs et appareils**, suivant **le même modèle et le même algorithme**.

Avant de commencer à développer leur propre version, les programmeurs devront comprendre les **caractéristiques fondamentales** de l’actif et de l’algorithme **AVC**.

-
-
-
-

## L’ACTIF

**100 smart contracts standards** de **tokens fongibles** ont été déployés sur la **blockchain Stacks**.

Chaque smart contract contient **1 Tokenmobile unique** avec une offre variant entre **200 et 50 000** unités.

En tout, **999 999 Tokenmobiles** ont été créés.

Chaque **Tokenmobile unique** possède **des attributs et métadonnées** essentiels au fonctionnement de l’algorithme **AVC**.

![](/media/asset.png)

**TYPE** - L’identifiant du Tokenmobile en morse.  

**OFFRE** - 1 token issu de l’offre fixe définie dans le smart contract.  

**CYCLES** - Le nombre de fois où le Tokenmobile **s’effondrera en valeur, redémarrera et rebondira**.  

**BOOST** - Le pourcentage d’augmentation de la durée du cycle à chaque redémarrage, augmentant ainsi son pic de valeur.  

**DÉBUT** - La durée du premier cycle.  

**MAX** - La durée du dernier cycle.  

**AVC** - L’algorithme/moteur qui valorise chaque Tokenmobile.  

-
-
-
-

## L’ALGORITHME

• **A** pour **Automatisation**. L’automatisation est basée sur **le temps**, chaque intervalle étant de **60 secondes**.  

• **V** pour **Valorisation**. La valorisation augmente par **paliers de ₿0.00001 ou ₿0.00003**.  

• **C** pour **Monnaie**. La monnaie utilisée comme référence est le **₿itcoin**.  

Un **Tokenmobile** verra donc sa valeur augmenter de **₿0.00001 ou ₿0.00003 toutes les 60 secondes**.

-
-
-
-

## LE PROGRAMME

![](/media/program.jpg)

Voici une **démo du programme** exécutant l’**algorithme AVC**.  
[VOIR LA DÉMO](https://drive.google.com/file/d/10M1PcLHT_r6kEz8bumL3yzdjFDoLvsWI/view?usp=drivesdk)

Vous voyez ici **2 RACKS**, chacun contenant **1 Tokenmobile** en cours de valorisation via AVC. (**Le programme officiel comportera 100 RACKS**).

1. **Adresse du smart contract** de l’actif en cours de valorisation.  
2. **Compteur en temps réel**, formaté en **AA/DDD/HH/MM/SS** (*Remarque : les jours sont comptés sur 365 jours. Pas d’années bissextiles, de semaines ou de mois*).  
3. **Horodatage** indiquant quand le cycle actuel prendra fin et le compteur redémarrera. (*Les horodatages de chaque Tokenmobile sont fournis dans le fichier FUNDAMENTALS*).  
4. **Nombre total de CYCLES**, qui diminue à chaque réinitialisation du compteur. (*Le premier cycle doit diminuer immédiatement après le démarrage de l’AVC d’un Tokenmobile, et non après sa fin*).  
5. **Le BOOST**.  
6. **L’OFFRE**.  

*(Boost et offre sont affichés uniquement dans l’interface utilisateur. Aucune action en code.)*

7. **L’AVC/valeur du Tokenmobile**, qui augmente de **₿0.00001 ou ₿0.00003 toutes les 60 secondes**.  
   La valeur est réinitialisée à **₿0.00000** à chaque **nouveau cycle**. (*À la fin du dernier cycle, la valeur reste figée à son maximum*).

Le programme officiel, prêt pour le **JOUR D’IGNITION**, devra contenir **100 RACKS** pour chacun des **100 smart contracts de Tokenmobiles**, démarrant **simultanément** et tournant **jusqu’à la fin de leur cycle de valorisation**.

Le **Tokenmobiles-100** sera le premier à atteindre la fin après **60 jours**, avec une **valeur maximale de ₿0.86400**, tandis que **Tokenmobiles-43** sera le dernier à atteindre la fin après **plus de 200 ans**, avec une **valeur maximale de ₿338.93753**.

Le programme nécessitera également **Une infrastructure backend**,  **Une interface frontend** affichant les mises à jour **en temps réel sans aucun délai**,  **Une solution d’hébergement** assurant **99,99 % de disponibilité pendant plus de 200 ans**.

-
-
-
-

## LE CODE

Il **n’existe aucun modèle ou code open source** pour le programme AVC. La démo actuelle est une simple démonstration visuelle en terminal.

Chaque programmeur devra coder **sa propre version à partir de zéro**, en choisissant ses propres outils, son propre serveur et son propre hébergement, en se basant sur les **données fondamentales** fournies.

L’objectif est d’**éviter les duplications** et d’empêcher que plusieurs versions aient les mêmes bogues.  
Il doit exister **plusieurs codes différents** exécutant le même programme, afin d’assurer **durabilité et sécurité**.

-
-
-
-

## L’ENVIRONNEMENT

L’initiative **Le Temps C’EST de l’Argent** sera active sur **GitHub et Discord**, permettant aux programmeurs de collaborer, discuter et partager leurs avancées.

Dès qu’un programmeur développe et partage **un test fonctionnel**, il recevra la **date du JOUR D’IGNITION** pour exécuter officiellement son programme, ainsi qu’un **lot d’actifs** (*l’équivalent de 10 ans du premier cycle de Tokenmobiles*).

-
-
-
-

## L’ACCOMPLISSEMENT

Si **plus de 100 versions du programme** sont mises en ligne le **JOUR D’IGNITION**, qu’elles soient **publiques ou privées**, **l’actif et le programme auront une reconnaissance immédiate**.

Comparé aux **actions, métaux, cryptos, ETF, etc.**, ce sera **le seul actif auto-valorisé au monde**.
