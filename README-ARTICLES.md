# Articles de Blog - Guide d'importation

Ce fichier contient des exemples d'articles de blog sur l'hypnothérapie à importer dans Strapi.

## Structure créée

Le type de contenu "Article" a été créé dans Strapi avec les champs suivants :
- **title** (string, requis) : Titre de l'article
- **slug** (uid, requis) : URL-friendly identifier généré automatiquement
- **content** (richtext, requis) : Contenu de l'article en HTML
- **excerpt** (text) : Résumé court de l'article
- **image** (media) : Image principale de l'article
- **publishedAt** (datetime) : Date de publication

## Comment importer les articles

### Option 1 : Via l'interface Strapi (recommandé)

1. Connectez-vous à votre admin Strapi : https://abundant-horse-f9e91a1796.strapiapp.com/admin
2. Allez dans "Content Manager" > "Article"
3. Cliquez sur "Create new entry"
4. Pour chaque article du fichier `articles-exemples.json` :
   - Copiez le titre dans le champ "title"
   - Le slug sera généré automatiquement
   - Copiez le contenu HTML dans le champ "content"
   - Copiez l'excerpt dans le champ "excerpt"
   - Ajoutez une image si vous en avez une
   - Définissez la date de publication dans "publishedAt"
   - Cliquez sur "Save" puis "Publish"

### Option 2 : Via l'API Strapi (pour développeurs)

Vous pouvez utiliser l'API Strapi pour créer les articles programmatiquement. Assurez-vous d'avoir un token d'API avec les permissions nécessaires.

## Articles disponibles

Le fichier `articles-exemples.json` contient 5 articles sur l'hypnothérapie :

1. **Comprendre l'hypnose thérapeutique : mythes et réalités**
   - Slug : `comprendre-hypnose-therapeutique-mythes-realites`
   - Introduction générale à l'hypnose thérapeutique

2. **Arrêter de fumer avec l'hypnose : une méthode douce et efficace**
   - Slug : `arreter-fumer-hypnose-methode-douce-efficace`
   - Focus sur l'arrêt du tabac

3. **Gérer le stress et l'anxiété grâce à l'hypnose**
   - Slug : `gerer-stress-anxiete-grace-hypnose`
   - Gestion du stress et de l'anxiété

4. **Retrouver confiance en soi avec l'hypnose thérapeutique**
   - Slug : `retrouver-confiance-soi-hypnose-therapeutique`
   - Développement de la confiance en soi

5. **L'hypnose pour améliorer votre sommeil**
   - Slug : `hypnose-ameliorer-sommeil`
   - Troubles du sommeil et insomnies

## Notes importantes

- Les articles sont en HTML formaté (richtext)
- Les images doivent être ajoutées manuellement via l'interface Strapi
- Assurez-vous de publier les articles (pas seulement les sauvegarder en brouillon)
- Les dates de publication sont déjà définies dans le JSON

## Personnalisation

N'hésitez pas à modifier le contenu des articles pour qu'ils correspondent mieux à votre pratique et à votre style. Vous pouvez également ajouter vos propres articles directement dans Strapi.
