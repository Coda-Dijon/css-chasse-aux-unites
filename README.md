# La chasse aux unités

**20 minutes — En binôme**

## Consignes

Remplacer les tailles fixes (`px`) par des unités relatives et observer
comment la page réagit quand on redimensionne la fenêtre ou qu'on zoome.

| # | Consigne                                                        | Unité à utiliser |
|---|-----------------------------------------------------------------|------------------|
| 1 | Remplacer la taille de police du `<body>` (16 px) par **1 rem** | `rem`            |
| 2 | Remplacer la largeur du conteneur (800 px) par **100 %**        | `%`              |
| 3 | Remplacer la marge du conteneur (40 px) par **2 rem**           | `rem`            |
| 4 | Remplacer la taille du titre (32 px) par **2 rem**              | `rem`            |
| 5 | Donner au conteneur une largeur de **90 vw** et observer        | `vw`             |
| 6 | Remplacer la largeur du conteneur par **`min(90%, 60rem)`**     | `min()`          |

## Bilan

Testez chaque modification en :

- Redimensionnant la fenêtre du navigateur
- Utilisant le zoom du navigateur (Ctrl + / Ctrl −)

**Questions à se poser :**

- Quelle unité suit la taille de police de référence ?
- Quelle unité suit la largeur du parent ?
- Quelle unité suit la largeur de la fenêtre ?
- Pourquoi `rem` est-il préférable à `px` pour l'accessibilité ?
