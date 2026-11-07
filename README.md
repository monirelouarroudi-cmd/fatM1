# Somme de vecteurs (Seconde)

> **Niveau** : élève venant de 3ème, qui connaît déjà les vecteurs et la translation.
> **Objectif** : consolider les acquis, puis maîtriser la somme de vecteurs (Chasles, parallélogramme, coordonnées).

---

## 1. Ce que tu connais déjà (3ème)

- Un vecteur $\overrightarrow{AB}$ a une **direction**, un **sens** et une **longueur**.
- $\overrightarrow{AB} = \overrightarrow{CD}$ signifie que $ABDC$ est un parallélogramme (attention à l'ordre des lettres).
- Le vecteur opposé de $\overrightarrow{AB}$ est $\overrightarrow{BA}$.
- Le vecteur nul : $\overrightarrow{AA} = \vec{0}$.

### Mini-test de rappel

1. Si $ABDC$ est un parallélogramme, que peut-on dire de $\overrightarrow{AB}$ et $\overrightarrow{CD}$ ?
2. Quel est l'opposé de $\overrightarrow{MN}$ ?
3. Dans un repère, comment calcule-t-on les coordonnées de $\overrightarrow{AB}$ ?

<details>
<summary>Correction</summary>

1. $\overrightarrow{AB} = \overrightarrow{CD}$.
2. $\overrightarrow{NM}$.
3. $\overrightarrow{AB}\binom{x_B - x_A}{y_B - y_A}$ : **arrivée moins départ**.

</details>

---

## 2. Cours

### 2.1 Idée de la somme

Faire la somme $\vec{u} + \vec{v}$, c'est **enchaîner** deux déplacements : d'abord $\vec{u}$, puis $\vec{v}$.

### 2.2 Relation de Chasles

Pour tous points $A$, $B$, $C$ :

$$\overrightarrow{AB} + \overrightarrow{BC} = \overrightarrow{AC}$$

**Astuce :** la fin du premier vecteur est le début du second. Les « $B$ » du milieu disparaissent.

**Exemple :** $\overrightarrow{MN} + \overrightarrow{NP} + \overrightarrow{PQ} = \overrightarrow{MQ}$

### 2.3 Règle du parallélogramme

Si deux vecteurs partent **du même point** :

$$\overrightarrow{AB} + \overrightarrow{AD} = \overrightarrow{AC} \iff ABCD \text{ est un parallélogramme}$$

### 2.4 Propriétés

- $\vec{u} + \vec{v} = \vec{v} + \vec{u}$ (commutativité)
- $(\vec{u} + \vec{v}) + \vec{w} = \vec{u} + (\vec{v} + \vec{w})$ (associativité)
- $\vec{u} + \vec{0} = \vec{u}$
- $\vec{u} + (-\vec{u}) = \vec{0}$
- **Différence :** $\vec{u} - \vec{v} = \vec{u} + (-\vec{v})$

### 2.5 Avec les coordonnées

Si $\vec{u}\binom{x}{y}$ et $\vec{v}\binom{x'}{y'}$ :

$$\vec{u} + \vec{v}\binom{x + x'}{y + y'} \qquad \vec{u} - \vec{v}\binom{x - x'}{y - y'}$$

Si $A(x_A ; y_A)$ et $B(x_B ; y_B)$ :

$$\overrightarrow{AB}\binom{x_B - x_A}{y_B - y_A}$$

**Exemple :** $\vec{u}\binom{3}{-2}$ et $\vec{v}\binom{-1}{4}$ donnent $\vec{u} + \vec{v}\binom{2}{2}$.

### 2.6 Méthode : démontrer un parallélogramme

Pour montrer que $ABCD$ est un parallélogramme, on montre que $\overrightarrow{AB} = \overrightarrow{DC}$ (mêmes coordonnées).

---

## 3. Exercices corrigés

### Niveau 1 : échauffement

#### Exercice 1
Simplifier en un seul vecteur :
1. $\overrightarrow{AB} + \overrightarrow{BC}$
2. $\overrightarrow{EF} + \overrightarrow{FG}$
3. $\overrightarrow{MN} + \overrightarrow{NP} + \overrightarrow{PQ}$

<details>
<summary>Correction</summary>

1. $\overrightarrow{AB} + \overrightarrow{BC} = \overrightarrow{AC}$ (Chasles)
2. $\overrightarrow{EF} + \overrightarrow{FG} = \overrightarrow{EG}$ (Chasles)
3. $\overrightarrow{MN} + \overrightarrow{NP} + \overrightarrow{PQ} = \overrightarrow{MP} + \overrightarrow{PQ} = \overrightarrow{MQ}$

</details>

#### Exercice 2
On donne $\vec{u}\binom{2}{5}$ et $\vec{v}\binom{-3}{1}$. Calculer :
1. $\vec{u} + \vec{v}$
2. $\vec{u} - \vec{v}$

<details>
<summary>Correction</summary>

1. $\vec{u} + \vec{v}\binom{2 + (-3)}{5 + 1} = \binom{-1}{6}$
2. $\vec{u} - \vec{v}\binom{2 - (-3)}{5 - 1} = \binom{5}{4}$

</details>

### Niveau 2 : programme de seconde

#### Exercice 3
Simplifier :
1. $\overrightarrow{AB} + \overrightarrow{CD} + \overrightarrow{BC}$
2. $\overrightarrow{AB} - \overrightarrow{CB}$
3. $\overrightarrow{AB} + \overrightarrow{CA} + \overrightarrow{BC}$

<details>
<summary>Correction</summary>

1. On réordonne : $\overrightarrow{AB} + \overrightarrow{BC} + \overrightarrow{CD} = \overrightarrow{AC} + \overrightarrow{CD} = \overrightarrow{AD}$
2. $\overrightarrow{AB} - \overrightarrow{CB} = \overrightarrow{AB} + \overrightarrow{BC} = \overrightarrow{AC}$
3. On réordonne : $\overrightarrow{CA} + \overrightarrow{AB} + \overrightarrow{BC} = \overrightarrow{CB} + \overrightarrow{BC} = \overrightarrow{CC} = \vec{0}$

</details>

#### Exercice 4
$ABCD$ est un parallélogramme. Simplifier :
1. $\overrightarrow{AB} + \overrightarrow{AD}$
2. $\overrightarrow{BA} + \overrightarrow{BC}$

<details>
<summary>Correction</summary>

1. Règle du parallélogramme (départ commun $A$) : $\overrightarrow{AB} + \overrightarrow{AD} = \overrightarrow{AC}$
2. Règle du parallélogramme (départ commun $B$) : $\overrightarrow{BA} + \overrightarrow{BC} = \overrightarrow{BD}$

</details>

#### Exercice 5
On donne $A(1 ; 2)$, $B(4 ; 3)$ et $C(2 ; -1)$.
1. Calculer les coordonnées de $\overrightarrow{AB}$ et $\overrightarrow{AC}$.
2. Calculer $\overrightarrow{AB} + \overrightarrow{AC}$.
3. Déterminer les coordonnées du point $D$ tel que $ABDC$ soit un parallélogramme.

<details>
<summary>Correction</summary>

1. $\overrightarrow{AB}\binom{4 - 1}{3 - 2} = \binom{3}{1}$ et $\overrightarrow{AC}\binom{2 - 1}{-1 - 2} = \binom{1}{-3}$
2. $\overrightarrow{AB} + \overrightarrow{AC}\binom{3 + 1}{1 + (-3)} = \binom{4}{-2}$
3. $ABDC$ est un parallélogramme $\iff \overrightarrow{AB} + \overrightarrow{AC} = \overrightarrow{AD}$.
   Donc $\overrightarrow{AD}\binom{4}{-2}$, soit $x_D - 1 = 4$ et $y_D - 2 = -2$.
   On obtient $D(5 ; 0)$.

</details>

#### Exercice 6
On donne $A(-1 ; 1)$, $B(3 ; 2)$, $C(4 ; 5)$ et $D(0 ; 4)$. Montrer que $ABCD$ est un parallélogramme.

<details>
<summary>Correction</summary>

$\overrightarrow{AB}\binom{3 - (-1)}{2 - 1} = \binom{4}{1}$ et $\overrightarrow{DC}\binom{4 - 0}{5 - 4} = \binom{4}{1}$.

Donc $\overrightarrow{AB} = \overrightarrow{DC}$, et $ABCD$ est un parallélogramme.

</details>

### Niveau 3 : défi

#### Exercice 7 : Vrai ou faux ?
Justifier chaque réponse.
1. $\overrightarrow{AB} + \overrightarrow{BA} = \vec{0}$
2. $\overrightarrow{AB} + \overrightarrow{AC} = \overrightarrow{BC}$
3. $\overrightarrow{AB} + \overrightarrow{BC} + \overrightarrow{CA} = \vec{0}$

<details>
<summary>Correction</summary>

1. **Vrai.** Chasles : $\overrightarrow{AB} + \overrightarrow{BA} = \overrightarrow{AA} = \vec{0}$.
2. **Faux.** Les deux vecteurs partent de $A$, donc Chasles ne s'applique pas. D'après la règle du parallélogramme, la somme vaut $\overrightarrow{AD}$ où $ABDC$ est un parallélogramme.
3. **Vrai.** $\overrightarrow{AB} + \overrightarrow{BC} + \overrightarrow{CA} = \overrightarrow{AC} + \overrightarrow{CA} = \overrightarrow{AA} = \vec{0}$.

</details>

#### Exercice 8
Soit $I$ le milieu de $[AB]$. Montrer que $\overrightarrow{AI} + \overrightarrow{BI} = \vec{0}$.

<details>
<summary>Correction</summary>

$I$ est le milieu de $[AB]$, donc $\overrightarrow{AI} = \overrightarrow{IB}$.

Ainsi $\overrightarrow{AI} + \overrightarrow{BI} = \overrightarrow{IB} + \overrightarrow{BI} = \overrightarrow{II} = \vec{0}$.

</details>
