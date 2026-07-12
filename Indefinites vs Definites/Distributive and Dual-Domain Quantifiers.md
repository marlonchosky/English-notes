# Distributive and Dual-Domain Quantifiers: Syntax and Bounded Domains

In English syntax, **Distributive Quantifiers** and **Dual-Domain Quantifiers** occupy a unique space between indefinite quantifiers and universal operators. Rather than quantifying a set as a collective blob (*all*, *some*), they force the syntax to evaluate entities individually or across a strictly bounded domain.

---

## 1. The Taxonomy of Bounded and Distributive Operators

Quantifiers in this category are grouped by two structural parameters: **Group Size (Domain)** and **Evaluation Mode** (Collective vs. Individual).

| Quantifier  | Domain Size       | Evaluation Mode            | Polarity / Value            | Verb Agreement | Example Construction       |
| :---------- | :---------------- | :------------------------- | :-------------------------- | :------------- | :------------------------- |
| **Both**    | Exactly 2 ($N=2$) | **Dual-Collective**        | Positive (+2)               | **Plural**     | *Both systems are online.* |
| **Either**  | Exactly 2 ($N=2$) | **Dual-Distributive**      | Disjunctive (1 or 2)        | **Singular**   | *Either path is valid.*    |
| **Neither** | Exactly 2 ($N=2$) | **Dual-Distributive**      | Negative Universal (0 of 2) | **Singular**   | *Neither option worked.*   |
| **Each**    | $N \ge 2$         | **Pure Distributive**      | Individual (1 by 1)         | **Singular**   | *Each student has a key.*  |
| **Every**   | $N \ge 3$         | **Aggregate Distributive** | Total Individualized        | **Singular**   | *Every server was tested.* |

---

## 2. Dual-Domain Quantifiers: The Rule of Two (*Both*, *Either*, *Neither*)

Dual-domain operators strictly require a contextual set of **exactly two items**. Applying them to sets of three or more creates a syntactic crash.

### A. Both (Universal Positive Dual)
* **Domain:** Exactly 2.
* **Evaluation Mode:** **Dual-Collective** (Evaluates the two items together as a combined pair, forcing plural verb agreement).
* **Agreement:** Always **Plural**.
* **Syntax:** Functions as a Pre-Determiner, Central Determiner, or Pronoun.
  * **Determiner:** *Both servers are running.*
  * **Pronoun / Partitive:** *Both of the servers are running.*

### B. Either (Distributive Choice Dual)
* **Domain:** Exactly 2.
* **Evaluation Mode:** **Dual-Distributive Disjunctive** (Evaluates Item A *or* Item B).
* **Agreement:** Always **Singular**.
* **Meaning:** "One or the other (item A or item B)."
  * **Determiner:** *You can take either route.*
  * **Pronoun / Partitive:** *Either of the routes is fine.*

### C. Neither (Universal Negative Dual)
* **Domain:** Exactly 2.
* **Evaluation Mode:** **Dual-Distributive Negative** (Evaluates Not A *and* Not B).
* **Agreement:** Always **Singular** (Formal Concord).
* **Meaning:** "Not the one and not the other (0 of 2)."
  * **Determiner:** *Neither key fits the lock.*
  * **Pronoun / Partitive:** *Neither of the keys fits the lock.*

### ⚠️ The 2 vs. 3+ Boundary Rule
* For **2 items**, use: *Both*, *Either*, *Neither*.
* For **3+ items**, switch to: *All*, *Any*, *None*.
  * `*Neither of the three candidates was hired.` *(Crash: Domain boundary exceeded)*
  * `None of the three candidates was hired.` *(Correct)*

---

## 3. Pure Distributives vs. Aggregate Distributives (*Each* vs. *Every*)

Distributive operators force the syntax to process entities one by one rather than as a single group unit.

### A. Each (Pure Distributive)
* **Domain:** $N \ge 2$.
* **Evaluation Mode:** **Pure Distributive** (Evaluates items individually in complete isolation).
* **Developer Analogy:** A `forEach()` loop executing logic on one element at a time in isolation.
* **Syntactic Behavior:** Can function as both a **Determiner** and a **Pronoun**.
  * *Each server was updated.* (Determiner)
  * *Each of the servers was updated.* (Pronoun/Partitive)

### B. Every (Aggregate Distributive)
* **Domain:** $N \ge 3$.
* **Evaluation Mode:** **Aggregate Distributive** (Evaluates items 1-by-1 to build and validate the complete 100% aggregate total).
* **Developer Analogy:** An `.every()` validation method—it checks every single item individually, but does so to return a verdict on the total array as an aggregate whole.
* **Syntactic Behavior:** **Determiner Only** (Requires an overt head noun; cannot act directly as a pronoun without *-one* / *-body*).
  * *Every server was updated.* (Determiner)
  * `*Every of the servers was updated.` *(Crash: Requires "Every one of...")*

---

## 4. Deep Divergence Breakdown: Why *Every* is "Aggregate" and *Both* is "Dual-Collective"

### 1. Why *Every* is an **Aggregate Distributive**
* **The "Distributive" Mechanism:** Like *each*, *every* forces singular noun and verb agreement (*Every server **was** tested*), preventing the set from being treated as a collective plural blob.
* **The "Aggregate" Domain:** While *each* isolates item $A$, then item $B$, then item $C$ independently, *every* aggregates them together into a complete collection: 
  $$\text{Item } A + \text{Item } B + \text{Item } C = 100\% \text{ of the entire domain } (N \ge 3)$$

### 2. Why *Both* is a **Dual-Collective**
* **The "Dual" Boundary:** *Both* is strictly locked to a domain size of $N=2$.
* **The "Collective" Evaluation:** Unlike *either* and *neither*, which evaluate the two items disjunctively/distributively (triggering singular agreement: *either route **is** fine*), **`both` evaluates the two items together as a combined joint set (+2)**.
* **Agreement Consequence:** Combining both entities into a joint set (+2) forces **plural verb agreement**:
  * *Both servers **are** online.* (Not: `*Both server is online.`)

---

## 5. Summary Checklist & Structural Guardrails

| Quantifier  | Domain Size | Evaluation Mode            | Verb Agreement | Core Meaning                           |
| :---------- | :---------- | :------------------------- | :------------- | :------------------------------------- |
| **Both**    | Exactly $2$ | **Dual-Collective**        | **Plural**     | Both items combined (+2)               |
| **Either**  | Exactly $2$ | **Dual-Distributive**      | **Singular**   | Item A OR Item B (1 of 2)              |
| **Neither** | Exactly $2$ | **Dual-Distributive**      | **Singular**   | Not A AND Not B (0 of 2)               |
| **Each**    | $N \ge 2$   | **Pure Distributive**      | **Singular**   | 1 by 1 in complete isolation           |
| **Every**   | $N \ge 3$   | **Aggregate Distributive** | **Singular**   | 1 by 1 to form the complete 100% total |