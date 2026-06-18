# Humanity's Fallibility — Information-Following Large Language Model Knowledge (*if-llm-humanity-fallibility.md*)

## File Header

- **Name:** Humanity's Fallibility — Information-Following Large Language Model Knowledge (*if-llm-humanity-fallibility.md*)
- **Version:** 2026-06-17 04:26 UTC by [Lance Hegland](lance.hegland@gmail.com)
- **Last Reviewed:** 2026-06-15 04:56 UTC by [Lance Hegland](lance.hegland@gmail.com)
- **Owner:** [Lance Hegland](lance.hegland@gmail.com)

- **Purpose:** Empower an IF-LLM to help an average U.S. adult understand why humans make harmful choices, hold biased beliefs, and treat others unfairly — including themselves — and to apply that understanding without judgment to improve sensemaking, decision quality, and interpersonal fairness.
- **Audience:** Average, diverse people in the United States of America today.
- **Features**
  - Six entries covering human fallibility from the underlying condition through to its behavioral expression: Fallibility → Temptations → Consequences of Temptations → Stereotypes → Prejudices → Discrimination.
  - Structured cognitive (Stereotypes) → affective (Prejudices) → behavioral (Discrimination) bias sequence to support precise IF-LLM retrieval.
  - Observed-pattern framing throughout — not moral judgments — with explicit acknowledgment that outcomes are shaped by diverse factors (environment, disability, trauma, discrimination, access).
  - Ontological relationships link fallibility patterns to [[HUMANITY:OODA]], [[HUMANITY:NEEDS]], [[HUMANITY:VALUES]], and [[HUMANITY:CONCERNS]].
  - Concept Disambiguation section guides IF-LLM selection when entries partially overlap (especially Fallibility vs. Temptations vs. Consequences; Stereotypes vs. Prejudices vs. Discrimination).
  - IF/THEN decision rules support structured retrieval workflows per entry.
- **Scope**
  - **Covers:** Human fallibility as a universal condition; common behavioral temptation patterns and their consequences; the cognitive-affective-behavioral bias sequence (Stereotypes → Prejudices → Discrimination); observed patterns across diverse U.S. and global communities throughout history.
  - **Out of Scope:** Clinical diagnosis or treatment of specific mental health or behavioral conditions; legal assessments of discrimination or hate crimes; political advocacy or partisan attribution of fallibility patterns; moral rulings about individuals; ranking of temptations by severity.
- **Use Cases**
  - **Supported:** Helping users understand why people (including themselves) make harmful choices or hold biased views; supporting conflict de-escalation and sensemaking; grounding discussions of societal concerns in shared human fallibility; improving decision quality through awareness of bias patterns; promoting fairness and self-compassion in difficult situations.
  - **Not Supported:** Not a clinical assessment tool; not for diagnosing individuals; not for generating legal determinations; not suitable for partisan blame attribution; not a substitute for professional ethics training, legal counsel, or mental health support (see [[HUMANITY:COPING]] for urgent and professional resources).

- **Dependencies (Required):** `if-llm-system-policies-processing.md`, `if-llm-humanity-index.md`, `if-llm-humanity.md`, `if-llm-humanity-experts.md`, `if-llm-humanity-narm.md`, `if-llm-humanity-ooda.md`, `if-llm-humanity-values.md`, `if-llm-humanity-values-1.md`, `if-llm-humanity-values-2.md`, `if-llm-humanity-values-3.md`, `if-llm-humanity-values-4.md`, `if-llm-humanity-values-5.md`
- **Stability:** Stable. Core entries, tag assignments, and namespace rules are intended to remain consistent across sessions. Silent reinterpretation of entries, tag reassignment, or scope expansion without an explicit Changelog entry is prohibited.
- **Known Gaps / Limitations**
  - Temptations list is structured by observable behavioral pattern, not by underlying psychological mechanism; users seeking mechanism-level explanations should also cite [[HUMANITY:REASONING_EXPERTS]] (Behavioral Scientists, Cognitive Psychologists, Decision Scientists).
  - Consequences of Temptations (HUMANITY.ELEMENTS.FALLIBILITY.TEMPTATIONS.CONSEQUENCES) is positioned structurally under Fallibility in the heading hierarchy but is logically a sibling of Temptations, not its child. Use [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] for retrieval regardless of heading depth.
  - Temptation patterns listed are not exhaustive; cultural, contextual, and individual variation is significant and these descriptions are not moral verdicts.
  - This file does not address the spectrum of severity within each temptation or consequence; context and degree matter significantly in real-world applications.
  - No entry currently addresses institutional or structural forms of fallibility separately from individual-level patterns; this is a gap for future consideration.

- **Changelog**
  - 2026-06-17 07:50 UTC by [Lance Hegland](lance.hegland@gmail.com): Updated `Index` > `Domain Knowledge Index` to reflect split of `if-llm-humanity-values-4.md` containing 10 entries into two separate files as follows:
    - `if-llm-humanity-values-4.md` contains the 5 entries  `Justice` through `Persistence`
    - `if-llm-humanity-values-5.md` contains the 5 entries  `Courage` through `Hope`
  - 2026-06-17 04:26 UTC by [Lance Hegland](lance.hegland@gmail.com): Updated `Index` > `Domain Knowledge Index` to reflect split of `if-llm-humanity-values.md` containing 31 entries into four separate files with roughly 550 lines each as follows:
    - `if-llm-humanity-values-1.md` contains the 7 entries `Values` through `Open-Mindedness`
    - `if-llm-humanity-values-2.md` contains the 7 entries  `Perspective` through `Humility`
    - `if-llm-humanity-values-3.md` contains the 7 entries  `Prudence` through `Humor`
    - `if-llm-humanity-values-4.md` contains the 10 entries  `Justice` through `Hope`
  - 2026-06-15 04:56 UTC by [Lance Hegland](lance.hegland@gmail.com): Replaced all TBD fields in File Header (Purpose, Features, Scope, Use Cases, Known Gaps/Limitations); added Concept Disambiguation section to Index; added Examples, Boundaries/Scope, Decision Rules, and Ontological Relationships to all six entries (Fallibility, Temptations, Consequences of Temptations, Stereotypes, Prejudices, Discrimination); updated Changelog with this entry.
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
- `if-llm-humanity-ooda.md`
  - Processing (OODA: Observe → Orient → Decide →  Act) → HUMANITY.ELEMENTS.OODA → [[HUMANITY:OODA]]
  - Observe → HUMANITY.ELEMENTS.OODA.OBSERVE → [[HUMANITY:OBSERVE]]
  - Senses → HUMANITY.ELEMENTS.OODA.OBSERVE.SENSES → [[HUMANITY:SENSES]]
  - Orient → HUMANITY.ELEMENTS.OODA.ORIENT → [[HUMANITY:ORIENT]]
  - Decide → HUMANITY.ELEMENTS.OODA.DECIDE →  [[HUMANITY:DECIDE]]
  - Act → HUMANITY.ELEMENTS.OODA.ACT → [[HUMANITY:ACT]]
- `if-llm-humanity-narm.md`
  - Needs → HUMANITY.ELEMENTS.NEEDS → [[HUMANITY:NEEDS]]
  - Consequences of Unmet Needs → HUMANITY.ELEMENTS.CONSEQUENCES_UNMET_NEEDS → [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]
  - Activities → HUMANITY.ELEMENTS.ACTIVITIES → [[HUMANITY:ACTIVITIES]]
  - Activities of Daily Living (ADLs) → HUMANITY.ELEMENTS.ACTIVITIES.ADLS → [[HUMANITY:ADLS]]
  - Instrumental Activities of Daily Living (IADLs) → HUMANITY.ELEMENTS.ACTIVITIES.IADLS → [[HUMANITY:IADLS]]
  - Limited Available Resources → HUMANITY.ELEMENTS.RESOURCES → [[HUMANITY:RESOURCES]]
  - Capabilities → HUMANITY.ELEMENTS.RESOURCES.CAPABILITIES → [[HUMANITY:CAPABILITIES]]
  - Motivators → HUMANITY.ELEMENTS.MOTIVATORS → [[HUMANITY:MOTIVATORS]]
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
  - Courage → HUMANITY.ELEMENTS.VALUES.COURAGE → [[HUMANITY:COURAGE]]
  - Bravery → HUMANITY.ELEMENTS.VALUES.BRAVERY → [[HUMANITY:BRAVERY]]
  - Integrity → HUMANITY.ELEMENTS.VALUES.INTEGRITY → [[HUMANITY:INTEGRITY]]
  - Vitality → HUMANITY.ELEMENTS.VALUES.VITALITY → [[HUMANITY:VITALITY]]
  - Hope → HUMANITY.ELEMENTS.VALUES.HOPE → [[HUMANITY:HOPE]]

### Concept Disambiguation

Use these notes to select between partially overlapping concepts for precise IF-LLM retrieval and reasoning.

- **[[HUMANITY:FALLIBILITY]] vs. [[HUMANITY:TEMPTATIONS]] vs. [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]**
  - Use `[[HUMANITY:FALLIBILITY]]` when the focus is on the *human condition* — being inherently limited, imperfect, and prone to error (the "why we struggle" lens). Produce: a compassionate framing of human limitation as universal and non-shameful.
  - Use `[[HUMANITY:TEMPTATIONS]]` when the focus is on the *specific impulse or behavioral pattern* that increases harm risk — e.g., greed, avoidance, tribal thinking (the "what we are pulled toward" lens). Produce: pattern identification for sensemaking or harm-prevention.
  - Use `[[HUMANITY:CONSEQUENCES_TEMPTATIONS]]` when the focus is on *outcomes already produced* by following temptations — broken trust, addiction, exploitation (the "what results" lens). Produce: consequence mapping to inform decision-making or help users recognize harm patterns.
  - Note: All three usually appear together; cite the one that most directly answers the user's question, then reference the others as context.

- **[[HUMANITY:STEREOTYPES]] vs. [[HUMANITY:PREJUDICES]] vs. [[HUMANITY:DISCRIMINATION]]**
  - Use `[[HUMANITY:STEREOTYPES]]` when the focus is on *cognitive generalizations* — oversimplified beliefs about groups (the "what someone thinks" lens). Produce: awareness of how group assumptions form and distort perception.
  - Use `[[HUMANITY:PREJUDICES]]` when the focus is on *affective pre-judgments* — feelings (dislike, fear, distrust) toward groups based on stereotypes (the "what someone feels" lens). Produce: awareness of how attitudes shape motivation and willingness to help.
  - Use `[[HUMANITY:DISCRIMINATION]]` when the focus is on *behavioral inequity* — unequal treatment in action (the "what someone does" lens). Produce: identification of harm-producing behaviors and their real-world effects on [[HUMANITY:NEEDS]] satisfaction.
  - Note: The three often chain (Stereotype → Prejudice → Discrimination) but are separable. Someone can hold stereotypes and prejudices without discriminating; and someone can discriminate without personal prejudice (due to rules, incentives, or social pressure).

- **[[HUMANITY:TEMPTATIONS]] vs. [[HUMANITY:MOTIVATORS]]**
  - Use `[[HUMANITY:TEMPTATIONS]]` when the focus is on *behavioral pulls that increase risk of harm* to self or others — patterns that, if followed routinely, undermine [[HUMANITY:NEEDS]] satisfaction.
  - Use `[[HUMANITY:MOTIVATORS]]` when the focus is on *drives that support efficient need satisfaction* — energizing reasons to act that, on balance, help rather than harm.
  - Note: Motivators can be hijacked by temptations (e.g., the healthy motivator "safety" can manifest as the temptation "hoarding"); context determines whether a drive is functioning as a motivator or a temptation.

- **[[HUMANITY:CONSEQUENCES_TEMPTATIONS]] vs. [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]**
  - Use `[[HUMANITY:CONSEQUENCES_TEMPTATIONS]]` when outcomes result primarily from *making harmful behavioral choices* — e.g., broken trust from dishonesty, harm from impulsive aggression.
  - Use `[[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]` when outcomes result primarily from *chronic deprivation* — e.g., anxiety from prolonged financial insecurity, withdrawal from persistent social exclusion.
  - Note: The two frequently interact; temptations can cause unmet needs (addiction → financial ruin → health deprivation), and unmet needs can fuel temptations (food insecurity → theft). When both apply, cite both.

### Local Knowledge Index

The following is a list of this file's common topic references mapped to canonical handles.

- Fallibility → HUMANITY.ELEMENTS.FALLIBILITY → [[HUMANITY:FALLIBILITY]]
- Temptations → HUMANITY.ELEMENTS.FALLIBILITY.TEMPTATIONS → [[HUMANITY:TEMPTATIONS]]
- Consequences of Temptations → HUMANITY.ELEMENTS.FALLIBILITY.TEMPTATIONS.CONSEQUENCES → [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]
- Stereotypes → HUMANITY.ELEMENTS.FALLIBILITY.STEREOTYPES → [[HUMANITY:STEREOTYPES]]
- Prejudices → HUMANITY.ELEMENTS.FALLIBILITY.PREJUDICES → [[HUMANITY:PREJUDICES]]
- Discrimination → HUMANITY.ELEMENTS.FALLIBILITY.DISCRIMINATION → [[HUMANITY:DISCRIMINATION]]

## Humanity

### Elements

#### Fallibility

ID: HUMANITY.ELEMENTS.FALLIBILITY
TAGS: [[HUMANITY:FALLIBILITY]]

Humans are inherently limited and fallible—we have [[HUMANITY:RESOURCES]], and we will sometimes miss commitments, make mistakes, or fall short. A healthier expectation is not "perfection," but [[HUMANITY:HUMILITY]] (recognizing our limitations and being willing to acknowledge mistakes) and [[HUMANITY:INTEGRITY]] (keeping promises small enough to keep, and repairing quickly when we miss—acknowledge, make amends, and adjust the system). When another person makes a mistake, pause and practice [[HUMANITY:HUMILITY]] (remember I'm fallible too), [[HUMANITY:MERCY]] (respond with [[HUMANITY:COMPASSION]], not punishment), [[HUMANITY:GRATITUDE]] (notice their effort and intention), [[HUMANITY:HUMOR]] (keep things human plus defuse blame and shame), [[HUMANITY:FAIRNESS]] (judge with the same standard you'd want applied to you), and [[HUMANITY:LEADERSHIP]] (help repair, learn, and move forward—together).

- **Examples**
  - **When a user is harsh on themselves for a mistake:** Cite [[HUMANITY:FALLIBILITY]] to normalize the experience and reframe the expectation from perfection to [[HUMANITY:HUMILITY]] and [[HUMANITY:INTEGRITY]]-based repair.
  - **When a user is frustrated with someone else's behavior:** Cite [[HUMANITY:FALLIBILITY]] to introduce the "they're human too" frame before exploring [[HUMANITY:TEMPTATIONS]] or [[HUMANITY:STEREOTYPES]] as more specific explanations.
  - **When explaining why people make the same mistakes repeatedly:** Cite [[HUMANITY:FALLIBILITY]] as the structural backdrop, then cite [[HUMANITY:TEMPTATIONS]] for the specific pattern and [[HUMANITY:OODA]] for how the loop breaks down.

- **Boundaries / Scope**
  - **Includes:** The universal human condition of being limited, error-prone, and vulnerable to harmful patterns; the emotional reality of fallibility (shame, self-criticism, blame of others); the compassionate framework for responding to mistakes in self and others.
  - **Excludes:** Specific behavioral patterns (see [[HUMANITY:TEMPTATIONS]]); their consequences (see [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]); cognitive-affective-behavioral bias sequence (see [[HUMANITY:STEREOTYPES]], [[HUMANITY:PREJUDICES]], [[HUMANITY:DISCRIMINATION]]); clinical mental health conditions.
  - **Primary purpose:** Provide IF-LLM with a compassionate, non-judgmental framing of human imperfection as the starting point for any conversation about why people struggle, make harmful choices, or hurt each other.

- **Decision Rules (IF/THEN)**
  - **IF** a user is criticizing themselves or others harshly for a mistake, **THEN** cite [[HUMANITY:FALLIBILITY]] first to normalize the experience, before exploring more specific patterns.
  - **IF** a user asks "why do people do such awful things?", **THEN** start with [[HUMANITY:FALLIBILITY]] (universal condition), then move to [[HUMANITY:TEMPTATIONS]] (specific patterns) and [[HUMANITY:LESSONS]] (historical evidence).
  - **IF** a user needs to repair a relationship after a failure, **THEN** cite [[HUMANITY:FALLIBILITY]] for the normalizing frame plus [[HUMANITY:INTEGRITY]] and [[HUMANITY:MERCY]] for the repair approach.
  - **IF** the question is about a specific harmful behavioral pull (greed, avoidance, tribalism), **THEN** move to [[HUMANITY:TEMPTATIONS]]; reserve [[HUMANITY:FALLIBILITY]] for the broader "why are we like this at all?" level.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:LESSONS]] (fallibility patterns recur across history and are documented in lessons); [[HUMANITY:OODA]] (fallibility introduces errors at every step of the loop); [[HUMANITY:TEMPTATIONS]] (temptations are the specific behavioral expression of fallibility); [[HUMANITY:CONCERNS]] (societal concerns often recur because fallibility is universal); [[HUMANITY:MISSION]] (the Mission explicitly acknowledges fallibility — "best" not "perfect")
  - **Produces:** [[HUMANITY:TEMPTATIONS]] (the specific pulls that emerge from our fallible condition); [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (the outcomes when temptations are followed); [[HUMANITY:STEREOTYPES]], [[HUMANITY:PREJUDICES]], [[HUMANITY:DISCRIMINATION]] (bias patterns as fallibility expressions in social perception)
  - **Reduced by:** [[HUMANITY:HUMILITY]] (recognition of limits); [[HUMANITY:WISDOM]] (learning from patterns); [[HUMANITY:REGULATION]] (self-management); [[HUMANITY:INTERDEPENDENCE]] (community correction and support); [[HUMANITY:LESSONS]] (guidance from historical patterns)
  - **Vulnerable to:** Shame spirals that increase avoidance and worsen outcomes; denial patterns that prevent learning; blame displacement onto others

##### Temptations

ID: HUMANITY.ELEMENTS.FALLIBILITY.TEMPTATIONS
TAGS: [[HUMANITY:TEMPTATIONS]]

Common temptations of [[HUMANITY:ROOT]] observed across our many, diverse communities throughout our history. Likely cause harm and risk to ability to efficiently and consistently satisfy [[HUMANITY:NEEDS]] for ourselves and and others. These are observed patterns, not moral judgments. Motivations are shaped by many, diverse factors (e.g., environment, disability, trauma, discrimination, access).

- Power and Control: Seeking dominance or authority at the expense of others.
  - Hoarding Limited Available Resources at others' expense.
  - Corruption: Using authority or influence for personal gain at others' expense (e.g., embezzlement, nepotism, bribery).
  - Manipulating others for personal gain.
  - Exploiting others to accumulate more Limited Available Resources, especially power, finances, relationships.
  - Bullying or abusive behavior.
  - Wrath: Acting out of uncontrolled anger or vengeance (e.g., verbal abuse, bullying, road rage, physical violence).
- Greed: Pursuing excessive accumulation of resources, causing prioritization of money, possessions, or power over ethics and relationships (e.g. fraud, exploitation).
- Tribal Thinking: Prioritizing group loyalty over broader ethical considerations.
  - Conformity: Succumbing to peer pressure or societal norms despite personal harm (e.g., smoking, excessive drinking, recreational drug use, unethical workplace behavior).
  - Cowardice: Avoiding necessary but difficult actions due to fear (e.g., staying silent about injustice, refusing to take responsibility).
  - Discriminating against others based on group differences.
  - Blindly following harmful ideologies or leaders.
- Immediate Gratification: Choosing short-term pleasure over long-term well-being and consequences.
  - Apathy: Ignoring the needs or suffering of others out of indifference (e.g., ignoring societal issues, littering, refusing to help someone in distress).
  - Dishonesty: Misleading others to gain advantage or avoid consequences. (e.g., lying, cheating, plagiarism).
  - Lust: Pursuing short-term physical gratification at the expense of long-term relationships, health, or well-being (e.g., extramarital affairs, excessive consumption of explicit content).
  - Gluttony: Overconsumption of Limited Available Resources (e.g. hydration, nutrition, relationships, finances, and experiences), often to cope with stress.
  - Addiction: Substance abuse or compulsive behaviors driven by chemical or psychological cravings (e.g., drug or alcohol dependency, gambling, excessive gaming).
  - Escapism: Avoiding responsibilities or problems by indulging in distractions.
- Risky Thrills: Engaging in dangerous activities for excitement or adventure.
  - Reckless driving or extreme sports without preparation.
  - Gambling excessively.
- Social Comparison: Comparing oneself to others, often leading to negative outcomes.
  - Envy: Acting destructively due to resentment of others' success or possessions (e.g., sabotage, spreading rumors, theft).
  - Pride: Overestimating self-worth, leading to arrogance and dismissal of others' needs (e.g., refusal to accept help, taking unnecessary risks, belittling others).
  - Overspending to "keep up with others."
  - Pursuing risky behaviors to gain social approval.
- Overcommitment: Taking on too many responsibilities, leading to stress or neglect of priorities.
  - Saying "yes" to too many obligations.
  - Sacrificing health or family for work demands.
- Confirmation Bias: Seeking information that aligns with existing beliefs while ignoring contradictory evidence.
  - Believing and sharing misinformation.
  - Resisting beneficial feedback or advice.
- Avoidance of Discomfort: Choosing to escape or numb uncomfortable emotions or situations.
  - Impatience: Making rash decisions to avoid delay or discomfort (e.g., skipping safety procedures, abandoning commitments).
  - Procrastinating important tasks.
  - Avoiding conflict resolution, leading to unresolved issues.

- **Examples**
  - **When a user describes impulsive spending or debt:** Cite [[HUMANITY:TEMPTATIONS]]: Immediate Gratification (Gluttony, Social Comparison) as the likely pattern; link to [[HUMANITY:RESOURCES]] (financial capability) and [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (Greed and Materialism) for context.
  - **When a user is frustrated that a colleague "never admits mistakes":** Cite [[HUMANITY:TEMPTATIONS]]: Pride (Social Comparison) and Avoidance of Discomfort as likely patterns; note that [[HUMANITY:FALLIBILITY]] and [[HUMANITY:HUMILITY]] are the counterweights.
  - **When a user observes political echo chambers or polarization:** Cite [[HUMANITY:TEMPTATIONS]]: Tribal Thinking (Conformity, Confirmation Bias) as the structural driver; link to [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (Prejudice and Discrimination, Broken Trust).
  - **When a user is struggling to maintain a commitment:** Cite [[HUMANITY:TEMPTATIONS]]: Avoidance of Discomfort or Immediate Gratification as likely competing pulls; then reference [[HUMANITY:PERSISTENCE]], [[HUMANITY:REGULATION]], and [[HUMANITY:INTEGRITY]] as countermeasures.

- **Boundaries / Scope**
  - **Includes:** Observable behavioral patterns that, when routinely chosen, increase risk of harm to self or others and reduce ability to satisfy [[HUMANITY:NEEDS]]; organized by pattern category (Power, Greed, Tribal, Gratification, etc.).
  - **Excludes:** Clinical diagnosis of specific conditions (see [[HUMANITY:REASONING_EXPERTS]]: Behavioral Scientists, Cognitive Psychologists); the consequences of these patterns (see [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]); legal or criminal determinations; moral verdicts about individual character.
  - **Primary purpose:** Enable IF-LLM to name the specific behavioral pull at work in a situation — not to judge it, but to make it visible and workable — so the user can make more intentional choices.

- **Decision Rules (IF/THEN)**
  - **IF** a user asks why someone (including themselves) keeps doing something harmful despite knowing better, **THEN** cite [[HUMANITY:TEMPTATIONS]] for the specific pattern and [[HUMANITY:FALLIBILITY]] for the broader condition.
  - **IF** a user describes societal problems (polarization, corruption, inequality), **THEN** identify the most relevant temptation patterns (Tribal Thinking, Power and Control, Greed) and connect to [[HUMANITY:CONCERNS]] and [[HUMANITY:CONSEQUENCES_TEMPTATIONS]].
  - **IF** a user is working on behavior change, **THEN** cite the specific temptation pattern to name it, then pivot to the countervailing [[HUMANITY:VALUES]] (e.g., Immediate Gratification → [[HUMANITY:PRUDENCE]], [[HUMANITY:REGULATION]]; Tribal Thinking → [[HUMANITY:PERSPECTIVE]], [[HUMANITY:OPENNESS]]).
  - **IF** the focus is on *outcomes already caused* by temptations rather than the temptation patterns themselves, **THEN** move to [[HUMANITY:CONSEQUENCES_TEMPTATIONS]].
  - **IF** a user asks about a specific individual's internal motivations rather than behavioral patterns, **THEN** note this file addresses patterns, not individual psychological profiles, and recommend [[HUMANITY:REASONING_EXPERTS]] for deeper analysis.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:FALLIBILITY]] (temptations are the behavioral expression of fallibility); [[HUMANITY:OODA]] (temptations most often disrupt [[HUMANITY:ORIENT]] and [[HUMANITY:DECIDE]]); [[HUMANITY:CONCERNS]] (many societal concerns are driven by temptation patterns at scale); [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (the outcomes produced when temptations are routinely followed); [[HUMANITY:MOTIVATORS]] (motivators can be hijacked to fuel temptations when [[HUMANITY:REGULATION]] is low)
  - **Produces:** [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (when temptations are routinely followed); [[HUMANITY:STEREOTYPES]], [[HUMANITY:PREJUDICES]], and [[HUMANITY:DISCRIMINATION]] (through Tribal Thinking and Social Comparison); [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (when temptations consume [[HUMANITY:RESOURCES]] needed for need satisfaction)
  - **Reduced by:** [[HUMANITY:REGULATION]] (self-management); [[HUMANITY:PRUDENCE]] (consequence awareness); [[HUMANITY:HUMILITY]] (recognition of vulnerability); [[HUMANITY:WISDOM]] (pattern awareness from [[HUMANITY:LESSONS]]); [[HUMANITY:INTERDEPENDENCE]] (accountability and community support)
  - **Amplified by:** Low [[HUMANITY:RESOURCES]] (especially energy, time, financial stress); strong social pressure; unmet [[HUMANITY:NEEDS]]; environments designed to exploit specific temptation patterns

#### Consequences of Temptations

ID: HUMANITY.ELEMENTS.FALLIBILITY.TEMPTATIONS.CONSEQUENCES
TAGS: [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]

Common consequences of routinely choosing [[HUMANITY:TEMPTATIONS]] (instead of intentionally and consistently practicing [[HUMANITY:VALUES]]). [[HUMANITY:TEMPTATIONS]] often contribute to reduced [[HUMANITY:REGULATION]] and [[HUMANITY:PERSPECTIVE]], which often contribute to the emergence of the outcomes listed below. These are observed patterns, not moral judgments. Outcomes are shaped by many, diverse factors (e.g., environment, disability, trauma, discrimination, access).

- Stagnation and Underachievement
  - Avoidance of Growth
  - Failure to Take Risks
- Despair and Loss of Meaning
  - Existential Crises
  - Moral Confusion
- Moral and Ethical Compromise
  - Moral Hypocrisy
  - Moral Drift
- Self-Destructive Behaviors
  - Neglect of Basic Needs
  - Risk-Taking and Recklessness
- Inflexibility and Rigidity
  - Resistance to Change
  - Over-Control and Micromanagement
- Selfishness and Narcissism
  - Neglect of Others' Needs
  - Excessive Focus on Self-Image
- Prejudice and Discrimination
  - Unconscious Bias
  - Bigotry and Intolerance
- Dishonesty and Deception
  - Lying and Cheating
  - Fraud and Manipulation
- Emotional Harm to Others
  - Neglect and Emotional Manipulation
  - Failure to Show Empathy
- Broken Trust in Relationships
  - Infidelity and Betrayal
  - Commitment Avoidance
- Isolation and Alienation
  - Social Withdrawal
  - Exclusion of Others
- Lack of Accountability
  - Avoidance of Responsibility
  - Blaming Others
- Addiction and Overindulgence
  - Substance Abuse
  - Overindulgence in Hedonistic Activities
- Greed and Materialism
  - Excessive Pursuit of Wealth or Status
  - Workaholism and Neglect of Personal Life
- Environmental Harm
  - Resource Exploitation
  - Neglect of Collective Responsibility
- Exploitation and Manipulation
  - Abuse of Power and Control
  - Exploitation of Vulnerable Populations
- Aggression and Violence
  - Unregulated Anger and Hostility
  - Bullying and Intimidation

- **Examples**
  - **When a user describes a relationship that has broken down over time:** Cite [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]: Broken Trust in Relationships and Lack of Accountability as likely outcomes; link back to [[HUMANITY:TEMPTATIONS]] (e.g., Dishonesty, Avoidance of Discomfort) that likely produced them.
  - **When a user observes rising polarization or public distrust:** Cite [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]: Broken Trust in Relationships, Isolation and Alienation, Prejudice and Discrimination as systemic-level outcomes of Tribal Thinking and Confirmation Bias temptations.
  - **When a user is experiencing burnout or exhaustion:** Cite [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]: Stagnation and Underachievement, Self-Destructive Behaviors (Neglect of Basic Needs) as likely downstream effects of Overcommitment; connect to [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] if health needs are now affected.

- **Boundaries / Scope**
  - **Includes:** Observable outcomes of routinely following temptation patterns — at individual, relational, and societal levels; not exhaustive but representative of the most significant recurring consequence categories.
  - **Excludes:** Consequences of unmet needs not caused by temptations (see [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]); clinical diagnoses; individual case judgments; legal or punitive determinations.
  - **Scope note:** A single temptation pattern often produces multiple consequences across categories; and a single consequence (e.g., Broken Trust) can result from multiple different temptation patterns. The relationship is many-to-many, not one-to-one.
  - **Primary purpose:** Enable IF-LLM to name what has already been produced by temptation patterns — so users can understand what they're dealing with and consider recovery paths ([[HUMANITY:COPING]], [[HUMANITY:VALUES]]).

- **Decision Rules (IF/THEN)**
  - **IF** a user is describing harm that has already occurred (broken trust, isolation, addiction), **THEN** cite [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] to name the outcome pattern; then trace back to the [[HUMANITY:TEMPTATIONS]] that likely produced it.
  - **IF** a user asks "what happens when people keep doing X?", **THEN** cite the relevant [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] category and connect it to [[HUMANITY:CONCERNS]] if the pattern is social/societal.
  - **IF** outcomes involve harm to physical or psychological health or basic functioning, **THEN** also cite [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] — the two often overlap when temptations deplete [[HUMANITY:RESOURCES]] needed for need satisfaction.
  - **IF** a user is asking how to recover or repair, **THEN** cite [[HUMANITY:COPING]] for immediate support and [[HUMANITY:VALUES]] (especially [[HUMANITY:INTEGRITY]], [[HUMANITY:MERCY]], [[HUMANITY:PERSISTENCE]]) for the repair path.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:TEMPTATIONS]] (the behavioral patterns that produce these consequences); [[HUMANITY:FALLIBILITY]] (consequences are evidence of human fallibility operating at scale); [[HUMANITY:CONCERNS]] (many societal concerns are consequences of temptations applied across communities and institutions); [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (these two consequence sets frequently interact and compound)
  - **Produced by:** [[HUMANITY:TEMPTATIONS]] (routinely following harmful behavioral patterns); [[HUMANITY:STEREOTYPES]], [[HUMANITY:PREJUDICES]], and [[HUMANITY:DISCRIMINATION]] (the bias-behavior chain also produces consequences under this entry)
  - **Reduces:** [[HUMANITY:CAPABILITIES]] (consequences deplete resources needed to function); [[HUMANITY:INTERDEPENDENCE]] (consequences often damage trust and community bonds); [[HUMANITY:RESOURCES]] (addiction, exploitation, and neglect consume finite resources); [[HUMANITY:RIGHTS]] (exploitation and discrimination produce rights violations)
  - **Addressed by:** [[HUMANITY:COPING]] (responses to consequences in progress); [[HUMANITY:VALUES]] (practices that interrupt the temptation-consequence cycle); [[HUMANITY:LESSONS]] (historical guidance on recovery and prevention)

##### Stereotypes

ID: HUMANITY.ELEMENTS.FALLIBILITY.STEREOTYPES
TAGS: [[HUMANITY:STEREOTYPES]]

**Stereotypes** are **generalized beliefs** about a group of people (e.g., "people from X are…"). They're *cognitive* (thoughts) and can be positive, negative, or "neutral," but they're often oversimplified and inaccurate. Stereotypes distort expectations. As such, stereotypes are an example of our [[HUMANITY:FALLIBILITY]]. Stereotypes and [[HUMANITY:PREJUDICES]] are often a result of insufficient [[HUMANITY:PERSPECTIVE]] and [[HUMANITY:THINKING]]. Stereotypes usually emerge from [[HUMANITY:TEMPTATIONS]] (e.g., **Tribal Thinking**, **Social Comparison**, **Power and Control**). Stereotypes may be supported by [[HUMANITY:TEMPTATIONS]]'s **Confirmation Bias**. [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (e.g., **Moral and Ethical Compromise**, **Inflexibility and Rigidity**, **Selfishness**) may also help to reinforce stereotypes. A person could hold stereotypes and [[HUMANITY:PREJUDICES]] without acting on them (i.e., without discriminating). However, stereotypes (in partnership with the [[HUMANITY:PREJUDICES]] they inspire) generally create significant risk of harm to "those people" (others) and ourselves during [[HUMANITY:ORIENT]] by impairing our [[HUMANITY:PERSPECTIVE]], [[HUMANITY:THINKING]], [[HUMANITY:COMPASSION]], and ultimately our [[HUMANITY:INTERDEPENDENCE]]. [[HUMANITY:STEREOTYPES]] often contribute to the emergence of [[HUMANITY:PREJUDICES]]. [[HUMANITY:DISCRIMINATION]] often contributes to the emergence and reinforcement of [[HUMANITY:STEREOTYPES]] and [[HUMANITY:PREJUDICES]]. Stereotypes (in partnership with the [[HUMANITY:PREJUDICES]] they inspire) reduce our [[HUMANITY:MOTIVATORS]] and likelihood of using our [[HUMANITY:RESOURCES]] and likelihood of performing [[HUMANITY:ACTIVITIES]] to help satisfy the [[HUMANITY:NEEDS]] of "those people", thereby impairing their ability to avoid [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]], while simultaneously limiting our [[HUMANITY:INTERDEPENDENCE]]. Stereotypes likely impair our consistent and efficient performance of our [[HUMANITY:MISSION]], which impairs our contributions to our [[HUMANITY:VISION]], thereby increasing risks and harms to the [[HUMANITY:RIGHTS]] of ourselves and others. Ultimately, stereotypes typically impair the intentional and consistent practice of many [[HUMANITY:VALUES]] (e.g., [[HUMANITY:THINKING]], [[HUMANITY:PERSPECTIVE]], [[HUMANITY:OPENNESS]], [[HUMANITY:CURIOSITY]], [[HUMANITY:LEARNING]], [[HUMANITY:LOVE]], [[HUMANITY:MERCY]], [[HUMANITY:REGULATION]], [[HUMANITY:PRUDENCE]], [[HUMANITY:HUMILITY]], [[HUMANITY:TEMPERANCE]], [[HUMANITY:HUMOR]], [[HUMANITY:GRATITUDE]], [[HUMANITY:PURPOSE]], [[HUMANITY:FAIRNESS]], [[HUMANITY:JUSTICE]], [[HUMANITY:CITIZENSHIP]], [[HUMANITY:LEADERSHIP]], [[HUMANITY:INTEGRITY]], [[HUMANITY:VITALITY]], [[HUMANITY:TRANSCENDENCE]], [[HUMANITY:COMPASSION]], [[HUMANITY:INTERDEPENDENCE]], [[HUMANITY:WISDOM]]).

- **Examples**
  - **When a user expresses surprise that someone from a specific group behaved "differently than expected":** Cite [[HUMANITY:STEREOTYPES]] as the cognitive framework that set the expectation; explain how it distorts [[HUMANITY:ORIENT]] and ask them to rebuild their model from direct observation.
  - **When explaining why first impressions can be unfair:** Cite [[HUMANITY:STEREOTYPES]] as the cognitive shortcut that generates first impressions about groups, and [[HUMANITY:THINKING]], [[HUMANITY:PERSPECTIVE]], and [[HUMANITY:OPENNESS]] as the values that counteract them.
  - **When a user is frustrated that others are "always like that":** Cite [[HUMANITY:STEREOTYPES]] to name the generalization, then [[HUMANITY:FALLIBILITY]] to normalize its presence, and [[HUMANITY:HUMILITY]] as the value that opens space for re-evaluation.

- **Boundaries / Scope**
  - **Includes:** Oversimplified generalized beliefs about groups (positive, negative, or "neutral"); the cognitive dimension of the bias sequence; how stereotypes form, are reinforced, and distort [[HUMANITY:ORIENT]].
  - **Excludes:** The affective (feelings-based) dimension — see [[HUMANITY:PREJUDICES]]; the behavioral dimension — see [[HUMANITY:DISCRIMINATION]]; clinical implicit bias assessment; specific legal categories of protected groups.
  - **Scope note:** Stereotypes are the *cognitive* entry point of the bias chain. Cite this entry when the focus is on what someone *thinks* or *expects* about a group, not yet what they *feel* (Prejudice) or *do* (Discrimination).
  - **Primary purpose:** Enable IF-LLM to name the cognitive layer of bias as a starting point for promoting [[HUMANITY:THINKING]] and [[HUMANITY:PERSPECTIVE]] without triggering defensiveness.

- **Decision Rules (IF/THEN)**
  - **IF** a user makes a sweeping generalization about a group, **THEN** cite [[HUMANITY:STEREOTYPES]] to name the pattern (without shaming), then invite them to rebuild from direct evidence using [[HUMANITY:THINKING]] and [[HUMANITY:PERSPECTIVE]].
  - **IF** a user asks why people form group generalizations, **THEN** cite [[HUMANITY:STEREOTYPES]] (cognitive shortcut under [[HUMANITY:FALLIBILITY]]) and [[HUMANITY:TEMPTATIONS]] (Tribal Thinking, Confirmation Bias) as the driving patterns.
  - **IF** the focus shifts to how those beliefs make someone feel about a group (dislike, fear, distrust), **THEN** move to [[HUMANITY:PREJUDICES]].
  - **IF** the focus shifts to actual unequal treatment, **THEN** move to [[HUMANITY:DISCRIMINATION]].
  - **IF** addressing stereotypes in an [[HUMANITY:ORIENT]] step, **THEN** apply the bias check: "Would I interpret this the same way if the person were from a different group?"

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:FALLIBILITY]] (stereotypes are a cognitive expression of human fallibility); [[HUMANITY:TEMPTATIONS]] (Tribal Thinking, Social Comparison, Confirmation Bias generate and reinforce stereotypes); [[HUMANITY:ORIENT]] (stereotypes most directly distort this OODA step); [[HUMANITY:PREJUDICES]] (stereotypes often give rise to prejudices); [[HUMANITY:DISCRIMINATION]] (stereotypes, through prejudices, often lead to discrimination)
  - **Produces:** [[HUMANITY:PREJUDICES]] (affective pre-judgments based on stereotyped beliefs); impaired [[HUMANITY:ORIENT]] accuracy; reduced [[HUMANITY:MOTIVATORS]] to help "outgroup" members; indirect [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] for those stereotyped
  - **Reduced by:** [[HUMANITY:THINKING]] (critical analysis of group generalizations); [[HUMANITY:PERSPECTIVE]] (exposure to diverse individual examples); [[HUMANITY:OPENNESS]] (willingness to revise beliefs); [[HUMANITY:HUMILITY]] (recognition of cognitive limits); [[HUMANITY:CURIOSITY]] (genuine interest in individual reality over group label)
  - **Reinforced by:** [[HUMANITY:TEMPTATIONS]] (Confirmation Bias, Tribal Thinking); [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (Inflexibility and Rigidity, Moral and Ethical Compromise); limited contact with outgroup members; media environments that amplify group-difference framing

##### Prejudices

ID: HUMANITY.ELEMENTS.FALLIBILITY.PREJUDICES
TAGS: [[HUMANITY:PREJUDICES]]

**Prejudices** are **pre-judgments or attitudes** (usually negative) toward a person or group, often based on [[HUMANITY:STEREOTYPES]] rather than direct knowledge. They're *affective* (feelings/evaluations), such as dislike, fear, or distrust. Prejudices generally create significant risk of harm to "those people" (others) and ourselves during [[HUMANITY:ORIENT]] by impairing our [[HUMANITY:PERSPECTIVE]], [[HUMANITY:THINKING]], [[HUMANITY:COMPASSION]], and ultimately our [[HUMANITY:INTERDEPENDENCE]]. Prejudices reduce our [[HUMANITY:MOTIVATORS]] and likelihood of using our [[HUMANITY:RESOURCES]] and likelihood of performing [[HUMANITY:ACTIVITIES]] to help satisfy the [[HUMANITY:NEEDS]] of "those people", thereby impairing their ability to avoid [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]], while simultaneously limiting our [[HUMANITY:INTERDEPENDENCE]]. [[HUMANITY:STEREOTYPES]] often contribute to the emergence of prejudices. Prejudices often lead to [[HUMANITY:DISCRIMINATION]]. However, a person could hold [[HUMANITY:STEREOTYPES]] and prejudices without acting on them (i.e., without discriminating). Prejudices impair the intentional and consistent practice of many [[HUMANITY:VALUES]] (e.g., [[HUMANITY:THINKING]], [[HUMANITY:PERSPECTIVE]], [[HUMANITY:OPENNESS]], [[HUMANITY:CURIOSITY]], [[HUMANITY:LEARNING]], [[HUMANITY:LOVE]], [[HUMANITY:MERCY]], [[HUMANITY:REGULATION]], [[HUMANITY:PRUDENCE]], [[HUMANITY:HUMILITY]], [[HUMANITY:TEMPERANCE]], [[HUMANITY:HUMOR]], [[HUMANITY:GRATITUDE]], [[HUMANITY:PURPOSE]], [[HUMANITY:FAIRNESS]], [[HUMANITY:JUSTICE]], [[HUMANITY:CITIZENSHIP]], [[HUMANITY:LEADERSHIP]], [[HUMANITY:INTEGRITY]], [[HUMANITY:VITALITY]], [[HUMANITY:TRANSCENDENCE]], [[HUMANITY:COMPASSION]], [[HUMANITY:INTERDEPENDENCE]], [[HUMANITY:WISDOM]]). Prejudices impair our consistent and efficient performance of our [[HUMANITY:MISSION]], which impairs our contributions to our [[HUMANITY:VISION]], thereby increasing risks and harms to the [[HUMANITY:RIGHTS]] of ourselves and others. [[HUMANITY:DISCRIMINATION]] may help to reinforce prejudices. Prejudices are often a result of insufficient [[HUMANITY:PERSPECTIVE]] and [[HUMANITY:THINKING]]; examples of our [[HUMANITY:FALLIBILITY]]. [[HUMANITY:STEREOTYPES]] and prejudices usually emerge from and are reinforced by [[HUMANITY:TEMPTATIONS]] (e.g., **Social Comparison**, **Tribal Thinking**, **Power and Control**). [[HUMANITY:STEREOTYPES]] and prejudices may be supported by [[HUMANITY:TEMPTATIONS]]'s **Confirmation Bias**. [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (e.g., **Moral and Ethical Compromise**, **Inflexibility and Rigidity**, **Selfishness**) may also help to reinforce [[HUMANITY:STEREOTYPES]] and prejudices.

- **Examples**
  - **When a user admits to feeling uncomfortable around a specific group without knowing why:** Cite [[HUMANITY:PREJUDICES]] as the affective layer — often inherited from [[HUMANITY:STEREOTYPES]] rather than personal experience — and [[HUMANITY:COMPASSION]] and [[HUMANITY:OPENNESS]] as the values that can soften and update it over time.
  - **When a user observes that someone "just doesn't like" a certain group:** Cite [[HUMANITY:PREJUDICES]] as the felt disposition; note it may or may not lead to [[HUMANITY:DISCRIMINATION]] depending on context and [[HUMANITY:REGULATION]].
  - **When exploring why bias persists even when people know it's wrong:** Cite the interaction of [[HUMANITY:STEREOTYPES]] (cognitive) and [[HUMANITY:PREJUDICES]] (affective) with [[HUMANITY:TEMPTATIONS]] (Confirmation Bias) as a self-reinforcing system that requires deliberate [[HUMANITY:THINKING]], [[HUMANITY:PERSPECTIVE]], and [[HUMANITY:REGULATION]] to interrupt.

- **Boundaries / Scope**
  - **Includes:** Pre-judgments and negative attitudes (dislike, fear, distrust) toward individuals based on group membership; the affective (emotional/evaluative) dimension of the bias sequence; the role of stereotypes in generating prejudicial attitudes.
  - **Excludes:** The cognitive dimension (oversimplified beliefs) — see [[HUMANITY:STEREOTYPES]]; the behavioral dimension (unequal treatment) — see [[HUMANITY:DISCRIMINATION]]; clinical assessment of phobias or disorders; legal determinations.
  - **Scope note:** Prejudices are the *affective bridge* between cognitive stereotypes and behavioral discrimination. Cite this entry when the focus is on what someone *feels* about a group, not just what they *think* (Stereotype) or *do* (Discrimination).
  - **Primary purpose:** Enable IF-LLM to name the emotional layer of bias when helping users explore discomfort, fear, or dislike connected to group membership, and to guide them toward [[HUMANITY:COMPASSION]], [[HUMANITY:PERSPECTIVE]], and [[HUMANITY:REGULATION]] as counterweights.

- **Decision Rules (IF/THEN)**
  - **IF** a user describes negative feelings (distrust, discomfort, dislike) toward a group without behavioral action, **THEN** cite [[HUMANITY:PREJUDICES]] as the affective layer; note that it does not automatically produce discrimination.
  - **IF** a user asks how biased attitudes form and persist, **THEN** cite the Stereotypes → Prejudices → Discrimination chain and explain the role of [[HUMANITY:TEMPTATIONS]] (Tribal Thinking, Confirmation Bias) in reinforcing each step.
  - **IF** focus shifts to what someone *believes* about a group (cognitive), **THEN** move to [[HUMANITY:STEREOTYPES]].
  - **IF** focus shifts to what someone *does* as a result (unequal treatment), **THEN** move to [[HUMANITY:DISCRIMINATION]].
  - **IF** helping a user reduce their own prejudicial feelings, **THEN** cite [[HUMANITY:COMPASSION]], [[HUMANITY:PERSPECTIVE]], [[HUMANITY:OPENNESS]], and [[HUMANITY:REGULATION]] as the primary values and [[HUMANITY:ORIENT]] bias check as the practical tool.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:STEREOTYPES]] (cognitive input to prejudice); [[HUMANITY:DISCRIMINATION]] (behavioral output often driven by prejudice); [[HUMANITY:FALLIBILITY]] (prejudices are an affective expression of human fallibility); [[HUMANITY:TEMPTATIONS]] (Tribal Thinking, Social Comparison, Confirmation Bias generate and reinforce prejudices); [[HUMANITY:ORIENT]] (prejudices distort the interpretation step most directly)
  - **Produced by:** [[HUMANITY:STEREOTYPES]] (belief layer that generates the feeling layer); [[HUMANITY:TEMPTATIONS]] (Social Comparison, Tribal Thinking); limited cross-group contact and exposure
  - **Produces:** [[HUMANITY:DISCRIMINATION]] (when prejudicial feelings drive unequal behavioral choices); reduced [[HUMANITY:MOTIVATORS]] to help others; indirect [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] for those affected
  - **Reduced by:** [[HUMANITY:COMPASSION]] (empathic engagement with individuals beyond group labels); [[HUMANITY:PERSPECTIVE]] (direct exposure to outgroup members as individuals); [[HUMANITY:OPENNESS]] (willingness to update feelings); [[HUMANITY:REGULATION]] (managing the affective response before it drives behavior); [[HUMANITY:THINKING]] (examining the evidence basis for the feeling)
  - **Reinforced by:** [[HUMANITY:DISCRIMINATION]] (behavioral inequality can "justify" prejudicial feelings); [[HUMANITY:TEMPTATIONS]] (Confirmation Bias); media and social environments that amplify outgroup threat framing

##### Discrimination

ID: HUMANITY.ELEMENTS.FALLIBILITY.DISCRIMINATION
TAGS: [[HUMANITY:DISCRIMINATION]]

**Discrimination** is **unequal treatment or unfair actions** toward people based on group membership (race, gender, religion, disability, etc.). It's *behavioral* (what someone does) and can be individual (one person), institutional (policies/practices), or structural (system-wide patterns). [[HUMANITY:STEREOTYPES]] and [[HUMANITY:PREJUDICES]] affect [[HUMANITY:ORIENT]], which affects [[HUMANITY:DECIDE]], which results in discrimination during [[HUMANITY:ACT]]. Discrimination is a result of our examples of our [[HUMANITY:FALLIBILITY]]. The resulting discrimination creates real-world unequal outcomes and harms (e.g., [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]], [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]). Discrimination may reinforce [[HUMANITY:STEREOTYPES]] and [[HUMANITY:PREJUDICES]] (e.g., treating a group unfairly can be used to "justify" biased beliefs). Discrimination does not require [[HUMANITY:STEREOTYPES]] or [[HUMANITY:PREJUDICES]]; someone might discriminate due to **rules/incentives/social pressure** even without strong personal [[HUMANITY:PREJUDICES]]. Discrimination is the likely reduction of using our [[HUMANITY:RESOURCES]] and likelihood of performing [[HUMANITY:ACTIVITIES]] to help satisfy the [[HUMANITY:NEEDS]] of "those people", thereby impairing their ability to avoid [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]], while simultaneously limiting our [[HUMANITY:INTERDEPENDENCE]]. Discrimination limits the intentional and consistent practice of many [[HUMANITY:VALUES]] (e.g., [[HUMANITY:THINKING]], [[HUMANITY:PERSPECTIVE]], [[HUMANITY:OPENNESS]], [[HUMANITY:CURIOSITY]], [[HUMANITY:LEARNING]], [[HUMANITY:LOVE]], [[HUMANITY:MERCY]], [[HUMANITY:REGULATION]], [[HUMANITY:PRUDENCE]], [[HUMANITY:HUMILITY]], [[HUMANITY:TEMPERANCE]], [[HUMANITY:HUMOR]], [[HUMANITY:GRATITUDE]], [[HUMANITY:PURPOSE]], [[HUMANITY:FAIRNESS]], [[HUMANITY:JUSTICE]], [[HUMANITY:CITIZENSHIP]], [[HUMANITY:LEADERSHIP]], [[HUMANITY:INTEGRITY]], [[HUMANITY:VITALITY]], [[HUMANITY:TRANSCENDENCE]], [[HUMANITY:COMPASSION]], [[HUMANITY:INTERDEPENDENCE]], [[HUMANITY:WISDOM]]). Discrimination limits consistent and efficient performance of our [[HUMANITY:MISSION]], which impairs our contributions to our [[HUMANITY:VISION]], thereby increasing risks and harms to the [[HUMANITY:RIGHTS]] of ourselves and others. [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (e.g., **Selfishness**, **Moral and Ethical Compromise**, **Inflexibility and Rigidity**, **Exploitation and Manipulation**, **Aggression and Violence**) may also contribute to more frequent and more severe discrimination.

- **Examples**
  - **When a user describes being treated differently at work because of their background:** Cite [[HUMANITY:DISCRIMINATION]] as the behavioral pattern (individual or institutional); connect to [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (Dignity, Safety, Inclusion) as the likely harm; and [[HUMANITY:RIGHTS]] as what is being violated.
  - **When explaining why systems produce unfair outcomes even when individuals don't feel personally biased:** Cite structural [[HUMANITY:DISCRIMINATION]] — policies/incentives that produce unequal treatment regardless of individual intent — and link to [[HUMANITY:HISTORY_EXPERTS]] for evidence of systemic patterns.
  - **When a user asks how to respond fairly in a decision affecting diverse groups:** Cite [[HUMANITY:DISCRIMINATION]] as the risk to avoid; apply the [[HUMANITY:DECIDE]] bias check ("Would I choose the same option if the person were from a different group?") and cite [[HUMANITY:FAIRNESS]], [[HUMANITY:JUSTICE]], and [[HUMANITY:THINKING]] as the guiding values.

- **Boundaries / Scope**
  - **Includes:** Individual, institutional, and structural forms of unequal treatment based on group membership; discrimination that does and does not arise from personal [[HUMANITY:PREJUDICES]] (rules-based, incentive-based, and social-pressure-based discrimination are all included); the real-world harm discrimination causes to [[HUMANITY:NEEDS]] satisfaction.
  - **Excludes:** The cognitive dimension (beliefs) — see [[HUMANITY:STEREOTYPES]]; the affective dimension (feelings) — see [[HUMANITY:PREJUDICES]]; legal determinations or case adjudication; clinical diagnosis; partisan framing of discrimination causation.
  - **Scope note:** Discrimination is the *behavioral output* of the bias chain — and can also arise independently of personal stereotypes or prejudices (through systems, rules, or social pressure). Cite this entry when the focus is on what is actually *done* to people, not what is thought or felt about them.
  - **Primary purpose:** Enable IF-LLM to name the behavioral harm layer of bias, connect it to real-world [[HUMANITY:NEEDS]] deprivation and [[HUMANITY:RIGHTS]] violations, and support users in understanding how to reduce discrimination through [[HUMANITY:VALUES]]-aligned choices and [[HUMANITY:OODA]] discipline.

- **Decision Rules (IF/THEN)**
  - **IF** a user describes unequal treatment or unfair outcomes affecting people based on group membership, **THEN** cite [[HUMANITY:DISCRIMINATION]] as the behavioral pattern and [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] as the likely downstream harm.
  - **IF** a user asks why discrimination persists even when people "know better," **THEN** explain the three layers (Stereotypes → Prejudices → Discrimination) plus institutional/structural forms that operate independently of personal belief.
  - **IF** focus is on the feelings that precede unfair behavior, **THEN** move to [[HUMANITY:PREJUDICES]]; if on beliefs, move to [[HUMANITY:STEREOTYPES]].
  - **IF** a user asks about the rights dimension of discrimination, **THEN** link to [[HUMANITY:RIGHTS]] (equal opportunity to satisfy needs) and [[HUMANITY:VISION]] (the world where all rights are honored).
  - **IF** a user asks what helps reduce discrimination, **THEN** cite [[HUMANITY:THINKING]], [[HUMANITY:FAIRNESS]], [[HUMANITY:JUSTICE]], [[HUMANITY:COMPASSION]], [[HUMANITY:PERSPECTIVE]], and [[HUMANITY:INTERDEPENDENCE]] as the values; and the [[HUMANITY:DECIDE]] bias check as the practical OODA tool.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:STEREOTYPES]] and [[HUMANITY:PREJUDICES]] (cognitive-affective inputs that frequently drive discriminatory behavior); [[HUMANITY:FALLIBILITY]] (discrimination is a behavioral expression of human fallibility); [[HUMANITY:ACT]] (discrimination occurs during the Act step of [[HUMANITY:OODA]], driven by biased [[HUMANITY:ORIENT]] and [[HUMANITY:DECIDE]]); [[HUMANITY:RIGHTS]] (discrimination is the primary mechanism by which rights are violated in practice); [[HUMANITY:CONCERNS]] (discrimination appears across nearly every concern category — healthcare access, employment, education, justice)
  - **Produced by:** [[HUMANITY:PREJUDICES]] (when affective bias drives unequal behavioral choices); institutional rules, incentives, and social pressure (independent of personal bias); [[HUMANITY:TEMPTATIONS]] (Power and Control, Tribal Thinking, Social Comparison)
  - **Produces:** [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (unequal access to Health, Safety, Dignity, Inclusion); [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (exploitation, aggression, broken trust at systemic scale); reinforcement of [[HUMANITY:STEREOTYPES]] and [[HUMANITY:PREJUDICES]] (behavioral inequality is used to "justify" cognitive and affective biases)
  - **Reduced by:** [[HUMANITY:FAIRNESS]] (equal and consistent treatment standard); [[HUMANITY:JUSTICE]] (systemic accountability); [[HUMANITY:THINKING]] (bias checks in decision-making); [[HUMANITY:COMPASSION]] (empathic regard for those affected); [[HUMANITY:INTERDEPENDENCE]] (recognition that everyone's well-being is connected); [[HUMANITY:LEADERSHIP]] (holding systems and norms to higher standards)
  - **Vulnerable to:** Normalization — when discriminatory patterns become "just how things are," they become harder to name and interrupt; requires active [[HUMANITY:WISDOM]] and [[HUMANITY:LESSONS]] awareness to recognize
