# brief

Ce dépôt ne contient **que le site construit** du brief projet de VigieChiro Companion, publié sur <https://brief.echonuit.fr/> depuis la branche `gh-pages`.

Il n'y a rien à modifier ici : la branche `gh-pages` est écrasée à chaque publication.

## Où sont les sources

Dans le dépôt du produit, [`echonuit/vigiechiro-pr-companion`](https://github.com/echonuit/vigiechiro-pr-companion), sous [`brief/`](https://github.com/echonuit/vigiechiro-pr-companion/tree/main/brief). La conception y vit à côté du code qu'elle décrit, avec le guide utilisateur (`docs/`) et la documentation développeur (`dev-docs/`) ; une évolution qui touche à la fois le produit et sa conception ne demande plus deux mises à jour dans deux dépôts.

L'historique d'origine y a été conservé : `git log -- brief/` montre les 129 commits du 11 mai au 22 juillet 2026, avec leurs auteurs et leurs messages. Les issues ont été transférées vers ce même dépôt.

Toute correction du brief passe donc par une pull request sur `echonuit/vigiechiro-pr-companion`, et la publication ici est automatique.

## Les autres dépôts de publication

| Dépôt | Site |
|---|---|
| [`echonuit/companion`](https://github.com/echonuit/companion) | [companion.echonuit.fr](https://companion.echonuit.fr/) - guide utilisateur |
| [`echonuit/companion-dev`](https://github.com/echonuit/companion-dev) | [companion-dev.echonuit.fr](https://companion-dev.echonuit.fr/) - documentation développeur |
