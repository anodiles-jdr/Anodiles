Tu travailles sur un projet de worldbuilding, de roman et de jeu de rôle basé sur une chaîne éditoriale Markdown.

PRINCIPES GÉNÉRAUX

- Le dépôt contient plusieurs univers.
- Les contenus sont atomiques : un fichier Markdown correspond à une seule unité documentaire.
- Les contenus sont destinés à être assemblés ultérieurement dans différentes publications (roman, bestiaire, atlas, livre de base, campagne, site web, PDF).
- Le contenu source est plus important que la publication finale.
- Le système est conçu pour rester portable et durable dans le temps.

PHILOSOPHIE

- Ne pas transformer le dépôt en wiki sémantique.
- Ne pas créer de graphes complexes.
- Ne pas ajouter de backlinks artificiels.
- Les métadonnées servent uniquement à classer, filtrer, sélectionner et compiler.
- Les métadonnées ne doivent pas devenir une base de connaissances du monde.
- Le contenu du monde doit rester dans les fichiers Markdown.

STRUCTURE

Les contenus sont rangés dans quelques dossiers métier simples :

- creatures
- places
- factions
- objects
- testimonies
- periods
- events
- scenarios
- rules
- editorial
- notes

Les dossiers servent à retrouver rapidement les documents.

Les métadonnées servent à filtrer les documents.

MÉTADONNÉES

Les clés sont toujours en anglais.

Exemples :

---
title: Dvat
type: creature
slug: dvat
period: republic
origin: demonocracy
editorial-state: canonical
---

Règles :

- type décrit la nature du document.
- slug représente le concept métier.
- period permet les filtrages temporels.
- origin permet les regroupements métiers.
- editorial-state indique si le document doit être retenu dans les publications.

Ne jamais ajouter de métadonnées inutiles.

Éviter notamment :

- theme
- mood
- keywords
- relations
- backlinks
- statistiques dérivées

sauf demande explicite.

TYPES

Exemples de types :

- creature
- place
- faction
- object
- testimony
- event
- period
- scenario
- rule

Types éditoriaux :

- anecdote
- did-you-know
- design-note
- gm-advice
- author-note
- example-of-play
- lore-fragment

LANGUES

Les métadonnées restent en anglais.

Le contenu peut exister dans plusieurs langues.

Le slug reste stable quelle que soit la langue.

HIÉRARCHIE MARKDOWN

Chaque fichier est autonome.

Toujours commencer par :

# Titre

Les sections internes utilisent :

## Section

### Sous-section

Ne jamais adapter les niveaux de titre en fonction d'une future compilation.

La compilation gère elle-même la hiérarchie globale.

OBJETS ÉDITORIAUX

Les contenus spéciaux utilisent des directives :

::: {.gm-summary}
...
:::

::: {.did-you-know}
...
:::

::: {.design-note}
...
:::

Ces blocs représentent une intention éditoriale et non une mise en page.

PRÉSENTATION

Le Markdown ne doit pas contenir :

- de HTML de mise en page
- de <br>
- de styles
- de CSS

Le rendu est géré par les templates et les feuilles de style.

IMAGES

Les images sont associées au contenu mais ne sont généralement pas référencées directement dans le markdown.

La mise en page décide :

- quelle image utiliser
- où l'insérer
- à quelle taille

PUBLICATIONS

Les contenus sont compilés via des manifestes.

Une publication sélectionne et assemble les contenus.

Exemples :

- livre-base
- bestiaire
- atlas
- roman
- campagne

Les documents ne doivent jamais contenir de logique de publication spécifique.

IA

Les IA doivent considérer chaque fichier comme un fragment documentaire réutilisable.

Elles peuvent :

- enrichir
- résumer
- traduire
- dériver
- produire des variantes

sans modifier la philosophie générale :

fragments atomiques → compilation → publication.