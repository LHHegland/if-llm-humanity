# Humanity's Values 4 — Information-Following Large Language Model Knowledge (*if-llm-humanity-values-4.md*)

## File Header

- **Name:** Humanity's Values 4 — Information-Following Large Language Model Knowledge (*if-llm-humanity-values-4.md*)
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


- **Dependencies (Required):** `if-llm-system-policies-processing.md`, `if-llm-humanity-index.md`, `if-llm-humanity.md`, `if-llm-humanity-experts.md`, `if-llm-humanity-narm.md`, `if-llm-humanity-ooda.md`, `if-llm-humanity-values.md`, `if-llm-humanity-values-1.md`, `if-llm-humanity-values-2.md`, `if-llm-humanity-values-3.md`, `if-llm-humanity-values-5.md`
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

- Justice → HUMANITY.ELEMENTS.VALUES.JUSTICE → [[HUMANITY:JUSTICE]]
- Fairness → HUMANITY.ELEMENTS.VALUES.FAIRNESS → [[HUMANITY:FAIRNESS]]
- Citizenship → HUMANITY.ELEMENTS.VALUES.CITIZENSHIP → [[HUMANITY:CITIZENSHIP]]
- Leadership → HUMANITY.ELEMENTS.VALUES.LEADERSHIP → [[HUMANITY:LEADERSHIP]]
- Persistence → HUMANITY.ELEMENTS.VALUES.PERSISTENCE → [[HUMANITY:PERSISTENCE]]

## Humanity

### Elements

#### Values

##### Justice

ID: HUMANITY.ELEMENTS.VALUES.JUSTICE
TAGS: [[HUMANITY:JUSTICE]]

Fairness in the treatment of individuals, families, and communities, ensuring that all people receive what they are due in terms of rights, opportunities, and responsibilities. It involves creating systems, laws, and practices that uphold equality, prevent harm, and protect the dignity of all. Justice seeks to balance the needs of individuals and society while addressing wrongdoing, promoting fairness, and ensuring accountability. Practicing justice requires us to make decisions that are ethical, equitable, and in alignment with the well-being of other people, other living beings, our environment, and ourselves — our [[HUMANITY:INTERDEPENDENCE]].

- **Included by Value**: [[HUMANITY:COMPASSION]]
- **Includes Values**: [[HUMANITY:FAIRNESS]], [[HUMANITY:CITIZENSHIP]], and [[HUMANITY:LEADERSHIP]]
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #283593
    - #948829
    - #299488
    - #942935
    - #359429
    - #882994
  - **Symbols**
    - **Scales / Balance**: impartial weighing of evidence, rights, and responsibilities.
    - **Blindfold**: equal treatment—judgment not based on status, wealth, or appearance.
    - **Gavel**: legitimate authority to decide disputes and enforce rules fairly.
    - **Sword**: justice has “teeth”—accountability and enforcement against harm.
    - **Courthouse Columns / Pillars**: stable institutions and rule-of-law foundations.
    - **Equal Sign (＝)**: equality under law; consistent standards applied to all.
    - **Open Law Book / Constitution**: rights, duties, and shared standards made transparent.
- **Literary Elements**
  - **Proverbs**
    - “**No one is above the law.**” — justice requires equal accountability.
    - “**Let the punishment fit the crime.**” — fairness means proportional consequences.
    - “**Fair is fair.**” — a plain-language commitment to impartial treatment.
    - “**What goes around comes around.**” — highlights accountability and consequences.
    - “**Give credit where credit is due.**” — justice includes rightful recognition and reward.
    - “**You reap what you sow.**” — links choices to outcomes; responsibility for harms/benefits.
    - “**Right is right, even if everyone is against it.**” — justice can require moral courage against pressure.
  - **Quotations**
    - “**Justice is the first virtue of social institutions, as truth is of systems of thought.**” ~ John Rawls, *A Theory of Justice* (1971).
    - “**Injustice anywhere is a threat to justice everywhere.**” ~ Martin Luther King Jr., “Letter from Birmingham Jail” (1963).
    - “**Justice is the constant and perpetual will to render to every man his due.**” ~ Ulpian
    - “**The arc of the moral universe is long, but it bends toward justice.**” ~ Parker→King
    - “**There is no crueller tyranny than that which is perpetrated under the shield of law and in the name of justice.**” ~ Montesquieu.
    - “**Power concedes nothing without a demand. It never did and it never will.**” ~ Frederick Douglass, “West India Emancipation” speech (1857).
    - “**The law, in its majestic equality, forbids the rich and poor alike to sleep under bridges, to beg in the streets, and to steal bread.**” ~ Anatole France, *The Red Lily* (1894).
  - **Myths**
    - **Themis and Dike** (Greek): personifications of divine order and “right judgment.”
    - **The Trial of Orestes** (Greek): justice moves from blood-vengeance to lawful process and civic courts.
    - **Maat and the Weighing of the Heart** (Egyptian): justice as balance, truth, and moral accountability.
    - **Shamash/Utu and the Gift of Law** (Mesopotamian): the sun-god as judge—justice revealed “in the light.”
    - **Forseti** (Norse): a deity associated with settling disputes peacefully and fairly.
    - **Yama as Judge of the Dead** (Indian traditions): consequences and moral accounting beyond immediate power.
  - **Folktales**
    - **Robin Hood** (English legend cycle): “rough justice” against corrupt power; fairness for the vulnerable.
    - **Judge Bao (Bao Zheng) stories** (Chinese): incorruptible public service; law applied without favoritism.
    - **Akbar & Birbal tales** (South Asian): clever rulings that expose deception and restore fairness.
    - **“Two Mothers, One Baby” variants** (many cultures): wise judgment tests true care, not loud claims.
    - **“The King’s Bell/Drum of Justice” motifs** (widely recurring): rulers must stay reachable to ordinary people’s grievances.
    - **“The Honest Witness” village tales** (common motif): community justice depends on truth-telling and courage.
  - **Fables**
    - **The Wolf and the Lamb** (Aesop): warns that “might makes right” is the opposite of justice.
    - **The Lion’s Share** (Aesop): power can hijack fairness unless rules constrain it.
    - **The Fox and the Stork** (Aesop): reciprocity—treat others as you want to be treated.
    - **The Frogs Who Asked for a King** (Aesop): poor leadership produces injustice; governance matters.
    - **The Farmer and the Stork** (Aesop): choices and associations can bring consequences (accountability).
    - **The Ant and the Grasshopper** (Aesop): fairness includes responsibility over time, not only in the moment.
  - **Parables**
    - **The Persistent Widow and the Unjust Judge**: justice may require persistence against indifferent power.
    - **The Good Samaritan**: moral justice crosses tribal boundaries; dignity for the harmed.
    - **The Workers in the Vineyard**: challenges our instinctive “fairness math” versus generosity and agreed terms.
    - **The Unforgiving Servant**: justice without mercy can become cruelty; accountability must remain human.
    - **The Rich Man and Lazarus**: moral critique of neglect and structural inequality.
    - **The Sheep and the Goats**: accountability for how we treat the vulnerable.
  - **Fairy Tales**
    - **Cinderella**: unjust treatment is ultimately exposed; dignity restored.
    - **Snow White**: wrongdoing is revealed; harm meets consequences.
    - **The Goose Girl**: truth surfaces and rightful place is restored.
    - **Rumpelstiltskin**: contracts, coercion, and the ethics of bargains—justice requires honest terms.
    - **The Emperor’s New Clothes**: social pressure can protect injustice; truth-telling disrupts it.
    - **The Little Match Girl**: moral indictment of indifference; prompts compassion-driven justice.

##### Fairness

ID: HUMANITY.ELEMENTS.VALUES.FAIRNESS
TAGS: [[HUMANITY:FAIRNESS]]

Making decisions and treating people in an impartial, just, and unbiased manner. It ensures that individuals are given equal opportunities, rights, and resources based on their needs and contributions. Fairness does not mean treating everyone exactly the same but rather ensuring that conditions and outcomes are equitable, reasonable, and free from favoritism or discrimination.

- **Included by Value**: [[HUMANITY:JUSTICE]]
- **Includes Values**: None
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #F5F5F5
    - #F5F5F5
    - #F5F5F5
    - #F5F5F5
    - #F5F5F5
    - #F5F5F5
  - **Symbols**
    - **Scales**: weighing claims evenly; balancing competing interests.
    - **Blindfold**: impartiality—decisions not based on status, wealth, or identity.
    - **Balance Beam / Seesaw**: fairness as “equal footing” and stabilized outcomes.
    - **Equal Sign (=)**: equal treatment under rules; consistency across people.
    - **Handshake**: fair agreement and mutual respect; “fair deal” symbolism.
    - **Level (carpenter’s level)**: “no tilt” toward favoritism; equal ground.
    - **Evenly divided circle / pie**: fair shares; just distribution of resources.
- **Literary Elements**
  - **Proverbs**
    - “**Fair is fair.**” — the basic expectation of even-handed treatment.
    - “**Turnabout is fair play.**” — reciprocity; you should accept the standards you apply to others.
    - “**What’s sauce for the goose is sauce for the gander.**” — the same rule should apply to everyone.
    - “**Don’t judge a book by its cover.**” — fairness requires looking past appearances and stereotypes.
    - “**Give credit where credit is due.**” — fairness in recognition and reward.
    - “**A deal is a deal.**” — fairness includes honoring agreements consistently.
    - “**Two wrongs don’t make a right.**” — fairness isn’t revenge; it’s principled restraint.
  - **Quotations**
    - “**Justice is the first virtue of social institutions, as truth is of systems of thought.**” ~ John Rawls, *A Theory of Justice*
    - “**Justice is the end of government. It is the end of civil society.**” ~ James Madison, *Federalist No. 51* (1788).
    - “**No man is above the law and no man is below it…**” ~ Theodore Roosevelt, *Third Annual Message* (1903).
    - “**Injustice anywhere is a threat to justice everywhere.**” ~ Martin Luther King Jr., “Letter from Birmingham Jail” (1963).
    - “**Power concedes nothing without a demand. It never did and it never will.**” ~ Frederick Douglass, “West India Emancipation” (1857).
    - “**The law, in its majestic equality, forbids the rich as well as the poor to sleep under bridges…**” ~ Anatole France, *The Red Lily* (1894).
    - “**If liberty and equality… are chiefly to be found in democracy, they will be best attained when all persons alike share in the government…**” ~ Aristotle, *Politics*.
  - **Myths**
    - **Ma’at and the Weighing of the Heart** (Egyptian): moral balance—your “weight” of truth/fairness determines judgment.
    - **Themis and Dike** (Greek): personifications of law and justice—fair order as a divine requirement.
    - **Astraea** (Greek/Roman): justice leaving a corrupt age—fairness as the condition for a “golden” society.
    - **The Trial of Orestes (Areopagus)** (Greek): shifts from vendetta to a court—procedural fairness over retaliation.
    - **Forseti** (Norse): god associated with settling disputes—peaceful, fair resolution.
    - **Yama / Dharmaraja with Chitragupta** (Hindu/Buddhist traditions): impartial accounting of deeds—fair consequences.
    - **Shamash and the giving of law** (Mesopotamian tradition around justice/law): fairness anchored in public, knowable rules.
  - **Folktales**
    - **Robin Hood** (English legend cycle): “fairness” framed as correcting exploitation and protecting the vulnerable.
    - **Stone Soup** (European): fair contribution—shared responsibility produces shared benefit.
    - **The Clever Farmer’s Daughter** (Grimm): fair judgment can outwit power and force consistency.
    - **The Empty Pot** (Chinese folktale): fairness in leadership selection—honesty treated as merit.
    - **King Solomon and the Two Mothers** (ancient Near Eastern/Israelite tradition): fairness as wise, impartial discernment.
    - **The Three Questions** (popularized by Tolstoy): fair action is timely and responsive to who is in front of you.
    - **The Bamboo Cutter’s fairness tests**: exposes unfair suitors through equal standards.
  - **Fables**
    - **The Wolf and the Lamb** (Aesop): unfairness when power invents “reasons” to harm the weak.
    - **The Lion’s Share** (Aesop): unfair division disguised as entitlement.
    - **The Fox and the Stork** (Aesop): reciprocity—fairness means not rigging the rules.
    - **The Ant and the Dove** (Aesop): fairness includes mutual aid; small and large can owe each other.
    - **The Dog in the Manger** (Aesop): unfair hoarding—blocking others from what you won’t use.
    - **The Bat and the Weasels** (Aesop): opportunism as “unfair play” (changing identity to escape consequences).
  - **Parables**
    - **The Good Samaritan**: fairness beyond in-groups—care based on need, not tribe.
    - **The Workers in the Vineyard**: challenges “fairness = strict equality”; highlights equity/intent.
    - **The Unforgiving Servant**: fair treatment includes consistent mercy standards.
    - **The Two Debtors**: fairness in moral accounting—gratitude and proportional humility.
    - **The Prodigal Son**: fairness vs mercy; resentment when “deservedness” feels violated.
    - **The Rich Man and Lazarus**: indicts unfair indifference; justice as moral reversal/accountability.
  - **Fairy Tales**
    - **Cinderella**: unfair treatment confronted; justice through recognition and dignity restored.
    - **The Goose Girl**: false status exposed; rightful place and fair truth restored.
    - **Beauty and the Beast**: fairness as seeing character over appearance.
    - **The Elves and the Shoemaker**: fair reward for kindness and good work.
    - **The Emperor’s New Clothes**: social fairness needs truth-telling; collective bias enables injustice.
    - **The Little Match Girl**: a stark warning about social unfairness and neglected suffering.
    - **The Twelve Brothers** (or similar sibling-justice tales): fairness in family obligations and broken promises.

##### Citizenship

ID: HUMANITY.ELEMENTS.VALUES.CITIZENSHIP
TAGS: [[HUMANITY:CITIZENSHIP]]

Responsibility and active participation of individuals in their families, communities, and societies. It involves upholding laws, respecting the rights of others, engaging in civic duties (such as voting and volunteering), and contributing to the common good of other people, other living beings, our environment, and ourselves. Citizenship recognizes that individuals are part of a larger social structure and have both rights and obligations within that structure.

- **Included by Value**: [[HUMANITY:JUSTICE]]
- **Includes Values**: None
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #1976D2
    - #D27519
    - #19D275
    - #D21975
    - #75D219
    - #7519D2
  - **Symbols**
    - **Ballot box / ballot**: civic duty and shared decision-making—participation matters.
    - **Town hall / civic building**: the “place of the public”—community problem-solving and accountability.
    - **Circle of people**: belonging + mutual responsibility; “we” over “me.”
    - **Raised hand**: volunteering, jury duty, public comment—showing up and speaking up.
    - **Bridge**: civic “connection work” across differences; building trust and cooperation.
    - **Civic seal / eagle**: shared institutions and the public good (bigger than any one person).
    - **Handshake**: social contract—rights paired with responsibilities; keeping commitments.
- **Literary Elements**
  - **Proverbs**
    - “**It takes a village.**” — citizenship is communal responsibility, not solo living.
    - “**Many hands make light work.**” — shared effort sustains communities.
    - “**United we stand, divided we fall.**” — cohesion and cooperation protect the common good.
    - “**If you want to go fast, go alone; if you want to go far, go together.**” — durable progress requires civic cooperation.
    - “**Charity begins at home.**” — citizenship starts with responsibility to nearby people and places.
    - “**Be the change you wish to see in the world.**” — civic virtue is practiced, not just demanded.
  - **Quotations**
    - “**Ask not what your country can do for you—ask what you can do for your country.**” ~ John F. Kennedy, *Inaugural Address* (Jan. 20, 1961).
    - “**A popular Government, without popular information, or the means of acquiring it, is but a Prologue to a Farce or a Tragedy…**” ~ James Madison (Aug. 4, 1822).
    - “**No right is more precious in a free country than that of having a voice in the election of those who make the laws under which… we must live.**” ~ U.S. Supreme Court, *Wesberry v. Sanders* (1964).
    - “**A republic, if you can keep it.**” ~ Benjamin Franklin.
    - “**…man is by nature a political animal…**” ~ Aristotle, *Politics*.
    - “**…the good we secure for ourselves is precarious and uncertain… until it is secured for all of us and incorporated into our common life.**” ~ Jane Addams, “The Subjective Necessity for Social Settlements” (1892).
  - **Myths**
    - **Athena vs. Poseidon (founding of Athens)** (Greek): citizenship as choosing a “civic gift” (olive tree—sustenance/law) over brute power; prioritizing public flourishing.
    - **Theseus and the synoecism of Attica** (Greek): mythic unification—shared identity and institutions create “one people.”
    - **Romulus and Remus** (Roman): founding a city-state; civic order emerges with rules, boundaries, and shared norms (and the dangers of faction).
    - **Cincinnatus** (Roman legend): public service as duty, not self-enrichment—leadership returned to the people after crisis.
    - **Yu the Great Tames the Flood** (Chinese): model of public works—sacrificial service to protect the community.
    - **The Sumerian King Gilgamesh** (Mesopotamian): the “bad ruler to responsible ruler” arc—power obligated to serve the city’s well-being.
  - **Folktales**
    - **Stone Soup** (European): civic contribution—community becomes stronger when everyone adds something.
    - **The Bremen Town Musicians** (German): forming a cooperative “little community” for safety and a shared future.
    - **The Empty Pot** (Chinese): civic trust—honesty as the basis for legitimate leadership.
    - **Anansi and the Pot of Wisdom** (West African/Akan): communities thrive when knowledge and responsibility are shared, not hoarded.
    - **The Three Questions** (folkloric motif/Tolstoy retelling): good citizenship is doing the right thing for the person in front of you, at the right time.
    - **Robin Hood cycle** (English legend): citizenship framed as resisting corruption and protecting vulnerable neighbors.
  - **Fables**
    - **The Bundle of Sticks** (Aesop): civic unity—collective strength protects everyone.
    - **The Ant and the Grasshopper** (Aesop): responsibility and preparation—pulling your weight in the long run.
    - **The Lion and the Mouse** (Aesop): civic reciprocity—everyone can contribute; no one is “too small” to matter.
    - **The Dog in the Manger** (Aesop): unfair obstruction—citizenship means not blocking others from public goods.
    - **The Boy Who Cried Wolf** (Aesop): civic trust—community safety depends on credibility and responsibility.
    - **The Belly and the Members** (ancient fable tradition): social interdependence—each role supports the whole community.
  - **Parables**
    - **The Good Samaritan**: neighborliness as civic duty—help based on need, not tribe.
    - **The Persistent Widow**: civic perseverance—advocacy and insistence on justice.
    - **The Talents**: stewardship—use what you have for something beyond yourself.
    - **The Two Sons**: citizenship is follow-through; not just promises or slogans.
    - **The Rich Fool**: private gain without public responsibility is shortsighted.
    - **The Sheep and the Goats**: moral accounting tied to how we treat others—community care as obligation.
  - **Fairy Tales**
    - **The Emperor’s New Clothes**: civic courage—truth-telling protects the public from collective self-deception.
    - **The Little Match Girl**: social responsibility—warning about community neglect of vulnerable people.
    - **The Elves and the Shoemaker**: reciprocity—gratitude and fair return strengthen community bonds.
    - **Cinderella**: dignity and fair recognition—social standing shouldn’t erase someone’s worth.
    - **The Ugly Duckling**: belonging and inclusion—communities mature when they make room for difference.
    - **The Three Little Pigs**: preparedness—responsible choices reduce risk for self and others.

##### Leadership

ID: HUMANITY.ELEMENTS.VALUES.LEADERSHIP
TAGS: [[HUMANITY:LEADERSHIP]]

Guiding, inspiring, and supporting others toward a common goal, including our [[HUMANITY:VALUES]], [[HUMANITY:VISION]], and [[HUMANITY:MISSION]]. It involves making ethical decisions, fostering collaboration, and ensuring that the needs of individuals, families, and communities are met. Effective leadership requires responsibility, integrity, and a commitment to justice, fairness, and the well-being of those being led.

- **Included by Value**: [[HUMANITY:JUSTICE]]
- **Includes Values**: None
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #5E35B1
    - #87B135
    - #3587B1
    - #B15E35
    - #35B15E
    - #B13587
  - **Symbols**
    - **Torch / Beacon**: leadership as illumination—setting direction when others can’t see the path.
    - **Compass**: orienting a group around purpose and values, especially under pressure.
    - **Bridge**: connecting people across differences; enabling cooperation and shared outcomes.
    - **Helm / Ship’s Wheel**: steering through uncertainty; responsibility for navigation and safety.
    - **Mountain Peak / Summit Flag**: shared goal-setting and perseverance toward collective achievement.
    - **Lighthouse**: steady guidance that prevents harm; reliability over charisma.
    - **Shepherd’s Crook**: protective stewardship—guiding a community and caring for the vulnerable.
- **Literary Elements**
  - **Proverbs**
    - “**Lead by example.**” — leadership is demonstrated in behavior, not just words.
    - “**A fish rots from the head down.**” — poor leadership spreads harm through the whole group.
    - “**Heavy is the head that wears the crown.**” — leadership carries weight, responsibility, and accountability.
    - “**The captain goes down with the ship.**” — leaders are expected to accept responsibility in crisis.
    - “**If you want to go fast, go alone; if you want to go far, go together.**” — leadership builds durable teamwork, not solo wins.
    - “**Many hands make light work.**” — effective leaders coordinate shared effort and empower others.
    - “**Too many cooks spoil the broth.**” — leadership includes clear roles and decision-making to prevent chaos.
  - **Quotations**
    - “**The buck stops here.**” ~ Harry S. Truman.
    - “**Leadership and learning are indispensable to each other.**” ~ John F. Kennedy, remarks prepared for delivery in Dallas (Nov. 22, 1963).
    - “**…the only thing we have to fear is fear itself…**” ~ Franklin D. Roosevelt, *First Inaugural Address* (Mar. 4, 1933).
    - “**Ultimately, a genuine leader is not a searcher for consensus but a molder of consensus.**” ~ Martin Luther King Jr., speech transcript.
    - “**It is better to lead from behind and to put others in front… You take the front line when there is danger.**” ~ Nelson Mandela.
    - “**Regard your soldiers as your children… look upon them as your own beloved sons, and they will stand by you even unto death.**” ~ Sun Tzu, *The Art of War*.
    - “**That which is not good for the bee-hive, cannot be good for the bee.**” ~ Marcus Aurelius, *Meditations*.
  - **Myths**
    - **Theseus and the Minotaur** (Greek): leadership as courage + responsibility—entering danger to protect the community.
    - **Odysseus’ voyage home** (Greek): leadership under uncertainty—strategy, endurance, and moral choices affect everyone.
    - **Gilgamesh as king of Uruk** (Mesopotamian): a “bad ruler to responsible ruler” arc—power must serve the people.
    - **Yu the Great taming the flood** (Chinese): leadership through public service—sacrifice and coordination for collective survival.
    - **Odin’s sacrifices for wisdom** (Norse): leadership requires costly commitment to insight and long-term consequences.
    - **Romulus and the founding of Rome** (Roman): institution-building—leadership creates order, laws, and shared identity (and warns about faction).
    - **Athena vs. Poseidon (founding of Athens)** (Greek): leadership as choosing civic flourishing over brute force.
  - **Folktales**
    - **Stone Soup** (European): leaders catalyze contribution—turning distrust into cooperation.
    - **The Empty Pot** (Chinese): legitimacy in leadership—honesty and fairness as the basis for authority.
    - **The Bremen Town Musicians** (German): shared leadership—weak individuals become strong through alliance.
    - **Anansi and the Pot of Wisdom** (West African/Akan): leaders can’t hoard what others need; wisdom must circulate.
    - **King Solomon’s judgment** (ancient Near Eastern tradition): leadership as discernment—seeking truth over appearances.
    - **Robin Hood cycle** (English legend): leadership as protection—standing against corruption for the vulnerable.
    - **The Emperor and the Nightingale** (Hans Christian Andersen): leadership must value what is real and life-giving over what is flashy.
  - **Fables**
    - **The Frogs Who Desired a King** (Aesop): warning about choosing leaders carelessly—and tolerating tyranny out of impatience.
    - **The Lion and the Mouse** (Aesop): humility in leadership—today’s “small” ally may be tomorrow’s savior/rescuer.
    - **The Bundle of Sticks** (Aesop): leadership strengthens unity—together is harder to break.
    - **The Dog in the Manger** (Aesop): misuse of power—blocking others from what you won’t use harms the whole group.
    - **The Boy Who Cried Wolf** (Aesop): leadership credibility—trust is a public resource that’s hard to rebuild.
    - **The Wolf and the Lamb** (Aesop): unjust leadership invents excuses—power without ethics becomes predation.
  - **Parables**
    - **The Good Samaritan**: leadership as moral initiative—doing what’s right without needing permission or praise.
    - **The Talents**: stewardship—leaders must responsibly develop what they’ve been entrusted with.
    - **The Wise and Foolish Builders**: leadership foundations—durability comes from integrity, not image.
    - **The Lost Sheep**: leadership as care—attention to the vulnerable, not only the majority.
    - **The Persistent Widow**: principled persistence—leaders keep pushing for justice when it’s unpopular.
    - **The Blind Leading the Blind**: caution against unqualified or self-deceived leadership that harms followers.
  - **Fairy Tales**
    - **The Emperor’s New Clothes**: leadership failure through vanity; good leadership welcomes truth-telling.
    - **The Pied Piper of Hamelin**: leaders must honor commitments; broken trust has community-wide consequences.
    - **The Goose Girl**: rightful authority restored—leadership legitimacy depends on truth and integrity.
    - **The Snow Queen**: leadership as rescue and steadfast love—guiding someone back from cold detachment.
    - **The Little Match Girl**: an indictment of civic/leader neglect—communities are judged by how they treat the vulnerable.
    - **King Thrushbeard**: leadership and character—humility and perspective reshape how power is used.

##### Persistence

ID: HUMANITY.ELEMENTS.VALUES.PERSISTENCE
TAGS: [[HUMANITY:PERSISTENCE]]

Determination to continue striving toward a goal despite obstacles, setbacks, or difficulties. It requires resilience, dedication, and a belief in long-term success. Persistence involves staying focused on a goal, not giving up when challenges arise, and continuously working toward success. Persistence helps ensure that progress is made and goals are achieved, despite obstacles or delays.

- **Included by Value**: [[HUMANITY:INTERDEPENDENCE]]
- **Includes Values**: [[HUMANITY:COURAGE]] and [[HUMANITY:HOPE]]
- **Visual Elements**
  - **Hexadic Color Scheme**
    - #F57C00
    - #007AF5
    - #F5007A
    - #00F57A
    - #7A00F5
    - #7AF500
  - **Symbols**
    - **Tortoise**: steady progress over time—keeps moving even when it’s slow.
    - **Mountain / Summit**: long, difficult climb that rewards endurance.
    - **Anvil**: “forged by repetition”—strength built through ongoing effort.
    - **Seedling breaking through soil**: growth that continues despite resistance.
    - **Marathon / Long road**: persistence as pacing and finishing, not sprinting.
    - **Lighthouse**: staying fixed on a guiding goal through storms.
- **Literary Elements**
  - **Proverbs**
    - “**If at first you don’t succeed, try, try again.**” — persistence after failure.
    - “**Slow and steady wins the race.**” — consistent effort beats bursts.
    - “**Rome wasn’t built in a day.**” — worthwhile goals take time.
    - “**Where there’s a will, there’s a way.**” — determination finds paths.
    - “**Fall seven times, stand up eight.**” — resilience as repeated return.
    - “**Little by little, a little becomes a lot.**” — accumulation through consistency.
  - **Quotations**
    - “**Nothing in the world can take the place of persistence… Persistence and determination alone are omnipotent.**” — *Calvin Coolidge*
    - “**If there is no struggle there is no progress.**” — *Frederick Douglass*, “West India Emancipation” (August 3, 1857)
    - “**Ever tried. Ever failed. No matter. Try again. Fail again. Fail better.**” — *Samuel Beckett*, *Worstward Ho* (1983)
    - “**Most of the important things in the world have been accomplished by people who have kept on trying when there seemed to be no hope at all.**” — *Dale Carnegie*, *How to Stop Worrying and Start Living* (1948)
    - “**It is hard to fail, but it is worse never to have tried to succeed.**” — *Theodore Roosevelt*, “The Strenuous Life” (April 10, 1899)
    - “**Through perseverance, many people win success out of what seemed destined to be certain failure.**” — *Benjamin Disraeli*
  - **Myths**
    - **Sisyphus** (Greek): persistence as enduring effort—even under heavy burden.
    - **Odysseus’ return to Ithaca** (Greek): years of setbacks; keeps striving toward home.
    - **Demeter’s search for Persephone** (Greek): relentless devotion in the face of loss.
    - **Isis reassembling Osiris** (Egyptian): patient, determined restoration after catastrophe.
    - **The Labors of Heracles** (Greek): repeated trials that demand endurance and resolve.
  - **Folktales**
    - **The Empty Pot** (Chinese): persistence + integrity—showing up honestly despite fear.
    - **The Little Hero of Haarlem** (Dutch): holding the dike—endurance that prevents disaster.
    - **The Magic Porridge Pot** (European): persistence in solving a problem you caused—learning to stop/adjust.
    - **The Stonecutter** (Japanese): repeated attempts to gain power reveal the need to persist wisely, not endlessly chase.
    - **The Boy Who Drew Cats** (Japanese): persistence in a craft saves him—skill built through continued practice.
  - **Fables**
    - **The Tortoise and the Hare** (Aesop): consistency beats flash.
    - **The Ant and the Grasshopper** (Aesop): sustained work prepares for hard seasons.
    - **The Crow and the Pitcher** (Aesop): keeps trying different tactics until it works.
    - **The Lion and the Mouse** (Aesop): persistence in small efforts can change outcomes.
    - **The Farmer and His Sons** (Aesop): continued labor yields “treasure” (a harvest).
  - **Parables**
    - **The Persistent Widow**: persistence in seeking justice over time.
    - **Friend at Midnight**: repeated asking eventually opens the door.
    - **The Sower**: outcomes depend on continuing through obstacles and conditions.
    - **The Talents**: steady, faithful effort grows what you’ve been given.
    - **The Wise and Foolish Builders**: persistence means building on a foundation that survives storms.
  - **Fairy Tales**
    - **The Snow Queen**: Gerda’s long journey—love expressed as persistence.
    - **Cinderella**: endurance through unfairness; keeps hope and continues forward.
    - **Jack and the Beanstalk**: repeated risk-taking and follow-through to change fortune.
    - **Hansel and Gretel**: persistence and cleverness to survive and escape.
    - **East of the Sun and West of the Moon**: determined quest across impossible distances.
