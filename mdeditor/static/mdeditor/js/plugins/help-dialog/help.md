# Markdown - tutoriel

## Syntaxe de base

Vous trouverez dans l'url suivante un documentation de la syntaxe markdown commune à la pluspart des éditeurs :

[Syntaxe markdown](https://guides.github.com/features/mastering-markdown/ "Mastering Markdown")

## Syntaxe additionnelle

Cette syntaxe est spécifique au site Brahms / Analyse / Sidney. Le rendu de cette syntaxe se fera côté front, après avoir enregistré le contenu en question.


#### Lien vers un compositeur/trice:

`[composer: XXX]` | XXX: id du compositeur/trice

#### Lien vers une oeuvre

`[work: XXX]` | XXX: id de l'oeuvre

#### Lien vers une note en bas de page

Placer la balise `[^label]` en remplaçant 'label' par un identifiant que vous souhaitez.
Mettez exactement la même balise en bas de page :
`[^label]: suivis de sa description`

#### Lien vers une 'flat' page

`[page: XXX]` | XXX: id de la flat page

#### Lien vers une définition

`[definition: XXX]` | XXX: id de la definition

#### Afficher une image :

`[image: XXX]` | XXX: id de l'image

#### Afficher un player audio

`[sound: XXX]` | XXX: id du fichier son

#### Afficher un player video

`[video: XXX]` | XXX: id du fichier video
