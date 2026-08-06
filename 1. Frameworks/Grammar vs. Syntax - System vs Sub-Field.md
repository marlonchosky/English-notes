# Terminology Guardrail: Grammar vs. Syntax

In linguistic analysis and syntactic study, terms like **"Grammatical Function"** and **"Syntactic Function"** are frequently used, leading to confusion over whether they represent separate concepts or identical roles. This note clarifies the hierarchical relationship between **Grammar** (the overarching system) and **Syntax** (a specific sub-field), and details why functional labels are often treated as synonyms.

---

## 1. Grammar (The Umbrella System)

**Grammar** is the complete structural framework and operating system of a language. It encompasses all rules governing how linguistic units combine, transform, and convey meaning across multiple levels of processing.

Grammar is composed of four primary sub-fields:

1. **Syntax:** Governs word order, sentence structure, phrase creation, and movement operations.
2. **Morphology:** Governs internal word structure, prefixes, suffixes, inflections, and tense markers (e.g., plural `-s`, past tense `-ed`, genitive `'s`).
3. **Semantics:** Governs literal meaning, truth conditions, scope, and domain limits (e.g., bounded vs. unbounded sets, telicity).
4. **Phonology:** Governs sound systems, stress patterns, and pronunciation rules.

---

## 2. Syntax (The Architectural Sub-Field)

**Syntax** is the specific branch within grammar that studies how words and phrases combine to form hierarchical tree structures, clauses, and complete sentences.

Syntax is concerned exclusively with:
* **Word Order & Constituency:** How words group together to form Determiner Phrases (DP), Prepositional Phrases (PP), Adjective Phrases (AP), etc.
* **Transformations & Movement:** How phrases shift from Deep Structure (base generation) to Surface Structure (e.g., $Wh$-Movement, T-to-C Movement, Tough-Movement).
* **Argument Selection & Complementation:** How verbs select mandatory arguments (Complements) vs. optional modifiers (Adjuncts).

---

## 3. Structural System Diagram

The relationship between the umbrella system (**Grammar**) and its structural sub-field (**Syntax**) is mapped below:

```text
                                  GRAMMAR (Overarching rules)
                                             │
             ┌───────────────────────────────┼───────────────────────────────┐
          SYNTAX                         MORPHOLOGY                       SEMANTICS
(Sentence structure & word order)   (Word formation & inflections)   (Logical meaning & scope)
             │                               │                               │
  E.g., "Direct Object of have"     E.g., "3rd person singular -s"   E.g., "Bounded domain (N=2)"
    (Syntactic Function)               (Morphological Rule)             (Semantic Property)