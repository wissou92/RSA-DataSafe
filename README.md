<p align="center">
  <img src="features/rsa_logo.png">
</p>

---

[![GitHub top language](https://img.shields.io/github/languages/top/RSA-Datasafe/RSA-Datasafe)](https://github.com/RSA-DataSafe/RSA-DataSafe)

# Projet autout de l'algorithme de RSA

Le but de ce projet est d'implémenter RSA. Nous auront la possibilité de signer et de vérifier un fichier pour s'assurer de l'identiter de l'envoyeur. 

# Installation - Déployement du produit 

## ⚒ Compiler le projet

make

## ▶ Executer le projet

make run

## ℹ Le code source

Il se trouve dans le répertoire `src/`.

`cd src/`

# Module de notre projet

## Interface

Ce module gère la communication entre le programme, l'utilisateur et les autres module.

## Génération des clés

Génère les clés pour chiffrer et déchiffrer un message.

## Chiffrement

Chiffre un message.

## Signature

Il a deux principale fonctionnalité :

- générer une signature
- verifier une signature

Ce module utilise une fonction de hashage. On a choisi d'utiliser sha3.

## Déchiffrement

Déchiffre un message.

## Gestion de fichier

Gére la connection à l'application ainsi que la sauvegarde des clés de l'utilisateur et de ses messages.
