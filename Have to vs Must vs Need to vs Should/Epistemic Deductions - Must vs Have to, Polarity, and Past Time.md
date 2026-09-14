# Epistemic Modality & Logical Deductions: Must vs. Have to

When evaluating evidence to reach a reasoned, high-confidence conclusion, **must** and **have to** shift from *deontic modality* (obligation/duty) to **epistemic modality**.

---

## 1. Present Epistemic Deduction: "Must" vs. "Have to"

| Form        | Register / Distribution              | Semantic Focus                           | Example                                                    |
| :---------- | :----------------------------------- | :--------------------------------------- | :--------------------------------------------------------- |
| **Must**    | Formal, Academic, Universal Standard | Reasoned logical deduction from evidence | *"The lights are on; she **must** be home."*               |
| **Have to** | Informal / Spoken American English   | Objective, evidence-forced inevitability | *"Look at those logs; this **has to be** a null pointer."* |

---

## 2. Negative Deductions (Epistemic Impossibility)

Polarity behavior diverges sharply in epistemic contexts:
* **Logical Impossibility:** Strictly requires **`can't`** / **`couldn't`** + base form.
  * *"The service was decommissioned; that **can't be** our endpoint responding."*
* **`Must not`:** Reserved for deontic prohibition (British/international) or weak negative explanation/assumption (American), *not* strict epistemic impossibility.
* **`Don't have to` / `Don't need to`:** Reverts to deontic lack of obligation (*optionality*), never epistemic impossibility.

---

## 3. Past Deductions: Modal + Perfect Aspect (`have + V3`)

Pure modals are syntactically defective; past time requires the perfect infinitive (`have + V3`) projected past the modal evaluation anchor:

$$\mathbf{\text{Modal / Semi-Modal}} + \mathbf{have} + \mathbf{V_3}$$

| Polarity        | Construction                             | Semantic Meaning                                 | Example                                                      |
| :-------------- | :--------------------------------------- | :----------------------------------------------- | :----------------------------------------------------------- |
| **Affirmative** | `must have + V3` / `had to have + V3`    | High certainty that a past event occurred        | *"The commit log changed; someone **must have pushed** to `main`."* |
| **Negative**    | `can't have + V3` / `couldn't have + V3` | Logical impossibility that a past event occurred | *"His VPN expired; he **couldn't have altered** the database."* |

---

## 4. Why "Had to + V_base" Fails for Past Deductions

Using `had to + V_base` (without `have V3`) switches back to deontic requirements:
* **`Had to + V_base` (Deontic / Inevitability):** Expresses a past external requirement, mandatory duty, or pre-scheduled necessity:
  * *"To test our failover daemon, the container **had to crash** during the spike."* (= It was required/scheduled to happen).
* **`Had to have + V_3` (Epistemic Deduction):** Expresses a logical conclusion about past reality derived from present evidence:
  * *"The memory leak was fatal; the container **had to have crashed** during the spike."* (= Based on the evidence, I conclude it crashed).

---

## 5. Summary Reference Matrix

| Timeframe / Polarity    | Target Meaning     | Licensed Form                        | Unlicensed / Crash Form        |
| :---------------------- | :----------------- | :----------------------------------- | :----------------------------- |
| **Present Affirmative** | High certainty     | `must / has to + V_base`             | —                              |
| **Present Negative**    | Impossibility      | `can't / couldn't + V_base`          | ❌ *mustn't*, *doesn't have to* |
| **Past Affirmative**    | Past certainty     | `must have + V3`, `had to have + V3` | ❌ *had to + V_base*            |
| **Past Negative**       | Past impossibility | `can't / couldn't have + V3`         | ❌ *mustn't have + V3*          |