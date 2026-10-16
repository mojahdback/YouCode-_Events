# YouCode Events

> Une plateforme web responsive pour découvrir les événements, consulter leurs détails et faciliter les inscriptions.

## Présentation

**YouCode Events** est un projet de site web dédié à la valorisation et à l'organisation des événements. Son objectif est d'offrir une expérience de navigation claire, moderne et accessible, sur **mobile, tablette et ordinateur**.

Le site permet aux visiteurs de parcourir les événements à venir, de découvrir les intervenants et partenaires, puis d'accéder à un formulaire d'inscription.

## Fonctionnalités principales

### 1. Accueil
- **Section héros** avec un message d'introduction et un bouton d'appel à l'action.
- **Prochains événements** mis en avant pour accéder rapidement à leur présentation.
- **Chiffres clés** pour illustrer l'activité de la plateforme.
- **Catégories d'événements** pour faciliter la découverte des différents thèmes.

### 2. Événements
- Cartes présentant une **image**, un **titre**, une **date**, un **lieu** et une **catégorie**.
- Lien depuis chaque carte vers la page de détail correspondante.
- Grille responsive adaptée à la largeur de l'écran :
  - **Mobile :** une colonne.
  - **Tablette :** deux colonnes.
  - **Ordinateur :** trois colonnes.

### 3. Détail d'un événement
- Présentation de l'événement et de son **programme**.
- Mise en avant des **intervenants**.
- **Informations pratiques** : date, horaire et lieu.
- **Bouton d'inscription** clairement identifiable.

### 4. Intervenants et partenaires
- Affichage des intervenants et partenaires sous forme de cartes ou de grille.
- Pour chaque intervenant : **photo, nom, rôle et courte description**.
- Présentation lisible des partenaires et de leur participation.

### 5. Inscription
Formulaire comprenant les champs suivants :

- Nom et prénom
- Adresse e-mail
- Numéro de téléphone
- Événement sélectionné
- Niveau du participant
- Message complémentaire
- Consentement à l'utilisation des données

**Expérience attendue :** vérification des champs obligatoires, indication visuelle des erreurs à proximité des champs concernés et affichage d'un message de confirmation après validation réussie. Les états d'erreur et de réussite doivent rester compréhensibles sans dépendre uniquement de la couleur.

## Technologies

| Technologie | Utilisation |
| --- | --- |
| **HTML5** | Structure sémantique des pages et formulaires |
| **CSS3** | Mise en page, styles, Flexbox, Grid et responsive design |
| **JavaScript** | Interactions et validation côté client, si intégrées |
| **Git & GitHub** | Versionnement et collaboration en équipe |

## Responsive Web Design

L'interface est pensée pour s'adapter aux différents écrans :

| Support | Organisation des cartes d'événements |
| --- | --- |
| Mobile | 1 colonne |
| Tablette | 2 colonnes |
| Ordinateur | 3 colonnes |

Les mises en page utilisent notamment **Flexbox**, **CSS Grid**, des dimensions flexibles et des **media queries**. Les images et les textes doivent rester lisibles sans défilement horizontal inutile.

## Accessibilité et qualité

- Navigation structurée avec des balises HTML sémantiques.
- Texte alternatif pertinent pour les images informatives.
- Contraste et lisibilité des textes.
- Champs de formulaire associés à des libellés explicites.
- Messages d'erreur visibles et formulés clairement.
- Parcours utilisable au clavier et boutons facilement identifiables.

## Installation et lancement

1. Cloner le dépôt GitHub du projet :

   ```bash
   git clone <URL_DU_DEPOT>
   ```

2. Ouvrir le dossier du projet dans **Visual Studio Code**.
3. Ouvrir la page d'accueil HTML dans un navigateur, ou utiliser l'extension **Live Server**.
4. Tester les différents formats d'écran avec les outils de développement du navigateur (**F12**).

> Remplacer `<URL_DU_DEPOT>` par l'adresse réelle du dépôt.

## Organisation du projet

Le code est organisé autour des pages HTML, des feuilles de style CSS et des ressources visuelles. Par exemple :

```text
YouCode-Events/
├── index.html                 #   Page d'accueil (si nommée ainsi)
├── evenement.html             #   Evenement
├──intervenants.html           #   Intervenants
            
  
                             
├── css/
│   ├── style.css              # Styles principaux
│   └── respon.css             # Adaptations responsive
├── assets/
│   └── icons/                 # Icônes et visuels
└── README.md
```

*Cette arborescence est indicative : adapter les noms et ajouter les autres pages selon les fichiers réellement présents dans le dépôt.*

## Objectifs du projet

- Concevoir une interface cohérente et agréable à utiliser.
- Appliquer les bonnes pratiques **HTML, CSS et responsive design**.
- Structurer les pages et les composants de manière réutilisable.
- Améliorer l'expérience utilisateur, notamment pour le parcours d'inscription.
- Développer la collaboration et la gestion de versions avec **Git/GitHub**.

---

**Projet pédagogique — YouCode Events**  
*Découvrir, partager et participer aux événements.*
