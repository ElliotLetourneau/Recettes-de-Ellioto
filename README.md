# 📖 Mon Recueil de Recettes

Catalogue personnel de recettes accessible via GitHub Pages.

## Structure du projet

```
mon-recueil/
├── index.html        ← Le site (ne pas modifier sauf pour personnaliser)
├── recettes.json     ← La liste de toutes tes recettes  ← À MODIFIER
├── recettes/         ← Dossier avec tous tes PDFs       ← À REMPLIR
│   ├── crepes-sirop-erable.pdf
│   ├── soupe-oignon.pdf
│   └── ...
└── README.md
```

## ➕ Ajouter une nouvelle recette

1. **Dépose ton PDF** dans le dossier `recettes/`
2. **Ouvre `recettes.json`** et ajoute une entrée en suivant ce modèle :

```json
{
  "nom": "Nom de ta recette",
  "categorie": "Plats — Viande",
  "fichier": "nom-du-fichier.pdf",
  "tags": ["rapide", "hivernal"]
}
```

### Catégories disponibles

| Valeur exacte à utiliser | Description |
|---|---|
| `Déjeuners / Brunchs` | |
| `Entrées / Soupes` | |
| `Salades` | |
| `Pâtes` | |
| `Plats — Viande` | |
| `Plats — Poisson & Fruits de mer` | |
| `Plats — Végétarien` | |
| `Accompagnements` | |
| `Desserts / Pâtisseries` | |

> ⚠️ Respecte l'orthographe exacte de la catégorie, sinon elle apparaîtra en doublon.

## 🚀 Déploiement sur GitHub Pages

1. Crée un dépôt GitHub (ex: `recettes`)
2. Pousse tous les fichiers
3. Va dans **Settings → Pages**
4. Source : `Deploy from branch` → branche `main`, dossier `/` (root)
5. Ton site sera disponible à : `https://ton-username.github.io/recettes/`

## 🏷️ Tips pour les tags

Les tags sont libres — utilise-les pour filtrer par saison, difficulté, type, etc.  
Exemples : `rapide`, `hivernal`, `végé`, `épicé`, `classique`, `familial`, `élégant`
