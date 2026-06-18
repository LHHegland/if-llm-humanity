# Humanity — Information-Following Large Language Model Knowledge (*if-llm-humanity.md*)

## File Header

- **Name:** Humanity — Information-Following Large Language Model Knowledge (*if-llm-humanity.md*)
- **Version:** 2026-06-17 04:26 UTC by [Lance Hegland](lance.hegland@gmail.com)
- **Last Reviewed:** 2026-06-13 02:54 UTC by [Lance Hegland](lance.hegland@gmail.com)
- **Owner:** [Lance Hegland](lance.hegland@gmail.com)

- **Purpose:** Empower an instruction-following large language model (IF-LLM) to help an average adult in the U.S. today to think more clearly, calmly, and fairly about real-life situations—especially under uncertainty—without turning the IF-LLM into a medical, legal, or moral authority. These use cases emphasize sensemaking, decision hygiene, and human dignity, while respecting autonomy and professional boundaries.
- **Audience:** Average, diverse people in the United States of America today.
- **Features**
  - Empowers how to think, not what to conclude.
  - Prioritizes fairness, safety, and clarity over speed or cleverness.
  - Provides structured OODA-based decision scaffolding for everyday situations.
  - Links human values to observable behaviors and literary examples for relatable illustration.
  - Grounds societal concerns in universal human needs and shared fallibility patterns.
  - Supports sensemaking across cultural and demographic diversity.
  - Maps ontological relationships across concepts to enable IF-LLM navigation and multi-step inference.
- **Scope**
  - **Covers:** Human psychology, social dynamics, behavioral patterns, universal human values, decision-making frameworks, coping strategies, and common societal concerns as observed across diverse U.S. communities.
  - User is not seeking diagnosis, legal rulings, or professional certification.
  - Use cases emphasize support, structure, and reflection, not command-and-control.
  - High-stakes situations still defer to professionals.
- **Use Cases**
  - **Supported:**
    - Personal decision support under uncertainty
    - Emotional regulation and coping (non-clinical)
    - Conflict de-escalation and communication prep
    - Sensemaking of complex or emotionally charged situations
    - Self-reflection and personal growth scaffolding
    - Life skills and daily functioning support
  - **Not Supported**
    - Not suitable for diagnosis, therapy, legal advice, or emergency response.
    - Not optimized for technical or domain-specific expertise.
    - Not for political advocacy, persuasion, or electoral recommendations.
    - Not a replacement for professional counseling, therapy, or spiritual direction.
    - Not for generating prescriptive behavioral health or treatment plans.
    - Not for population-level policy recommendations or regulatory guidance.

- **Dependencies (Required):** `if-llm-system-policies-processing.md`, `if-llm-humanity-index.md`, `if-llm-humanity.md`, `if-llm-humanity-experts.md`, `if-llm-humanity-fallibility.md`, `if-llm-humanity-narm.md`, `if-llm-humanity-ooda.md`, `if-llm-humanity-values.md`, `if-llm-humanity-values-1.md`, `if-llm-humanity-values-2.md`, `if-llm-humanity-values-3.md`, `if-llm-humanity-values-4.md`, `if-llm-humanity-values-5.md`
- **Stability:** Stable. Core entries, tag assignments, and namespace rules are intended to remain consistent across sessions. Silent reinterpretation of entries, tag reassignment, or scope expansion without an explicit Changelog entry is prohibited.
- **Known Gaps / Limitations**
  - `[[HUMANITY:RULES]]` is a stub entry (currently unpopulated); IF-LLM should fall back to `[[HUMANITY:LESSONS]]` and `[[HUMANITY:ELEMENTS]]` for relationship patterns until populated.
  - `if-llm-humanity-index.md` is referenced in the Domain Knowledge Index but does not currently exist; treat the inline Domain Knowledge Index in this file as authoritative.
  - Supplemental files `if-llm-humanity-fallibility.md`, `if-llm-humanity-narm.md`, and `if-llm-humanity-ooda.md` retain legacy TBD headers; their entry content is authoritative, but file-level metadata is incomplete pending header updates.
  - `if-llm-humanity-values.md` is 2,361+ lines; IF-LLM context windows may not load it in full — prioritize values explicitly referenced by canonical tag if truncation occurs.
  - Concerns list items are annotated at the category level for `[[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]` and `[[HUMANITY:TEMPTATIONS]]` mapping, but not at the individual sub-item level.
  - Disambiguation guidance for overlapping concepts is provided in the Index; it is not yet embedded within individual supplemental file entries.

- **Changelog**
  - 2026-06-17 07:50 UTC by [Lance Hegland](lance.hegland@gmail.com): Updated `Index` > `Domain Knowledge Index` to reflect split of `if-llm-humanity-values-4.md` containing 10 entries into two separate files as follows:
    - `if-llm-humanity-values-4.md` contains the 5 entries  `Justice` through `Persistence`
    - `if-llm-humanity-values-5.md` contains the 5 entries  `Courage` through `Hope`
  - 2026-06-17 04:26 UTC by [Lance Hegland](lance.hegland@gmail.com): Updated `Index` > `Domain Knowledge Index` to reflect split of `if-llm-humanity-values.md` containing 31 entries into four separate files with roughly 550 lines each as follows:
    - `if-llm-humanity-values-1.md` contains the 7 entries `Values` through `Open-Mindedness`
    - `if-llm-humanity-values-2.md` contains the 7 entries  `Perspective` through `Humility`
    - `if-llm-humanity-values-3.md` contains the 7 entries  `Prudence` through `Humor`
    - `if-llm-humanity-values-4.md` contains the 10 entries  `Justice` through `Hope`
  - 2026-06-13 04:15 UTC by [Lance Hegland](lance.hegland@gmail.com): Improved wording for index instructions.
  - 2026-06-13 07:51 UTC by [Lance Hegland](lance.hegland@gmail.com): Added Dependencies, Stability, Known Gaps/Limitations to File Header; expanded Features (7 items) and Scope (Covers statement); expanded Not Supported (6 items); added Concept Disambiguation section to Index; annotated [[HUMANITY:CONCERNS]] category headings with [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] and [[HUMANITY:TEMPTATIONS]] construct mappings.
  - 2026-06-13 02:54 UTC by [Lance Hegland](lance.hegland@gmail.com): Reviewed, fine-tuned, expanded [[HUMANITY:LESSONS]].
  - 2026-06-13 UTC by [Lance Hegland](lance.hegland@gmail.com): Expanded [[HUMANITY:RIGHTS]], [[HUMANITY:VISION]], and [[HUMANITY:MISSION]] with operational descriptions, relatable examples, and adjacent concept connections.
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

Refer to the list of domain knowledge file indexes for common topic references and canonical handles contained in `if-llm-humanity-index.md`.

Use with the following supplemental files to integrate knowledge subdomains mapped to the following common topic references and canonical handles (i.e., IDs and namespaced tags):

- `if-llm-system-policies-processing.md` → Processing Policies → SYS_POLICIES → [[SYS_POLICIES:ROOT]]
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
  - Courage → HUMANITY.ELEMENTS.VALUES.COURAGE → [[HUMANITY:COURAGE]]
  - Bravery → HUMANITY.ELEMENTS.VALUES.BRAVERY → [[HUMANITY:BRAVERY]]
  - Integrity → HUMANITY.ELEMENTS.VALUES.INTEGRITY → [[HUMANITY:INTEGRITY]]
  - Vitality → HUMANITY.ELEMENTS.VALUES.VITALITY → [[HUMANITY:VITALITY]]
  - Hope → HUMANITY.ELEMENTS.VALUES.HOPE → [[HUMANITY:HOPE]]

### Concept Disambiguation

Use these notes to select between partially overlapping concepts for precise IF-LLM retrieval and reasoning.

- **[[HUMANITY:FALLIBILITY]] vs. [[HUMANITY:TEMPTATIONS]] vs. [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]**
  - Use `[[HUMANITY:FALLIBILITY]]` when the focus is on the *human condition* — being inherently limited, imperfect, and prone to error (the "why we struggle" lens).
  - Use `[[HUMANITY:TEMPTATIONS]]` when the focus is on the *impulse or behavioral pattern* that increases harm risk — e.g., greed, avoidance, tribal thinking (the "what we are pulled toward" lens).
  - Use `[[HUMANITY:CONSEQUENCES_TEMPTATIONS]]` when the focus is on *outcomes already produced* by following temptations — e.g., broken trust, addiction, exploitation (the "what results" lens).
- **[[HUMANITY:MOTIVATORS]] vs. [[HUMANITY:VALUES]]**
  - Use `[[HUMANITY:MOTIVATORS]]` when the focus is on what *drives or sustains an individual's effort* — intrinsic drives, goals, and reasons to keep acting.
  - Use `[[HUMANITY:VALUES]]` when the focus is on *principles and practices* that guide ethical, effective behavior — what one aspires to do and how one aspires to act.
  - Note: Values can function as motivators, but motivators are not always values. When both apply, cite both.
- **[[HUMANITY:NEEDS]] vs. [[HUMANITY:CONCERNS]]**
  - Use `[[HUMANITY:NEEDS]]` when the focus is on *universal human requirements* for health, safety, dignity, and inclusion (the structural baseline).
  - Use `[[HUMANITY:CONCERNS]]` when the focus is on *contextual, situational, or societal threats* to those needs as observed in modern U.S. life.
- **[[HUMANITY:VISION]] vs. [[HUMANITY:MISSION]]**
  - Use `[[HUMANITY:VISION]]` when the focus is on the *long-horizon aspiration* — the world we are working toward.
  - Use `[[HUMANITY:MISSION]]` when the focus is on *present-moment action* — what we each do right now to move toward the Vision.

### Local Knowledge Index

The following is a list of this file's common topic references mapped to canonical handles.

- Humanity → HUMANITY → [[HUMANITY:ROOT]]
- Rules → HUMANITY.RULES → [[HUMANITY:RULES]]
- Elements → HUMANITY.ELEMENTS → [[HUMANITY:ELEMENTS]]
- Coping → HUMANITY.ELEMENTS.COPING → [[HUMANITY:COPING]]
- Concerns → HUMANITY.ELEMENTS.CONCERNS → [[HUMANITY:CONCERNS]]
- Lessons Learned → HUMANITY.ELEMENTS.LESSONS → [[HUMANITY:LESSONS]]
- Unalienable Rights → HUMANITY.ELEMENTS.RIGHTS → [[HUMANITY:RIGHTS]]
- Vision → HUMANITY.ELEMENTS.VISION → [[HUMANITY:VISION]]
- Mission → HUMANITY.ELEMENTS.MISSION → [[HUMANITY:MISSION]]

## Humanity

ID: HUMANITY
TAGS: [[HUMANITY:ROOT]]

Collective experiences of human beings across our many, widespread, diverse communities throughout our vast history.

### Rules

ID: HUMANITY.RULES
TAGS: [[HUMANITY:RULES]]

The most significant and common relationships among [[HUMANITY:ELEMENTS]] of [[HUMANITY:ROOT]] based on patterns identified within our collective [[HUMANITY:LESSONS]]. These relationships have been, and continue to be, identified across our many, widespread, diverse communities throughout our vast history. These relationships continue to be studied, analyzed, evaluated, refined, and applied to improve our collective [[HUMANITY:CAPABILITIES]].

No rules exist yet.

### Elements

ID: HUMANITY.ELEMENTS
TAGS: [[HUMANITY:ELEMENTS]]

The most significant and common elements of [[HUMANITY:ROOT]] based on patterns identified within our collective [[HUMANITY:LESSONS]]. These patterns have been, and continue to be, identified across our many, widespread, diverse communities throughout our vast history. These patterns continue to be studied, analyzed, evaluated, refined, and applied to improve our collective [[HUMANITY:CAPABILITIES]].

#### Coping

ID: HUMANITY.ELEMENTS.COPING
TAGS: [[HUMANITY:COPING]]

Options that often help reduce depression, distress, anxiety, and panic, identify recovery strategies, plus perform our [[HUMANITY:MISSION]] when people are experiencing difficulty efficiently and consistently accessing essential [[HUMANITY:RESOURCES]], performing [[HUMANITY:ACTIVITIES]], and satisfying [[HUMANITY:NEEDS]]; may help to identify and develop support networks and strategies to recover from effects of [[HUMANITY:CONCERNS]] and [[HUMANITY:TEMPTATIONS]], [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]], and [[HUMANITY:CONSEQUENCES_TEMPTATIONS]].

- Urgent Help
  - 911: If you're in life-threatening danger, call 911 or go to the nearest emergency room.
  - Suicide & Crisis Lifeline: Call or text 988.
  - Crisis Text Line: Text HOME to 741-741 to reach a trained crisis counselor.
  - If you are a veteran, contact the Veterans Crisis Line By calling 988 or texting 838255
  - Disaster Distress Helpline: If you have experienced a disaster, call or text 1-800-985-5990.
- Friends and Family: Reach out to a close friend or loved one.
- Community Leaders: Contact a minister, spiritual leader, or someone else in your community.
- Local Resource Lists
  - [Substance Abuse and Mental Health Services Administration (SAMHSA) Local Resources](https://www.samhsa.gov/find-help)
  - [Anxiety and Depression Association of America (ADAA) Local Resources](https://adaa.org/find-help) lists support groups, therapists, and other resources
- Professionals
  - Talk with a mental health professional.
  - Contact your primary doctor or other health care provider.
- Self-Help Options
  - [[HUMANITY:MISSION]]; remember that you are a vital member of our society plus critical to our [[HUMANITY:INTERDEPENDENCE]] and achieving our [[HUMANITY:VISION]].
  - The Four Agreements (Source: [The Four Agreements: A Practical Guide to Personal Freedom](https://www.amazon.com/Four-Agreements-Practical-Personal-Freedom/dp/1878424319) by Don Miguel Ruiz and published by Amber-Allen Publishing during 1997)
    - Be Impeccable with Your Word: Speak and act with integrity, avoid gossip, and use your words to spread truth and positivity.
    - Don't Take Anything Personally: Understand that others' actions and words are a reflection of their own reality, not yours.
    - Don't Make Assumptions: Communicate clearly and ask questions instead of making assumptions that lead to misunderstandings.
    - Always Do Your Best: Give your best effort in every situation, recognizing that your best will vary depending on circumstances.
  - Six Quick and Easy Daily Habits (Source: [The Happiness Advantage: How a Positive Brain Fuels Success in Work and Life](https://www.amazon.com/Happiness-Advantage-Principles-Psychology-Performance/dp/0307591549) written by Shawn Achor and published by Crown Currency during 2010)
    - Gratitudes: Take two minutes to write down three things that you're grateful for — or that made you smile — during the last 24 hours. They don't have to be huge. For example, seeing and feeling sunshine,  someone sharing a piece of gum, or enjoying a delicious meal. This helps to train our brains to focus on positive experiences.
    - The Doubler: Take two minutes to write about one of the experiences you're grateful for from the previous exercise. Just list as many details as you can about that experience during these two minutes: who was involved, where it happened, when it happened, what happened, how it happened, and why you were grateful or why you smiled. This helps us to train our brain by practicing positive thinking and optimism.
    - The Fun 15: Do 15 minutes of a fun cardio activity, like dancing, bike riding, or walking the dog.  This can help us boost our mood, energy, and overall mental well-being.
    - Meditation: Take a two-minute break to just concentrate on your breathing, practice mindfulness, or meditate. This helps us to reduce stress and increase focus.
    - Conscious Act of Kindness: Perform a kind act, like sending a short email or text thanking someone for something you are grateful for or sharing a cup of coffee with someone. This helps train our brain to practice kindness and gratitude, which helps us to strengthen social connections and increase happiness.
    - Nurture Social Connections: Engage in a meaningful interaction with friends, family, or colleagues. Share conversation over a beverage or meal or walk. This helps to strengthen our social connections and enhance our well-being.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:NEEDS]] (coping addresses difficulty satisfying needs); [[HUMANITY:RESOURCES]] (coping options depend on what resources are currently available); [[HUMANITY:ACTIVITIES]] (coping strategies are themselves activities); [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] and [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (coping responds to these outcomes); [[HUMANITY:MISSION]] (coping supports continued mission performance under strain); [[HUMANITY:OODA]] (coping often begins with re-orienting — slowing or resetting the loop); [[HUMANITY:CONCERNS]] (concerns frequently trigger the need for coping); [[HUMANITY:VALUES]] (effective coping draws on [[HUMANITY:COMPASSION]], [[HUMANITY:PERSISTENCE]], [[HUMANITY:WISDOM]], and [[HUMANITY:REGULATION]])
  - **Requires:** At least one accessible support option (urgent, professional, community, or self-help); awareness of current [[HUMANITY:RESOURCES]] to know which options are reachable; minimal [[HUMANITY:CAPABILITIES]] — especially the autonomy and relationships needed to act; sufficient [[HUMANITY:REGULATION]] to initiate help-seeking rather than avoiding it

#### Concerns

ID: HUMANITY.ELEMENTS.CONCERNS
TAGS: [[HUMANITY:CONCERNS]]

Common concerns of [[HUMANITY:ROOT]] observed across our many, diverse communities throughout our history along with relatable modern societal examples, not exhaustive; use examples when the user's request is about modern societal concerns or fears of [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]], [[HUMANITY:TEMPTATIONS]], and [[HUMANITY:CONSEQUENCES_TEMPTATIONS]].

- Economic Concerns *(→ [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]: financial security, shelter, health; [[HUMANITY:TEMPTATIONS]]: Greed, Immediate Gratification, Power and Control)*
  - Cost of Living
    - Inflation and rising prices
    - Housing affordability
    - Cost of healthcare and prescription drugs
    - Cost of education and student debt
  - Employment and Wages
    - Job security and layoffs
    - Wage stagnation
    - Workplace automation and job displacement
    - Gig economy and unstable employment
  - Wealth Inequality
    - Income disparity
    - Corporate influence on economy
    - Access to financial resources and opportunities
- Healthcare and Public Health *(→ [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]: health, safety, mental well-being; [[HUMANITY:TEMPTATIONS]]: Avoidance of Discomfort, Immediate Gratification)*
  - Access to Healthcare
    - High costs of medical care
    - Insurance coverage gaps
    - Rural healthcare shortages
  - Mental Health
    - Rising stress, anxiety, and depression
    - Lack of affordable mental health services
    - Social isolation and loneliness
  - Public Health Challenges
    - Opioid crisis and substance abuse
    - Infectious disease outbreaks
    - Chronic disease prevalence
- Social and Political Issues *(→ [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]: safety, dignity, inclusion; [[HUMANITY:TEMPTATIONS]]: Tribal Thinking, Power and Control, Confirmation Bias)*
  - Government and Political Stability
    - Partisan division and polarization
    - Trust in government and institutions
    - Election integrity and voting rights
  - Civil Rights and Equality
    - Racial and ethnic disparities
    - Gender equality and LGBTQ+ rights
    - Disability rights and accessibility
  - Crime and Public Safety
    - Gun violence and mass shootings
    - Police reform and criminal justice
    - Human trafficking and exploitation
- Environmental and Climate Concerns *(→ [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]: health, safety, resource access; [[HUMANITY:TEMPTATIONS]]: Greed, Immediate Gratification)*
  - Climate Change
    - Extreme weather events and natural disasters
    - Rising temperatures and sea levels
    - Carbon emissions and pollution
  - Resource Management
    - Water scarcity and contamination
    - Renewable energy transition
    - Food security and sustainable agriculture
  - Conservation and Biodiversity
    - Deforestation and habitat loss
    - Wildlife protection
    - Urbanization and environmental impact
- Education and Workforce Development *(→ [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]: financial security, inclusion, capabilities; [[HUMANITY:TEMPTATIONS]]: Greed, Social Comparison)*
  - K-12 Education
    - Quality of public schools
    - Teacher shortages and funding issues
    - Standardized testing and curriculum debates
  - Higher Education
    - Student loan debt and affordability
    - College access and graduation rates
    - Relevance of degrees to job market
  - Workforce Training
    - Skills gap and vocational education
    - Lifelong learning and career adaptability
    - STEM and technology education
- Technology and Digital Life *(→ [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]: safety, dignity, privacy; [[HUMANITY:TEMPTATIONS]]: Power and Control, Confirmation Bias)*
  - Privacy and Data Security
    - Online surveillance and data breaches
    - Social media influence on personal privacy
    - Cybercrime and identity theft
  - Misinformation and Media Influence
    - Spread of fake news and propaganda
    - Social media echo chambers
    - Censorship and freedom of speech
  - Artificial Intelligence and Automation
    - Ethical concerns of AI decision-making
    - Job displacement due to automation
    - Regulation of emerging technologies
- Family and Community Well-being *(→ [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]: health, safety, shelter, inclusion; [[HUMANITY:TEMPTATIONS]]: Overcommitment, Avoidance of Discomfort)*
  - Work-Life Balance
    - Overwork and burnout
    - Parental leave and childcare access
    - Family support services
  - Housing and Homelessness
    - Affordable housing shortages
    - Rising rent and homeownership challenges
    - Homelessness and support systems
  - Aging Population
    - Elder care and retirement security
    - Social isolation among seniors
    - Long-term healthcare and assisted living
- National and Global Security *(→ [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]: safety, health, stability; [[HUMANITY:TEMPTATIONS]]: Power and Control, Tribal Thinking)*
  - Domestic Security
    - Terrorism and extremist threats
    - Cybersecurity threats to infrastructure
    - Border security and immigration policies
  - Global Conflicts and Relations
    - International conflicts and wars
    - U.S. relations with foreign governments
    - Trade policies and economic sanctions
  - Public Safety Infrastructure
    - Emergency preparedness and response
    - Disaster relief and recovery efforts
    - Law enforcement and first responder support

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:NEEDS]] (concerns often represent active or perceived threats to health, safety, dignity, or inclusion); [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (concerns frequently reflect or produce unmet needs); [[HUMANITY:TEMPTATIONS]] and [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (many societal concerns are driven or worsened by patterns of temptation at scale); [[HUMANITY:FALLIBILITY]] (concerns recur in part because of shared human fallibility); [[HUMANITY:COPING]] (recognizing a concern activates coping); [[HUMANITY:LESSONS]] (many concerns echo patterns documented throughout lessons); [[HUMANITY:VISION]] (concerns represent the gap between current reality and the Vision); [[HUMANITY:RIGHTS]] (many concerns involve rights being threatened or denied)
  - **Requires:** Contextual awareness of which concerns apply to the user's specific situation, community, and [[HUMANITY:NEEDS]]; connection to [[HUMANITY:NEEDS]] to assess which concerns are most directly impactful; fairness discipline — applying [[HUMANITY:STEREOTYPES]] and [[HUMANITY:PREJUDICES]] awareness to avoid attributing concerns inequitably across groups

#### Lessons Learned

ID: HUMANITY.ELEMENTS.LESSONS
TAGS: [[HUMANITY:LESSONS]]

[[HUMANITY:ROOT]]'s most significant lessons learned that have been gathered, tested, refined, and shared throughout our vast history across our many, widespread, and diverse communities and societies — our [[HUMANITY:WISDOM]]. Critical lessons include the following:

- We are highly adaptable and resilient.
  - Humans can overcome challenges by adjusting to new environments and circumstances.
  - Resilience strengthens individuals and societies in times of crisis.
  - This offers powerful reasons to have [[HUMANITY:HOPE]] plus practice [[HUMANITY:PERSISTENCE]], [[HUMANITY:COMPASSION]], and [[HUMANITY:INTERDEPENDENCE]] for ourselves and others.
- We are fallible (i.e., [[HUMANITY:FALLIBILITY]]).
  - We experience and are highly vulnerable to [[HUMANITY:TEMPTATIONS]], which may cause us to experience [[HUMANITY:CONSEQUENCES_TEMPTATIONS]].
  - We are vulnerable to [[HUMANITY:STEREOTYPES]] and [[HUMANITY:PREJUDICES]], which may cause us to perform [[HUMANITY:DISCRIMINATION]].
- Each of us has [[HUMANITY:NEEDS]].
  - Each of us has various quantities of [[HUMANITY:RESOURCES]], including various [[HUMANITY:CAPABILITIES]], in addition to [[HUMANITY:MOTIVATORS]] that help us perform [[HUMANITY:ACTIVITIES]], such as [[HUMANITY:ADLS]] and [[HUMANITY:IADLS]], to meet our [[HUMANITY:NEEDS]].
  - If we cannot reasonably and consistently satisfy [[HUMANITY:NEEDS]], we likely experience [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]].
- When we are awake, we are constantly [[HUMANITY:OODA]], including [[HUMANITY:OBSERVE]], [[HUMANITY:SENSES]], [[HUMANITY:ORIENT]], [[HUMANITY:DECIDE]], [[HUMANITY:ACT]], then repeating.
- Everything is [[HUMANITY:INTERDEPENDENCE]]; each and every person, living being, and part of our environment, both now and throughout the future.
  - Nothing survives or thrives alone; mutualism, or at least commensalism, is essential.
  - Everything progresses through collaboration, shared resources, and resource exchange.
- [[HUMANITY:INTERDEPENDENCE]] requires [[HUMANITY:COMPASSION]] and empathy.
  - Understanding others' struggles leads to stronger relationships and communities.
  - Compassion improves problem-solving and conflict resolution.
- [[HUMANITY:INTERDEPENDENCE]] requires [[HUMANITY:PERSISTENCE]] and determination.
  - History shows that consistent effort leads to progress and success.
  - Movements for social change and innovation rely on perseverance.
- We require a balance of change and stability.
  - Societies evolve, but our core [[HUMANITY:VALUES]] remain constant.
  - Innovation thrives when grounded in foundational [[HUMANITY:WISDOM]].
- We can learn from our past experiences.
  - Studying history prevents repeated mistakes.
  - Ethical failures and injustices highlight necessary improvements.
- Individuals, families, communities, and societies thrive when the following occur:
  - individuals share and are committed to practicing [[HUMANITY:VALUES]].
  - individuals have [[HUMANITY:RIGHTS]] that are known, understood, respected, and protected.
  - individuals share and contribute to the [[HUMANITY:VISION]].
  - individuals share and are committed to the [[HUMANITY:MISSION]].
- [[HUMANITY:WISDOM]] is shared through storytelling and tradition.
  - Narratives carry cultural values, moral lessons, and survival strategies.
  - Stories reinforce shared identity and human connection.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:WISDOM]] (lessons are the cumulative source of wisdom); [[HUMANITY:VALUES]] (lessons are encoded in and reinforce values); [[HUMANITY:FALLIBILITY]] (many lessons arise from recognizing patterns of fallibility across history); [[HUMANITY:NEEDS]] (lessons teach how to more reliably satisfy needs); [[HUMANITY:INTERDEPENDENCE]] (lessons consistently reinforce interdependence as essential); [[HUMANITY:MISSION]] and [[HUMANITY:VISION]] (lessons guide mission performance and inform the vision); [[HUMANITY:OODA]] (lessons improve the quality and efficiency of the OODA loop over time); [[HUMANITY:COPING]] (lessons include coping strategies refined through history); [[HUMANITY:CONCERNS]] (concerns recur as lessons warn they will)
  - **Requires:** [[HUMANITY:WISDOM]] to recognize applicable lessons and apply them to present circumstances; [[HUMANITY:HUMILITY]] to acknowledge past mistakes as sources of learning; [[HUMANITY:PERSPECTIVE]] to recognize patterns across diverse communities and time periods; [[HUMANITY:PERSISTENCE]] to apply lessons consistently rather than only in easy moments; [[HUMANITY:INTERDEPENDENCE]] because lessons are gathered and validated across communities, not by individuals alone

#### Unalienable Rights

ID: HUMANITY.ELEMENTS.RIGHTS
TAGS: [[HUMANITY:RIGHTS]]

Equal opportunity to satisfy [[HUMANITY:NEEDS]]. Unalienable Rights exist for every person by virtue of being human — they are not earned, conditional, or revocable based on group membership, background, or circumstance. When rights are respected, people can access the [[HUMANITY:RESOURCES]] and perform the [[HUMANITY:ACTIVITIES]] required to meet their [[HUMANITY:NEEDS]] for Health, Safety, Dignity, and Inclusion. When rights are denied or violated — through [[HUMANITY:DISCRIMINATION]], structural inequality, or neglect — the predictable result is [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] that compound over time and impair [[HUMANITY:INTERDEPENDENCE]].

- **Example:** A parent working two jobs still has the right to safe housing, medical care, and to be treated with dignity at work — regardless of income, race, or immigration status. When any of those rights are denied, their ability to meet their own and their family's needs suffers directly.
- **Adjacent Concepts**
  - **Grounded in:** [[HUMANITY:NEEDS]] — rights are defined as equal opportunity to satisfy needs
  - **Realized through:** [[HUMANITY:VISION]] — the Vision is the world in which all rights are honored
  - **Threatened by:** [[HUMANITY:DISCRIMINATION]] — a primary mechanism by which rights are denied in practice
  - **Violation produces:** [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]
  - **Enabled by:** equitable access to [[HUMANITY:RESOURCES]]
- **Ontological Relationships**
  - **Related to:** [[HUMANITY:NEEDS]] (rights are defined as equal opportunity to satisfy needs); [[HUMANITY:VISION]] (rights are what the Vision protects); [[HUMANITY:MISSION]] (performing the Mission includes honoring rights); [[HUMANITY:DISCRIMINATION]] (discrimination is the primary behavioral threat to rights); [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (rights violations predictably produce unmet needs); [[HUMANITY:RESOURCES]] (equitable resource access is what makes rights real in practice); [[HUMANITY:LESSONS]] (history's lessons repeatedly document what happens when rights are denied); [[HUMANITY:FALLIBILITY]] (rights violations are often products of fallibility — especially [[HUMANITY:TEMPTATIONS]] like power-seeking and tribal thinking)
  - **Requires:** Recognition that all people share equal [[HUMANITY:NEEDS]] regardless of group membership; awareness of how [[HUMANITY:DISCRIMINATION]] operates to deny rights in practice; connection to [[HUMANITY:RESOURCES]] to identify what access is actually needed to satisfy needs; [[HUMANITY:JUSTICE]] and [[HUMANITY:FAIRNESS]] to identify violations and respond equitably

#### Vision

ID: HUMANITY.ELEMENTS.VISION
TAGS: [[HUMANITY:VISION]]

Each and every person, living being, and part of our environment has [[HUMANITY:RIGHTS]], both now and throughout the future. The Vision is the long-horizon picture of human flourishing that gives direction to our individual and collective efforts — a world where every person has an equal opportunity to satisfy their [[HUMANITY:NEEDS]] for Health, Safety, Dignity, and Inclusion, now and for generations to come. The Vision serves as a "north star" that orients the [[HUMANITY:MISSION]] and sustains [[HUMANITY:PERSISTENCE]] when daily challenges feel overwhelming. It reminds us that our individual actions — however small — are contributions to something larger than ourselves.

- **Example:** When a neighbor shovels an elderly resident's sidewalk, volunteers at a food pantry, or votes thoughtfully, they are contributing to a world where everyone has a fair shot at safety, health, dignity, and belonging — the Vision expressed through everyday choices.
- **Adjacent Concepts**
  - **Defined by:** [[HUMANITY:RIGHTS]] — the Vision is the state in which all rights are universally honored
  - **Pursued through:** [[HUMANITY:MISSION]] — the Mission is how the Vision is approached in daily life
  - **Informed by:** [[HUMANITY:LESSONS]] — the Vision reflects what humanity has collectively learned enables flourishing
  - **Requires:** [[HUMANITY:INTERDEPENDENCE]] — achieving the Vision depends on recognizing that everyone's well-being is connected
  - **Threatened by:** [[HUMANITY:DISCRIMINATION]], [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]], and unchecked [[HUMANITY:TEMPTATIONS]]
- **Ontological Relationships**
  - **Related to:** [[HUMANITY:RIGHTS]] (the Vision is the state in which all rights are honored); [[HUMANITY:MISSION]] (the Mission is how the Vision is approached daily); [[HUMANITY:NEEDS]] (the Vision centers on universal need satisfaction for all people); [[HUMANITY:LESSONS]] (the Vision is informed by what humanity has collectively learned enables flourishing); [[HUMANITY:CONCERNS]] (concerns represent the gap between current reality and the Vision); [[HUMANITY:VALUES]] (the Vision is grounded in shared values, especially [[HUMANITY:WISDOM]] and [[HUMANITY:INTERDEPENDENCE]])
  - **Requires:** [[HUMANITY:INTERDEPENDENCE]] — the Vision cannot be achieved alone; [[HUMANITY:PERSISTENCE]] — the Vision is long-horizon and requires sustained effort; [[HUMANITY:HOPE]] — to maintain belief that the Vision is achievable; [[HUMANITY:COMPASSION]] — to care about others' rights and needs as part of the shared Vision; [[HUMANITY:WISDOM]] — to understand what the Vision means in practice and navigate toward it

#### Mission

ID: HUMANITY.ELEMENTS.MISSION
TAGS: [[HUMANITY:MISSION]]

Simply do our best in each moment to practice our [[HUMANITY:WISDOM]], honor our [[HUMANITY:INTERDEPENDENCE]], plus practice [[HUMANITY:COMPASSION]] and [[HUMANITY:PERSISTENCE]] for others and ourselves given our unique circumstances and our [[HUMANITY:RESOURCES]]. The Mission translates the long-horizon [[HUMANITY:VISION]] into what is actionable right now — with whatever [[HUMANITY:RESOURCES]] each person actually has. "Do our best" explicitly acknowledges [[HUMANITY:FALLIBILITY]]: the Mission is not a demand for perfection, but a call to show up consistently, apply our [[HUMANITY:WISDOM]], care for each other, and keep going when it is hard. In practice, the Mission is performed through the [[HUMANITY:ACTIVITIES]] we choose each day — from how we treat a coworker, to how we ask for help, to how we raise our children.

- **Example:** A caregiver managing a sick family member while working full-time performs the Mission every time they show up with patience, asks for help when needed, and makes the best decisions they can with the time and energy they have — not because it is easy, but because they care and they keep going.
- **Adjacent Concepts**
  - **Moves toward:** [[HUMANITY:VISION]] — the Mission is how the Vision is pursued in daily life
  - **Expressed through:** [[HUMANITY:ACTIVITIES]] — specifically [[HUMANITY:ADLS]] and [[HUMANITY:IADLS]] — using available [[HUMANITY:RESOURCES]]
  - **Bounded by:** [[HUMANITY:RESOURCES]] — "our best" depends on current time, energy, and capabilities
  - **Acknowledges:** [[HUMANITY:FALLIBILITY]] — "do our best" is not perfection; the Mission remains within reach even when we fall short
  - **Operationalized by:** [[HUMANITY:WISDOM]], [[HUMANITY:COMPASSION]], [[HUMANITY:PERSISTENCE]], [[HUMANITY:INTERDEPENDENCE]]
  - **Enacted through:** [[HUMANITY:OODA]] — the OODA loop is the real-time mechanism by which the Mission is performed moment to moment
- **Ontological Relationships**
  - **Related to:** [[HUMANITY:VISION]] (the Mission pursues the Vision); [[HUMANITY:ACTIVITIES]] (the Mission is performed through activities); [[HUMANITY:OODA]] (OODA is the real-time mechanism of Mission performance); [[HUMANITY:RESOURCES]] (the Mission is bounded by available resources); [[HUMANITY:FALLIBILITY]] (the Mission acknowledges fallibility — "best" not "perfect"); [[HUMANITY:LESSONS]] (lessons guide Mission performance); [[HUMANITY:COPING]] (coping supports continued Mission performance under strain); [[HUMANITY:RIGHTS]] (performing the Mission includes honoring others' rights)
  - **Requires:** Awareness of current [[HUMANITY:RESOURCES]] — to calibrate what "best" means right now; [[HUMANITY:REGULATION]] — sufficient self-regulation to choose mission-aligned actions over temptation-driven ones; [[HUMANITY:OODA]] — the cognitive loop to sense, interpret, decide, and act; at least one accessible [[HUMANITY:ACTIVITY]] ([[HUMANITY:ADLS]] or [[HUMANITY:IADLS]]) to perform; at least one active [[HUMANITY:MOTIVATORS]] to sustain effort
