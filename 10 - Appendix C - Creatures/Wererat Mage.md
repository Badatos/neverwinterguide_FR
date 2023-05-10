---
name: Magicien Rat-garou
slug: wererat-wizard-page
---

```Monster {.two-column}
name: Magicien Rat-garou
slug: wererat-wizard
size: Taille M
type: Humanoïde
alignment: Loyal Mauvais
ac: 12 (15 avec armure de mage)
hp: 49 (11d8)
speed: 9m
str: 9
dex: 14
con: 11
int: 17
wis: 12
cha: 11
saves: Int +6, Wis +4
skills: Arcanes +6, Histoire +6
damageImmunities: contondant, perforant et tranchant d’attaques non magiques qui ne sont pas en argent
senses: vision dans le noir 18m, Perception passive 11
languages: commun + 2 langues au choix et Jargon des voleurs (mais ne peut pas parler sous forme de rat)
challenge: 5
environments: Urbain
traits:
  - name: Odorat aiguisé
    description: Le rat-garou a un avantage aux jets de Sagesse (Perception) basés sur l’odorat.
actions:
  - name: Explosion arcanique (forme humanoïde ou hybride uniquement)
    description: "Attaque au corps à corps ou à distance avec un sort : +6 au toucher, allonge 1,50m ou portée 36m, une cible. *Touché* : 19 (3d10 + 3) dégâts de force."
  - name: Morsure (forme de rat ou hybride uniquement)
    description: "Attaque au corps à corps avec une arme : +5 au toucher, allonge 1,50 m, une cible. *Touché* : 4 (1d4 + 2) dégâts perforants. Si la cible est un humanoïde, elle doit réussir un jet de sauvegarde de Constitution DD 11 ou être atteinte de la lycanthropie de rat-garou."
  - name: Incantation (forme humanoïde ou hybride uniquement)
    description: "Le rat-garou lance l’un des sorts suivants, en utilisant l’Intelligence comme capacité d’incantation (jet de sauvegarde contre ses sorts DD 14) :

        * À volonté : <i>Lumières dansantes</i>, <i>Main de mage</i>, <i>Prestidigitation</i>

        * 2/jour chacun: <i>Boule de feu</i>, <i>Armure de mage</i>, <i>Serviteur invisible</i>, <i>Tempête de grêle</i>"
bonus-actions:
  - name: Métamorphose
    description: Le rat-garou se change en un hybride rat-humanoïde ou en rat géant, ou reprend sa forme véritable (la forme humanoïde). Mise à part sa taille, ses statistiques sont les mêmes quelle que soit sa forme. L’équipement qu’il porte ou transporte ne se transforme pas. Il retrouve sa forme véritable s’il meurt.
image: WereratMage.jpg
token: WereratMageToken.png
column-after: actions
column-after-property: Morsure (forme de rat ou hybride uniquement)
```
