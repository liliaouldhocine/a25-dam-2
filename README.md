# **Objectif du projet**

Vous devez développer une application mobile simple avec Flutter et Dart. L'application doit être fonctionnelle, proprement structurée selon l'architecture MVVM et versionnée sur GitHub.

## **Exigences techniques**

### 1. Application Flutter

- Application mobile fonctionnelle (Android/iOS)
- Code en Dart avec **architecture MVVM obligatoire**
- Interface utilisateur intuitive
- Utilisation d'au moins un package pub.dev (hors packages Flutter standards)

### 2. Architecture MVVM requise

Vous devez implémenter le pattern Model-View-ViewModel avec :

- **Models** : Classes de données
- **Views** : Widgets UI (Stateless/Stateful)
- **ViewModels** : Gestion de l'état et logique métier
- Séparation claire des responsabilités
- Communication View ↔ ViewModel via des streams, ChangeNotifier ou StateNotifier

## **Consignes de remise**

### 1. Repository GitHub

- Créez un repository **public** sur GitHub
- Nommez-le de façon descriptive (ex: `flutter-mvvm-calculator`)
- **Invitez-moi comme collaborateur** : mon username GitHub est **liliaouldhocine**

### 2. Structure du repository avec MVVM

```txt
votre-repo/
├── lib/
│   ├── models/          # Classes Model
│   ├── viewmodels/      # Classes ViewModel
│   ├── views/           # Écrans et widgets
│   ├── services/        # Services externes (API, storage)
│   ├── utils/           # Utilities, constants
│   └── main.dart
├── assets/
├── test/
│   ├── viewmodels_test/ # Tests des ViewModels
│   └── ...
├── pubspec.yaml
├── README.md            # Documentation (OBLIGATOIRE)
└── ...
```

### 3. README.md obligatoire

Le fichier README à la racine doit contenir :

**a. En-tête du projet**

- Nom de l'application
- Capture d'écran ou GIF de l'application

**b. Description**

- À quoi sert l'application ?
- Fonctionnalités principales
- Public cible

**c. Architecture MVVM**

- Diagramme ou explication de votre architecture
- Rôle de chaque dossier (models, viewmodels, views)
- Communication entre les composants

**d. Installation et lancement**

```bash
flutter pub get
flutter run
```

**e. Fonctionnement**

- Comment utiliser l'application ?
- Navigation entre les écrans
- Fonctionnalités clés

**f. Équipe**

- Noms complets des membres du groupe
- Rôles/répartition des tâches
- Email universitaire / CEGEP / Personnel

**g. Technologies utilisées**

- Packages Flutter utilisés
- Versions (Flutter, Dart)
- Packages pour MVVM (provider, riverpod, flutter_bloc, etc.)

**h. Défis et solutions** (optionnel)

- Difficultés rencontrées
- Solutions apportées

## **Critères d'évaluation**

1. **Fonctionnalité** (30%) : L'application fonctionne sans erreur
2. **Architecture MVVM** (30%) : Respect du pattern, séparation des concerns
3. **Code qualité** (20%) : Lisibilité, commentaires, structure
4. **Interface utilisateur** (10%) : Design, ergonomie
5. **Documentation** (10%) : README complet et instructions claires

## **Packages recommandés pour MVVM**

- `provider` : Pour la gestion d'état simple
- `riverpod` : Alternative moderne à Provider
- `flutter_bloc` : Pour une approche BLoC
- `get_it` : Pour l'injection de dépendances

## **Dates importantes**

- Début du projet : [date]
- Remise sur GitHub : [date et heure]
- Présentation/démonstration : [date]

## **Support**

- Questions techniques : [préciser le canal de communication]
- Problèmes GitHub : contacter l'enseignant directement

## **Important**

- Le code doit être votre propre travail
- Citez vos sources si vous utilisez du code externe
- Les commits réguliers sur GitHub sont recommandés
- Testez votre application sur émulateur et si possible sur device physique
- **L'architecture MVVM doit être strictement respectée**

---

**Rappel** : L'invitation GitHub vers `liliaouldhocine` est obligatoire pour que je puisse évaluer votre projet. Sans invitation, le projet ne sera pas considéré comme remis.

Bon travail à tous.
