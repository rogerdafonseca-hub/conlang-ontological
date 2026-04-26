# 📜 RFC-02 — LEXICAL DERIVATION & SEMANTIC COMPRESSION PROTOCOL

## Version 0.8.0

---

## 🔹 Status

**Status:** Draft — Stable Candidate  
**Applies to:** Ontological System → Lexical Output  
**Scope:** Defines how long ontological expressions are converted into usable words

---

## 🔹 1. Purpose

This document defines a **deterministic and scalable method** to derive **short lexical forms** from **extended ontological chains** without loss of essential meaning.

---

## 🔹 2. Problem Definition

Ontological expressions are structurally unlimited:

```
VCV + CV + CV + CV + CV ...
```

However, natural language requires:

```
CV + CV + CV      (preferred)
CV + CV + CV + CV (maximum common)
```

This protocol defines how to **compress meaning while preserving interpretability**.

---

## 🔹 3. Core Principles

### 3.1 Information Preservation

> The system must preserve **semantic identity**, not full structure.

---

### 3.2 Controlled Reduction

> Compression must be **systematic**, never arbitrary.

---

### 3.3 Context Integration

> Context is a **valid carrier of meaning** and may replace explicit structure.

---

### 3.4 Pronounceability Constraint

> All derived forms must conform to **phonological rules (v0.8.0)**.

---

## 🔹 4. Structural Hierarchy

Given:

```
VCV + CV₁ + CV₂ + CV₃ + CV₄ ...
```

|Element|Role|Priority|
|---|---|---|
|VCV|origin domain / lens|conditional|
|CV₁|semantic nucleus|critical|
|CV₂|primary modifier|high|
|CV₃|secondary modifier|medium|
|CV₄+|refinements|low|

---

## 🔹 5. Compression Levels

---

### 🔸 Level 0 — Full Ontological Form

```
VCV + CV + CV + CV + CV
```

- Maximum precision
    
- Not optimized for speech
    

---

### 🔸 Level 1 — Standard Lexical Form

```
VCV + CV₁ + CV₂
```

- Default derivation
    
- Balanced clarity and efficiency
    

---

### 🔸 Level 2 — Reduced Lexical Form

```
V + CV₁ + CV₂
```

- VCV reduced to vowel marker
    
- Used when domain remains inferable
    

---

### 🔸 Level 3 — Contextual Form

```
CV₁ + CV₂ (+ CV₃)
```

- VCV omitted
    
- Requires contextual disambiguation
    

---

## 🔹 6. VCV Handling Rules

---

### RULE 6.1 — Domain Preservation

> The originating domain (VCV) must be preserved unless safely inferable.

---

### RULE 6.2 — Reduction Strategy

VCV may be reduced as follows:

|Form|Result|
|---|---|
|VCV|V (vowel only)|

Example:

```
agru → a
ekli → e
```

---

### RULE 6.3 — Omission Condition

VCV may be omitted only if:

- domain is clear from context
    
- or ambiguity is negligible
    

---

## 🔹 7. Selection Algorithm

---

### Step 1 — Remove low-priority elements

Discard:

```
CV₄+
```

---

### Step 2 — Identify semantic nucleus

Always retain:

```
CV₁
```

---

### Step 3 — Select strongest modifiers

Choose:

```
CV₂ (+ CV₃ if needed)
```

---

### Step 4 — Evaluate VCV necessity

- keep → if ambiguity risk
    
- reduce → if partially clear
    
- remove → if fully clear
    

---

## 🔹 8. Redundancy Elimination

> If two elements express overlapping meaning, remove the weaker one.

Example:

```
pi (in) + ep (inside) → keep only one
```

---

## 🔹 9. Length Constraints

|Level|Max Units|
|---|---|
|Standard|3|
|Extended|4|

> Longer forms are not permitted in lexical output.

---

## 🔹 10. Cluster Handling

- Clusters (EC) count as **one unit**
    
- No artificial vowel insertion allowed
    

Example:

```
kra = 1 unit
pla = 1 unit
```

---

## 🔹 11. Contextual Compression

> Context may replace explicit structure.

Example:

Context: spatial discussion

```
(pa + lo + nu) → palonu
```

Without context:

```
a + pa + lo → apalo
```

---

## 🔹 12. Semantic Integrity Rule

> A derived word must retain:

- domain identity (explicit or contextual)
    
- core semantic function
    

---

## 🔹 13. Examples

---

### Example 1

Full:

```
agru + pa + ti + lo + nu
```

Standard:

```
a + pa + ti → apati
```

Reduced:

```
pati
```

---

### Example 2

Full:

```
ekli + kra + lo + nu
```

Standard:

```
e + kra + lo → ekralo
```

Reduced:

```
kralo
```

---

### Example 3

Full:

```
ikri + pa + lo + sa
```

Standard:

```
i + pa + lo → ipalo
```

---

## 🔹 14. Evolution Allowance

> Frequently used forms may naturally shorten over time.

Example:

```
apati → pti (long-term evolution)
```

This process is:

- gradual
    
- usage-driven
    
- not enforced by the system
    

---

## 🔹 15. Compliance

A valid lexical form MUST:

✔ preserve semantic nucleus  
✔ follow phonological rules  
✔ respect length limits  
✔ avoid forced articulation

---

## 🔹 16. Summary

The protocol ensures:

- infinite expressive depth (ontology)
    
- efficient communication (lexicon)
    
- controlled ambiguity (context-aware)
    

---

## 🔒 Final Statement

> Meaning is structured in depth, but spoken in essence.

This protocol defines the bridge between **infinite structure** and **human language usability**.