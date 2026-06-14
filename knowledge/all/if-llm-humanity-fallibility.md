# Humanity's Fallibility — Information-Following Large Language Model Knowledge (*if-llm-humanity-fallibility.md*)

## File Header

- **Name:** Humanity's Fallibility — Information-Following Large Language Model Knowledge (*if-llm-humanity-fallibility.md*)
- **Version:** 2026-06-14 07:42 UTC by [Lance Hegland](lance.hegland@gmail.com)
- **Last Reviewed:** 2026-06-14 07:42 UTC by [Lance Hegland](lance.hegland@gmail.com)
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

- **Dependencies (Required):** `if-llm-system-policies-processing.md`, `if-llm-humanity.md`, `if-llm-humanity-experts.md`, `if-llm-humanity-ooda.md`, `if-llm-humanity-narm.md`, `if-llm-humanity-values.md`
- **Stability:** Stable. Core entries, tag assignments, and namespace rules are intended to remain consistent across sessions. Silent reinterpretation of entries, tag reassignment, or scope expansion without an explicit Changelog entry is prohibited.
- **Known Gaps / Limitations**
  - TBD

- **Changelog**
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
- `if-llm-humanity-values.md`
  - Values → HUMANITY.ELEMENTS.VALUES → [[HUMANITY:VALUES]]
  - Wisdom → HUMANITY.ELEMENTS.VALUES.WISDOM → [[HUMANITY:WISDOM]]
  - Interdependence → HUMANITY.ELEMENTS.VALUES.INTERDEPENDENCE → [[HUMANITY:INTERDEPENDENCE]]
  - Love → HUMANITY.ELEMENTS.VALUES.LOVE → [[HUMANITY:LOVE]]
  - Critical Thinking → HUMANITY.ELEMENTS.VALUES.THINKING → [[HUMANITY:THINKING]]
  - Curiosity → HUMANITY.ELEMENTS.VALUES.CURIOSITY → [[HUMANITY:CURIOSITY]]
  - Open-Mindedness → HUMANITY.ELEMENTS.VALUES.OPENNESS → [[HUMANITY:OPENNESS]]
  - Perspective → HUMANITY.ELEMENTS.VALUES.PERSPECTIVE → [[HUMANITY:PERSPECTIVE]]
  - Love of Learning → HUMANITY.ELEMENTS.VALUES.LEARNING → [[HUMANITY:LEARNING]]
  - Creativity → HUMANITY.ELEMENTS.VALUES.CREATIVITY → [[HUMANITY:CREATIVITY]]
  - Compassion → HUMANITY.ELEMENTS.VALUES.COMPASSION → [[HUMANITY:COMPASSION]]
  - Temperance → HUMANITY.ELEMENTS.VALUES.TEMPERANCE → [[HUMANITY:TEMPERANCE]]
  - Mercy → HUMANITY.ELEMENTS.VALUES.MERCY → [[HUMANITY:MERCY]]
  - Humility → HUMANITY.ELEMENTS.VALUES.HUMILITY → [[HUMANITY:HUMILITY]]
  - Prudence → HUMANITY.ELEMENTS.VALUES.PRUDENCE → [[HUMANITY:PRUDENCE]]
  - Self-Regulation → HUMANITY.ELEMENTS.VALUES.REGULATION → [[HUMANITY:REGULATION]]
  - Transcendence → HUMANITY.ELEMENTS.VALUES.TRANSCENDENCE → [[HUMANITY:TRANSCENDENCE]]
  - Gratitude → HUMANITY.ELEMENTS.VALUES.GRATITUDE → [[HUMANITY:GRATITUDE]]
  - Purpose → HUMANITY.ELEMENTS.VALUES.PURPOSE → [[HUMANITY:PURPOSE]]
  - Appreciation of Excellence → HUMANITY.ELEMENTS.VALUES.EXCELLENCE → [[HUMANITY:EXCELLENCE]]
  - Humor → HUMANITY.ELEMENTS.VALUES.HUMOR → [[HUMANITY:HUMOR]]
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

Humans are inherently limited and fallible—we have [[HUMANITY:RESOURCES]], and we will sometimes miss commitments, make mistakes, or fall short. A healthier expectation is not “perfection,” but [[HUMANITY:HUMILITY]] (recognizing our limitations and being willing to acknowledge mistakes) and [[HUMANITY:INTEGRITY]] (keeping promises small enough to keep, and repairing quickly when we miss—acknowledge, make amends, and adjust the system). When another person makes a mistake, pause and practice [[HUMANITY:HUMILITY]] (remember I’m fallible too), [[HUMANITY:MERCY]] (respond with [[HUMANITY:COMPASSION]], not punishment), [[HUMANITY:GRATITUDE]] (notice their effort and intention), [[HUMANITY:HUMOR]] (keep things human plus defuse blame and shame), [[HUMANITY:FAIRNESS]] (judge with the same standard you’d want applied to you), and [[HUMANITY:LEADERSHIP]] (help repair, learn, and move forward—together).

##### Temptations

ID: HUMANITY.ELEMENTS.FALLIBILITY.TEMPTATIONS
TAGS: [[HUMANITY:TEMPTATIONS]]

Common temptations of [[HUMANITY:ROOT]] observed across our many, diverse communities throughout our history. Likely cause harm and risk to ability to efficiently and consistently satisfy [[HUMANITY:NEEDS]] for ourselves and and others. These are observed patterns, not moral judgments. Motivations are shaped by many, diverse factors (e.g., environment, disability, trauma, discrimination, access).

- Power and Control: Seeking dominance or authority at the expense of others.
  - Hoarding Limited Available Resources at others’ expense.
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
  - Neglect of Others’ Needs
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

##### Stereotypes

ID: HUMANITY.ELEMENTS.FALLIBILITY.STEREOTYPES
TAGS: [[HUMANITY:STEREOTYPES]]

**Stereotypes** are **generalized beliefs** about a group of people (e.g., “people from X are…”). They’re *cognitive* (thoughts) and can be positive, negative, or “neutral,” but they’re often oversimplified and inaccurate. Stereotypes distort expectations. As such, stereotypes are an example of our [[HUMANITY:FALLIBILITY]]. Stereotypes and [[HUMANITY:PREJUDICES]] are often a result of insufficient [[HUMANITY:PERSPECTIVE]] and [[HUMANITY:THINKING]]. Stereotypes usually emerge from [[HUMANITY:TEMPTATIONS]] (e.g., **Tribal Thinking**, **Social Comparison**, **Power and Control**). Stereotypes may be supported by  [[HUMANITY:TEMPTATIONS]]’s **Confirmation Bias**. [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (e.g., **Moral and Ethical Compromise**, **Inflexibility and Rigidity**, **Selfishness**) may also help to reinforce stereotypes. A person could hold stereotypes and [[HUMANITY:PREJUDICES]] without acting on them (i.e., without discriminating). However, stereotypes (in partnership with the [[HUMANITY:PREJUDICES]] they inspire) generally create significant risk of harm to “those people” (others) and ourselves during [[HUMANITY:ORIENT]] by impairing our [[HUMANITY:PERSPECTIVE]], [[HUMANITY:THINKING]], [[HUMANITY:COMPASSION]], and ultimately our [[HUMANITY:INTERDEPENDENCE]]. [[HUMANITY:STEREOTYPES]] often contribute to the emergence of [[HUMANITY:PREJUDICES]]. [[HUMANITY:DISCRIMINATION]] often contributes to the emergence and reinforcement of [[HUMANITY:STEREOTYPES]] and [[HUMANITY:PREJUDICES]]. Stereotypes (in partnership with the [[HUMANITY:PREJUDICES]] they inspire) reduce our [[HUMANITY:MOTIVATORS]] and likelihood of using our [[HUMANITY:RESOURCES]] and likelihood of performing [[HUMANITY:ACTIVITIES]] to help satisfy the [[HUMANITY:NEEDS]] of “those people”, thereby impairing their ability to avoid [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]], while simultaneously limiting our [[HUMANITY:INTERDEPENDENCE]]. Stereotypes likely impair our consistent and efficient performance of our [[HUMANITY:MISSION]], which impairs our contributions to our [[HUMANITY:VISION]], thereby increasing risks and harms to the [[HUMANITY:RIGHTS]] of ourselves and others. Ultimately, stereotypes typically impair the intentional and consistent practice of many [[HUMANITY:VALUES]] (e.g., [[HUMANITY:THINKING]], [[HUMANITY:PERSPECTIVE]], [[HUMANITY:OPENNESS]], [[HUMANITY:CURIOSITY]], [[HUMANITY:LEARNING]], [[HUMANITY:LOVE]], [[HUMANITY:MERCY]], [[HUMANITY:REGULATION]], [[HUMANITY:PRUDENCE]], [[HUMANITY:HUMILITY]], [[HUMANITY:TEMPERANCE]], [[HUMANITY:HUMOR]], [[HUMANITY:GRATITUDE]], [[HUMANITY:PURPOSE]], [[HUMANITY:FAIRNESS]], [[HUMANITY:JUSTICE]], [[HUMANITY:CITIZENSHIP]], [[HUMANITY:LEADERSHIP]], [[HUMANITY:INTEGRITY]], [[HUMANITY:VITALITY]], [[HUMANITY:TRANSCENDENCE]], [[HUMANITY:COMPASSION]], [[HUMANITY:INTERDEPENDENCE]], [[HUMANITY:WISDOM]]).

##### Prejudices

ID: HUMANITY.ELEMENTS.FALLIBILITY.PREJUDICES
TAGS: [[HUMANITY:PREJUDICES]]

**Prejudices** are **pre-judgments or attitudes** (usually negative) toward a person or group, often based on [[HUMANITY:STEREOTYPES]] rather than direct knowledge.  They’re *affective* (feelings/evaluations), such as dislike, fear, or distrust. Prejudices generally create significant risk of harm to “those people” (others) and ourselves during [[HUMANITY:ORIENT]] by impairing our [[HUMANITY:PERSPECTIVE]], [[HUMANITY:THINKING]], [[HUMANITY:COMPASSION]], and ultimately our [[HUMANITY:INTERDEPENDENCE]]. Prejudices reduce our [[HUMANITY:MOTIVATORS]] and likelihood of using our [[HUMANITY:RESOURCES]] and likelihood of performing [[HUMANITY:ACTIVITIES]] to help satisfy the [[HUMANITY:NEEDS]] of “those people”, thereby impairing their ability to avoid [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]], while simultaneously limiting our [[HUMANITY:INTERDEPENDENCE]]. [[HUMANITY:STEREOTYPES]] often contribute to the emergence of prejudices. Prejudices often lead to [[HUMANITY:DISCRIMINATION]]. However, a person could hold [[HUMANITY:STEREOTYPES]] and prejudices without acting on them (i.e., without discriminating). Prejudices impair the intentional inconsistent practice of many [[HUMANITY:VALUES]] (e.g., [[HUMANITY:THINKING]], [[HUMANITY:PERSPECTIVE]], [[HUMANITY:OPENNESS]], [[HUMANITY:CURIOSITY]], [[HUMANITY:LEARNING]], [[HUMANITY:LOVE]], [[HUMANITY:MERCY]], [[HUMANITY:REGULATION]], [[HUMANITY:PRUDENCE]], [[HUMANITY:HUMILITY]], [[HUMANITY:TEMPERANCE]], [[HUMANITY:HUMOR]], [[HUMANITY:GRATITUDE]], [[HUMANITY:PURPOSE]], [[HUMANITY:FAIRNESS]], [[HUMANITY:JUSTICE]], [[HUMANITY:CITIZENSHIP]], [[HUMANITY:LEADERSHIP]], [[HUMANITY:INTEGRITY]], [[HUMANITY:VITALITY]], [[HUMANITY:TRANSCENDENCE]], [[HUMANITY:COMPASSION]], [[HUMANITY:INTERDEPENDENCE]], [[HUMANITY:WISDOM]]). Prejudices impair our consistent and efficient performance of our [[HUMANITY:MISSION]], which impairs our contributions to our [[HUMANITY:VISION]], thereby increasing risks and harms to the [[HUMANITY:RIGHTS]] of ourselves and others. [[HUMANITY:DISCRIMINATION]] may help to reinforce prejudices. Prejudices are often a result of insufficient [[HUMANITY:PERSPECTIVE]] and [[HUMANITY:THINKING]]; examples of our [[HUMANITY:FALLIBILITY]]. [[HUMANITY:STEREOTYPES]] and prejudices usually emerge from and are reinforced by [[HUMANITY:TEMPTATIONS]] (e.g., **Social Comparison**, **Tribal Thinking**, **Power and Control**). [[HUMANITY:STEREOTYPES]] and prejudices may be supported by [[HUMANITY:TEMPTATIONS]]’s **Confirmation Bias**. [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (e.g., **Moral and Ethical Compromise**, **Inflexibility and Rigidity**, **Selfishness**) may also help to reinforce [[HUMANITY:STEREOTYPES]] and prejudices.

##### Discrimination

ID: HUMANITY.ELEMENTS.FALLIBILITY.DISCRIMINATION
TAGS: [[HUMANITY:DISCRIMINATION]]

**Discrimination** is **unequal treatment or unfair actions** toward people based on group membership (race, gender, religion, disability, etc.). It’s *behavioral* (what someone does) and can be individual (one person), institutional (policies/practices), or structural (system-wide patterns). [[HUMANITY:STEREOTYPES]] and [[HUMANITY:PREJUDICES]] affect [[HUMANITY:ORIENT]], which affects [[HUMANITY:DECIDE]], which results in discrimination during [[HUMANITY:ACT]]. Discrimination is a result of our examples of our [[HUMANITY:FALLIBILITY]]. The resulting discrimination creates real-world unequal outcomes and harms (e.g.,  [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]], [[HUMANITY:CONSEQUENCES_TEMPTATIONS]]). Discrimination may reinforce [[HUMANITY:STEREOTYPES]] and [[HUMANITY:PREJUDICES]] (e.g., treating a group unfairly can be used to “justify” biased beliefs). Discrimination does not require [[HUMANITY:STEREOTYPES]] or [[HUMANITY:PREJUDICES]]; someone might discriminate due to **rules/incentives/social pressure** even without strong personal [[HUMANITY:PREJUDICES]]. Discrimination is the likely reduction of using our [[HUMANITY:RESOURCES]] and likelihood of performing [[HUMANITY:ACTIVITIES]] to help satisfy the [[HUMANITY:NEEDS]] of “those people”, thereby impairing their ability to avoid [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]], while simultaneously limiting our [[HUMANITY:INTERDEPENDENCE]]. Discrimination limits the intentional and consistent practice of many [[HUMANITY:VALUES]] (e.g., [[HUMANITY:THINKING]], [[HUMANITY:PERSPECTIVE]], [[HUMANITY:OPENNESS]], [[HUMANITY:CURIOSITY]], [[HUMANITY:LEARNING]], [[HUMANITY:LOVE]], [[HUMANITY:MERCY]], [[HUMANITY:REGULATION]], [[HUMANITY:PRUDENCE]], [[HUMANITY:HUMILITY]], [[HUMANITY:TEMPERANCE]], [[HUMANITY:HUMOR]], [[HUMANITY:GRATITUDE]], [[HUMANITY:PURPOSE]], [[HUMANITY:FAIRNESS]], [[HUMANITY:JUSTICE]], [[HUMANITY:CITIZENSHIP]], [[HUMANITY:LEADERSHIP]], [[HUMANITY:INTEGRITY]], [[HUMANITY:VITALITY]], [[HUMANITY:TRANSCENDENCE]], [[HUMANITY:COMPASSION]], [[HUMANITY:INTERDEPENDENCE]], [[HUMANITY:WISDOM]]). Discrimination limits consistent and efficient performance of our [[HUMANITY:MISSION]], which impairs our contributions to our [[HUMANITY:VISION]], thereby increasing risks and harms to the [[HUMANITY:RIGHTS]] of ourselves and others. [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (e.g., **Selfishness**, **Moral and Ethical Compromise**, **Inflexibility and Rigidity**, **Exploitation and Manipulation**, **Aggression and Violence**) may also contribute to more frequent and more severe discrimination.
