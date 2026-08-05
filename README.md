# VIDOM — Maquette interactive

Maquette HTML/CSS/JS autonome (aucune dépendance hors la police Google Inter) du projet **VIDOM — la mémoire vivante du logement** : vitrine publique, onboarding de création du logement, et application complète (15 domaines métier), avec des données fictives.

## Publier la maquette avec GitHub Pages

1. Créer un dépôt vide sur GitHub, par exemple nommé `vidom`.
2. Depuis ce dossier :

   ```bash
   git remote add origin https://github.com/<votre-compte>/vidom.git
   git branch -M main
   git push -u origin main
   ```

3. Dans GitHub, aller dans **Settings → Pages**, choisir **Deploy from a branch**, branche `main`, dossier `/ (root)`.
4. Après quelques minutes, la maquette est accessible à l'adresse :

   `https://<votre-compte>.github.io/vidom/`

Le fichier servi est `index.html` à la racine du dépôt, donc aucune configuration supplémentaire n'est nécessaire.
