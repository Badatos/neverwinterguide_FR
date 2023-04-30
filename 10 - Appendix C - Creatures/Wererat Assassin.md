---
name: Assassin Rat-garou
slug: wererat-assassin-page
---

```Monster {.two-column}
name: Assassin Rat-garou
slug: wererat-assassin
size: Taille M
type: Humanoïde
alignment: Loyal mauvais
ac: 16 (Cuir clouté)
hp: 75 (9d10 + 26)
speed: 9m
str: 11
dex: 18
con: 14
int: 11
wis: 11
cha: 12
saves: Dex +7, Int +3
skills: Perception +3, Discrétion +7
damageImmunities: contondant, perforant et tranchant d'attaques non magiques qui ne sont pas en argent
senses: vision dans le noir 18m, Perception passive 13
languages: commun, Jargon des voleurs (mais ne peut pas parler sous forme de rat)
challenge: 4
environments: Urbain
traits:
  - name: Odorat aiguisé
    description: Le rat-garou a un avantage aux jets de Sagesse (Perception) basés sur l'odorat.
actions:
  - name: Attaques multiples (forme humanoïde ou hybride uniquement)
    description: "Le rat-garou effectue 3 attaques, une seule peut être une attaque de morsure."
  - name: Dague (forme humanoïde ou hybride uniquement)
    description: "Attaque au corps à corps avec une arme : +6 au toucher, allonge 1,50 m, une cible. *Touché* : 6 (1d4 + 4) dégâts perforants."
  - name: Arbalète de poing (forme humanoïde ou hybride uniquement)
    description: "Attaque à distance avec une arme : +6 pour toucher, portée 9/36 m, une cible. *Touché* : 7 (1d6 + 4) dégâts perforants."
  - name: Morsure (forme de rat ou hybride uniquement)
    description: "Attaque au corps à corps avec une arme : +6 au toucher, allonge 1,50 m, une cible. *Touché* : 6 (1d4 + 4) dégâts perforants. Si la cible est un humanoïde, elle doit réussir un jet de sauvegarde de Constitution DD 11 ou être atteinte de la lycanthropie de rat-garou."
bonus-actions:
  - name: Métamorphose
    description: Le rat-garou se change en un hybride rat-humanoïde ou en rat géant, ou reprend sa forme véritable (la forme humanoïde). Mise à part sa taille, ses statistiques sont les mêmes quelle que soit sa forme. L'équipement qu'il porte ou transporte ne se transforme pas. Il retrouve sa forme véritable s'il meurt.
reactions:
  - name: Esquive instinctive
    description: "Le rat-garou réduit de moitié les dégâts d'une attaque qui le touche. Il doit pouvoir voir son attaquant."
image: WereratAssassin.jpg
token: WereratAssassinToken.png
column-after: actions
```
