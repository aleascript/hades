### A propos des résultats des résolutions par les dés

* Résultats concernant l'objectif:
    - **OUI**: l'objectif annoncé est réalisé. 
    - **oui**: l'objectif annoncé est partiellement réalisé ou concrètement la Destinée peut demander à choisir entre plusieurs options. 
    - **NON**: l'objectif annoncé est réalisé et c'est définitif. 
    - **non**: l'objectif annoncé n'est pas atteint mais ce n'est pas définitif.   
* Résultats concernant un gain ou une perte: 
    - **bénéfice**: se traduit par un avantage, un trait, une jauge ou autre...
    - **préjudice**: se traduit par un handicap, un trait, une jauge ou autre...
* Résultats concernant la fiction:
    - **difficulté**: la Destinée ajoute une difficulté. 
    - **opportunité**: la Destinée ajoute une opportunité qui se traduit par un avantage souvent.     
    

Et donc: 

| Différence | Résultats |
|:----------:|-----------|
| -3 | * NON + préjudice<br>*  non + préjudice + préjudice + difficulté |
| -2 | * NON<br>* non + préjudice + difficulté |
| -1 | * non + difficulté |
| +1 | * OUI + préjudice<br>* oui <br>* non + opportunité |
| +2 | * OUI<br>* OUI + bénéfice + préjudice |
| +3 | * OUI + bénéfice |

Les différents résultats sont dans la main de la Destinée. Il peut proposer des options mais c'est lui qui décide s'il y a lieu de proposer la fin de résolution ou pas ou s'il pense qu'à ce moment là ca serait bien de continuer. 

Evidemment à tout moment le protagoniste peut changer son objectif et c'est même souhaitable pour ne pas rendre le jeu monotone. 

### A propos du nommage des joueurs

Dans une 1ere version, j'ai été tenté de distinguer: 

* Les joueurs de protagonistes des protagonistes eux-mêmes (JP=Joueur de protagoniste) 
* Le joueur de la destinée de la destinée elle-même (JD=Joueur de la destinée).

J'ai finalement fusionné les termes pour éviter d'introduire une nouvelle sémantique un peu lourde. 
La Destinée est donc le joueur de la destinée et les Protagonistes sont les joueurs qui jouent les protagonistes ainsi que les protagonistes eux-mêmes pour favoriser l'immersion. En cas de distinguo (rare), il est facile de spécifier si c'est le  joueur du protagoniste ou le protagoniste lui-même. 

### Moteur de résolution

On a privilégié la version simple car elle est la plus fluide car chaque champ annonce simplement le nombre de pairs obtenus et le résultat est immédiat. Dans la version avancée, c'est moins fluide car en cas d'égalité, il faut compter les scores et cela ralentit la fiction par des calculs à la marge. 

Or le but du jeu n'est pas d'être un exercice de précision mais d'être orienté narration en restant plausible. 

Voici la version initiale qui était plus complexe en terme de calculs lors des égalités. 

**Jets de dés** (version avancée)

1. Chaque camp jette son pool de dés. 
2. Pour chaque 6 obtenu, on lance un dé supplémentaire (qui peut donner lieu à d'autres lancers en cas de 6). On appelle ces dés les dés du chaos. 
3. On compte ensuite le nombre de dés pairs obtenus dans chaque camp.
4. Le résultat est égal au nombre dés pairs du protagoniste moins le nombre de dés pairs de l'obstacle. 
5. En cas d'égalité des pairs, on additionne les valeurs des dés pairs de chaque camp. Si le protagoniste a un score supérieur ou égal à l'obstacle, il obtient un progrès (+1), sinon il subit un revers (-1).
6. S'il n'y a aucun pair, on additionne les valeurs des dés de chaque champ. Si le protagoniste a un score supérieur ou égal à l'obstacle, il obtient un progrès (+1), sinon il subit un revers (-1).

### Statistiques

Malgré son appartent simplicité, les statistiques apparaissent plutôt riches et intéressantes. 

* Statistiques du moteur de résolution 

|Protagoniste|Obstacle|Succes|Echec|-3|-2|-1|+1|+2|+3|Fortunes|
|---|---|---|---|---|---|---|---|---|---|---|
|1D|1D|46.466|53.534|0.0|4.171|49.363|42.328|4.138|0.0|0.0|
|2D|2D|59.287|40.713|2.175|9.441|29.097|47.495|9.583|2.209|4.384|
|3D|3D|60.764|39.236|5.213|11.472|22.551|44.232|11.278|5.254|10.467|
|4D|4D|60.522|39.478|8.08|12.116|19.282|40.057|12.342|8.123|16.203|
|5D|5D|59.932|40.068|10.691|11.988|17.389|36.875|12.359|10.698|21.389|
|6D|6D|58.656|41.344|12.983|12.126|16.235|33.701|11.92|13.035|26.018|
|7D|7D|58.299|41.701|14.87|11.759|15.072|31.78|11.757|14.762|29.632|
|8D|8D|57.463|42.537|16.442|11.65|14.445|29.739|11.411|16.313|32.755|
|1D|2D|35.658|64.342|4.052|15.852|44.438|33.521|2.137|0.0|2.137|
|2D|3D|44.907|55.093|8.803|17.083|29.207|38.05|5.706|1.151|6.857|
|3D|4D|47.173|52.827|13.044|16.519|23.264|36.547|7.511|3.115|10.626|
|4D|5D|48.382|51.618|15.784|15.749|20.085|34.603|8.702|5.077|13.779|
|8D|9D|48.464|51.536|23.486|13.202|14.848|27.266|9.179|12.019|21.198|
|2D|1D|71.471|28.529|0.0|2.0|26.529|51.581|15.74|4.15|2.0|
|3D|2D|74.206|25.794|1.202|5.691|18.901|48.579|16.824|8.803|6.893|
|4D|3D|73.015|26.985|3.158|7.618|16.209|44.005|16.493|12.517|10.776|
|5D|4D|71.163|28.837|5.165|8.409|15.263|39.67|15.502|15.991|13.574|
|9D|8D|65.815|34.185|12.097|9.438|12.65|29.434|13.181|23.2|21.535|
|1D|2D|35.61|64.39|4.088|15.775|44.527|33.479|2.131|0.0|2.131|
|1D|3D|24.558|75.442|14.694|24.011|36.737|23.514|1.044|0.0|1.044|
|1D|4D|16.158|83.842|28.85|26.786|28.206|15.65|0.508|0.0|0.508|
|1D|5D|10.218|89.782|44.388|24.911|20.483|9.96|0.258|0.0|0.258|
|1D|8D|2.153|97.847|79.409|12.356|6.082|2.104|0.049|0.0|0.049|
|2D|1D|71.568|28.432|0.0|2.097|26.335|51.636|15.729|4.203|2.097|
|3D|1D|84.865|15.135|0.0|1.011|14.124|46.27|23.744|14.851|1.011|
|4D|1D|91.931|8.069|0.0|0.534|7.535|36.179|26.61|29.142|0.534|
|5D|1D|95.788|4.212|0.0|0.28|3.932|26.217|25.068|44.503|0.28|
|8D|1D|99.412|0.588|0.0|0.024|0.564|7.678|12.477|79.257|0.024|

Il y a un léger avantage pour les protagonistes mais c'est assumé car ce sont eux les héros de l'histoire. 

La possibilité d'obtenir des fortunes augmentent plus il y a de dés dans les pools et cela reflète bien que c'est la complexité qui est pourvoyeuse d'expérience. 



* Statistiques du moteur de résolution en ne limitant pas les dés du chaos au 1er lancer. 

|Protagoniste|Obstacle|Succes|Echec|-3|-2|-1|+1|+2|+3|Fortunes|
|---|---|---|---|---|---|---|---|---|---|---|
|1D|1D|43.89|56.11|1.616|7.834|46.66|34.634|7.663|1.593|3.209|
|2D|2D|56.24|43.76|6.278|11.128|26.354|38.675|11.287|6.278|12.556|
|3D|3D|58.394|41.606|10.374|11.896|19.336|36.181|11.855|10.358|20.732|
|4D|4D|58.219|41.781|13.975|11.744|16.062|32.521|11.68|14.018|27.993|
|5D|5D|57.576|42.424|16.636|11.505|14.283|29.651|11.157|16.768|33.404|
|6D|6D|57.062|42.938|19.016|10.728|13.194|27.237|10.919|18.906|37.922|
|7D|7D|56.242|43.758|20.984|10.423|12.351|25.18|10.55|20.512|41.496|
|8D|8D|56.112|43.888|22.348|10.072|11.468|23.625|10.071|22.416|44.764|
|1D|2D|33.648|66.352|10.291|17.009|39.052|28.429|4.363|0.856|5.219|
|2D|3D|43.334|56.666|16.019|16.363|24.284|32.198|7.341|3.795|11.136|
|3D|4D|45.603|54.397|20.261|15.12|19.016|30.257|8.575|6.771|15.346|
|4D|5D|46.91|53.09|23.007|13.806|16.277|28.42|8.812|9.678|18.49|
|8D|9D|47.839|52.161|29.696|10.914|11.551|21.884|8.669|17.286|25.955|
|2D|1D|68.784|31.216|0.867|4.284|26.065|41.63|17.079|10.075|5.151|
|3D|2D|71.353|28.647|3.764|7.349|17.534|39.019|16.284|16.05|11.113|
|4D|3D|70.142|29.858|6.819|8.547|14.492|35.102|15.102|19.938|15.366|
|5D|4D|68.474|31.526|9.655|8.886|12.985|31.779|13.927|22.768|18.541|
|9D|8D|63.618|36.382|17.142|8.599|10.641|23.203|10.66|29.755|25.741|
|1D|2D|33.477|66.523|10.215|16.925|39.383|28.248|4.414|0.815|5.229|
|1D|3D|23.947|76.053|24.176|21.205|30.672|21.072|2.415|0.46|2.875|
|1D|4D|16.032|83.968|39.357|21.87|22.741|14.407|1.367|0.258|1.625|
|1D|5D|10.585|89.415|53.66|19.461|16.294|9.625|0.779|0.181|0.96|
|1D|8D|2.546|97.454|83.29|9.064|5.1|2.4|0.121|0.025|0.146|
|2D|1D|68.695|31.305|0.893|4.415|25.997|41.611|17.005|10.079|5.308|
|3D|1D|82.777|17.223|0.48|2.398|14.345|37.235|21.527|24.015|2.878|
|4D|1D|90.085|9.915|0.301|1.401|8.213|29.208|21.543|39.334|1.702|
|5D|1D|94.525|5.475|0.149|0.795|4.531|21.157|19.402|53.966|0.944|
|8D|1D|98.992|1.008|0.021|0.134|0.853|6.589|9.115|83.288|0.155|

Les stats ne rajoutent pas grand chose et en pratique quand il y a beaucoup de dés dans les pools, cela peut devenir pénible de relancer à chaque 6.  


* Statistiques du moteur de résolution avancé qui nécessite de faire des totaux

Juste pour la forme car en jeu ce n'est vraiment pas pratique. 
Les statistiques sont faites ici avec des dés du chaos au 1er jet mais pas après. 

|Protagoniste|Obstacle|Succes|Echec|-3|-2|-1|+1|+2|+3|Fortunes|
|---|---|---|---|---|---|---|---|---|---|---|
|1D|1D|57.183|42.817|0.0|4.066|38.751|52.942|4.241|0.0|0.0|
|2D|2D|54.735|45.265|2.158|9.403|33.704|43.116|9.462|2.157|4.315|
|3D|3D|53.582|46.418|5.228|11.48|29.71|36.839|11.591|5.152|10.38|
|4D|4D|52.618|47.382|8.133|12.173|27.076|32.352|12.079|8.187|16.32|
|5D|5D|52.058|47.942|10.548|12.177|25.217|29.338|12.2|10.52|21.068|
|6D|6D|51.589|48.411|12.866|12.084|23.461|26.821|11.892|12.876|25.742|
|7D|7D|51.215|48.785|14.884|11.911|21.99|24.927|11.723|14.565|29.449|
|8D|8D|51.289|48.711|16.156|11.558|20.997|23.467|11.443|16.379|32.535|
|1D|2D|31.467|68.533|4.051|15.663|48.819|29.399|2.068|0.0|2.068|
|2D|3D|38.234|61.766|8.993|16.84|35.933|31.578|5.501|1.155|6.656|
|3D|4D|40.065|59.935|12.744|16.588|30.603|29.292|7.551|3.222|10.773|
|4D|5D|41.468|58.532|15.689|15.629|27.214|27.543|8.643|5.282|13.925|
|8D|9D|42.735|57.265|23.311|13.102|20.852|21.421|9.235|12.079|21.314|
|2D|1D|75.262|24.738|0.0|2.077|22.661|55.416|15.803|4.043|2.077|
|3D|2D|68.647|31.353|1.207|5.581|24.565|42.862|16.944|8.841|6.788|
|4D|3D|65.18|34.82|3.049|7.504|24.267|36.299|16.279|12.602|10.553|
|5D|4D|63.275|36.725|5.152|8.548|23.025|31.715|15.697|15.863|13.7|
|9D|8D|59.307|40.693|12.115|9.535|19.043|23.204|13.065|23.038|21.65|
|1D|2D|31.409|68.591|4.13|15.808|48.653|29.353|2.056|0.0|2.056|
|1D|3D|20.487|79.513|14.819|24.005|40.689|19.473|1.014|0.0|1.014|
|1D|4D|13.11|86.89|29.286|26.516|31.088|12.563|0.547|0.0|0.547|
|1D|5D|8.202|91.798|44.412|24.857|22.529|7.956|0.246|0.0|0.246|
|1D|8D|1.788|98.212|79.213|12.376|6.623|1.752|0.036|0.0|0.036|
|2D|1D|75.382|24.618|0.0|2.156|22.462|55.542|15.826|4.014|2.156|
|3D|1D|85.237|14.763|0.0|1.076|13.687|46.392|24.067|14.778|1.076|
|4D|1D|90.594|9.406|0.0|0.515|8.891|34.681|26.728|29.185|0.515|
|5D|1D|94.162|5.838|0.0|0.25|5.588|24.954|24.711|44.497|0.25|
|8D|1D|98.793|1.207|0.0|0.034|1.173|7.129|12.289|79.375|0.034| 

Concrètement c'est difficile de faire le total des pairs et des impairs surtout pour ne gérer que l'égalité. C'est pour cela que cette mécanique a été abandonnée. 

### Révéler les protagonistes

Il y a des éléments nécessaires pré-établis à la création des protagonistes mais l'idée du  jeu est de permettre ensuite aux Protagonistes de se révéler petit à petit en cours de partie, surtout pendant la session zéro. Le problème n'est pas simple car il faut arbitrer les deux questions suivantes: 

* Par quoi commencer ? C'est à dire quels sont les éléments nécessaires ? C'est à la Destinée de fournir ce cadre à mon avis quand il crée le jeu. 
* Où s'arrêter ? C'est à dire quand estime-t'on qu'on ne peut plus révéler de traits (hormis via les Fortunes)  ? La question est là plus délicate. 

**Piste avec les fortunes**

On pourrait avoir un certain nombre de fortunes qui ne peuvent être utilisée que pour révéler le protagoniste dans les premières sessions. 

Mais cela pose deux questions: 

1. Quel nombre attribuer en début de partie ? 
2. A quel moment bascule-t'on sur le mode fortune qui permet de modifier un résultat et de demander un rebondissement positif à la Destinée ? 

### Création du jeu 

Une idée commence à émerger: **jouer pour créer le jeu**

Cela permettrait à la Destinée de tester son jeu en quelque sorte (en mode solo). 

Faire des allers retours entre les étapes suivantes: 

* A. Poser le cadre de l'univers 
* B. Créer un protagoniste adversaire: essayer de prendre un profil proche des protagonistes (en étant un adversaire potentiel)
* C. Lister les scènes types du jeu 
* D. Jouer les scènes types (en dehors de toute intrigue) en impliquant l'adversaire.
* E. Intégrer un groupe type 

L'idée est d'enrichir l'univers et les éléments du jeu tout en jouant. 

Note: a priori, on joue sans tenir en compte la jauge de destin. 

### Une pierre, deux coups

L'idée sous-jacente est de voir s'il est possible d'avoir un mode solo qui soit générateur de ressources pour inviter ensuite des amis et jouer à plusieurs. 

Cela implique une écriture particulière qui relève plus du listing que du style. 

Comparez par exemple: 

```
Vous faites face à la forêt hantée. 
Devant vous, un mur qui s'étend à l'infini apparemment. 
Des arbres à perte de vue et derrière vous voyez pas plus loin 
que quelques dizaines de pas. 
Aucun chemin ne semble présent. 
Il semble y faire sombre. 
```

```
FORET HANTEE
Immense
Visibilité réduite 
Sombre
Pas de chemin
```

Autre exemple sur une une ligne: en mettant en gras ce qui pourrait servir dans une résolution.  

* **LA MERE SUPERIEURE**: **Très âgée**, **Canne**, Courbée, Visage creusé, Des yeux pétillants d'**intelligence**, Une robe de soeur couleur sombre, Un air **revêche** et dur, Des grosses **bagues** brillantes aux doigts 

On obtient donc des ressources directement exploitables. Reste plus qu'a assembler le pseudo-récit en assemblant les éléments dans des scènes types à jouer ce qui permettra de faire émerger des traits pour nos ressources. 

Exemple:

```
SITUATION: putsch de Ralandis 
LIEU: le hall du chef 
CONTEXTE: l'ancien chef vient de mourir
DETAILS: 
    - Ambiance lugubre
    - Des chants de femmes
    - Une lumière tamisée
    - Tous les gens importants du clan sont là (le Cercle Extérieur)
    - Le corps de RIALTAR git sur un chariot mortuaire ouvragé et décoré 
PERSONNAGES: 
    - RALANDIS: veut devenir le nouveau chef 
    - KAILLA: refuse qu'un Uroxi devienne chef
    - BOURDABAR: veut manger le chef mort ! 
    - CRIMOS: veut faire le choix le plus juste au yeux de Lankhor Mhy 
    - ... 
CONFLIT: chacun s'exprime mais c'est le Conseil (le Cercle interne) qui vote.
D'un coté les avantages de Ralandis (lui meme et ceux acquis a sa cause) contre ceux qui ne veulent pas de lui. 
Le jet permettra de savoir si des indécis l'ont choisi ou pas. 
Exemple: revers -> le conseil demande à Ralandis de faire ses preuves 
avant le jour divin de la prochaine semaine de la Vérité 
(dans 2 semaines donc!) 
Il doit venger RIALTAR et apaiser les Dieux. 
Le problème pour lui c'est que se faisant 
il devra se détourner de ses obligations de lutte contre le Chaos 
(conflit au sein des Uroxi, devra choisir entre combattre 
un ennemi chaotique ou remplir sa quête 
et s'éloigner de l'eternelle bataille...).  
```

Rien n'empêche dans un pur bullet-style de détailler chaque élément important ce qui permet finalement d'adapter la scène pour d'autres joueurs. Par exemple, la mort du chef de clan mais sans le putsch de Ralandis. 

On pourrait ainsi rentrer de plain-pied dans le setting en jouant des résolutions avec de vrais traits et en rôdant ainsi sa façon d'appréhender les conséquences des jets. 

On peut également faire l'exercice avec des ressources existantes pour transcrire au format HaDes des descriptions, statistiques d'autres moteurs de jeu. L'idée est d'avoir une fiche de lieu, de second rôle directement exploitable par la suite. 

Reste maintenant à définir aussi une organisation de classement pour pouvoir s'y retrouver facilement.  