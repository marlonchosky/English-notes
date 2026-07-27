# Syntactic Notes: Interrogative Words & Verb Agreement

## 1. Overview & Core Principle

Interrogative words (*wh-* items) such as **who**, **which**, **what**, and **whose** display variable-number syntactic behavior when functioning as interrogative pronouns. Their grammatical number (singular vs. plural) is not inherently fixed; instead, it depends on the **intended target set** or the **underlying noun phrase** they represent.

---

## 2. "Whose": Determiner vs. Pronoun Syntactic Shifts

The word *whose* can function as either an interrogative determiner ($D^0$) or an interrogative pronoun ($NP$ head):

### A. Interrogative Determiner ($D^0$)
* **Structure:** $[ \text{Whose} + \text{Head Noun} ] + \text{Aux/Verb} + \text{Subject}?$
* **Example:** *"Whose book is this?"*
* **Syntactic Role:** Directly modifies an overt head noun (*book*).
* **Usage:** Far more common in natural English due to direct information flow and structural alignment with possessive determiners (*my book* $\rightarrow$ *whose book*).

### B. Interrogative Pronoun ($NP$ Head)
* **Structure:** $[ \text{Whose} ] + \text{Verb} + \text{Subject NP}?$
* **Example:** *"Whose is this book?"*
* **Syntactic Role:** Stands alone as the structural head, replacing the entire noun phrase (*whose property / item*).
* **Usage:** More formal or used in elliptical/deictic contexts (e.g., pointing at an item: *"Whose are these?"*).

---

## 3. Wh- Words and Verb Agreement Rules

When $wh$-pronouns head a clause or subject phrase, verb agreement is governed by selection scope and contextual intent.

### Rule 1: Comparative & Exclusive Selection Scope ($N = 2$ or 1 Winner)
When comparing options to identify a **single superior or specific entity**, the $wh$-word carries a singular feature $[+\text{Singular}]$ and requires a **singular verb**.

* **Example:**
  $$\text{"Which of these two cluster configurations } \mathbf{\text{handles}} \text{ high concurrency better?"}$$
* **Analysis:** The comparative post-modifier *"better"* explicitly restricts the selection to a single optimal candidate ($1$ out of $2$). Thus, *handles* (singular) is mandatory.

### Rule 2: Plural Selection Scope
When the context implies or asks for **multiple entities** within a set, the $wh$-pronoun inherits plural features $[+\text{Plural}]$ and requires a **plural verb**.

* **Examples:**
  * *"Which of these node configurations **are** currently failing?"*
  * *"Who **are** the developers assigned to this ticket?"*

### Rule 3: Default Strategy with Unknown Target
If the answer set could be either singular or plural and no contextual constraint exists, English defaults to **singular agreement**.

* **Examples:**
  * *"Which of the candidates **has** submitted the assignment?"*
  * *"Who **is** responsible for this build pipeline?"*

---

## 4. Structural Contrast: Interrogatives vs. Partitive Quantifiers

It is crucial to distinguish between $wh$-selection scope and standard transparent partitive quantifiers:

| Feature / Construction                              | Mechanism                                                    | Example                               | Verb Form                         |
| :-------------------------------------------------- | :----------------------------------------------------------- | :------------------------------------ | :-------------------------------- |
| **Interrogative Selection** (*Which/Who of...*)     | **Head Primacy:** Governed by intended selection set ($1$ vs. many). | *"Which of the servers **is** down?"* | Singular (focus on specific unit) |
| **Transparent Quantifiers** (*Some of, Most of...*) | **Look-Through:** Agreement matches the object of the preposition. | *"Some of the servers **are** down."* | Plural (governed by *servers*)    |

---

## 5. Summary Checklist

1. **Whose as Determiner:** More natural & common than pronoun form (*"Whose book is this?"* > *"Whose is this book?"*).
2. **Selective *Which* with Binary Comparison:** Always singular (**handles**, **works**, **is**).
3. **Number Feature Inheritance:** $Wh$-pronouns (*who*, *which*, *what*, *whose*) inherit $[ \pm \text{Singular} ]$ based on the expected answer set, defaulting to singular when unknown.
