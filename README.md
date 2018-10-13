# OpenMapTiles Geo.data.gouv.fr

Geo.data.gouv.fr rattaché à [Etalab](https://www.etalab.gouv.fr) a mis récemment en place un serveur de tuiles vectoriel utilisant le [projet OpenMapTiles](https://openmaptiles.org)

Il s'est avéré à travers [des échanges sur Twitter](https://twitter.com/jdesboeufs/status/1004995399273385985) qu'il serait intéressant de documenter comment consommer les tuiles vecteur de ce serveur. Ce dépôt constitue une amorce pour cela.

## Exemples

Vous trouverez les exemples chacun dans son répertoire pour chacune des librairies JavaScript principale existante.

* [démo Mapbox GL JS](https://raw.githack.com/webgeodatavore/openmaptiles-geo-data-gouv-fr/master/mapbox-gl-js/mapbox-gl-js-openmaptiles.html) Elle prend le style natif fourni

* [démo OpenLayers](https://raw.githack.com/webgeodatavore/openmaptiles-geo-data-gouv-fr/master/openlayers/openlayers-openmaptiles.html) Elle prend le style Mapbox JSON JS mis à disposition et les convertit à la volée en style OpenLayers.

* [démo Tangram](https://raw.githack.com/webgeodatavore/openmaptiles-geo-data-gouv-fr/master/tangram/tangram-openmaptiles.html). Attention, ce dernier dispose en plus d'un fichier de style minimaliste spécifique à Tangram appelé `scene.yaml` car il n'est pas possible de réutiliser les styles OpenMapTiles dans Tangram directement


## Crédits

La majorité des crédits sont à donner aux exemples [du site OpenMaptile.org](http://openmaptiles.org)

Nous ne représentons pas Etalab bien qu'utilisant leur service en le documentant.

## Contribuer

Pour contribuer, ouvrez [une "issue"](https://github.com/webgeodatavore/openmaptiles-geo-data-gouv-fr/issues/new) (jargon pour remonter une erreur ou une demande d'améliorations) pour discuter ou une "Pull Request" (raccourci sous le nom PR souvent qui est réservé à des gens qui savent comment contribuer au code/la documentation sur Github)
