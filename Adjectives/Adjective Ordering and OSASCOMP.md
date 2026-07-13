# Adjective Ordering, Heavy APs, and Positional Constraints

Adjectives and Adjective Phrases ($AP$) modify nouns or pronouns, but their positioning within a Determiner Phrase ($DP$) or Verb Phrase ($VP$) is strictly constrained by syntactic rules.

---

## 1. Canonical Adjective Ordering: OSASCOMP

When multiple pre-nominal adjectives modify a single head noun, English enforces a hierarchical ordering system known as **OSASCOMP**. Deviating from this order produces unnatural or ungrammatical sequences.

$$\text{Opinion} \longrightarrow \text{Size} \longrightarrow \text{Age} \longrightarrow \text{Shape} \longrightarrow \text{Color} \longrightarrow \text{Origin} \longrightarrow \text{Material} \longrightarrow \text{Purpose}$$

| Order | Category                  | Examples                             | Sample Mapping |
| :---: | :------------------------ | :----------------------------------- | :------------- |
| **1** | **Opinion / Observation** | *useful, sleek, beautiful, horrible* | *sleek*        |
| **2** | **Size**                  | *large, small, huge, tiny*           | *small*        |
| **3** | **Age**                   | *old, new, modern, legacy*           | *modern*       |
| **4** | **Shape**                 | *square, rectangular, round*         | *rectangular*  |
| **5** | **Color**                 | *green, blue, dark, pale*            | *black*        |
| **6** | **Origin**                | *Japanese, American, local*          | *Japanese*     |
| **7** | **Material**              | *metal, plastic, wooden, steel*      | *metal*        |
| **8** | **Purpose / Type**        | *SQL, server, deployment, cooking*   | *server*       |

### Example Construction
> *"We installed a **sleek, small, modern, Japanese, metal, server** rack."*

---

## 2. Heavy Adjective Phrases ($AP$) and Post-Positioning

While simple adjectives sit pre-nominally (*before the noun*), an Adjective Phrase that contains its own **complement** (a Prepositional Phrase or Infinitive Clause) becomes **syntactically heavy** and must shift to the **post-nominal position** (*after the noun*).

### A. Prepositional Phrase Complements
* `*We deployed a [capable of high throughput] system.` *(Crash: Pre-nominal heavy AP)*
* ✅ *We deployed a system **[capable of high throughput]**.*

### B. Infinitive Clause Complements
* `*He is an [eager to learn C#] developer.` *(Crash: Pre-nominal heavy AP)*
* ✅ *He is a developer **[eager to learn C#]**.*
* ✅ *I need something **[quick to resolve this bug]**.*

---

## 3. Post-Positive Adjectives with Compound Indefinite Pronouns

Compound indefinite pronouns (*someone, something, anyone, anything, nobody, nothing*) act as complete $DP$ heads. They **reject pre-determiners and pre-nominal adjectives**, forcing all modifying adjectives into the **post-positive position**.

* `*I need a quick something.` *(Crash)*
* `*Did you find interesting anything?` *(Crash)*
* ✅ *I need **something quick**.*
* ✅ *Did you find **anything interesting**?*

---

## 4. Attributive vs. Predicate Adjective Restrictions

Adjectives are classified by where they can physically appear in a sentence:

### A. Predicate-Only Adjectives ($A$-Adjectives)
Adjectives starting with the prefix *a-* (*alive, asleep, afraid, aware, alone*) alongside words like *glad* cannot stand directly before a noun (*attributively*). They must follow a linking verb (*predicatively*).
* `*An asleep engineer missed the alert.` *(Crash)*
* ✅ *The engineer was **asleep** and missed the alert.*
* ✅ *A **sleeping** engineer missed the alert.* (Attributive substitution)

### B. Attributive-Only Adjectives
Adjectives like *main, primary, chief, utter, mere* can only modify nouns directly before them. They cannot stand alone as predicate adjectives.
* `*The backup server seems primary.` *(Crash)*
* ✅ *The backup server seems to be the **primary server**.*