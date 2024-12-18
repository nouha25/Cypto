# 🚀 Projet de Cryptographie Avancée : McEliece et Hamming Code

## 📝 Description
Ce projet explore les concepts avancés de cryptographie à travers deux modules clés :
1. **Code Hamming** : Correction d'erreurs pour des transmissions fiables.
2. **Chiffrement McEliece** : Un schéma post-quantique basé sur les codes correcteurs d'erreurs.

🔒 **Objectifs principaux :**
- Détecter et corriger des erreurs avec le code Hamming (7, 4).
- Implémenter le chiffrement et déchiffrement McEliece avec génération de clés.

---

## 📂 Structure des fichiers

| Fichier            | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `CodeHamming.cpp`  | Implémentation du décodage Hamming et correction des erreurs.               |
| `mceliece.cpp`     | Implémentation du chiffrement McEliece, génération de clés et déchiffrement.|
| `TP3-McEleice.pdf` | Documentation théorique sur le code Hamming et McEliece.                   |

---

## 🌟 Fonctionnalités

### 🎯 1. Code Hamming (7, 4)
- **Encodage** : Ajoute des bits de parité pour détecter et corriger une erreur par bloc.
- **Décodage** : Vérifie et corrige les erreurs en analysant les bits de parité.
- **Correction d'erreur** : Capable de corriger une seule erreur par bloc de 7 bits.

### 🔐 2. Chiffrement McEliece
- **Génération de clés** :
  - 🗝️ **Clé publique** : Matrice génératrice permutée pour le chiffrement.
  - 🗝️ **Clé privée** : Matrice originale et de parité pour le déchiffrement.
- **Chiffrement** : Encode un message à l'aide de la clé publique et ajoute un vecteur d'erreur.
- **Déchiffrement** : Utilise la clé privée pour corriger les erreurs et retrouver le message original.

---

## 🛠️ Compilation et Exécution

### 🚀 Étapes

1. **Compiler les fichiers** :
   ```bash
   g++ CodeHamming.cpp -o CodeHamming
   g++ mceliece.cpp -o mceliece
   ```

2. **Exécuter les programmes** :
   - Pour décoder les messages Hamming :
     ```bash
     ./CodeHamming
     ```
   - Pour générer des clés et exécuter le chiffrement McEliece :
     ```bash
     ./mceliece
     ```

---

## 📚 Ressources

- [Documentation sur le code Hamming](https://web.archive.org/web/20060525060427/http://www.caip.rutgers.edu/~bushnell/dsdwebsite/hamming.pdf)
- [Introduction au chiffrement McEliece](https://arxiv.org/pdf/1907.12754)

---

## 👨‍💻 Auteurs
Nouhaila JABBAR et Rim SADIQI


 
 
