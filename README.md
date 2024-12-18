# 🚀 **Projet de Cryptographie Avancée : McEliece et Hamming Code**

---

## 📝 **Description**
Ce projet explore les concepts avancés de cryptographie à travers deux modules clés :

1. **🛡️ Code Hamming** : Correction d'erreurs pour assurer des transmissions fiables.
2. **🔐 Chiffrement McEliece** : Un schéma post-quantique basé sur les codes correcteurs d'erreurs.

🔒 **Objectifs principaux :**
- ✅ Détecter et corriger des erreurs grâce au **code Hamming (7, 4)**.
- 🔑 Implémenter le **chiffrement et déchiffrement McEliece** avec génération de clés.

---
## 📂 **Structure des fichiers**

| 🗂️ **Fichier**          | 📝 **Description**                                                                     |
|-------------------------|---------------------------------------------------------------------------------------|
| `CodeHamming.cpp`       | Implémentation du **décodage Hamming** et correction des erreurs.                     |
| `mceliece.cpp`          | Implémentation du **chiffrement McEliece**, génération de clés et déchiffrement.      |
| `TP3-McEleice.pdf`      | Documentation théorique sur le **code Hamming** et le chiffrement **McEliece**.       |

---
## 🌟 **Fonctionnalités**

### 🎯 **1. Code Hamming (7, 4)**
- **🧩 Encodage** : Ajout de bits de parité pour détecter et corriger les erreurs.
- **🔍 Décodage** : Analyse des bits de parité pour corriger d'éventuelles erreurs.
- **⚙️ Correction d'erreur** : Capable de corriger **une seule erreur** par bloc de **7 bits**.

### 🔐 **2. Chiffrement McEliece**
- **🗝️ Génération de clés** :
  - **🔑 Clé publique** : Matrice génératrice permutée pour le chiffrement.
  - **🔒 Clé privée** : Matrice originale et matrice de parité pour le déchiffrement.
- **🛡️ Chiffrement** : Encodage d'un message via la **clé publique** avec ajout d'un **vecteur d'erreur**.
- **🔓 Déchiffrement** : Correction des erreurs à l'aide de la **clé privée** pour retrouver le message original.

---

## 🛠️ **Compilation et Exécution**

### 🚀 **Étapes pour exécuter le projet**

1. **🔧 Compiler les fichiers** :
   ```bash
   g++ CodeHamming.cpp -o CodeHamming
   g++ mceliece.cpp -o mceliece
   ```

2. **▶️ Exécuter les programmes** :

- **Pour décoder les messages Hamming** :
   ```bash
   ./CodeHamming
   ```

- **Pour générer des clés et exécuter le chiffrement McEliece** :
   ```bash
   ./mceliece
   ```

---

## 👨‍💻 **Auteurs**
**Nouhaila JABBAR** et **Rim SADIQI**

