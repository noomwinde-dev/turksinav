# 🇹🇷 Türkçe C1 Seviye Sınav ve Eğitim Platformu

Une plateforme web interactive et autonome d'entraînement et d'évaluation pour le niveau avancé **C1 en langue turque**. Ce projet est spécialement conçu pour développer la capacité d'inférence logique (*Yargı Çıkarma*), l'analyse fine de textes académiques et la détection des pièges classiques des QCM.

---

## 📸 Aperçu des Fonctionnalités

- **Sessions d'examen dynamiques** : Séries de 5 questions tirées d'une base de données thématique C1 (Intelligence Artificielle, Écologie, Économie, Neurosciences, etc.).
- **Analyse détaillée des pièges (*Hata Analizi*)** : Pour chaque option (A, B, C), une explication pédagogique précise indique pourquoi la réponse est correcte ou en quoi elle constitue un piège (généralisation, extrapolation, inversion logique).
- **Lexique académique intégré (*Vocabulary*)** : Vocabulaire clé et tournures idiomatiques définis pour chaque texte.
- **Mode Révision des erreurs (*Hataları İncele*)** : Enregistrement automatique des questions manquées pour un travail ciblé sur les points faibles.
- **Gestion de la progression (JSON & LocalStorage)** :
  - Sauvegarde automatique en temps réel.
  - Exportation et importation de l'historique sous forme de fichier `.json`.
  - Réinitialisation de la progression à tout moment.
- **Interface Utilisateur Moderne (UI/UX)** :
  - Mode sombre / Mode clair (*Dark Mode* toggle).
  - Barre de progression visuelle et score dynamique.
  - Design fluide et adaptatif (*Responsive Design*).
- **100% Autonome & Hors-ligne** : Fonctionne directement dans n'importe quel navigateur web sans dépendance à un serveur back-end.

---

## 🛠️ Technologies Utilisées

- **HTML5** : Structure sémantique de l'application Single Page (SPA).
- **Tailwind CSS** : Styling moderne, gestion du mode sombre et mise en page réactive.
- **JavaScript (Vanilla ES6+)** : Logique de l'examen, gestion de la base de données, stockage local et manipulation du DOM.
- **LocalStorage API** : Persistence des données utilisateur dans le navigateur.

---

## 🚀 Installation et Utilisation

Aucune installation complexe ni serveur Node.js n'est requis.

1. **Cloner ou télécharger le projet** :
   ```bash
   git clone [https://github.com/noomwinde-dev/turksinav.git](https://github.com/noomwinde-dev/turksinav.git)
   
