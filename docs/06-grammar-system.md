# 06. Grammar System

_Version 0.8.0_

---

## Overview

The grammar operates through **operator chaining** — particles that modify the element immediately following them. There is no heavy morphology. Position carries meaning, and the most important element comes first.

**Core principles:**
- Modifier always precedes what it modifies
- The most important element comes first
- Grammar controls the relationship between speaker and listener — it does not describe the world

---

## The Two Layers

| Layer | Name | Format | Function |
|---|---|---|---|
| Deep | Sistema Ontológico | VCV + CV + CV... | Semantic infrastructure. Defines what something IS. |
| Surface | Léxico Nominal | CVCV + CV | Human interface. Names real things. Spoken language. |

Grammar acts on the surface layer. The ontological system is the underlying map.

---

## Word Classes

The language has one foundational class: **roots**. Every root belongs to a domain (first consonant C₁). Grammatical class emerges from operators and position — not from the word's form. Any word can function as noun, verb, or adjective.

---

## The V-Family — Functional Operators

The V-family is the grammatical engine. Its particles **precede the target word** and transform it into a specific grammatical function.

> **Rule:** *va* never appears alone. It always takes a following word as its nucleus.
> ❌ *ba va* (invalid — no nucleus)
> ✔ *ba va wa be* (valid — *wa* is the nucleus)

### CV — Function Activators

| Particle | Function | Equivalent | Example |
|---|---|---|---|
| **va** | activates as verb / action | to [verb] | *ba va wa be* = I love you |
| **ve** | activates as adjective / quality | -like, -ish | *ve para* = watery |
| **vi** | activates as instrument | used as, via | *vi pata* = using stone |
| **vo** | activates as collective / set | group of | *vo pata* = quarry |
| **vu** | emphasis / intensity | really, truly, very | *ba vu va wa be* = I REALLY love you |

### VC — Derivational Operators

| Particle | Function | Equivalent | Example |
|---|---|---|---|
| **av** | agent / doer | -er, -or | *av vapa* = runner |
| **ev** | having / causing the quality | -ous, -ful | *ev wa* = loving |
| **iv** | result / product | -ed, past participle | *iv vata* = the broken |
| **ov** | iterative / does repeatedly | habitual agent | *ov vapa* = chronic runner |
| **uv** | reciprocal / one another | mutual, inter- | *uv wa* = mutual love |

---

## Omission of *va*

*va* is omissible when predicative context is obvious:

| Form | Register | Meaning |
|---|---|---|
| *ba va wa be* | formal / explicit | I love you |
| *ba wa be* | subject present, *va* omitted | I love you |
| *wa be* | colloquial / obvious | love you |

---

## Emphasis — *vu*

*vu* intensifies the element immediately following it. Scope is strictly local — it modifies only the next block.

```
ba vu va wa be     → I REALLY love you (emphasis on action)
ba vu ve wa        → I am VERY loving (emphasis on attribute)
ba va wa vu be     → I love YOU specifically (emphasis on object)
vu ba va wa be     → TRULY, I love you (emphasis on whole utterance)
```

*vu* combines freely with other operators:
```
ha vu ba va wa be  → I REALLY do love you (certainty + emphasis)
hu vu ba va wa be  → I absolutely do NOT love you (negation + emphasis)
ba vu va wa be ha  → I REALLY love you, right? (emphasis + confirmation)
```

---

## The H-Family — Interaction Operator

H is a **two-dimensional interaction operator**. It controls the relationship between speaker and listener — not logical truth.

| Position | Function |
|---|---|
| **Sentence-initial** | Speaker's position (affirmation, negation, doubt) |
| **Sentence-final** | Alignment demand (confirmation, questioning) |

### H Values — Vowel = Degree of Certainty

| Form | Initial meaning | Final meaning |
|---|---|---|
| **ha** | yes / affirmation | "right?" / "isn't it?" |
| **he** | probably yes | "you think so?" |
| **hi** | maybe / uncertain | "could it be?" |
| **ho** | probably not | "don't you think?" |
| **hu** | no / negation | "isn't it not?" |

> **Key rule:** The vowel encodes certainty degree. Intonation encodes the speech act.
> *ha.* = yes (statement) / *ha?* = yes? (question) / *ha!* = yes! (exclamation)

### H in Initial Position — Speaker's Position

```
ha ba va wa be     → I love you (affirmation)
hi ba va wa be     → maybe I love you (doubt)
hu ba va wa be     → I don't love you (negation)
```

### H in Final Position — Alignment Demand

```
ba va wa be ha     → I love you, right?
ba va wa be hi     → I love you… could that be?
ba va wa be hu     → I don't love you, is that right?
```

### H in Both Positions — Full Framing

```
ha ba va wa be ha  → I love you, don't I?
hi ba va wa be ha  → maybe I love you… right?
hu ba va wa be hi  → I don't love you… or do I?
```

---

## Negation — *hu*

*hu* (H-family) is the negation operator. Its scope depends on position:

| Form | Scope | Meaning |
|---|---|---|
| *hu ba va wa be* | global (initial) | I don't love you |
| *ba hu va wa be* | local (before verbal block) | I don't do the loving |
| *ba va hu wa be* | local (before nucleus) | I do the not-loving |

*hu* + *vu* = emphatic negation:
```
hu vu ba va wa be   → I absolutely do NOT love you
ba hu vu va wa be   → I truly don't do this
```

---

## Sentence Structure

General template (everything optional except the nucleus):

```
[H-initial]  [vu]  [MODIFIERS]  [SUBJECT]  [va]  [NUCLEUS]  [OBJECT]  [L-contrast]  [H-final]
```

**The most important element comes first.** Any element can be fronted. The structure remains interpretable because:
1. The first B-particle before *va* = default subject anchor
2. Modifiers always precede what they modify
3. H marks the interactional frame

### Basic Examples

```
ba va wa be             → I love you
wa be                   → love you (colloquial)
ba va pata nana         → I work stone on the soil
ha ba va wa be ha       → I really love you, don't I?
```

---

## Tense — The T Operator

T-family particles anchor a process to a time. **Optional.**

| Particle | Function |
|---|---|
| **ta** | distant past |
| **te** | near past |
| **ti** | present |
| **to** | near future |
| **tu** | distant future |

```
ba te va wa be     → I liked you (recently)
ba ta va wa be     → I loved you (long ago)
ba tu va wa be     → I will love you
```

Absence of T = general / atemporal / habitual reading.

---

## Aspect — The G Operator

| Particle | Function |
|---|---|
| **ga** | punctual (single moment) |
| **ge** | cyclic / habitual |
| **gi** | ongoing / in progress |
| **go** | continuous / sustained |
| **gu** | complete / finished |

```
ba gi va wa be     → I am loving you (ongoing)
ba gu va wa be     → I finished loving you
ba ge va wa be     → I habitually love you
```

---

## Modality — The M Operator

| Particle | Function |
|---|---|
| **ma** | can, be able to |
| **me** | may, be allowed to |
| **mi** | factual / indicative |
| **mo** | must, should |
| **mu** | certainly, inevitably |

```
ba ma va wa be     → I can love you
ba mo va wa be     → I must love you
ba mu va wa be     → I will certainly love you
```

---

## Operator Stacking

Operators stack left-to-right, each modifying the next:

```
[H]  [vu]  [M]  [T]  [G]  [Subject]  [va]  [Nucleus]  [Object]
```

### Examples

```
ba vu ma va wa be           → I can REALLY love you
ba ma te gi va wa be        → I could have been loving you
ha vu ma ta ba va wa be ha  → could I REALLY have loved you? right?
```

---

## Questions

**Yes/no questions** — use H-final or H-initial with rising intonation:
```
ba va wa be ha?    → do I love you?
ha ba va wa be?    → do I really love you?
```

**Content questions** — K-family reference words + H:
```
ba va wa ke ha     → who do I love?
ki ba va wa be ha  → where do I love you?
```

K-family (*ka* = who, *ke* = what, *ki* = where, *ko* = when, *ku* = why, *ik* = how) works in both declarative and interrogative contexts. H marks the interrogative mode via intonation.

---

## Contrast — The L Operator

| Particle | Function | Example |
|---|---|---|
| **la** | and, also | *ba va wa be la bi va wa bi* |
| **le** | or | *wa le ma* = love or thought |
| **li** | but, however | *ba va wa be li ba hu va wa bi* |
| **lo** | therefore | *ba va wa be lo ba vu va patu be* |
| **lu** | if, provided that | *lu ba va wa be lo ba gu* |

---

## Emotional Predicates — W-Family

W-family words function directly as predicates without *va*:

| Particle | Meaning |
|---|---|
| **wa** | love |
| **we** | like |
| **wi** | neutral / indifferent |
| **wo** | dislike |
| **wu** | hate |

```
ba wa be           → I love you
ba we para         → I like water
bi wu nana         → he hates soil
```

W follows **inverted gradation**: a = most positive, u = most negative.

---

## Three Independent Axes

The grammar has three distinct expressivity dimensions:

| Axis | Operator | Function |
|---|---|---|
| **Interaction** | H (initial/final) | speaker's position + listener alignment |
| **Intensity** | vu | emphasis and force |
| **Focus** | word order / fronting | what matters most |

These three axes are independent and combinable:
```
ha vu ba va wa za be ha
→ I REALLY love YOU specifically, right?
  (affirmation + emphasis + fronting + focus on object + confirmation)
```

---

## Summary of Rules

| Rule | Description |
|---|---|
| Most important first | Front any element to prioritize it |
| Modifier before modified | All operators precede their target |
| *va* = verbal activator | Transforms any following word into verb |
| *va* never alone | Must always be followed by a nucleus |
| *va* omissible | When predicative context is obvious |
| *vu* = emphasis | Intensifies the immediately following element |
| H-initial = speaker position | Affirmation / negation / doubt |
| H-final = alignment demand | Confirmation / questioning |
| H vowel = certainty degree | ha=yes, he=probable, hi=uncertain, ho=probably not, hu=no |
| H intonation = speech act | ↓ statement / ↑ question / ↓! exclamation |
| *hu* = negation | Global (initial) or local (before target element) |
| *hu* + *vu* = emphatic negation | Absolute denial |
| T = tense (optional) | Temporal anchoring |
| G = aspect (optional) | How action unfolds |
| M = modality (optional) | Possibility, necessity |
| First B before *va* = subject | Default subject anchor in flexible word order |
| L = contrast / conjunction | Connects clauses logically |

---

## Relationship to the Ontological System

- **Ontology** defines what things ARE
- **Grammar** defines how things are communicated between people

The same root lives in both layers simultaneously — as a structural entity in the ontological system, and as a functional unit in spoken interaction. Grammar does not describe the world — it controls speech about the world.
