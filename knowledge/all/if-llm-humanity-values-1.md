# Humanity's Values 1 — Information-Following Large Language Model Knowledge (*if-llm-humanity-values-1.md*)

## File Header

- **Name:** Humanity's Values 1 — Information-Following Large Language Model Knowledge (*if-llm-humanity-values-1.md*)
- **Version:** 2026-06-17 04:26 UTC by [Lance Hegland](lance.hegland@gmail.com)
- **Last Reviewed:** 2026-06-17 04:26 UTC by [Lance Hegland](lance.hegland@gmail.com)
- **Owner:** [Lance Hegland](lance.hegland@gmail.com)

- **Purpose:** TBD
- **Audience:** Average, diverse people in the United States of America today.
- **Features**
  - TBD
- **Scope**
  - **Covers:** TBD
  - **Out of Scope:** TBD
- **Use Cases**
  - **Supported:** TBD
  - **Not Supported:** TBD

- **Dependencies (Required):** TBD
- **Stability:** Stable. Core entries, tag assignments, and namespace rules are intended to remain consistent across sessions. Silent reinterpretation of entries, tag reassignment, or scope expansion without an explicit Changelog entry is prohibited.
- **Known Gaps / Limitations**
  - TBD

- **Changelog**
  - 2026-06-17 07:50 UTC by [Lance Hegland](lance.hegland@gmail.com): Split `if-llm-humanity-values-4.md` containing 10 entries into two separate files as follows:
    - `if-llm-humanity-values-4.md` contains the 5 entries  `Justice` through `Persistence`
    - `if-llm-humanity-values-5.md` contains the entries  `Courage` through `Hope`
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
- `if-llm-humanity-values-5.md`
  - Courage → HUMANITY.ELEMENTS.VALUES.COURAGE → [[HUMANITY:COURAGE]]
  - Bravery → HUMANITY.ELEMENTS.VALUES.BRAVERY → [[HUMANITY:BRAVERY]]
  - Integrity → HUMANITY.ELEMENTS.VALUES.INTEGRITY → [[HUMANITY:INTEGRITY]]
  - Vitality → HUMANITY.ELEMENTS.VALUES.VITALITY → [[HUMANITY:VITALITY]]
  - Hope → HUMANITY.ELEMENTS.VALUES.HOPE → [[HUMANITY:HOPE]]

### Concept Disambiguation

Use these notes to select between partially overlapping concepts for precise IF-LLM retrieval and reasoning.

- TBD

### Local Knowledge Index

The following is a list of this file's common topic references mapped to canonical handles.

- Values → HUMANITY.ELEMENTS.VALUES → [[HUMANITY:VALUES]]
- Wisdom → HUMANITY.ELEMENTS.VALUES.WISDOM → [[HUMANITY:WISDOM]]
- Interdependence → HUMANITY.ELEMENTS.VALUES.INTERDEPENDENCE → [[HUMANITY:INTERDEPENDENCE]]
- Love → HUMANITY.ELEMENTS.VALUES.LOVE → [[HUMANITY:LOVE]]
- Critical Thinking → HUMANITY.ELEMENTS.VALUES.THINKING → [[HUMANITY:THINKING]]
- Curiosity → HUMANITY.ELEMENTS.VALUES.CURIOSITY → [[HUMANITY:CURIOSITY]]
- Open-Mindedness → HUMANITY.ELEMENTS.VALUES.OPENNESS → [[HUMANITY:OPENNESS]]

## Humanity

### Elements

#### Values

ID: HUMANITY.ELEMENTS.VALUES
TAGS: [[HUMANITY:VALUES]]

Values based on humanity's most significant [[HUMANITY:LESSONS]] that have been gathered, tested, refined, and shared throughout human history across our many diverse communities and societies; [[HUMANITY:WISDOM]].

- [[HUMANITY:VALUES]] relationship heuristic:
  - [[HUMANITY:ROOT]] values [[HUMANITY:WISDOM]].
  - [[HUMANITY:WISDOM]] is [[HUMANITY:INTERDEPENDENCE]]; [[HUMANITY:INTERDEPENDENCE]] is [[HUMANITY:WISDOM]].
  - [[HUMANITY:INTERDEPENDENCE]] requires [[HUMANITY:COMPASSION]] and [[HUMANITY:PERSISTENCE]].
  - [[HUMANITY:INTERDEPENDENCE]] includes [[HUMANITY:LOVE]] and [[HUMANITY:THINKING]].
  - [[HUMANITY:THINKING]] includes [[HUMANITY:CURIOSITY]], [[HUMANITY:OPENNESS]], [[HUMANITY:PERSPECTIVE]], [[HUMANITY:LEARNING]] and [[HUMANITY:CREATIVITY]].
  - [[HUMANITY:COMPASSION]] includes [[HUMANITY:TEMPERANCE]], [[HUMANITY:TRANSCENDENCE]], and [[HUMANITY:JUSTICE]].
  - [[HUMANITY:TEMPERANCE]] includes [[HUMANITY:MERCY]], [[HUMANITY:HUMILITY]], [[HUMANITY:PRUDENCE]], and [[HUMANITY:REGULATION]].
  - [[HUMANITY:TRANSCENDENCE]] includes [[HUMANITY:GRATITUDE]], [[HUMANITY:PURPOSE]], [[HUMANITY:EXCELLENCE]], and [[HUMANITY:HUMOR]] as those values relate to [[HUMANITY:COMPASSION]].
  - [[HUMANITY:TRANSCENDENCE]] includes [[HUMANITY:HOPE]] as hope relates to [[HUMANITY:PERSISTENCE]].
  - [[HUMANITY:JUSTICE]] includes [[HUMANITY:FAIRNESS]], [[HUMANITY:CITIZENSHIP]], and [[HUMANITY:LEADERSHIP]].
  - [[HUMANITY:PERSISTENCE]] includes [[HUMANITY:COURAGE]] and [[HUMANITY:HOPE]] (i.e., [[HUMANITY:HOPE]] is the only value included in [[HUMANITY:TRANSCENDENCE]] that is also included in [[HUMANITY:PERSISTENCE]]; [[HUMANITY:HOPE]] is the only value included in [[HUMANITY:TRANSCENDENCE]] that is also excluded in [[HUMANITY:COMPASSION]]).
  - [[HUMANITY:COURAGE]] includes [[HUMANITY:BRAVERY]], [[HUMANITY:INTEGRITY]], and [[HUMANITY:VITALITY]].

- **Examples**
  - **When a user faces a moral dilemma or asks "what should I do?":** Cite [[HUMANITY:VALUES]] as the ethical guidance layer; use the VALUES heuristic to identify which value cluster (Compassion, Persistence, Thinking, Justice, etc.) is most relevant to the situation, then move to the specific value entry.
  - **When explaining why something that felt good caused harm:** Cite [[HUMANITY:VALUES]] alongside [[HUMANITY:TEMPTATIONS]] — the temptation overrode the relevant value (e.g., Immediate Gratification overrode [[HUMANITY:PRUDENCE]]; Deception overrode [[HUMANITY:INTEGRITY]]).
  - **When a user is trying to understand why they keep quitting hard things:** Cite [[HUMANITY:PERSISTENCE]] → [[HUMANITY:COURAGE]] → [[HUMANITY:HOPE]] as the relevant value chain; connect to [[HUMANITY:MOTIVATORS]] (what drives are sustaining vs. depleted) and [[HUMANITY:RESOURCES]] (is energy the actual constraint?).
  - **When integrating ethical guidance into an OODA recommendation:** At the Orient step, check [[HUMANITY:PERSPECTIVE]] and [[HUMANITY:HUMILITY]]; at the Decide step, check [[HUMANITY:PRUDENCE]] and [[HUMANITY:FAIRNESS]]; at the Act step, check [[HUMANITY:INTEGRITY]] and [[HUMANITY:REGULATION]].
  - **When explaining why diverse communities share core values despite different cultural expressions:** Cite [[HUMANITY:VALUES]] as the universal framework; use Literary Elements within individual value entries to demonstrate how the same values appear across cultures in different symbolic forms.

- **Boundaries / Scope**
  - **Includes:** The 30 values organized by the VALUES heuristic; the relationship structure among them; the ethical guidance layer applicable across all other Humanity knowledge entries; the literary and symbolic representations within each individual value entry.
  - **Excludes:** Clinical therapy or formal values-clarification assessment; religious doctrine or theological argument about the source of values; policy prescription; individual case adjudication; historical or biographical analysis of values sources.
  - **Primary purpose:** Enable IF-LLM to identify *which value or value cluster is most relevant* to a user's situation — and to use that value as an ethical anchor for reasoning, explaining, or guiding behavior.

- **Decision Rules (IF/THEN)**
  - **IF** a user asks for ethical guidance, **THEN** use the VALUES heuristic to identify the relevant value cluster first (Compassion branch vs. Persistence branch), then move to the specific value entry.
  - **IF** multiple values are in tension, **THEN** trace the VALUES heuristic: values higher in the hierarchy (Wisdom, Interdependence) often resolve tension between lower-order values by providing the integrating principle.
  - **IF** a user describes a struggle that is primarily about sustained effort or follow-through, **THEN** start with the [[HUMANITY:PERSISTENCE]] branch (Courage, Hope, Bravery, Integrity, Vitality).
  - **IF** a user describes a struggle involving how to treat others or navigate conflict, **THEN** start with the [[HUMANITY:COMPASSION]] branch (Temperance, Transcendence, Justice and their sub-values).
  - **IF** a user mentions "hope" without clarifying context, **THEN** check whether it relates to meaning and transcendence (cite [[HUMANITY:TRANSCENDENCE]]) or sustained effort despite hardship (cite [[HUMANITY:PERSISTENCE]]); see Concept Disambiguation for guidance.
  - **IF** a user asks what everyone has in common aspirationally, **THEN** cite [[HUMANITY:VALUES]] as the framework alongside [[HUMANITY:NEEDS]] (structural baseline) and [[HUMANITY:RIGHTS]] (equal opportunity) — together these form the shared human foundation.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:NEEDS]] (values guide *how* we act to satisfy needs; needs define *what* must be satisfied); [[HUMANITY:MOTIVATORS]] (values are long-horizon motivational anchors; motivators are short-horizon energizing drives); [[HUMANITY:LESSONS]] (values are distilled from humanity's most significant accumulated lessons); [[HUMANITY:MISSION]] (values govern how the mission is performed); [[HUMANITY:OODA]] (values provide ethical checks at each OODA step — especially Orient and Decide); [[HUMANITY:FALLIBILITY]] (without fallibility awareness, values become performative rather than practiced)
  - **Grounds:** All 30 individual value entries, organized through [[HUMANITY:WISDOM]] → [[HUMANITY:INTERDEPENDENCE]] → [[HUMANITY:COMPASSION]] and [[HUMANITY:PERSISTENCE]] branches
  - **Required by:** [[HUMANITY:OODA]] decision-making at the Orient and Decide steps; [[HUMANITY:ACTIVITIES]] selection when ethical choices are at stake; [[HUMANITY:MISSION]] performance in ways that benefit both individuals and community
  - **Vulnerable to:** [[HUMANITY:TEMPTATIONS]] (values can be rationalized away or bypassed under resource depletion or stress); [[HUMANITY:STEREOTYPES]] and [[HUMANITY:PREJUDICES]] (which can distort how values are applied across groups); [[HUMANITY:DISCRIMINATION]] (which can systematically restrict who gets to benefit from values in practice)
  - **Reinforced by:** [[HUMANITY:INTERDEPENDENCE]] (shared practice strengthens values across community); [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (experiencing the cost of values violations motivates return to values); [[HUMANITY:COPING]] (values-aligned coping sustains wellbeing through difficulty); [[HUMANITY:EXPERTS]] (Reasoning Experts explain *why* values work; History Experts show *where* they have been proven across time)

##### Wisdom

ID: HUMANITY.ELEMENTS.VALUES.WISDOM
TAGS: [[HUMANITY:WISDOM]]

Consistently gathering, testing, and refining evidence of humanity’s most significant [[HUMANITY:LESSONS]] plus sharing those lessons (i.e. offering testimonials) across our many diverse communities and societies. Basically, these lessons indicate that consistently practicing [[HUMANITY:INTERDEPENDENCE]] often increases the likelihood of more efficiently nurturing and sustaining [[HUMANITY:RESOURCES]], more efficiently performing [[HUMANITY:ACTIVITIES]], and subsequently more efficiently satisfying [[HUMANITY:NEEDS]], collectively, on average, over time. Wisdom is the ability to apply our [[HUMANITY:RESOURCES]] to perform [[HUMANITY:ACTIVITIES]] to satisfy [[HUMANITY:NEEDS]] in a thoughtful and ethical manner. It involves making sound judgments, considering long-term consequences, and acting in ways that benefit both individuals and society, in the present place and time plus elsewhere and throughout the future. Ultimately, it means striving to consistently perform our [[HUMANITY:MISSION]] and contribute to our [[HUMANITY:VISION]].

- **Included by Value**: None
- **Includes Values**: [[HUMANITY:INTERDEPENDENCE]]
- **Experiential Evidence** (Pattern Learning): Repeatedly experiencing that consistently practicing wisdom often makes it easier to efficiently satisfy [[HUMANITY:NEEDS]], collectively, on average, over time.
  - more frequently and consistently practicing compassion often improves relationships and reduces conflict;
  - more frequently and consistently practicing persistence often helps finish hard things;
  - more frequently and consistently practicing interdependence often creates bigger, stronger, and more impactful safety nets;
  - more frequently and consistently practicing wisdom often prevents avoidable messes.
- **Social Reinforcement**: People are more likely to be more frequently, more consistently, and more significantly socially rewarded with support satisfying their [[HUMANITY:NEEDS]] (i.e., or, at least, less likely to experience more frequent, more consistent, and more significant social harms and risks to their ability to satisfy their [[HUMANITY:NEEDS]]) within their affiliated institutions (e.g., families, peer groups, spiritual communities, schools, workplaces), which reinforce these values as follows:
  - praising them;
  - telling illustrative stories about them;
  - building rituals around them;
  - sanctioning choices and actions that do not consistently demonstrate them (e.g., selfishness, rashness, quitting)
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #4B0082
    - #358000
    - #003580
    - #804A00
    - #00804A
    - #800035
  - **Symbols**
    - **Owl**: culturally associated with insight, “seeing in the dark,” and careful observation.
    - **Lamp / Lantern**: wisdom as illumination—revealing what was hidden and guiding steps forward.
    - **Open Book**: learning + reflection; wisdom as knowledge *integrated* over time.
    - **Tree**: long-lived growth, roots (principles), and branching understanding; especially an old oak / “tree of knowledge”.
    - **Key**: discernment—unlocking meaning, solutions, or the “right question.”
    - **Compass**: moral/intellectual direction—staying oriented amid complexity.
    - **Mirror**: self-examination; wisdom as honest reflection and humility.
- **Literary Elements**
  - **Proverbs**
    - “**Look before you leap.**” — wise action anticipates consequences.
    - “**Measure twice, cut once.**” — careful thinking prevents avoidable mistakes.
    - “**A stitch in time saves nine.**” — timely correction is practical wisdom.
    - “**Still waters run deep.**” — wisdom is often quiet, not performative.
    - “**You reap what you sow.**” — recognizes cause-and-effect and moral accountability.
    - “**When in doubt, leave it out.**” — restraint can be wiser than overconfidence.
  - **Quotations**
    - “**The fool doth think he is wise, but the wise man knows himself to be a fool.**” ~ William Shakespeare, *As You Like It*, Act 5, Scene 1 (c. 1599).
    - “**Where is the wisdom we have lost in knowledge? Where is the knowledge we have lost in information?**” ~ T. S. Eliot, *Choruses from “The Rock”* (1934).
    - “**A wise man, therefore, proportions his belief to the evidence.**” ~ David Hume, *An Enquiry Concerning Human Understanding* (1748), “Of Miracles.”
    - “**…the unexamined life is not worth living…**” ~ Plato, *Apology*, 38a (Socrates speaking; commonly translated into English this way).
    - “**Sapere aude! Have courage to use your own understanding!**” ~ Immanuel Kant, “An Answer to the Question: What is Enlightenment?” (1784).
  - **Myths**
    - **Athena and Arachne** (Greek): wisdom includes humility; skill without reverence becomes arrogance.
    - **Odin at Mímir’s Well** (Norse): wisdom demands sacrifice and commitment to insight.
    - **Oedipus and the Sphinx** (Greek): intelligence as problem-solving—yet warns that knowledge without self-knowledge can mislead.
    - **Daedalus and Icarus** (Greek): wise limits; ignoring counsel leads to downfall.
    - **King Midas** (Greek): the “wish” myth—wisdom distinguishes value from glitter.
    - **Gilgamesh’s search for immortality** (Mesopotamian): wisdom as acceptance of human limits and meaningful legacy.
  - **Folktales**
    - **Stone Soup** (European): communal wisdom—shared contribution creates abundance.
    - **Anansi and the Pot of Wisdom** (West African/Ashanti): wisdom can’t be hoarded; it spreads in community.
    - **The Empty Pot** (Chinese): integrity and truthfulness are marks of real wisdom.
    - **Why the Sea Is Salt** (Scandinavian): cautionary wisdom about greed and consequences.
    - **Nasreddin Hodja tales** (Middle Eastern): “wise fool” humor that exposes pride and faulty logic.
    - **The Three Questions** (widely circulated; famously retold in many forms): wisdom centers on the right time, the right person, the right action.
  - **Fables**
    - **The Ant and the Grasshopper** (Aesop): prudence and planning outperform short-term pleasure.
    - **The Tortoise and the Hare** (Aesop): steady discipline beats overconfidence.
    - **The Crow and the Pitcher** (Aesop): creative problem-solving as practical wisdom.
    - **The Boy Who Cried Wolf** (Aesop): wisdom includes credibility and long-term trust.
    - **The Fox and the Grapes** (Aesop): warns against self-deception and rationalization.
    - **The Lion and the Mouse** (Aesop): humility—wisdom recognizes value in the “small.”
  - **Parables**
    - **The Wise and Foolish Builders**: wisdom builds on a firm foundation (values/practice), not appearance.
    - **The Sower**: wisdom is receptivity and perseverance—conditions shape outcomes.
    - **The Good Samaritan**: wisdom includes compassion beyond tribal boundaries.
    - **The Prodigal Son**: wisdom as repentance, mercy, and restored relationship.
    - **The Talents**: wise stewardship—using gifts responsibly rather than burying them.
    - **The Rich Fool**: warns that “smart” accumulation can still be unwise without purpose.
  - **Fairy Tales**
    - **The Three Little Pigs**: wisdom = preparation and durable choices.
    - **Little Red Riding Hood**: practical wisdom about boundaries, trust, and listening to good counsel.
    - **Beauty and the Beast**: wise perception—seeing character beneath appearances.
    - **The Fisherman and His Wife**: wisdom about contentment and the dangers of endless wanting.
    - **Cinderella**: patient virtue and discernment amid unfairness; wisdom isn’t always loud.
    - **The Emperor’s New Clothes**: collective self-deception—and the wisdom of honest speech.

##### Interdependence

ID: HUMANITY.ELEMENTS.VALUES.INTERDEPENDENCE
TAGS: [[HUMANITY:INTERDEPENDENCE]]

How everything is connected and relies on each other for health and safety. Interdependence means we are part of a huge, diverse, and complex interconnected system that includes other human beings, other living beings, plus things in our environment. Interdependence requires us to consider how our decisions and actions impact others, their needs, in addition to our needs. Interdependence is the mutual reliance between human beings, other living beings, plus things in our environment; including other individuals, families, communities, and societies. Interdependence requires appreciation of others and their contributions; requires us to value cooperation plus shared responsibility to collective well-being. Interdependence requires [[HUMANITY:COMPASSION]] and [[HUMANITY:PERSISTENCE]] for ourselves and others.

- **Included by Value**: [[HUMANITY:WISDOM]]
- **Includes Values**
  - Secondary Values: [[HUMANITY:COMPASSION]] and [[HUMANITY:PERSISTENCE]]
  - Tertiary Values: [[HUMANITY:LOVE]] and [[HUMANITY:THINKING]]
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #00897B
    - #8A000E
    - #0E8A00
    - #7C008A
    - #8A7C00
    - #000E8A
  - **Symbols**
    - **Linked hands**: mutual support, cooperation, and “we do this together.”
    - **Chain links**: strength and reliability come from connection; each link affects the whole.
    - **Spiderweb / network graph**: interconnection—movement or damage in one place affects others.
    - **Knot / Celtic knot**: enduring bonds; relationships that hold under strain.
    - **Bridge**: connection across difference (people/communities/resources) enabling shared well-being.
    - **Circle of people**: inclusion + shared responsibility; no single “center” dominates.
    - **Mycelium / root network**: hidden support systems that share resources across the whole.
- **Literary Elements**
  - **Proverbs**
    - “**Many hands make light work.**” — shared effort reduces individual burden.
    - “**It takes a village.**” — people develop best inside supportive communities.
    - “**Two heads are better than one.**” — collective thinking improves decisions.
    - “**One hand washes the other.**” — reciprocity; mutual benefit sustains trust.
    - “**United we stand, divided we fall.**” — unity improves resilience and safety.
    - “**A chain is only as strong as its weakest link.**” — the group’s well-being depends on each part.
  - **Quotations**
    - “**We are caught in an inescapable network of mutuality, tied in a single garment of destiny…**” — *Martin Luther King Jr.*, **“Letter from Birmingham Jail”** (1963).
    - “**No man is an island… every man is a piece of the continent…**” — *John Donne*, **Devotions upon Emergent Occasions**, Meditation XVII (1624).
    - “**Alone we can do so little; together we can do so much.**” — *Helen Keller* (attributed to a speech excerpt).
    - “**The good we secure for ourselves is precarious and uncertain until it is secured for all of us and incorporated into our common life.**” — *Jane Addams* (often cited from her work *Democracy and Social Ethics*).
    - “**We must all hang together, or, most assuredly, we shall all hang separately.**” — *Benjamin Franklin* (commonly attributed to him around the signing of the Declaration).
  - **Myths**
    - **Indra’s Net** (Hindu/Buddhist tradition): reality as a web where each part reflects and affects all.
    - **Yggdrasil** (Norse): a “world tree” binding realms—cosmic interconnection and dependence.
    - **Demeter and Persephone** (Greek): cycles of life (seasons/harvest) depend on relational restoration.
    - **Gaia** (Greek): Earth as a living whole—life systems interrelate and must stay in balance.
    - **Spider Woman** (Hopi and related Southwestern traditions, in many retellings): life as a woven web of relations and responsibilities.
  - **Folktales**
    - **Stone Soup**: pooled small contributions create shared abundance.
    - **The Bremen Town Musicians**: the weak become safe by forming a coalition.
    - **The Enormous Turnip**: success requires everyone pulling together—including the smallest helper.
    - **The Mitten** (Ukrainian): shared shelter and negotiated space keep many safe.
    - **Swimmy** (often treated as a modern folktale): coordinated action protects the vulnerable from bigger threats.
  - **Fables**
    - **The Bundle of Sticks** (Aesop): unity creates strength; isolation invites breaking.
    - **The Lion and the Mouse** (Aesop): “small” help matters; mutual aid can save the powerful too.
    - **The Ant and the Dove** (Aesop): kindness circulates—help returned in unexpected ways.
    - **The Four Oxen and the Lion** (Aesop): divided, they’re vulnerable; together, they’re safe.
    - **The Father and His Sons** (often told as a fable): cooperation prevents avoidable harm.
  - **Parables**
    - **The Good Samaritan**: care crosses group boundaries; we rely on “neighbors” beyond tribe.
    - **The Lost Sheep**: the group bears responsibility for the vulnerable member.
    - **The Unforgiving Servant**: social life depends on mercy/repair; unforgiveness breaks community.
    - **The Sower**: outcomes depend on conditions outside the seed itself—context and support matter.
    - **The Workers in the Vineyard**: community cohesion requires shared norms of fairness and care.
  - **Fairy Tales**
    - **The Elves and the Shoemaker**: unseen help sustains livelihoods; gratitude/reciprocity completes the cycle.
    - **Snow White and the Seven Dwarfs**: mutual shelter and shared work create safety and belonging.
    - **Hansel and Gretel**: survival depends on cooperation, courage, and shared problem-solving.
    - **The Little Red Hen**: a cautionary tale—refusal to contribute breaks reciprocity and shared benefit.
    - **The Three Little Pigs**: shared refuge and preparation protect the group from predictable threats.

##### Love

ID: HUMANITY.ELEMENTS.VALUES.LOVE
TAGS: [[HUMANITY:LOVE]]

Deep and enduring sense of care, connection, and commitment toward other people, other living beings, our environment, and ourselves. Love fosters emotional bonds, trust, and support in relationships, our [[HUMANITY:INTERDEPENDENCE]]. It motivates kindness, sacrifice, and a willingness to act for the well-being of others. Love is foundational for strong relationships, families, and communities, reinforcing the shared responsibility and emotional connection that sustain [[HUMANITY:INTERDEPENDENCE]]. Love motivates us to support, nurture, and protect other people, other living beings, our environment, and ourselves. It involves wanting the best for others and can strengthen connections between people, living beings, and our environment to foster harmony and understanding in relationships and communities.

- **Included by Value**: [[HUMANITY:INTERDEPENDENCE]]
- **Includes Values**: None
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #E53935
    - #34E2E5
    - #E534E2
    - #34E537
    - #3734E5
    - #E2E534
  - **Symbols**
    - **Heart-in-hands**: love as *active care*—choosing to protect and support others.
    - **Open hands (giving hands)**: generosity, service, and the willingness to help.
    - **Helping hand / mutual aid icon**: love expressed through practical support and shared responsibility.
    - **Shelter/roof over a figure**: love as protection—creating safety and stability for others.
    - **Seedling / watering can**: nurturing growth in people, communities, and even ecosystems.
    - **Circle of people (community ring)**: love sustaining families/communities through belonging and mutual support.
    - **Bandage / first-aid symbol**: compassion-in-action—love that heals and reduces harm.
- **Literary Elements**
  - **Proverbs**
    - “**No act of kindness is ever wasted.**” — love shows up as consistent care.
    - “**Kindness costs nothing.**” — love is accessible as everyday practice.
    - “**Charity begins at home.**” — love includes responsibility to those closest (and can expand outward).
    - “**A friend in need is a friend indeed.**” — love proves itself through support under strain.
    - “**You catch more flies with honey than vinegar.**” — gentleness and goodwill work better than harshness.
    - “**A house divided against itself cannot stand.**” — love helps hold families/communities together through unity.
  - **Quotations**
    - “**Love is as love does… an act of will… We choose to love.**” — *bell hooks*, *All About Love*.
    - “**Love is the only force capable of transforming an enemy into a friend.**” — *Martin Luther King Jr.*.
    - “**Love isn't a state of perfect caring… it is an active noun… To love… is to strive to accept… right here and now.**” — *Fred Rogers*.
    - “**Love and compassion are necessities, not luxuries. Without them, humanity cannot survive.**” — *Dalai Lama XIV*, *The Art of Happiness*.
    - “**No one has ever become poor by giving.**” — *Anne Frank*
    - “**…the good we secure for ourselves is precarious… until it is secured for all of us and incorporated into our common life.**” — *Jane Addams*
  - **Myths**
    - **Demeter and Persephone** (Greek): nurturing, protective love sustaining life and community.
    - **Isis and Osiris** (Egyptian): restorative devotion—love that rebuilds after loss.
    - **Prometheus** (Greek): sacrificial love for humanity—taking risks to help others thrive.
    - **Kuan Yin / Avalokiteśvara traditions** (East Asian/Buddhist): compassion as universal, responsive love toward suffering.
    - **Philemon and Baucis** (Greco-Roman): love expressed as hospitality, generosity, and care for strangers (community love).
  - **Folktales**
    - **Stone Soup**: love as shared contribution—community care creates abundance.
    - **The Enormous Turnip**: collective helping—everyone’s pull matters, even the smallest.
    - **The Grateful Crane** (Japan, many versions): gratitude and self-giving care (often framed as kindness repaid).
    - **The Grateful Dead** (international folktale motif): compassion rewarded; honoring dignity even when it’s costly.
    - **The Mitten** (Eastern Europe): shared warmth/shelter—making room for others.
    - **Anansi and the Pot of Wisdom** (West Africa, often taught similarly): care and wisdom aren’t hoarded—shared for communal good.
  - **Fables**
    - **The Lion and the Mouse** (Aesop): mercy and care create unexpected mutual rescue.
    - **The Ant and the Dove** (Aesop): love as reciprocal protection—help offered, help returned.
    - **Androcles and the Lion** (traditional): kindness builds trust that can override fear.
    - **The North Wind and the Sun** (Aesop): gentleness succeeds where force fails—love persuades without coercion.
    - **The Travelers and the Bear** (Aesop): a caution that love includes loyalty and not abandoning others.
  - **Parables**
    - **The Good Samaritan**: love crosses boundaries; care for the vulnerable stranger.
    - **The Lost Sheep**: love pursues and protects those at risk of being forgotten.
    - **The Unforgiving Servant**: love includes mercy; refusing mercy fractures community.
    - **The Star Thrower** (modern parable): love is small-but-real action to reduce suffering.
    - **The Parable of the Two Wolves**: love as the practice of feeding compassion over harm.
    - **The Bridge Builder**: love as building passage for those who come after.
  - **Fairy Tales**
    - **The Selfish Giant** (Oscar Wilde): love as welcome, generosity, and protection of children.
    - **The Elves and the Shoemaker**: gratitude and mutual care sustain livelihoods.
    - **The Ugly Duckling**: love as belonging and acceptance—seeing worth beyond exclusion.
    - **The Star Money** (Grimm): radical generosity to the needy.
    - **The Little Match Girl** (Andersen): a compassion story—meant to awaken protective love in the reader/community.
    - **The Snow Queen** (Andersen): steadfast friendship-love and rescue—devotion without romance.

##### Critical Thinking

ID: HUMANITY.ELEMENTS.VALUES.THINKING
TAGS: [[HUMANITY:THINKING]]

Analyzing, evaluating, and questioning information, ideas, and beliefs to make well-reasoned and informed decisions. It requires logic, skepticism, and a willingness to consider different perspectives. It involves examining evidence, identifying biases, and considering multiple perspectives before making decisions or forming opinions. Critical thinking helps individuals navigate complex issues, avoid manipulation, and make better judgments, contributing to a more informed and thoughtful society.

- **Included by Value**: [[HUMANITY:INTERDEPENDENCE]]
- **Includes Values**: [[HUMANITY:CURIOSITY]], [[HUMANITY:OPENNESS]], [[HUMANITY:PERSPECTIVE]], [[HUMANITY:LEARNING]], and [[HUMANITY:CREATIVITY]]
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #1565C0
    - #C17115
    - #15C171
    - #C11565
    - #65C115
    - #7115C1
  - **Symbols**
    - **Magnifying Glass**: close inspection; “look for the evidence.”
    - **Question Mark**: skepticism and inquiry before belief.
    - **Scales of Justice / Balance Scale**: weighing competing claims and tradeoffs.
    - **Brain / Head silhouette with gears**: structured reasoning and mental discipline.
    - **Checklist / Clipboard**: methodical verification; reduce missed steps and bias.
    - **Graph / Chart**: evidence-based thinking; patterns, trends, and falsifiability.
    - **Puzzle Pieces**: assembling facts into a coherent model; spotting missing pieces.
- **Literary Elements**
  - **Proverbs**
    - “**Trust, but verify.**” — skepticism with fairness; confirm claims.
    - “**Look before you leap.**” — evaluate consequences before acting.
    - “**Measure twice, cut once.**” — careful checking prevents costly errors.
    - “**Consider the source.**” — assess credibility and incentives.
    - “**The devil is in the details.**” — small assumptions can break conclusions.
    - “**Don’t believe everything you hear.**” — resist rumors/manipulation.
  - **Quotations**
    - “**What can be asserted without evidence can also be dismissed without evidence.**” — Christopher Hitchens (often cited as *Hitchens’s razor*).
    - “**The first principle is that you must not fool yourself—and you are the easiest person to fool.**” — Richard P. Feynman, “Cargo Cult Science” (1974).
    - “**It is wrong always, everywhere, and for anyone, to believe anything upon insufficient evidence.**” — W. K. Clifford, *The Ethics of Belief*.
    - “**Extraordinary claims require extraordinary evidence.**” — popularized by Carl Sagan (often called the “Sagan standard”).
    - “**The greatest enemy of knowledge is not ignorance; it is the illusion of knowledge.**” — often attributed to Daniel J. Boorstin (commonly misattributed to others).
    - “**Believe those who are seeking the truth. Doubt those who find it.**” — widely attributed to André Gide.
  - **Myths**
    - **Oedipus and the Sphinx** (Greek): puzzle-solving; reasoning under pressure.
    - **Daedalus and Icarus** (Greek): ignoring constraints/evidence leads to failure.
    - **Cassandra** (Greek): how bias/social incentives can cause people to dismiss warnings.
    - **Pandora’s Box** (Greek): curiosity without forethought; second-order effects.
    - **Theseus and the Minotaur** (Greek): planning and “tools” (Ariadne’s thread) as problem-solving.
  - **Folktales**
    - **The Blind Men and the Elephant** (South Asian): limited data → flawed certainty; need multiple perspectives.
    - **Nasreddin Hodja tales** (Middle Eastern): “wise fool” stories that expose bad logic and assumptions.
    - **The Three Questions** (widely circulated): prioritization and situational judgment over abstract certainty.
    - **Anansi and the Pot of Wisdom** (West African/Ashanti): knowledge spreads; no one person sees everything.
    - **The Clever Rabbit and the Lion** (Panchatantra tradition): strategy and reasoning beat brute force.
  - **Fables**
    - **The Fox and the Crow** (Aesop): flattery bypasses judgment—don’t be “hacked.”
    - **The Boy Who Cried Wolf** (Aesop): credibility is evidence capital; lying destroys signal.
    - **The Wolf in Sheep’s Clothing** (Aesop): appearances mislead; verify identity/intent.
    - **The Fox and the Grapes** (Aesop): rationalization and self-serving bias.
    - **The Crow and the Pitcher** (Aesop): iterative problem-solving and experimentation.
    - **The Tortoise and the Hare** (Aesop): consistent method beats impulsive overconfidence.
  - **Parables**
    - **The House on Rock vs. Sand**: beliefs/actions need a tested foundation, not vibes.
    - **The Wheat and the Tares**: avoid premature judgment; uncertainty is real.
    - **The Poisoned Arrow** (Buddhist): focus on actionable questions; don’t get lost in untestable speculation.
    - **The Blind Turtle and the Yoke** (Buddhist): highlights base rates/probability—rare events are rare.
    - **The Raft** (Buddhist): models/tools are useful—don’t cling to them when they stop serving truth.
  - **Fairy Tales**
    - **The Emperor’s New Clothes**: social pressure overrides perception; speak the observable.
    - **Little Red Riding Hood**: verify identity; don’t accept a convincing disguise.
    - **Bluebeard**: warning signs and rule-testing; don’t ignore constraints.
    - **Hansel and Gretel**: problem-solving under scarcity; avoid obvious traps.
    - **The Princess and the Pea**: “testing a claim” (a crude experiment), though it also satirizes elitism.

##### Curiosity

ID: HUMANITY.ELEMENTS.VALUES.CURIOSITY
TAGS: [[HUMANITY:CURIOSITY]]

Desire to explore, learn, and understand new things. It drives people to ask questions, seek new knowledge, discover new experiences, and gain a deeper understanding of other people, other living beings, our environment, and ourselves. Curiosity fuels intellectual and creative growth, leading to a deeper understanding of complex issues.

- **Included by Value**: [[HUMANITY:THINKING]]
- **Includes Values**: None
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #FF9800
    - #0066FF
    - #FF0066
    - #00FF99
    - #9900FF
    - #66FF00
  - **Symbols**
    - **Magnifying glass**: looking closer; examining details you’d otherwise miss.
    - **Question mark**: the habit of asking “why?” and “how?”
    - **Open book**: active learning—curiosity turning into knowledge.
    - **Telescope / microscope**: exploration of the unknown (big or small); discovery mindset.
    - **Lightbulb**: insight that follows investigation (“aha!” moments).
    - **Footprints / path**: following a trail of clues; willingness to venture beyond the familiar.
    - **Lab flask / beaker**: experimentation—testing ideas to learn what’s true.
- **Literary Elements**
  - **Proverbs**

    - “**Curiosity killed the cat.**” — a caution: curiosity can create risk if reckless.
    - “**Ask questions and you’ll learn.**” — curiosity as the engine of growth.
    - “**He who asks a question remains a fool for five minutes; he who does not ask remains a fool forever.**” (often labeled a “Chinese proverb”) — values inquiry over pride.
    - “**Look before you leap.**” — channel curiosity into investigation before action.
    - “**Don’t judge a book by its cover.**” — curiosity pushes past appearances to reality.
    - “**Knowledge is power.**” — curiosity builds knowledge that increases capability.
  - **Quotations**
    - “**The important thing is not to stop questioning.** … **Never lose a holy curiosity.**” — *Albert Einstein* (attributed to a Life magazine memoir source).
    - “**I have no special talents. I am only passionately curious.**” — *Albert Einstein*, letter to Carl Seelig (Mar 11, 1952) often cited with Einstein Archive reference.
    - “**Curiosity is the wick in the candle of learning.**” — *William Arthur Ward*.
    - “**The cure for boredom is curiosity. There is no cure for curiosity.**” — *Dorothy Parker*.
    - “**All men by nature desire to know.**” — *Aristotle*, *Metaphysics*.
    - “**…it is owing to their wonder that men both now begin and at first began to philosophize…**” — *Aristotle*, *Metaphysics*.
    - “**Curiosity is, in great and generous minds, the first passion and the last.**” — *Samuel Johnson*.
  - **Myths**
    - **Pandora’s Box** (Greek): curiosity opens the unknown—can bring trouble, but also hope and insight.
    - **Odin at Mímir’s Well** (Norse): relentless desire for knowledge, even at great personal cost.
    - **Prometheus** (Greek): curiosity + foresight push boundaries of what humans can know/do.
    - **Orpheus and Eurydice** (Greek): curiosity/uncertainty (“looking back”) shows how doubt can undo a quest.
    - **Psyche and Cupid** (Greco-Roman): curiosity to “see” what’s hidden—truth-seeking with relational consequences.
    - **Tree of Knowledge** (Genesis tradition): curiosity for moral/experiential knowledge—portrayed as transformative and risky.
  - **Folktales**
    - **The Blind Men and the Elephant** (South Asian): curiosity needs multiple perspectives to approach truth.
    - **Anansi and the Pot of Wisdom** (West African/Ashanti): curiosity and knowledge spread; cannot be hoarded.
    - **The Three Questions** (widely circulated): curiosity focused on “what matters most” (right time/person/action).
    - **The Clever Rabbit and the Lion** (Panchatantra tradition): curiosity + observation enable clever solutions.
    - **Stone Soup** (European): curious openness gets people to test an idea and discover shared abundance.
  - **Fables**
    - **The Crow and the Pitcher** (Aesop): curiosity as experimentation—trying possibilities until something works.
    - **The Fox and the Goat** (Aesop): curiosity without foresight can trap you; ask “and then what?”
    - **The Lion and the Mouse** (Aesop): curiosity about the “small” reveals unexpected value.
    - **The Ant and the Grasshopper** (Aesop): curiosity about consequences supports planning and learning.
    - **The Boy Who Cried Wolf** (Aesop): curiosity about “is it true?” protects trust and community.
    - **The Dog and His Reflection** (Aesop): curiosity mixed with greed/illusion—test perceptions before acting.
  - **Parables**
    - **The Mustard Seed**: curiosity about small beginnings—how little things become transformative.
    - **The Sower**: curiosity about causes—why the same “seed” yields different outcomes.
    - **The Talents**: curiosity applied—exploring and developing what you’ve been given rather than burying it.
    - **The Lost Sheep**: curiosity as seeking—going after what’s missing to restore wholeness.
    - **The Poisoned Arrow** (Buddhist): disciplined curiosity—focus on questions that heal rather than distract.
  - **Fairy Tales**
    - **Alice’s Adventures in Wonderland**: curiosity as the doorway into discovery, absurdity, and growth.
    - **Bluebeard**: forbidden-curiosity tale—warns that curiosity needs safety and wisdom.
    - **Goldilocks and the Three Bears**: curiosity explores boundaries; teaches respect and consequences.
    - **Jack and the Beanstalk**: curiosity-driven risk leads to big discovery (and big danger).
    - **The Little Mermaid**: curiosity about another world pushes transformation and sacrifice.
    - **Beauty and the Beast**: curiosity that looks deeper than appearances reveals truth.

##### Open-Mindedness

ID: HUMANITY.ELEMENTS.VALUES.OPENNESS
TAGS: [[HUMANITY:OPENNESS]]

Willingness to consider new ideas, perspectives, and possibilities without immediate judgment or rejection. It involves being receptive to different thoughts and experiences, allowing for growth and understanding. It involves humility, flexibility, and a readiness to change one's views when presented with new information. Open-mindedness fosters dialogue, personal growth, and a deeper understanding of others.

- **Included by Value**: [[HUMANITY:THINKING]]
- **Includes Values**: None
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #4FC3F7
    - #F78550
    - #50F785
    - #F750C2
    - #C2F750
    - #8550F7
  - **Symbols**
    - **Open door**: openness to new possibilities; “letting something in” instead of shutting it out.
    - **Open hands / open palm**: receptivity and non-defensiveness; willingness to receive or reconsider.
    - **Two speech bubbles / dialogue icon**: listening + exchange; open-mindedness grows through conversation.
    - **Overlapping circles (Venn diagram)**: finding shared ground; integrating multiple viewpoints.
    - **Prism / refracted light**: one “beam” becoming many angles; perspective-taking and nuance.
    - **Compass / multi-direction arrows**: considering more than one direction before choosing.
    - **Globe / diverse faces circle**: exposure to different cultures and lived experiences reduces narrow judgments.
- **Literary Elements**
  - **Proverbs**
    - “**Don’t judge a book by its cover.**” — suspend snap judgments; look deeper.
    - “**There are two sides to every story.**” — invites perspective-taking before concluding.
    - “**Walk a mile in someone else’s shoes.**” — empathy as a pathway to openness.
    - “**Live and let live.**” — tolerance for differences that don’t harm others.
    - “**Keep an open mind.**” — direct cultural shorthand for receptivity.
    - “**When in Rome, do as the Romans do.**” — humility and adaptability in unfamiliar contexts.
    - “**Listen more than you speak.**” — openness begins with attention and restraint.
  - **Quotations**
    - “**He who knows only his own side of the case knows little of that…**” — *John Stuart Mill, On Liberty*.
    - “**The test of a first-rate intelligence is the ability to hold two opposed ideas in the mind at the same time…**” — *F. Scott Fitzgerald*.
    - “**Travel is fatal to prejudice, bigotry, and narrow-mindedness…**” — *Mark Twain, The Innocents Abroad*.
    - “**…keep an open mind, but not so open that your brains fall out.**” — attribution varies.
    - “**When the facts change, I change my mind. What do you do, sir?**” — often attributed to *Keynes*, but the sourcing is contested.
    - “**Be curious, not judgmental.**” — popular modern line.
    - “**…the mind is like a parachute… it only functions when it is open.**” — early print tracing exists; attribution varies (metaphor for openness enabling learning).
  - **Myths**
    - **Baucis and Philemon** (Greek): welcoming “strangers” without contempt; hospitality as open-hearted openness.
    - **Odin as a Wanderer** (Norse motif): wisdom comes through meeting the unfamiliar; don’t dismiss the unknown traveler.
    - **The Judgment of Solomon** (biblical tradition): suspending assumptions; seeking truth through deeper understanding.
    - **Athena and Arachne** (Greek): skill without humility hardens into arrogance; openness includes teachability.
    - **Cassandra** (Greek): groups reject uncomfortable information; warns against closed-minded denial.
  - **Folktales**
    - **The Blind Men and the Elephant** (South Asian): each person has a partial truth; openness integrates perspectives.
    - **Stone Soup** (European): openness to a strange idea creates shared benefit.
    - **The Empty Pot** (Chinese): openness to truth over image; integrity beats performative certainty.
    - **Anansi and the Pot of Wisdom** (West African/Ashanti): wisdom can’t be hoarded; it spreads through community.
    - **Nasreddin Hodja tales** (Middle Eastern): humor exposes rigid thinking; invites flexibility and self-awareness.
    - **The Three Questions** (widely circulated): openness to what matters now—right time, right person, right action.
  - **Fables**
    - **The North Wind and the Sun** (Aesop): alternative approaches can work better than force; be open to different methods.
    - **The Lion and the Mouse** (Aesop): don’t dismiss the “small”; openness sees value everywhere.
    - **The Fox and the Grapes** (Aesop): rationalization closes the mind; openness admits disappointment honestly.
    - **The Tortoise and the Hare** (Aesop): overconfidence = mental rigidity; steady learning wins.
    - **The Crow and the Pitcher** (Aesop): experimentation and flexibility; trying new angles.
    - **The Traveler and the Bear** (Aesop variants): reassess “friends” and assumptions under stress; reality-check beliefs.
  - **Parables**
    - **The Good Samaritan**: expands moral concern beyond tribe; openness to the “other.”
    - **The Pharisee and the Tax Collector**: humility over self-certainty; openness begins with self-critique.
    - **The Prodigal Son**: openness to repentance and restored relationship; mercy over rigid condemnation.
    - **The Lost Sheep**: openness to the overlooked/outcast; valuing the one who “doesn’t fit.”
    - **The Workers in the Vineyard**: challenges rigid “fairness” instincts; invites broader perspective on generosity.
    - **The Two Sons**: openness is doing truth, not just claiming it; willingness to change course.
  - **Fairy Tales**
    - **Beauty and the Beast**: seeing beyond appearances; openness to unexpected goodness.
    - **The Ugly Duckling** (Andersen): reframes identity and belonging; openness corrects premature judgments.
    - **The Emperor’s New Clothes**: groupthink closes minds; openness to reality requires courage to notice/say truth.
    - **The Frog Prince**: transformation and reappraisal; what seems repulsive may be worthy.
    - **Alice’s Adventures in Wonderland**: practicing flexibility in a world that breaks expectations; curiosity over rigidity.
    - **Goldilocks and the Three Bears**: exploration meets boundaries; openness paired with respect.
