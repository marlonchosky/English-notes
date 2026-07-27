# Wh-Movement ($\bar{A}$-Movement) and Syntactic Transformations

In generative grammar, Wh-Movement (also categorized as $\bar{A}$-Movement or A-bar movement) is a transformational process where an interrogative operator ($wh$-phrase) is displaced from its underlying base-generated thematic position to the left edge of a clause.

---

## 1. Deep Structure vs. Surface Structure

Sentences containing $wh$-phrases are generated in their canonical argument or adjunct slots before undergoing fronting.

### A. Deep Structure (Base Generation)
* **Sentence:** You deployed [which endpoint]$_i$?
* **Base Position:** The complement position following the transitive verb *deployed*.
* **Thematic Assignment:** Direct Object / Patient $\theta$-role.

### B. Surface Structure (Post-Movement)
* **Sentence:** [Which endpoint]$_i$ did you deploy $t_i$?
* **Operation:** The $wh$-phrase front-loads to the left edge of the main clause, leaving a co-indexed silent trace ($t_i$ or $\varnothing$) at the base site.

---

## 2. Structural Landing Site: $\text{Spec, CP}$

Hierarchically, $wh$-movement targets a non-argument operator slot: the **Specifier of the Complementizer Phrase ($\text{Spec, CP}$)**.

$$\text{[CP } [\text{Which endpoint}]_i \text{ [C' } \text{did}_j \text{ [IP } \text{you } t_j \text{ [VP } \text{deploy } t_i \text{ ]]]]\}}$$

---

## 3. Transformations: Subject vs. Non-Subject Wh-Movement & Do-Support

The transformational steps required for $wh$-questions depend directly on whether the $wh$-operator targets the **Subject** or a **Non-Subject (Object/Adjunct)** argument.

### A. Non-Subject Wh-Movement (Requires T-to-C Movement or Do-Support)

When a $wh$-operator originates in object or adjunct position, $wh$-fronting triggers **Subject-Auxiliary Inversion (T-to-C Movement)** to satisfy the interrogative Force of $C^0$.

1. **With an Auxiliary Verb (Direct T-to-C Inversion):**
   * **Base:** You [T can] deploy [which service]$_i$.
   * **Step 1 ($Wh$-Shift):** [Which service]$_i$ you [T can] deploy $t_i$?
   * **Step 2 (T-to-C Inversion):** [Which service]$_i$ [C can$_j$] you $t_j$ deploy $t_i$?

2. **Without an Auxiliary Verb (The Do-Support Trigger):**
   * Main lexical verbs (*deploy*, *test*, *run*) **cannot** directly invert or move to $C^0$ in modern English (* *What deployed you?* is ungrammatical).
   * **Do-Support Mechanism:** When Tense features ($[\pm \text{Past}]$) are left stranded without a modal or auxiliary verb, English inserts the dummy auxiliary **`do`** into $T^0$, which then moves to $C^0$ carrying the tense and number agreement.
   * **Base:** You [T -past] deployed [which endpoint]$_i$.
   * **Do-Insertion & Inversion:** [Which endpoint]$_i$ **[C did$_j$]** you $t_j$ **deploy** $t_i$? *(The main verb reverts to bare infinitive form as `did` absorbs the past tense).*

### B. Subject Wh-Movement (Vacuous Movement / No Do-Support)

When the $wh$-word itself is the **Subject** of the matrix clause, it is already situated at the left edge of the Inflectional Phrase ($\text{Spec, IP}$).

* **Sentence:** *"Who deployed the microservice?"*
* **Base Structure:** [Who]$_i$ [T -past] deployed the microservice.
* **Do-Support Restriction:** **Do-support is blocked** in standard subject questions because the $wh$-word satisfies operator scope without requiring auxiliary inversion across a subject.
  * ✅ *"Who deployed the code?"*
  * ❌ *\*"Who did deploy the code?"* *(Ungrammatical except under contrastive/emphatic stress).*

---

## 4. Extraction Alternations: Pied-Piping vs. Stranding

When a $wh$-word originates inside a Prepositional Phrase ($PP$), English licenses two distinct extraction behaviors:

| Mode                      | Structural Behavior                                          | Example Sentence                                | Style / Context     |
| :------------------------ | :----------------------------------------------------------- | :---------------------------------------------- | :------------------ |
| **Pied-Piping**           | The $wh$-determiner drags the entire container $PP$ to $\text{Spec, CP}$. | *[To what extent]$_i$ will you optimize $t_i$?* | Formal / Technical  |
| **Preposition Stranding** | The $wh$-phrase extracts alone, leaving $P^0$ stranded at the base site. | *Who$_i$ did you talk [to $t_i$]?*              | Standard / Informal |

---

## 5. Syntactic Movement Diagnostics & Crash Rules

| Feature                               | Wh-Movement ($\bar{A}$-Movement)            | Tough-Movement ($A$-Movement)                                |
| :------------------------------------ | :------------------------------------------ | :----------------------------------------------------------- |
| **Trigger Constraint**                | Interrogative operator fronting             | Adjectival predicate constraint (*easy*, *tough*, *hard*)    |
| **Target Landing Site**               | Non-argument position ($\text{Spec, CP}$)   | Canonical Subject position ($\text{Spec, IP}$)               |
| **Auxiliary Inversion / Do-Support?** | **YES** (Non-Subject $Wh$)                  | **NO** (*The endpoint is easy to test.*)                     |
| **Crash Diagnostic**                  | *\*What you deployed?* (Missing Do-Support) | *\*Who did deploy this?* (Spurious Do-Support in Subject-Wh) |

|      |      |      |
| :--- | :--- | :--- |
|      |      |      |
|      |      |      |
|      |      |      |
|      |      |      |