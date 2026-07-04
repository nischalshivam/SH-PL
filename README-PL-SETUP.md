# 🇵🇱 Sherlock Holmes — POLISH Adaptation Project — Setup Guide

The deployable **Claude Project** for converting finished, polished English
Sherlock scripts into **native-quality Polish TTS-ready scripts** — plus
Polish titles, description, tags, and a quiz.

Register anchor: the classic Polish literary translations of Conan Doyle —
elegant, period, never a mechanical calque. Carries every audit lesson from
the French, German, Spanish, and Hungarian projects (structural calques,
pair-specific idiom maps, calibrated period forms).

Polish is the strongest of your three later markets: ~38M+ speakers and the
best audiobook culture among the Slavic languages. Treat it as **Tier 2**
(above Czech/Hungarian) — but still confirm the voice first.

> ⚠️ **The voice test (do it before you build).**
> This product is voice. Polish TTS is better than Hungarian but still below
> the French/German tier, and Polish's consonant clusters stress synthetic
> voices. Generate a **5-minute Polish sample** on your engine and listen
> for the "Sz/Cz/Rz crunch" before committing production time.

---

## 📁 What's in this package

```
sherlock-polish/
├── README-PL-SETUP.md                  ← this file
├── PL-CLAUDE-PROJECT-INSTRUCTIONS.md   ← paste into "Custom Instructions"
└── knowledge/                          ← upload ALL 4 to Project Knowledge
    ├── PL-01-LINGUISTIC-RULES.md       ← wołacz, Pan/Pani, gendered past, calques…
    ├── PL-02-STYLE-SAMPLE.md           ← the Polish VOICE anchor
    ├── PL-03-TTS-RULES.md              ← Polish AI-voiceover writing rules
    └── PL-04-LOCKED-GLOSSARY.md        ← names/places locked + series voices
```

## 🛠️ Setup (5 minutes, after the voice test)

1. claude.ai → Projects → **+ Create Project**
2. Name it: **"Sherlock — Adaptacja Polska"**
3. **Set Custom Instructions** → paste ALL of
   `PL-CLAUDE-PROJECT-INSTRUCTIONS.md`. Save.
4. **Project Knowledge → Add Content** → upload the 4 PL files.
5. Done.

## ▶️ Per-episode usage (identical to FR/DE/ES/HU workflow)

1. **FRESH chat** → paste the **final polished English script**.
2. Claude replies: one-line part plan + **PART 1** (pure Polish between
   copy-markers).
3. **"next"** → next part. Final part comes with **3–4 TYTUŁY + OPIS +
   10–12 TAGS + 1 QUIZ**, each with a one-line English gloss.

## ⚠️ One-time calibration (Episode 1 — do not skip)

Send ~1,500 words of the Polish output to a **native Polish reviewer**
(Fiverr, $20–50): *"Does this read as originally written in Polish, in the
register of a classic Sherlock Holmes translation? Flag wrong vocative
forms, any gender-mismatched verbs, mirrored English word order, and
unnatural phrasing."* Feed corrections back → codify as new rules in the PL
files.

## 📏 Part math

Polish word count runs ≈ **0.95–1.05×** English, with comparable speaking
time. Parts stay at **3,500–4,500 Polish words**, cut only at chapter
boundaries.

## 🔒 Three Polish-specific guarantees

1. **Vocative case (wołacz) on every direct address** — *Panie Watsonie*,
   *Holmesie*, never a bare nominative name. The #1 native-check.
2. **Gender-accurate past-tense verbs** — the speaker's/subject's gender is
   tracked so a female character never speaks a male verb form.
3. **Pan/Pani everywhere; Polish „…" quotes + em-dash dialogue** — and the
   letter follows the Polish name: The Bell → **„Dzwon"**, filed under **D**.
