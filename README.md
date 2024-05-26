# Plateforme d'Orientation Académique

## Installation et Configuration

Importer le projet dans votre IDE. Ouvrez votre IDE préféré. Importez le projet comme un projet Java existant.

Configurer JavaFX :
- Téléchargez et configurez le SDK JavaFX dans votre IDE.
- Ajoutez le chemin du module JavaFX dans les configurations de votre projet.

Configurer les fichiers JSON :
- Assurez-vous que les fichiers JSON (`Etudiant.json`, `FicheVoeux.json`, `Option.json`, etc.) sont présents dans les emplacements appropriés.
- Les fichiers nécessaires se trouvent dans le répertoire `src/Java`.

Pour lancer l'application, suivez les étapes ci-dessous :

### Exécuter la classe principale :

Localisez la classe `MainApp.java` dans le package `Javafx`. Exécutez cette classe pour démarrer l'application.

```java
src/Javafx/MainApp.java
```
# Naviguer dans l'application

Une fois l'application démarrée, vous serez accueilli par une page de bienvenue. Vous pouvez vous connecter soit en tant qu'étudiant, soit en tant que responsable.

## Pour les Étudiants :

### Connexion Étudiant
Saisissez votre numéro d'étudiant et votre mot de passe pour vous connecter.

### Soumission des Fiches de Vœux
Une fois connecté, vous pouvez consulter les options disponibles et soumettre vos choix de spécialisation.

### Consultation des Résultats
Après la période de soumission et le traitement des données, vous pourrez consulter vos résultats d'affectation.

## Pour les Responsables :

### Connexion Responsable
Saisissez votre identifiant et votre mot de passe pour vous connecter.

### Gestion du Processus d'Orientation
- Activez ou désactivez la période de soumission des fiches de vœux.
- Lancez l'algorithme d'orientation pour traiter les choix des étudiants.
- Consultez les statistiques des résultats pour évaluer le processus.

## Fonctionnalités Clés
- **Interface Intuitive** : Utilisation de JavaFX pour une interface utilisateur fluide et réactive.
- **Gestion des Données avec JSON** : Utilisation de fichiers JSON pour stocker et gérer les données des étudiants, des options et des résultats.
- **Algorithme d'Orientation** : Implémentation de l'algorithme Gale-Shapley pour assurer une répartition équitable des options.
- **Statistiques et Rapports** : Génération de statistiques détaillées pour analyser les résultats de l'orientation.

## Auteurs
- Celine XIAO
- KEM Nathan
- EL BOUZIDI TIALI Fayçal
- HONORE Calista
- NGUYEN Guillaume
