# d2-rpg-system

## L'objectif
Fournir un système de jeu simple, pour organiser des parties de jeu de rôle improvisées, sans avoir prévu de materiel dédié.

Vous n'avez pas forcément toujours des dés à portée de main, encore moins des dés autre qu'a 6 face. pas forcément non plus de jeu de carte, en revanche, sur les quelques personnes qui veulent jouer avec vous, il est peu probable qu'aucune n'ai quelques picèes qui traine au fond d'une poche ou d'un sac.

## Le materiel

- Quelques pièces de monnaie (ou n'importe quoi qui par une action simple permet de déterminer un état parmi deux, avec environ 50% de chance d'avoir chaque état, des jetons bicolor, des dominos, des CD, des bou de papier déchirés avec une marque d'un coté...)
- De quoi écrire (le doigt dans la poussière du sol ou sur du sable, ça peut suffir, ou un stylo dans le creux de la main ou...)

Si vous n'avez qu'une seule pièce (ou élément assimilé) c'est moins pratique, mais vous pouvez faire des lancés successifs.
Pour la suite, nous nommerons les pièces ou assimilé des D2 et plutôt que **pile ou face**, ce sera **réussite ou échec**.


## Principe de base

Quand une action nécessite un jet de dé, en tant que MJ, choisissez une difficulté en nombre de réussite.
Selon les caractéristiques du lanceur, (éventuellement accompagné d'un bonus de compétence ou de situation), il lance un certain nombre de D2.
S'il fait suffisement de réussite, c'est réussi. Sinon c'est raté. (Vous pouvez ajuster le degré de réussite ou d'échec à l'écart à la difficulté que vous aviez défini en tant que MJ).

### Fumble et explosion

Si vous aimez les fumbles (échec critique) et les explosion de dé (réussite critique), deux options :
- Soit vous considérez qu'un réusultat inferieur de 3 au nombre de réussite nécessaire est un échec critique, ou superieur de 3 une réussite critique...
- Soit vous aimez réduire les chance de fumble avec la maitrise et augmenter les réussite critique de la même façon et je vous propose ce système :

Si un lancé ne donne aucune réussite, c'est un fumble (ainsi, plus on lance de D2, moins on a de chance de faire de fumble)
Si un lancé donne au moins 3 réussite, compté les réussite et relancer les D2 sauf 3. Additionnez les nouvelles réussites, et s'il y en a au moins 3, refaite de même...

**Exemple 1 :**
Je lance 9 D2.
Je fais 4 réussites.
Je relance donc 9-3 : 6 dés.
Je fais 3 réussites.
Je relance donc 6-3 : 3 dés.
Je fais 3 réussites.
Je relance donc 3-3 : 0 dés...
J'ai donc totalisé 10 réussites.

**Exemple 2 :**
Je lance 9 D2.
Je fais 2 réussites.
Je ne relance pas.
J'ai donc totalisé 2 réussites.

**Exemple 3 :**
Je lance 9 D2.
Je fais 0 réussites.
C'est un fumble !

**Exemple 4 :**
Je lance 9 D2.
Je fais 9 réussites.
Je relance donc 9-3 : 6 dés.
Je fais 6 réussites.
Je relance donc 6-3 : 3 dés.
Je fais 3 réussites.
Je relance donc 3-3 : 0 dés...
J'ai donc totalisé 18 réussites. (le maximum atteignable avec 9 d2, même en explosant au max)

[Variantes](https://github.com/GammaNu/d2-rpg-system/wiki/variante-explosions)

## Ordre de grandeur

Réussir quelquechose de trivial ne nécessite normalement pas de jet de dé. (Si par le contexte, vous voulez qu'un dé soit lancé, considéré que c'est uen action simple)
Une action simple : 1 réussite
Une action normal (ou complexe mais pas difficile) : 2 réussites
Une action difficile : 3 réussite.
Une action improbable/extraordinaire : 4 réussites.
Une action impossible sans quelquechose d'extra-ordinaire (talent, contexte...) : 5 réussites.
Plus de 6 réussites : C'est pas humain... Mais si votre scénario non plus, tout va bien.

## Fiche perso

A vous de choisir de caractérisitque si vous voulez en mettre explicitement, des compétences etc...

Pour simplifier je recommande une autre approche :
- Considérer que tous personnage à une base de 2 (donc lance 2 D2 pour faire quelquechose sans rapport particulier avec le personnage.
- Considérer que chaque personnage à un domaine principal (métier à +2) et deux domaines secondaires (hobby à +1)
- Considérer qu'un jeune classique est plus vif +1 pour les actions physique, à des sens plus aigue +1, mais moins de connaissance -1.
- Considérér qu'un jeune geek n'a pas de bonus physique, mais à le bonus de sens +1 et pas de malus de connaissance (s'il doit avoir des bonus de connaissance, c'est via son domaine principal ou ses domaines secondaire).
- Considérer qu'un vieux à un malus -1 pour ce qui est physique (moduler l'étendu des domaines physique selon l'age), à un malus coté sens, mais généralement compensé par l'experience pour identifier ce que signifie ce qu'il perçoit. Et un bonus en connaissance de +1 (moduler le spectre de connaissance selon l'age)


## Combat

Coté point de vie, survie et assimilé, ça dépend beaucoup du style de votre univers.

Ce que je propose :
- L'attaquant fait un jet d'attaque, le défenseur fait un jet de défense s'il est en condition d'esquiver/parer activement et retranche son résultat au jet d'attaque.
- Selon l'équilibrage, vous pouvez choisir d'ajouter une défense passive lié aux caractéristiques + armure ou non.
- Si après avoir retranché la défense, le nombre de réussite à l'attaque est positif ou nul, la cible est touchée.

**Degré de blessure selon le nombre de réussite de marge :**
- 0 : blessure bénine (ça peux s'infecter et devenir plus grave, mais ça n'handicape en rien sur le moment)
- 1 : blessure douloureuse (malus (-1) au membre touché et au moral / à la motivation)
- 2 : blessure profonde (cas précédent avec malus à 2, et le membre gardera des séquelles durable à moins d'être remarcablement bien soigné)
- 3 : blessure grave (membre sectionné, poison foudroyant à effet immédiat (mais non létal à l'instant), tombé inconscient...) (si localisé à la tête, mort probable)
- 4 : tête ou torse -> mort immédiate, sinon considérer une marge de 3 pour les dégats physique (pour les poisons et autre à effet global... dommage)
5 et plus : marge-4 réussites à la localisation.

**Localisation des dégats :**
La cible lance 3 D2.
- 0 réussite : tête
- 1 réussite : tronc
- 2 ou 3 réussites : un membre auxilière déterminé comme suit pour un humanoïde : 1 D2 -> réussite jambe échec bras. 1 second D2 -> réussite : gauche, échec droit.

Si une armure hétérogène est à prendre en compte (pas de casque par exemple), on lance la localisation avec de calculer la marge de réussite pour la gravité des blessures (la marge dépendra de l'armure local).

Si l'attaquant veux faire une attaque ciblé précisément, son attaque augmente en difficulté d'1 ou 2 selon la difficulté d'atteindre la zone souhaité. Lors de la localisation, la zone souhaité est touché sur 2 et 3 réussite, une zone voisine sur 1 réussite, et une localisation standard est lancé sur 0 réussite.

