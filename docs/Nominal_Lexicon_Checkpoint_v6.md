# NOMINAL LEXICON — RULES AND DIRECTIVES
**Universal Ontological Language Project**
Version 0.8.0 — Restoration Checkpoint v6
April 2026

> This checkpoint documents all architectural decisions, rules, and directives established for the nominal lexicon system. It is a **manifesto of rules**, not a data file. Tables and word lists are maintained separately in domain files.

---

## PART 1 — SYSTEM ARCHITECTURE

### 1.1 The Three Independent Systems

The language operates through three systems that must never collapse into each other:

| System | Layer | Purpose | Format |
|---|---|---|---|
| Grammatical | Surface | Controls how things are said | CV / VC / VCV particles |
| Ontological | Deep | Defines what things ARE | VCV + CV + CV... |
| Nominal Lexicon | Surface | Names real things for speech | CVCV + CV + CV... |

**Rule:** The same consonants appear in all three systems with different roles. This is intentional. The consonant signals the domain regardless of which system you are operating in.

**Rule:** The nominal lexicon is derived from the ontological system but follows its own principles. The word does not carry the structure — it points to it.

---

### 1.2 The Three-Layer Word Structure

Every nominal word has up to three functional layers:

```
[C₁V₁C₂V₂]  +  [C₃V₃]  +  [C₄V₄...]
   Layer 1          Layer 2       Layer 3+
  Ontological      Category      Identity
   address         (usage)      (distinction)
```

**Layer 1 — Ontological Address (Syllables 1–2, CVCV)**
- Derived directly from the domain matrix
- C₁ = primary domain (MANDATORY — never override)
- V₁ = row position in the matrix (axis of the primary domain)
- C₂ = secondary domain / operational direction (PREFERENTIAL)
- V₂ = column position in the matrix (axis of the secondary domain)
- Every CVCV base points to a unique position in ontological space

**Layer 2 — Usage Category (Syllable 3, CV)**
- The third consonant (C₃) indexes the word into one of 20 usage categories
- Chosen from the official closed set of 20 consonants
- Represents a **functional reindexation** of the ontological domains into human use
- The third vowel (V₃) follows the official gradation tendencies

**Layer 3+ — Identity (Syllable 4+)**
- Purely distinctive — no derivation rules apply
- Differentiates specific instances within the same category
- Freely assigned for memorability and phonetic clarity

---

## PART 2 — WORD-MOTHER PRINCIPLE

### 2.1 Definition

Every CVCV word derived from a matrix cell is a **word-mother** — the broadest, most productive entry in its semantic field.

**Rule:** The word-mother carries the maximum generality within its field. All longer words sharing its first two syllables belong to its semantic family.

**Rule:** The word-mother is always valid and usable at its level of generality. A speaker who does not know the specific word can always use the word-mother and be understood correctly, at a higher level of abstraction.

### 2.2 Density

Not all matrix cells generate valid word-mothers. This is expected and linguistically healthy.

**Rule:** Do not force word-mothers into cells where the concept is too abstract, redundant, or meta-conceptual. Mark these as NVW.

**Rule:** Lexicalization happens when there is **semantic tension** between the two axes — not redundancy. Reflexive crossings (PI×PI, PU×PU) and very close crossings tend toward NVW.

**Observed density:** Between 8 and 12 valid word-mothers per 25-cell matrix is considered healthy.

**Pattern:** The higher the ontological abstraction of the row, the lower the lexical density. Essence rows (PA-) generate fewer words than combination rows (PO-).

### 2.3 NVW — No Valid Word

When a cell does not generate a usable word-mother:
- Mark the cell as **NVW**
- Leave the structural position intact
- NVW cells may be revisited in future versions
- Never force a word into a NVW cell

**Rule:** Structural completeness takes priority over lexical completeness. Every cell must exist structurally, even if empty.

---

## PART 3 — LEXICAL PROJECTION RULES

### 3.1 C₁ — Primary Domain Consonant

**Rule:** C₁ is MANDATORY and always mirrors the primary ontological domain.
- P-words are always in the Matter domain
- N-words are always in the Life domain
- M-words are always in the Mind domain
- This rule has no exceptions

### 3.2 C₂ — Secondary Domain Consonant

**Rule:** C₂ is PREFERENTIAL — it represents the soft semantic clustering of the word within its domain.
- Can be overridden for phonetic reasons
- Can be overridden to avoid collision with existing words
- Should follow the matrix structure when possible

### 3.3 V₁ and V₂ — Ontological Vowels

**Rule:** V₁ and V₂ are derived from the matrix row and column positions.
- They are not free — they are determined by the ontological address
- V₁ = position of the word within the primary domain axis
- V₂ = position of the word within the secondary domain axis

### 3.4 Word Length and Frequency

**Rule:** Word length encodes frequency and importance.

| Length | Format | Use |
|---|---|---|
| CVCV | 2 syllables | Universal core — highest frequency |
| CVCVCV | 3 syllables | Common — specific daily concepts |
| CVCVCVCV | 4 syllables | Less common — technical/specialized |
| 5+ syllables | CVCV... | Rare — highly specific or scientific |

**Rule:** The most frequent and important concept in a semantic field gets the shortest word.

---

## PART 4 — THE SEMANTIC AXIS LAW

> **Meaning = Ontology(C₁) × Operation(C₂)**

**Rule:** C₁ signals the domain. C₂ signals the operational direction within that domain. A speaker who knows the 20 base domains can infer the semantic family of any word from its first two consonants.

**Rule:** This law applies to Layers 1 only. Layers 2 and 3 follow different rules (category and identity).

---

## PART 5 — THE 20 USAGE CATEGORIES (Layer 2 — C₃)

### 5.1 Definition

The third consonant indexes the word into one of 20 usage categories. These categories are:
- A **functional reindexation** of the ontological domains into human experience
- **Isomorphic** with the ontological domains (same structural skeleton)
- **Not equivalent** to the ontological domains (different perspective)
- A closed set — no new categories can be added without system revision

**The relationship:**
- Ontological domain = what the thing IS in reality
- Usage category = where it lives in human experience

### 5.2 Official Table

| C₃ | Usage Category | Scope |
|---|---|---|
| **-p-** | natural raw substances | unprocessed matter |
| **-b-** | biological / corporeal | living origin, vital functions |
| **-t-** | food and beverages | nutritive consumption |
| **-g-** | geological / mineral | inorganic, terrestrial origin |
| **-r-** | transitory physical states | mud, vapor, gel, foam |
| **-l-** | applied physical structures | paste, layer, mass |
| **-s-** | granulates and powders | flour, sand, dust |
| **-d-** | industrial / manufactured | paint, rubber, plastic |
| **-k-** | collective / social use | materials used communally |
| **-n-** | organic / agricultural | compost, humus, resin |
| **-v-** | energetic / fuel | oil, gas, coal, combustibles |
| **-ǰ-** | internal / active fluids | syrup, solvent, glaze, bodily fluid |
| **-x-** | reactive / corrosive | acid, base, oxidizer |
| **-m-** | medical / biochemical | medicine, serum, antidote |
| **-ľ-** | sensorially marked | perfume, spice, olfactory substance |
| **-y-** | marking / pigmentation | pigment, ink, dye |
| **-w-** | affective / ritual | honey, incense, ritual substance |
| **-z-** | extreme / dangerous | explosive, strong toxin, radioactive |
| **-h-** | environmental / atmospheric | mist, smoke, airborne particle |
| **-f-** | external interface / contact | adhesive, surface agent, contact lubricant |

**Critical distinction:**
- **-ǰ-** = the fluid itself (internal, active, in motion)
- **-f-** = the fluid as agent between surfaces (external, contact, interface)

### 5.3 Disambiguation Rule

**Rule:** When a thing fits multiple categories, choose the **most salient function in human use**, not the total ontological composition.

> *"Milk is an aliment first, biological second, liquid third."*

**Rule:** The same physical substance can have different words depending on the perspective being encoded. This is not error — it is expressive power.

Examples:
- *popada* = paint (as manufactured product → -d-)
- *popaya* = pigment (as marking agent → -y-)
- *popaǰa* = the fluid itself
- *popafa* = that fluid as surface adhesive

All four are valid entries for related but distinct concepts.

**Formal definition of C₃:**
> *The third consonant encodes the dominant functional class of human use, chosen by practical salience and not by complete ontological composition.*

---

## PART 6 — THE GRADATION SYSTEM (Layer 2 — V₃)

### 6.1 Official Vowel Tendencies

The third vowel (V₃) follows semi-structured tendencies — not rigid rules, but stable preferences that aid memory and organization.

| Vowel | Tendency |
|---|---|
| **-a** | base / unmarked (most general form of the category) |
| **-e** | refined / processed |
| **-i** | lower charge / lower functional density |
| **-o** | dense / loaded / higher intensity |
| **-u** | extreme / concentrated / specialized |

**Formal definition:**
> *The final vowel encodes the degree of specificity and functional charge within the category, ranging from base (-a) to specialized (-u).*

### 6.2 Application Rules

**Rule:** V₃ tendencies are **semi-structured** — they guide but do not constrain.
- They are not a rigid gradation
- They do not limit to 5 words per category
- Override is permitted when a better form is needed
- The system is Option C (semi-structured), not Option A (free) or Option B (fixed)

**Rule:** The -i and -o distinction:
- -i = lower charge / lesser functional density (lighter, more diffuse)
- -o = denser / heavier / more intense

**Rule:** -u is not merely "more intense than -o" — it is **maximum specialization**. A -u word is the most specific, concentrated, or technically defined instance within its category.

---

## PART 7 — EXTRACTION PROTOCOL

### 7.1 From Matrix to Word-Mother

When building word-mothers from domain matrices, follow this sequence:

1. **Locate the cell** — identify the row × column intersection
2. **Read the ontological description** — what is the abstract concept at this address?
3. **Find the simplest real-world anchor** — what is the most common thing this concept describes?
4. **Verify domain purity** — does the word remain unambiguously in its primary domain?
5. **Check for NVW conditions** — is the concept too abstract, reflexive, or redundant?
6. **Assign or mark** — assign the word-mother or mark NVW

### 7.2 NVW Conditions

Mark a cell as NVW when:
- The crossing is reflexive or nearly reflexive (same axis × same axis)
- The concept belongs more naturally to another domain
- The concept is a process rather than an entity (belongs to V domain)
- The concept is purely relational with no stable real-world anchor
- The word would duplicate a word-mother from another cell

### 7.3 Domain Purity Tests

Before assigning a word-mother, verify:
- **Type test:** Is this still the same type of thing, at a different level? (If no → wrong row)
- **Refinement test:** Is this a refinement of the same base concept? (If no → wrong column)
- **Purity test:** Does this involve use, action, or context? (If yes → may belong to V or another domain)
- **Contamination test:** Does this word invade Y (information), M (cognition), K (social), L (abstract structure), or V (process)?

---

## PART 8 — DOMAIN AXIS DEFINITIONS

### 8.1 Rule

Each of the 20 domains must have a defined 5-step axis before its matrices can be built. The axis defines what A, E, I, O, U mean within that domain.

**Rule:** Axis definitions are domain-specific and immutable once established. They must not be changed after matrices have been built using them.

### 8.2 Known Axis Definitions (v0.8.0)

**P (Matter):** PA=essence · PE=unit · PI=configuration · PO=combination · PU=property

**T (Time):** TA=origin · TE=progression · TI=moment · TO=sequence · TU=cycle

**K (Social):** KA=origin · KE=structuring · KI=participation · KO=relation · KU=system

**B (Entity):** BA=emergence · BE=formation · BI=individuation · BO=relation · BU=system

**M (Mind):** MA=perception · ME=concept formation · MI=recognition · MO=reasoning · MU=cognition system

**G (Space):** GA=position · GE=extension · GI=distribution · GO=relation · GU=boundary

Additional domain axis definitions are documented in their respective domain files (01-p-domain.md, 02-t-domain.md, etc.).

---

## PART 9 — DIRECTIONALITY

### 9.1 The Asymmetry Rule

> **A + B ≠ B + A**

PT (Matter × Time) is not the same as TP (Time × Matter). Directionality encodes the relational meaning between domains.

**Rule:** Always specify which domain is the row (primary) and which is the column (secondary). The meaning changes with direction.

### 9.2 Semantic Tension Rule

**Rule:** Lexicalization is most productive when there is **semantic tension** between the two domains — not similarity, not redundancy.

- Distant domains crossing → high lexical density
- Similar or redundant domains crossing → low lexical density, more NVW
- Reflexive crossings (PP, TT, KK) → lowest density, mostly NVW except diagonal

---

## PART 10 — CRITICAL DISTINCTIONS

### 10.1 Ontological Type vs Usage Category

These are isomorphic but not equivalent:
- Ontological domain = structure of reality
- Usage category (C₃) = structure of human experience of reality

**Rule:** C₃ reflects the ontological domains but does not repeat them. It is a functional reindexation — same skeleton, different perspective.

### 10.2 State vs Configuration

**Rule:** State (being ill, being intact) belongs to domain R.
**Rule:** Configuration (form, arrangement, structure) belongs to domain L or to PI in the P-domain matrix.

Do not conflate state with configuration. When in doubt:
- If it describes **how something is arranged** → configuration (PI or L)
- If it describes **a condition of being** → state (R)

### 10.3 Process vs Entity

**Rule:** Processes belong to domain V. The nominal lexicon contains entities, not processes.

If a word-mother candidate describes something happening rather than something existing → it belongs in V, not in the lexicon as a noun-entry.

### 10.4 Usage Category vs Ontological Domain

**Rule:** C₃ (usage category) encodes dominant function in human use.
**Rule:** C₁C₂ (ontological address) encodes what the thing IS.

A word's ontological address never changes. A word's usage category is chosen once at assignment and remains stable.

---

## PART 11 — WHAT IS FORBIDDEN

The following are explicitly prohibited in the nominal lexicon:

1. **Forcing NVW cells** — never assign a word to a cell where the concept is too abstract or redundant
2. **Domain contamination** — a P-word must never describe something that belongs to Y, M, K, L, or V
3. **Process words as nouns** — words describing actions or changes belong to V
4. **Overriding C₁** — the primary domain consonant is immutable
5. **Free V₃ assignment without tendencies** — the gradation system must be consulted even when overridden
6. **Inventing new usage categories** — C₃ is a closed set of 20

---

## PART 12 — QUICK REFERENCE

### Decision Rules (in order of application)

1. C₁ always = primary domain. Never override.
2. Derive V₁ and V₂ from the matrix position.
3. C₂ preferentially = operational direction. Override only for phonetics or collision.
4. Check the cell against NVW conditions before assigning.
5. If valid, assign the word-mother (CVCV).
6. For Layer 2: choose C₃ from the official table by dominant human use.
7. Choose V₃ following the gradation tendencies (a=base → u=specialized).
8. Layer 3+ is free — assign for memorability and distinctiveness.
9. When in doubt about category: ask "what do humans use this FOR most often?"
10. When in doubt about domain purity: apply the four purity tests.

### The Three Disambiguation Questions

When uncertain about a word's classification, ask:

1. **What is it?** → determines C₁C₂ (ontological address)
2. **What is it used for, primarily?** → determines C₃ (usage category)
3. **Which specific one is it?** → determines V₃ and Layer 3+ (identity)

---

**File:** `Nominal_Lexicon_Checkpoint_v6.md`
**Version:** 0.8.0
**Date:** April 2026
**Status:** ✅ Active — rules manifesto, no tables

**Related files:**
- `10-lexicon-nominal.md` — Full documentation with tables
- `05-structure.md` — System architecture
- `09-ontological-system.md` — Ontological system
- `01-p-domain.md` through domain files — Matrix data

---

> *"Structure is not constraint — it is the framework that enables infinite expression."*
> *"The word does not carry the structure — it points to it."*
