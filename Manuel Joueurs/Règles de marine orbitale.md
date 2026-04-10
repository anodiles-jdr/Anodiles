---
tags:
  - Règles
  - Navigation
---
## 1. Principes généraux

La navigation dans l’Anneau d’Îles ne se résout ni par un jet unique, ni par un simple calcul de distance.

Un voyage est une lutte progressive entre :

- la route promise par la carte,
- et la résistance réelle de la mer orbitale.

Cette résistance est représentée par la Difficulté de Route (DR).  
Le voyage progresse semaine après semaine, jusqu’à ce que les navigateurs aient “vaincu” la DR.

---

## 2. La Difficulté de Route (DR)

La DR mesure :

- la complexité du trajet,
- la résistance des courants,
- la difficulté d’interception orbitale,
- et le risque global du voyage.

👉 La DR n’indique pas le temps.  
👉 Elle indique ce qu’il faut surmonter pour arriver.

### Calcul de la DR

La DR est la somme de quatre composantes :

---

### Dθ — Écart angulaire

Mesure la distance sur la couronne de l’Anneau.

Calcul :

- DR += ⌈Δθ / 15⌉

Exemples :

- 12° → +1 DR
- 30° → +2 DR
- 42° → +3 DR
- 75° → +5 DR

📌 Dθ représente la longueur de route, pas sa difficulté intrinsèque.

---

### Dρ — Contrainte radiale (profondeur)

Mesure le changement de bande dans l’Anneau.

- Même bande → +0
- Bande adjacente → +3
- Intérieure ↔ extérieure → +6

📌 Dρ représente la résistance des champs de mer répulsifs.  
La navigation reste tangentielle, mais la mer pousse et détourne.

---

### Dv — Écart de constellation

Mesure la différence de vitesse orbitale entre départ et arrivée.

- Par rang d’écart → +2 DR

Exemples :

- Constellations voisines → +2
- Écart moyen → +4
- Écart fort → +6

📌 Dv représente la difficulté à viser un rendez‑vous orbital.

---

### Drdv — Qualité du rendez‑vous

Mesure la dynamique relative entre le navire et l’île cible.

- Le point d’arrivée fuit (devant + plus rapide) → +5 DR
- Le point vient vers nous (derrière + plus rapide) → −5 DR
- On rattrape (devant + plus lente) → +0 DR

📌 Drdv est un modificateur majeur :  
la même route peut devenir triviale ou infernale selon le sens du monde.

---

## 3. Résoudre un voyage : jets cumulés

### Principe

Un voyage est résolu semaine par semaine.

Chaque semaine :

1. Le capitaine effectue un jet de navigation.
2. Le résultat est ajouté à une progression cumulée.
3. Lorsque la progression cumulée atteint ou dépasse la DR, le voyage est terminé.

---

### Le jet hebdomadaire

#### Dé de navire

Selon la qualité et la vitesse du navire :

|Type de navire|Dé|
|---|---|
|Canot, radeau|d2|
|Navire lent, ancien|d4|
|Navire standard|d6|
|Navire rapide / optimisé|d8|

📌 Le dé représente la capacité du navire à maintenir une trajectoire utile dans les courants orbitaux.

---

#### Bonus de capitaine

Ajoute un bonus fixe selon l’expérience du capitaine :

- Inexpérimenté → +0
- Capitaine confirmé → +1
- Maître‑pilote → +2
- Légende vivante → +3

📌 Le capitaine réduit l’incertitude, il ne nie pas la mer.

---
### Échec critique de navigation

La navigation dans l’Anneau est une lutte progressive.  
Même une bonne manœuvre répétée peut devenir dangereuse si la mer se referme.

#### Déclenchement d’un échec critique

Un échec critique survient lorsque :

> Trois jets hebdomadaires affichent exactement le même résultat total  
> (dé du navire + bonus du capitaine),  
> quels que soient leurs effets positifs ou négatifs.

- Les jets n’ont pas besoin d’être consécutifs.
- Le total considéré est le résultat final, après bonus.
- L’échec critique peut survenir même si la progression est bonne.

📌 Exemple :

- Semaine 1 : 5
- Semaine 3 : 5
- Semaine 6 : 5  
    → Échec critique déclenché, même si la DR est presque atteinte.

---

#### Interprétation fictionnelle

- La mer “a compris” la manœuvre.
- Le navire est entré dans une résonance orbitale défavorable.
- Les élémentaires s'invitent dans votre voyages.
- Les mêmes choix produisent désormais des effets amplifiés.

> _« Ce n’est pas que la manœuvre était mauvaise.  
> C’est qu’elle a été répétée trop longtemps. »_
### Progression

```
Progression += (dé de navire + bonus de capitaine)
```

Quand :

```
Progression ≥ DR
```

👉 Le navire arrive à destination.

---

## 4. Temps de voyage

Le temps réel du voyage est le nombre de semaines écoulées avant d’atteindre la DR.

La carte donne une attente (Δθ).  
La mer impose la réalité (DR + jets).

Ainsi :

> _« La carte promet une semaine.  
> La mer en réclame quatre. »_

---

## 5. Modificateurs optionnels de DR (avant le voyage)

Ces modificateurs ajustent la DR initiale.

### Conditions environnementales

- Mer calme / alignement parfait → −2 DR
- Saison instable → +2 DR
- Anomalie orbitale connue → +3 DR

### Routes et informations

- Route cartographiée → −1 DR
- Route secrète connue → −2 DR
- Route non cartographiée → +2 DR

### Politique et pression

- Escorte alliée → −1 DR
- Zone hostile → +2 DR
- Blocus ou poursuite → +3 DR

---

## 6. Modificateurs optionnels aux jets hebdomadaires

Ces modificateurs s’appliquent chaque semaine.

### État du navire

- Navire endommagé → −1 au jet
- Navire parfaitement entretenu → +1
- Coque magique / stabilisée → +1

### Équipage

- Équipage fatigué → −1
- Équipage discipliné → +1
- Mutinerie latente → −2

### Décisions du capitaine

- Manœuvre prudente → −1 DR restant (1 fois)
- Manœuvre risquée → +1 au jet, mais événement en cas d’échec
- Sacrifice matériel → +2 au jet (conséquence durable)

---

## 7. Événements hebdomadaires (optionnel mais recommandé)

- Jet minimal naturel sur le dé du navire :
    - pas de progression cette semaine,
    - complication mineure.
- Jet exceptionnel (dé max + bonus ≥ 10) :
    - progression doublée cette semaine,
    - ou réduction immédiate de la DR restante de 2.

---

## 8. Sortir de l’Anneau (règle canonique)

Si :

- Dρ ≥ 2 rangs et
- DR ≥ 15

Alors le MJ peut déclarer :

> _« Cette route sort de l’Anneau.  
> Elle est rapide.  
> Elle est extrêmement dangereuse. »_

La résolution devient narrative, avec risques majeurs, pertes possibles, ou conséquences irréversibles.

---

## 9. Lecture synthétique pour les joueurs

> Δθ dit combien de degrés.  
> DR dit combien la mer résiste.  
> Les jets disent combien de semaines passent.

---

## 10. Conclusion (texte in‑world)

> _« Naviguer dans l’Anneau n’est pas aller d’un point à un autre.  
> C’est convaincre le monde de vous laisser passer.  
> Chaque semaine gagnée est une victoire,  
> et chaque degré arraché à la mer est une promesse tenue. »_