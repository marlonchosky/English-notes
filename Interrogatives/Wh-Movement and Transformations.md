# Wh-Movement ($\bar{A}$-Movement) and Syntactic Transformations

In generative grammar, **Wh-Movement** (also categorized as $\bar{A}$-Movement or A-bar movement) is a transformational process where an interrogative operator ($wh$-phrase) is displaced from its underlying base-generated thematic position to the front of a clause.

---

## 1. Deep Structure vs. Surface Structure

Sentences containing $wh$-phrases are generated in their canonical argument slots before undergoing fronting.

### A. Deep Structure (Base Generation)
* **Sentence:** *You deployed [which endpoint]$_i$?*
* **Base Position:** The object position following the transitive verb *deployed*.
* **Thematic Assignment:** The phrase receiving the Direct Object / Patient $\theta$-role.

### B. Surface Structure (Post-Movement)
* **Sentence:** *[Which endpoint]$_i$ did you deploy $t_i$?*
* **Operation:** The $wh$-phrase front-loads to the left edge of the main clause, leaving a co-indexed silent trace ($t_i$ or $\varnothing$) at the base site.

---

## 2. Structural Landing Site: $\text{Spec, CP}$

Hierarchically, $wh$-movement targets a non-argument operator slot: the **Specifier of the Complementizer Phrase ($\text{Spec, CP}$)**.

$$\text{[CP } [\text{Which endpoint}]_i \text{ [C' } \text{did}_j \text{ [IP } \text{you } t_j \text{ [VP } \text{deploy } t_i \text{ ]]]]}$$

### The Two-Step Transformation Chain
1. **Wh-Operator Shift:** The $wh$-phrase moves to $\text{Spec, CP}$ to scope the clause.
2. **Subject-Auxiliary Inversion ($\text{I}^0$-to-$\text{C}^0$ Movement):** The finite auxiliary verb moves from its inflectional head ($\text{I}^0$) into the Complementizer Head ($\text{C}^0$).

---

## 3. Extraction Alternations: Pied-Piping vs. Stranding

When a $wh$-word originates inside a Prepositional Phrase ($PP$), English licenses two distinct extraction behaviors:

| Mode                      | Structural Behavior                                          | Example Sentence                                | Style / Context     |
| :------------------------ | :----------------------------------------------------------- | :---------------------------------------------- | :------------------ |
| **Pied-Piping**           | The $wh$-determiner drags the entire container $PP$ to $\text{Spec, CP}$. | *[To what extent]$_i$ will you optimize $t_i$?* | Formal / Technical  |
| **Preposition Stranding** | The $wh$-phrase extracts alone, leaving $P^0$ stranded at the base site. | *Who$_i$ did you talk [to $t_i$]?*              | Standard / Informal |

---

## 4. Syntactic Movement Diagnostics

To compare $Wh$-Movement against other movement phenomena in the repository:

| Feature                  | Wh-Movement ($\bar{A}$-Movement)          | Tough-Movement ($A$-Movement)                             |
| :----------------------- | :---------------------------------------- | :-------------------------------------------------------- |
| **Trigger Constraint**   | Interrogative operator fronting           | Adjectival predicate constraint (*easy*, *tough*, *hard*) |
| **Target Landing Site**  | Non-argument position ($\text{Spec, CP}$) | Canonical Subject position ($\text{Spec, IP}$)            |
| **Auxiliary Inversion?** | YES (*What **did** you test?*)            | NO (*The endpoint **is** easy to test.*)                  |
| **Primary Reference**    | `Interrogatives/Wh-Movement.md`           | `Tough-Movement and Adjectival Complements.md`            |