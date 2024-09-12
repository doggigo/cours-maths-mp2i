Soit $E$ l'ensemble des naturels $n \in \mathbb N$ tels que $P(n)$ est fausse.
Montrons que $E$ est vide ($E = \varnothing$) 
Supposons $E \neq \varnothing$.
$E$ étant une partie non-vide de $\mathbb N$, $E$ admet un plus petit élément $n_0$.
On a donc $P(n_0)$ fausse et donc $n_0 \ge 1$ puisque par hypothèse P(0) vraie.

$n_0 - 1$ est un naturel qui n'appartient pas à $E$ (puisque $n_0$ est le plus petit élément de $E$).
Donc $P(n_0 - 1)$ vraie.
Or, par hypothèse d'hérédité, $P(n_0 - 1)$ vraie donne $P(n_0)$ vraie.
Ceci contredit le principe de tiers exclu.
P(n_0) ne peut pas être vrai et faux.

> **Conclusion** : le théorème est prouvé car $E = \varnothing$ 
