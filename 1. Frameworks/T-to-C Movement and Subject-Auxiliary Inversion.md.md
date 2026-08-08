# T-to-C Movement (Subject-Auxiliary Inversion)

In formal generative syntax, **T-to-C Movement**—traditionally known in school grammar as **Subject-Auxiliary Inversion**—is a head-movement operation where a verb sitting in the **Tense Head ($T^0$)** moves upward into the **Complementizer Head ($C^0$)**.

---

## 1. Decoding the Acronyms: What do $T$ and $C$ Stand For?

To understand T-to-C movement, you have to look at the top two structural "ceilings" of a sentence tree:

| Symbol          | Full Term                        | What Lives There?                                            | Role in the Sentence                                         |
| :-------------- | :------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| **$T^0$ / $T$** | **Tense** *(formerly Infl / IP)* | Tense markers ($[\pm \text{Past}]$), auxiliary verbs (*have, be*), and modals (*can, will, should*). | Controls time reference and subject-verb agreement.          |
| **$C^0$ / $C$** | **Complementizer**               | Clause markers (*that, if, whether*) or abstract clause-type features (e.g., $[+\text{Q}]$ for questions). | Controls overall clause force (declarative vs. interrogative). |

---

## 2. The Syntactic Trigger: Why Does It Move?

1. **Clause Force Requirement:** Every direct question carries an abstract interrogative feature—represented as $[+\text{Q}]$ or $[+\text{WH}]$—located in $C^0$.
2. **Feature Checking:** In standard English main (matrix) clauses, $C^0$ is a strong head that cannot remain empty. It demands that an auxiliary verb move out of $T^0$ and jump up to $C^0$ to explicitly express interrogative force.

```text
       CP  (Complementizer Phrase)
      /  \
  Spec    C'
         /  \
        C°   TP  (Tense Phrase)
  [can_j]   /  \
          Subj  T'
         (you) /  \
              T°   VP
             t_j  ...
```

---

## 3. Step-by-Step Derivation

Tracing how the statement *"You can deploy the service"* transforms into the direct question *"Can you deploy the service?"* or *"Which service can you deploy?"*:

### A. Base Generation (Deep Structure in TP)
* **Structure:** `[TP You [T° can] [VP deploy the service]]`
* **State:** The modal *can* resides in $T^0$.

### B. T-to-C Movement (Yes/No Question Surface Structure)
* **Operation:** *can* jumps from $T^0$ across the subject *you* into $C^0$.
* **Structure:** `[CP [C° can_j] [TP you [T° t_j] [VP deploy the service]]]`
* **Output:** *"Can you deploy the service?"*

### C. Combining with Wh-Movement (Wh-Question Surface Structure)
If a $wh$-operator is present, $wh$-movement and T-to-C movement occur in tandem:
1. $Wh$-Fronting targets $\text{Spec, CP}$.
2. Auxiliary inverts from $T^0$ to $C^0$.

$$\text{[CP [Spec, CP } \text{Which service}]_i \text{ [C' [C° } \mathbf{\text{can}}_j \text{] [TP you [T° } t_j \text{] [VP deploy } t_i \text{ ]]]]}$$

---

## 4. What Happens Without an Auxiliary? (The Do-Support Trigger)

Main lexical verbs (*deploy, run, build, crash*) in modern English cannot physically move from $V^0$ up into $T^0$ and then into $C^0$ (*"Deployed you the service?"* is ungrammatical).

When $T^0$ contains no modal or auxiliary verb, the tense feature ($[\pm \text{Past}]$) is left stranded. Syntax resolves this by triggering **Do-Support**:
1. The dummy auxiliary **`do`** is inserted into $T^0$ to hold tense and number agreement.
2. The newly created `do` then undergoes T-to-C movement into $C^0$.

> **Example:**
> * Base: `You [T° -past] deploy the endpoint.`
> * Do-Insertion: `You [T° do] deploy the endpoint.`
> * T-to-C & Wh-Shift: `[CP [Which endpoint]_i [C° did_j] [TP you t_j [VP deploy t_i]]]`

---

## 5. Critical Exceptions to T-to-C Movement

### Exception 1: Subject $Wh$-Questions (Blocked / Vacuous)
When the $wh$-phrase is itself the **Subject** of the sentence, T-to-C movement and Do-Support do **not** occur in standard English.

* ✅ *"Who deployed the hotfix?"* `(No Do-Support / No Inversion)`
* ❌ *"*Who did deploy the hotfix?"* `(Ungrammatical except under contrastive/emphatic stress)`

**Why?** The subject $wh$-word already occupies the left edge of $TP$ ($\text{Spec, TP}$), right adjacent to $C^0$. Moving an auxiliary across the subject is impossible because the $wh$-word *is* the subject.

### Exception 2: Embedded / Indirect Questions (Blocked)
T-to-C movement is restricted to **matrix (main) clauses**. Embedded indirect questions block auxiliary inversion because embedded $C^0$ is filled by a complementizer or marked differently.

* ✅ Direct Question (Matrix $\rightarrow$ T-to-C required):  
  *"What **did you** change?"*
* ✅ Indirect Question (Embedded $\rightarrow$ T-to-C blocked):  
  *"I asked what **you changed**."* `(NOT: *I asked what did you change)`

---

## 6. Summary Matrix for Quick Reference

| Question Type        | Target Position    | T-to-C Movement Happens?        | Example                          |
| :------------------- | :----------------- | :------------------------------ | :------------------------------- |
| **Yes/No Direct**    | Clause Force       | **YES** ($T^0 \rightarrow C^0$) | *"**Will** you test the build?"* |
| **Non-Subject $Wh$** | Object / Adjunct   | **YES** ($T^0 \rightarrow C^0$) | *"What **did** you test $t_i$?"* |
| **Subject $Wh$**     | Matrix Subject     | **NO** (Blocked)                | *"Who $t_i$ tested the build?"*  |
| **Embedded $Wh$**    | Subordinate Clause | **NO** (Blocked)                | *"I know what you tested."*      |