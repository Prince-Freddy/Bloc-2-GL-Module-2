# DevStart Agency — Site Web

## 📋 Informations du groupe

**Bloc 2 — Génie Logiciel | Module 2 : Architecture logicielle & modularité**  
**Académie de Programmation | IFRI — L1**  
**Date : Dimanche 03 Mai 2026**

### Membres du Groupe 2

| Nom & Prénom |
|---|
| DJOMAМOU Souviens Hosana Loth |
| JOSSE Marianne Leslie |
| ADJALLALA Agossi Melvine |
| HOUETO Brian |
| HOUNHOWAKOU Prince Freddy |

---

## 📌 Description du projet

Ce dépôt contient le travail du **Module 2 — Découper pour mieux régner**. À partir de la page d'accueil du stagiaire (Module 1), notre groupe a conçu une **architecture logicielle modulaire** pour le site DevStart Agency, sans modifier le rendu visuel. L'objectif est simple : chaque fichier a une seule responsabilité, et la structure est pensée pour accueillir facilement trois nouvelles pages dans le futur — Portfolio, Blog et Espace Client.

---

## 🌿 Branches du dépôt

| Branche | Contenu |
|---|---|
| `main` | Code original du Module 1 — conservé intact, jamais modifié |
| `module2` | Nouvelle architecture modulaire conçue par le groupe |

---

## 🗂️ Structure des dossiers (branche `module2`)

```
DevStart/
│
├── Original/
│   ├── index.html               ← Page d'accueil
│   ├── portfolio.html           ← Page Portfolio (future)
│   ├── blog.html                ← Page Blog (future)
│   ├── espace-client.html       ← Espace Client (futur)
│   │
│   └── Assets/
│       ├── Styles/              ← Styles communs à toutes les pages
│       │   ├── base.css
│       │   ├── header.css
│       │   ├── hero.css
│       │   ├── services.css
│       │   ├── about.css
│       │   ├── testimonials.css
│       │   ├── contact.css
│       │   └── footer.css
│       │
│       ├── Components/          ← Éléments réutilisables sur plusieurs pages
│       │   ├── card.css
│       │   └── button.css
│       │
│       ├── Pages/               ← Styles spécifiques à chaque future page
│       │   ├── portfolio.css
│       │   ├── blog.css
│       │   └── espace-client.css
│       │
│       └── img/                 ← Ressources visuelles du site
│           ├── hero.png
│           └── team.png
│
└── README.md
```

---

## 📁 Rôle de chaque fichier CSS

| Fichier | Rôle |
|---|---|
| `base.css` | Reset général, couleurs globales et police du site |
| `header.css` | Style de la barre de navigation |
| `hero.css` | Style de la section d'accueil |
| `services.css` | Style des cartes de services |
| `about.css` | Style de la section À propos |
| `testimonials.css` | Style des témoignages clients |
| `contact.css` | Style du formulaire de contact |
| `footer.css` | Style du pied de page |
| `card.css` | Style réutilisable pour toutes les cartes |
| `button.css` | Style réutilisable pour tous les boutons |
| `portfolio.css` | Styles spécifiques à la page Portfolio |
| `blog.css` | Styles spécifiques à la page Blog |
| `espace-client.css` | Styles spécifiques à l'Espace Client |

---

## 🧠 Ce que cette architecture change concrètement

| Avant (Module 1) | Après (Module 2) |
|---|---|
| 1 seul `style.css` pour tout le site | 1 fichier CSS par section et par page |
| Difficile de savoir où chercher quand quelque chose bug | On sait immédiatement dans quel fichier se trouve le problème |
| Modifier une section risque d'en casser une autre | Chaque fichier est isolé — aucun risque de conflit |
| Un nouveau développeur met du temps à comprendre la structure | La structure se comprend en moins de 30 secondes |
