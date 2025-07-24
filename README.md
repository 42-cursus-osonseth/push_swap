🧮 push_swap

Trier une pile d'entiers avec un set d'instructions limité, de la logique et beaucoup d'optimisations.

---

## 🎯 Objectif

Implémenter un programme en C qui trie une pile de nombres entiers en utilisant un **nombre minimum d’opérations**, via un algorithme personnalisé basé sur des **opérations de piles** (`swap`, `push`, `rotate`, etc.).

---

## 📦 Contenu

- Un programme nommé `push_swap` qui prend en **paramètres des entiers à trier**.
- Une **pile A** contenant les valeurs au départ, à trier.
- Une **pile B** utilisée temporairement comme zone de travail.
- Le programme affiche sur la sortie standard la **liste minimale d’instructions** nécessaires au tri.

---

## ⚙️ Instructions autorisées

- `sa`, `sb`, `ss` : swap les deux premiers éléments.
- `pa`, `pb` : push de l'une à l'autre pile.
- `ra`, `rb`, `rr` : rotate (déplace le premier élément à la fin).
- `rra`, `rrb`, `rrr` : reverse rotate (déplace le dernier élément en tête).

---

## 📐 Approche algorithmique

- **Cas simples** (2 à 5 éléments) : algorithmes triés à la main.
- **Grandes piles** : tri basé sur l’**algorithme Turkish** :
  - Retour optimisé dans la pile A en fonction du coût des mouvements.
- Choix stratégique des éléments à déplacer pour **minimiser le nombre d'instructions**.

---

