<p align="center">
  <img src="https://github.com/iMoDzF4N4T1K/iMoDzF4N4T1K/raw/main/assets/xmb/header.svg" alt="XMB Header" />
</p>

<h1 align="center">🏁 Gran Turismo 5 Tool</h1>

<p align="center">
  <b>Pack d’outils pour éditer / gérer des sauvegardes Gran Turismo 5 (PS3 / RPCS3)</b><br/>
  <sub>⚠️ Utilisation à vos risques — faites toujours une copie de votre sauvegarde AVANT modification.</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/iMoDzF4N4T1K/Gran-Turismo-5-Tool?style=flat-square" />
  <img src="https://img.shields.io/github/forks/iMoDzF4N4T1K/Gran-Turismo-5-Tool?style=flat-square" />
  <img src="https://img.shields.io/github/last-commit/iMoDzF4N4T1K/Gran-Turismo-5-Tool?style=flat-square" />
  <img src="https://img.shields.io/github/license/iMoDzF4N4T1K/Gran-Turismo-5-Tool?style=flat-square" />
</p>

<p align="center">
  <a href="#-présentation">Présentation</a> •
  <a href="#-compatibilité-très-important">Compatibilité</a> •
  <a href="#-contenu-du-dépôt">Contenu</a> •
  <a href="#-pré-requis">Pré-requis</a> •
  <a href="#-utilisation-ps3">PS3</a> •
  <a href="#-utilisation-rpcs3">RPCS3</a> •
  <a href="#-title-id--savedata">Title ID</a> •
  <a href="#-licence--crédits">Licence</a>
</p>

<p align="center">
  <img src="https://github.com/iMoDzF4N4T1K/iMoDzF4N4T1K/raw/main/assets/xmb/divider_1.svg" alt="divider" />
</p>

## ✨ Présentation

**Gran-Turismo-5-Tool** regroupe plusieurs outils “classiques” de la communauté pour travailler sur **Gran Turismo 5 (version normale)** :
- édition de sauvegarde (progression / flags / divers selon l’outil),
- édition du garage,
- outils complémentaires.

> ✅ Ici on parle de **Gran Turismo 5 “normal”** (pas Prologue / autres éditions).  
> ✅ Toujours travailler sur une **copie** de votre sauvegarde, pas sur l’unique original.

<p align="center">
  <img src="https://github.com/iMoDzF4N4T1K/iMoDzF4N4T1K/raw/main/assets/xmb/divider_1.svg" alt="divider" />
</p>

## 🚨 Compatibilité (TRÈS IMPORTANT)

### ✅ Version de jeu recommandée : **mise à jour 2.11 MAX**
Pour utiliser les tools **sans mauvaises surprises**, il est fortement recommandé de rester en :
- **GT5 ≤ 2.11** ✅  
- **GT5 ≥ 2.12** ⚠️ certaines fonctions / champs peuvent ne plus fonctionner (ou ne plus s’appliquer correctement).

> En clair : si tu veux “le meilleur taux de réussite”, **reste en 2.11**.

### ✅ Sauvegarde requise : **save normale (pas un backup système)**
- Utilise la **sauvegarde standard** du jeu (le dossier `SAVEDATA` avec `PARAM.SFO`, etc.)
- ❌ Pas un **backup complet** fait via l’outil de sauvegarde/restauration système PS3.

<p align="center">
  <img src="https://github.com/iMoDzF4N4T1K/iMoDzF4N4T1K/raw/main/assets/xmb/divider_1.svg" alt="divider" />
</p>

## 📦 Contenu du dépôt

Le dépôt est organisé en 3 packs :

- **GT5_Editor_v 1.6 (2.14)**
- **GT5_Garage_Editor_v131_slim355_q-k/Release**
- **GT5_Save_Editor_v0.0.10.3/GT5_Save_Editor_v0.0.10.3**

> ℹ️ Même si un dossier mentionne une version plus haute, la règle “safe” ici reste : **2.11 max** (sinon certaines fonctions risquent de ne pas suivre).

<p align="center">
  <img src="https://github.com/iMoDzF4N4T1K/iMoDzF4N4T1K/raw/main/assets/xmb/divider_1.svg" alt="divider" />
</p>

## ⚙️ Pré-requis

- **Windows** (la plupart des outils sont distribués en `.exe`)
- **Gran Turismo 5 (version normale)** en **2.11 max**
- Une **sauvegarde GT5 normale** (format SAVEDATA)

<p align="center">
  <img src="https://github.com/iMoDzF4N4T1K/iMoDzF4N4T1K/raw/main/assets/xmb/divider_1.svg" alt="divider" />
</p>

## 🕹️ Utilisation (PS3)

### 1) Récupérer la save
- Copie ta sauvegarde GT5 sur USB (méthode classique PS3)

### 2) Faire une copie (recommandé)
- Duplique le dossier de save sur ton PC (ex: `SAVEDATA_GT5_ORIGINAL` → `SAVEDATA_GT5_EDIT`)

### 3) Éditer
- Lance l’outil voulu
- Ouvre le dossier de save
- Applique tes modifications
- Sauvegarde / exporte

### 4) Réinjecter
- Recopie la save modifiée sur USB
- Remets-la sur PS3
- Lance le jeu et vérifie

<p align="center">
  <img src="https://github.com/iMoDzF4N4T1K/iMoDzF4N4T1K/raw/main/assets/xmb/divider_1.svg" alt="divider" />
</p>

## 🖥️ Utilisation (RPCS3)

✅ **RPCS3 est parfaitement fonctionnel** avec ces outils.

Les sauvegardes sont au même emplacement “logique” que sur PS3, dans le dossier RPCS3 :

```txt
dev_hdd0\home\00000001\savedata\
