# TP Conception d'une application avec UML - Fromagerie DigiCheese

**Auteur :** Baptiste Rouault  
**Formation :** M1 CYBER-RESSOURCE  
**TP :** Conception d'une application avec UML  

## Description

Ce projet contient les livrables du TP de conception d'application avec UML pour la fromagerie DigiCheese. L'objectif est de modéliser une application de gestion pour une fromagerie en utilisant les différents diagrammes UML.

## Structure du projet

```
fromagerie_digicheese_baptiste_rouault/
├── README.md                    # Ce fichier
├── .gitignore                   # Fichiers ignorés par Git
├── 01_acteurs_roles.md          # Identification des acteurs et rôles
├── 04_scenario_gestion_colis.md  # Scénario de gestion des colis
├── Schéma global d'architecture.png  # Architecture globale
├── imageUML/                    # Images des diagrammes UML
└── puml/                        # Fichiers source PlantUML
    ├── 02_architecture.puml     # Diagramme d'architecture
    ├── 03_use_cases.puml        # Diagramme des cas d'utilisation
    ├── 05_activity.puml         # Diagramme d'activité
    ├── 06_sequence.puml         # Diagramme de séquence
    └── 07_class_diagram.puml    # Diagramme de classes
```

## Diagrammes UML réalisés

1. **Diagramme des acteurs et rôles** - Identification des différents acteurs du système
2. **Diagramme d'architecture** - Vue globale de l'architecture système
3. **Diagramme des cas d'utilisation** - Fonctionnalités principales du système
4. **Diagramme d'activité** - Flux de processus métier
5. **Diagramme de séquence** - Interactions entre les composants
6. **Diagramme de classes** - Structure des données et relations

## Technologies utilisées

- **PlantUML** - Génération des diagrammes UML
- **Markdown** - Documentation
- **Git** - Versioning

## Compilation des diagrammes

Pour générer les diagrammes à partir des fichiers PlantUML :

```bash
# Installation de PlantUML (si nécessaire)
# Utiliser un éditeur supportant PlantUML comme VS Code avec l'extension PlantUML
# Ou utiliser la ligne de commande :
java -jar plantuml.jar puml/*.puml
```

## Auteur

**Baptiste Rouault**  
Étudiant en M1 CYBER-RESSOURCE  
TP de Conception d'une application avec UML
