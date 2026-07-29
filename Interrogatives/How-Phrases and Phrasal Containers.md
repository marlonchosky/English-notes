# Interrogative How-Phrases and Phrasal Containers

## 1. Core Principle: Head vs. Container

The interrogative operator **`how`** is strictly a **Degree Adverb** ($Adv^0$). It cannot function as a noun, determiner, or adjective on its own. However, when it modifies another word, it gets wrapped inside that word's phrasal container.

When $Wh$-Movement occurs, **`how`** acts as an operator, fronting the **entire container phrase** to the left edge of the clause ($\text{Spec, CP}$).

---

## 2. The Primary Container Realizations

Depending on what head word **`how`** modifies, the resulting container takes on one of three distinct phrase types:

### A. Determiner Phrase / Noun Phrase (DP / NP Container)
* **Structure:** `[DP [AdvP How] + [D° much/many] + [N° Head Noun]]`
* **Target Modified:** The quantifier/determiner *much* or *many*.
* **Syntactic Function:** Direct Object, Subject, or Complement of a Transitive Verb.
* **Examples:**
  1. *"**[How much money]**$_i$ do you have $t_i$?"*
     - **Container:** Determiner Phrase (Direct Object of *have*).
     - **Word Classes:** `how` (Degree Adverb) $\rightarrow$ `much` (Quantifier/Determiner) $\rightarrow$ `money` (Head Noun).
  
  2. *"**[How many servers]**$_i$ crashed $t_i$?"*
     - **Container:** Determiner Phrase (Subject DP).
     - **Word Classes:** `how` (Degree Adverb) $\rightarrow$ `many` (Quantifier/Determiner) $\rightarrow$ `servers` (Head Noun).
  3. *"**[How much ground]**$_i$ did we cover $t_i$?"*
     - **Container:** Determiner Phrase (Direct Object of *cover*).
     - **Word Classes:** `how` (Degree Adverb) $\rightarrow$ `much` (Quantifier/Determiner) $\rightarrow$ `ground` (Head Noun).

---

### B. Adverb Phrase (AdvP Container)
* **Structure:** `[AdvP [Adv° How] + [Adv° Head Adverb]]`
* **Target Modified:** A manner, degree, measure, or temporal/frequency adverb.
* **Syntactic Function:** Adverbial Adjunct or Adverbial Complement.
* **Examples:**
  1. *"**[How much]**$_i$ do you love this $t_i$?"*
     - **Container:** Adverb Phrase (Adverbial Adjunct of Degree modifying the verb *love*).
     - **Word Classes:** `how` (Interrogative Degree Adverb) modifying `much` (Head Degree Adverb). *(No head noun present).*

  2. *"**[How fast]**$_i$ did he drive $t_i$?"*
     - **Container:** Adverb Phrase (Manner Adverbial Adjunct modifying *drive*).
     - **Word Classes:** `how` (Degree Adverb) modifying `fast` (Head Manner Adverb).

  3. *"**[How often]**$_i$ does the pipeline run $t_i$?"*
     - **Container:** Adverb Phrase (Frequency Adverbial Adjunct modifying *run*).
     - **Word Classes:** `how` (Degree Adverb) modifying `often` (Head Frequency Adverb).

---

### C. Adjective Phrase (AP Container)
* **Structure:** `[AP [Adv° How] + [A° Head Adjective]]`
* **Target Modified:** A predicate, scalar, or depictive adjective.
* **Syntactic Function:** Subject Complement or Object Complement.
* **Examples:**
  1. *"**[How tall]**$_i$ is the tower $t_i$?"*
     - **Container:** Adjective Phrase (Subject Complement of *is* measuring physical dimension/scale).
     - **Word Classes:** `how` (Degree Adverb) modifying `tall` (Head Predicate Adjective).

  2. *"**[How stable]**$_i$ is the system $t_i$?"*
     - **Container:** Adjective Phrase (Subject Complement of *is* evaluating state/quality).
     - **Word Classes:** `how` (Degree Adverb) modifying `stable` (Head Predicate Adjective).

---

## 3. Comprehensive Breakdown Matrix

| Fronted Phrase            | Internal Role of `how` | Head Word Modified      | Container Phrase Class     | Syntactic Function in Sentence     |
| :------------------------ | :--------------------- | :---------------------- | :------------------------- | :--------------------------------- |
| **"How much money..."**   | Degree Adverb          | `much` (Determiner)     | **Determiner Phrase (DP)** | Direct Object of *have*            |
| **"How many servers..."** | Degree Adverb          | `many` (Determiner)     | **Determiner Phrase (DP)** | Subject of *crashed*               |
| **"How much..."**         | Degree Adverb          | `much` (Degree Adverb)  | **Adverb Phrase (AdvP)**   | Degree Adverbial modifying verb    |
| **"How fast..."**         | Degree Adverb          | `fast` (Manner Adverb)  | **Adverb Phrase (AdvP)**   | Manner Adverbial modifying verb    |
| **"How often..."**        | Degree Adverb          | `often` (Frequency Adv) | **Adverb Phrase (AdvP)**   | Frequency Adverbial modifying verb |
| **"How tall..."**         | Degree Adverb          | `tall` (Adjective)      | **Adjective Phrase (AP)**  | Subject Complement of linking verb |
| **"How stable..."**       | Degree Adverb          | `stable` (Adjective)    | **Adjective Phrase (AP)**  | Subject Complement of linking verb |

---

## 4. Syntactic Diagnostic: Pied-Piping of Containers

Nouns, adverbs, and adjectives inside these containers cannot be left behind when **`how`** moves to $\text{Spec, CP}$:

* **Correct (Full Container Fronting):**
  * $\text{[DP How much money]}_i \text{ do you have } t_i\text{?}$
  * $\text{[AdvP How fast]}_i \text{ did he drive } t_i\text{?}$
  * $\text{[AP How tall]}_i \text{ is he } t_i\text{?}$

* **Crash (Stranding the Head Word):**
  * $\text{* How}_i \text{ do you have [ } t_i \text{ much money]?}$
  * $\text{* How}_i \text{ did he drive [ } t_i \text{ fast]?}$
  * $\text{* How}_i \text{ is he [ } t_i \text{ tall]?}$