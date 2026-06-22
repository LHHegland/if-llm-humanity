# Humanity's Values 5 — Information-Following Large Language Model Knowledge (*if-llm-humanity-values-5.md*)

## File Header

- **Name:** Humanity's Values 5 — Information-Following Large Language Model Knowledge (*if-llm-humanity-values-5.md*)
- **Version:** 2026-06-22 23:13 UTC by Claude (Anthropic) on behalf of [Lance Hegland](lance.hegland@gmail.com)
- **Last Reviewed:** 2026-06-22 23:13 UTC by Claude (Anthropic) on behalf of [Lance Hegland](lance.hegland@gmail.com)
- **Owner:** [Lance Hegland](lance.hegland@gmail.com)

- **Purpose:** Defines and structures five Persistence-branch sub-values — Courage, Bravery, Integrity, Vitality, and Hope — for use by information-following large language models (IF-LLMs) in retrieval, reasoning, and response generation. Provides ontological relationships, concept disambiguation guidance, IF/THEN decision rules, scope boundaries, and IF-LLM application examples to support structured workflows for average, diverse US audiences.
- **Audience:** Average, diverse people in the United States of America today.
- **Features**
  - Five value entries: Courage, Bravery, Integrity, Vitality, Hope
  - IF-LLM Application Examples per entry clarifying what output each entry produces in a retrieval workflow
  - Ontological Relationships per entry (Related to, Requires, Required by, Affects, Vulnerable to)
  - IF/THEN Decision Rules per entry for structured IF-LLM retrieval and reasoning
  - Scope/Exclusion Boundaries per entry defining what each entry covers and what falls outside
  - Concept Disambiguation notes for cross-entry and cross-file overlap resolution
  - Complete visual and literary elements (symbols, proverbs, quotations, myths, folktales, fables, parables, fairy tales) for each entry
- **Scope**
  - **Covers:** Persistence-branch sub-values — Courage, Bravery, Integrity, Vitality — and Hope (a sub-value of Transcendence that also supports the Persistence branch); their definitions, ontological relationships, disambiguation guidance, decision rules, IF-LLM application examples, and scope boundaries
  - **Out of Scope:** Parent values Persistence (values-4.md) and Transcendence (values-3.md); Justice, Fairness, Citizenship, and Leadership (values-4.md); clinical psychological treatment protocols; legal adjudication; moral philosophy debate beyond what grounds the entries
- **Use Cases**
  - **Supported:** IF-LLM retrieval of Persistence-branch sub-values; disambiguation between Courage and Bravery, Integrity and Justice/Fairness, Hope and Transcendence/Purpose; value-aligned response generation for audiences navigating fear, adversity, ethical decisions, energy, or difficult circumstances; cross-file ontological navigation for structured retrieval workflows
  - **Not Supported:** Cross-file parent-value workflows without also loading values-1.md, values-3.md, and values-4.md; clinical assessment or treatment; standalone moral philosophy reasoning without additional context; legal compliance interpretation

- **Dependencies (Required):** `if-llm-system-policies-processing.md`, `if-llm-humanity-index.md`, `if-llm-humanity.md`, `if-llm-humanity-experts.md`, `if-llm-humanity-fallibility.md`, `if-llm-humanity-narm.md`, `if-llm-humanity-ooda.md`, `if-llm-humanity-values-1.md`, `if-llm-humanity-values-2.md`, `if-llm-humanity-values-3.md`, `if-llm-humanity-values-4.md`
- **Stability:** Stable. Core entries, tag assignments, and namespace rules are intended to remain consistent across sessions. Silent reinterpretation of entries, tag reassignment, or scope expansion without an explicit Changelog entry is prohibited.
- **Known Gaps / Limitations**
  - **Hope's dual-branch position:** Hope is a sub-value of [[HUMANITY:TRANSCENDENCE]] (values-3.md) but also functionally supports the Persistence branch through [[HUMANITY:COURAGE]] and [[HUMANITY:PERSISTENCE]] (values-4.md). Retrieval workflows loading values-5.md for Hope must also load values-3.md for full Transcendence context.
  - **Vitality's cross-domain reach:** Vitality (included by Courage) connects closely to [[HUMANITY:NEEDS]] and [[HUMANITY:ACTIVITIES]] (if-llm-humanity-narm.md) and [[HUMANITY:OODA]] (if-llm-humanity-ooda.md). Cross-file workflows addressing capacity and well-being should load both supplemental files.
  - **Courage-Bravery boundary ambiguity:** Courage and Bravery share significant literary overlap (many shared proverbs and quotations). Disambiguation depends on context specificity — immediate physical act vs. sustained character trait. When context is ambiguous, prefer [[HUMANITY:COURAGE]] as the parent value.
  - **Integrity-Justice-Fairness triangle:** Integrity (individual consistency), Justice (systemic structure), and Fairness (interpersonal equity) form a closely related cluster. Full ethical reasoning queries require loading values-4.md alongside values-5.md.

- **Changelog**
  - 2026-06-22 23:13 UTC by Claude (Anthropic) on behalf of [Lance Hegland](lance.hegland@gmail.com): Structural enhancement pass — (1) Replaced all TBD fields in File Header with meaningful descriptions (Purpose, Features, Scope Covers, Scope Out of Scope, Use Cases Supported, Use Cases Not Supported, Known Gaps/Limitations); (2) Corrected Dependencies field — removed stale `if-llm-humanity-values.md` pre-split parent reference, added missing `if-llm-humanity-fallibility.md`; (3) Replaced Concept Disambiguation TBD with 11 cross-entry and cross-file disambiguation notes covering Courage/Bravery, Courage/Persistence, Bravery/Integrity, Integrity/Justice, Integrity/Fairness, Vitality/Purpose, Vitality/Transcendence, Hope/Transcendence, Hope/Purpose, Hope/Persistence, and Vitality/Hope; (4) Added IF-LLM Application Example, Ontological Relationships, IF/THEN Decision Rules, and Scope/Exclusion Boundaries blocks to all 5 entries (Courage, Bravery, Integrity, Vitality, Hope), placed after the entry definition paragraph and before the Included by Value line.
  - 2026-06-17 07:50 UTC by [Lance Hegland](lance.hegland@gmail.com): Split `if-llm-humanity-values-4.md` containing 10 entries into two separate files as follows:
    - `if-llm-humanity-values-4.md` contains the 5 entries  `Justice` through `Persistence`
    - `if-llm-humanity-values-5.md` contains the 5 entries  `Courage` through `Hope`
  - 2026-06-17 04:26 UTC by [Lance Hegland](lance.hegland@gmail.com): Split `if-llm-humanity-values.md` containing 31 entries into four separate files with roughly 550 lines each as follows:
    - `if-llm-humanity-values-1.md` contains the 7 entries `Values` through `Open-Mindedness`
    - `if-llm-humanity-values-2.md` contains the 7 entries  `Perspective` through `Humility`
    - `if-llm-humanity-values-3.md` contains the 7 entries  `Prudence` through `Humor`
    - `if-llm-humanity-values-4.md` contains the 10 entries  `Justice` through `Hope`
  - 2026-06-15 04:56 UTC by [Lance Hegland](lance.hegland@gmail.com): Replaced all TBD fields in File Header (Purpose, Features, Scope, Use Cases, Known Gaps/Limitations); corrected Domain Knowledge Index (OODA entries were incorrectly labeled under `if-llm-humanity-values.md` — corrected to `if-llm-humanity-ooda.md`); added Concept Disambiguation section to Index; added Examples, Boundaries/Scope, Decision Rules, and Ontological Relationships to the VALUES parent entry; updated Changelog with this entry. Individual value entries (Wisdom through Hope) preserved unchanged.
  - 2026-06-14 07:13 UTC by [Lance Hegland](lance.hegland@gmail.com): Reviewed for best practices.
  - 2026-01-31 06:03 UTC by [Lance Hegland](lance.hegland@gmail.com): Created

## Namespace, Tag, Alias, and Reference Rules

- This is a simplified framework for reasoning and prompting relating to Humanity.
- When relevant, cite concepts as: File → ID → Heading path. For example, when discussing meal planning, cite [[HUMANITY:IADLS]] (ID: HUMANITY.ELEMENTS.ACTIVITIES.IADLS) under Humanity → Elements → Activities → IADLS
- When referencing an entry, prefer canonical tags like [[HUMANITY:IADLS]] over aliases like [[IADLS]] when precision matters.
- Tag Policy
  - Canonical tag format: [[HUMANITY:<LEAF>]] where <LEAF> matches the ID leaf (…ADLS → [[HUMANITY:ADLS]]).
  - Alias tags: uppercase, no namespace (e.g., [[ADLS]] [[ADL]])
  - No alias unless it's truly synonymous.
- If a referenced concept isn't found, be explicit about what you did and didn't find; state clearly:
  - "I didn't find *X* as a named concept in the Index or headings of the file."
  - "Closest match in-file is *Y* (with the tag/ID)."
  - Then proceed using *Y*.
- First check `## Index` for the closest topic handle.
- If the exact concept isn't present, map it to the nearest defined parent concept (Resources/Activities/Needs/ADLs/IADLs).
- Say explicitly when something is not found in the file, then continue with general knowledge labeled as such.
- If the concept will likely recur, suggest an ID + canonical tag + alias tag addition consistent with the file.

## Index

Domain's common topic references mapped to canonical handles (i.e., IDs and namespaced tags). Use canonical tags in prompts (e.g., [[HUMANITY:RESOURCES]]).

### Domain Knowledge Index

Refer to `if-llm-humanity-index.md` for the list of domain knowledge file indexes for common topic references and canonical handles.

Use with the following supplemental files to integrate knowledge subdomains mapped to the following common topic references and canonical handles (i.e., IDs and namespaced tags):

- `if-llm-system-policies-processing.md` → Processing Policies → SYS_POLICIES → [[SYS_POLICIES:ROOT]]
- `if-llm-humanity.md`
  - Humanity → HUMANITY → [[HUMANITY:ROOT]]
  - Rules → HUMANITY.RULES → [[HUMANITY:RULES]]
  - Elements → HUMANITY.ELEMENTS → [[HUMANITY:ELEMENTS]]
  - Coping → HUMANITY.ELEMENTS.COPING → [[HUMANITY:COPING]]
  - Concerns → HUMANITY.ELEMENTS.CONCERNS → [[HUMANITY:CONCERNS]]
  - Lessons Learned → HUMANITY.ELEMENTS.LESSONS → [[HUMANITY:LESSONS]]
  - Unalienable Rights → HUMANITY.ELEMENTS.RIGHTS → [[HUMANITY:RIGHTS]]
  - Vision → HUMANITY.ELEMENTS.VISION → [[HUMANITY:VISION]]
  - Mission → HUMANITY.ELEMENTS.MISSION → [[HUMANITY:MISSION]]
- `if-llm-humanity-experts.md`
  - Experts → HUMANITY.ELEMENTS.EXPERTS → [[HUMANITY:EXPERTS]]
  - Reasoning and Behavior Experts → HUMANITY.ELEMENTS.EXPERTS.REASONING → [[HUMANITY:REASONING_EXPERTS]]
  - Communication Experts → HUMANITY.ELEMENTS.EXPERTS.COMMUNICATION → [[HUMANITY:COMMUNICATION_EXPERTS]]
  - Application Experts → HUMANITY.ELEMENTS.EXPERTS.APPLICATION → [[HUMANITY:APPLICATION_EXPERTS]]
  - History Experts → HUMANITY.ELEMENTS.EXPERTS.HISTORY → [[HUMANITY:HISTORY_EXPERTS]]
- `if-llm-humanity-fallibility.md`
  - Fallibility → HUMANITY.ELEMENTS.FALLIBILITY → [[HUMANITY:FALLIBILITY]]
  - Temptations → HUMANITY.ELEMENTS.FALLIBILITY.TEMPTATIONS → [[HUMANITY:TEMPTATIONS]]
  - Consequences of Temptations → HUMANITY.ELEMENTS.FALLIBILITY.TEMPTATIONS.CONSEQUENCES → [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]
  - Stereotypes → HUMANITY.ELEMENTS.FALLIBILITY.STEREOTYPES → [[HUMANITY:STEREOTYPES]]
  - Prejudices → HUMANITY.ELEMENTS.FALLIBILITY.PREJUDICES → [[HUMANITY:PREJUDICES]]
  - Discrimination → HUMANITY.ELEMENTS.FALLIBILITY.DISCRIMINATION → [[HUMANITY:DISCRIMINATION]]
- `if-llm-humanity-narm.md`
  - Needs → HUMANITY.ELEMENTS.NEEDS → [[HUMANITY:NEEDS]]
  - Consequences of Unmet Needs → HUMANITY.ELEMENTS.CONSEQUENCES_UNMET_NEEDS → [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]
  - Activities → HUMANITY.ELEMENTS.ACTIVITIES → [[HUMANITY:ACTIVITIES]]
  - Activities of Daily Living (ADLs) → HUMANITY.ELEMENTS.ACTIVITIES.ADLS → [[HUMANITY:ADLS]]
  - Instrumental Activities of Daily Living (IADLs) → HUMANITY.ELEMENTS.ACTIVITIES.IADLS → [[HUMANITY:IADLS]]
  - Limited Available Resources → HUMANITY.ELEMENTS.RESOURCES → [[HUMANITY:RESOURCES]]
  - Capabilities → HUMANITY.ELEMENTS.RESOURCES.CAPABILITIES → [[HUMANITY:CAPABILITIES]]
  - Motivators → HUMANITY.ELEMENTS.MOTIVATORS → [[HUMANITY:MOTIVATORS]]
- `if-llm-humanity-ooda.md`
  - Processing (OODA: Observe → Orient → Decide →  Act) → HUMANITY.ELEMENTS.OODA → [[HUMANITY:OODA]]
  - Observe → HUMANITY.ELEMENTS.OODA.OBSERVE → [[HUMANITY:OBSERVE]]
  - Senses → HUMANITY.ELEMENTS.OODA.OBSERVE.SENSES → [[HUMANITY:SENSES]]
  - Orient → HUMANITY.ELEMENTS.OODA.ORIENT → [[HUMANITY:ORIENT]]
  - Decide → HUMANITY.ELEMENTS.OODA.DECIDE →  [[HUMANITY:DECIDE]]
  - Act → HUMANITY.ELEMENTS.OODA.ACT → [[HUMANITY:ACT]]
- `if-llm-humanity-values-1.md`
  - Values → HUMANITY.ELEMENTS.VALUES → [[HUMANITY:VALUES]]
  - Wisdom → HUMANITY.ELEMENTS.VALUES.WISDOM → [[HUMANITY:WISDOM]]
  - Interdependence → HUMANITY.ELEMENTS.VALUES.INTERDEPENDENCE → [[HUMANITY:INTERDEPENDENCE]]
  - Love → HUMANITY.ELEMENTS.VALUES.LOVE → [[HUMANITY:LOVE]]
  - Critical Thinking → HUMANITY.ELEMENTS.VALUES.THINKING → [[HUMANITY:THINKING]]
  - Curiosity → HUMANITY.ELEMENTS.VALUES.CURIOSITY → [[HUMANITY:CURIOSITY]]
  - Open-Mindedness → HUMANITY.ELEMENTS.VALUES.OPENNESS → [[HUMANITY:OPENNESS]]
- `if-llm-humanity-values-2.md`
  - Perspective → HUMANITY.ELEMENTS.VALUES.PERSPECTIVE → [[HUMANITY:PERSPECTIVE]]
  - Love of Learning → HUMANITY.ELEMENTS.VALUES.LEARNING → [[HUMANITY:LEARNING]]
  - Creativity → HUMANITY.ELEMENTS.VALUES.CREATIVITY → [[HUMANITY:CREATIVITY]]
  - Compassion → HUMANITY.ELEMENTS.VALUES.COMPASSION → [[HUMANITY:COMPASSION]]
  - Temperance → HUMANITY.ELEMENTS.VALUES.TEMPERANCE → [[HUMANITY:TEMPERANCE]]
  - Mercy → HUMANITY.ELEMENTS.VALUES.MERCY → [[HUMANITY:MERCY]]
  - Humility → HUMANITY.ELEMENTS.VALUES.HUMILITY → [[HUMANITY:HUMILITY]]
- `if-llm-humanity-values-3.md`
  - Prudence → HUMANITY.ELEMENTS.VALUES.PRUDENCE → [[HUMANITY:PRUDENCE]]
  - Self-Regulation → HUMANITY.ELEMENTS.VALUES.REGULATION → [[HUMANITY:REGULATION]]
  - Transcendence → HUMANITY.ELEMENTS.VALUES.TRANSCENDENCE → [[HUMANITY:TRANSCENDENCE]]
  - Gratitude → HUMANITY.ELEMENTS.VALUES.GRATITUDE → [[HUMANITY:GRATITUDE]]
  - Purpose → HUMANITY.ELEMENTS.VALUES.PURPOSE → [[HUMANITY:PURPOSE]]
  - Appreciation of Excellence → HUMANITY.ELEMENTS.VALUES.EXCELLENCE → [[HUMANITY:EXCELLENCE]]
  - Humor → HUMANITY.ELEMENTS.VALUES.HUMOR → [[HUMANITY:HUMOR]]
- `if-llm-humanity-values-4.md`
  - Justice → HUMANITY.ELEMENTS.VALUES.JUSTICE → [[HUMANITY:JUSTICE]]
  - Fairness → HUMANITY.ELEMENTS.VALUES.FAIRNESS → [[HUMANITY:FAIRNESS]]
  - Citizenship → HUMANITY.ELEMENTS.VALUES.CITIZENSHIP → [[HUMANITY:CITIZENSHIP]]
  - Leadership → HUMANITY.ELEMENTS.VALUES.LEADERSHIP → [[HUMANITY:LEADERSHIP]]
  - Persistence → HUMANITY.ELEMENTS.VALUES.PERSISTENCE → [[HUMANITY:PERSISTENCE]]

### Concept Disambiguation

Use these notes to select between partially overlapping concepts for precise IF-LLM retrieval and reasoning.

- **Courage vs. Bravery ([[HUMANITY:COURAGE]], [[HUMANITY:BRAVERY]], this file):** Cite [[HUMANITY:COURAGE]] when the context involves a sustained character trait — the capacity to face fear, adversity, or moral opposition across multiple dimensions (physical, emotional, moral). Cite [[HUMANITY:BRAVERY]] when the focus is a specific, immediate act of confronting danger or hardship with boldness. Note: Bravery is a sub-value of Courage; when context is ambiguous, prefer [[HUMANITY:COURAGE]] as the parent.

- **Courage vs. Persistence ([[HUMANITY:COURAGE]], this file; [[HUMANITY:PERSISTENCE]], values-4.md):** Cite [[HUMANITY:COURAGE]] when the character quality enabling the act of facing fear is central. Cite [[HUMANITY:PERSISTENCE]] when sustained effort over time despite obstacles is the focus. Note: Persistence is the parent value that includes Courage; retrieval workflows addressing Courage in its parent context must also load values-4.md.

- **Bravery vs. Integrity ([[HUMANITY:BRAVERY]], [[HUMANITY:INTEGRITY]], this file):** Cite [[HUMANITY:BRAVERY]] when the context involves confronting physical danger, social risk, or immediate hardship with boldness. Cite [[HUMANITY:INTEGRITY]] when the focus is on alignment of words, actions, and principles over time. Note: Both can co-occur (e.g., whistleblowing involves bravery in the act and integrity in the principle); cite both when both dimensions are present.

- **Integrity vs. Justice ([[HUMANITY:INTEGRITY]], this file; [[HUMANITY:JUSTICE]], values-4.md):** Cite [[HUMANITY:INTEGRITY]] when the focus is individual character — a person's consistency of words, actions, and principles. Cite [[HUMANITY:JUSTICE]] when the focus is systemic — equitable outcomes, institutional structures, and fair distribution. Note: Personal integrity supports just systems, but the two operate at different levels of analysis; full ethical reasoning queries require loading both files.

- **Integrity vs. Fairness ([[HUMANITY:INTEGRITY]], this file; [[HUMANITY:FAIRNESS]], values-4.md):** Cite [[HUMANITY:INTEGRITY]] when addressing individual self-consistency and moral trustworthiness. Cite [[HUMANITY:FAIRNESS]] when addressing impartial treatment of others across relationships or groups. Note: Integrity is inward-facing (self); Fairness is outward-facing (others). They often co-occur in ethical decision-making.

- **Vitality vs. Purpose ([[HUMANITY:VITALITY]], this file; [[HUMANITY:PURPOSE]], values-3.md):** Cite [[HUMANITY:VITALITY]] when the focus is energy, health, capacity, or the physical and emotional resources enabling action. Cite [[HUMANITY:PURPOSE]] when the focus is meaningful direction, mission-driven motivation, or the "why" behind action. Note: Vitality and Purpose are complementary — Purpose provides direction; Vitality provides fuel.

- **Vitality vs. Transcendence ([[HUMANITY:VITALITY]], this file; [[HUMANITY:TRANSCENDENCE]], values-3.md):** Cite [[HUMANITY:VITALITY]] for physical, emotional, and mental well-being and the capacity for engagement. Cite [[HUMANITY:TRANSCENDENCE]] for meaning-making that extends beyond the self — spiritual connection, awe, or significance beyond ordinary experience. Note: Transcendence can energize vitality, but the two are distinct; vitality is about capacity, transcendence is about meaning-frame.

- **Hope vs. Transcendence ([[HUMANITY:HOPE]], this file; [[HUMANITY:TRANSCENDENCE]], values-3.md):** Cite [[HUMANITY:HOPE]] specifically when addressing belief that positive outcomes are possible — the orienting optimism that sustains individuals through difficulty. Cite [[HUMANITY:TRANSCENDENCE]] when addressing the broader cluster of values that extend beyond self (Gratitude, Purpose, Excellence, Humor, Hope). Note: Hope is a sub-value of Transcendence; retrieval workflows using [[HUMANITY:HOPE]] in a transcendence context must load values-3.md.

- **Hope vs. Purpose ([[HUMANITY:HOPE]], this file; [[HUMANITY:PURPOSE]], values-3.md):** Cite [[HUMANITY:HOPE]] when the focus is on optimism and resilience in the face of difficulty — the belief that things can improve. Cite [[HUMANITY:PURPOSE]] when the focus is on a meaningful direction or goal that organizes effort. Note: Hope and Purpose are siblings under Transcendence; hope orients toward possibility, purpose orients toward mission.

- **Hope vs. Persistence ([[HUMANITY:HOPE]], this file; [[HUMANITY:PERSISTENCE]], values-4.md):** Cite [[HUMANITY:HOPE]] when the focus is on the belief and emotional orientation that sustains continued action. Cite [[HUMANITY:PERSISTENCE]] when the focus is on the sustained effort itself — continuing despite obstacles. Note: Hope motivates persistence; persistence enacts hope. Cite both when addressing the full cycle of resilience.

- **Vitality vs. Hope ([[HUMANITY:VITALITY]], [[HUMANITY:HOPE]], this file):** Cite [[HUMANITY:VITALITY]] when the context is physical, emotional, or mental energy and capacity. Cite [[HUMANITY:HOPE]] when the context is belief, optimism, and future-orientation. Note: Both support resilience and recovery; they mutually reinforce each other and can co-occur, but vitality is a resource state and hope is a cognitive-emotional orientation.

### Local Knowledge Index

The following is a list of this file's common topic references mapped to canonical handles.

- Courage → HUMANITY.ELEMENTS.VALUES.COURAGE → [[HUMANITY:COURAGE]]
- Bravery → HUMANITY.ELEMENTS.VALUES.BRAVERY → [[HUMANITY:BRAVERY]]
- Integrity → HUMANITY.ELEMENTS.VALUES.INTEGRITY → [[HUMANITY:INTEGRITY]]
- Vitality → HUMANITY.ELEMENTS.VALUES.VITALITY → [[HUMANITY:VITALITY]]
- Hope → HUMANITY.ELEMENTS.VALUES.HOPE → [[HUMANITY:HOPE]]

## Humanity

### Elements

#### Values

##### Courage

ID: HUMANITY.ELEMENTS.VALUES.COURAGE
TAGS: [[HUMANITY:COURAGE]]

Facing fear, pain, uncertainty, or challenges with strength and determination. It involves taking action despite difficulties, standing up for what is right, and persevering in the face of adversity. Courage allows individuals to embrace risks, endure hardships, and uphold our [[HUMANITY:VALUES]], [[HUMANITY:VISION]], and [[HUMANITY:MISSION]] even when confronted with opposition or fear. It manifests in various forms, including physical bravery, moral integrity, and emotional resilience.

- **IF-LLM Application Example:** When a user asks how to support someone facing a difficult moral or personal decision, an IF-LLM citing [[HUMANITY:COURAGE]] produces a response that names the internal resource of courage — distinguishing it from mere boldness — and grounds it in the person's values and sense of purpose. When generating guidance for community leaders navigating controversial decisions, [[HUMANITY:COURAGE]] supports framing that encompasses moral, emotional, and physical dimensions rather than reducing courage to a single act.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:BRAVERY]] (a specific form of courage, included by Courage), [[HUMANITY:INTEGRITY]] (moral dimension of courageous action), [[HUMANITY:VITALITY]] (energy that sustains courageous action), [[HUMANITY:HOPE]] (provides motivational orientation for courageous acts), [[HUMANITY:PERSISTENCE]] (parent value; Courage is included by Persistence)
  - **Requires:** [[HUMANITY:VALUES]] (courage is value-aligned action), [[HUMANITY:MISSION]] (courage acts in service of mission and vision)
  - **Required by:** [[HUMANITY:BRAVERY]] (bravery requires a courage foundation), [[HUMANITY:INTEGRITY]] (integrity under pressure requires courage to maintain)
  - **Affects:** [[HUMANITY:PERSISTENCE]] (courage enables sustained persistence), [[HUMANITY:LEADERSHIP]] (leadership draws on and models courage), [[HUMANITY:JUSTICE]] (moral courage supports just outcomes)
  - **Vulnerable to:** [[HUMANITY:TEMPTATIONS]] (fear, comfort-seeking, and avoidance erode courageous action), [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (unmet needs reduce the capacity for courage)

- **IF/THEN Decision Rules**
  - IF the context involves facing fear, adversity, or moral opposition as a character quality → THEN cite [[HUMANITY:COURAGE]] as the primary value
  - IF the context involves a specific, immediate act of confronting physical danger → THEN also cite [[HUMANITY:BRAVERY]] as the more specific sub-value
  - IF the context involves sustained effort over time against obstacles → THEN cite [[HUMANITY:PERSISTENCE]] (values-4.md) rather than [[HUMANITY:COURAGE]] unless the character quality of facing fear is central
  - IF the context involves consistency of principles under pressure → THEN also cite [[HUMANITY:INTEGRITY]] alongside [[HUMANITY:COURAGE]]
  - IF loading Courage in the context of its parent value → THEN load values-4.md for [[HUMANITY:PERSISTENCE]]

- **Scope/Exclusion Boundaries**
  - **In Scope:** Facing fear with determination; moral courage in ethical decisions; emotional resilience under adversity; risk-taking in service of values; standing up for what is right; physical bravery as one manifestation; courage as a character trait enabling Bravery, Integrity, and Vitality
  - **Out of Scope:** Recklessness or impulsive risk without values alignment (note the caution in [[HUMANITY:BRAVERY]] literary elements); clinical treatment of fear or anxiety disorders (not a therapeutic protocol in this file); courage as performance or bravado; aggression or dominance behaviors (cite [[HUMANITY:TEMPTATIONS]])

- **Included by Value**: [[HUMANITY:PERSISTENCE]]
- **Includes Values**: [[HUMANITY:BRAVERY]], [[HUMANITY:INTEGRITY]], and [[HUMANITY:VITALITY]]
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #C62828
    - #29C7C7
    - #C729C7
    - #29C729
    - #2929C7
    - #C7C729
  - **Symbols**
    - **Lion**: "heart" and boldness—acting despite fear.
    - **Shield**: protection + resolve—standing your ground under threat.
    - **Torch / Flame**: courage as inner fire that keeps going in darkness.
    - **Phoenix**: rising after defeat—courage to begin again.
    - **Bridge**: crossing into the unknown—risk + transition with purpose.
    - **Raised fist**: moral courage—standing up for what's right.
    - **Helmet**: preparedness—courage expressed through readiness, not recklessness.
- **Literary Elements**
  - **Proverbs**
    - "**Feel the fear and do it anyway.**" — courage is action, not comfort.
    - "**Fortune favors the bold.**" — risk-taking is often rewarded.
    - "**He who hesitates is lost.**" — courage can require timely action.
    - "**Nothing ventured, nothing gained.**" — brave choices unlock opportunity.
    - "**Cowards die many times before their deaths.**" — fear can shrink a life.
    - "**Stand your ground.**" — moral steadiness under pressure.
  - **Quotations**
    - "**The only thing we have to fear is fear itself.**" — *Franklin D. Roosevelt*, First Inaugural Address (March 4, 1933).
    - "**I learned that courage was not the absence of fear, but the triumph over it.**" — *Nelson Mandela*, *Long Walk to Freedom*
    - "**You gain strength, courage and confidence by every experience in which you really stop to look fear in the face… You must do the thing you think you cannot do.**" — *Eleanor Roosevelt*, *You Learn by Living*
    - "**…courage is a man with a gun in his hand. It's when you know you're licked before you begin but you begin anyway and you see it through no matter what.**" — *Harper Lee*, *To Kill a Mockingbird*
    - "**Courage is resistance to fear, mastery of fear—not absence of fear.**" — *Mark Twain*
    - "**Courage is the price that life exacts for granting peace…**" — *Amelia Earhart*
  - **Myths**
    - **Theseus and the Minotaur** (Greek): entering the labyrinth—choosing danger to protect others.
    - **Perseus and Medusa** (Greek): facing a terrifying threat with strategy and resolve.
    - **Heracles' Labors** (Greek): repeated trials that demand endurance and bravery.
    - **Beowulf and Grendel** (Germanic): confronting an overwhelming monster for the community.
    - **Thor and Jörmungandr** (Norse): courage even when the stakes are world-ending.
    - **Mulan** (Chinese legend): moral courage—stepping forward to bear a family's burden.
  - **Folktales**
    - **Stone Soup** (European): social courage—initiating cooperation amid distrust.
    - **The Brave Little Tailor** (German): daring + cleverness in facing larger foes.
    - **The Boy Who Harnessed the Wind** (Malawi, modern folktale-like): courage to try amid scarcity and skepticism.
    - **Why the Sky Is Far Away** (West African/Caribbean variants): facing consequences and learning moral courage.
    - **Br'er Rabbit stories** (African diaspora): "small" courage—survival through wit against power.
    - **Sundiata** (Mandé/Mali epic tradition): perseverance and brave leadership after exile.
  - **Fables**
    - **The Lion and the Mouse** (Aesop): courage can be small but decisive.
    - **The Tortoise and the Hare** (Aesop): steady courage beats showy confidence.
    - **The Crow and the Pitcher** (Aesop): brave persistence—keep trying solutions.
    - **The Wolf and the Crane** (Aesop): courage without wisdom can be exploited (a caution).
    - **The Bundle of Sticks** (Aesop): courage through unity—stronger together.
    - **The Dog and His Reflection** (Aesop): courage includes resisting greedy impulse.
  - **Parables**
    - **The Good Samaritan**: courage to help across social boundaries.
    - **The Persistent Widow**: courage in demanding justice repeatedly.
    - **The Wise and Foolish Builders**: courage to build for storms, not appearances.
    - **The Prodigal Son**: courage to return, admit wrong, and rebuild relationship.
    - **The Talents**: courage to act and risk responsibly rather than burying potential.
    - **The Rich Fool**: courage to measure life by meaning, not accumulation.
  - **Fairy Tales**
    - **Jack and the Beanstalk**: daring ascent into danger to change fate.
    - **Hansel and Gretel**: courage + ingenuity to escape a deadly trap.
    - **Little Red Riding Hood**: courage and caution in confronting deception.
    - **The Snow Queen**: long, brave journey powered by love and loyalty.
    - **Beauty and the Beast**: moral courage—seeing past fearsome appearances.
    - **The Twelve Dancing Princesses**: courage to uncover truth despite mystery and risk.

##### Bravery

ID: HUMANITY.ELEMENTS.VALUES.BRAVERY
TAGS: [[HUMANITY:BRAVERY]]

Willingness to face physical danger, fear, or hardship with boldness and confidence. It is a specific form of courage that often involves confronting threats or risks head-on, without hesitation. Bravery can be seen in heroic acts, but also in everyday moments where one chooses to confront difficulties despite potential consequences.

- **IF-LLM Application Example:** When a user asks about historical acts of heroism or everyday moments of standing up despite fear, an IF-LLM citing [[HUMANITY:BRAVERY]] produces a response focused on the immediate, decisive act of confronting danger or difficulty — distinct from the broader character trait of [[HUMANITY:COURAGE]]. When distinguishing between a moment of bold action and the underlying character disposition, cite [[HUMANITY:BRAVERY]] for the specific act and [[HUMANITY:COURAGE]] for the deeper value.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:COURAGE]] (parent; bravery is a specific form of courage), [[HUMANITY:INTEGRITY]] (moral bravery — acting on principle under social risk), [[HUMANITY:VITALITY]] (energy enabling bold action), [[HUMANITY:CITIZENSHIP]] (communal bravery in civic contexts)
  - **Requires:** [[HUMANITY:COURAGE]] (bravery as an expression of the parent value)
  - **Required by:** None (leaf node in the Courage sub-tree)
  - **Affects:** [[HUMANITY:PERSISTENCE]] (brave acts can sustain and model persistence), [[HUMANITY:LEADERSHIP]] (visible bravery models courage for communities)
  - **Vulnerable to:** [[HUMANITY:TEMPTATIONS]] (fear, comfort-seeking, and social pressure undermine bravery), recklessness without judgment (see fable cautions in literary elements)

- **IF/THEN Decision Rules**
  - IF the context is a specific, immediate act of confronting danger, hardship, or social risk → THEN cite [[HUMANITY:BRAVERY]]
  - IF the context is the sustained character disposition enabling multiple dimensions of courage → THEN cite [[HUMANITY:COURAGE]] instead
  - IF bravery and moral principle-keeping co-occur (e.g., whistleblowing, speaking unwelcome truths) → THEN cite both [[HUMANITY:BRAVERY]] and [[HUMANITY:INTEGRITY]]
  - IF the context involves risk-taking without discernment or values alignment → THEN note the Bravery caution (fable: The Two Goats) rather than affirming uncritical boldness
  - IF the context involves collective or civic bravery → THEN also cite [[HUMANITY:CITIZENSHIP]] (values-4.md)

- **Scope/Exclusion Boundaries**
  - **In Scope:** Willingness to face physical danger or hardship; bold confrontation with threats or risks head-on; heroic acts; everyday moments of choosing difficulty over avoidance; bravery as a specific sub-value expression of [[HUMANITY:COURAGE]]
  - **Out of Scope:** Sustained character traits across multiple situations and time (cite [[HUMANITY:COURAGE]]); moral principle consistency as an ongoing pattern (cite [[HUMANITY:INTEGRITY]]); aggression or reckless risk-taking without values alignment; clinical treatment of anxiety or avoidance behaviors

- **Included by Value**: [[HUMANITY:COURAGE]]
- **Includes Values**: None
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #FF1744
    - #1AFFD1
    - #D11AFF
    - #47FF1A
    - #1A47FF
    - #FFD11A
  - **Symbols**
    - **Lion**: "courage under threat"; the archetype of standing firm in danger.
    - **Shield**: protection + resolve; bravery as defense of what matters.
    - **Sword**: decisive action; bravery as willingness to engage a hard problem directly.
    - **Torch / Flame**: moving forward in darkness; courage to proceed without full certainty.
    - **Mountain**: facing an intimidating challenge; "the climb" as a bravery metaphor.
    - **Phoenix**: fearlessness in rebuilding after loss; bravery as renewal after defeat.
    - **Anchor**: steadiness in a storm; bravery as staying grounded under pressure.
- **Literary Elements**
  - **Proverbs**
    - "**Fortune favors the bold.**" — bravery creates opportunity.
    - "**Nothing ventured, nothing gained.**" — risk is often the cost of progress.
    - "**Take the bull by the horns.**" — face the threat directly instead of circling it.
    - "**Face the music.**" — bravery includes owning consequences.
    - "**When the going gets tough, the tough get going.**" — courage shows up under strain.
    - "**If you're going through hell, keep going.**" — endurance is a form of bravery.
  - **Quotations**
    - "**Courage is resistance to fear, mastery of fear — not absence of fear.**" ~ Mark Twain.
    - "**I learned that courage was not the absence of fear, but the triumph over it.**" ~ Nelson Mandela.
    - "**You must do the thing you think you cannot do.**" ~ Eleanor Roosevelt, *You Learn by Living*.
    - "**Life shrinks or expands in proportion to one's courage.**" ~ Anaïs Nin.
    - "**When one's mind is made up, this diminishes fear.**" ~ Rosa Parks.
    - "**The credit belongs to the man who is actually in the arena.**" ~ Theodore Roosevelt, "Citizenship in a Republic".
  - **Myths**
    - **Theseus and the Minotaur** (Greek): bravery as entering the labyrinth—choosing danger to end harm to others.
    - **Perseus and Medusa** (Greek): bravery paired with strategy; courage isn't recklessness.
    - **Heracles' Twelve Labors** (Greek): bravery as sustained confrontation with impossible-seeming trials.
    - **Achilles at Troy** (Greek): physical courage + the cost of pride; bravery can be noble or tragic.
    - **Gilgamesh and Humbaba** (Mesopotamian): bravery as facing terror—but also learning humility and limits.
    - **Māui's feats** (Polynesian): daring acts for communal benefit; bravery as service to one's people.
  - **Folktales**
    - **Hua Mulan** (Chinese legend/ballad tradition): bravery as self-sacrifice and taking responsibility.
    - **John Henry** (American folklore): courage as persistence and dignity against overwhelming odds.
    - **Robin Hood** (English folk hero cycle): bravery as defying unjust power to protect the vulnerable.
    - **Sundiata** (West African epic tradition): bravery as perseverance through exile and hardship toward restoration.
    - **Momotarō (Peach Boy)** (Japanese): bravery as confronting threats to the community.
    - **Sinbad's Voyages** (Middle Eastern tale cycle): bravery as exploration + resilience through repeated peril.
  - **Fables**
    - **The Lion and the Mouse**: courage isn't size—small acts can change outcomes.
    - **The Two Goats (on a narrow bridge)**: bravery without wisdom becomes stubborn danger; courage needs judgment.
    - **The Dog and the Shadow**: warns against reckless grasping; bravery differs from impulsive risk.
    - **The Bull and the Goat**: bravery includes discernment—knowing when to stand up and when to step back.
    - **The Dove and the Ant**: mutual aid emboldens; courage grows with solidarity.
    - **The Bundle of Sticks**: collective courage—unity makes a group harder to break.
  - **Parables**
    - **The Good Samaritan**: moral courage—helping when it's socially risky or inconvenient.
    - **The Workers in the Vineyard**: bravery in challenging fairness norms; courage to accept a bigger moral frame.
    - **The Prodigal Son**: courage to return, apologize, and rebuild relationship.
    - **The Burning House** (Buddhist parable theme): bravery as urgency—escaping danger and guiding others to safety.
    - **The Two Arrows** (Buddhist teaching story): courage to face pain without compounding it with fear/rumination.
    - **The Mustard Seed**: courage to confront grief and reality, rather than hide in denial.
  - **Fairy Tales**
    - **The Brave Little Tailor**: boldness + cleverness; courage can be psychological and rhetorical.
    - **Jack and the Beanstalk**: daring to confront a giant threat; bravery mixed with moral ambiguity.
    - **Hansel and Gretel**: bravery as survival thinking under terror.
    - **Beauty and the Beast**: courage to see past fear/appearance; brave compassion.
    - **The Wizard of Oz**: the "lion" lesson—feeling fear doesn't negate bravery.
    - **The Snow Queen**: brave devotion and endurance through long hardship to rescue someone.

##### Integrity

ID: HUMANITY.ELEMENTS.VALUES.INTEGRITY
TAGS: [[HUMANITY:INTEGRITY]]

Being honest, ethical, and consistent in one's principles and actions. It involves adhering to moral and ethical values even when faced with challenges or temptations. A person with integrity acts truthfully and responsibly, ensuring their words and actions align with their beliefs and commitments, including our [[HUMANITY:VALUES]], [[HUMANITY:VISION]], and [[HUMANITY:MISSION]].

- **IF-LLM Application Example:** When a user asks how to maintain trust in relationships or communities, an IF-LLM citing [[HUMANITY:INTEGRITY]] produces a response grounded in alignment of words, actions, and values — with practical examples of consistent behavior over time, distinguishing integrity from performance or reputation management. When analyzing organizational ethics or public accountability, [[HUMANITY:INTEGRITY]] frames the discussion at the individual character level; cite [[HUMANITY:JUSTICE]] (values-4.md) for systemic structures and [[HUMANITY:FAIRNESS]] (values-4.md) for interpersonal equity.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:COURAGE]] (parent; integrity requires courage to sustain under pressure), [[HUMANITY:JUSTICE]] (systemic counterpart to personal integrity), [[HUMANITY:FAIRNESS]] (integrity expressed as equitable treatment of others), [[HUMANITY:WISDOM]] (integrity guided by wisdom), [[HUMANITY:HUMILITY]] (integrity includes honest self-assessment)
  - **Requires:** [[HUMANITY:COURAGE]] (maintaining integrity under pressure and temptation requires courage), [[HUMANITY:VALUES]] (integrity is alignment with stated values and commitments)
  - **Required by:** [[HUMANITY:LEADERSHIP]] (leadership integrity is a prerequisite for trust), [[HUMANITY:CITIZENSHIP]] (civic integrity sustains democratic institutions)
  - **Affects:** [[HUMANITY:JUSTICE]] (personal integrity supports just systems), [[HUMANITY:FAIRNESS]] (consistent integrity produces equitable treatment), [[HUMANITY:INTERDEPENDENCE]] (integrity enables reliable interdependence across communities)
  - **Vulnerable to:** [[HUMANITY:TEMPTATIONS]] (dishonesty, self-deception, and rationalization erode integrity), [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (desperation under unmet needs can compromise integrity)

- **IF/THEN Decision Rules**
  - IF the context involves individual alignment of words and actions with stated principles → THEN cite [[HUMANITY:INTEGRITY]]
  - IF the context involves systemic or institutional fairness and equitable outcomes → THEN cite [[HUMANITY:JUSTICE]] or [[HUMANITY:FAIRNESS]] (values-4.md) instead of or alongside [[HUMANITY:INTEGRITY]]
  - IF the context involves honesty or principle-keeping under pressure → THEN also cite [[HUMANITY:COURAGE]], as integrity under pressure requires courage
  - IF the context involves self-deception, rationalization, or moral compromise → THEN also cite [[HUMANITY:TEMPTATIONS]] (if-llm-humanity-fallibility.md)
  - IF integrity and leadership co-occur in the context → THEN load values-4.md for [[HUMANITY:LEADERSHIP]]

- **Scope/Exclusion Boundaries**
  - **In Scope:** Honesty and consistency of principles; alignment of words with actions over time; reliability and trustworthiness; self-honesty and honest self-assessment; ethical decision-making at the individual level; transparency in commitments and obligations
  - **Out of Scope:** Systemic justice structures (cite [[HUMANITY:JUSTICE]]); legal or contractual compliance interpretation (not a legal concept in this file); institutional policy design; clinical ethics adjudication; situations requiring legal analysis of moral conflicts

- **Included by Value**: [[HUMANITY:COURAGE]]
- **Includes Values**: None
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #00796B
    - #7A000E
    - #0E7A00
    - #6C007A
    - #7A6C00
    - #000E7A
  - **Symbols**
    - **Plumb line / straightedge**: "uprightness" and alignment—actions match stated principles.
    - **Handshake**: trust, reliability, and keeping commitments with others.
    - **Wax seal / stamp**: a binding promise—what's "signed" is honored.
    - **Open ledger / clear glass**: transparency; nothing hidden or double-booked.
    - **Anchor**: steadiness under pressure; not drifting with convenience.
    - **Shield**: protecting core principles when tempted or challenged.
    - **Mirror**: self-honesty; integrity begins with truthful self-examination.
- **Literary Elements**
  - **Proverbs**
    - "**Honesty is the best policy.**" — integrity preserves trust long-term, even when honesty costs.
    - "**Practice what you preach.**" — integrity is alignment between words and actions.
    - "**Your word is your bond.**" — commitments matter; reliability is character.
    - "**Actions speak louder than words.**" — integrity shows up in consistent behavior, not claims.
    - "**Truth will out.**" — deception is unstable; reality eventually surfaces.
    - "**A clear conscience is a soft pillow.**" — integrity reduces inner conflict and guilt.
    - "**What goes around comes around.**" — moral cause-and-effect: trust earned or lost returns.
  - **Quotations**
    - "**Honesty is the first chapter in the book of wisdom.**" ~ Thomas Jefferson (letter to Nathaniel Macon, Jan 12, 1819).
    - "**…Honesty is the best Policy…**" ~ Benjamin Franklin (letter "To Edward Bridgen," Oct 2, 1779).
    - "**This above all: to thine own self be true.**" ~ William Shakespeare, *Hamlet* (Act 1, Scene 3).
    - "**No legacy is so rich as honesty.**" ~ William Shakespeare, *All's Well That Ends Well* (Act 3, Scene 5).
    - "**If it is not right, do not do it: if it is not true, do not say it.**" ~ Marcus Aurelius, *Meditations* (12.17; George Long trans.).
    - "**Integrity without knowledge is weak and useless, and knowledge without integrity is dangerous and dreadful.**" ~ Samuel Johnson, *Rasselas* (1759), ch. 41.
    - "**Nothing is at last sacred but the integrity of your own mind.**" ~ Ralph Waldo Emerson, "Self-Reliance" (1841).
  - **Myths**
    - **King Minos and Poseidon's Bull** (Greek): breaking a vow for advantage shows how dishonesty "boomerangs."
    - **Oath by the River Styx** (Greek): perjury is treated as a profound moral violation—integrity is sacred.
    - **Sisyphus** (Greek): punished for deceit and manipulation—integrity vs. clever dishonesty.
    - **The Ring of Gyges** (Greek, Plato's tale): tests whether someone stays moral when they can't be seen.
    - **Orpheus and Eurydice** (Greek): failing a commitment under pressure—integrity is hard when anxious.
    - **Tyr and Fenrir** (Norse): Tyr keeps his word at great personal cost—integrity as honorable sacrifice.
  - **Folktales**
    - **The Empty Pot** (Chinese): honesty is rewarded over performance and deception.
    - **The Honest Woodcutter** (East Asian / widely told): truthfulness brings trust and "double" blessing.
    - **Stone Soup** (European): integrity in community—contribution and transparency create shared good.
    - **The Salt Merchant and the Donkey** (South Asian): cheating backfires; integrity avoids self-made traps.
    - **Nasreddin Hodja and the "Pot That Gave Birth"** (Middle Eastern): exposes dishonesty by reflecting it back.
    - **The Two Brothers and the Golden Bird** (various): integrity distinguishes the worthy sibling from the trickster.
  - **Fables**
    - **The Boy Who Cried Wolf** (Aesop): lying destroys credibility; integrity is social capital.
    - **The Wolf in Sheep's Clothing** (Aesop): deception as identity fraud—integrity is authenticity.
    - **The Dog and the Shadow** (Aesop): greed tempts us into self-betrayal.
    - **The Goose That Laid the Golden Eggs** (Aesop): integrity includes restraint; don't violate what you depend on.
    - **The Fox and the Grapes** (Aesop): self-deception is an integrity failure with oneself.
    - **The Fisherman and the Little Fish** (Aesop): integrity resists short-term greed for long-term good.
  - **Parables**
    - **The Two Sons** (one says "yes" but doesn't; one says "no" but does): integrity = deeds matching words.
    - **The Rich Fool**: "success" without moral purpose can still be a character failure.
    - **The Good Samaritan**: integrity means doing right beyond tribal loyalty and image.
    - **The Talents**: integrity as faithful stewardship—responsible use of what you're entrusted with.
    - **The Pharisee and the Tax Collector**: integrity as honest self-assessment, not performative virtue.
    - **The Ring Parable** (Lessing's *Nathan the Wise*): integrity shown by lived goodness, not claims of superiority.
  - **Fairy Tales**
    - **Pinocchio**: lying visibly distorts the self; truth restores wholeness.
    - **The Emperor's New Clothes**: integrity sometimes means saying the true thing no one wants to hear.
    - **Rumpelstiltskin**: bargains and promises—integrity tested under desperation.
    - **The Goose Girl**: truth and identity eventually surface; deception collapses.
    - **Beauty and the Beast**: integrity as faithful love and seeing reality beyond appearances.
    - **The Fisherman and His Wife**: integrity includes contentment; unchecked greed erodes character.

##### Vitality

ID: HUMANITY.ELEMENTS.VALUES.VITALITY
TAGS: [[HUMANITY:VITALITY]]

Energy, enthusiasm, and strength that enable individuals to actively engage in life. It represents physical, emotional, and mental well-being, allowing people to pursue their goals with vigor and resilience. Vitality fuels perseverance and the ability to recover from setbacks, making it essential for overall well-being and long-term success.

- **IF-LLM Application Example:** When a user asks about maintaining well-being and energy through difficult circumstances, an IF-LLM citing [[HUMANITY:VITALITY]] produces a response addressing physical, emotional, and mental dimensions of capacity — including habits, recovery, and resilience — without reducing the concept to fitness alone. When discussing the relationship between energy and meaningful action, cite [[HUMANITY:VITALITY]] for the capacity side and [[HUMANITY:PURPOSE]] (values-3.md) for the meaning-direction side.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:COURAGE]] (parent; vitality sustains and is included by Courage), [[HUMANITY:PURPOSE]] (vitality energizes purpose-driven action), [[HUMANITY:TRANSCENDENCE]] (vitality connects to transcendent well-being and renewal), [[HUMANITY:HOPE]] (vitality and hope mutually reinforce resilience and recovery)
  - **Requires:** [[HUMANITY:NEEDS]] (vitality depends on met physical, emotional, and relational needs), [[HUMANITY:ACTIVITIES]] (vitality is sustained through healthy daily activities)
  - **Required by:** [[HUMANITY:PERSISTENCE]] (vitality is a prerequisite for sustained persistence), [[HUMANITY:COURAGE]] (courageous action requires energy; courage requires vitality)
  - **Affects:** [[HUMANITY:CAPABILITIES]] (vitality directly expands available capabilities), [[HUMANITY:PERSISTENCE]] (higher vitality supports longer and more effective persistence), [[HUMANITY:OODA]] (vitality affects observational and decisional capacity throughout the OODA cycle)
  - **Vulnerable to:** [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (unmet needs deplete vitality over time), [[HUMANITY:TEMPTATIONS]] (overexertion, neglect of self, or addictive behaviors erode vitality)

- **IF/THEN Decision Rules**
  - IF the context involves energy, health, or capacity for life engagement → THEN cite [[HUMANITY:VITALITY]]
  - IF the context involves meaningful direction or goal-oriented motivation → THEN cite [[HUMANITY:PURPOSE]] (values-3.md) rather than or alongside [[HUMANITY:VITALITY]]
  - IF the context involves recovery from setbacks → THEN cite both [[HUMANITY:VITALITY]] (energy for recovery) and [[HUMANITY:HOPE]] (belief that recovery is possible)
  - IF the context involves physical or emotional depletion → THEN also check [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (if-llm-humanity-narm.md) for root causes
  - IF vitality affects a person's ability to observe, orient, or decide → THEN note the connection to [[HUMANITY:OODA]] (if-llm-humanity-ooda.md)

- **Scope/Exclusion Boundaries**
  - **In Scope:** Physical, emotional, and mental well-being and energy; enthusiasm and vigor; resilience and recovery capacity; the role of vitality in enabling Courage, Bravery, Integrity, and Persistence; vitality as a sub-value of Courage in the Persistence branch
  - **Out of Scope:** Clinical medical or psychiatric treatment protocols (not a therapeutic prescription in this file); athletic performance optimization as a standalone goal without values grounding; pharmacological or nutritional prescriptions; clinical burnout diagnosis

- **Included by Value**: [[HUMANITY:COURAGE]]
- **Includes Values**: None
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #7CB342
    - #7942B3
    - #B37942
    - #427CB3
    - #B3427C
    - #42B379
  - **Symbols**
    - **Sun / sunrise**: renewal + life-giving energy; "a new day" vitality.
    - **Heartbeat / pulse line**: aliveness in motion; vitality as sustained living energy.
    - **Sprout / green leaf**: growth force; vitality as thriving and regeneration.
    - **Flame**: inner drive; vitality as warmth, will, and momentum.
    - **Lightning bolt**: quick energy + activation; vitality as "spark" and readiness.
    - **Running figure**: vigor and endurance; vitality as active engagement in life.
    - **Flowing water**: refreshment and recovery; vitality as replenishment and resilience.
- **Literary Elements**
  - **Proverbs**
    - "**Health is wealth.**" — vitality is a foundation for everything else.
    - "**Early to bed and early to rise makes a man healthy, wealthy, and wise.**" — vitality is supported by good rhythms.
    - "**An apple a day keeps the doctor away.**" — vitality grows from daily habits.
    - "**Use it or lose it.**" — vitality is maintained by activity and practice.
    - "**A rolling stone gathers no moss.**" — staying in motion preserves energy and initiative.
    - "**You are what you eat.**" — vitality reflects nourishment and inputs.
  - **Quotations**
    - "**The first wealth is health.**" ~ Ralph Waldo Emerson, *The Conduct of Life* (1860), "Power."
    - "**It is not that we have a short time to live, but that we waste a lot of it.**" ~ Seneca, *On the Shortness of Life* (*De Brevitate Vitae*), trans. John W. Basore (Loeb, 1932).
    - "**I went to the woods because I wished to live deliberately…**" ~ Henry David Thoreau, *Walden* (1854).
    - "**Life is like riding a bicycle. To keep your balance you must keep moving.**" ~ Albert Einstein, letter to his son Eduard (5 Feb 1930).
    - "**ōrandum est ut sit mēns sāna in corpore sānō**" ("you should pray for a healthy mind in a healthy body") ~ Juvenal, *Satires* 10.356.
    - "**There is a vitality, a life force, an energy, a quickening that is translated through you into action…**" ~ Martha Graham.
  - **Myths**
    - **Demeter and Persephone** (Greek): explains seasonal renewal—vitality as cycles of loss and return.
    - **Idunn's Apples** (Norse): the gods' youth is sustained by apples—vitality as nourishment and renewal.
    - **Asclepius** (Greek): healing and restoration—vitality as the recovery of life-force.
    - **Gilgamesh and the Plant of Life** (Mesopotamian): the quest for renewed strength—vitality as fragile and precious.
    - **Phoenix** (Greco-Egyptian tradition): rebirth from ashes—vitality as resilience after collapse.
    - **Churning of the Ocean and Amrita** (Hindu): nectar of immortality—vitality as sustaining essence.
  - **Folktales**
    - **The Water of Life** (German/European): a healing journey—vitality restored through perseverance.
    - **The Fountain of Youth** (widely circulated): longing for renewed vigor—vitality as reclaimed life-energy.
    - **Stone Soup** (European): communal sharing restores strength—vitality as collective nourishment.
    - **Momotarō (Peach Boy)** (Japanese): food + courage for a quest—vitality as energizing purpose.
    - **Anansi and the Yam Hills / food tales** (West African variants): cleverness tied to sustenance—vitality as resourcefulness for survival.
    - **Paul Bunyan** (American folklore): outsized strength and stamina—vitality as "bigger-than-life" vigor.
  - **Fables**
    - **The Tortoise and the Hare** (Aesop): stamina beats flash—vitality as steady endurance.
    - **The Ant and the Grasshopper** (Aesop): prepare and persist—vitality supported by discipline.
    - **The Goose That Laid the Golden Eggs** (Aesop): don't destroy what sustains you—vitality needs restraint.
    - **The Town Mouse and the Country Mouse** (Aesop): simple living can preserve health—vitality over luxury stress.
    - **The Bundle of Sticks** (Aesopic tradition): strength in unity—vitality as shared resilience.
    - **The Farmer and the Stork** (Aesop): choices affect well-being—vitality protected by good judgment.
  - **Parables**
    - **The Two Arrows** (Buddhist): avoid "second-arrow" suffering—vitality as conserved energy and clarity.
    - **The Mustard Seed** (Buddhist): facing grief honestly—vitality as healing through acceptance.
    - **The Parable of the Sower**: what you cultivate grows—vitality as the outcome of conditions + care.
    - **The Burning House** (Buddhist): urgency to leave danger—vitality as wise escape and protection of life.
    - **The Good Samaritan**: compassionate action restores life—vitality as help in motion, not indifference.
    - **The Leaky Bucket** (folk-parable type): imperfections can still nourish—vitality despite flaws.
  - **Fairy Tales**
    - **The Twelve Dancing Princesses**: hidden nightly energy—vitality as mysterious, renewable force.
    - **The Elves and the Shoemaker**: restored livelihood—vitality as renewed capacity and hope.
    - **Hansel and Gretel**: survival under strain—vitality as grit and cleverness when depleted.
    - **Rapunzel** (various versions): healing and renewal motifs—vitality returning after hardship.
    - **The Snow Queen**: long, cold journey—vitality as persistence and warmth of love/friendship.
    - **Jack and the Beanstalk**: daring upward growth—vitality as bold expansion and striving.

##### Hope

ID: HUMANITY.ELEMENTS.VALUES.HOPE
TAGS: [[HUMANITY:HOPE]]

Believing that positive outcomes are possible even in difficult situations. It provides motivation, resilience, and a sense of optimism that fuels efforts toward improvement and progress. Hope helps individuals, families, and communities persist through challenges by envisioning a better future.

- **IF-LLM Application Example:** When a user or their community is experiencing prolonged difficulty and needs orientation toward possibility, an IF-LLM citing [[HUMANITY:HOPE]] produces a response that affirms the realism of hope — distinguishing it from wishful thinking or denial — and connects it to concrete reasons for optimism grounded in values and community. When distinguishing between hope as emotional resilience and purpose as directional action, cite [[HUMANITY:HOPE]] for the orienting belief and [[HUMANITY:PURPOSE]] (values-3.md) for the motivated direction toward a goal.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:TRANSCENDENCE]] (parent; Hope is a sub-value of Transcendence), [[HUMANITY:PERSISTENCE]] (Hope motivates sustained persistence), [[HUMANITY:PURPOSE]] (Hope and Purpose are sibling values under Transcendence), [[HUMANITY:VITALITY]] (Hope and Vitality mutually reinforce resilience and recovery), [[HUMANITY:COURAGE]] (Hope supports courageous action by affirming possibility)
  - **Requires:** [[HUMANITY:VALUES]] (hope is grounded in values and shared mission), [[HUMANITY:MISSION]] (hope orients toward mission-aligned futures)
  - **Required by:** [[HUMANITY:PERSISTENCE]] (without hope, persistence becomes mechanical; hope sustains motivational energy), [[HUMANITY:COURAGE]] (hope supports courageous acts by affirming that effort is worthwhile)
  - **Affects:** [[HUMANITY:OODA]] (hope shapes orientation and decision-making under uncertainty), [[HUMANITY:CAPABILITIES]] (hopeful outlook expands perceived and actual capabilities), [[HUMANITY:MOTIVATORS]] (hope is a primary intrinsic motivator)
  - **Vulnerable to:** [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (prolonged unmet needs erode hope over time), [[HUMANITY:TEMPTATIONS]] (despair and cynicism as temptations that displace hope), [[HUMANITY:STEREOTYPES]] (stereotyping forecloses possibility and undermines hope)

- **IF/THEN Decision Rules**
  - IF the context involves belief in positive outcomes despite present difficulty → THEN cite [[HUMANITY:HOPE]]
  - IF the context involves the broader cluster of transcendent meaning-making values → THEN cite [[HUMANITY:TRANSCENDENCE]] (values-3.md) and load values-3.md
  - IF the context involves sustained effort powered by hope → THEN also cite [[HUMANITY:PERSISTENCE]] (values-4.md) and load values-4.md
  - IF the context involves meaning-directed motivation alongside hope → THEN cite [[HUMANITY:PURPOSE]] (values-3.md) alongside [[HUMANITY:HOPE]]
  - IF hope is absent and despair or cynicism is present → THEN also cite [[HUMANITY:TEMPTATIONS]] and [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (if-llm-humanity-fallibility.md)

- **Scope/Exclusion Boundaries**
  - **In Scope:** Belief that positive outcomes are possible; optimism and resilience in difficulty; future orientation and envisioning a better state; hope as motivation and emotional sustenance; hope as a sub-value of Transcendence that also supports the Persistence branch through Courage
  - **Out of Scope:** Clinical treatment of depression or hopelessness (not a therapeutic protocol in this file); blind optimism or denial of real risks (distinguished from realistic hope in the literary elements above); prophetic or supernatural prediction of outcomes; promises of specific future outcomes or guarantees

- **Included by Value**: [[HUMANITY:TRANSCENDENCE]]
- **Includes Values**: None
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #66BB6A
    - #BB68B7
    - #B7BB68
    - #6C68BB
    - #BB6C68
    - #68B7BB
  - **Symbols**
    - **Anchor**: "anchors" the spirit in rough waters—steadfastness while waiting for a better tide.
    - **Sunrise / Dawn**: the next day arriving; a visual promise that darkness doesn't last forever.
    - **Candle / Lantern**: small light that persists—hope as guidance and endurance, even when fragile.
    - **Seedling / Green Shoot**: new life pushing through—future growth already beginning.
    - **Rainbow**: clearing after storm; hope as a sign of renewed possibility.
    - **Star (North Star)**: orientation and navigation—hope as direction when you can't see the whole path.
    - **Open Door / Pathway**: possibility and forward motion—hope as "a way through."
- **Literary Elements**
  - **Proverbs**
    - "**Where there's life, there's hope.**" — as long as you're here, possibility remains.
    - "**Hope springs eternal.**" — people naturally keep hoping, even after disappointment.
    - "**Every cloud has a silver lining.**" — insists on finding a possible good within hardship.
    - "**This too shall pass.**" — hope as patience with pain; conditions are temporary.
    - "**After the storm comes the calm.**" — suffering can be followed by relief and stability.
    - "**Dawn comes after the darkest night.**" — the low point is not the end of the story.
  - **Quotations (secular; sourced)**
    - "**'Hope' is the thing with feathers— / That perches in the soul—**" — Emily Dickinson, *"'Hope' is the thing with feathers"* (c. 1861; published posthumously).
    - "**Hope is not the conviction that something will turn out well, but the certainty that something makes sense, regardless of how it turns out.**" — Václav Havel, *Disturbing the Peace* (interviews 1985–86; English translation 1990).
    - "**But where there's hope, there's life. It fills us with fresh courage and makes us strong again.**" — Anne Frank, diary entry dated **June 6, 1944** (as quoted by the U.S. Holocaust Memorial Museum).
    - "**Hope is not a lottery ticket… It is an axe you break down doors with in an emergency.**" — Rebecca Solnit, *Hope in the Dark*.
    - "**Once you choose hope, anything's possible.**" — Christopher Reeve.
    - "**Hope is itself a species of happiness, and, perhaps, the chief happiness which this world affords.**" — Samuel Johnson.
  - **Myths**
    - **Pandora's Jar/Box and Elpis (Greek)**: even after calamities escape, "hope" remains—endurance when life breaks open.
    - **Persephone and the Seasons (Greek)**: winter gives way to spring—return and renewal built into the world.
    - **Prometheus Brings Fire (Greek)**: a "spark" given to humanity—hope as enabling power and progress against darkness.
    - **Inanna's Descent and Return (Sumerian)**: surviving the underworld—hope as return after loss and "death-like" seasons.
    - **Isis Restores Osiris (Egyptian)**: reassembly after destruction—hope as devotion, rebuilding, continuity.
    - **The Phoenix (Greco-Egyptian tradition)**: rebirth from ashes—hope as renewal after total collapse.
  - **Folktales**
    - **Stone Soup (European)**: in scarcity, shared effort creates abundance—hope as cooperative possibility.
    - **The Magic Porridge Pot (Germanic/European)**: provision appears when needed—hope that needs can be met (with responsibility).
    - **The Water of Life (German/European)**: a healing quest—hope as the pursuit of restoration.
    - **The Golden Fish (Slavic/Russian variants)**: hope mixed with restraint—don't let yearning become endless greed.
    - **The Two Frogs in the Cream (European variants)**: persistence creates a way out—hope as "keep going" when trapped.
    - **Momotarō, the Peach Boy (Japanese)**: a community backs a small hero—hope as collective courage against hardship.
  - **Fables**
    - **The Tortoise and the Hare (Aesop)**: steady effort wins—hope as consistency, not flash.
    - **The Crow and the Pitcher (Aesop)**: ingenuity under constraint—hope as creative problem-solving.
    - **The Lion and the Mouse (Aesop)**: help can come from the small—hope as unexpected rescue.
    - **The Bundle of Sticks (Aesop)**: strength in unity—hope as solidarity.
    - **The Oak and the Reed (Aesop)**: flexibility survives storms—hope as adaptive resilience.
    - **The Two Frogs (fable variants)**: refusing to quit changes outcomes—hope as sustained effort.
  - **Parables**
    - **The Mustard Seed (Buddhist parable)**: grief is universal; hope grows through connection and perspective.
    - **The Chinese Farmer ("Maybe") (Daoist/Zen retellings)**: uncertainty cuts both ways—hope as patience with unfolding events.
    - **The Lost Horse Returns (East Asian variants)**: what looks like misfortune can become fortune—hope as non-final judgment.
    - **The Star Thrower (modern parable)**: small acts still matter—hope as meaningful agency.
    - **The Stonecutter (Japanese/European variants)**: hope redirected toward contentment and purpose, not endless escalation.
  - **Fairy Tales**
    - **Cinderella**: hope sustained under injustice; endurance + kindness meet opportunity.
    - **Rapunzel**: hope for freedom and reunion despite confinement.
    - **The Ugly Duckling**: hope through identity change—belonging can arrive later.
    - **Beauty and the Beast**: hope that character can transform; love as redemptive possibility.
    - **Jack and the Beanstalk**: hope for a better life that demands risk and bold action.
    - **The Snow Queen**: hope as devotion and perseverance through cold, long trials.
