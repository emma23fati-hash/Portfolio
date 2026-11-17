# Portfolio de Fatima Emmanuella Joseph

Site web de mon portfolio de BUT Génie Mécanique et Productique (parcours CPD), créé à partir de mon portfolio Canva.

## Contenu du dossier

- `index.html` : tout le texte du site, chapitre par chapitre.
- `style.css` : les couleurs, les polices et la mise en page.
- `images/` : les images exportées depuis Canva.

## Mettre le site en ligne avec GitHub Pages

1. Créez un compte sur github.com si vous n’en avez pas.
2. Cliquez sur « New repository ». Nommez-le par exemple `portfolio`, laissez-le en « Public » et validez.
3. Sur la page du dépôt, cliquez sur « Add file », puis « Upload files ».
4. Glissez `index.html`, `style.css`, `README.md` et le dossier `images` en entier, puis cliquez sur « Commit changes ».
5. Allez dans « Settings », puis « Pages ». Dans « Branch », choisissez `main` et le dossier `/ (root)`, puis « Save ».
6. Après une à deux minutes, l’adresse du site s’affiche en haut de cette page, sous la forme `https://votre-pseudo.github.io/portfolio/`.

## Modifier le site

Directement sur GitHub : ouvrez `index.html`, cliquez sur le crayon (« Edit this file »), modifiez le texte, puis « Commit changes ». Le site se met à jour en une à deux minutes.

- Changer un texte : modifiez ce qui se trouve entre `<p>` et `</p>`. Ne supprimez pas les balises.
- Chaque chapitre commence par un commentaire comme `<!-- ===== 4. INDUSTRIE ===== -->`, pour vous repérer.
- Ajouter un bloc : copiez un bloc complet `<article class="folio"> ... </article>` et collez-le juste en dessous, puis changez le titre et le texte.
- Ajouter une image : envoyez-la dans le dossier `images` (« Add file », « Upload files »), puis ajoutez dans un bloc :
  `<figure><img src="images/mon-image.jpg" alt="Description de l’image"></figure>`
- Changer les couleurs : en haut de `style.css`, modifiez les valeurs comme `--trait: #2f6fb0;`.

Pour modifier sur votre ordinateur, installez Visual Studio Code, ouvrez le dossier, et ouvrez `index.html` dans un navigateur pour voir le résultat.

## Attention

Un dépôt « Public » et un site GitHub Pages sont visibles par tout le monde. Vérifiez que votre CV ne montre pas votre adresse ou votre numéro de téléphone si vous ne voulez pas les rendre publics, et faites valider par votre tuteur les informations sur l’entreprise.
