# Luzizmu Rules for Tetum Hunspell Dictionary

## 1. Definition
- **Luzizmu**: Portuguese loanwords in Tetum.
- Any word borrowed from Portuguese that is **not natively Tetum** can be considered Luzizmu.
- Native Tetum words like `feto` (woman) are **never Luzizmu**.

## 2. Morphology
- **Verbs:** No conjugation is applied.
  - Example: `emprestar` → `ha’u empresta`, `ó empresta`, `nia empresta`
- **Gender and number:** No inflection.
- **Plural endings:** Portuguese plural forms are forbidden.
- **Agent nouns (-dor, -or):** Maintain accent on last vowel.
  - Examples: `jogador` → `jogadór`, `pintor` → `pintór`

## 3. Spelling Rules
- **Alphabet:** aábdeéfghiíjklmnñoóprstuúvxyz´
- **One sound, one letter rule:**

### Consonants
- `c` → `k` or `s` depending on sound
- `q` → `k`
- `ç` → `s`
- `nh` → `ñ`
- `lh` → `ll`
- `x` → `z` (if /z/), `x` (if /ʃ/), `ks` (if /ks/)
- `g` → `j` if pronounced /ʒ/, stays `g` if /g/
- `gue` → `ge`, `gui` → `gia`
- `rr` → stays `rr`
- `ss` → `s`

### Vowels
- `ão` → `aun`
- `ã` → `án`
- `-em` (nasal) → `-ein`
- `o` pronounced /u/ → `u`
- Accented vowels: only `á, é, í, ó, ú`
- Accent rules:
  - Drop penultimate accent if word already has one (except hiatus like `saúde`)
  - Words with antepenultimate stress keep the accent (e.g., `música` → `múzika`)

## 4. Grammar & Particles
- Particles never attach to verbs.
- Words can appear with definite/indefinite articles (`ne´e`, `ida`) but **Luzizmu spelling is unchanged**.

## 5. Hunspell Flag
- **Flag:** `/L`
- All Luzizmu words in the `.dic` file **must be flagged** as `/L`.

