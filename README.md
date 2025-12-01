# Probeats — Maquette & Site statique

Livrable : maquette Figma (.fig) + site statique (5 pages) pour la présentation client.

## Contenu du dépôt
- `figma/probeats-maquette.fig` — maquette Figma (Desktop + Mobile) incluant : Accueil, Produit, Commande, À propos, Assistance, styles & composants.
- `index.html`, `produit.html`, `commande.html`, `apropos.html`, `assistance.html`
- `css/styles.css`
- `assets/` — images, logos, favicon, fonts, icons

## Consignes respectées
- Visuels **pleine page** sur les maquettes.
- Header : logo + menu (Produits, À propos, Assistance, Panier, Connexion).
- Footer : liens pages + mentions légales + contact + réseaux sociaux.
- Icônes : ajout via la librairie d’icônes Figma Community.
- Texte : Lorem Ipsum (www.lipsum.com).
- Padding : tous les blocs de contenu → `24px`.
- Prototype : enchaînements et interactions (desktop & mobile).

## Deployment / Soumission
- Vérifier que le repo est **public**.
- Copier l'URL du repo sur CEF Learning.

## Workflow git rapide
```bash
git init
git add .
git commit -m "Initial commit: probeats site + fig"
git remote add origin https://github.com/Nouseback/probeats-site.git
git branch -M main
git push -u origin main
