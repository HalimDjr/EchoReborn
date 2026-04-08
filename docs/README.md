# 🎮 EchoReborn

> Jeu de rôle au tour par tour développé en C# avec MonoGame — données de jeu gérées via XML/XSD/XSLT.

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![MonoGame](https://img.shields.io/badge/MonoGame-E73C00?style=for-the-badge&logo=monogame&logoColor=white)
![XML](https://img.shields.io/badge/XML-005FAD?style=for-the-badge&logo=xml&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

---

## 📖 Description

**EchoReborn** est un jeu vidéo RPG au tour par tour développé avec le framework **MonoGame** en C#.  
Le projet met en avant une architecture data-driven : les ennemis, compétences, dialogues et niveaux sont définis dans des fichiers **XML**, validés par des schémas **XSD** et transformés via **XSLT**.

---

## ✨ Fonctionnalités

### ⚔️ Système de Combat
- Combats au tour par tour
- Actions : Attaque, Défense, Compétences
- Calculs de dégâts et soins
- Conditions de victoire / défaite

### 🧙 Gestion des Personnages
- Système de stats : HP, MP, Attaque, Défense, Vitesse
- Système de niveaux et d'expérience
- Compétences et capacités spéciales

### 🌍 Monde du Jeu
- 5 zones / localisations
- Transitions entre les zones
- Points de sauvegarde
- 3 à 5 types d'ennemis par zone

### 💾 Progression
- Système de dialogue
- Sauvegarde et chargement de partie
- Menu principal & menu pause
- Interface de combat et affichage des stats

---

## 🛠️ Stack Technique

| Technologie | Rôle |
|-------------|------|
| **C#** | Langage principal |
| **MonoGame** | Framework de jeu (rendu, input, audio) |
| **XML** | Données de jeu (ennemis, niveaux, compétences) |
| **XSD** | Validation des schémas XML |
| **XSLT** | Transformation et génération de contenu |

---

## 🚀 Lancer le projet

### Prérequis

- [.NET SDK 6+](https://dotnet.microsoft.com/download)
- Templates MonoGame :

```bash
dotnet new --install MonoGame.Templates.CSharp
```

### Installation & lancement

```bash
# Cloner le repo
git clone https://github.com/HalimDjr/EchoReborn.git
cd EchoReborn

# Restaurer les dépendances
dotnet restore

# Lancer le jeu
dotnet run
```


---

## 📄 Licence

Ce projet est développé dans un cadre académique.  
Toute réutilisation est soumise à l'accord des contributeurs.
