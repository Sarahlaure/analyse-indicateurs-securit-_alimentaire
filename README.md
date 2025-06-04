# 📊 Analyse statistique des indicateurs de sécurité alimentaire au Tchad

Ce projet a été réalisé dans le cadre de l’examen final de **Projet Statistique sous R** en ISEP3 à l’ENSAE de Dakar.  
Il comporte deux volets complémentaires :

1. 🔍 Une **analyse statistique détaillée** des indicateurs de sécurité alimentaire à partir des données d’enquête
2. 💻 Une **application Shiny** interactive de visualisation des résultats

---

## 🧪 Partie 1 : Analyse statistique sous R

L’analyse repose sur une série de questions posées dans le cadre de l’examen, portant sur :

- ✅ **Nettoyage des données**
- 🧮 **Calcul d’indicateurs** 
- 📈 **Analyse descriptive** et **agrégats** (moyennes par région, scores normalisés, etc.)
- 🗂 **Fusion et préparation des bases**
- 📊 **Génération de tableaux** et **graphes comparatifs**

Les scripts R utilisés sont bien structurés, commentés, et rédigés sous RMarkdown pour produire un document clair, reproductible et exportable au format Word ou PDF.

---

## 💻 Partie 2 : Application Shiny interactive

Une application web a été développée pour :

- 🔎 Explorer dynamiquement les scores par **région ou département**
- 🗺 Afficher une **carte interactive** avec `leaflet`
- 📊 Présenter les résultats dans des **tableaux triables** (avec export possible)
- 📘 Documenter chaque indicateur via des onglets explicatifs

📍 **Lien de déploiement** : https://fogwoungsarahlaure.shinyapps.io/app_indicateurs_shiny/

---

## 🧠 Indicateurs étudiés

| Acronyme | Nom complet |
|----------|-------------|
| SCA      | Score de Consommation Alimentaire |
| rCSI     | Indice réduit des Stratégies de Survie |
| LhCSI    | Stratégies d’adaptation des moyens d’existence (LCS-FS) |
| HDDS     | Score de Diversité Alimentaire des Ménages |
| SERS     | Score de Résilience Structurelle |
| MAD      | Régime Alimentaire Minimum Acceptable |

---

## 👩🏽‍🎓 Réalisé par

**FOGWOUNG DJOUFACK Sarah-Laure**  
Étudiante en **ISEP3 – ENSAE de Dakar**  
🔗 [Profil GitHub](https://github.com/Sarahlaure)

---

## Livrables

- Un document **R Markdown** structuré a été utilisé pour traiter l’ensemble des questions posées dans le cadre de l’examen.
- Une version finale au format **Word** a été générée à partir de ce document pour la présentation des résultats.
- Enfin, une **application Shiny interactive** a été développée, comprenant trois pages principales :
    - **Page d’accueil** : propose une synthèse visuelle des indicateurs de sécurité alimentaire au niveau national, avec des encadrés pour la présentation de chaque indicateur.
    - **Page d’exploration interactive** : permet la **visualisation cartographique** et la **comparaison des indicateurs** par région ou département, à l’aide de **filtres dynamiques**.
    - **Page de documentation** : regroupe un **guide d’utilisation**, un **dictionnaire des variables**, ainsi que les **contributeurs** du projet.
