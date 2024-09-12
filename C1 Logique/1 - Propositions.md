
**Une proposition** est une phrase qu'on peut qualifier de vraie ou fausse
Un **prédicat** est une proposition dépendante d'un ou plusieurs paramètres

**Le principe de tiers exclu** rapporte qu'une proposition ne peut être que vraie ou fausse

$P$ et $Q$ deux propositions


- $P \land Q$ représente "P et Q"
- $P \lor Q$ représente "P ou Q"
- $\neg P$ représente "non P" 
- $P \Longrightarrow Q$ représente "P implique Q"
	- $P$ est une condition suffisante à $Q$
	- $Q$ est une condition nécessaire à $P$
- $P \Longleftrightarrow Q$ représente "P équivalent à Q"
	- $P$ et $Q$ sont une condition nécessaire et suffisante l'une pour l'autre

| $P$ | $Q$ | $\neg P$ | $P \land Q$ | $P \lor Q$ | $P \Longrightarrow Q$<br> | $P \Longleftrightarrow Q$ |
| --- | --- | -------- | ----------- | ---------- | ------------------------- | ------------------------- |
| V   | V   | F        | V           | V          | V                         | V                         |
| V   | F   | F        | F           | V          | F                         | F                         |
| F   | V   | V        | F           | V          | V                         | F                         |
| F   | F   | V        | F           | F          | V                         | V                         |
- Loi de la double négation :
$$
\neg(\neg P) \Longleftrightarrow P
$$

- Loi de De Morgan : 
$$
\begin{align}
\neg(P \land Q) && \iff && \neg P \lor \neg Q\\
\neg(P \lor Q) && \iff && \neg P \land \neg Q
\end{align}
$$
- Quelques identités à connaître par cœur :
$$
\begin{align}
P \implies Q &&\iff &&& \neg P \lor Q \\
(P \iff Q) &&\iff &&& (P \implies Q \land Q \implies P)\\
\end{align}
$$
- $\land$ et $\lor$ sont **associatifs** :
$$
\begin{align}
P\lor (Q\lor P) \iff (P\lor Q)\lor P \\
P\land (Q\land P) \iff (P\land Q)\land P
\end{align}
$$
- $\lor$ et $\land$ sont **commutatifs** :
$$
\begin{align}
P \land Q \iff Q \land P \\
P \lor Q \iff Q \lor P
\end{align}
$$
- $\land$ et $\lor$ sont **distributifs** l'un par rapport à l'autre :
$$
\begin{align}
P \land (P \lor Q) \iff (P\land P) \lor (P \land Q) \\
P \lor (P \land Q) \iff (P\lor P) \land (P \lor Q) \\
\end{align}
$$

- **Le principe de contraposition** :
$$(P \implies Q) \iff (\neg Q \implies \neg P)$$
