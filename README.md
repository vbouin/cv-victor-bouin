# Victor Bouin — CV interactif

CV interactif one-page (scrollytelling, bilingue FR/EN) — Design · Innovation · IA.
DA premium « luminous noir », identité Exoflow. 100 % statique, aucun build.

## Déploiement Vercel (recommandé)
Repo **privé**. Deux options :

**A. Depuis le dépôt GitHub (le plus simple)**
1. vercel.com → *Add New… → Project* → *Import* `vbouin/cv-victor-bouin`
2. Framework Preset : **Other** · Build Command : *(vide)* · Output Directory : `.`
3. Deploy. (Le `vercel.json` gère URLs propres, cache et en-têtes de sécurité.)

**B. En CLI**
```bash
npm i -g vercel
cd cv-victor
vercel        # preview
vercel --prod # production
```

## Aperçu local
Ouvrir `index.html`, ou `python3 -m http.server 4680`.

## Contenu
Hero · Structures (Exoflow/Acmé) · Références · Témoignages · Approche · Chaîne de valeur ·
Expertises · Méthode · Labo clients · Layers · Parcours · Formations · Projets IA · Vision · Contact

## Notes
- Données 100 % en dur (i18n FR/EN) — pas d'entrée utilisateur, pas de backend, pas de secret.
- Logos clients : Wikimedia Commons. Témoignages : verbatims réels (questionnaire de satisfaction 2025).
