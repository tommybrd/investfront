# InvestFront (alpha)

Jeu de gestion par navigateur : vous êtes investisseur et vous prenez des parts dans les commerces de France.

**Jouer :** https://tommybrd.github.io/investfront/

- Carte de France réelle (OpenStreetMap), environ 1 200 commerces fictifs dans 63 villes, 16 secteurs. La région Centre-Val de Loire (Blois, Tours, Orléans et alentours) est plus dense.
- Chaque commerce a son chiffre d'affaires, sa marge, sa valorisation, comparés à la moyenne de son secteur.
- Achat de parts, dividendes trimestriels, prêts bancaires selon vos capacités.
- Immobilier : locaux commerciaux, immeubles, bureaux, entrepôts et terrains à acheter (comptant ou à crédit), louer, rénover ou bâtir.
- Holding : fiscalité allégée et équipe à embaucher (opérations, fiscaliste, analyste, directeur financier, gestionnaire immobilier).
- Actualités, conjoncture, faillites, vitesse du jeu réglable, sauvegarde dans le navigateur.

Tout le jeu tient dans `index.html` (HTML, CSS et JavaScript, sans étape de build). La carte utilise
[Leaflet](https://leafletjs.com/) et les tuiles © les contributeurs d'[OpenStreetMap](https://www.openstreetmap.org/copyright).
Les entreprises, leurs noms, leurs gérants et leurs chiffres sont inventés.
