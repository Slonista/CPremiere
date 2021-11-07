# CHAPITRE 2 = Probabilités conditionnelles et indépendance



## 		I - Probabilités conditionnelles

### 		<u>Définitions</u> :

Soit `A` et `B` deux évènement de $\Omega$ avec $P(A) \neq 0$

On appelle probabilité conditionnelle de `B` sachant `A`, la probabilité **qu'un évènement `B` se réalise, sachant que l'évènement `A` est réalisé.**

Elle est notée $P_{A}(B)$ et est **défini par** : $P_{A}(B) = \frac{P(A \cap B)}{P(A)}$ 



### 		<u>Remarques</u> :

- $P_{A}(B)$ se lit "probabilité de `B` sachant `A`"

- $P_{A}(A) = 1$ 

- $0 \leq P_{A}(B) \leq 1$

- $P_{A}(\Omega) = 1$  et  $P_{A}(\phi) = 0$​

- En situation d'équiprobabilité, on a :

  $P_{A}(B) = \frac{P(A \cap B)}{P(A)}$ 

- Si on connais la probabilité conditionnelle $P_{A}(B)$ alors :

  $P(A \cap B) = P(A) \times P(B)$ 



### <u>Exemples</u> : 

Le tableau ci-dessous donne le nombre d'élèves reçu au baccalauréat dans une classe de Terminale.

|   | Reçu  | Non reçu | Total |
| :--------:  | :--------: |:--------:| :--------:|
| **Filles** | *18* |   *1*      | *19* |
| **Garçon** | *13* | *3*           | *16* |
| **Total** | *31* | *4*       | *35* |



On choisit un élève au hasard.

- La probabilité que l'élève soit reçu `(R)` sachant que l'élève est une fille `(F)` est :

  $P_{F}(R) = \frac{P(R \cap F)}{P(F)} = \frac{18}{19}$ 

- La probabilité que l'élève soit une fille`(F)` sachant que l'élève est reçu `(R)`est :

  $P_{R}(F) = \frac{P(R \cap F)}{P(R)} = \frac{18}{31}$ 
