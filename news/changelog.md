# 📝 CHANGELOG — Universal Ontological Language

**Complete Version History and Development Log**

_All notable changes to this project will be documented in this file._

---

## [0.8.0] - 2026-04 — COMPOSITIONAL EC SYSTEM 🏗️

### **Major Release: Domain Remodeling and Transparent EC Derivation**

This version introduces a fundamental redesign of the domain ordering and the consonant cluster (EC) system. ECs are now **compositionally derived** from base domain combinations, making the system fully transparent — a speaker who knows the 20 base domains can infer EC meanings without memorization.

---

### 🎯 **BREAKING CHANGES**

#### **Domain Reordering**
All 20 base domains have been reordered by **ontological proximity** (concrete → abstract) for better systematic derivation of ECs:

| # | C | Domain |
|---|---|---|
| 1 | P | Matter |
| 2 | B | Entity |
| 3 | T | Time |
| 4 | G | Space |
| 5 | R | State |
| 6 | L | Structure |
| 7 | S | Quantity |
| 8 | D | Artifact |
| 9 | K | Social |
| 10 | N | Life |
| 11 | V | Action |
| 12 | J̌ | Motion |
| 13 | X | Causality |
| 14 | M | Mind |
| 15 | Ľ | Perception |
| 16 | Y | Information |
| 17 | W | Emotion |
| 18 | Z | Intensity |
| 19 | H | Environment |
| 20 | F | Interaction |

#### **EC Compositional Architecture**

R and L elevated to **ontological operators**:
- **R as second element** = "state of X" (condition, phase, applied being)
- **L as second element** = "structure of X" (form, organization, pattern)

**×R series (9 active):** PR, BR, TR, GR, KR, LR, MR, XR, FR

**×L series (10 active):** PL, BL, TL, GL, KL, NL, VL, ML, XL, FL

---

### ✨ **NEW FEATURES**

#### **Compositional EC Meanings**
All ECs now have transparent meanings derivable from their component domains:
- **PR** (P+R) = Physical state / material condition
- **BR** (B+R) = Identity (entity as state)
- **FL** (F+L) = Interface / boundary / structured interaction
- etc.

#### **Domain Definitions Sharpened**
- **H** reassigned from Dwelling/Shelter to **Environment** (surrounding context, habitat)
- **F** reassigned from Food/Nutrition to **Interaction** (contact, exchange, interface)
- **FL** now covers Dwelling/Shelter as a derived EC (F+L = structured interaction)

#### **Grammar — Family V Reformulated**
V-family is now a system of **activation and derivation operators** (all pre-word):

**CV — Function Activators:**
| Particle | Function |
|---|---|
| va | activates as verb/action |
| ve | activates as adjective/quality |
| vi | activates as instrument |
| vo | activates as collective/set |
| vu | emphasis / intensity |

**VC — Derivational Operators:**
| Particle | Function |
|---|---|
| av | agent / doer |
| ev | having/causing the quality |
| iv | result / product |
| ov | iterative / does repeatedly |
| uv | reciprocal / one another |

#### **Grammar — Family H Reformulated**
H is now a **two-dimensional epistemic/interaction operator**:
- **Initial position** = speaker's epistemic stance (ha=yes, he=probable, hi=uncertain, ho=probably not, hu=no)
- **Final position** = alignment demand from listener ("right?", "isn't it?")
- **Intonation** = speech act type (statement, question, exclamation)

#### **Grammar — Negation System Clarified**
- **hu** (H-family) = negation operator (global when initial, local when before target)
- **vu** (V-family) = emphasis/intensity (not negation)
- **hu + vu** = emphatic negation

#### **Grammar — Family W Updated**
W-family reformulated as primary emotional scale:
- wa = love / we = like / wi = neutral / wo = dislike / wu = hate

---

### 📁 **DOCUMENTATION STRUCTURE**

Docs folder finalized:
```
01-philosophy.md
02-phonology.md
03-core-uva.md
04-primary-and-informal-concepts.md
05-structure.md
06-grammar-system.md
07-grammar-cv-vc.md
08-expanded-grammar-vcv.md
09-ontological-system.md
10-lexicon-nominal.md
11-3D-spatial-coordinates.md
Nominal_Lexicon_Checkpoint_v5.md
```

---

### 🔧 **IMPROVEMENTS**

- Grammar system overview consolidated in `06-grammar-system.md`
- CV/VC system expanded to 30 families (20 base + 10 active ECs + 1 reserved GL)
- VCV system: 750 particles (30 families × 25)
- Operator stacking formalized: `[H] [vu] [M] [T] [G] [Subject] [va] [Nucleus] [Object] [L] [H]`

---

## [0.7.4] - 2026-04 — GRAMMAR FINALIZATION

### **Minor Release: Grammar Completion and EC Expansion**

---

### ✨ **NEW FEATURES**

#### **New Active ECs**
- **BL** /bl/ — Identity / Self
- **KL** /kl/ — Energy / Force
- **FL** /fl/ — Dwelling / Shelter (freed H for Expression/Interjection)
- **FR** /fɾ/ — Force / Interaction (push, pull, hold, hit, release)

#### **Family H — Expression / Interjection**
H freed from Relation domain and reassigned to discourse/expression:
- CV: ha=interrogative, he=confirmation, hi=topic marker, ho=surprise, hu=hesitation
- VC: ah=emphasis, eh=doubt, ih=indecision, oh=citation, uh=emphatic denial
- VCV: full set of nuanced expressions documented

#### **Family K — Reference Words**
K formalized as reference words usable in both interrogative and declarative contexts. H-family marks interrogative mode separately.

#### **VCV System Complete**
- 750 particles total (30 families × 25)
- All EC families documented (BL, KL, FL, FR + previous 7)

---

### 🔧 **IMPROVEMENTS**

- Family M: VC removed (negation handled by V-family)
- Family S: *us* removed (redundant with *su*)
- EC TR: deactivated (covered by X/Y/Z + G + P)
- GL reserved for future expansion

---

## [0.7.0] - 2026-03/04 — DUAL-LAYER ARCHITECTURE

### **Major Release: Ontological and Lexical System Separation**

---

### 🎯 **BREAKING CHANGES**

#### **Dual-Layer Architecture Formalized**
- **Sistema Ontológico** (VCV+CV+CV...): semantic infrastructure, defines what something IS
- **Léxico Nominal** (CVCV+CV): human interface, usable spoken words

#### **Semantic Axis Law Established**
> C₂ defines OPERATIONS, not concepts.
> Meaning = Ontology (C₁) × Operation (C₂)

---

### ✨ **NEW FEATURES**

#### **17 C₂ Axes Finalized**
T, K, V, R, M, B, G, J̌, S, F, H, N, D, L, Ľ, W, X axes fully defined with 5-step progressions.

#### **Domain Matrix System**
- 7 nucleus matrices finalized: PP, MM, BB, YY, ĽĽ, TRTR, DRDR
- 17 directional matrices P× completed: PT, PK, PB, PM, PG, PV, PR, PJ̌, PS, PF, PH, PN, PD, PL, PĽ, PW, PX
- PAPA field lexicon: 36 words (water=para, stone=pata, soil=pana...)

#### **Nominal Lexicon Projection Rules**
- C₁ = MANDATORY (primary domain)
- C₂ = PREFERENTIAL (soft clustering, overridable)
- Vowels = FREE (purely distinctive)
- Length = FREQUENCY (shorter = more common)

#### **Exception Group Formalized**
W, X, Y, Z confirmed as exception group with inverted gradation rules.

---

### 📚 **DOCUMENTATION**

- README v0.7.0 created
- Nominal_Lexicon_Checkpoint_v1 through v5 created
- Complete documentation suite in English

---

## [0.6.0] - 2026-03-19 — FOUNDATION COMPLETE 🎉

### **Major Release: Complete Restructuring**

---

### 🎯 **BREAKING CHANGES**

#### **Spatial Coordinate System Unification**
- X, Y, Z now exclusively spatial across all systems
- Old Y (Intensity/Degree) → GR /gɾ/ (EC)
- Old Z (Intention/Volition) → PL /pl/ (EC)

#### **Inverted Gradation Rule**
- W-family: a=positive → u=negative
- X, Y, Z: a=max(+) → u=min(−)

---

### ✨ **NEW FEATURES**

- EC GR /gɾ/ — Intensity/Degree added
- EC PL /pl/ — Intention/Volition added
- Complete 3D Cartesian coordinate system: `[X-vowel]+[Y-vowel]+[Z-vowel]`
- 675 CVCV base words created across 27 domains
- VEC pronunciation rule: isolated V+EC → nasal final vowel

---

### 📚 **DOCUMENTATION**

- README.md, WELCOME.md, INDEX.md, LEARNING-PATH.md created
- All documentation translated to English
- 05-grammar-cv-vc.md and 06-basics-vcv.md updated

---

## [0.5.x] - 2025-2026 — Development Phase

### [0.5.3] - 2026-02 — VCV Experimentation
- Initial VCV particle development
- Experimental domain structures

### [0.5.2] - 2025-12 — Grammar Expansion
- VC system development
- Modal and aspectual particles

### [0.5.1] - 2025-10 — Initial Documentation
- First grammar documentation (Portuguese)
- Basic vocabulary lists

### [0.5.0] - 2025-08 — Early Structure
- 25-consonant alphabet (later reduced to 20)
- Initial CV particle system

---

## [0.4.x] - 2024-2025 — Conceptual Phase

### [0.4.0] - 2024-12 — Foundation Concepts
- Ontological domain concept
- Vowel gradation principles
- Systematic structure ideas

---

## [0.3.x and earlier] - 2024 — Experimental Phase

- Different phonological systems tested
- Multiple grammatical approaches explored
- Vocabulary organization strategies
- Learning from natural and constructed languages

---

## Version Numbering Scheme

**Format:** MAJOR.MINOR.PATCH

- **MAJOR (0):** Pre-1.0 development phase
- **MINOR:** Significant structural changes
- **PATCH:** Bug fixes and minor improvements

**1.0.0 will represent:** Complete language specification with comprehensive corpus

---

**Last Updated:** April 2026
**Current Version:** 0.8.0
**Next planned:** 0.9.0 — Lexicon expansion and translation corpus
