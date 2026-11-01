# Expédition ᐊᐅᔪᐃᑦᑐᖅ · Auyuittuq 2027

Site de présentation de notre traversée à ski et pulka du col Akshayuk, dans le parc national Auyuittuq (Nunavut), en avril 2027. Il sert surtout à trouver des partenaires pour nous équiper.

- **Équipe :** 7 amis, 4 de Montréal et 3 du Nunavut
- **Itinéraire :** Qikiqtarjuaq → Pangnirtung, 100 km à ski en 8 jours, de −30 à −40 °C
- **Contact :** dorianecara2@gmail.com

## Contenu du dépôt

```
index.html      le site complet (textes FR/EN, styles et animations)
img/            photos, dessins et écritures à la main
  hw/           les mots écrits à la main sur les étiquettes en ruban
README.md       ce fichier
```

Le site est un simple fichier HTML, sans base de données ni étape de compilation. Les polices viennent de Google Fonts.

## Mettre le site à jour

1. Ouvrir le dépôt sur GitHub.
2. Cliquer sur **Add file → Upload files**.
3. Glisser le nouveau `index.html`, ainsi que les nouvelles images dans `img/` s'il y en a. Les fichiers qui portent le même nom sont remplacés.
4. Cliquer sur **Commit changes**.

Vercel republie le site automatiquement, en moins d'une minute.

### Modifier un texte rapidement

Ouvrir `index.html` sur GitHub et cliquer sur le crayon ✏️ pour l'éditer. Chaque texte existe en deux versions, une en français et une en anglais :

```html
<span class="fr">Texte en français</span><span class="en">English text</span>
```

Penser à modifier les deux, puis cliquer sur **Commit changes**.

### Changer une photo

Remplacer le fichier dans `img/` par une nouvelle image **portant exactement le même nom**, par exemple `team-victor.jpg`. Format recommandé : JPEG d'environ 1600 px de large au maximum, et moins de 400 Ko si possible.

## Hébergement

- **GitHub :** stocke les fichiers et garde l'historique de toutes les modifications.
- **Vercel :** met le site en ligne à chaque modification. Réglages : Framework Preset **Other**, sans commande de build.
- **Domaine :** à brancher dans Vercel → Settings → Domains.

## Crédits

- Photos : Antho, Doriane et l'équipe
- Dessins du carnet : Antho, col Akshayuk
- Écriture des étiquettes : Doriane
