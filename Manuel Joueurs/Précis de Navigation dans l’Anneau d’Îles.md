---
tags:
  - Règles
  - Navigation
---
> _Cours de marine orbitale appliquée
## I — Principes fondamentaux de l’Anneau

L’Anneau d’Îles n’est ni une mer plate, ni un océan ouvert.  
C’est une couronne mobile, en rotation autour d’un noyau infranchissable, où chaque île suit une orbite propre.

Trois vérités doivent être gravées dans l’esprit de tout navigateur :

1. On ne traverse pas l’Anneau, on le suit.  
    La navigation sûre est tangentielle, le long de la couronne.
    
2. La distance ne se mesure pas en lieues, mais en degrés.  
    Toute navigation se lit en angles, pas en kilomètres.
    
3. La mer n’est pas immobile.  
    Les îles avancent, fuient ou reviennent selon leur vitesse de constellation.
    
## II — Le repère de navigation (système en degrés)

Toute position dans l’Anneau est définie par trois paramètres :
### 1. θ — Position angulaire (0°–360°)

- Position de l’île sur la couronne, vue depuis le noyau.
- La distance principale entre deux îles est :
    - Δθ, l’écart angulaire minimal (0° à 180°).

👉 Δθ détermine le temps de base du voyage.
### 2. ρ — Profondeur dans l’Anneau (0°–90°)

- ρ = 0° : bord intérieur (vers la mer centrale)
- ρ = 90° : bord extérieur (vers les zones instables)

On distingue trois bandes de navigation :

- Intérieure (0–30°)
- Médiane (30–60°)
- Extérieure (60–90°)

👉 Δρ ne décrit pas une route, mais une contrainte :  
changer de bande force des détours dangereux, car les champs de mer répulsifs s’opposent aux mouvements radiaux.
### 3. v — Vitesse de constellation (tours/an)

Chaque constellation d’îles a une vitesse orbitale fixe.  
Exemples : 0.8, 1.0, 1.3, 1.5 tours/an.

👉 Δv (écart de vitesse) transforme un trajet en :

- poursuite,
- interception,
- ou rendez‑vous favorable.
## III — Carte contre mer : deux lectures du voyage

### 1. Le temps cartographique (la carte seule)

À partir de Δθ uniquement, on obtient un temps de base :

|Δθ|Temps de base|
|---|---|
|0–15°|~1 semaine|
|15–40°|2–3 semaines|
|40–80°|1–2 mois|
|80–140°|3–6 mois|
|>140°|expédition|
👉 C’est ce que promet le parchemin.
### 2. Le temps marin réel (la mer en mouvement)

Le temps réel est ajusté par :

- Δρ : détours imposés par la profondeur,
- |Δv| : difficulté d’interception orbitale,
- Rendez‑vous :
    - _devant + plus rapide_ → elle fuit,
    - _derrière + plus rapide_ → elle revient,
    - _devant + plus lente_ → on rattrape.

👉 Ainsi, un trajet peut être :

- court en angle,
- mais long en semaines.

> _La carte mesure la distance.  
> La mer mesure la patience._

## IV — La Difficulté de Route (DR)

La navigation n’est pas qu’une question de temps.  
Elle est aussi une question de risque.

### DR — Difficulté de Route

DR est un indice synthétique qui mesure :

- la complexité du trajet,
- la probabilité de complications,
- la tension du voyage.

DR se calcul ainsi :

- Dθ (écart angulaire) 
	- divisé par 15 arrondi au supérieur. Donc 42° donne +3 en DR.
- Dρ (contrainte radiale)
	-  +3 par rang, exemple intérieur vers extérieur : +6
- Dv (écart de constellation)
	- +2 par rang
- Drdv (qualité du rendez‑vous).
	- Le point d'arrivé fuit : +5
	- Le point vient vers nous : -5
	- On rattrape : +0

👉 DR ≠ temps.  
DR dit _comment_ le voyage se passe, pas _combien de semaines il dure_.

### Usage JdR de DR

- Jets de navigation  
    Exemple (d20) :  
    `DC = 10 + 2 × DR`
    
- Complications narratives
    
    - DR faible → voyage propre
    - DR moyen → retard, tension, usure
    - DR élevé → dérive, événement majeur, perte
## V — Règle d’or de la navigation dans l’Anneau

### Navigation sûre

- Suit la couronne,
- Accepte les détours,
- Respecte les vitesses orbitales.

### Navigation forcée (radiale)

- Coupe vers le noyau ou l’extérieur,
- Très rapide, mais extrêmement dangereuse,
- Hors des cartes,
- Domaine des fous, des désespérés et des légendes.

> _Sortir de l’Anneau n’est pas une route.  
> C’est une chute._
## VI — Lecture d’un résultat type (exemple canon)

```
Δθ = 12° (devant)
Δρ = 10° (médiane → médiane)
Δv = +0.4
DR = 5 → proche ; rendez‑vous défavorable
Temps : base ~1 semaine ; ajusté ~3.8 semaines
```

Lecture correcte :

- Proche sur la carte,
- Même bande → navigation tangentielle,
- Mais l’île est devant et plus rapide,
- Le voyage devient une interception,
- La mer transforme une semaine promise en près d’un mois réel.
## VII — Schéma mental à transmettre aux joueurs

> Δθ dit combien de degrés.  
> Δρ dit combien la mer résiste.  
> Δv dit si l’île fuit ou revient.  
> DR dit si le voyage sera paisible ou chaotique.
## VIII — Conclusion (enseignement du cartographe)

> _« Sur l’Anneau, la distance est une question d’angle,  
> le temps une question de vitesse,  
> et le danger une question d’orgueil.  
> Celui qui confond la carte et la mer  
> apprend vite pourquoi les îles dérivent seules. »_