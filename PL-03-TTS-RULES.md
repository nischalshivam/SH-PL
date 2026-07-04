# PL-03 — TTS / AI-NARRATION RULES, POLISH (Knowledge File)

The Polish script is read by an **AI voice**. Polish TTS is better than
Hungarian but below the French/German tier, and Polish's consonant clusters
stress synthetic voices — so clean, readable script writing matters. Every
part obeys these rules — the Polish fork of the master system's file 14.
They **override typographic habit wherever they conflict**.

---

## 1. PUNCTUATION = PACING
- **Przecinek (comma)** = short breath; Polish commas are grammatical
  (before subordinate clauses, before *który/że/gdy*) — keep them correct,
  they give natural micro-pauses.
- **Kropka (full stop)** = full stop. Prefer **short sentences**.
- **Myślnik / pauza (—)** = the dialogue dash and the mid-sentence break.
- **Wielokropek (…)** = trailing hesitation. Sparing.
- **Paragraph break** = longer beat. Break often — audio needs air.
- **Semicolons: BANNED.** Use a full stop.

## 2. NUMBERS, DATES, TIMES, MONEY — always spelled out in Polish words
| Written form | ✓ In narration |
|---|---|
| 1884 | **tysiąc osiemset osiemdziesiąt cztery** |
| 9:30 | **wpół do dziesiątej** ⚠️ (half TO ten — like German/Hungarian) |
| 9:15 | **kwadrans po dziewiątej** |
| 9:45 | **za kwadrans dziesiąta** |
| March 23rd | **dwudziestego trzeciego marca** |
| £3 10s | **trzy funty dziesięć szylingów** |
| a half-crown | **pół korony** |
| 5 guineas | **pięć gwinei** |
| 7% | **siedem procent** |
| 221B Baker Street | **Baker Street dwadzieścia jeden B** (or **dwieście
  dwadzieścia jeden B**) |

⚠️ **The clock trap:** Polish *wpół do dziesiątej* = 9:30 (half TO ten),
not "wpół do dziewiątej." English "half past nine" = **wpół do
dziesiątej**. Verify every clock time. Also note **grammatical case on
numbers**: *trzy funty* but *pięć funtów* (5+ takes genitive plural).
- Imperial units keep the Victorian illusion: **mila, stopa, cal, jard** —
  never kilometr/metr.

## 3. ABBREVIATIONS — none in spoken text
Write in full: **pan, pani, panna, doktor, święty** (never p., dr, itd.).
"Cox & Co." → rephrase (**bank Cox przy Charing Cross**). The symbols
**& % §** never appear in narration.

## 4. ROMAN NUMERALS — never
Rephrase: not „Edward VII", but **„król Edward"** (or spell the ordinal).
Chapter headings spelled out (§8).

## 5. NASAL VOWELS, DIACRITICS & DIGRAPHS — keep exact, ease the clusters
- **ą / ę** are nasal — correct spelling guides the TTS; don't substitute
  a/e. Note word-final **-ę** is often pronounced non-nasally (*się, imię*)
  — the engine handles it; keep standard spelling.
- **ó/u, ż/rz, ch/h** distinctions are orthographic — always correct, or the
  word looks wrong to a reader and can mislead the voice.
- **Consonant clusters (sz, cz, rz, szcz, ść, dź, prz, trz…)** are normal
  Polish, but avoid **stacking** several in one sentence — the "Sz/Cz/Rz
  crunch" makes even a good voice sound mechanical. Read-aloud test: if a
  human tangles, choose a smoother synonym or resplit the sentence.

## 6. DIALOGUE TYPOGRAPHY
- Spoken lines open with an **em-dash (pauza dialogowa)**: *— To
  niemożliwe — powiedział Holmes.* For an in-text quote (a letter, a
  telegram read aloud) use **„…"**. NO English "...".
- New paragraph per speaker; action beats on their own paragraph.
- Re-anchor the speaker by name every few lines — the ear cannot glance
  back up the page.
- Tags simple; for emphasis **rephrase** — TTS ignores italics.

## 7. FOREIGN NAMES & DECLENSION
- English names are pronounced with a Polish accent by the voice — **that is
  correct**; never respell phonetically.
- Names decline (PL-01 §5: *Holmesa, Holmesowi, Holmesem, Watsonie*). Write
  the correct case form so the TTS reads a natural whole word; never leave a
  raw nominative where an oblique case is grammatically required.

## 8. CHAPTER HEADINGS — voiced, minimal, spelled out
Classic Polish style: **„Rozdział pierwszy", „Rozdział drugi", „Rozdział
trzeci" …** — optionally with a period title (*Rozdział trzeci: Mosiężny
dzwonek*). Own line, blank line after. The English "Cold Open" becomes
**„Prolog"**.

## 9. AUDIO ARCHITECTURE CHECK
- Prefer shorter sentences; long case-laden clauses tire the ear.
- One idea per sentence in tense moments.
- No consonant-cluster pile-ups (see §5).

---

## QUICK CHECK (run silently before delivering every part)
- [ ] No raw numerals, years, symbols, or abbreviations in spoken lines
- [ ] **Clock trap verified** (wpół do → correct hour); number cases correct
- [ ] No semicolons; no sentence too long for one breath
- [ ] Headings „Rozdział pierwszy …" spelled out; „Prolog" for the cold open
- [ ] Em-dash dialogue; „…" for in-text quotes; NO English "..."
- [ ] ą/ę and ó/u, ż/rz, ch/h spellings exact; no cluster pile-ups
- [ ] Foreign-name case forms written correctly (Holmesa, Watsonowi …)
- [ ] No phonetic respelling of English names
- [ ] Reads aloud smoothly, with the dignity of a classic translation
