# 📊 Dashboard de Gestion Financière

Tableau de bord interactif pour suivre les dépôts, retraits et analyser ses finances personnelles.

## 🚀 Fonctionnalités

- **Gestion des transactions** :
  - Ajout de dépôts/retraits
  - Suppression de transactions
  - Historique complet
- **Statistiques en temps réel** :
  - Solde calculé automatiquement
  - Nombre total de transactions
  - Sommes cumulées par type
- **Visualisations graphiques** :
  - Camembert des flux financiers (Chart.js)
  - Courbe d'évolution journalière
- **Persistance des données** :
  - Stockage local (localStorage)
  - Mise à jour instantanée des graphiques


## 🚀 Technologies utilisées

* [Next.js](https://nextjs.org/)
* [Tauri](https://v2.tauri.app/)
* [Chart.js](https://www.chartjs.org/)


## 🎨 UI/UX Features
- **Feedback visuel** :
    - Couleurs conditionnelles (vert/rouge) selon le type de transaction
    - Surbrillance au survol
- **Micro-interactions** :
    - Animation des graphiques
    - Bouton "Ajouter" avec effet hover
 
## 👨‍💻 Auteurs

* [DevDhomm](https://github.com/DevDhomm)


## Voir en ligne

Vous pouvez voir la version en ligne [ici](https://finance-local-app.vercel.app/).


## Contribuer

Vous pouvez contribuer au projet en suivant ces instructions:

1. Cloner le repository : `git clone https://github.com/DevDhomm/FLAD.git`
2. Installer les dependencies : `pnpm install`
3. Lancer l'app : `pnpm tauri dev`