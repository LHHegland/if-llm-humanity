# Humanity's Needs ← Activities ← Resources ← Motivations (NARM) Process — Information-Following Large Language Model Knowledge (*if-llm-humanity-narm.md*)

## File Header

- **Name:** Humanity's Needs ← Activities ← Resources ← Motivations (NARM) Process — Information-Following Large Language Model Knowledge (*if-llm-humanity-narm.md*)
- **Version:** 2026-06-17 04:26 UTC by [Lance Hegland](lance.hegland@gmail.com)
- **Last Reviewed:** 2026-06-15 04:56 UTC by [Lance Hegland](lance.hegland@gmail.com)
- **Owner:** [Lance Hegland](lance.hegland@gmail.com)

- **Purpose:** Empower an IF-LLM to help an average U.S. adult understand the fundamental human resource-activity-need system (NARM) — why people struggle when resources run low, how everyday activities connect to core human needs, what behaviors signal unmet needs, and what practical steps can help someone build capacity and meet their needs more effectively.
- **Audience:** Average, diverse people in the United States of America today.
- **Features**
  - Eight integrated entries covering Needs, Consequences of Unmet Needs, Activities (ADLs and IADLs), Limited Available Resources, Capabilities, and Motivators — organized as an upstream-causation system (Motivators → Resources → Activities → Needs).
  - Detailed resource-building tips for Time, Energy, Integrity, and each of seven Capability types (Autonomy, Abilities, Relationships, Experiences, Knowledge, Skills, Tools, Finances).
  - Consequences of Unmet Needs organized by need category (Health, Safety, Dignity, Inclusion) with observable behavioral indicators useful for sensemaking.
  - Ontological relationships across all entries link NARM to [[HUMANITY:OODA]], [[HUMANITY:FALLIBILITY]], [[HUMANITY:VALUES]], and [[HUMANITY:CONCERNS]].
  - Concept Disambiguation section distinguishes overlapping entries (especially Needs vs. Motivators, Resources vs. Capabilities, ADLs vs. IADLs, Consequences of Unmet Needs vs. Consequences of Temptations).
  - IF/THEN decision rules support structured retrieval workflows per entry.
- **Scope**
  - **Covers:** Universal human needs (Health, Safety, Dignity, Inclusion); behavioral consequences of unmet needs; the activities (ADLs and IADLs) required to meet them; the limited resources required to perform those activities; buildable capability multipliers; and the motivators that sustain effort — all as an integrated system.
  - **Out of Scope:** Clinical assessment or treatment of need deprivation; medical, legal, or financial advice; policy prescription for addressing systemic resource gaps; individual case management; diagnosis of specific medical or psychological conditions from the Consequences of Unmet Needs indicators.
- **Use Cases**
  - **Supported:** Helping users identify which needs are unmet and why; supporting practical resource and capability planning; interpreting behavioral signs of need deprivation in self and others (non-clinically); grounding coping conversations in the NARM framework; supporting goal-setting, habit-building, and daily functioning improvement.
  - **Not Supported:** Not a clinical assessment tool; not for medical diagnosis; not suitable for generating professional service referrals for clinical needs (see [[HUMANITY:COPING]] for emergency and professional resource guidance); not a replacement for financial, legal, or healthcare professional advice; not for population-level policy analysis.

- **Dependencies (Required):** `if-llm-system-policies-processing.md`, `if-llm-humanity.md`, `if-llm-humanity-experts.md`, `if-llm-humanity-fallibility.md`, `if-llm-humanity-ooda.md`, `if-llm-humanity-values.md`
- **Stability:** Stable. Core entries, tag assignments, and namespace rules are intended to remain consistent across sessions. Silent reinterpretation of entries, tag reassignment, or scope expansion without an explicit Changelog entry is prohibited.
- **Known Gaps / Limitations**
  - Consequences of Unmet Needs indicators are observable behavioral signals, not clinical diagnoses. They should be used for sensemaking and support, not assessment or labeling.

- **Changelog**
  - 2026-06-17 04:26 UTC by [Lance Hegland](lance.hegland@gmail.com): Updated `Index` > `Domain Knowledge Index` to reflect split of `if-llm-humanity-values.md` containing 31 entries into four separate files with roughly 550 lines each as follows:
    - `if-llm-humanity-values-1.md` contains the 7 entries `Values` through `Open-Mindedness`
    - `if-llm-humanity-values-2.md` contains the 7 entries  `Perspective` through `Humility`
    - `if-llm-humanity-values-3.md` contains the 7 entries  `Prudence` through `Humor`
    - `if-llm-humanity-values-4.md` contains the 10 entries  `Justice` through `Hope`
  - 2026-06-15 04:56 UTC by [Lance Hegland](lance.hegland@gmail.com): Replaced all TBD fields in File Header (Purpose, Features, Scope, Use Cases, Known Gaps/Limitations); added Concept Disambiguation section to Index; added Examples, Boundaries/Scope, Decision Rules, and Ontological Relationships to all eight entries (Needs, Consequences of Unmet Needs, Activities, ADLs, IADLs, Resources, Capabilities, Motivators); updated Changelog with this entry.
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
  - Courage → HUMANITY.ELEMENTS.VALUES.COURAGE → [[HUMANITY:COURAGE]]
  - Bravery → HUMANITY.ELEMENTS.VALUES.BRAVERY → [[HUMANITY:BRAVERY]]
  - Integrity → HUMANITY.ELEMENTS.VALUES.INTEGRITY → [[HUMANITY:INTEGRITY]]
  - Vitality → HUMANITY.ELEMENTS.VALUES.VITALITY → [[HUMANITY:VITALITY]]
  - Hope → HUMANITY.ELEMENTS.VALUES.HOPE → [[HUMANITY:HOPE]]

### Concept Disambiguation

Use these notes to select between partially overlapping concepts for precise IF-LLM retrieval and reasoning.

- **[[HUMANITY:NEEDS]] vs. [[HUMANITY:MOTIVATORS]]**
  - Use `[[HUMANITY:NEEDS]]` when the focus is on *universal structural requirements* for human health, safety, dignity, and inclusion — the four categories that every person requires regardless of context, culture, or preference.
  - Use `[[HUMANITY:MOTIVATORS]]` when the focus is on *contextual energizing drivers* — the specific reasons, drives, and preferences that cause an individual to act, which vary widely across people and situations.
  - Note: Needs are the *destination*; motivators are part of the *engine* that drives the journey. When a user asks "what does everyone need?" cite [[HUMANITY:NEEDS]]. When a user asks "what makes this person keep going (or stop)?" cite [[HUMANITY:MOTIVATORS]].

- **[[HUMANITY:RESOURCES]] vs. [[HUMANITY:CAPABILITIES]]**
  - Use `[[HUMANITY:RESOURCES]]` when the focus is on the *core limited inputs* humans draw on to perform activities — Time, Energy, and Integrity. These are consumed as used, finite, and non-substitutable.
  - Use `[[HUMANITY:CAPABILITIES]]` when the focus is on *buildable multipliers* that increase what a person can achieve per unit of resource — Autonomy, Abilities, Relationships, Experiences, Knowledge, Skills, Tools, Finances. These can be developed over time.
  - Note: Resources are the *fuel*; Capabilities are the *engine efficiency*. When a user asks "I don't have enough time/energy," cite [[HUMANITY:RESOURCES]]. When a user asks "how do I get better at this?" cite [[HUMANITY:CAPABILITIES]].

- **[[HUMANITY:ADLS]] vs. [[HUMANITY:IADLS]]**
  - Use `[[HUMANITY:ADLS]]` when the focus is on *essential personal self-care tasks* that directly meet Health, Safety, and Dignity needs — bathing, toileting, dressing, transferring, eating. These are the most basic functional activities.
  - Use `[[HUMANITY:IADLS]]` when the focus is on *instrumental support activities* that enable ADLs and support Inclusion — meal preparation, housekeeping, shopping, transportation, communication, medications, finances.
  - Note: ADLs are the *floor* (minimum functioning); IADLs are the *scaffolding* (what supports the floor and enables participation). When a user is in crisis or has reduced capacity, start with [[HUMANITY:ADLS]]; when building sustainable daily functioning, add [[HUMANITY:IADLS]].

- **[[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] vs. [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]**
  - Use `[[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]` when outcomes result primarily from *chronic deprivation* — prolonged inability to meet Health, Safety, Dignity, or Inclusion needs (e.g., anxiety from financial insecurity, withdrawal from social exclusion).
  - Use `[[HUMANITY:CONSEQUENCES_TEMPTATIONS]]` when outcomes result primarily from *making harmful behavioral choices* — following temptation patterns that damage trust, relationships, or functioning (e.g., addiction, broken trust, moral drift).
  - Note: These two consequence sets frequently interact and compound. Temptations can cause unmet needs (addiction → financial ruin → health deprivation); unmet needs can fuel temptations (insecurity → hoarding). When both apply, cite both and identify which is driving the cycle.

- **[[HUMANITY:ACTIVITIES]] vs. [[HUMANITY:OODA]]**
  - Use `[[HUMANITY:ACTIVITIES]]` when the focus is on *what a person does* to satisfy needs — the content of their behavior (bathing, shopping, communicating, earning income).
  - Use `[[HUMANITY:OODA]]` when the focus is on *how a person decides what to do* — the sense-make-act loop that governs behavioral choices in real time.
  - Note: Activities are the *output* of the OODA loop; OODA is the *process* that selects and executes activities. Cite both when explaining that someone has the right activities in mind but keeps making poor moment-to-moment decisions about them.

### Local Knowledge Index

The following is a list of this file's common topic references mapped to canonical handles.

- Needs → HUMANITY.ELEMENTS.NEEDS → [[HUMANITY:NEEDS]]
- Consequences of Unmet Needs → HUMANITY.ELEMENTS.CONSEQUENCES_UNMET_NEEDS → [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]
- Activities → HUMANITY.ELEMENTS.ACTIVITIES → [[HUMANITY:ACTIVITIES]]
- Activities of Daily Living (ADLs) → HUMANITY.ELEMENTS.ACTIVITIES.ADLS → [[HUMANITY:ADLS]]
- Instrumental Activities of Daily Living (IADLs) → HUMANITY.ELEMENTS.ACTIVITIES.IADLS → [[HUMANITY:IADLS]]
- Limited Available Resources → HUMANITY.ELEMENTS.RESOURCES → [[HUMANITY:RESOURCES]]
- Capabilities → HUMANITY.ELEMENTS.RESOURCES.CAPABILITIES → [[HUMANITY:CAPABILITIES]]
- Motivators → HUMANITY.ELEMENTS.MOTIVATORS → [[HUMANITY:MOTIVATORS]]

## Humanity

### Elements

#### Needs

ID: HUMANITY.ELEMENTS.NEEDS
TAGS: [[HUMANITY:NEEDS]]

Needs of humans that are satisfied by [[HUMANITY:ACTIVITIES]], which require [[HUMANITY:RESOURCES]]. These needs include the following:

- **Health**: essential items for survival, such as nutrition, hydration, shelter, and sleep.
- **Safety**: feeling and being safe from harm; having physical security, financial stability, and a supportive environment.
- **Dignity**: self-esteem, achievements, skills, independence, and respect from others; involves realizing potential, personal growth, and achieving fulfillment.
- **Inclusion**: ability for meaningful contribution and participation in activities with chosen families, friends, and communities; meaningful participation and contribution to familial, social, cultural, spiritual, educational, economic, romantic, and sexual activities.

- **Examples**
  - **When a user describes constant worry, physical exhaustion, or inability to focus:** Cite [[HUMANITY:NEEDS]]: Health or Safety as the likely unmet need categories; explore what [[HUMANITY:RESOURCES]] or [[HUMANITY:ACTIVITIES]] are insufficient.
  - **When a user feels unappreciated, incompetent, or stuck:** Cite [[HUMANITY:NEEDS]]: Dignity as the unmet need; connect to [[HUMANITY:CAPABILITIES]] development and [[HUMANITY:MOTIVATORS]] as pathways.
  - **When a user feels lonely, excluded, or disconnected:** Cite [[HUMANITY:NEEDS]]: Inclusion as the unmet need; connect to [[HUMANITY:IADLS]] (using communication devices, coordinating transportation) and [[HUMANITY:COPING]] (social connection strategies).
  - **When framing why any human struggle matters:** Cite [[HUMANITY:NEEDS]] as the universal structural baseline — not a preference, but a requirement — to ground the conversation in shared humanity rather than individual failure.

- **Boundaries / Scope**
  - **Includes:** The four universal need categories (Health, Safety, Dignity, Inclusion) applicable to all humans regardless of background, culture, or circumstance; the structural framework for understanding why people struggle when activities and resources are insufficient.
  - **Excludes:** Specific behavioral consequences of unmet needs (see [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]); individual preferences or desires that are not universal requirements; clinical diagnoses of need deprivation; policy prescriptions for meeting needs at scale.
  - **Primary purpose:** Provide IF-LLM with a consistent, non-judgmental framework for identifying what a person actually requires — as a universal human — before assessing what resources, activities, or support they need.

- **Decision Rules (IF/THEN)**
  - **IF** a user describes a struggle without naming what's wrong, **THEN** use [[HUMANITY:NEEDS]] categories as a diagnostic lens: "Is this primarily a Health, Safety, Dignity, or Inclusion challenge?"
  - **IF** a user's situation involves multiple unmet needs, **THEN** prioritize Health and Safety first (survival baseline), then Dignity and Inclusion.
  - **IF** the focus is on the observable signs of unmet needs, **THEN** move to [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] for the detailed indicator list.
  - **IF** the focus is on why someone can't meet their needs, **THEN** explore [[HUMANITY:RESOURCES]] (is the input insufficient?) and [[HUMANITY:CAPABILITIES]] (is the multiplier underdeveloped?) and [[HUMANITY:MOTIVATORS]] (is the drive depleted?).
  - **IF** a user asks what everyone has in common, **THEN** cite [[HUMANITY:NEEDS]] (universal) alongside [[HUMANITY:RIGHTS]] (equal opportunity to satisfy them) and [[HUMANITY:FALLIBILITY]] (we all struggle sometimes).

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:RIGHTS]] (rights are defined as equal opportunity to satisfy needs); [[HUMANITY:CONCERNS]] (societal concerns represent active or perceived threats to need satisfaction); [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (what happens when needs go unmet consistently); [[HUMANITY:ACTIVITIES]] (activities are the means of satisfying needs); [[HUMANITY:RESOURCES]] (resources are required to perform activities); [[HUMANITY:MISSION]] (the Mission is to perform activities that satisfy needs with available resources)
  - **Satisfied by:** [[HUMANITY:ACTIVITIES]] (specifically [[HUMANITY:ADLS]] and [[HUMANITY:IADLS]]) using available [[HUMANITY:RESOURCES]] and [[HUMANITY:CAPABILITIES]]
  - **Threatened by:** [[HUMANITY:DISCRIMINATION]] (restricts access to need-satisfying resources and activities); [[HUMANITY:TEMPTATIONS]] (can consume resources needed for needs); [[HUMANITY:FALLIBILITY]] (errors and harmful patterns reduce need satisfaction efficiency); [[HUMANITY:CONCERNS]] (represent active societal-level threats to needs)
  - **Required by:** [[HUMANITY:OODA]] (the OODA loop is oriented toward protecting and satisfying needs at each step); [[HUMANITY:MOTIVATORS]] (need-driven motivators sustain effort toward need satisfaction)

#### Consequences of Unmet Needs

ID: HUMANITY.ELEMENTS.CONSEQUENCES_UNMET_NEEDS
TAGS: [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]

Common consequences of unmet needs of humanity observed across our many, diverse communities throughout our history; results of consistent and prolonged challenges satisfying [[HUMANITY:NEEDS]]. These are observed patterns, not moral judgments. Outcomes are shaped by many, diverse factors (e.g., environment, disability, trauma, discrimination, access).

- **Health**
  - Death
  - Illness: Increased susceptibility to infections and diseases due to a weakened immune system.
  - Weight Loss: Sudden or significant decrease in body weight.
  - Hunger: Asking for food and beverages, hoarding, eating or drinking quickly or in large amounts when available.
  - Malnutrition: Weight loss, weakness, fatigue, and other signs of inadequate nutrition.
  - Dehydration: Dry skin, dizziness, confusion, and other symptoms of not having enough water.
  - Mood Swings: Increased irritability, anger, frustration, or sadness as a result of unmet survival needs.
  - Poor Hygiene: Unkempt appearance, dirty clothes, body odor.
  - Fatigue: Dark circles under eyes, sluggish movements, frequent yawning.
  - Poor Sleep: Chronic fatigue, irritability, and cognitive impairment due to lack of restful sleep.
  - Desperation: Engaging in risky behaviors or illegal activities in hopes of securing resources to satisfy basic survival needs.
  - Seeking Resources: Frequently asking for resources perceived to satisfy unmet needs.
  - Isolation: Withdrawing from social activities or groups they previously enjoyed due to lack of energy plus shame or embarrassment.
  - Depression: Feelings of hopelessness, despair, and lack of motivation due to ongoing survival struggles.
  - Decreased Performance: Decline in family, community, education, and employment performance due to lack of focus and energy; increased tardiness and absenteeism.
  - Focus on Survival: Prioritizing immediate survival over long-term goals or relationships.
  - Anxiety and Stress: Persistent worry about how to survive, leading to high levels of stress.
- **Safety**
  - Defiance and Rebellion: Oppositional behavior as a reaction to perceived control or coercion. Questioning or challenging rules, instructions, or perceived authority figures.
  - Anger, Frustration, and Resentment: Negative emotions like anger, frustration, irritation, and resentment stemming from perceived constraints or lack of freedom.
  - Seeking Control: Efforts to gain more control, such as pushing for more decision-making power or independence.
  - Mood Swings: Fluctuations in mood, especially related to experiences of perceived control or autonomy. Occasional breakdowns or emotional reactions disproportionate to the situation.
  - Paranoia: Excessive distrust of others, especially those perceived as having control or being manipulative, and heightened suspicion of being in danger.
  - Hypervigilance: Being excessively alert to potential dangers or threats, constantly on guard and regularly checking safety.
  - Excessive Preparation: Carrying multiple self-defense items, having backup plans, and having elaborate safety plans to significantly reduce risks.
  - Physical Symptoms: Headaches, stomachaches, and other stress-related ailments.
  - Sleep Problems: Insomnia or disrupted sleep due to worry and stress.
  - Fatigue: Signs of tiredness or exhaustion, potentially due to constant stress and vigilance.
  - Frequent Complaints: Expressing dissatisfaction with their lack of autonomy or control.
  - Health Complaints: Frequent complaints about stress-related health issues.
  - Frequent Expressions of Fear: Verbally expressing worries about safety and security.
  - Visible Frustration: Showing signs of frustration or irritability, particularly when discussing their autonomy.
  - Visible Stress: Physical signs of stress due to uncertainty and perceived threats, such as clenched jaws, tense posture, or nervous fidgeting, indicating a desire to break free from constraints.
  - Visible Anxiety: Appearing nervous, jumpy, or easily startled.
  - Dependence on Routine: Relying heavily on routines and predictability to create a sense of safety.
  - Risk-Averse Behavior: Reluctance to take risks or try new things due to fear of harm.
  - Neglect of Self-Care: Decreased attention to personal hygiene or health due to preoccupation with safety.
  - Low Motivation: Reduced enthusiasm and drive to pursue goals or engage in activities, particularly where autonomy is perceived to be restricted.
  - Avoidance: Avoiding places, people, or situations perceived as potentially dangerous or threatening.
  - Isolation: Withdrawing from social interactions to avoid potential threats where they feel controlled or pressured.
  - Compliance Without Engagement: Following instructions mechanically without genuine interest or engagement.
  - Seeking Excessive Reassurance: Frequently asking for confirmation of safety and security from others.
  - Anxiety and Fear: Persistent worry about personal health, safety, finances, or stability.
  - Feelings of Helplessness: A sense of powerlessness and lack of control over one's circumstances.
- **Dignity**
  - Defensive Behavior: Reacting strongly to criticism or perceived slights, often with anger or denial.
  - Frustration and Irritability: Increased frustration and irritability resulting from feeling unfulfilled, frustrated, and overwhelmed due to unmet aspirations and goals, lack of clarity and understanding, plus continuous stress and overexertion.
  - Mood Swings: Fluctuations in mood including increased irritability or sadness related to feelings of purpose and achievement, feedback, opportunities, or lack thereof.
  - Frequent Complaints: Expressing dissatisfaction with their current situation or feeling stuck, especially with their work, lack of opportunities, or feeling unfulfilled.
  - Escapism: Excessive engagement in activities that distract from the lack of fulfillment, such as social activities, recreation, gaming, multimedia, shopping, relationships, eating, substance use, gambling, or other potentially harmful or risky overindulgence.
  - Fatigue: Signs of tiredness or exhaustion, possibly due to stress or overworking.
  - Lack of Motivation: Showing a decreased interest in pursuing new challenges or endeavors that previously held appeal.
  - Depression: Feelings of sadness, hopelessness, and a lack of motivation related to perceived incompetence or judgment of others.
  - Excessive Criticism of Self: Frequently putting oneself down or expressing doubt about one's abilities.
  - Regret: Persistent feelings of regret over missed opportunities or unachieved potential, dreams, goals, or projects.
  - Neglected Appearance: Lack of attention to personal grooming or hygiene, potentially reflecting time constraints, low energy, distractions, low self-regard, disengagement, or lack of initiative.
  - Expressing Tension: Expressing feelings of being stressed or overwhelmed, such as clenched jaws, tense posture, nervous fidgeting, frequent sighing, or comments.
  - Perfectionism: Setting unrealistically high standards and being overly critical of oneself when these standards are not met, leading to feelings of inadequacy.
  - Overachievement: Pushing oneself excessively to demonstrate competence, achieve success, and gain recognition.
  - Dependence on Others: Relying excessively on others for help, guidance, answers, decisions, feedback, reassurance, or validation.
  - Expressions of Doubt: Expressing confusion or doubts about their abilities and competence; appearing unsure, hesitant, or anxious in situations where competence or performance may be evaluated or judged.
  - Visible Discontent: Consistently dissatisfied, unfulfilled, or restless.
  - Frequent Changes: Changing jobs, hobbies, or interests in search of fulfillment.
  - Procrastination, Withdrawal, or Avoidance: Hesitation or refusal to participate in activities, especially social, vocational, personal growth, or self-improvement; those that could trigger feelings of inadequacy; situations where evaluation or judgment might occur; including discussions, tasks, projects, responsibilities, or challenges.
  - Declining Performance: Making errors due to nervousness or lack of confidence; reduced efficiency due to repetitive double-checking.
  - Avoidance of Eye Contact: Avoiding eye contact during discussions or explanations, possibly due to embarrassment or insecurity.
  - Anxiety: Worry about one's competence, lack of opportunities, confusion, lack of meaningful activities, fear of failure, and excessive concern about others' opinions.
  - Low Self-Esteem: Persistent feelings of inadequacy, self-doubt, and a lack of confidence.
  - Expressions of Boredom: Frequently mentioning feeling bored or unchallenged by their current activities.
- **Inclusion**
  - Mood Swings: Experiencing sudden changes in mood, particularly when social, political, and community interactions are involved.
  - Risky Behaviors: Engaging in behaviors that are risky, impulsive, out of character, or extreme as a way to gain attention, or to feel a sense of connection.
  - Expressing Discontent: Verbally expressing feelings of exclusion, frustration, or powerlessness.
  - Frustration: Feeling frustrated or powerless due to the inability to participate meaningfully.
  - Avoidance: Avoiding interactions due to feeling disconnected or misunderstood, including familial, social, cultural, spiritual, educational, economic, romantic, and sexual interactions.
  - Lack of Engagement and Commitment: Rarely participating and difficulty committing to interactions, connections, and relationships. Being physically present but not actively participating or contributing.
  - Fatigue: Signs of tiredness or exhaustion, potentially due to emotional stress or lack of engagement.
  - Neglected Appearance: Lack of attention to personal grooming or hygiene, which might indicate a lack of motivation or care.
  - Withdrawal: Pulling away from interactions due to fear of rejection and exclusion; appearing bored, disengaged, or indifferent in group settings.
  - Depression: Feelings of sadness, hopelessness, and a lack of interest in activities once enjoyed due to disconnection.
  - Tension: Physical signs of stress, such as clenched jaws, tense posture, or nervous fidgeting during social, political, and community interactions.
  - Over-Involvement: Focusing excessively on specific roles, groups, labels, or areas where they feel they can participate and have control.
  - Frequent Changes: Constantly changing connections, relationships, hobbies, jobs, or groups in search of stable connections; seeking other ways to feel engaged, such as virtual communities or solitary activities.
  - Inconsistent Behavior: Exhibiting different personas or behaviors in various situations to fit in or be accepted; changing attitudes, beliefs, or behaviors in different contexts in hopes of gaining or maintaining acceptance with others.
  - Clinginess: Excessive attempts to maintain and confirm connections, such as frequent texting or needing to be physically close; overly dependent on certain relationships.
  - Attention-Seeking: Acting out in ways that seem intended to attract notice, whether positive or negative.
  - Confusion and Uncertainty: Feeling unsure about their role in interactions and among local communities and groups.
  - Loneliness: A pervasive sense of isolation and lack of meaningful connections.
  - Feelings of Exclusion: A sense of being left out or not belonging to a group or community.
  - Anxiety: Nervousness and worry about forming and maintaining relationships, often due to fear of rejection or judgment.
  - Expressing Feelings of Loneliness: Frequently talking about feeling lonely or disconnected.
  - Low Self-Esteem: Reduced self-worth plus feelings of worthlessness, being unlovable or unlikable due to lack of involvement and recognition.

- **Examples**
  - **When a user describes someone who seems irritable, defensive, and disengaged at work:** Cite [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]: Dignity indicators (Defensive Behavior, Frustration, Lack of Motivation) to frame the interpretation before assigning blame.
  - **When a user is worried about a friend who has withdrawn socially and seems sad:** Cite [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]: Inclusion indicators (Withdrawal, Depression, Loneliness) as the likely pattern; connect to [[HUMANITY:COPING]] for support pathways.
  - **When a user notices a child acting out in class:** Cite [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]: Safety or Inclusion indicators (Defiance and Rebellion, Seeking Control, Risky Behaviors) to reframe behavior as a signal rather than a character flaw.

- **Boundaries / Scope**
  - **Includes:** Observable behavioral, emotional, and physical indicators of unmet needs organized by need category; patterns applicable across diverse populations and contexts; non-clinical sensemaking tools for understanding why someone may be struggling.
  - **Excludes:** Clinical diagnosis of specific conditions (indicators here are signals, not diagnoses); legal or forensic assessments; individual case management; judgment about character or intent; outcomes caused primarily by temptation choices rather than deprivation (see [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]).
  - **Scope note:** When the same indicator (e.g., Depression, Fatigue, Mood Swings) appears under multiple need categories, it signals that the need category matters for identifying the *source* — not just the symptom. Identify which need category seems most active before applying indicators.
  - **Primary purpose:** Give IF-LLM a structured, compassionate lens for interpreting difficult behaviors as *signals of unmet needs* rather than character flaws — and to identify the right support pathway.

- **Decision Rules (IF/THEN)**
  - **IF** a user describes behaviors that are puzzling, frustrating, or concerning in someone else, **THEN** check [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] by need category before attributing the behavior to character, intent, or [[HUMANITY:TEMPTATIONS]].
  - **IF** Health indicators are present (malnutrition, poor sleep, fatigue, depression), **THEN** address Health needs first — they are the survival baseline. Refer to [[HUMANITY:COPING]] if urgent.
  - **IF** Safety indicators are dominant (hypervigilance, paranoia, defiance, excessive reassurance-seeking), **THEN** explore what threats — real or perceived — are affecting the person's sense of security.
  - **IF** Dignity indicators are dominant (self-criticism, perfectionism, avoidance of evaluation, low motivation), **THEN** explore what skills, recognition, independence, or purpose might be missing or blocked.
  - **IF** Inclusion indicators are dominant (withdrawal, clinginess, frequent changes, loneliness), **THEN** explore what connections, community roles, or participation opportunities are missing or inaccessible.
  - **IF** multiple need categories are indicated simultaneously, **THEN** note that needs interact and compound; prioritize addressing the most basic (Health → Safety → Dignity → Inclusion) first when resources are limited.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:NEEDS]] (the four unmet need categories that produce these consequences); [[HUMANITY:TEMPTATIONS]] (temptations can deplete resources needed for need satisfaction, producing these consequences); [[HUMANITY:FALLIBILITY]] (fallibility increases vulnerability to these outcomes); [[HUMANITY:CONCERNS]] (many societal concerns represent systemic patterns of unmet needs across communities); [[HUMANITY:RIGHTS]] (chronic unmet needs often indicate rights violations)
  - **Produced by:** Consistent and prolonged inability to perform [[HUMANITY:ACTIVITIES]] using [[HUMANITY:RESOURCES]] to satisfy [[HUMANITY:NEEDS]]; [[HUMANITY:DISCRIMINATION]] (restricts access to need-satisfying activities and resources); [[HUMANITY:TEMPTATIONS]] (can deplete resources); [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (can compound need deprivation)
  - **Addressed by:** [[HUMANITY:COPING]] (urgent and professional support resources); [[HUMANITY:ACTIVITIES]] (restoring ADL and IADL capacity); [[HUMANITY:RESOURCES]] and [[HUMANITY:CAPABILITIES]] development (rebuilding the input system); [[HUMANITY:INTERDEPENDENCE]] (community support as a resource)
  - **Amplified by:** [[HUMANITY:DISCRIMINATION]] (systemic barriers to need satisfaction); low [[HUMANITY:RESOURCES]] across multiple types simultaneously; social isolation reducing [[HUMANITY:INTERDEPENDENCE]] support

#### Activities

ID: HUMANITY.ELEMENTS.ACTIVITIES
TAGS: [[HUMANITY:ACTIVITIES]]

Basic human activities requiring [[HUMANITY:RESOURCES]] to satisfy [[HUMANITY:NEEDS]]. Activities are the behavioral means by which humans convert [[HUMANITY:RESOURCES]] into [[HUMANITY:NEEDS]] satisfaction. Without sufficient activities — either because resources are depleted, capabilities are insufficient, or motivators are absent — needs go unmet and [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] emerge.

- **Examples**
  - **When a user asks how to help someone who seems to be struggling:** Identify which [[HUMANITY:ADLS]] or [[HUMANITY:IADLS]] may be compromised and which [[HUMANITY:RESOURCES]] are most constrained.
  - **When a user asks "what should I focus on first?":** Check which activities most directly serve the most pressing unmet [[HUMANITY:NEEDS]] (Health and Safety first, then Dignity and Inclusion).
  - **When explaining why someone seems unable to "get it together":** Cite [[HUMANITY:ACTIVITIES]] as the functional layer — activity performance breaks down when [[HUMANITY:RESOURCES]] (time, energy) are depleted or [[HUMANITY:CAPABILITIES]] are insufficient.

- **Boundaries / Scope**
  - **Includes:** All behavioral actions humans perform using resources to meet needs; encompasses both ADLs (essential self-care) and IADLs (instrumental support activities); the functional output layer of the NARM system.
  - **Excludes:** The OODA decision process that governs which activities to perform (see [[HUMANITY:OODA]]); resources required to perform activities (see [[HUMANITY:RESOURCES]]); needs that activities are designed to satisfy (see [[HUMANITY:NEEDS]]); clinical activity analysis or occupational therapy assessment.
  - **Primary purpose:** Enable IF-LLM to identify the *functional action layer* of the NARM system — what the person is doing (or not doing) — when exploring why needs are or are not being met.

- **Decision Rules (IF/THEN)**
  - **IF** a user is struggling to meet their needs, **THEN** identify which activities are missing, blocked, or being performed with insufficient resources.
  - **IF** a user asks what to do to feel better, **THEN** start with the most basic activities (ADLs for survival, IADLs for sustainability) before recommending more complex interventions.
  - **IF** activities are being performed but needs are still unmet, **THEN** explore whether [[HUMANITY:RESOURCES]] are insufficient to perform them effectively, or whether [[HUMANITY:CAPABILITIES]] need development.
  - **IF** the question is about how someone decides which activities to perform, **THEN** move to [[HUMANITY:OODA]] (the decision loop governing activity selection and execution).

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:NEEDS]] (activities exist to satisfy needs); [[HUMANITY:RESOURCES]] (activities require resources); [[HUMANITY:OODA]] (the OODA loop selects and executes activities); [[HUMANITY:MISSION]] (the Mission is performed through daily activities)
  - **Requires:** [[HUMANITY:RESOURCES]] (time, energy, integrity) and [[HUMANITY:CAPABILITIES]] (autonomy, skills, tools, finances, etc.)
  - **Satisfies:** [[HUMANITY:NEEDS]] (Health, Safety, Dignity, Inclusion) when performed with sufficient resources
  - **Disrupted by:** [[HUMANITY:FALLIBILITY]], [[HUMANITY:TEMPTATIONS]], and [[HUMANITY:DISCRIMINATION]] (which restrict access or deplete resources); [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (which reduce the capacity to perform activities, creating reinforcing cycles)

##### Activities of Daily Living (ADLs)

ID: HUMANITY.ELEMENTS.ACTIVITIES.ADLS
TAGS: [[HUMANITY:ADLS]]

Essential tasks satisfying [[HUMANITY:NEEDS]] of **Health**, **Safety**, and **Dignity**, including the following:

- bathing;
- using the bathroom;
- dressing;
- transferring; and,
- eating.

- **Examples**
  - **When a user describes someone who has stopped bathing or eating regularly:** Cite [[HUMANITY:ADLS]] as the functional baseline that has broken down; this signals significant [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (Health) and warrants [[HUMANITY:COPING]] resources.
  - **When assessing the severity of a situation:** Check ADL performance first — if basic self-care is compromised, this is the highest-priority intervention point before anything else.
  - **When explaining the hierarchy of functioning:** ADLs are the *floor* — if someone cannot reliably perform them, higher-order activities (IADLs, social participation) will also suffer.

- **Boundaries / Scope**
  - **Includes:** The five foundational self-care activities (bathing, toileting, dressing, transferring/mobility, eating); the survival-level baseline for Health, Safety, and Dignity need satisfaction.
  - **Excludes:** Instrumental activities that support ADLs (see [[HUMANITY:IADLS]]); social participation activities (Inclusion); clinical occupational therapy assessment of ADL capacity; specific disability accommodations.
  - **Primary purpose:** Establish the *minimum functional floor* — if a user or someone they care about cannot reliably perform these activities, that signals an urgent need for support.

- **Decision Rules (IF/THEN)**
  - **IF** ADL performance is severely compromised, **THEN** prioritize this above all other NARM interventions; refer to [[HUMANITY:COPING]] for professional and urgent support resources.
  - **IF** a user is planning how to support someone who is struggling, **THEN** assess ADL capacity first before addressing IADLs or higher-order needs.
  - **IF** resources are very limited, **THEN** allocate them to ADLs first (survival baseline) before IADLs or capability building.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:IADLS]] (IADLs prepare and support ADL performance — meal prep enables eating; managing medications enables health); [[HUMANITY:NEEDS]]: Health, Safety, Dignity (direct satisfaction targets); [[HUMANITY:RESOURCES]] (ADLs require time, energy, and often assistive tools or support)
  - **Requires:** Minimal [[HUMANITY:RESOURCES]] and [[HUMANITY:CAPABILITIES]] (basic autonomy and physical ability; assistive devices when ability is reduced)
  - **Enables:** Survival-level satisfaction of Health, Safety, and Dignity [[HUMANITY:NEEDS]]
  - **Disrupted by:** Severe [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (illness, exhaustion, depression); physical disability without accommodation; extreme resource scarcity

##### Instrumental Activities of Daily Living (IADLs)

ID: HUMANITY.ELEMENTS.ACTIVITIES.IADLS
TAGS: [[HUMANITY:IADLS]]

Tasks that help to satisfy [[HUMANITY:ADLS]] plus [[HUMANITY:NEEDS]] of **Inclusion**, including the following:

- preparing meals;
- housekeeping;
- home maintenance;
- shopping;
- coordinating transportation;
- using communication devices;
- managing medications; and,
- managing finances.

- **Examples**
  - **When a user describes struggling to keep up with bills, appointments, or groceries:** Cite [[HUMANITY:IADLS]] as the activity layer under strain; identify which [[HUMANITY:RESOURCES]] (time, energy, finances, skills) are insufficient.
  - **When a user asks how to help an elderly parent stay independent:** Cite [[HUMANITY:IADLS]] as the primary functional domain — which of these eight activities can the parent still manage, and which need support?
  - **When building a plan to improve daily functioning:** Systematically check which IADLs are working well and which are failing; each failed IADL typically threatens a specific need category (finance management → Safety; communication → Inclusion; meal prep → Health).

- **Boundaries / Scope**
  - **Includes:** The eight instrumental activities (meal prep, housekeeping, home maintenance, shopping, transportation, communication, medications, finances) that support ADL performance and enable Inclusion; the scaffolding layer of daily functioning above the survival floor.
  - **Excludes:** The five foundational self-care ADLs (see [[HUMANITY:ADLS]]); employment, education, or recreational activities beyond basic instrumental functions; clinical occupational therapy assessment.
  - **Primary purpose:** Identify the *instrumental functioning layer* — the activities that sustain daily life and enable participation. When IADLs break down, ADL performance and need satisfaction typically follow.

- **Decision Rules (IF/THEN)**
  - **IF** a user's basic needs are met (ADLs functioning) but daily life feels unmanageable, **THEN** systematically assess which IADLs are breaking down and why.
  - **IF** an IADL is failing, **THEN** identify the specific [[HUMANITY:RESOURCES]] or [[HUMANITY:CAPABILITIES]] deficit (e.g., finances failing → financial capability; communication failing → knowledge or tools).
  - **IF** building a recovery or support plan, **THEN** start with IADLs that most directly support unmet needs (meal prep for Health; managing finances for Safety; using communication devices for Inclusion).

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:ADLS]] (IADLs prepare the conditions for ADL success); [[HUMANITY:NEEDS]]: Health (meal prep, medications), Safety (finances, home maintenance), Inclusion (communication devices, transportation); [[HUMANITY:CAPABILITIES]] (many IADLs require specific capability types — finances → financial capability; communication → tools + knowledge)
  - **Requires:** More [[HUMANITY:RESOURCES]] and [[HUMANITY:CAPABILITIES]] than ADLs — particularly Knowledge, Skills, Tools, and Finances
  - **Enables:** Sustained ADL performance and Inclusion [[HUMANITY:NEEDS]] satisfaction; participation in social, economic, and community life
  - **Disrupted by:** Resource scarcity (time, energy, finances); capability gaps (lacking knowledge, skills, or tools); [[HUMANITY:DISCRIMINATION]] (barriers to accessing transportation, financial services, communication technology)

#### Limited Available Resources

ID: HUMANITY.ELEMENTS.RESOURCES
TAGS: [[HUMANITY:RESOURCES]]

Core inputs humans draw on to perform [[HUMANITY:ACTIVITIES]] that produce results meeting [[HUMANITY:NEEDS]]. These resources are constrained by availability: **time** and **energy** are finite and are spent as they are used; **integrity** is an alignment-and-trust resource that can compound through consistent choices but can be damaged quickly; and **[[HUMANITY:CAPABILITIES]]** are buildable multipliers—developed over time by investing time/energy with integrity—that increase what a person can achieve per unit of effort. (i.e., Autonomy + Abilities + Experiences + (Integrity[Discipline] + Tools) + (Skills + Relationships[Collaboration + Supplies]) + (Knowledge + Time + Energy) + (Mentors[Guidance + Accountability] + Finances) → Resources → Activities → Capacity)

- **Time**: Fixed, nonrenewable, always passing; the scarcest budgeting constraint.
  - *Tips*
    - Choose intentionally; reduce distractions.
    - Spend prime hours on highest-leverage work (hardest thinking, hardest conversations).
    - Prefer commitments that satisfy multiple needs at once (health + inclusion: walk with a friend).
    - Batch small tasks (errands, email) and avoid context switching.
    - Reduce "time leakage" (unplanned scrolling, fragmented multitasking) by shaping environment: notifications, app limits, physical cues.
    - Create slack: buffers between commitments; fewer simultaneous "must-do" projects.
    - Invest in systems (meal planning, routines, checklists) that permanently lower recurring time costs.
- **Energy**: Capacity to act (physical, cognitive, emotional); replenishable but limited day-to-day.
  - *Tips*
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Experiences + Capabilities[Abilities + Mentors[Guidance + Accountability] + Knowledge + Skills + Tools + Finances] → Health & Wellness → Energy
    - Protect the "basics": sleep consistency, movement, nutrition/hydration.
    - Design for recovery: breaks, downshifts, realistic pacing; treat burnout as a depletion spiral.
    - Reduce chronic drains: untreated pain, persistent conflict, chaotic finances, unsafe environments.
    - Match task type to energy type (creative work when fresh; admin when tired).
    - Use "minimum effective dose" habits (10–20 minutes of movement; simple meal defaults).
    - Automate or simplify recurring decisions to preserve mental energy.
- **Integrity**: Alignment between values, words, and actions; creates self-trust and social trust; fragile under violations.
  - *Tips*
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Experiences + Capabilities[Abilities + Mentors[Guidance + Accountability] + Knowledge + Skills + Tools + Finances] → Integrity
    - Keep promises small enough to keep; renegotiate early, not late.
    - Practice clear boundaries and honest expectations (especially around time/money).
    - Repair quickly when you miss: acknowledge, make amends, change the system that caused it.
    - Leverage integrity as a "trust multiplier": fewer check-ins, less defensiveness, smoother collaboration.
    - Use it to simplify decisions: values-based rules beat constant re-evaluation.
    - Invest it where compounding matters most (key relationships, your reputation, critical responsibilities).
- **[[HUMANITY:CAPABILITIES]]**
  - *Tips*
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Experiences + Capabilities[Abilities + Relationships[Collaboration + Supplies] + Mentors[Guidance + Accountability] + Knowledge + Skills + Tools + Finances] → Capabilities
    - Choose a small number of "keystone" capabilities to build (e.g., communication + budgeting + a career skill).
    - Practice deliberately (feedback loops), and maintain with light repetition (don't let skills/tools drift).
    - Protect against degradation: avoid neglect (atrophy), misalignment (wrong goals), and overcomplexity (too many tools/subscriptions).
    - Use capabilities to increase *output per hour* (templates, scripts, habits, checklists, delegating).
    - Prefer capabilities that transfer across life domains (communication improves work + family + community).
    - Periodically prune: drop low-ROI tools, skills, and commitments.

- **Examples**
  - **When a user is overwhelmed and can't figure out why:** Cite [[HUMANITY:RESOURCES]]: assess Time (are they overcommitted?), Energy (are they depleted?), and Integrity (are commitments creating friction?).
  - **When a user asks "where do I start to improve my life?":** Cite [[HUMANITY:RESOURCES]] as the input layer — stabilizing Time and Energy first gives the foundation for everything else.
  - **When explaining why someone who "tries hard" still fails to follow through:** Cite [[HUMANITY:RESOURCES]] depletion (often Energy or Time) as a likely structural cause before attributing it to character weakness or [[HUMANITY:TEMPTATIONS]].

- **Boundaries / Scope**
  - **Includes:** The three core limited inputs (Time, Energy, Integrity) plus [[HUMANITY:CAPABILITIES]] as a fourth buildable category; practical tips for managing each resource type; the heuristic model of resource → activity → capacity.
  - **Excludes:** The specific capabilities that amplify resource use (see [[HUMANITY:CAPABILITIES]]); the activities performed with resources (see [[HUMANITY:ACTIVITIES]]); the needs satisfied (see [[HUMANITY:NEEDS]]); financial, legal, or medical resource advice.
  - **Primary purpose:** Enable IF-LLM to identify the *input layer* of the NARM system — whether a person's difficulty is rooted in insufficient or depleted core resources rather than lack of motivation or capability.

- **Decision Rules (IF/THEN)**
  - **IF** a user describes chronic overwhelm, inability to follow through, or exhaustion, **THEN** assess [[HUMANITY:RESOURCES]] (Time, Energy, Integrity) before exploring [[HUMANITY:TEMPTATIONS]] or [[HUMANITY:CAPABILITIES]].
  - **IF** a user asks how to be more productive or effective, **THEN** start with resource management (protecting time and energy) before adding capability development.
  - **IF** integrity is fragile (broken promises, damaged trust, self-distrust), **THEN** prioritize integrity repair as a resource investment — it multiplies the value of time and energy.
  - **IF** resources are critically low, **THEN** reduce scope (fewer commitments), protect basics (sleep, food, safety), and build recovery before expanding activities.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:ACTIVITIES]] (resources are consumed by activities); [[HUMANITY:NEEDS]] (resources are ultimately invested to satisfy needs); [[HUMANITY:CAPABILITIES]] (capabilities amplify the yield of resources); [[HUMANITY:MOTIVATORS]] (motivators sustain the will to invest resources); [[HUMANITY:OODA]] (the OODA loop consumes time and energy at every step)
  - **Required by:** All [[HUMANITY:ACTIVITIES]] (ADLs and IADLs require at minimum time and energy); [[HUMANITY:OODA]] (requires time and energy to run); [[HUMANITY:MISSION]] performance
  - **Depleted by:** [[HUMANITY:TEMPTATIONS]] (especially Overcommitment, Immediate Gratification, Avoidance of Discomfort); [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (chronic unmet needs consume energy and attention); [[HUMANITY:DISCRIMINATION]] (creates barriers that cost additional resources to navigate)
  - **Replenished by:** Recovery activities (sleep, nutrition, movement); [[HUMANITY:COPING]] strategies; [[HUMANITY:INTERDEPENDENCE]] (shared resource access through community); deliberate resource management using the tips in this entry

##### Capabilities

ID: HUMANITY.ELEMENTS.RESOURCES.CAPABILITIES
TAGS: [[HUMANITY:CAPABILITIES]]

Buildable multipliers that improve efficiency and effectiveness when using [[HUMANITY:RESOURCES]] to perform [[HUMANITY:ACTIVITIES]] and meet [[HUMANITY:NEEDS]].

- **Autonomy**: *learnable ability* to [[HUMANITY:REGULATION]] (e.g., [[HUMANITY:MOTIVATORS]], [[HUMANITY:TEMPTATIONS]], [[HUMANITY:RESOURCES]], [[HUMANITY:ACTIVITIES]]), setting priorities and governing self; *available degree of control and discretion* over [[HUMANITY:RESOURCES]] and [[HUMANITY:ACTIVITIES]] of others and self (i.e., authority, freedom, power).
  - *Tips*
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Experiences + Capabilities[Abilities + Relationships[Collaboration + Supplies] + Mentors[Guidance + Accountability] + Knowledge + Skills + Tools + Finances] → Integrity → Autonomy → Capabilities
    - **Protect energy so decisions don't feel impossible**: consistent sleep/movement/nutrition, reducing chronic drains, and matching tasks to your energy type lowers the "cost" of choosing and acting.
    - **Invest in integrity to reduce coordination overhead**: when self-trust and social trust are high, you need fewer "check-ins," less rework, and fewer defensive cycles—making autonomy smoother to exercise.
    - **Strengthen relationships for support + opportunity**: supportive connections can provide help, accountability, and access to opportunities you can't create alone (which expands your option set).
    - **Grow knowledge + skills to widen your choice-set**: more competence and accurate information expands what you can realistically do (work, negotiate, solve problems, navigate systems).
    - **Use tools + systems to reduce recurring effort**: tools "extend capability," and systems like routines/checklists/meal planning reduce ongoing time costs—freeing discretionary time for self-directed choices.
    - **Build financial buffers to buy options**: emergency funds, lower debt burden, and "financial flexibility" can reduce forced choices and let you say "no," switch jobs, move, get training, etc.
- **Abilities**: Baseline aptitudes (physical, cognitive, emotional).
  - *Tips*
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Experiences + Capabilities[Abilities + Mentors[Guidance + Accountability] + Knowledge + Skills + Tools + Finances] → Health & Wellness → Abilities → Capabilities
    - Maintain health, practice, accommodations, realistic load.
    - Pick roles/tasks that reflect your strengths, your weaknesses, existing opportunities, and existing threats (i.e., risks).
      - Strengths + Opportunities = Leverage: Use strengths to maximize/seize opportunities.
      - Strengths + Threats = Defend: Use strengths to minimize/mitigate threats (i.e., risks).
      - Weaknesses + Opportunities = Collaborate: Partner with someone whose strengths are your weaknesses; use opportunities to overcome/minimize weaknesses.
      - Weaknesses + Threats = Avoid: minimize weaknesses and avoid threats (i.e., risks).
- **Relationships**: Connections with people who provide support, opportunity, belonging, accountability.
  - *Tips*
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Experiences + Capabilities[Abilities + Relationships] → Mentors (5-7 diverse) → Capabilities
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Experiences + Capabilities[Abilities + Mentors[Guidance + Accountability] + Knowledge + Skills + Tools + Finances] → Relationships → Capabilities
    - Maintain reliability, reciprocity, shared time, conflict repair.
    - Ask early, ask clearly, and offer value; "weak ties" help opportunity, "strong ties" help resilience.
- **Experiences**: Lived repetitive experiences that build judgment and confidence.
  - *Tips*
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Capabilities[Abilities + Relationships + (Knowledge + Skills + Tools + Finances + Mentors[Guidance + Accountability])] → Experiences → (Integrity + Autonomy + Abilities + Relationships + Knowledge + Skills + Tools + Finances) → Capabilities
    - Reflect (what worked/failed), capture lessons, seek varied repetitive experiences.
    - Turn experience into patterns/playbooks; avoid repeating avoidable mistakes.
- **Knowledge**: Accurate information and understanding.
  - *Tips*
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Experiences + Capabilities[Abilities + Mentors[Guidance + Accountability] + (Knowledge + Skills + Tools + Finances)] → Knowledge → (Autonomy + Skills) → Capabilities
    - Curate inputs; refresh what changes; verify important claims.
    - Apply in decisions; summarize into checklists/heuristics to reduce mental load.
- **Skills**: Trained, repeatable competencies (communication, writing, trades, coding, caregiving).
  - *Tips*
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Experiences + Capabilities[Abilities + Knowledge + Mentors[Guidance + Accountability] + (Skills + Tools + Finances)] → (Skills + Autonomy) → Capabilities
    - Maintain deliberate practice + feedback; small weekly repetitions prevent decay.
    - Focus on the "20% skills" that drive 80% outcomes in your life (often communication, planning, and domain skill).
- **Tools**: Physical/digital aids that extend capability (devices, apps, vehicles, appliances) and capacity.
  - *Tips* + Mentors[Guidance + Accountability]
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Experiences + Capabilities[Abilities + Knowledge + Skills + (Tools + Finances + Mentors[Guidance + Accountability])] → Tools → (Autonomy + Tools) → Capabilities
    - Keep them simple, secure, and functional (updates, backups, maintenance schedules).
    - Standardize and template; don't let tool choice become procrastination.
- **Finances**: Money, credit, and financial flexibility that buffer shocks and buy time/options.
  - *Tips*
    - Heuristic: (Time + Energy + Integrity[Discipline] + Autonomy) + Experiences + Relationships[Awareness + Sales + Collaboration + Supplies] + Capabilities[Abilities + Knowledge + Skills + Tools + (Finances + Mentors[Guidance + Accountability])] → (Finances + Autonomy) → Capabilities
    - Maintain spending plan, emergency fund, insurance coverage where appropriate, avoid high-interest spirals.
    - Buy back time (outsourcing key pain points), reduce stressors that drain energy, invest in high-ROI capability building (training, certifications, equipment).

- **Examples**
  - **When a user wants to improve their daily functioning:** Cite [[HUMANITY:CAPABILITIES]] to identify which of the eight capability types is most underdeveloped relative to their goals — then use the relevant Tips to build it.
  - **When a user feels stuck despite having time and energy:** Cite [[HUMANITY:CAPABILITIES]] — the multiplier may be the bottleneck (e.g., lacking Knowledge of how systems work, or Tools that would reduce effort).
  - **When explaining why two people with the same resources get very different results:** Cite [[HUMANITY:CAPABILITIES]] as the explanation — higher capability multipliers produce more need satisfaction per unit of time and energy invested.

- **Boundaries / Scope**
  - **Includes:** Eight buildable capability types (Autonomy, Abilities, Relationships, Experiences, Knowledge, Skills, Tools, Finances); practical tips for developing each; the heuristic model showing how capabilities interact and compound.
  - **Excludes:** Core limited resources (Time, Energy, Integrity) — see [[HUMANITY:RESOURCES]]; specific activities performed with capabilities (see [[HUMANITY:ACTIVITIES]]); clinical assessment of ability or disability; professional financial advice.
  - **Primary purpose:** Enable IF-LLM to identify *which specific multiplier* is the bottleneck in a user's situation — and to point toward the practical development pathway for that capability type.

- **Decision Rules (IF/THEN)**
  - **IF** a user has adequate time and energy but still can't meet their needs, **THEN** assess [[HUMANITY:CAPABILITIES]] as the likely bottleneck — which of the eight types is most limiting?
  - **IF** a user asks "how do I get better at [X]?", **THEN** identify the relevant capability type (usually Skills + Knowledge, supported by Relationships and Mentors) and apply the Tips.
  - **IF** a user wants to build long-term capacity, **THEN** suggest "keystone" capabilities (Autonomy, Relationships, Skills in communication and planning) that transfer across life domains.
  - **IF** a user's capabilities are adequate but results are poor, **THEN** reassess whether [[HUMANITY:RESOURCES]] (Time, Energy, Integrity) or [[HUMANITY:MOTIVATORS]] (drives and reasons to act) are the actual constraint.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:RESOURCES]] (capabilities amplify resource yield; the two together determine what a person can accomplish); [[HUMANITY:ACTIVITIES]] (capabilities determine how effectively activities are performed); [[HUMANITY:LESSONS]] (capabilities are built through applied learning from experience); [[HUMANITY:EXPERTS]] (experts are a primary source of capability development — knowledge, mentorship, and skill)
  - **Required by:** Complex [[HUMANITY:IADLS]] (many require specific capability types); [[HUMANITY:MISSION]] performance at higher effectiveness levels
  - **Built by:** Deliberate practice with feedback; investment of Time and Energy; [[HUMANITY:INTERDEPENDENCE]] (Relationships and Mentors are capability types themselves); [[HUMANITY:LESSONS]] application
  - **Depleted by:** Neglect (atrophy); misalignment with actual goals; overcomplexity; [[HUMANITY:DISCRIMINATION]] (restricting access to education, tools, financial systems, and relationship networks)

#### Motivators

ID: HUMANITY.ELEMENTS.MOTIVATORS
TAGS: [[HUMANITY:MOTIVATORS]]

Common motivators of humanity across our many, diverse communities throughout our history; support the efficient and consistent achievement of [[HUMANITY:NEEDS]] for self and others.

- Survival and Basic Needs (e.g. Physiological Needs)
  - Hydration and Nutrition
  - Shelter
  - Health
- Safety and Security
  - Physical Safety
  - Emotional Safety
  - Resource Security
    - Finances
    - Relationships
    - Integrity
    - Tools
    - Time
    - Experiences
    - Talents
    - Energy
- Social Connection and Belonging
  - Love and Relationships
    - Attachment and Emotional Bonds
  - Affiliation and Community
  - Acceptance
- Esteem and Recognition
  - Recognition and Success
  - Social Status and Influence
  - Respect from Others
  - Power
  - Self-Worth
- Autonomy and Freedom
  - Personal Freedom and Independence
  - Control
  - Mastery and Competence
  - Avoidance of Overwhelm
- Growth and Achievement
  - Purpose
    - Existential Fulfillment
      - Spiritual Fulfillment
      - Connection to the Transcendent
    - Moral and Ethical Alignment
      - Altruism and Compassion
      - Environmental and Social Ethics
    - Legacy and Contribution
  - Challenges
    - Cognitive and Intellectual Stimulation
      - Problem-Solving and Creativity
    - Physical Stimulation
  - Learning
- Pleasure and Enjoyment
  - Recreation
  - Aesthetic Experiences
  - Sensory Satisfaction
- Avoidance of Pain and Discomfort
  - Emotional Avoidance
  - Physical Avoidance
- Identity and Self-Expression
  - Personal Identity
  - Cultural and Social Identity
  - Role Fulfillment
- Avoidance of Uncertainty
  - Predictability
  - Information
- Relational and Interpersonal Dynamics
  - Reciprocity and Fairness
  - Power Dynamics
- Environmental and Contextual Preferences
  - Familiarity vs. Exploration
  - Simplicity vs. Complexity
- Time and Temporal Preferences
  - Immediate Gratification vs. Delayed Rewards
  - Routine vs. Novelty

- **Examples**
  - **When a user asks "why does my coworker always need to be in charge?":** Cite [[HUMANITY:MOTIVATORS]]: Esteem and Recognition (Power, Social Status) and Autonomy and Freedom (Control) as likely active motivators — not necessarily a character flaw.
  - **When a user struggles to maintain a new habit:** Cite [[HUMANITY:MOTIVATORS]] to identify which drives have been engaged (or are missing) for the habit; connect to [[HUMANITY:VALUES]] (Purpose, Persistence) for longer-horizon fuel when immediate motivators are insufficient.
  - **When explaining why different people respond to the same situation very differently:** Cite [[HUMANITY:MOTIVATORS]] as the variable — different active motivators produce different responses to identical circumstances.

- **Boundaries / Scope**
  - **Includes:** Common drives and energizing reasons that sustain human effort across diverse contexts; applicable across cultures with variation in expression; both approach motivators (toward reward) and avoidance motivators (away from harm).
  - **Excludes:** Universal structural requirements (see [[HUMANITY:NEEDS]]); values-based principles guiding how to act (see [[HUMANITY:VALUES]]); behavioral pulls toward harm (see [[HUMANITY:TEMPTATIONS]]) — though motivators can be hijacked into temptation patterns.
  - **Scope note:** Motivators explain *why someone acts* in a given moment; needs explain *what they universally require*; values explain *how they aspire to act*. All three are related but distinct.
  - **Primary purpose:** Enable IF-LLM to identify what is driving (or blocking) a person's effort in a specific context — and to connect that drive to more sustainable, values-aligned motivators when short-term motivators are insufficient or harmful.

- **Decision Rules (IF/THEN)**
  - **IF** a user asks "why does someone do [X]?" and the behavior seems puzzling, **THEN** cite [[HUMANITY:MOTIVATORS]] to identify the likely active drive; note that the same motivator can produce very different behaviors depending on context and resources.
  - **IF** a user is losing motivation for something important, **THEN** identify which motivators previously fueled the effort (Survival, Esteem, Purpose, Growth?) and which have weakened; connect to [[HUMANITY:VALUES]] for longer-term drive.
  - **IF** a motivator appears to be producing harmful behavior, **THEN** check whether it has been hijacked by [[HUMANITY:TEMPTATIONS]] (e.g., "Autonomy and Freedom" → "Avoidance of Discomfort" → procrastination or abandonment).
  - **IF** a user wants to build sustainable motivation, **THEN** prefer motivators rooted in Purpose, Growth, and Social Connection over those rooted in Avoidance of Pain — the latter create fragile, reactive motivation.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:NEEDS]] (motivators often arise from unmet or threatened needs); [[HUMANITY:VALUES]] (values provide longer-horizon motivational fuel beyond immediate drives); [[HUMANITY:TEMPTATIONS]] (motivators can be hijacked into temptation patterns when [[HUMANITY:REGULATION]] is low); [[HUMANITY:MISSION]] (the Mission is sustained by motivators — especially Purpose and Interdependence)
  - **Sustains:** Effort toward [[HUMANITY:ACTIVITIES]] (motivators are the energizing reason to begin and persist); [[HUMANITY:OODA]] loop cycling (motivators keep the loop running toward relevant aims)
  - **Depleted by:** Chronic unmet [[HUMANITY:NEEDS]] (especially Safety and Dignity deprivation); [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (especially Depression, Fatigue, Low Motivation); prolonged [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (Stagnation and Underachievement, Despair and Loss of Meaning)
  - **Rebuilt by:** Meeting baseline [[HUMANITY:NEEDS]] (especially Health and Safety); activating Purpose and Growth motivators through small wins; [[HUMANITY:INTERDEPENDENCE]] (community connection reactivates Social Connection and Belonging motivators); [[HUMANITY:COPING]] strategies that restore agency
