# LibraFlow - Système de Gestion de Bibliothèque

**LibraFlow** est un système de gestion de bibliothèque simple et efficace, développé en langage C. Ce projet permet de gérer un stock de livres en offrant des fonctionnalités telles que l'ajout, la suppression, la recherche, et la mise à jour des informations des livres.

## Fonctionnalités

- **Ajouter un livre** : Ajoutez un nouveau livre au stock avec des informations telles que le titre, l'auteur, le prix, et la quantité.
- **Afficher tous les livres** : Visualisez la liste complète des livres disponibles dans le stock.
- **Rechercher un livre** : Recherchez un livre par son titre.
- **Mettre à jour la quantité** : Modifiez la quantité disponible d'un livre spécifique.
- **Supprimer un livre** : Supprimez un livre du stock.
- **Afficher le nombre total de livres** : Obtenez le nombre total de livres disponibles dans le stock.

## Structure du Projet

Le projet est structuré autour d'une seule source principale (`main.c`) qui contient toutes les fonctions nécessaires pour gérer les livres. Les informations des livres sont stockées dans un tableau de structures.

### Structure de Données

```c
typedef struct {
    char titre[MAX_TITRE];
    char auteur[MAX_AUTEUR];
    float prix;
    int quantite;
} LIVRE;
