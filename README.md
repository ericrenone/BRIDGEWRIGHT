# BRIDGEWRIGHT
## The Load-Bearing Connection Framework for Cross-Domain Invention

> A connection between two fields is worth exactly what it can carry.
> Bridgewright is a method for finding connections, loading them until they either hold or break, and keeping only the ones that hold.

---

## Contents

1. [Why this framework exists](#1-why-this-framework-exists)
2. [The core claim](#2-the-core-claim)
3. [What the evidence says](#3-what-the-evidence-says)
4. [The framework at a glance](#4-the-framework-at-a-glance)
5. [Stage I — Footing: build the bottleneck ledger](#5-stage-i--footing)
6. [Stage II — Span: search at the right distance](#6-stage-ii--span)
7. [Stage III — Alignment: map structure, not surface](#7-stage-iii--alignment)
8. [Stage IV — Load test: make it able to fail](#8-stage-iv--load-test)
9. [Stage V — Anchoring: embed the new in the known](#9-stage-v--anchoring)
10. [The two engines: association and control](#10-the-two-engines)
11. [Rhythm: pressure, release, return](#11-rhythm)
12. [Working with machines without converging on the mean](#12-working-with-machines)
13. [Metrics that cannot be gamed by fluency](#13-metrics)
14. [Failure modes and their signatures](#14-failure-modes)
15. [A 30-day practice](#15-a-30-day-practice)
16. [Worked example](#16-worked-example)
17. [Glossary](#17-glossary)
18. [Sources](#18-sources)

---

## 1. Why this framework exists

Most people with broad technical exposure can propose a plausible mashup of two fields. Language models can propose hundreds an hour. Generating combinations is no longer scarce. What is scarce is a combination that still stands after someone has pushed on it.

The literature on creativity, analogy, and innovation has quietly converged on this point from several directions at once:

- Bibliometrics shows that the highest-impact work is not the most novel work. It is conventional work with a small injection of unusual pairing.
- Cognitive neuroscience shows that the ability to generate novel associations and the ability to judge their appropriateness are separate systems, supported by separate brain networks, and that strong creators couple them rather than favor one.
- Design research shows that distant inspiration raises novelty in the lab but, on real innovation platforms, nearer sources often produce the better ideas, because distant sources are harder to map correctly.
- Open-innovation research shows that outsiders win problem-solving contests at a higher rate, but only when they search hard and search widely.
- Peer-review research shows that novelty is not punished when it is well situated in existing work, and that it is punished (or ignored for years) when it is not.

Every one of these results points to the same structure: **the connecting instinct is an opening move, and its value is decided entirely by what happens next.** Bridgewright is a framework for the "what happens next."

---

## 2. The core claim

A cross-domain connection is **load-bearing** when it satisfies four conditions:

| Condition | Question it answers | Test |
|---|---|---|
| **Structural** | Do the two domains share a *mechanism*, not just a vocabulary? | Relational mapping holds when surface features are stripped |
| **Reusable** | Does one component do work in both the source and the target? | The same primitive serves at least two roles |
| **Falsifiable** | Can you name the observation that would break it? | A specific prediction, written before testing |
| **Anchored** | Can a specialist in the target field see where it sits? | The connection is expressed in the target field's own terms and prior work |

A connection that meets all four can carry weight: a prototype, a paper, a product, a decision. A connection that meets fewer is a *sketch*. Sketches are useful; they are where every load-bearing connection starts. But they must not be mistaken for the finished thing, and the central discipline of the framework is refusing to let a sketch feel like a bridge.

---

## 3. What the evidence says

This section summarizes the findings the framework is built on. Each later stage cites the lines it uses.

### 3.1 Novelty pays when it is embedded in convention
Analysis of 17.9 million papers found that the works with the highest probability of becoming top-cited "hits" were those grounded in highly conventional combinations of prior work *with* a tail of unusual pairings. Papers combining high conventionality and high tail-novelty had a hit rate of about 9 per 100, versus under 6 per 100 for papers that were conventional without the novelty injection, and about 5 per 100 for papers that were novel without the conventional grounding. Novelty and conventionality are not opposites; the winning configuration uses both.

### 3.2 Novel work is riskier, slower to be recognized, and higher-gain in the long run
A study of all Web of Science articles from a single year found that highly novel papers (those making distant, first-ever combinations of referenced journals) were roughly 40% more likely to become top-1% cited in the long run, were cited in a broader set of disciplines, and had higher variance in outcomes. They were also systematically under-recognized in short citation windows and published in lower-impact-factor venues. Novelty is rare (about one paper in nine) and its payoff is delayed.

### 3.3 Peer review is not anti-novelty — it is anti-unsituated-novelty
Review files from 49 life- and physical-science journals showed no evidence that novel manuscripts were less likely to be accepted. Reviewers favored novel research that was *well situated in the existing literature*. The barrier is not newness; it is newness that arrives without a map.

### 3.4 Outsiders win, but only when they search hard
Across 166 broadcast-search science challenges involving over 12,000 solvers, the probability of producing a winning solution *rose* with the distance between the solver's expertise and the problem's field. A follow-up study showed the mechanism: distant solvers succeeded when they exerted high cognitive-search effort, and near solvers succeeded when they drew on a wide variety of knowledge elements (high search variation). Distance alone is not the advantage; distance plus effort is.

### 3.5 Intermediate recombination has the highest impact
In biopharmaceutical patents, the relationship between how much an invention recombines and how much impact it has is curvilinear. Inventions combining components from *local, adjacent, and distant* domains together had the highest technological impact — more than purely local or purely distant combinations. Related work finds that knowledge unused for a long time ("dormant" components) is, surprisingly, as valuable to recombine as recently rejuvenated knowledge.

### 3.6 Far analogies help in the lab; mapping difficulty erodes the gain in the field
Controlled studies show that far-field, less-common examples raise the novelty and quality of design ideas, and that merely *solving* far analogies induces a relational mindset that transfers to later tasks. But a text analysis of hundreds of design concepts on a live innovation platform found that conceptually *nearer* sources were associated with more creative outcomes. The reconciliation offered by the design literature is that usefulness of analogical distance is curvilinear: very near sources add little, very far sources are too hard to map correctly, and the productive band sits in between — and moves with the solver's skill.

### 3.7 Novelty and appropriateness run on different engines
A 2024 study combining behavioral tasks with resting-state connectome modeling found that the novelty of generated ideas depends more on semantic associative ability and is predicted by interactions within the default-mode network, while the appropriateness of ideas depends more on executive control and is predicted by a different connectivity pattern. Separate work on remote-associate tasks found that more remote associations recruit the executive and attention networks *in addition to* the default network — the harder the leap, the more control is needed to land it. Large-sample imaging work identifies "control-default hubs" — regions that bridge both networks — as the connectivity most strongly tied to creative ability.

### 3.8 Incubation works, and it works better when the break is light
A meta-analysis of 117 studies found a reliable positive effect of incubation breaks on creative problem solving, strongest when the break involved an undemanding task rather than rest or a hard task. Recent preregistered work finds that task-related mind wandering during the break — not spontaneous drift — predicts the post-break gain.

### 3.9 Constraints help up to a point
A cross-disciplinary review of constraints on creativity finds an inverted-U: too few constraints leave the search unfocused and familiar paths unchallenged; too many eliminate every interesting path. The useful band depends on experience and available time.

### 3.10 Exaptation is where disruption increasingly comes from
Most radical inventions in a sampled patent set were exaptive — an artifact or technique co-opted for a function it was never designed for. Newer work shows that while the average disruptiveness of papers and patents has declined for decades, the share of innovation drawing on cross-domain, functionally shifted knowledge has risen, and exaptation measurably raises disruptiveness.

### 3.11 Brokers see options others cannot
People whose networks span structural holes between groups are more likely to express ideas, less likely to have them dismissed, and more likely to have them judged valuable. The mechanism is vision: brokerage exposes a person to heterogeneous beliefs and practices, and new ideas emerge from selection and synthesis across the holes.

### 3.12 Machines raise the individual floor and lower the collective ceiling
In a randomized experiment with 300 writers, access to AI-generated ideas made stories more creative and better written — especially for less creative writers — but made the stories *more similar to each other*. Individual gain, collective homogenization. Separately, benchmark work shows that current language models recognize near analogies easily and struggle with far, cross-domain analogies without scaffolding.

### 3.13 Analogy can be scaled by representing purpose and mechanism
Research on computational analogy found that extracting a problem's *purpose* and its *mechanism* as separate representations allows retrieval of structurally analogous solutions from distant fields with far better precision than keyword similarity. The three barriers to analogical innovation at scale are fixation, search cost, and the complexity of real problems that need multiple analogies at multiple levels.

---

## 4. The framework at a glance

```
          ┌─────────────────────────────────────────────────────────────┐
          │                      BRIDGEWRIGHT                          │
          ├─────────────┬─────────────┬─────────────┬─────────┬─────────┤
          │  I. FOOTING │  II. SPAN   │ III. ALIGN  │ IV. LOAD│ V. ANCHOR│
          │             │             │             │  TEST   │         │
          │ Know what   │ Search at   │ Map the     │ Make it │ Embed it │
          │ is stuck,   │ the right   │ mechanism,  │ able to │ in the   │
          │ in purpose/ │ distance,   │ not the     │ fail;   │ target   │
          │ mechanism   │ three rings │ vocabulary  │ smallest│ field's  │
          │ form        │ at once     │             │ build   │ frame    │
          └─────────────┴─────────────┴─────────────┴─────────┴─────────┘
                 ▲                                                  │
                 └──────────── the ledger grows from every test ────┘

   Running underneath all five stages:
   • Two engines   — association generates, control evaluates, hubs couple them
   • Rhythm        — pressure, release, return
   • Machine hedge — use models for span, never for alignment or load test
```

The stages are sequential for any single connection, but a working practitioner has many connections in flight, each at a different stage. The *ledger* (Stage I) is the persistent artifact; everything else operates on entries in it.

---

## 5. Stage I — Footing
### Build the bottleneck ledger

**Principle.** Connectors think "what is stuck?" before "what is new?" A tool from another field is only valuable relative to a bottleneck, so the first asset is a maintained list of bottlenecks, each written in a form that makes it searchable across domains.

**Why this stage comes first.** The scaling-analogy work (§3.13) found that the single most useful thing a human can do to enable cross-domain retrieval is to separate a problem's *purpose* from its *mechanism*. Reformulation research (the Gestalt tradition, re-representation, and inventive-design methods such as TRIZ) agrees that the hardest problems are usually hard in their *stated* representation and become tractable once restated. Representation is where the leverage is.

**The ledger entry.** Every bottleneck gets a card with five fields:

```
BOTTLENECK #___
Purpose      What must be achieved, stated without any reference to the current method.
Mechanism    How it is currently attempted, and the step where it breaks.
Constraint   What makes the break hard (cost, time, physics, regulation, scale).
Invariant    What must stay true in any solution (the non-negotiables).
Form         The abstract shape of the problem in one line, e.g.
             "track a slowly drifting reference without pausing the main task."
```

The **Form** line is the search key. It should contain no domain nouns. If you cannot write it without domain nouns, you have not yet separated purpose from mechanism, and you are not ready to search.

**Practices.**
- Keep the ledger as a living file. Add entries as you encounter stuck problems in reading, work, or conversation — not only your own.
- Rewrite each Form line at least three ways. Different abstractions retrieve different sources. A problem stated as "remove noise" retrieves filters; stated as "distinguish signal from a known interferer" it retrieves cancellation; stated as "estimate a hidden state" it retrieves trackers.
- Record the *constraint* carefully. The constraints are what will later disqualify most candidate sources, so writing them down early saves the most time of any step in the framework.
- Apply the inverted-U on constraints (§3.9): if a bottleneck has no constraints listed, add the real ones; if it has so many that no solution is conceivable, find the one or two that are actually binding and park the rest.

**Exit criterion.** A Form line that a stranger from an unrelated field could read and recognize as something they have seen.

---

## 6. Stage II — Span
### Search at the right distance

**Principle.** Search three rings at once, and spend effort in proportion to distance.

**Why.** The impact evidence (§3.5) says the best inventions draw from *local, adjacent, and distant* sources simultaneously, not from the farthest source available. The contest evidence (§3.4) says distance pays only with effort. The design evidence (§3.6) says the productive distance band is curvilinear and depends on the searcher's mapping skill. Together these rule out two popular strategies — "stay in your lane" and "go as far as possible" — and replace them with a portfolio.

**The three rings.**

| Ring | Definition | What it contributes | Risk |
|---|---|---|---|
| **Local** | Your own field's standard toolkit | Appropriateness, credibility, the conventional base | Fixation; nothing new |
| **Adjacent** | Fields that share your mathematics or your materials | The most *reliably* mappable new mechanisms | Feels novel but is often already known to insiders |
| **Distant** | Fields sharing only the Form line | The tail novelty that produces hits | High mapping failure rate; effort-intensive |

Every search for a bottleneck should return at least one candidate from each ring. A connection built only from the distant ring has no conventional base to anchor to (§3.1); a connection built only from the local ring is not a connection.

**Search moves, in order of cost.**

1. **Form-line search.** Query literature, patents, and people with the Form line, not the domain nouns. This is the cheapest distant-ring move and the one the scaling-analogy work validated.
2. **Dormant-knowledge sweep.** Look for techniques in your *own* field that have not been used in a decade (§3.5). Recombinant lag is U-shaped: the very old is as valuable as the very fresh.
3. **Exaptive scan.** Ask of any artifact you already have: *what else does this do that nobody designed it to do?* (§3.10). Exaptation is a search over latent function, not over fields.
4. **Broker inventory.** List the groups you belong to that do not talk to each other (§3.11). The structural holes in your own network are the cheapest distant-ring sources available because you already speak both languages.
5. **Deliberate marginality.** For a bottleneck that has resisted everything above, bring it to someone technically far from it, state only the Form line and constraints, and ask what their field does. Expect a low hit rate and a high payoff when it hits.

**Effort rule.** Record, for each candidate, which ring it came from. Budget time per candidate as *local: 1, adjacent: 2, distant: 4*. If a distant candidate cannot be mapped (Stage III) within its budget, shelve it with a note rather than forcing it. The contest evidence says distance without effort fails; it does not say effort must be unbounded.

**Exit criterion.** A short list of candidate sources, tagged by ring, each with the specific mechanism it offers written in one sentence.

---

## 7. Stage III — Alignment
### Map structure, not surface

**Principle.** A connection is real when the *relations* line up, not when the *words* do. Structure-mapping theory holds that analogical mapping is a one-to-one alignment of relational structure — and that the deepest analogies match higher-order relations (relations between relations) rather than objects or attributes.

**Why this is the stage where most connections die.** The benchmark evidence (§3.12) is blunt: far analogies are hard even for very capable systems, and the failure mode is always the same — surface similarity mistaken for structural similarity. A "buzzword pile" is a set of sources that share vocabulary with the target and nothing else. It feels exactly as coherent as a real connection. The only defense is an explicit mapping.

**The alignment table.** For each candidate source, fill this in:

```
SOURCE: ______________________          TARGET: BOTTLENECK #___

Source element        →   Target element        Relation preserved?   Role
───────────────────────────────────────────────────────────────────────────
(object/quantity)     →   (object/quantity)     yes / no / partial    ___
(object/quantity)     →   (object/quantity)     yes / no / partial    ___
(relation A→B)        →   (relation A'→B')      yes / no / partial    ___
(higher-order:        →   (higher-order:        yes / no / partial    ___
 "A causes B when C")     "A' causes B' when C'")

Unmapped source elements (must be inert, not load-bearing): ____________
Unmapped target elements (must be inert, not load-bearing): ____________
```

**Three alignment tests, applied in order.**

1. **The strip test.** Rewrite the source mechanism with every domain noun replaced by a letter. Then rewrite the target the same way. If the two abstracted descriptions are the same text, the mapping is structural. If they are only the same *topic*, it is surface.
2. **The reuse test.** Identify at least one primitive (an operation, a component, a data structure, a procedure) that would serve *two distinct roles* in the combined system — for example, the same operation that performs the main task also performs the update that keeps the main task calibrated. Reuse like this is the single most reliable signature of a structural fit, because it cannot arise from vocabulary overlap; it arises only when the underlying operations are the same. A connection with no reuse is a juxtaposition, and juxtapositions rarely survive Stage IV.
3. **The inertness test.** Everything in the source that does *not* map onto the target must be shown to be inert — it must not be doing work the source's success depended on. The classic failure is importing a technique whose real performance came from an unmapped element (a special material, a favorable regime, an assumption the target violates).

**Mapping at multiple levels.** Real bottlenecks usually need more than one analogy (§3.13): one for the overall architecture, others for the subproblems. Keep a separate alignment table for each level, and be explicit about which level each source is being used at. A source that maps well at the architecture level and poorly at the component level is still useful — at the architecture level only.

**Exit criterion.** An alignment table in which every load-bearing relation in the target has a mapped counterpart, at least one reuse primitive is named, and every unmapped source element is marked inert with a reason.

---

## 8. Stage IV — Load test
### Make it able to fail

**Principle.** A connection you cannot name a breaking observation for is a connection you do not understand. The difference between a connecting instinct and a proven connection is a prediction that could have failed and did not.

**Why.** Fluent generation is cheap, and the fluency of a proposal carries no information about its truth (§1, §3.12). The only signal that distinguishes a load-bearing connection from a sketch is a check that the connection could lose. This stage exists to manufacture that signal as cheaply as possible.

**The load-test record.** Before building anything, write:

```
CONNECTION: SOURCE ___ → BOTTLENECK #___

Prediction     If the mapping is structural, then when I ____, I will observe ____.
Breaker        If instead I observe ____, the mapping fails at relation ____.
Regime         The prediction holds only when ____ (the constraints under which the
               source's mechanism is known to work).
Smallest build The minimum artifact that can produce the observation: ____.
Budget         ____ hours / ____ currency. Hard stop.
```

**Rules for the smallest build.**
- It must exercise the *reuse primitive* from Stage III. If the shared primitive does not actually serve both roles in the build, the connection was surface-level and you have found out at the lowest possible cost.
- It must be built *outside* the favorable regime at least once. The most common way a connection fails is that it works in the easy case (well-conditioned, low-noise, small-scale) and degrades faster than the incumbent in the hard case. Test the hard case early.
- It must produce a number that can be compared to a reference. "It works" is not an observation. "Error stayed at the arithmetic floor after 10,000 iterations, where the incumbent drifted 20× faster" is.
- It must be small enough that its *failure* is cheap. The purpose of the build is not to succeed; it is to find out.

**Splitting claims.** A connection usually carries several claims at once: the structural ones (the mapping holds; the primitive is reused), the performance ones (it is faster, cheaper, smaller), and the contextual ones (someone will need it). Test them separately and record them separately. It is normal — the typical pattern in early-stage work — for the structural claims to survive and the performance and contextual claims to fail. That outcome is not a failed connection; it is a correctly scoped one. Record which claims held.

**Exit criterion.** A load-test record with the observation filled in, and a one-line verdict: *holds / holds in regime ___ only / fails at relation ___*.

---

## 9. Stage V — Anchoring
### Embed the new in the known

**Principle.** A connection that holds is still invisible until a specialist in the target field can see where it sits. The highest-impact work is unusual pairing embedded in conventional framing (§3.1), and review is friendly to novelty that is well situated and hostile to novelty that is not (§3.3).

**Why connectors neglect this stage.** The person who made the connection sees both fields at once; the audience sees one. Anchoring is the deliberate act of rebuilding the connection from inside the target field, using its prior work, its vocabulary, and its benchmarks, so that the audience does not have to cross the span themselves.

**Anchoring moves.**

1. **Cite the conventional base first.** Lead with what the target field already knows and does. The novel element should arrive as a modification to a familiar structure, not as a replacement for it.
2. **Translate the source into target terms.** Do not ask the audience to learn the source field. Present the imported mechanism as if it had been invented inside the target, then footnote its origin.
3. **Name the regime.** State precisely where the connection holds (from Stage IV) and where it does not. Specialists trust bounded claims and distrust unbounded ones.
4. **Report the breaker.** Say what observation would have falsified the connection and that it did not occur. This is the single most credibility-building sentence available to an outsider.
5. **Expect delayed recognition and plan for it.** Novel work is under-cited in short windows and over-cited in the long run (§3.2). Do not read early silence as rejection. Place the work where the *foreign* field that will eventually cite it can find it.

**The honesty clause.** Anchoring is not spin. Every claim that failed in Stage IV is stated as failed. The connection's value is in the claims that held, and listing the ones that did not is what makes the ones that did believable.

**Exit criterion.** A description of the connection that a target-field specialist can evaluate without knowing the source field, including the conventional base, the regime, the breaker, and the failed claims.

---

## 10. The two engines

Novelty and appropriateness are produced by different cognitive systems (§3.7). The associative engine — semantic memory, spreading activation, the default-mode network — generates distant candidates. The control engine — working memory, inhibition, goal maintenance, the executive network — evaluates and prunes them. Strong creators are not those with the strongest single engine; they are those whose two engines are *coupled*, and the harder the associative leap, the more control is needed to land it.

Bridgewright assigns the engines to stages deliberately:

| Stage | Dominant engine | Secondary |
|---|---|---|
| I. Footing | Control (precise representation) | Association (alternative Forms) |
| II. Span | Association (wide retrieval) | Control (ring tagging, effort budget) |
| III. Alignment | Control (one-to-one mapping) | Association (noticing higher-order relations) |
| IV. Load test | Control | — |
| V. Anchoring | Control (audience modeling) | Association (translation) |

Two consequences follow.

**Do not run both engines on the same pass.** Generating candidates and evaluating them in the same sitting produces the worst of both: association is suppressed by premature judgment, and judgment is contaminated by the fluency of fresh ideas. Separate the passes in time. Generate in one session; align and test in another.

**The connecting instinct is an association-engine skill.** Fit-finding — noticing that a distant mechanism matches a Form line — is fast, feels effortless, and is often right about the *structure*. Claim-checking is a control-engine skill. It is slow, effortful, and is where most people's training is thinnest. The typical early-stage profile is strong instinct, weak checking. The framework exists to supply the checking that the instinct does not.

---

## 11. Rhythm

**Pressure, release, return.** Incubation reliably improves creative problem solving (§3.8), with three conditions: a serious preparation period first, a break filled with light activity rather than rest or hard work, and a return to the problem. Task-related mind wandering during the break — the problem drifting in and out of attention — is what predicts the gain, not blank drift.

Applied to the stages:

- **Pressure** is Stages I and III: hard, controlled work on representation and mapping. Do not shortcut it; longer preparation produces larger incubation effects.
- **Release** is a deliberate gap before Stage II search, and again between Stage III and Stage IV. Fill it with something undemanding. The alignment table you could not complete often completes itself on the walk.
- **Return** is scheduled, not left to chance. Put the return on a calendar. The effect requires actually coming back.

**Constraints as rhythm.** Impose a constraint when search is drifting (too open) and remove one when search is empty (too closed). The inverted-U (§3.9) is navigated by adjusting constraints up and down, not by setting them once.

---

## 12. Working with machines

Language models are extraordinary span tools and poor alignment tools. The evidence (§3.12): they raise individual output quality, especially for people with less prior facility; they produce outputs that converge on each other; and they handle near analogies well and far analogies poorly without scaffolding.

**Use them for Stage II.** Feed a model the Form line (never the domain nouns) and ask what fields solve this shape of problem. Ask for the adjacent and distant rings explicitly and separately. Ask for dormant techniques and exaptive uses of named artifacts. These are retrieval tasks, and retrieval is what the models are good at.

**Do not let them do Stage III or IV.** A model will produce a plausible-sounding alignment table for any pair of sources, because plausibility is what it optimizes. The strip test, the reuse test, and the inertness test must be performed by a person who can be wrong and knows it. The load test must produce an observation from the world, not a prediction from a model.

**Hedge against convergence.** If every practitioner uses the same model with the same prompt, every practitioner retrieves the same distant sources, and the collective distribution of connections narrows. Three hedges:
1. Run Form-line searches through a human broker (§6, move 4) *as well as* a model, and compare what each returned.
2. Seed the model with your own dormant-knowledge sweep rather than asking it to start from zero.
3. Keep a private ledger. The ledger is the part of the process that is yours; a model given the same bottleneck will not have your Form lines, your constraints, or your network's holes.

**Scaffold far analogies.** When asking a model for distant sources, give it solved examples of structural (not surface) analogies first, and ask it to show the relation mapping, not just the source. This is the configuration under which model performance on far analogies improves.

---

## 13. Metrics

These are chosen because none of them can be raised by generating more fluently.

| Metric | Definition | Target |
|---|---|---|
| **Survival ratio** | Connections that pass Stage IV ÷ connections that enter Stage III | Track over time; rising ratio means alignment skill is improving |
| **Reuse count** | Number of primitives serving two or more roles in a surviving connection | ≥ 1 for every connection that reaches Stage V |
| **Ring mix** | Fraction of surviving connections that draw on all three rings | Rising |
| **Claim split** | For each tested connection: structural claims held / performance claims held / contextual claims held | Record separately; expect structural > performance > contextual |
| **Breaker rate** | Fraction of Stage IV records with a specific breaker written *before* the build | 100% |
| **Time to breaker** | Hours from a Stage III exit to a Stage IV observation | Falling |
| **Anchor check** | Can a target-field specialist evaluate the Stage V description without source-field knowledge? (yes/no, asked of a real specialist) | Yes |

The one metric to avoid is *number of connections proposed*. It rewards the cheap part of the process and is inflated by machine assistance.

---

## 14. Failure modes

| Failure | Signature | Stage where it should have been caught |
|---|---|---|
| **Buzzword pile** | Sources share vocabulary with the target; strip test produces different abstractions | III — strip test |
| **Juxtaposition** | Two mechanisms sit side by side; no primitive serves two roles | III — reuse test |
| **Hidden carrier** | Connection works in the build, but performance came from an unmapped source element | III — inertness test; IV — hard-regime build |
| **Favorable-regime fallacy** | Works in the easy case, degrades faster than the incumbent in the hard case | IV — out-of-regime build |
| **Unfalsifiable instinct** | No breaker can be written; every outcome is explained | IV — breaker required before build |
| **Fluency trap** | The proposal *sounds* complete; confidence rises with each rewrite and no observation has been made | IV |
| **Orphan novelty** | Connection holds but is presented with no conventional base; reviewers cannot place it | V |
| **Overclaim bleed** | Failed performance claims are quietly dropped rather than reported, contaminating the credibility of the structural claims that held | V — honesty clause |
| **Distance worship** | Only distant-ring sources are pursued; survival ratio collapses | II — three-ring rule |
| **Lane keeping** | Only local-ring sources; nothing is a connection | II — three-ring rule |
| **Same-pass generation** | Candidates judged in the session that produced them; both engines degraded | §10 |
| **Monoculture retrieval** | Every search runs through the same model with the same prompt | §12 |

---

## 15. A 30-day practice

**Week 1 — Footing.**
Build a ledger of ten bottlenecks. For each, write Purpose, Mechanism, Constraint, Invariant, and three Form lines. Do not search yet. End the week by showing three Form lines to someone outside your field and asking whether they recognize the shape.

**Week 2 — Span.**
For five of the ten, run the three-ring search. Use the Form-line search, a dormant-knowledge sweep, and one broker conversation. Tag every candidate by ring. Budget effort 1:2:4. Shelve anything over budget with a note.

**Week 3 — Alignment.**
Take a break of two days with light work. Return. Build alignment tables for the most promising candidate per bottleneck. Apply strip, reuse, and inertness tests. Expect most to fail; record why. Compute the survival ratio into Stage IV.

**Week 4 — Load test and anchor.**
For each surviving connection, write the load-test record *before* building. Build the smallest artifact, including one out-of-regime run. Record the claim split. For any connection that holds, write a one-page Stage V description and give it to a target-field specialist. Ask only: "Can you tell where this sits, and what would break it?"

**End of month.** You have a ledger, a survival ratio, and at least one connection with a written breaker and an observation. That is the difference between an instinct and a result.

---

## 16. Worked example

A deliberately generic example, so the method is visible without domain knowledge.

**Footing.** A team's measurement pipeline has a sensor whose calibration drifts slowly. Current mechanism: pause the pipeline every few hours and recalibrate against a reference. Breaks at: the pause. Constraint: the pipeline must run continuously; compute budget is small; no large memory. Invariant: readings must stay within tolerance at all times.
*Form line:* "Track a slowly drifting reference without pausing the main task, using the main task's own outputs as the teacher."

**Span.** Local ring: scheduled recalibration (the incumbent). Adjacent ring: control systems — observers that estimate hidden state from outputs. Distant ring (via Form-line search): communications receivers, which correct for a drifting channel using their own decoded symbols as the reference, with no pause and no pilot signal.

**Alignment.** Strip test: source = "estimate a slowly varying transform from the difference between received and decided values; apply the estimate to the next received value." Target abstracts to the same text. Reuse test: the operation that applies the correction to incoming data is the same operation that computes the next correction from the residual — one primitive, two roles. Inertness test: the source's performance depends on decisions being mostly correct; the target's tolerance band makes this plausible but it is now a stated assumption, not an inert element — it is carried into the load test as the regime.

**Load test.** Prediction: after a step change in calibration of a given size, the pipeline recovers to tolerance within a bounded number of readings with no pause and no out-of-tolerance reading. Breaker: if recovery requires more than the bound, or any reading leaves tolerance, the mapping fails at the "decisions are mostly correct" relation. Regime: drift rate below a stated threshold. Smallest build: a simulation with the real sensor's noise model, run both inside and outside the drift threshold. Outcome recorded as a claim split: structural claims hold; the "small compute" performance claim holds; a "works at any drift rate" claim fails outside the threshold and is dropped.

**Anchoring.** Written for the measurement team: "A standard recursive estimator, of the kind already used in our control loops, applied to calibration drift so that the pipeline corrects itself from its own in-tolerance readings. Holds for drift below X; above X, the existing scheduled recalibration remains necessary. It would have failed if recovery had exceeded N readings; it did not." Source-field origin in a footnote.

---

## 17. Glossary

**Alignment table** — the explicit one-to-one mapping of source relations onto target relations.
**Anchoring** — expressing a surviving connection in the target field's own conventional frame.
**Bottleneck ledger** — the persistent list of stuck problems, each in purpose/mechanism/constraint/invariant/form representation.
**Breaker** — the observation, written before testing, that would falsify a connection.
**Claim split** — separate recording of structural, performance, and contextual claims and their test outcomes.
**Control-default hubs** — brain regions bridging the executive and default networks; the neural correlate of coupled engines.
**Exaptation** — co-opting an existing artifact or technique for a function it was not designed for.
**Form line** — a one-line abstract statement of a bottleneck's shape, free of domain nouns; the cross-domain search key.
**Inertness test** — verifying that unmapped source elements did no load-bearing work in the source's success.
**Load-bearing connection** — a connection that is structural, reusable, falsifiable, and anchored.
**Recombinant lag** — time since a piece of knowledge was last reused; U-shaped in its relation to impact.
**Reuse primitive** — a single operation or component that serves two distinct roles in the combined system; the signature of structural fit.
**Ring (local / adjacent / distant)** — the three search radii; surviving connections should draw on all three.
**Sketch** — a connection that has not yet passed the load test. Where every real connection begins.
**Strip test** — replacing domain nouns with letters in both source and target to check whether the abstractions coincide.
**Structural hole** — a gap between groups in a network that do not communicate; brokers who span it see options others cannot.
**Survival ratio** — connections passing the load test divided by connections entering alignment.
**Tail novelty** — a small fraction of unusual pairings within an otherwise conventional base; the configuration associated with the highest hit rate.

---

## 18. Sources

- Uzzi, B., Mukherjee, S., Stringer, M., & Jones, B. (2013). Atypical combinations and scientific impact. *Science*, 342(6157), 468–472. https://www.kellogg.northwestern.edu/faculty/jones-ben/htm/atypical_combinations_and_scientific_impact.pdf
- Wang, J., Veugelers, R., & Stephan, P. (2017). Bias against novelty in science: A cautionary tale for users of bibliometric indicators. *Research Policy*, 46(8), 1416–1436. https://www.nber.org/papers/w22180
- Teplitskiy, M., et al. (2022). Is novel research worth doing? Evidence from peer review at 49 journals. *PNAS*. https://pmc.ncbi.nlm.nih.gov/articles/PMC9704701
- Jeppesen, L. B., & Lakhani, K. R. (2010). Marginality and problem-solving effectiveness in broadcast search. *Organization Science*, 21(5), 1016–1033. https://pubsonline.informs.org/doi/10.1287/orsc.1090.0491
- Acar, O. A., & van den Ende, J. (2016). Knowledge distance, cognitive-search processes, and creativity: The making of winning solutions in science contests. *Psychological Science*, 27(5). https://journals.sagepub.com/doi/full/10.1177/0956797616634665
- Keijl, S., Gilsing, V. A., Knoben, J., & Duysters, G. (2016). The two faces of inventions: The relationship between recombination and impact in pharmaceutical biotechnology. *Research Policy*, 45(5), 1061–1074. https://repository.tilburguniversity.edu/items/a89eccd5-aa2f-478a-bfba-b6680b73fd48
- Kok, H., Faems, D., & de Faria, P. (2019). Dusting off the knowledge shelves: Recombinant lag and the technological value of inventions. *Journal of Management*. https://www.hhs.se/news/hoi-news/2019/sse-researcher-holmer-kok-wins-prestigious-best-paper-award/
- Chan, J., Fu, K., Schunn, C., Cagan, J., Wood, K., & Kotovsky, K. (2011). On the benefits and pitfalls of analogies for innovative design: Ideation performance based on analogical distance, commonness, and modality of examples. *Journal of Mechanical Design*, 133(8). https://www.lrdc.pitt.edu/Schunn/papers/Chanetal2011.pdf
- Fu, K., Chan, J., Cagan, J., Kotovsky, K., Schunn, C., & Wood, K. (2013). The meaning of "near" and "far": The impact of structuring design databases and the effect of distance of analogy on design output. *Journal of Mechanical Design*, 135(2). https://www.lrdc.pitt.edu/Schunn/papers/fuchanetal-near-far-2013.pdf
- Chan, J., Dow, S. P., & Schunn, C. D. (2015). Do the best design ideas (really) come from conceptually distant sources of inspiration? *Design Studies*, 36, 31–58. https://www.lrdc.pitt.edu/Schunn/papers/Chan-Dow-Schun-desstudies-nearfar-inpress.pdf
- Vendetti, M. S., Wu, A., & Holyoak, K. J. (2014). Far-out thinking: Generating solutions to distant analogies promotes relational thinking. *Psychological Science*, 25(4), 928–933. https://journals.sagepub.com/doi/10.1177/0956797613518079
- Gentner, D. (2025). Analogy. *Open Encyclopedia of Cognitive Science*. https://groups.psych.northwestern.edu/gentner/papers/Gentner-Analogy-OECS2025.pdf
- Wang, X., Chen, Q., Zhuang, K., et al. (2024). Semantic associative abilities and executive control functions predict novelty and appropriateness of idea generation. *Communications Biology*, 7, 703. https://doi.org/10.1038/s42003-024-06405-0
- Ovando-Tellez, M., Kenett, Y. N., et al. (2022). Brain connectivity-based prediction of combining remote semantic associates for creative thinking. *Creativity Research Journal*. https://cris.iucc.ac.il/en/publications/brain-connectivity-based-prediction-of-combining-remote-semantic-/
- Beaty, R. E., et al. Diverse functional interaction driven by control-default network hubs supports creative thinking. https://par.nsf.gov/biblio/10468789
- Sio, U. N., & Ormerod, T. C. (2009). Does incubation enhance problem solving? A meta-analytic review. *Psychological Bulletin*, 135(1), 94–120. Summarized in: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3990058/
- Preregistered study on incubation and mind wandering in creative writing (2025). *Scientific Reports*. https://pmc.ncbi.nlm.nih.gov/articles/PMC12241419/
- Acar, O. A., Tarakci, M., & van Knippenberg, D. (2019). Creativity and innovation under constraints: A cross-disciplinary integrative review. *Journal of Management*, 45(1), 96–121. https://openaccess.city.ac.uk/id/eprint/20459/
- Andriani, P., Ali, A., & Mastrogiorgio, M. (2017). Measuring exaptation and its impact on innovation, search, and problem solving. *Organization Science*, 28(2), 320–338. https://ideas.repec.org/a/inm/ororsc/v28y2017i2p320-338.html
- Innovation beyond intention: Harnessing exaptation for technological breakthroughs (2024). arXiv:2412.19662. https://arxiv.org/pdf/2412.19662
- Park, M., Leahey, E., & Funk, R. J. (2023). Papers and patents are becoming less disruptive over time. *Nature*, 613, 138–144.
- Burt, R. S. (2004). Structural holes and good ideas. *American Journal of Sociology*, 110(2), 349–399. https://snap.stanford.edu/class/cs224w-readings/Burt04StructureHole.pdf
- Doshi, A. R., & Hauser, O. P. (2024). Generative AI enhances individual creativity but reduces the collective diversity of novel content. *Science Advances*, 10(28). https://doi.org/10.1126/sciadv.adn5290
- Sourati, Z., et al. (2023). ARN: Analogical reasoning on narratives. arXiv:2310.00996. https://arxiv.org/pdf/2310.00996
- Kittur, A., Yu, L., Hope, T., Chan, J., et al. (2019). Scaling up analogical innovation with crowds and AI. *PNAS*, 116(6), 1870–1877. https://www.cmu.edu/news/stories/archives/2019/february/scaling-analogies-search.html
- Hope, T., Chan, J., Kittur, A., & Shahaf, D. (2017). Accelerating innovation through analogy mining. *KDD*. https://sotaverified.org/papers/accelerating-innovation-through-analogy
- Yu, Y., & Romero, D. M. (2024). Does the use of unusual combinations of datasets contribute to greater scientific impact? arXiv:2402.05024. https://arxiv.org/html/2402.05024v4
- Olteteanu, A.-M. (2015). "Seeing as" and re-representation: Their relation to insight, creative problem-solving and types of creativity. https://media.suub.uni-bremen.de/handle/elib/3525
