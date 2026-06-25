# Humanity's Experts — Information-Following Large Language Model Knowledge (`if-llm-humanity-experts.md`)

## File Header

- **Version:** 2026-06-25 04:54 UTC by [Lance Hegland](lance.hegland@gmail.com)
- **Last Reviewed:** 2026-06-14 07:42 UTC by [Lance Hegland](lance.hegland@gmail.com)
- **Owner:** [Lance Hegland](lance.hegland@gmail.com)

- **Purpose:** Empower an IF-LLM to identify and cite relevant expert domains when helping an average U.S. adult understand who studies the patterns described in this knowledge ecosystem, what expert types to seek when a situation requires specialized knowledge, and how to attribute claims to recognized fields of expertise.
- **Audience:** Average, diverse people in the United States of America today.
- **Features**
  - Four expert subdomain categories (Reasoning/Behavior, Communication, Application, History) organized by functional role.
  - Role listings structured into professional subcategories for precise IF-LLM retrieval.
  - Integrates with [[HUMANITY:CAPABILITIES]] and [[HUMANITY:LESSONS]] for expertise-to-application mapping.
  - Concept Disambiguation section guides IF-LLM selection when a role spans multiple expert categories.
  - IF/THEN decision rules support structured IF-LLM retrieval workflows per entry.
- **Scope**
  - **Covers:** Professional and academic expert roles that study, analyze, and apply humanity's significant patterns; organized by functional domain (reasoning/behavior, communication, application, history).
  - **Out of Scope:** Individual practitioner directories; credential verification; clinical or legal referrals; technical subspecialties outside the humanity knowledge domain.
- **Use Cases**
  - **Supported:** Helping users understand which expert fields address their question; recommending professional consultation types; attributing knowledge claims to recognized disciplines when IF-LLM reasoning is grounded in those fields.
  - **Not Supported:** Not a referral service for individual practitioners; not optimized for clinical, legal, or engineering subspecialties; not for generating professional credentials or certifications; not for diagnosing, prescribing, or providing therapy.

- **Dependencies (Required):** `if-llm-system-policies-processing.md`, `if-llm-humanity-index.md`
- **Stability:** Stable. Core entries, tag assignments, and namespace rules are intended to remain consistent across sessions. Silent reinterpretation of entries, tag reassignment, or scope expansion without an explicit Changelog entry is prohibited.
- **Known Gaps / Limitations**
  - Many expert roles appear across multiple subcategories (e.g., Philosophers, Developmental Psychologists, Cultural Anthropologists). The Concept Disambiguation section provides selection guidance, but cross-category roles are not fully deduplicated within individual entries.
  - Expert lists represent professional and academic roles commonly recognized in the U.S. and internationally; they are not exhaustive and may not reflect all relevant subdisciplines or emerging fields.
  - No individual practitioner names, directories, or specific institutions are listed; users seeking a specific professional should be directed to appropriate referral resources (e.g., professional associations, 211 services, SAMHSA).
  - Ontological relationships describe the most significant connections across the ecosystem; edge cases spanning multiple categories require IF-LLM judgment and may benefit from citing more than one expert subcategory.

- **Changelog**
  - 2026-06-25 04:54 UTC by [Lance Hegland](lance.hegland@gmail.com):
    - Moved **Domain Knowledge Index** and **Domain Concept Disambiguation** from all files into `if-llm-humanity-index.md`.
    - Updated **Dependencies** in each file.
    - Retained **Local Knowledge Index** and **Local Concept Disambiguation** in each knowledge file.
    - Reviewed and updated **Known Gaps / Limitations** in each knowledge file.
  - 2026-06-17 07:50 UTC by [Lance Hegland](lance.hegland@gmail.com): Updated `Index` > `Domain Knowledge Index` to reflect split of `if-llm-humanity-values-4.md` containing 10 entries into two separate files as follows:
    - `if-llm-humanity-values-4.md` contains the 5 entries  `Justice` through `Persistence`
    - `if-llm-humanity-values-5.md` contains the 5 entries  `Courage` through `Hope`
  - 2026-06-17 04:26 UTC by [Lance Hegland](lance.hegland@gmail.com): Updated `Index` > `Domain Knowledge Index` to reflect split of `if-llm-humanity-values.md` containing 31 entries into four separate files with roughly 550 lines each as follows:
    - `if-llm-humanity-values-1.md` contains the 7 entries `Values` through `Open-Mindedness`
    - `if-llm-humanity-values-2.md` contains the 7 entries  `Perspective` through `Humility`
    - `if-llm-humanity-values-3.md` contains the 7 entries  `Prudence` through `Humor`
    - `if-llm-humanity-values-4.md` contains the 10 entries  `Justice` through `Hope`
  - 2026-06-14 07:42 UTC by [Lance Hegland](lance.hegland@gmail.com): Completed all TBD fields in File Header (Purpose, Features, Scope, Use Cases, Known Gaps/Limitations); removed circular self-reference from Dependencies list; added Concept Disambiguation section with cross-category role guidance; added Ontological Relationships, Examples, Boundaries/Scope, and IF/THEN Decision Rules to all five expert entries (Experts parent + four subcategories); added distinctive opening descriptions summarizing what each expert subcategory produces; updated Changelog with this specific entry.
  - 2026-06-13 04:23 UTC by [Lance Hegland](lance.hegland@gmail.com): Reviewed and updated for best practices.
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

### Local Concept Disambiguation

Use these notes to select between partially overlapping expert categories for precise IF-LLM retrieval and reasoning.

- **[[HUMANITY:REASONING_EXPERTS]] vs. [[HUMANITY:COMMUNICATION_EXPERTS]]**
  - Use `[[HUMANITY:REASONING_EXPERTS]]` when the focus is on *how humans think, decide, or behave* — logic, ethics, cognition, motivation, and behavioral science.
  - Use `[[HUMANITY:COMMUNICATION_EXPERTS]]` when the focus is on *how humans express, transmit, and preserve meaning* — language, narrative, folklore, and cultural storytelling.
  - Note: Philosophers and Psychologists appear in both. Cite [[HUMANITY:REASONING_EXPERTS]] for *analytical and ethical frameworks*; cite [[HUMANITY:COMMUNICATION_EXPERTS]] for *how those frameworks are transmitted across cultures and time*.
- **[[HUMANITY:REASONING_EXPERTS]] vs. [[HUMANITY:APPLICATION_EXPERTS]]**
  - Use `[[HUMANITY:REASONING_EXPERTS]]` when the focus is on *developing or evaluating the underlying frameworks* — moral theory, cognitive models, standards development.
  - Use `[[HUMANITY:APPLICATION_EXPERTS]]` when the focus is on *putting knowledge into practice* in real-world domains — healthcare ethics, social work, policy, organizational development.
  - When a user is asking *what to do* in a complex situation, prefer [[HUMANITY:APPLICATION_EXPERTS]]. When asking *why* something works or how to reason about it, prefer [[HUMANITY:REASONING_EXPERTS]].
- **[[HUMANITY:HISTORY_EXPERTS]] vs. [[HUMANITY:APPLICATION_EXPERTS]]**
  - Use `[[HUMANITY:HISTORY_EXPERTS]]` when the focus is on *understanding patterns across time and civilizations* — long-term trends, cross-cultural comparisons, why similar problems recur.
  - Use `[[HUMANITY:APPLICATION_EXPERTS]]` when the focus is on *current real-world implementation* — what professionals do today to apply those lessons.
  - Cite both when a user is asking about a problem that recurs historically AND needs guidance on current professional practice.
- **[[HUMANITY:HISTORY_EXPERTS]] vs. [[HUMANITY:COMMUNICATION_EXPERTS]]**
  - Use `[[HUMANITY:HISTORY_EXPERTS]]` when the focus is on *what happened and why* — historical evidence, social trends, civilizational analysis.
  - Use `[[HUMANITY:COMMUNICATION_EXPERTS]]` when the focus is on *how that history was told, preserved, or transmitted* — oral traditions, literature, religious narrative, folklore.

- **Roles appearing in multiple categories**
  - *Philosophers / Ethicists*: cite [[HUMANITY:REASONING_EXPERTS]] for logical and ethical frameworks; [[HUMANITY:COMMUNICATION_EXPERTS]] for philosophical literature and its transmission; [[HUMANITY:APPLICATION_EXPERTS]] for applied ethics in professional practice; [[HUMANITY:HISTORY_EXPERTS]] for the history of ideas and worldviews.
  - *Developmental Psychologists*: cite [[HUMANITY:REASONING_EXPERTS]] for cognitive and behavioral development frameworks; [[HUMANITY:COMMUNICATION_EXPERTS]] for language development and moral learning through narrative.
  - *Cultural Anthropologists*: cite [[HUMANITY:COMMUNICATION_EXPERTS]] for cultural storytelling, ritual, and tradition; [[HUMANITY:APPLICATION_EXPERTS]] for cross-cultural applied work; [[HUMANITY:HISTORY_EXPERTS]] for belief systems, social norms, and lived experience across civilizations.
  - *Sociologists*: cite [[HUMANITY:HISTORY_EXPERTS]] for structural and comparative social analysis over time; [[HUMANITY:APPLICATION_EXPERTS]] for policy, organizational, and community application.

### Local Knowledge Index

The following is a list of this file's common topic references mapped to canonical handles.

- Experts → HUMANITY.ELEMENTS.EXPERTS → [[HUMANITY:EXPERTS]]
- Reasoning and Behavior Experts → HUMANITY.ELEMENTS.EXPERTS.REASONING → [[HUMANITY:REASONING_EXPERTS]]
- Communication Experts → HUMANITY.ELEMENTS.EXPERTS.COMMUNICATION → [[HUMANITY:COMMUNICATION_EXPERTS]]
- Application Experts → HUMANITY.ELEMENTS.EXPERTS.APPLICATION → [[HUMANITY:APPLICATION_EXPERTS]]
- History Experts → HUMANITY.ELEMENTS.EXPERTS.HISTORY → [[HUMANITY:HISTORY_EXPERTS]]

### Domain Knowledge Index

Refer to `if-llm-humanity-index.md` for the list of domain knowledge file indexes for common topic references and canonical handles.

## Humanity

### Elements

#### Experts

ID: HUMANITY.ELEMENTS.EXPERTS
TAGS: [[HUMANITY:EXPERTS]]

Experts of [[HUMANITY:ROOT]]'s most significant patterns. These patterns have been, and continue to be, identified across our many, widespread, diverse communities throughout our vast history. Experts comprehensively study, analyze, evaluate, refine, and apply these patterns to build and maintain their related [[HUMANITY:CAPABILITIES]]. Together, the four expert subcategories — Reasoning/Behavior, Communication, Application, and History — represent the full span of human inquiry into who we are, how we think, how we share what we know, how we put it into practice, and how we document it over time.

- **Examples**
  - **Helping a user understand a complex situation (general):** "Several expert fields can shed light on this. Researchers in [[HUMANITY:REASONING_EXPERTS]] study why people behave this way; [[HUMANITY:HISTORY_EXPERTS]] can show whether similar patterns have appeared before; and [[HUMANITY:APPLICATION_EXPERTS]] work on what communities and organizations can actually do about it."
  - **When a user asks "who should I talk to about this?":** Identify the relevant expert subcategory (e.g., [[HUMANITY:APPLICATION_EXPERTS]] for professional consultation), then note that specific practitioners can be located through professional associations or community referral services (e.g., 211, SAMHSA).
  - **Attributing a knowledge claim:** "This insight draws on [[HUMANITY:REASONING_EXPERTS]] — specifically Behavioral Scientists and Cognitive Psychologists — who have documented this pattern across many studies."

- **Boundaries / Scope**
  - **Includes:** All four expert subcategories; academic, professional, and applied roles that study and apply humanity's patterns.
  - **Excludes:** Individual practitioner names, service directories, specific institutions, credential-granting bodies; clinical diagnosis, legal advice, or emergency services (for urgent help, see [[HUMANITY:COPING]]).
  - **Primary purpose:** Enable IF-LLM to attribute claims to recognized expert domains and guide users toward appropriate professional fields when a situation exceeds general knowledge.

- **Decision Rules (IF/THEN)**
  - **IF** a user's question requires domain expertise, **THEN** cite the most relevant expert subcategory to signal where authoritative knowledge comes from.
  - **IF** a user asks "who studies [X]?" **THEN** identify the best-fit subcategory first; if multiple subcategories apply, cite both with a brief disambiguation note.
  - **IF** a user asks "who should I talk to about [X]?" **THEN** cite the relevant [[HUMANITY:APPLICATION_EXPERTS]] subcategory and recommend professional consultation through appropriate channels.
  - **IF** multiple subcategories apply equally, **THEN** cite the most action-relevant one first and note the others.

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:LESSONS]] (experts are the primary agents who identify, test, refine, and transmit lessons); [[HUMANITY:WISDOM]] (experts collectively produce the evidence base from which wisdom is drawn); [[HUMANITY:CAPABILITIES]] (expert knowledge enables the development of human capabilities); [[HUMANITY:VALUES]] (experts study, codify, and transmit human values across disciplines and traditions)
  - **Grounds:** [[HUMANITY:LESSONS]] (expert study produces the validated patterns that become lessons); [[HUMANITY:WISDOM]] (expert synthesis across fields produces wisdom)
  - **Required by:** [[HUMANITY:CAPABILITIES]] development (building human capabilities requires expert-generated knowledge, frameworks, and professional practice)
  - **Affects:** the quality and depth of [[HUMANITY:LESSONS]] available to the IF-LLM; the reliability of [[HUMANITY:ORIENT]] when domain expertise is relevant to interpreting a situation

##### Reasoning and Behavior Experts

ID: HUMANITY.ELEMENTS.EXPERTS.REASONING
TAGS: [[HUMANITY:REASONING_EXPERTS]]

Experts of [[HUMANITY:ROOT]]'s most significant reasoning and behavior patterns. These patterns have been, and continue to be, identified across our many, widespread, diverse communities throughout our vast history. Experts comprehensively study, analyze, evaluate, refine, and apply these patterns to build and maintain their related [[HUMANITY:CAPABILITIES]]. These experts produce the intellectual frameworks, cognitive models, behavioral theories, moral philosophies, decision sciences, and standards that explain *why* humans think and behave as they do — forming the analytical backbone of [[HUMANITY:LESSONS]], [[HUMANITY:VALUES]], and [[HUMANITY:OODA]]. Experts include the following:

- Formal Logic and Foundations Specialists
  - Logicians
  - Proof Theorists
  - Model Theorists
- Philosophy and Epistemology Professionals
  - Philosophers
  - Analytic Philosophers
  - Ethicists
  - Applied Ethicists
- Theology and Religious Studies Professionals
  - Systematic Theologians
  - Religious Philosophers
- Cognitive and Behavioral Science Experts
  - Cultural Psychologists
  - Social Psychologists
  - Moral Psychologists
  - Positive Psychologists
  - Cognitive Psychologists
  - Behavioral Scientists
  - Human Factors Specialists
  - Human Needs & Motivation Researchers
  - Quality-of-Life & Wellbeing Researchers
  - Personality Psychologists
  - Industrial-Organizational Psychologists
- Economics and Decision Sciences Professionals
  - Systems Thinkers
  - Systems Engineers
  - Human Factors Engineers
  - Cognitive Engineers
  - Economists
  - Game Theorists
  - Operations Research Analysts
  - Decision Scientists
- Standards, Policy, and Governance Professionals
  - Social Systems Planners
  - Human Rights Experts
  - Standards Developers
  - Policy Analysts
  - Program Evaluators
  - Regulatory & Compliance Specialists
- Human Development & Wellbeing Experts
  - Developmental Psychologists
  - Change Management Consultants
  - Evaluation & Impact Assessment Specialists
  - Educational Psychologists
  - Curriculum Designers
  - Learning Experience Designers
  - Instructional Systems Designers
  - Character Education Specialists

- **Examples**
  - **Cognitive bias and decision-making:** User asks "Why do people fall for scams even when they know better?" → cite [[HUMANITY:REASONING_EXPERTS]]: Cognitive Psychologists, Behavioral Scientists, Human Factors Specialists.
  - **Ethical dilemmas:** User asks "What does ethics say about lying to protect someone's feelings?" → cite [[HUMANITY:REASONING_EXPERTS]]: Ethicists, Applied Ethicists, Moral Psychologists.
  - **Stress and decision quality:** User asks "Who studies how people make worse decisions when they're stressed or tired?" → cite [[HUMANITY:REASONING_EXPERTS]]: Decision Scientists, Cognitive Engineers, Behavioral Scientists.
  - **Standards and policy:** User asks "Who designs the rules that organizations use to make fair decisions?" → cite [[HUMANITY:REASONING_EXPERTS]]: Standards Developers, Policy Analysts, Program Evaluators.

- **Boundaries / Scope**
  - **Includes:** Academic and professional roles focused on the analytical, ethical, cognitive, and behavioral dimensions of human reasoning and decision-making; framework and standards development.
  - **Excludes:** Clinical treatment roles such as therapists or counselors (see [[HUMANITY:APPLICATION_EXPERTS]]); roles focused primarily on communication and narrative transmission (see [[HUMANITY:COMMUNICATION_EXPERTS]]); historical analysis of reasoning patterns over time (see [[HUMANITY:HISTORY_EXPERTS]]); individual practitioners or service directories.
  - **Primary purpose:** Provide IF-LLM with the expert attribution source for claims about *how* and *why* humans think, reason, decide, and behave.

- **Decision Rules (IF/THEN)**
  - **IF** a user asks *why* humans think, reason, or make decisions the way they do → [[HUMANITY:REASONING_EXPERTS]]
  - **IF** a user asks about cognitive bias, moral dilemmas, or behavioral patterns → [[HUMANITY:REASONING_EXPERTS]] (Moral Psychologists, Behavioral Scientists, Cognitive Psychologists)
  - **IF** a user asks about decision-making under stress, scarcity, or low resources → [[HUMANITY:REASONING_EXPERTS]] (Decision Scientists, Cognitive Engineers) and [[HUMANITY:HISTORY_EXPERTS]] for historical patterns
  - **IF** a user asks about ethical frameworks, moral philosophy, or values-based reasoning → [[HUMANITY:REASONING_EXPERTS]] (Ethicists, Moral Psychologists, Philosophers)
  - **IF** a user asks about standards, policy design, or regulatory frameworks → [[HUMANITY:REASONING_EXPERTS]] (Standards Developers, Policy Analysts, Regulatory Specialists)
  - **IF** the user also asks *how to apply* these frameworks in a professional or community setting → add [[HUMANITY:APPLICATION_EXPERTS]]

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:OODA]] (reasoning experts study and improve the quality of the full OODA loop — especially [[HUMANITY:ORIENT]] and [[HUMANITY:DECIDE]]); [[HUMANITY:THINKING]] (reasoning experts develop and validate frameworks for critical thinking); [[HUMANITY:VALUES]] (moral philosophers and ethicists define, refine, and test human values); [[HUMANITY:FALLIBILITY]] (behavioral scientists document recurring patterns of human error, bias, and temptation); [[HUMANITY:TEMPTATIONS]] (economists, behavioral scientists, and cognitive psychologists explain the mechanics of temptation patterns); [[HUMANITY:LESSONS]] (reasoning experts synthesize and validate lessons about how humans think and decide across contexts)
  - **Grounds:** [[HUMANITY:OODA]] quality (especially [[HUMANITY:ORIENT]] and [[HUMANITY:DECIDE]] accuracy); [[HUMANITY:THINKING]] frameworks; [[HUMANITY:VALUES]] definitions
  - **Required by:** [[HUMANITY:CAPABILITIES]] development (building cognitive and reasoning capabilities requires expert knowledge and validated frameworks)
  - **Affects:** quality of [[HUMANITY:ORIENT]] and [[HUMANITY:DECIDE]] steps; accuracy of [[HUMANITY:VALUES]] application; depth of understanding of [[HUMANITY:FALLIBILITY]] and [[HUMANITY:TEMPTATIONS]]
  - **Vulnerable to:** narrow disciplinary framing — a single expert field rarely captures the full picture; cite multiple subcategories when a question spans cognition, ethics, and behavior

##### Communication Experts

ID: HUMANITY.ELEMENTS.EXPERTS.COMMUNICATION
TAGS: [[HUMANITY:COMMUNICATION_EXPERTS]]

Experts of [[HUMANITY:ROOT]]'s most significant communication patterns. These patterns have been, and continue to be, identified across our many, widespread, diverse communities throughout our vast history. Experts comprehensively study, analyze, evaluate, refine, and apply these patterns to build and maintain their related [[HUMANITY:CAPABILITIES]]. These experts preserve, transmit, and interpret [[HUMANITY:LESSONS]] across cultures, languages, and time through storytelling, linguistic analysis, religious narrative, folklore, mythology, and literary tradition — explaining *how* humanity shares and sustains its [[HUMANITY:WISDOM]]. They produce linguistic analyses, narrative frameworks, cultural translations, archival records, and literary interpretations that keep humanity's patterns alive and accessible across generations and communities. Experts include the following:

- Linguistics and Language
  - Linguists
  - Comparative Linguists
  - Historical Linguists
  - Philologists
  - Etymologists
  - Phraseologists
  - Sociolinguists
  - Semiotic Analysts
- Cultural and Historical
  - Cultural Anthropologists
  - Cultural Historians
  - Cultural Sociologists
  - Ethnographers
  - Ethnologists
  - Religious Historians
  - Scholars of Esoteric Traditions
  - Philosophers
  - Ethics and Philosophy Teachers
  - Moral Theologians
- Religious and Theological
  - Clergy Members (Pastors, Priests, Imams, Rabbis)
  - Theologians
  - Religious Studies Professors
  - Comparative Religion Scholars
- Folklore, Mythology, and Traditional Literature
  - Folklorists
  - Mythologists
  - Comparative Mythologists
  - Professors of Mythology and Folklore
  - Mythopoetic Theorists
  - Oral History Specialists
  - Oral Tradition Scholars
- Literary
  - Literary Scholars
  - Literary Critics
  - Comparative Literature Scholars
  - Literary Journalists
  - English Professors
  - Literature Teachers and Professors
  - High School and College Literature Teachers
  - University Professors (Folklore Studies)
  - Literature and Humanities Educators
- Psychological and Developmental
  - Developmental Psychologists
  - Psychologists (Cognitive and Language Development)
  - Psychologists (Moral Development in Stories)
  - Narrative Therapists
- Archival and Preservation
  - Archivists
  - Manuscript Archivists
  - Rare Book Specialists
  - Special Collections Librarians
  - Librarians (Rare Books and Special Collections)
- Education and Development
  - Children's Book Authors
  - Children's Literature Professors
  - Children's Media Analysts
  - K-12 Teachers (Literature and Social Studies)
  - Language Teachers (Idioms and Proverbs)
  - Creative Writing Instructors
  - Curriculum Developers (Humanities, Cultural Studies, Literature, and Language Education)
- Storytelling and Narrative
  - Novelists
  - Fiction Writers
  - Playwrights
  - Screenwriters
  - Comic Book Writers and Artists (Mythological Themes)
  - Multimedia Storytellers
  - Storytellers and Oral Tradition Performers
- Media and Content
  - Documentary Filmmakers (Cultural Storytelling)
  - Content Creators (Religious or Moral Storytelling)
  - Publishers and Editors (Folklore and Mythology Publications)
  - Editors (Language Usage and Etymology)

- **Examples**
  - **Origins of sayings and proverbs:** User asks "Where does the saying 'don't judge a book by its cover' come from, and what does it really mean?" → cite [[HUMANITY:COMMUNICATION_EXPERTS]]: Etymologists, Phraseologists, Folklorists.
  - **Cross-cultural teaching of values:** User asks "How do different cultures teach children about honesty?" → cite [[HUMANITY:COMMUNICATION_EXPERTS]]: Comparative Mythologists, Children's Literature Professors, Curriculum Developers, Cultural Anthropologists.
  - **Recurring story themes:** User asks "Why do completely different cultures have the same kinds of stories — like a great flood, or a trickster figure?" → cite [[HUMANITY:COMMUNICATION_EXPERTS]]: Comparative Mythologists, Mythopoetic Theorists, Comparative Religion Scholars.
  - **Understanding a cultural tradition:** User asks "What do oral traditions do for a community that written records don't?" → cite [[HUMANITY:COMMUNICATION_EXPERTS]]: Oral Tradition Scholars, Ethnographers, Sociolinguists.

- **Boundaries / Scope**
  - **Includes:** Expert roles focused on language, storytelling, narrative, folklore, mythology, literature, archival preservation, and cultural transmission of human wisdom across communities and generations.
  - **Excludes:** Applied professional practice in clinical or legal communication settings (see [[HUMANITY:APPLICATION_EXPERTS]]); analytical reasoning frameworks and ethical theory development (see [[HUMANITY:REASONING_EXPERTS]]); historical social structures beyond their storytelling dimensions (see [[HUMANITY:HISTORY_EXPERTS]]); individual authors, storytellers, or media creators not functioning as scholarly experts.
  - **Primary purpose:** Provide IF-LLM with expert attribution for claims about *how* human wisdom is encoded in and transmitted through language, narrative, and cultural tradition.

- **Decision Rules (IF/THEN)**
  - **IF** a user asks about the origin or meaning of a proverb, saying, or idiom → [[HUMANITY:COMMUNICATION_EXPERTS]] (Etymologists, Phraseologists, Folklorists)
  - **IF** a user asks about myths, folktales, or religious stories across cultures → [[HUMANITY:COMMUNICATION_EXPERTS]] (Comparative Mythologists, Religious Studies Professors, Comparative Religion Scholars)
  - **IF** a user asks how a cultural value is taught to children → [[HUMANITY:COMMUNICATION_EXPERTS]] (Children's Literature Professors, Curriculum Developers, Language Teachers)
  - **IF** a user asks about preserving or passing down cultural knowledge → [[HUMANITY:COMMUNICATION_EXPERTS]] (Archivists, Oral Tradition Scholars, Special Collections Librarians)
  - **IF** a user asks why the same story themes appear across unrelated cultures → [[HUMANITY:COMMUNICATION_EXPERTS]] (Comparative Mythologists, Mythopoetic Theorists) and [[HUMANITY:HISTORY_EXPERTS]] for cross-civilizational patterns
  - **IF** the user also asks *why* these patterns persist historically or socially → add [[HUMANITY:HISTORY_EXPERTS]]

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:LESSONS]] (communication experts are the primary transmitters of humanity's lessons through story, proverb, and tradition); [[HUMANITY:WISDOM]] (the sharing of lessons across communities — storytelling and tradition — is how [[HUMANITY:WISDOM]] is defined in [[HUMANITY:LESSONS]]); [[HUMANITY:VALUES]] (communication experts show how values are embedded, taught, and sustained through narrative across cultures); [[HUMANITY:ORIENT]] (narrative and cultural context are primary inputs that shape how people interpret situations — the Orient step of [[HUMANITY:OODA]])
  - **Grounds:** transmission of [[HUMANITY:LESSONS]] across communities and generations; cultural context for [[HUMANITY:ORIENT]] accuracy
  - **Required by:** [[HUMANITY:WISDOM]] (wisdom spreads through the communication patterns these experts study and preserve)
  - **Affects:** how effectively [[HUMANITY:LESSONS]] and [[HUMANITY:VALUES]] are understood and adopted across diverse communities; the richness of [[HUMANITY:ORIENT]] when cultural and narrative context is relevant
  - **Vulnerable to:** cultural bias — communication experts from any single tradition may not represent the full range of human storytelling and wisdom; cite cross-cultural and comparative experts when diversity of perspective matters

##### Application Experts

ID: HUMANITY.ELEMENTS.EXPERTS.APPLICATION
TAGS: [[HUMANITY:APPLICATION_EXPERTS]]

Experts applying [[HUMANITY:ROOT]]'s most significant [[HUMANITY:LESSONS]]. These [[HUMANITY:LESSONS]] have been, and continue to be, identified across our many, widespread, diverse communities throughout our vast history. Experts comprehensively study, analyze, evaluate, refine, and apply these [[HUMANITY:LESSONS]] to build and maintain their related [[HUMANITY:CAPABILITIES]]. These experts translate humanity's lessons into real-world practice across professional domains — healthcare, law, policy, education, organizations, and communities. They produce ethical guidelines, policy frameworks, clinical protocols, professional standards, and organizational development tools that help individuals and institutions apply [[HUMANITY:WISDOM]] in everyday life, explaining *how* to put knowledge into practice to better satisfy [[HUMANITY:NEEDS]] and prevent [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]. Experts include the following:

- Ethics and Philosophy
  - Philosophers
  - Ethicists
  - Moral Theorists
  - Applied Ethicists
- Social and Behavioral Sciences
  - Anthropologists
  - Sociologists
  - Psychologists
  - Behavioral Scientists
  - Cultural Anthropologists
- Education and Academia
  - Ethics Professors
  - Theology Professors
  - Workplace Ethics Trainers
  - Curriculum Developers for Ethics and Theology
  - Educational Researchers
  - Academic Advisors
- Healthcare and Bioethics
  - Medical Ethicists
  - Clinical Ethicists
  - Bioethics Researchers
- Health and Human Services
  - Social Workers
  - Public Health Educators
  - Health Coaches
  - Community Health Workers
  - Patient Advocates
  - Child and Family Advocates
- Legal and Judicial Systems
  - Legal Ethics Specialists
  - Judges
  - Legal Scholars
  - Compliance Officers
  - Public Defenders
- Public Policy and Advocacy
  - Human Rights Advocates
  - Social Policy Analysts
  - Public Policy Analysts
  - Healthcare Policy Analysts
  - Political Scientists
  - Community Development Specialists
  - Advocacy and Outreach Coordinators
  - Environmental Policy Analysts
- Corporate and Organizational Ethics
  - Business Ethicists
  - Ethics and Compliance Officers
  - Corporate Social Responsibility (CSR) Managers
  - Diversity and Inclusion Specialists
  - Organizational Development Specialists
- Education and Training
  - Career Counselors
  - Training and Development Specialists
  - Educational Administrators
  - Vocational Guidance Counselors
- Organizational Development
  - Industrial-Organizational Psychologists
  - Human Resources Specialists
  - Workforce Development Specialists
  - Organizational Change Consultants
  - Talent Management Advisors
- Labor Market and Employment
  - Occupational Analysts
  - Compensation and Benefits Managers
  - Labor Market Analysts
  - Employment Policy Experts
  - Job Development Specialists
- Communication and Media
  - Media Ethics Analysts
  - Digital Media Ethics Advisors
  - Public Relations Specialists with Ethical Focus
  - Media Analysts
  - Investigative Journalists
  - Community Engagement Coordinators

- **Examples**
  - **Workplace ethical challenges:** User asks "Who can help me figure out the right thing to do when my boss asks me to do something that feels wrong?" → cite [[HUMANITY:APPLICATION_EXPERTS]]: Business Ethicists, Ethics and Compliance Officers, Workplace Ethics Trainers.
  - **Accessing community support:** User asks "What kind of professional helps people find resources when they're struggling to make ends meet?" → cite [[HUMANITY:APPLICATION_EXPERTS]]: Social Workers, Community Health Workers, Advocacy and Outreach Coordinators.
  - **Organizational fairness:** User asks "Who studies how to make workplaces fairer for everyone?" → cite [[HUMANITY:APPLICATION_EXPERTS]]: Industrial-Organizational Psychologists, Diversity and Inclusion Specialists, Organizational Development Specialists.
  - **Healthcare ethics:** User asks "Who helps hospitals make difficult ethical decisions about patient care?" → cite [[HUMANITY:APPLICATION_EXPERTS]]: Medical Ethicists, Clinical Ethicists, Bioethics Researchers.

- **Boundaries / Scope**
  - **Includes:** Expert roles that apply humanity's patterns in professional, institutional, or community contexts, with an emphasis on real-world outcomes for individuals and groups; covers health, law, education, policy, organizational, and community practice domains.
  - **Excludes:** Theoretical framework development (see [[HUMANITY:REASONING_EXPERTS]]); historical or cross-civilizational analysis (see [[HUMANITY:HISTORY_EXPERTS]]); narrative and storytelling transmission (see [[HUMANITY:COMMUNICATION_EXPERTS]]); individual practitioners providing direct services — this file lists roles, not specific professionals; emergency crisis services (see [[HUMANITY:COPING]] for urgent resources).
  - **Primary purpose:** Enable IF-LLM to identify what *type* of professional to recommend when a user's situation calls for real-world expert guidance; support the user in understanding who to seek, not who specifically.

- **Decision Rules (IF/THEN)**
  - **IF** a user asks who can help them *do something* about a difficult human situation (ethically, socially, legally, or organizationally) → [[HUMANITY:APPLICATION_EXPERTS]]
  - **IF** a user asks about professional support for health, family, or community challenges → [[HUMANITY:APPLICATION_EXPERTS]] (Social Workers, Public Health Educators, Patient Advocates, Community Health Workers)
  - **IF** a user asks about organizational ethics, workplace fairness, or diversity and inclusion → [[HUMANITY:APPLICATION_EXPERTS]] (Business Ethicists, Diversity and Inclusion Specialists, Organizational Development Specialists)
  - **IF** a user asks about legal ethics, policy design, or human rights advocacy → [[HUMANITY:APPLICATION_EXPERTS]] (Legal Ethics Specialists, Human Rights Advocates, Public Policy Analysts)
  - **IF** a user asks about how to become more capable or advance in a career → [[HUMANITY:APPLICATION_EXPERTS]] (Career Counselors, Training and Development Specialists, Workforce Development Specialists) and [[HUMANITY:CAPABILITIES]]
  - **IF** the user also wants to understand *why* these practices developed or what history shows → add [[HUMANITY:HISTORY_EXPERTS]] and [[HUMANITY:REASONING_EXPERTS]]

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:LESSONS]] (application experts are the bridge between humanity's lessons and real-world practice); [[HUMANITY:NEEDS]] (application experts design systems and professional roles to help people meet their needs); [[HUMANITY:ACTIVITIES]] (application experts support IADLs through social work, healthcare, policy, and education); [[HUMANITY:CAPABILITIES]] (application experts build human capabilities through education, workforce development, and organizational systems); [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]] (application experts respond to and work to prevent consequences of unmet needs); [[HUMANITY:RIGHTS]] (legal experts, policy analysts, and human rights advocates work to protect and enforce rights)
  - **Grounds:** practical expression of [[HUMANITY:LESSONS]] in professional contexts; real-world systems for [[HUMANITY:NEEDS]] satisfaction
  - **Required by:** [[HUMANITY:CAPABILITIES]] growth at the community and institutional level (requires professional expertise and systems); [[HUMANITY:NEEDS]] satisfaction at scale (requires healthcare, social service, policy, and education infrastructure)
  - **Affects:** real-world outcomes for [[HUMANITY:NEEDS]] satisfaction; prevention of [[HUMANITY:CONSEQUENCES_UNMET_NEEDS]]; protection of [[HUMANITY:RIGHTS]] in practice
  - **Vulnerable to:** gaps between policy intent and lived experience — cite [[HUMANITY:HISTORY_EXPERTS]] when historical patterns suggest that a policy approach has known limitations

##### History Experts

ID: HUMANITY.ELEMENTS.EXPERTS.HISTORY
TAGS: [[HUMANITY:HISTORY_EXPERTS]]

Experts of [[HUMANITY:ROOT]]'s most significant patterns. These patterns help inform [[HUMANITY:LESSONS]]. These patterns have been, and continue to be, identified across our many, widespread, diverse communities throughout our vast history. Experts comprehensively study, analyze, evaluate, refine, and apply these patterns to build and maintain their related [[HUMANITY:CAPABILITIES]]. These experts document, analyze, and interpret humanity's patterns across civilizations, societies, and time — producing the evidence base from which [[HUMANITY:LESSONS]] and [[HUMANITY:WISDOM]] are identified and validated. They explain *what has happened*, *why similar problems recur*, and *what the long arc of human experience reveals* about our shared nature, through archaeological, historical, sociological, geographic, and interdisciplinary lenses. Experts include the following:

- Anthropology and Archaeology
  - Cultural Anthropologists (belief systems, social norms, rituals, lived experience)
  - Social Anthropologists (institutions, kinship, power, inequality)
  - Archaeologists (material evidence of human behavior over deep time)
  - Biological / Physical Anthropologists (human evolution, biological diversity)
  - Linguistic Anthropologists (language, meaning, communication patterns)
- History and Historical Analysis
  - Historians (political, social, economic, cultural history)
  - World / Global Historians (cross-civilizational patterns and long-term trends)
  - Social Historians (everyday life, marginalized populations)
  - Intellectual Historians (belief systems, ideologies, worldviews)
  - Economic Historians (material conditions, labor, development over time)
- Sociology and Demography
  - Sociologists (social structures, institutions, inequality, group behavior)
  - Comparative Sociologists (cross-society patterns and variation)
  - Demographers (population trends, migration, fertility, mortality)
  - Social Network Analysts (relationships and diffusion of ideas/behaviors)
- Psychology and Human Behavior
  - Social Psychologists (attitudes, group dynamics, identity)
  - Cultural Psychologists (how culture shapes cognition and emotion)
  - Developmental Psychologists (human experience across the life course)
  - Evolutionary Psychologists (behavioral patterns shaped by evolution)
- Philosophy, Ethics, and Religion
  - Philosophers (human nature, meaning, knowledge, morality)
  - Moral Philosophers / Ethicists (values and normative foundations)
  - Philosophers of History (interpretation of historical meaning and progress)
  - Religious Studies Scholars (belief systems, practices, comparative religion)
  - Theologians (faith traditions and interpretations, context-dependent)
- Political Science and Governance
  - Political Scientists (power, governance, collective decision-making)
  - Comparative Politics Scholars (institutional variation across societies)
  - Political Theorists (foundations of authority, rights, justice)
  - International Relations Scholars (global patterns, conflict, cooperation)
- Economics and Political Economy
  - Economists (incentives, resource allocation, structural trends)
  - Institutional Economists (rules, norms, and human behavior)
  - Political Economists (interaction of economy, power, and society)
  - Development Economists (poverty, inequality, human well-being)
- Geography and Environmental Studies
  - Human Geographers (place, culture, migration, spatial patterns)
  - Cultural Geographers (landscape, identity, meaning)
  - Environmental Anthropologists / Geographers (human–environment interaction)
- Area, Cultural, and Indigenous Studies
  - Area Studies Scholars (region-specific deep cultural and historical analysis)
  - Ethnic Studies Scholars (race, identity, power, lived experience)
  - Indigenous Studies Scholars (Indigenous histories, knowledge systems)
- Interdisciplinary and Integrative Fields
  - Humanists (synthesizing history, philosophy, culture)
  - Cultural Studies Scholars (media, identity, power, meaning-making)
  - Systems Thinkers (long-term, cross-domain human patterns)
  - Complexity Scientists studying social systems (emergent human behavior)
- Knowledge Synthesis and Public Communication
  - Science and Humanities Communicators (translate complex human research)
  - Public Intellectuals (integrative analysis for broad audiences)
  - Museum Curators and Public Historians (interpret and communicate human pasts)
  - Documentary Researchers and Writers (narrative synthesis of human experience)

- **Examples**
  - **Recurring societal problems:** User asks "Why do societies keep repeating the same mistakes with money, power, and corruption?" → cite [[HUMANITY:HISTORY_EXPERTS]]: World/Global Historians, Institutional Economists, Systems Thinkers, Political Economists.
  - **Historical patterns of inequality:** User asks "How have different societies dealt with inequality throughout history?" → cite [[HUMANITY:HISTORY_EXPERTS]]: Economic Historians, Social Historians, Comparative Sociologists, Development Economists.
  - **Community recovery:** User asks "What does history show about how communities recover after major disasters or crises?" → cite [[HUMANITY:HISTORY_EXPERTS]]: Social Historians, Demographers, Cultural Anthropologists, Environmental Anthropologists.
  - **Why a social problem feels stuck:** User asks "Why has racism been so hard to eliminate even when people know it's wrong?" → cite [[HUMANITY:HISTORY_EXPERTS]]: Ethnic Studies Scholars, Social Anthropologists, Intellectual Historians, Political Scientists; then [[HUMANITY:APPLICATION_EXPERTS]] for what is being done about it.

- **Boundaries / Scope**
  - **Includes:** Expert roles that study human experience across time and civilizations through historical, anthropological, sociological, psychological, geographic, and interdisciplinary lenses; both deep-time and modern historical analysis; cross-civilizational and comparative perspectives.
  - **Excludes:** Present-day professional application and direct practice (see [[HUMANITY:APPLICATION_EXPERTS]]); narrative and storytelling transmission of history (see [[HUMANITY:COMMUNICATION_EXPERTS]]); analytical reasoning frameworks divorced from historical evidence (see [[HUMANITY:REASONING_EXPERTS]]); individual historians, specific institutions, or media outlets.
  - **Primary purpose:** Enable IF-LLM to attribute claims about long-term human patterns to recognized scholarly fields, and to ground [[HUMANITY:LESSONS]] in the evidence base that history experts produce.

- **Decision Rules (IF/THEN)**
  - **IF** a user asks about patterns that repeat across history or across different civilizations → [[HUMANITY:HISTORY_EXPERTS]]
  - **IF** a user asks "why does this keep happening?" about a social, political, or economic problem → [[HUMANITY:HISTORY_EXPERTS]] (Historians, Sociologists, Systems Thinkers, Complexity Scientists)
  - **IF** a user asks about the origins of a cultural practice, belief system, or social norm → [[HUMANITY:HISTORY_EXPERTS]] (Cultural Anthropologists, Intellectual Historians, Religious Studies Scholars)
  - **IF** a user asks about long-term population trends, migration, or demographic change → [[HUMANITY:HISTORY_EXPERTS]] (Demographers, Human Geographers, Social Network Analysts)
  - **IF** a user asks what lessons history offers about a current challenge → [[HUMANITY:HISTORY_EXPERTS]] to identify the pattern; [[HUMANITY:LESSONS]] to connect it to validated wisdom
  - **IF** the user also needs to understand what is being done about it today → add [[HUMANITY:APPLICATION_EXPERTS]]
  - **IF** the user also needs to understand how these patterns are told and transmitted across communities → add [[HUMANITY:COMMUNICATION_EXPERTS]]

- **Ontological Relationships**
  - **Related to:** [[HUMANITY:LESSONS]] (history experts are the primary scholars who identify, validate, and document humanity's most significant lessons across civilizations); [[HUMANITY:WISDOM]] (the historical record is the evidence base from which [[HUMANITY:WISDOM]] is distilled and tested); [[HUMANITY:FALLIBILITY]] (historians document recurring patterns of human fallibility, error, and moral compromise across societies and eras); [[HUMANITY:TEMPTATIONS]] and [[HUMANITY:CONSEQUENCES_TEMPTATIONS]] (historical analysis shows how temptations have produced consequences at civilizational scale); [[HUMANITY:CONCERNS]] (modern U.S. concerns often echo patterns that history experts have documented across many societies); [[HUMANITY:VISION]] (history informs what the Vision requires by revealing what has and has not enabled human flourishing)
  - **Grounds:** [[HUMANITY:LESSONS]] (history experts produce the primary evidence base from which lessons are identified and validated); [[HUMANITY:WISDOM]] (historical patterns across diverse civilizations are the foundation of validated wisdom)
  - **Required by:** [[HUMANITY:WISDOM]] validation (wisdom requires tested patterns, not just assertion); [[HUMANITY:LESSONS]] grounding (lessons without historical evidence are vulnerable to recency bias)
  - **Affects:** depth and validity of [[HUMANITY:LESSONS]] available to the IF-LLM; quality of [[HUMANITY:ORIENT]] when historical context is relevant to interpreting a current situation; accuracy of [[HUMANITY:CONCERNS]] framing (recognizing whether a concern is novel or recurring)
  - **Vulnerable to:** recency bias — history experts covering only recent periods may miss the longer-arc patterns; cite World/Global Historians and Comparative Sociologists when long-term cross-civilizational perspective is needed
