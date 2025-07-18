# 📉 Analyse de churn – Plateforme SaaS B2B

Ce projet a pour but d'identifier les utilisateurs à risque de résiliation sur une plateforme SaaS B2B, à travers une analyse exploratoire, un scoring métier, et un dashboard Power BI clair et actionnable.

---

## 🎯 Objectif

- Identifier les facteurs de churn client
- Créer un score de risque simple, basé sur l’usage réel
- Visualiser les données dans un tableau de bord interactif
- Aider les équipes produit à prioriser leurs actions

---

## 🧰 Stack utilisée

- **Python** – pandas, seaborn, matplotlib
- **SQL** – extraction & jointures multi-tables
- **Google Colab** – nettoyage + visualisations
- **Power BI** – dashboard final (interactif)

---

## 🛠 Méthodologie

### 1. Préparation des données
- Nettoyage des doublons et valeurs manquantes
- Feature engineering : fréquence d’utilisation, réactivité au support, etc.

### 2. Analyse exploratoire
- Visualisations : churn rate global, heatmaps de corrélation
- Comparaison des clients churnés vs. actifs

### 3. Scoring de churn
- Score sur 5 indicateurs métiers
- Création de segments : faible / moyen / haut risque

### 4. Dashboard
- Visualisation du churn global et par segment
- Filtres dynamiques par type d’abonnement, secteur, etc.
- Export PDF mensuel pour les équipes

---

## 📊 Résultat

- 🖥️ Dashboard Power BI en ligne (lien partagé à la demande)
- 📄 Rapport PDF exécutif pour décision produit
- 📌 Recommandations orientées action : UX, onboarding, support

---

## ✅ Compétences démontrées

- Analyse exploratoire de données
- Traitement et nettoyage dans Python
- Construction d’indicateurs métiers
- Restitution visuelle et claire via Power BI
- Approche orientée client SaaS

---

## 📁 Arborescence du dépôt

churn-analysis-saas/
├── data/ # Dataset fictif ou anonymisé
├── notebooks/ # .ipynb notebook (Google Colab)
├── dashboard/ # .pbix Power BI + screenshots
├── report/ # Rapport final PDF
└── README.md # Ce fichier

