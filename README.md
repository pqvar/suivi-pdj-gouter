# 📊 Suivi PDJ & Goûter

Application web pour la gestion des coûts et marges du petit-déjeuner et goûter en hôtellerie.

## 🚀 Accès direct

👉 **[Lancer l'application](https://VOTRE-USERNAME.github.io/VOTRE-REPO/index.html)**

*(Remplacez VOTRE-USERNAME et VOTRE-REPO par vos vraies valeurs)*

## 📖 Description

Application de suivi hebdomadaire permettant de :
- Calculer automatiquement les coûts matières
- Suivre les marges par petit-déjeuner
- Gérer la répartition PDJ/Goûter
- Exporter les données

Développée pour optimiser la gestion des buffets petit-déjeuner avec suivi par inventaire hebdomadaire.

## ✨ Fonctionnalités

### 📦 Gestion des inventaires
- Saisie hebdomadaire : stock début, achats, stock fin
- Calcul automatique de la consommation
- Répartition intelligente PDJ/Goûter par produit

### 📊 Indicateurs en temps réel
- Coût moyen par petit-déjeuner
- Marge % (objectif 70-75%)
- Coût goûter par semaine
- Évolution sur 4 semaines

### 📚 Historique
- Conservation de 20 semaines
- Suppression sélective
- Vue d'ensemble complète

### 🛒 Configuration produits
- 12 produits pré-configurés
- Ajout de produits personnalisés
- Prix et ratios modifiables

### 💾 Export des données
- **Excel** : 2 feuilles (Historique + Produits)
- **PDF** : Rapport complet avec indicateurs

## 🎯 Utilisation

### Étape 1 : Démarrer une semaine
1. Onglet **Tableau de bord**
2. Renseigner : date, nombre de PDJ, prix de vente
3. Cliquer sur **"Démarrer nouvelle semaine"**

### Étape 2 : Inventaire
1. **Lundi matin** : Stock début
2. **Pendant la semaine** : Achats
3. **Dimanche soir** : Stock fin
4. Cliquer sur **"Enregistrer inventaire"**

### Étape 3 : Consultation
Les calculs sont automatiques :
- Consommation = Stock début + Achats - Stock fin
- Coût = Consommation × Prix unitaire
- Répartition selon % PDJ configuré
- Marge = (Prix vente - Coût) / Prix vente

## 💻 Installation locale

### Téléchargement
```bash
