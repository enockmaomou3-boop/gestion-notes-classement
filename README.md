# 📊 Gestion des Notes et Classement

Une application web moderne pour gérer les notes des étudiants avec classement automatique, statistiques et export de données.

## ✨ Fonctionnalités

### Gestion des notes
- ➕ **Ajouter des étudiants** avec leurs notes (0-20)
- ✏️ **Éditer** les informations des étudiants
- 🗑️ **Supprimer** des étudiants individuellement
- 🔄 **Classement automatique** par ordre décroissant de notes

### Mentions scolaires
Les mentions sont attribuées automatiquement selon les notes:
- 🟢 **Très Bien** : ≥ 16/20
- 🔵 **Bien** : ≥ 14/20
- 🟠 **Assez Bien** : ≥ 12/20
- 🟡 **Passable** : ≥ 10/20
- 🔴 **Ajourné** : < 10/20

### Statistiques
- 📈 Nombre total d'étudiants
- 📊 Moyenne générale
- ⬆️ Meilleure note
- ⬇️ Note la plus basse

### Export et persistance
- 💾 **Stockage local** - Les données sont sauvegardées automatiquement dans le navigateur
- 📥 **Export CSV** - Télécharger les résultats en format CSV
- 📥 **Export JSON** - Télécharger les résultats en format JSON
- 🗑️ **Effacer tout** - Réinitialiser complètement les données

## 🚀 Utilisation

1. **Ouvrir l'application** : Ouvrez `index.html` dans votre navigateur
2. **Ajouter un étudiant** : Entrez le nom et la note, puis cliquez sur "Ajouter"
3. **Éditer** : Cliquez sur "✏️ Éditer" pour modifier un étudiant
4. **Supprimer** : Cliquez sur "🗑️ Supprimer" pour enlever un étudiant
5. **Exporter** : Téléchargez vos résultats en CSV ou JSON
6. **Les données sont automatiquement sauvegardées** dans le localStorage de votre navigateur

## 🛠️ Technologies utilisées

- **HTML5** - Structure
- **CSS3** - Styling moderne et responsive
- **JavaScript (Vanilla)** - Logique d'application
- **localStorage** - Persistance des données

## 📱 Responsive Design

L'application s'adapte parfaitement à tous les appareils:
- 📱 Téléphones
- 📱 Tablettes
- 💻 Ordinateurs de bureau

## 📝 Licence

Projet libre d'utilisation

## 👨‍💻 Auteur

Créé avec ❤️ par enockmaomou3-boop