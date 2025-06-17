# Breguet-Watch-Scraper

# 💼 Projet IA – Structuration intelligente de données horlogères

Ce dépôt contient le code et les ressources associés au projet de **collecte et d’analyse automatisée de fiches produits horlogères**, avec un focus sur la marque **Breguet**.

---

## 🧩 Objectif du projet

L’objectif est de **scraper automatiquement** les fiches montres disponibles sur la plateforme [EveryWatch.com](https://www.everywatch.com), puis de **structurer les descriptions textuelles techniques** à l’aide d’un modèle d’intelligence artificielle avancé (GPT-4 via l’API OpenAI).

Ce pipeline vise à générer une base de données exploitable, normalisée, et prête à être utilisée dans des analyses métier (pricing, veille concurrentielle, enrichissement de catalogue, etc.).

---

## ⚙️ Technologies utilisées

- **Python 3.12+**
- **Playwright** : pour le scraping dynamique des pages web
- **OpenAI (GPT-4)** : pour l’extraction intelligente des informations techniques
- **Pandas / JSON / Excel** : pour la manipulation et l’export des données
- **Jupyter Notebook** : pour les tests et l’itération rapide

- 
## 🗂️ Structure du dépôt

```bash
.
├── (E1) Document d’analyse stratégique.pdf   # Analyse des choix technologiques et IA
├── (E2) Compte rendu de projet.pdf           # Compte rendu vulgarisé à destination du client
├── Daytona-db-sample.xlsx        # Base de données contenant des montres déjà récupérées manuellement par le client
├── README.md                     # Documentation du projet
├── Watchfeed.csv                 # Export brut des fiches scrappées
├── all_watches_data.json         # Données horlogères structurées
├── login.py                      # Script de connexion / authentification générique
├── login_mac.py                  # Variante du script login pour macOS
├── re_logic_bis2.py              # Script de scrapping de 4800 montres
├── remplissage_excel.ipynb       # Notebook afin de répartir les données scrapper depuis le json vers excel
