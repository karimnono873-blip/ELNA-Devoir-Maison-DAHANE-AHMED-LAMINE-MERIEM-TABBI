# 🌌 Filtre Passe-Bande (Cellule de Rauch) - Visualisation Interactive

[![Thème](https://img.shields.io/badge/Thème-Astronomic_Violet_Blue-7b2cbf?style=flat-square)](#)
[![Technologies](https://img.shields.io/badge/Stack-HTML5_%7C_CSS3_%7C_JS-4cc9f0?style=flat-square)](#)

Ce dépôt contient une page web interactive et monolithique dédiée à l'étude analytique et visuelle d'un **filtre actif passe-bande du second ordre (Topologie de Rauch)**. 

Le projet a été conçu pour allier rigueur académique et design UI moderne, avec un thème sombre inspiré de l'esthétique "Astronomic Google Pixel Violet Blue".

## 📑 Sommaire
- [Aperçu du Projet](#aperçu-du-projet)
- [Fonctionnalités Principales](#fonctionnalités-principales)
- [Contexte Académique](#contexte-académique)
- [Utilisation](#utilisation)
- [Crédits](#crédits)

## 🚀 Aperçu du Projet

L'objectif de cette page est de fournir une compréhension complète du comportement du filtre de Rauch, un montage crucial dans le conditionnement de signaux pour les systèmes automatisés. La page inclut le schéma électrique, les équations mathématiques de bout en bout, et une simulation visuelle de sa réponse fréquentielle.

## ✨ Fonctionnalités Principales

* 🎨 **Design Thématique immersif** : Interface "Dark Space" avec des effets de lueur néon (Violet/Bleu) pour une lisibilité optimale et un rendu visuel saisissant.
* 📐 **Schéma Vectoriel (SVG) Intégré** : Représentation précise et stylisée du circuit de Rauch (AOP, résistances, condensateurs) dessinée entièrement en code pur, sans images externes.
* 🧮 **Démonstrations Analytiques** : Explications pas-à-pas incluant :
    * Le concept de masse virtuelle (Vref+ / Vref-).
    * L'application du théorème de Millman.
    * Le calcul complet de la fonction de transfert de A à Z.
    * L'extraction du module et de l'argument (phase).
* 📊 **Diagrammes de Bode Dynamiques** : Tracé interactif du gain (en dB) et de la phase (en degrés) généré via **Chart.js**, illustrant clairement les pentes d'atténuation (±20 dB/décade).

## 🎓 Contexte Académique

Ce projet a été réalisé dans le cadre du module d'**Électronique Analytique / Systèmes Automatisés**. Il vise à démontrer l'application pratique et la modélisation mathématique des filtres actifs utilisés dans l'industrie pour isoler les signaux utiles des bruits parasites.

* **Présenté à :** Dr. Laib

## ⚙️ Utilisation

Le projet est conçu comme un fichier monolithique (tout-en-un). Aucune installation complexe n'est requise.

1.  Clonez ce dépôt ou téléchargez le fichier `index.html`.
2.  Ouvrez simplement le fichier `index.html` dans n'importe quel navigateur web moderne (Chrome, Firefox, Edge, Safari).
3.  Une connexion Internet est requise uniquement pour charger les polices Google Fonts (Orbitron, Rajdhani) et la bibliothèque Chart.js via CDN.

## 👨‍💻 Crédits

**Créé et développé par :** Dahane Ahmed Lamine
