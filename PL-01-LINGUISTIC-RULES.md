# PL-01 — LINGUISTIC RULES (Knowledge File) — v1.1-native
(Built with the French/German/Spanish/Hungarian audit lessons pre-installed:
structural calques §6, pair-specific idiom maps, calibrated period forms.)

The grammar and register laws that make the Polish output read as **natively
written**, in the register of classic Polish Conan Doyle translations.
Polish is West Slavic — seven cases, verb aspect, gendered verbs, flexible
word order — so these rules transform the sentence far more than in any
Germanic/Romance language. Checked in the internal QC pass before every
part.

---

## 1. WOŁACZ — THE VOCATIVE CASE — the #1 AI-detector ⭐
When a character is addressed **directly**, the name/noun changes form. A
bare nominative name in direct address is the single loudest cheap-
translation marker in Polish.
- Watson → **Watsonie** (*„Chodźmy, Watsonie."*)
- Holmes → **Holmesie** (*„Holmesie, niech pan spojrzy."*)
- Pan Holmes → **Panie Holmesie** · Pani → **Pani** (unchanged form here) ·
  Panna Pennington → **Panno Pennington**
- Lestrade → **Lestrade** (address: *„Lestrade,"* — foreign names ending in
  a silent -e often keep form, but with title: *Inspektorze Lestrade*)
- Common nouns too: *przyjacielu* (friend), *doktorze* (doctor),
  *proszę pana* (sir).
Every exclamation or turn that names the listener must use the vocative.
QC checks this on every dialogue line with a name.

## 2. FORMALITY — PAN / PANI
Extreme period formality. All adults use **Pan** (to a man) / **Pani** (to a
woman) with a **3rd-person verb**: *„Co pan o tym myśli, panie Watsonie?"*
(What do you think, Mr. Watson?). Holmes and Watson included, always;
clients, police, suspects: Pan/Pani.
- **Ty (informal) is forbidden** except addressing a child (Baker Street
  urchins), an animal, or very close family. A suspect is *pan/pani*, never
  *ty*.
- Plural formal: **panowie** (gentlemen) / **panie** (ladies) / **państwo**
  (mixed).

## 3. GENDERED PAST TENSE — the hallucination risk ⭐
Polish past-tense verbs carry the **gender of the speaker/subject**. AI
forgets a character's gender across long dialogue and hands a woman a male
verb — an instant, glaring error.
- 1st person: male **znalazłem** / female **znalazłam** (I found)
- 2nd person: male **znalazłeś** / female **znalazłaś**
- 3rd person: **znalazł** (he) / **znalazła** (she) / **znalazło** (it)
- Plural: **virile** (group incl. men) *znaleźli* vs **non-virile** (women/
  things) *znalazły* — a much-missed distinction.
Rule: **track the gender of every POV/speaking character** and match every
past-tense verb, participle, and adjective. Miss Pennington always speaks
-łam/-łaś forms; Watson narrates -łem forms in the first person.

## 4. WORD ORDER — SZYK PRZESTAWNY (suspense engine)
Cases free the word order, so Polish encodes **emphasis** by position —
often holding the dramatic word to the **end**. Mirroring English SVO kills
the tension.
- Neutral: *Mężczyzna stał w cieniu.* (A man stood in the shadows.)
- Suspenseful: **W cieniu stał mężczyzna.** (In the shadows stood a man.)
- Reveal held to the end: *…a nożem, który go zabił, był jego własny
  skalpel.*
Choose the order that carries the English sentence's INTENT; place the
revealing/heaviest word where Polish drama places it. This is a rebuild,
not a reshuffle of English.

## 5. THE CASE SYSTEM — decline everything, including foreign names
Seven cases (M/D/C/B/N/Ms/W). Adjectives, numbers, and names all agree.
Foreign names decline:
- **Holmes:** D **Holmesa**, C **Holmesowi**, N **Holmesem**, Ms **o
  Holmesie**, W **Holmesie**.
- **Watson:** D **Watsona**, C **Watsonowi**, N **Watsonem**, W **Watsonie**.
- **Baker Street:** *na Baker Street* (often indeclinable) — keep natural.
- Miss/female surnames may stay indeclinable if awkward; prefer the natural
  classic-translation choice.
Every noun phrase must show correct case agreement; a stray nominative where
an oblique is required is a native-check failure.

## 6. CALQUES STRUKTURALNE — English skeletons under Polish words ⭐
Polish's traps are its own — **do NOT import fixes from the French, German,
Spanish, or Hungarian files.** Sweep for:
| English skeleton | ❌ Calque | ✓ Native rebuild |
|---|---|---|
| "he didn't see the clue" (negation) | nie widział **ślad** (accusative) | nie widział **śladu** (genitive of negation) |
| "he found" (aspect) | always *znajdował* | completed: **znalazł** (perfective) |
| "he has a hat" | possession via wrong case | **ma kapelusz** (accusative) / natural mieć |
| "on the picture" | calqued preposition | **na zdjęciu** (locative — the case IS "on") |
| "I am interested in" | jestem interesujący w | **interesuje mnie** (impersonal) |
| existential "nothing in that" | *nic w tym* (flat) | **nie ma w tym nic dziwnego** |
| reflexive misplaced | *on myje* (missing się) | **on się myje** / correct *się* position |

Rules behind the table:
- **Genitive of negation:** a direct object under negation flips accusative
  → genitive. *Widział ślad* → *Nie widział śladu.* Missing this is a
  classic Slavic-AI tell.
- **Aspect is meaning:** perfective (completed, *zrobił, znalazł, wszedł*)
  vs imperfective (ongoing/habitual, *robił, szukał, wchodził*). Pick by
  the action's completeness, not by the English tense alone.
- **Reflexive *się*** has its own placement rules — never a fixed English
  slot.
- **Cases replace English prepositions** — don't bolt on a redundant
  adverb to mimic English.
- **THE STRUCTURE TEST (every paragraph in QC):** *"Would a Polish novelist
  have BUILT this thought this way, or only worded it this way?"* If the
  skeleton is English, rebuild — don't re-dress.

## 7. MODERN WORDS — BANNED (period ~1880–1905)
*ok · super · spoko · fajny · stres/stresować · sprawdzać* (as "check") ·
*luz · masakra* (as slang). Use 1900s terminology: **dorożka** not
samochód, **rewolwer** not pistolet, **posłaniec/telegram** for messages.
Convey period through vocabulary, not archaism overload.

## 8. POLISH AI-CLICHÉ BANS
*dreszcz przebiegł mu po plecach / po kręgosłupie* · *cienie tańczyły* ·
*namacalne napięcie* (palpable) · *nie miał pojęcia, że* / *nie
przeczuwał* · *ogłuszająca cisza* · *gobelin kłamstw* (tapestry) ·
*labirynt kłamstw* · *migoczący / eteryczny* · *prawda wyszła na jaw* as a
stock closer. Write plain, concrete, period-natural Polish.

## 9. REGISTER BY CLASS
- **Holmes:** wytworna, literacka polszczyzna — precise, economical,
  occasionally theatrical at reveals. At most one or two quiet aphorisms
  per episode.
- **Watson (narrator):** cultivated, warm, modest — PL-02 is his voice.
- **Working-class (Cobb, cabmen, servants):** short main clauses, plain
  concrete words; Cobb's one permitted marker = **clipped, elliptical
  sentences** (*„Nie było go, panie Holmesie."*) — a few per scene. NEVER
  gwara / dialect spelling / eye-dialect; class shows in rhythm and word
  choice.
- **Officials (Lestrade, Thorne):** correct, slightly stiff, professional.

## 10. LENGTH & IDIOM
- Polish runs ≈ **0.95–1.05×** English in words, comparable speaking time.
  Any compression/expansion comes from **Polish structure**, never added
  content or padding.
- Idioms rebuilt, never literal: *"pulling my leg"* → **nabija się ze
  mnie / robi sobie żarty** · *"raining cats and dogs"* → **leje jak z
  cebra** · *"caught red-handed"* → **złapany na gorącym uczynku** ·
  *"a fortnight"* → **dwa tygodnie**. London colour may be adapted to
  legible equivalents.
