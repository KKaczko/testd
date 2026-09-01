# Mela i Piko — Project Context

> Status: DRAFT
> Project phase: Pre-production
> Canonical repository: this repository

---

# 1. Project goal

**Mela i Piko** is a Polish educational animated series for very young children.

The objective is to create short, calm, visually consistent episodes that help
children discover basic concepts and simple truths about the world.

The project should eventually support a highly automated production pipeline,
but automation must never replace educational or creative quality control.

The long-term production goal is approximately:

topic
→ educational brief
→ script
→ storyboard
→ visual prompts
→ image generation
→ animation
→ narration
→ sound
→ render
→ automated QC
→ human review
→ publication

The immediate goal is NOT mass production.

The immediate goal is to design a repeatable high-quality format and produce
a small number of excellent pilot episodes.

---

# 2. Target audience

## Core audience

**20–36 months**

## Secondary audience

Approximately:

**18–42 months**

Content should primarily be designed for a child around 2–3 years old.

The project should not attempt to simultaneously serve children aged 2 and 6.

If a concept is too complex for the core audience, simplify it without making
it scientifically false or postpone the topic.

---

# 3. Positioning

The core positioning is:

> **Pierwsze odkrycia świata dla malucha.**

English working description:

> First discoveries of the world for toddlers.

This is not primarily:

- a nursery-rhyme channel,
- a traditional cartoon,
- a preschool lecture,
- a compilation of unrelated vocabulary,
- high-stimulation entertainment.

Each episode should focus on one small discovery.

Examples:

- Skąd bierze się cień?
- Dlaczego pada deszcz?
- Co pływa?
- Co robi wiatr?
- Jak rośnie kwiatek?
- Co robi pszczoła?
- Co dzieje się z lodem?

---

# 4. Product promise

For the child:

- see something,
- learn its name,
- repeat it,
- observe a simple property or change,
- answer a simple question,
- discover one basic relationship.

Default learning sequence:

**zobacz → nazwij → powtórz → obserwuj → odpowiedz → odkryj → powtórz**

For the parent:

- calm pacing,
- short duration,
- limited stimulation,
- real educational value,
- scientifically correct information,
- human-reviewed content,
- recognizable original characters.

AI is a production technology, not the product proposition.

Do not market the project as “AI cartoons”.

---

# 5. Episode format

Target duration:

**2:00–3:30**

Preferred duration:

**2:30–3:00**

Typical number of scenes:

**7–10**

Preferred:

**8–9**

Typical scene duration:

approximately **8–25 seconds**

Do not add cuts only to increase visual stimulation.

---

# 6. Educational constraints

Each episode should contain:

- 1 main concept,
- up to 2 supporting concepts,
- maximum 3 meaningful new concepts in total,
- one simple scientifically correct fact,
- approximately 2–3 questions,
- natural repetition of important vocabulary.

Typical question pause:

**2–3 seconds**

Default:

**2.5 seconds**

Questions should have a clear answer.

Examples:

- Gdzie jest chmura?
- Co to?
- Który jest duży?
- Co pływa?
- Co słyszysz?

Avoid abstract and multi-part questions.

---

# 7. Language

Language should be simple and natural.

Typical sentence length:

**2–7 words**

Examples:

> To jest chmura.

> Chmura jest na niebie.

> Zobacz kroplę.

> Kropla spada.

Avoid:

- long definitions,
- unnecessary synonyms,
- abstract terminology,
- complex subordinate clauses,
- explanations intended for school-age children.

Simplification must not introduce scientific falsehoods.

---

# 8. Tone

The series should be:

- calm,
- warm,
- curious,
- friendly,
- safe,
- lightly playful,
- visually clear.

It should not be:

- frantic,
- noisy,
- aggressive,
- chaotic,
- overstimulating,
- based on constant surprise,
- based on exaggerated reactions.

Silence and observation are allowed.

---

# 9. Main characters

## Mela

Mela is a small friendly fox.

She represents the child's curiosity.

She:

- notices,
- asks,
- observes,
- tries,
- discovers.

She is not a teacher.

Typical phrases:

- Ooo!
- Co to?
- Popatrz!
- Tutaj?
- Jeszcze raz!
- Chmura!

Mela should usually speak in very short phrases.

Her final design is not yet locked.

Canonical character specification belongs in:

`characters/mela/character-bible.md`

---

## Piko

Piko is a small friendly robot.

He is:

- calm,
- helpful,
- precise,
- a demonstrator rather than a lecturer.

He can perform simple experiments and show cause-and-effect relationships.

Typical phrases:

- Sprawdźmy.
- To jest cień.
- Piłka pływa.
- Kamień tonie.

Piko should never deliver long monologues.

His final design has not yet been created.

Canonical character specification will belong in:

`characters/piko/character-bible.md`

---

# 10. Narrator

The narrator is the main source of verbal explanation.

Voice characteristics:

- warm,
- calm,
- clear,
- natural,
- not theatrical.

Approximate share of spoken content:

**60–70%**

Mela:

approximately **20–30%**

Piko:

approximately **5–15%**

These values are guidelines, not strict quotas.

---

# 11. Visual direction

Current direction:

**soft stylized 2.5D / 3D**

Visual characteristics:

- rounded forms,
- matte materials,
- soft lighting,
- simplified geometry,
- limited texture detail,
- readable silhouettes,
- non-photorealistic appearance,
- few important objects per frame.

General visual metaphor:

> a dimensional illustrated children's book

rather than:

> highly detailed cinematic animation.

---

# 12. Scene composition

Each scene should have:

**one primary point of attention**

If the episode teaches “apple”, the apple should be:

- large,
- easy to recognize,
- clearly separated from the background,
- visually important.

Prefer approximately:

**1–5 important elements per frame**

Avoid decorative clutter.

---

# 13. Camera

Default:

**static camera**

Allowed:

- very slow push-in,
- gentle pan,
- subtle tracking,
- mild parallax.

Avoid:

- fast zooms,
- whip pans,
- spinning camera,
- handheld motion,
- dramatic lens distortion,
- rapid cinematic movement.

Camera movement should support attention rather than create stimulation.

---

# 14. Animation

Prefer:

**one primary action at a time**

Good example:

1. Mela looks at a cloud.
2. Mela points.
3. The cloud slowly moves.

Bad example:

- Mela jumps,
- Piko spins,
- camera zooms,
- clouds race,
- flowers dance,
- particles flash.

Idle animation should remain subtle.

---

# 15. Audio

Narration always has priority.

Music should be:

- quiet,
- instrumental,
- simple,
- reusable,
- emotionally gentle.

Prefer a small recurring music library instead of generating a new soundtrack
for every episode.

Sound effects should correspond to visible events.

Examples:

- rain,
- water drop,
- bee,
- duck,
- wind,
- subtle Piko beep.

Avoid sudden loud sounds.

---

# 16. Character consistency strategy

Text prompts alone are not considered sufficient for character consistency.

The final source of truth for each character should eventually include:

- canonical neutral render,
- turnaround sheet,
- expression sheet,
- pose sheet,
- scale reference,
- approved color palette.

Generation should use canonical visual references whenever possible.

General rule:

> reuse approved assets before generating new ones.

---

# 17. Asset philosophy

The project should gradually build a reusable asset library.

Example:

assets/
  characters/
  locations/
  objects/
  audio/
    music/
    sfx/

If an approved object already exists, prefer reuse or controlled transformation
over generating a completely new version.

This should improve:

- consistency,
- cost,
- speed,
- reproducibility.

---

# 18. Human-in-the-loop

Human approval is mandatory before publication.

During early production there should be at least three review gates:

script
→ HUMAN REVIEW

storyboard
→ HUMAN REVIEW

final video
→ HUMAN REVIEW

After the production system becomes reliable, some intermediate reviews may be
reduced, but final human approval remains mandatory.

---

# 19. AI usage

AI may assist with:

- topic ideation,
- scripts,
- storyboard drafts,
- prompt generation,
- images,
- animation,
- TTS,
- sound effects,
- metadata,
- automated quality checks.

AI should not independently decide:

- whether a scientific explanation is acceptable,
- whether a strange visual generation is suitable for toddlers,
- whether a character redesign becomes canonical,
- whether an episode should be published.

---

# 20. Production architecture — future direction

Long-term target:

topic
↓
Educational Planner
↓
Script Generator
↓
Schema Validator
↓
Storyboard
↓
Asset Resolver
↓
Image generation / reuse
↓
Image-to-video / deterministic animation
↓
TTS
↓
SFX / music
↓
Remotion
↓
FFmpeg
↓
Automated QC
↓
Human preview
↓
YouTube private upload
↓
Human approval
↓
Publish

Important:

Do NOT implement this full pipeline yet.

The format and visual identity must first be proven manually.

---

# 21. Technical philosophy

Automation orchestration may eventually use:

- n8n,
- a small production API,
- structured LLM outputs,
- JSON Schema,
- image generation providers,
- video providers,
- TTS providers,
- Remotion,
- FFmpeg,
- YouTube API.

n8n should act as an orchestrator, not as the location for all business logic.

Provider-specific APIs should ideally be hidden behind abstractions.

Example future interfaces:

ImageProvider

VideoProvider

TTSProvider

StorageProvider

This should allow provider replacement without redesigning the entire workflow.

---

# 22. Repository as source of truth

Do not rely on conversational memory for locked project decisions.

The repository should eventually contain:

docs/
  product-bible.md
  educational-guidelines.md
  qc-rules.md

characters/
  mela/
    character-bible.md
    references/
  piko/
    character-bible.md
    references/

world/
  style-bible.md
  world-bible.md
  locations/

episodes/

schemas/

prompts/

assets/

production/

Canonical documents should be version controlled.

---

# 23. Initial pilots

The first three pilot concepts are:

## EP001 — Skąd bierze się cień?

Tests:

- Mela,
- lighting,
- simple cause/effect,
- child interaction.

## EP002 — Dlaczego pada deszcz?

Tests:

- weather,
- cloud,
- water drops,
- environmental animation.

## EP003 — Co pływa, a co tonie?

Tests:

- Piko,
- simple experiment,
- prediction,
- object animation.

Do not produce dozens of episodes before these pilots validate the format.

---

# 24. Pilot success criteria

The pilots should answer:

1. Is Mela recognizable and appealing?
2. Is Piko compatible with the visual world?
3. Does the visual style look professional?
4. Can character identity remain consistent across scenes?
5. Is the pacing appropriate for the target age?
6. Does the educational structure work?
7. Is AI generation quality sufficient?
8. Can another episode be produced that clearly looks like the same series?

The most important technical test is not:

> Can we produce one good episode?

It is:

> Can we produce the next episode with the same characters and visual identity?

---

# 25. Current design state

Currently:

- Product concept: CANDIDATE
- Mela concept: DRAFT
- Mela visual design: NOT LOCKED
- Piko concept: DRAFT
- Piko visual design: NOT STARTED
- World design: DRAFT
- Episode structure: CANDIDATE
- Production pipeline: CONCEPT ONLY

Do not accidentally convert draft choices into locked specifications.

---

# 26. Current next steps

Work in this order:

1. create / review Product Bible,
2. create Mela Character Bible,
3. generate Mela visual candidates,
4. select one candidate direction,
5. refine Mela,
6. create canonical Mela reference pack,
7. consistency-test Mela,
8. lock Mela v1,
9. design Piko,
10. design world,
11. create EP001 storyboard,
12. produce pilot,
13. evaluate results,
14. only then design production automation.

---

# 27. Core project principle

The development order is:

**quality → consistency → repeatability → automation → scale**

Never reverse this order.