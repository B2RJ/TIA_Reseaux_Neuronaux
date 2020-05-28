<h1>Techniques de l'Intelligence Artificielle</h1>
<h2>Réseaux de neurones</h2>
<h3>Documents réponses</h3>
<h4>Richard BRUNEAU</h4>


<h3>Étude "théorique" de cas simple</h3>
<h4>Influence de η</h4>

<p>Si η est égale à 0, alors ΔWi,j = 0. Du coup, la prochaine valeur du neurone gagnant ne changera pas</p>
<p>Si η est égale à 1, alors ΔWi,j = 1*1*(xi-wi,j). Du coup, la prochaine valeur du poids va tendre vers X.</p>
<p>Si η est compris entre ]0,1][, alors Wi,j = η*1*(xi-wi,j). Du coup, si η tend vers 0, la valeur du neurone restera proche de W* et si η tend vers 1, la valeur va tendre vers X.</p>

<h4>Influence de σ</h4>
<p> Si σ augmente, alors la division va tendre vers 0. Nous allons donc avoir la fonction de voisinage qui tend vers 1. Cela pour effet que les voisins vont plus apprendre l'entrée courante.</p>
<p> Plus σ est grand, plus l'auto-organisation obtenue sera resserée. En effet, plus le sigma augmente, plus les neurone apprennent et donc plus ils se déplacent.</p>
<p> Une mesure envisageable pour quantifier l'influence de σ serait de mesurer l'aire de la grille en fonction de différents σ et d'essayer de trouver un rapport entre la différence de l'air et la variation du sigma.</p>

<h4>Influence de la distribution d'entrée</h4>
<p>Le vecteur va converger entre les deux entrées à égale distance de l'une que de l'autre.</p>
<p>Si X1 est présenté n fois plus que X2, alors le neuronnes va se déplacer vers X1. A 1/n de la mi-distance entre X1 et X2.</br>
Si il est deux fois plus présents, le neurones sera à 1/4 de la distance totale.</br>
Si il est trois fois plus présents, le neurones sera à 1/3 de la mi-distance.</p>
<p>Les neuronnes vont se placer à l'intérieur de la plage de données de façons à couvrir présicément le centre de la plage.</p>

