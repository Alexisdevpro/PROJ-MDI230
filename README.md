# PROJ-MDI230

## Projet 1 — : Modelisation de Slicing 5G (URLLC et EMBB)<br>
Cette partie s'intéresse à la problématique du découpage en tranches (slicing) dans les réseaux 5G, permettant de faire coexister plusieurs services virtuels sur la même infrastructure physique.

Deux slices sont étudiées :

**URLLC** (Ultra-Reliable Low Latency Communication) : trafic très sensible à la latence, ne tolérant pas de mise en attente.<br>
**eMBB** (enhanced Mobile Broadband) : trafic à haut débit, tolérant une certaine latence.

Les objectifs sont les suivants :<br>
- Étudier des modèles théoriques à l’aide des files M/M/S/S et des formules d’Erlang-B.
- Simuler des files avec deux classes de clients, la classe URLLC étant prioritaire, y compris avec préemption des clients eMBB.
- Déterminer les conditions de stabilité du système et calculer les probabilités stationnaires à l’aide d’approches matricielles.
- Comparer avec un modèle plus réaliste basé sur les canaux de garde, dans lequel les clients URLLC ne peuvent pas préempter mais bénéficient de serveurs réservés.
<br><br>

## Projet 2 — Modélisation Épidémiologique<br>
Le deuxième projet traite de la modélisation mathématique de la propagation d’une épidémie au sein d’une population.

Points abordés :<br>
- Modèles SIR et SEIR classiques (versions déterministes et stochastiques).
Simulation de processus de naissance-mort et chaînes de Markov.<br>
- Étude des effets de politiques de santé publique sur l’évolution de l’épidémie.<br>
- Comparaison entre modèles discrets et modèles continus (équations différentielles vs simulation aléatoire).


