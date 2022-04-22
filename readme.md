#Python 
##Vigenère Encryption Tool
Le **chiffrement de Vigenère**, type de [chiffrement par substitution](https://fr.wikipedia.org/wiki/Chiffrement_par_substitution "Chiffrement par substitution") utilisé pour le chiffrement de données dans lequel la structure originale du texte en clair est quelque peu dissimulée dans le texte chiffré en utilisant plusieurs différents chiffrages par substitution monoalphabétiques plutôt qu'un seul. 

La clé de code spécifie quelle substitution particulière doit être employée pour chiffrer chaque symbole du texte en clair. Ces chiffrages résultants, connus sous le nom générique de _**polyalphabétiques**_, ont une longue histoire d'utilisation. Les systèmes diffèrent principalement par la manière dont la clé est utilisée pour choisir parmi la collection de règles de substitution monoalphabétique.

<p align="center">
  <img src="https://iili.io/VAnXQn.md.png" />
</p>

## Prérequis

<p>
<p align="center">
<a href="https://www.python.org/downloads/"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Python_logo_and_wordmark.svg" alt="W3Schools" width="436" height="139" border="0" />
</a>
</p>

## Installation

<h3><strong>Windows </strong>&nbsp;<img src="https://simpleicons.org/icons/windows.svg" alt="" width="20" height="20" /></h3>

[Télécharger le repository](https://github.com/danglock/V.E.T-Vigenere-Encryption-Tool/archive/refs/heads/main.zip)

<h3><strong>Linux / UX </strong>&nbsp;<img src="https://simpleicons.org/icons/linux.svg" alt="" width="25" height="25" /></h3>


Télécharger le repository avec la commande suivante :
```bash
git clone https://github.com/danglock/Python-Vigenere-Encryption-Tool.git
```
Entrer dans le repository
```bash
cd Python-Vigenere-Encryption-Tool
```  

Rendre le fichier exécutable
```bash
chmod +x vigenere.py
```

## Utilisation

**Attention !** Veuillez **remplacer** ``./vigenere.py`` par ``python vigenere.py`` lors d'une utilisation sous l'**OS Windows**.

Voici la commande permettant d'effectuer un chiffrement Vigenère :
```bash
./vigenere.py -k "key"
```

Chiffrer un text :
```bash
./vigenere.py -k "key" -e "TextToEncrypt"
```

Chiffrer le contenu d'un fichier, puis préciser un chemin de sortie :

```bash
./vigenere.py -k "key" -EF "InputFile.txt" -OF "OutputFile.txt"
```

## À propos

Ce script a été développé dans un cadre d'étude de l'interpréteur python et du chiffrement. Nous déclinons toutes les responsabilités quant à une utilisation malintentionnée.

Message destiné aux élèves de l'EPSIC  : si vous utilisez ce code dans le cadre d'un examen, vous pouvez vous en inspirer, mais pas le copier.

**Auteur :** danglock

**Contributeur :** AlexioShow, Ploudo

**Date :** 13.04.2022
