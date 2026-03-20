# 📝 CHANGELOG — Conlang Project

**Complete Version History and Development Log**

_All notable changes to this project will be documented in this file._

---

## [0.6.0] - 2026-03-19 — FOUNDATION COMPLETE 🎉

### **Major Release: Complete Restructuring**

This version represents the completion of the foundational phase of the language. The entire grammatical system has been restructured for maximum coherence and the nominal lexicon is now fully documented with 675 base words.

---

### 🎯 **BREAKING CHANGES**

#### **Spatial Coordinate System Unification**
- **X, Y, Z are now EXCLUSIVELY spatial** across all systems (CV, VC, VCV)
- Previous Y and Z grammatical functions migrated to new ECs
- Complete 3D Cartesian coordinate system implemented

**Migration:**
- Old Y (Intensity/Degree) → New **GR** /gɾ/ (EC)
- Old Z (Intention/Volition) → New **PL** /pl/ (EC)

**Rationale:** Eliminates dual-function confusion and creates a pure, integrated 3D spatial system

---

#### **Inverted Gradation Rule Clarification**
**Standard gradation:** a (min) → e → i → o → u (max)

**Exceptions (inverted):**
1. **W-family (Emotion):** a=positive → u=negative
2. **X-family (Spatial X-axis):** a=max(+) → u=min(−)
3. **Y-family (Spatial Y-axis):** a=max(+) → u=min(−)
4. **Z-family (Spatial Z-axis):** a=max(+) → u=min(−)

**Impact:** Spatial coordinates now follow intuitive mapping (a=high/right/front, u=low/left/back)

---

### ✨ **NEW FEATURES**

#### **Consonant System Expansion**
- **Added:** Consonant cluster **GR** /gɾ/ — Intensity/Degree
- **Added:** Consonant cluster **PL** /pl/ — Intention/Volition
- **Total consonants:** 20 base + 10 clusters (7 defined, 3 reserved)

#### **3D Spatial Coordinate System**
```
Structure: [X-vowel] + [Y-vowel] + [Z-vowel]

Examples:
- xiyizi = (0,0,0) absolute center
- xayaza = (+,+,+) top-right-front corner
- xuyuzu = (−,−,−) bottom-left-back corner
```

**Features:**
- Complete 3D positioning
- VCV movement expressions
- Coordinate-based navigation
- Integrated across all grammar layers

#### **VCV Movement Patterns**
```
[Vowel-Origin][Consonant-Axis][Vowel-Destination]

Examples:
- axu = X-axis: from right to left
- uxa = X-axis: from left to right
- aza = Z-axis: stays at top
- uze = Z-axis: rises from bottom to mid-high
```

#### **Complete Nominal Lexicon**
- **675 CVCV base words** systematically created
- **27 ontological domains** fully populated
- **All domains:** 25 words each (5 series × 5 gradations)

**Coverage:**
- P (Substance/Matter): Physical states
- B (Communication): Expression types
- M (Mind/Cognition): Mental processes
- T (Time/Temporality): Temporal concepts
- K (Social/Cultural): Human relations
- N (Nature/Living): Life and ecosystems
- D (Structure/Form): Shapes and patterns
- L (Light/Energy): Energy types
- V (Life/Vitality): Health and vigor
- G (Geography/Space): Landforms and territories
- R (Tool/Artifact): Tools and machines
- F (Food/Nutrition): Food and meals
- H (Dwelling/Shelter): Buildings and settlements
- S (Quantity/Measurement): Numbers and values
- J̌ (Motion/Movement): Speed and paths
- W (Weather/Climate): Weather phenomena
- Ľ (Knowledge/Information): Truth and sources
- [+ 7 EC domains: PR, BR, TR, DR, KR, GR, PL]

#### **Modifier System Finalization**
- **24 functional modifiers** documented (17 base + 7 EC)
- **5-vowel gradation** for each modifier (a→e→i→o→u)
- **120 variants** possible per base word
- **Rule clarified:** Modifier always final syllable, one per word maximum

#### **Pronunciation Rules**
**VEC (Vowel + EC) Rule:**
- Isolated V+EC → nasal final vowel: **agr** = /agɾã/
- V+EC+V → oral vowel: **agra** = /agɾa/

**Purpose:** Distinguish VEC from VECV in speech

---

### 📚 **DOCUMENTATION**

#### **New Documents**
- `README.md` — Complete project overview (English)
- `WELCOME.md` — Friendly introduction and orientation
- `INDEX.md` — Comprehensive navigation and reference
- `LEARNING-PATH.md` — Month-by-month curriculum (18 months)
- `09-lexicon-nominal-matrix.md` — Vocabulary system with examples
- `nominal-lexicon.md` — All 675 base words documented

#### **Updated Documents**
- `05-grammar-cv-vc.md` — Fully translated to English, updated with GR/PL
- `06-basics-vcv.md` — Complete VCV system (675 particles)

#### **Translations**
- All Portuguese documentation converted to English
- Consistent terminology throughout
- Professional presentation

---

### 🔧 **SYSTEM IMPROVEMENTS**

#### **Grammar Organization**
- **CV/VC particles:** 270 total (135 + 135)
- **VCV particles:** 675 total (27 families × 25)
- **Clear hierarchy:** CV (basic) → VC (extended) → VCV (nuanced)

#### **Lexicon Architecture**
```
[Domain][Subcategory][...Syllables...][Modifier]
  CV¹       CV²          CVⁿ             CV(final)

Position of modifier:
- 2-syllable base → modifier is 3rd syllable
- 3-syllable base → modifier is 4th syllable
- 4-syllable base → modifier is 5th syllable
```

#### **Gradation Systematization**
**Each CV² series gradates by most productive semantic property:**

Examples:
- P-domain: Physical state (gas, liquid, solid, granular, plasma)
- K-domain: Age (infant, child, adult, elder, ancestor)
- T-domain: Duration (instant, brief, medium, long, epoch)

**Result:** Highly productive and memorable patterns

---

### 📊 **STATISTICS**

**Vocabulary:**
- Base CVCV words: **675**
- With modifiers (24×5): **81,000** theoretical words
- Grammar particles (CV+VC+VCV): **945**

**Documentation:**
- Core files: **8** documents
- Total pages equivalent: **~2,000**
- Example sentences: **50+** (foundation set)

**System Coverage:**
- Phonemes: **35** (20 consonants + 10 clusters + 5 vowels)
- Grammatical domains: **27** (20 base + 7 ECs)
- Functional modifiers: **24** (17 base + 7 ECs)

---

### 🎓 **PEDAGOGICAL FRAMEWORK**

#### **Learning Levels Defined**
1. **Basic (0-6 months):** 100 words, CV/VC basics, simple conversation
2. **Intermediate (6-12 months):** 300 words, all modifiers, VCV intro, functional fluency
3. **Advanced (12-18 months):** 675+ words, complete VCV, full fluency
4. **Master (18+ months):** 2000+ words, creative expansion, native-like proficiency

#### **Curriculum Structure**
- Month-by-month breakdown
- Clear milestones
- Practice activities
- Assessment criteria

---

### 🐛 **BUG FIXES**

#### **Consistency Issues Resolved**
- **Fixed:** Y and Z dual-function confusion (grammar vs spatial)
- **Fixed:** Inconsistent gradation documentation
- **Fixed:** Missing EC definitions in earlier versions
- **Fixed:** Ambiguous modifier position rules

#### **Documentation Errors**
- **Fixed:** Portuguese-English terminology mismatches
- **Fixed:** Inconsistent IPA notation
- **Fixed:** Missing cross-references between documents
- **Fixed:** Outdated examples from previous versions

---

### 🔄 **CHANGES FROM v0.5.x**

#### **Removed/Deprecated**
- ❌ Y and Z as grammatical functions in CV/VC
- ❌ Inconsistent gradation patterns
- ❌ Ambiguous modifier rules
- ❌ Portuguese-only documentation
- ❌ Incomplete domain coverage

#### **Modified**
- ♻️ X, Y, Z redefined as pure spatial coordinates
- ♻️ Modifier system clarified (one per word, final position)
- ♻️ VCV families restructured for consistency
- ♻️ Example words updated for clarity

#### **Added**
- ✅ GR and PL consonant clusters
- ✅ Complete 675-word lexicon
- ✅ 3D spatial coordinate system
- ✅ Comprehensive English documentation
- ✅ Learning path curriculum
- ✅ Navigation index

---

### 📖 **EXAMPLES**

#### **Spatial Coordinates**
```
xiyizi = (0,0,0) center
xayaza = (+,+,+) top-right-front
xoyozo = (−,−,−) bottom-left-back (moderate)
```

#### **Modified Words**
```
pepi (liquid) base word:
→ pepima = drop (magnitude-min)
→ pepimi = pond (magnitude-med)
→ pepimu = ocean (magnitude-max)
→ pepiva = still water (movement-min)
→ pepivu = waterfall (movement-max)
→ pepilu = pure water (quality-max)
```

#### **Grammatical Particles**
```
Old system:
ya, ye, yi, yo, yu = intensity/degree (REMOVED)

New system:
gra, gre, gri, gro, gru = intensity/degree (EC GR)
ya, ye, yi, yo, yu = Y-axis spatial position
```

---

### 🙏 **ACKNOWLEDGMENTS**

This version represents a complete foundation for the language. Special recognition for:
- Systematic restructuring of spatial grammar
- Complete domain population (675 words)
- Professional documentation suite
- Clear learning pathway

---

### 📋 **MIGRATION GUIDE**

#### **For Users of v0.5.x**

**Action Required:**
1. **Update spatial references:** Y/Z are now purely spatial
2. **Use GR for intensity:** Where you used Y-particles for intensity, use GR
3. **Use PL for intention:** Where you used Z-particles for intention, use PL
4. **Review modifier usage:** Ensure modifier is final syllable only

**Example Migration:**
```
Old (v0.5.x):
- ya = weak intensity
- yu = strong intensity

New (v0.6.0):
- gra = weak intensity
- gru = strong intensity
- ya = extreme front (spatial Y-axis)
- yu = extreme back (spatial Y-axis)
```

---

### 🎯 **WHAT'S NEXT**

See `ROADMAP.md` for detailed future plans.

**Immediate priorities (v0.6.1 - April 2026):**
- 100 essential 3-syllable words
- 200 basic example sentences
- Audio recording planning

---

## [0.5.x] - 2025-2026 — Development Phase

### **[0.5.3] - 2026-02** — VCV Experimentation
- Initial VCV particle development
- Experimental domain structures
- Vector-based approaches tested

### **[0.5.2] - 2025-12** — Grammar Expansion
- VC system development
- Modal and aspectual particles
- Spatial grammar experimentation

### **[0.5.1] - 2025-10** — Initial Documentation
- First grammar documentation
- Portuguese-language materials
- Basic vocabulary lists

### **[0.5.0] - 2025-08** — Early Structure
- 25-consonant alphabet (later reduced to 20)
- Initial CV particle system
- Concept development

---

## [0.4.x] - 2024-2025 — Conceptual Phase

### **[0.4.0] - 2024-12** — Foundation Concepts
- Ontological domain concept
- Vowel gradation principles
- Systematic structure ideas

---

## [0.3.x and earlier] - 2024 — Experimental Phase

### **Various experiments**
- Different phonological systems tested
- Multiple grammatical approaches
- Vocabulary organization strategies
- Learning from natural and constructed languages

---

## Version Numbering Scheme

**Format:** MAJOR.MINOR.PATCH

- **MAJOR (0):** Pre-1.0 development phase
- **MINOR (6):** Significant feature additions or structural changes
- **PATCH (0):** Bug fixes and minor improvements

**1.0.0 will represent:** Complete language specification with comprehensive corpus

---

## Tags and References

- `v0.6.0` - Foundation Complete
- `v0.5.3` - VCV Development
- `v0.5.0` - Early Grammar
- `v0.4.0` - Initial Concepts

---

## Contributing to Changelog

When contributing changes, please:
1. Add entries to "Unreleased" section at top
2. Use clear, descriptive language
3. Categorize changes appropriately
4. Include examples where relevant
5. Link to related documentation

**Categories:**
- **BREAKING CHANGES** — Incompatible changes
- **NEW FEATURES** — New functionality
- **IMPROVEMENTS** — Enhanced existing features
- **BUG FIXES** — Corrections
- **DOCUMENTATION** — Doc updates
- **DEPRECATED** — Soon-to-be removed features
- **REMOVED** — Deleted features

---

**Changelog Format:** Based on [Keep a Changelog](https://keepachangelog.com/)  
**Versioning:** [Semantic Versioning](https://semver.org/)

---

**Last Updated:** March 19, 2026  
**Current Version:** 0.6.0  
**Next Version:** 0.6.1 (Planned April 2026)

---
