Pour trouver une solution à une question on associe 2 types de raisonnements :
- **déductif** : choisir un ensemble suffisant de proprietes, en deduire une propriete necessaire (On passe du general au particulier)
- **inductif** : a partir de cas particuliers on conjecture une propriété générale a confirmer par déductions. Cette démarche participe au choix de départ de **raisonnement déductif**.

### Prouver une proposition $P$
- **Preuve directe** : On cherche $Q$ vraie (condition suffisante) telle $Q \implies P$

- **Preuve par l'absurde** : supposer $P$ fausse, en déduire $Q$ (on montre $\neg P \implies Q$), en sachant $Q$ fausse. On a donc $Q \land \neg Q$ vraie : impossible (tiers exclu), donc $P$ est vraie.

- **Preuve par disjonction de cas** : on sépare en différents cas dont la réunion donne le cadre.

### Prouver une implication $P \implies Q$
- **Preuve directe** : on suppose $P$ vraie, et on montre que $Q$ est vraie (modus ponens)
> **Modus ponens** : Pour montrer $P \Longrightarrow Q$ (vraie), on se contente donc de montrer que : si $P$ est vraie alors $Q$ l'est aussi. Inversement, si $P$ et $P \Longrightarrow Q$ sont vraies, alors $Q$ est vraie : c'est ce qu'on appelle le modus ponens. En pratique, pour montrer $Q$ vraie, on cherche $P$ vraie telle que $P \Longrightarrow Q$ soit vrai...

- **Preuve par contraposée** : on montre que $\neg Q \implies \neg P$

### Prouver une équivalence $P \iff Q$
- **Preuve directe** : (à choisir uniquement dans des cas très simples) : on établit les équivalences successives de $P$ jusqu'à $Q$

- **Preuve par double implication** : on montre $P \implies Q$ et on montre $Q \implies P$


### Preuve par récurrence
> Théorème 

$$
\begin{align}
&\text{Soit P un prédicat sur } \mathbb N \text{. On suppose :} \\
&P(0) \text{ vraie} &(initialisation)\\
&\forall n \in \mathbb N, P(n) \implies P(n + 1)& (hérédité)\\
&\text{Alors :} \;\; \forall n \in \mathbb N, P(n)
\end{align}
$$

1) Expliciter la propriété a prouver : $\text{pour tout naturel n, posons }HR(n) : …$
2) On initialise la récurrence au(x) plus petit(s) entier(s) utilisé(s)
3) On montre que la propriété est héréditaire.
4) On conclut en citant le théorème utilisé, comme toujours !
### Analyse-Synthèse
> Elle sert pour résoudre des **problèmes d'existence**

Si on ne voit pas la solution, on va appliquer l'analyse-synthèse. 
- **Analyse** *on recherche la forme des solutions possibles par condition nécessaire*
	1) on suppose qu'une telle solution existe, et on la pose : "soit..."
	2) on réduit au maximum l'ensemble des possibilités
	3) s'il reste une seule possibilité : l'**unicité en cas d'existence** est démontrée.
- **Synthèse :**
	Si l'une des possibilités données par l'analyse vérifie correctement les exigences du problème, on a montré l'existence d'une solution.