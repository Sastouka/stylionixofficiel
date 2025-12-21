# STYLIONIX 💈 - Salon Management System

**STYLIONIX** est une application complète de gestion pour salons de coiffure et barbiers, développée en **Flutter**. Elle offre une solution "Tout-en-un" pour gérer les rendez-vous, les finances, les employés et les clients, avec une interface double (Mode Homme & Mode Femme).

---

## 📸 Aperçu

![Banner](assets/images/banner_preview.png)
*(Générez cette bannière via l'outil marketing inclus)*

## ✨ Fonctionnalités Principales

### 📅 Agenda & Réservations [BookingScreen]
* **Calendrier Intuitif :** Vue mensuelle et journalière des rendez-vous.
* **Prise de RDV Rapide :** Sélection du client, du coiffeur et du service.
* **Gestion des Créneaux :** Vérification automatique de la disponibilité des coiffeurs.
* **Statuts :** Suivi des paiements (Payé/Non Payé) et actions rapides (Modifier/Supprimer/Encaisser).

### 💰 Finance & Statistiques [FinanceScreen]
* **Dashboard Financier :** Suivi en temps réel des Recettes, Dépenses et du Net.
* **Graphiques Interactifs :**
    * Bar Chart : Revenus par coiffeur.
    * Pie Chart : Répartition du chiffre d'affaires par service.
* **Historique Détaillé :** Liste de toutes les transactions avec filtres (Par coiffeur, par période).
* **Saisie Rapide :** Ajout facile de dépenses (Loyer, Électricité) ou de ventes produits.

### 💎 Premium & Monétisation [PremiumScreen]
* **Modèle Freemium :** Écran de vente intégré pour la version "Licence à Vie".
* **Avantages Pro :** Déblocage des sauvegardes Cloud, thèmes illimités, et suppression des publicités.
* **Restauration des achats :** Gestion native des droits utilisateurs.

### 🌗 Double Mode (Homme / Femme)
* L'application gère deux bases de données distinctes pour s'adapter aux barbiers (Thème Sombre/Bleu) et aux salons pour dames (Thème Magenta/Moderne).

---

## 🛠️ Stack Technique

* **Framework :** Flutter (Dart)
* **State Management :** Provider
* **Graphiques :** `fl_chart`
* **Calendrier :** `table_calendar`
* **Formatage :** `intl`
* **Fonts :** `google_fonts` (Bebas Neue, Lato, Inter)

---

## 📂 Structure du Projet

```text
lib/
├── models/            # Modèles de données (Appointment, Stylist, Service...)
├── providers/         # Gestion d'état (AppState)
├── screens/
│   ├── booking_screen.dart  # Gestion de l'agenda
│   ├── finance_screen.dart  # Statistiques et comptabilité
│   ├── premium_screen.dart  # Page de vente / Upgrade
│   └── settings_screen.dart # Configuration
├── utils/             # Traductions et aides
└── main.dart          # Point d'entrée