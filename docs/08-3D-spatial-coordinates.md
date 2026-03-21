# 🧭 3D Spatial Coordinates

**Integrated Spatial Positioning and Movement**

_Version 0.6.5 — Complete Cartesian Implementation_

---

## 🎯 Overview

The language features a **complete 3D spatial coordinate system** using the X, Y, Z consonants in grammar (CV/VC/VCV particles). This system allows precise specification of position, direction, and movement in three-dimensional space through systematic vowel gradation.

**Core Principle:** Three axes (X, Y, Z) × Five vowels (a, e, i, o, u) = Complete spatial expression

**Important:** This is the **grammatical** function of X, Y, Z. In nominal lexicon (CVCV words), these same consonants represent different ontological domains (Causality, Knowledge, Intensity).

---

## 📐 THE THREE AXES

### **X-Axis — Lateral (Left ↔ Right)**

**Consonant:** X /ʃ/  
**Orientation:** Horizontal, perpendicular to body  
**Reference frame:** Speaker-relative or absolute

| Vowel | Position | Description | Coordinate |
|-------|----------|-------------|------------|
| **xa** | Maximum right | Extreme right position | (+1, 0, 0) |
| **xe** | Mid-right | Moderately right | (+0.5, 0, 0) |
| **xi** | Center | On centerline (neither left nor right) | (0, 0, 0) |
| **xo** | Mid-left | Moderately left | (−0.5, 0, 0) |
| **xu** | Maximum left | Extreme left position | (−1, 0, 0) |

**Inverted gradation:** a = maximum positive (+), u = maximum negative (−)

---

### **Y-Axis — Frontal (Back ↔ Front)**

**Consonant:** Y /ʒ/  
**Orientation:** Horizontal, parallel to body facing  
**Reference frame:** Speaker-relative or absolute

| Vowel | Position | Description | Coordinate |
|-------|----------|-------------|------------|
| **ya** | Maximum front | Extreme forward position | (0, +1, 0) |
| **ye** | Mid-front | Moderately forward | (0, +0.5, 0) |
| **yi** | Center | On midline (neither front nor back) | (0, 0, 0) |
| **yo** | Mid-back | Moderately backward | (0, −0.5, 0) |
| **yu** | Maximum back | Extreme backward position | (0, −1, 0) |

**Inverted gradation:** a = maximum positive (+), u = maximum negative (−)

---

### **Z-Axis — Vertical (Down ↔ Up)**

**Consonant:** Z /z/  
**Orientation:** Vertical  
**Reference frame:** Gravity-based or relative

| Vowel | Position | Description | Coordinate |
|-------|----------|-------------|------------|
| **za** | Maximum up | Extreme upper position | (0, 0, +1) |
| **ze** | Mid-up | Moderately elevated | (0, 0, +0.5) |
| **zi** | Center | On horizontal plane | (0, 0, 0) |
| **zo** | Mid-down | Moderately lowered | (0, 0, −0.5) |
| **zu** | Maximum down | Extreme lower position | (0, 0, −1) |

**Inverted gradation:** a = maximum positive (+), u = maximum negative (−)

---

## 🎯 CV SPATIAL PARTICLES — STATIC POSITION

### **Usage:** Marking static location on each axis

**Syntax:** [noun] + [spatial CV particle]

**Examples:**

```
[object] xa = object at-right
[object] yi = object at-center-front-back
[object] za = object at-top
```

**Combined axes (using multiple particles):**
```
[object] xa ya za = object at top-right-front corner
[object] xu yu zu = object at bottom-left-back corner
[object] xi yi zi = object at absolute center
```

---

### **Complete CV Spatial Paradigm**

**X-axis particles:**
- **xa** /ʃa/ = at extreme right
- **xe** /ʃe/ = at mid-right
- **xi** /ʃi/ = at lateral center
- **xo** /ʃo/ = at mid-left
- **xu** /ʃu/ = at extreme left

**Y-axis particles:**
- **ya** /ʒa/ = at extreme front
- **ye** /ʒe/ = at mid-front
- **yi** /ʒi/ = at frontal center
- **yo** /ʒo/ = at mid-back
- **yu** /ʒu/ = at extreme back

**Z-axis particles:**
- **za** /za/ = at extreme top
- **ze** /ze/ = at mid-top
- **zi** /zi/ = at vertical center
- **zo** /zo/ = at mid-bottom
- **zu** /zu/ = at extreme bottom

---

## 🔄 VCV SPATIAL PARTICLES — MOVEMENT PATTERNS

### **Structure:** [Initial Vowel][Consonant][Final Vowel]

- **Initial vowel** = Starting position
- **Consonant** = Axis of movement
- **Final vowel** = Ending position

### **Movement Types**

**Stationary:** Same vowel on both sides
```
axa = stays at extreme right
ixi = stays at center
uzu = stays at extreme bottom
```

**Directional:** Different vowels
```
axu = moves from right to left (full traverse)
uxa = moves from left to right (full traverse)
azi = moves from top to center
iza = moves from center to top
```

**Partial movement:**
```
axe = moves from extreme right to mid-right (slight leftward)
exa = moves from mid-right to extreme right (slight rightward)
```

---

### **Complete VCV Movement Matrix (Example: X-axis)**

| VCV | Movement | Description |
|-----|----------|-------------|
| **axa** | (+) → (+) | Stays at extreme right |
| **axe** | (+) → (+/2) | Right to mid-right |
| **axi** | (+) → (0) | Right to center |
| **axo** | (+) → (−/2) | Right to mid-left |
| **axu** | (+) → (−) | Right to extreme left (full traverse) |
| **exa** | (+/2) → (+) | Mid-right to extreme right |
| **exe** | (+/2) → (+/2) | Stays at mid-right |
| **exi** | (+/2) → (0) | Mid-right to center |
| **exo** | (+/2) → (−/2) | Mid-right to mid-left |
| **exu** | (+/2) → (−) | Mid-right to extreme left |
| **ixa** | (0) → (+) | Center to extreme right |
| **ixe** | (0) → (+/2) | Center to mid-right |
| **ixi** | (0) → (0) | Stays at center |
| **ixo** | (0) → (−/2) | Center to mid-left |
| **ixu** | (0) → (−) | Center to extreme left |
| **oxa** | (−/2) → (+) | Mid-left to extreme right |
| **oxe** | (−/2) → (+/2) | Mid-left to mid-right |
| **oxi** | (−/2) → (0) | Mid-left to center |
| **oxo** | (−/2) → (−/2) | Stays at mid-left |
| **oxu** | (−/2) → (−) | Mid-left to extreme left |
| **uxa** | (−) → (+) | Extreme left to extreme right (full traverse) |
| **uxe** | (−) → (+/2) | Extreme left to mid-right |
| **uxi** | (−) → (0) | Extreme left to center |
| **uxo** | (−) → (−/2) | Extreme left to mid-left |
| **uxu** | (−) → (−) | Stays at extreme left |

**Total per axis:** 25 movement patterns (5×5)  
**Total all axes:** 75 movement patterns (25×3)

---

## 🗺️ 3D COORDINATE SPECIFICATION

### **Format:** Combine X, Y, Z particles/VCVs

**Static position (CV):**
```
xa yi za = at (right, center-Y, top)
xi yi zi = at (center-X, center-Y, center-Z) = absolute center
xu yu zu = at (left, back, bottom)
```

**3D Coordinates as sequence:**
```
Position: X-vowel + Y-vowel + Z-vowel

Examples:
aaa = (+1, +1, +1) = top-right-front corner
uuu = (−1, −1, −1) = bottom-left-back corner
iii = (0, 0, 0) = absolute center
aia = (+1, 0, +1) = top-right, center-depth
```

---

### **3D Movement (VCV sequences):**

**Specify movement on each axis independently:**

```
[object] axa aya aza
= object stays at top-right-front corner (stationary in all axes)

[object] axu aya aza
= object moves left while staying at front-top

[object] axi iyi azi
= object: right→center, stays Y-center, top→Z-center
```

---

## 📍 REFERENCE FRAMES

### **Speaker-Relative (Default)**

**Orientation:** Based on speaker's perspective
- **X-axis:** Speaker's left/right
- **Y-axis:** Speaker's front/back
- **Z-axis:** Speaker's up/down

**Usage:**
```
xa = to my right
ya = in front of me
za = above me
```

---

### **Object-Relative**

**Orientation:** Based on object being described
- **X-axis:** Object's left/right
- **Y-axis:** Object's front/back
- **Z-axis:** Object's up/down

**Usage (with possessive marker):**
```
[object] bi xa = its right side
[object] bi ya = its front
[object] bi za = its top
```

---

### **Absolute (Cardinal)**

**Orientation:** Fixed environmental reference
- **X-axis:** East (+) / West (−)
- **Y-axis:** North (+) / South (−)
- **Z-axis:** Up (+) / Down (−) (gravity-based)

**Usage (with absolute marker):**
```
xa [absolute marker] = eastward
ya [absolute marker] = northward
za [absolute marker] = upward
```

---

## 🎯 PRACTICAL APPLICATIONS

### **1. Giving Directions**

```
be va pa xa = you go to-right (go right)
be va pa ya = you go to-front (go forward)
be va pa za = you go to-up (go up)

Combined:
be va pa xa ya = you go to right-front (go diagonally forward-right)
```

---

### **2. Describing Locations**

```
[object] vi pi xa = object is at right
[object] vi pi xi yi zi = object is at center (all axes)
[object] vi pi xu yu zu = object is at left-back-bottom corner
```

---

### **3. Indicating Movement**

```
[object] va axu = object does right→left (moves leftward)
[object] va aya = object does stay-front (stays in front)
[object] va izi = object does center→center-Z (stays at mid-height)
```

---

### **4. Specifying Trajectories**

```
[object] va axu aya azi
= object moves: X(right→left), Y(stays-front), Z(top→center)
= "moves leftward while staying forward and descending to middle"
```

---

## 🎨 COMMON SPATIAL EXPRESSIONS

### **Cardinal Directions (Absolute Frame)**

```
xa = east / eastward
xu = west / westward
ya = north / northward
yu = south / southward
za = up / upward / skyward
zu = down / downward / groundward
```

---

### **Relative Positions**

```
xa = right side
xu = left side
ya = front side
yu = back side
za = top side / upper part
zu = bottom side / lower part
xi = middle (lateral)
yi = middle (frontal)
zi = middle (vertical)
```

---

### **3D Corners**

```
xa ya za = top-right-front corner
xa ya zu = bottom-right-front corner
xa yu za = top-right-back corner
xa yu zu = bottom-right-back corner
xu ya za = top-left-front corner
xu ya zu = bottom-left-front corner
xu yu za = top-left-back corner
xu yu zu = bottom-left-back corner
```

---

### **Movement Patterns**

```
Oscillation:
axu, uxa, axu, uxa... = back-and-forth (left-right)
aya, uyu, aya, uyu... = back-and-forth (front-back)
aza, uzu, aza, uzu... = back-and-forth (up-down)

Circular (XY plane):
axa → aya → uxa → uyu → axa = clockwise square
axa → uyu → uxa → aya → axa = counterclockwise square

Spiral:
Combine gradual X-Y rotation with Z-axis movement
```

---

## 🔧 Integration with Grammar

### **With Prepositions (P-family)**

```
pa xa = to-right (allative + position)
pi xa = at-right (locative + position)
po xa = from-right (ablative + position)

Combined motion:
pa [via] axu = to [destination] via right→left path
```

---

### **With Demonstratives (D-family)**

```
di xa = this one-at-right
da xu yu zu = that one-at left-back-bottom
do xa? = which right? (which one on the right?)
```

---

### **With Verbs (V-family)**

```
va axu = do right→left = move leftward
ve aza = become top→high = rise
vi pi xi yi zi = be at center = be centered
```

---

## 📊 Coordinate Precision Levels

### **Coarse (CV only)**

5 positions per axis:
```
X: xa, xe, xi, xo, xu (5 positions)
Y: ya, ye, yi, yo, yu (5 positions)
Z: za, ze, zi, zo, zu (5 positions)

Total positions: 5³ = 125 discrete locations
```

---

### **Fine (VCV)**

25 movement states per axis:
```
X: axa, axe, axi... (25 states)
Y: aya, aye, ayi... (25 states)
Z: aza, aze, azi... (25 states)

Total states: 25³ = 15,625 possible movement combinations
```

---

### **Continuous (Natural Language)**

Combine multiple VCV sequences for smooth paths:
```
[object] va axi, exi, ixi, oxi, uxi
= object moves: right → mid-right → center → mid-left → left
= smooth rightward-to-leftward traverse
```

---

## 🎯 Teaching Sequence

### **Week 1: Single Axis (Z - Vertical)**

**Easiest:** Vertical is universal (gravity-based)

```
za = top
zi = middle
zu = bottom

Practice: Describing object heights
```

---

### **Week 2: Add X-Axis (Lateral)**

```
xa = right
xi = center
xu = left

Practice: Left-right positioning
```

---

### **Week 3: Add Y-Axis (Frontal)**

```
ya = front
yi = middle
yu = back

Practice: Front-back positioning
```

---

### **Week 4: Combine Axes**

```
3D corners: xa ya za, xu yu zu, etc.
Practice: Complete spatial descriptions
```

---

### **Month 2: Movement (VCV)**

```
Static → Dynamic
axa (stays right) vs. axu (moves right→left)

Practice: Describing motions
```

---

## 🌍 Cultural & Contextual Uses

### **Architecture & Interior Design**

```
[room] vi pi xi yi zi = room is centered
[furniture] vi pi xa ya = furniture is at right-front
[window] vi pi za = window is at top
```

---

### **Navigation & Wayfinding**

```
be va pa xa ya = you go to right-front
[path] va axu = path goes rightward-to-leftward
[destination] vi pi xu yu = destination is at left-back
```

---

### **Dance & Choreography**

```
VCV sequences for movement:
axa → axe → axi → axo → axu = smooth leftward glide
aya → uyu → aya = forward-back-forward step
```

---

### **Sports & Physical Activity**

```
[ball] va aza = ball goes upward (rises)
[player] va axu aya = player moves left-staying-forward
[object] va uxi uyi uzi = object moves toward center (all axes)
```

---

## 🎨 Advanced Patterns

### **Relative Motion**

**Two objects' relative positions:**

```
[object1] xa, [object2] xu = object1 right, object2 left
= objects on opposite sides

[object1] axa, [object2] axu
= object1 stays right, object2 moves to left
= objects diverging
```

---

### **Velocity Indication**

**Speed through particle repetition or modifiers:**

```
Slow: va axi oxi uxi (gradual center→left traverse)
Fast: va axu (direct right→left)
```

---

### **Curved Paths**

**Combine axes for non-linear movement:**

```
va axa aya (stay right-front)
→ va axe aye (move to mid-right, mid-front)
→ va axi ayi (move to center, stay front)
= curved path toward center
```

---

## 📐 Mathematical Representation

### **Coordinate Notation**

```
Vowel → Numeric value:
a = +1
e = +0.5
i = 0
o = −0.5
u = −1

Examples:
xa yi za = (1, 0, 1)
xu yu zu = (−1, −1, −1)
xe yo zi = (0.5, −0.5, 0)
```

---

### **Vector Notation (VCV)**

```
VCV = (start, end)

axu = X-axis: (1, −1) = Δ = −2 (full leftward)
aza = Z-axis: (1, 1) = Δ = 0 (stationary up)
ixi = X-axis: (0, 0) = Δ = 0 (stationary center)
```

---

## 🎯 Summary

**CV Spatial (Static):**
- 15 particles (5 per axis × 3 axes)
- Static position marking
- Simple and essential

**VCV Spatial (Dynamic):**
- 75 particles (25 per axis × 3 axes)
- Movement and trajectory
- Nuanced and expressive

**3D Combinations:**
- CV: 125 discrete positions (5³)
- VCV: 15,625 movement states (25³)
- Infinite smooth paths through sequencing

---

**File:** `07-vector-system.md`  
**Version:** 0.6.5  
**Status:** ✅ Complete — 3D spatial coordinate system documented

**Related Documentation:**
- **[04-structure.md](04-structure.md)** — Dual function of X, Y, Z
- **[05-grammar-cv-vc.md](05-grammar-cv-vc.md)** — X, Y, Z families in grammar
- **[06-basics-vcv.md](06-basics-vcv.md)** — VCV movement patterns
- **[02-phonology.md](02-phonology.md)** — Pronunciation of X, Y, Z

---

> *"In three dimensions, five vowels locate everything."*

---
