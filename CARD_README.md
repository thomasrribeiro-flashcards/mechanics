# Mechanics SRS card blueprint

This document is the source of truth for creating and auditing cards in this repository. Its goal is not to maximize card count. Its goal is to produce a compact set of retrieval prompts that builds durable, transferable mechanics knowledge and problem-solving skill.

The deck targets introductory, calculus-aware classical mechanics. It should help the learner:

1. identify the physical system and choose an appropriate model;
2. translate among words, diagrams, graphs, vectors, and equations;
3. retrieve core principles and their conditions of validity;
4. solve representative problems without copying a memorized surface pattern;
5. detect impossible results, sign errors, hidden assumptions, and common misconceptions.

## 1. Evidence behind the design

### 1.1 Retrieval, not exposure, drives durable learning

Attempting to retrieve an answer produces better delayed retention than repeatedly reading it. Retrieval practice can also improve inference and transfer, not merely memory for the exact wording tested. Therefore every card must require the learner to generate, select, explain, predict, derive, or evaluate something before seeing the back.

Implications:

- Do not create cards whose answer is visible in the prompt.
- Prefer cued recall over yes/no recognition.
- Do not use a cloze when the visible sentence makes the deletion nearly automatic.
- Make the back corrective and explanatory enough to repair an error, but not so long that several independent judgments are graded together.

### 1.2 Spacing and successive relearning stabilize retrieval

Spacing reviews over time improves retention, and the most effective spacing depends on how long the knowledge must be retained. Repeated successful retrieval across separated sessions—successive relearning—is more useful than massing repetitions in one sitting.

Implications:

- Let FSRS schedule reviews; do not duplicate a card merely to make it appear more often.
- A failed card should receive feedback and return sooner, not be reread several times immediately.
- A card should remain stable enough for its review history to accumulate. Edit learned cards only to fix a real defect.
- Sleep supports consolidation, but it does not rescue weak encoding or replace retrieval practice. Avoid neuroscience-themed claims that do not change an authoring decision.

### 1.3 Feedback must resolve the attempted question

Retrieval is most useful when the learner receives the correct answer after an attempt. Feedback is especially important for low-confidence correct responses, misconceptions, and confidently held errors.

Implications:

- The back must directly answer the front before adding explanation.
- Show the decisive reasoning step, not only the final formula or number.
- For common misconceptions, state why the tempting alternative fails.
- Never make an incorrect statement memorable merely to negate it later. Phrase misconception cards as a concrete diagnosis or comparison.

### 1.4 Interleaving trains model selection

Blocked practice helps a novice acquire a new procedure, but interleaving related problem types later forces the learner to decide which strategy applies. This discrimination is central to mechanics, where the difficult step is often choosing between kinematics, Newton's laws, energy, momentum, and angular momentum.

Implications:

- Introduce a model with a short blocked progression: concept → worked example → completion/problem.
- Then include mixed “What model and why?” prompts whose surface features do not name the method.
- Contrast easily confused conditions: static versus kinetic friction, equilibrium versus constant speed, centripetal acceleration versus tangential acceleration, momentum conservation versus kinetic-energy conservation.
- Do not label every problem with its chapter method on the front; that removes the choice the learner must practice.

### 1.5 Worked examples should fade into independent retrieval

Worked examples reduce unnecessary search for novices, especially when many interacting steps are new. As knowledge grows, excessive scaffolding becomes redundant. Use an example-to-problem progression rather than either pure exposition or unguided problem solving.

Recommended progression for each major problem family:

1. **Model card:** identify the system, assumptions, and governing principle.
2. **Worked example:** full IPEE reasoning.
3. **Completion card:** omit a key setup or intermediate step for the learner to supply.
4. **Independent problem:** give only the physical situation and requested quantity.
5. **Discrimination card:** mix it with nearby methods and ask which applies.

### 1.6 Atomicity is a scheduling property, not context removal

One card should produce one meaningful grading decision. If one half of an answer can be correct while another half is wrong, the card is probably not atomic. However, a mechanics prompt needs enough physical context to determine the model; stripping that context can turn understanding into symbol recognition.

Use these tests:

- Can the response be judged correct or incorrect as a whole?
- Would forgetting one clause require a different review interval from the rest?
- Does the prompt uniquely specify the desired fact or reasoning step?
- Is every detail on the front needed to choose or execute the method?
- Could the card be answered from wording cues without understanding the physics?

Split independent facts. Keep tightly coupled reasoning together when the relationship itself is the learning target.

## 2. The mechanics card portfolio

A good chapter uses several retrieval modes. It does not need an arbitrary quota of each type.

### 2.1 Concept and causal-explanation cards (`Q:/A:`)

Use for “what,” “why,” and “under what conditions” questions.

```markdown
Q: Why can an object have acceleration while its speed stays constant?
A: Acceleration measures change in the velocity vector. In uniform circular motion the direction changes continuously even though the speed does not.
```

Standards:

- Ask one explicit question.
- Put the direct answer in the first sentence.
- Prefer one sentence; use at most three concise sentences.
- Include the condition of validity when it determines whether the statement is true.

### 2.2 Model-selection and discrimination cards (`Q:/A:`)

Use to train the highest-value step: deciding what principle applies.

```markdown
Q: A block slides down a rough track and the question asks only for its speed after a known vertical drop. Which framework is shortest, and what term accounts for roughness?
A: Use work–energy: $\Delta K + \Delta U = W_{nc}$, with friction included as negative non-conservative work.
```

The prompt should contain diagnostic physical information without naming the method. The back names the method and the decisive cue.

### 2.3 Qualitative prediction cards (`Q:/A:`)

Use before formulas or calculations to build a physical model.

```markdown
Q: A satellite is moved to a larger circular orbit. Before calculating, how should its orbital speed and total energy change?
A: Its speed decreases, while its total energy increases toward zero (becomes less negative).
```

Predictions should test direction, scaling, limiting behavior, or a comparison. They are not invitations to guess trivia.

### 2.4 Formula and relationship cards (`C:` or `Q:/A:`)

Formula recall is useful only when tied to meaning and conditions.

Every formula card must provide:

- a descriptive cue;
- all variable meanings not already obvious from the same sentence;
- the model assumptions or validity condition;
- unambiguous vector/scalar notation;
- no more than one independent deletion, except for one tightly coupled pair.

```markdown
C: For constant acceleration, the time-independent kinematic relation is $v^2 = [v_0^2 + 2a\Delta x]$, where $\Delta x$ is displacement.
```

Avoid “naked equation” cards such as “Newton's second law is [$F=ma$].” First establish what net force means and when constant mass is assumed.

### 2.5 Representation-translation cards (`Q:/A:`)

Mechanics fluency requires moving between representations.

Useful directions include:

- verbal situation → free-body diagram;
- graph slope/area → physical quantity;
- equation → graph shape or limiting behavior;
- vector diagram → components and signs;
- force diagram → governing component equations;
- motion description → energy or momentum bar chart.

When no figure asset exists, describe a small, precise graph or diagram in words. Add a real diagram only when it is required to answer the question; decorative images add no retrieval value.

Prefer visual retrieval over passive illustration:

- ask the learner to predict, sketch, label, identify, compare, or translate the figure before reveal;
- place an unlabeled/setup figure on the front only when it does not disclose the answer;
- place labeled diagrams, completed constructions, and worked-example figures on the back;
- use progressive or separate cards when one completed figure would reveal several independent answers;
- create a new card identity for a new visual retrieval task instead of attaching its progress to a previously mastered textual task.

### 2.6 Misconception and error-diagnosis cards (`Q:/A:`)

Use for errors that are common, consequential, and plausible.

```markdown
Q: A student sets static friction equal to $\mu_sN$ for a block that remains at rest. What is the error?
A: $\mu_sN$ is only the maximum. Actual static friction takes the value required for equilibrium, up to that limit.
```

Prefer diagnosis over a bare true/false prompt. Explain the boundary between the correct and incorrect model.

### 2.7 Procedural and worked-problem cards (`P:/S:`)

Use IPEE when the learning target is a multi-step method.

- **IDENTIFY:** define the system, model, and applicable assumptions.
- **PLAN:** choose axes/representations and governing principles before inserting numbers.
- **EXECUTE:** solve symbolically as far as practical, then evaluate any supplied values.
- **EVALUATE:** check dimensions, sign/direction, limiting cases, conservation, and scale.

Variables and numbers serve different purposes:

- Use **variables** to teach a reusable derivation or schema.
- Use **numbers** sparingly to test unit handling, sign conventions, scale, and computational execution.
- Prefer a symbolic setup before numerical substitution.
- Do not create many cards that differ only in numbers; that is worksheet practice, not an efficient SRS deck.

Full IPEE belongs on the first representative problem in a family. Later problems should fade scaffolding so the learner retrieves the setup independently.

## 3. Mechanics-specific reasoning standard

For any nontrivial problem, the solution should make the following chain visible:

1. **System:** What object(s) are inside the system boundary?
2. **Frame:** What reference frame and coordinate signs are used?
3. **Model:** Particle, rigid body, projectile without drag, ideal string/pulley, small-angle oscillator, circular orbit, etc.
4. **Interactions:** What external forces or energy/momentum transfers matter?
5. **Representation:** FBD, motion graph, vector components, energy accounting, collision diagram, or rotation axis.
6. **Principle:** Kinematics, $\sum\vec F=m\vec a$, work–energy, momentum/impulse, $\sum\tau=I\alpha$, angular momentum, or oscillator equation.
7. **Execution:** Algebra first; numbers and units second.
8. **Evaluation:** Dimensions, signs, bounds, special cases, and an independent check when feasible.

Never award a correct numerical answer produced from a physically wrong setup. The setup is the primary retrieval target.

## 4. Ordering and prerequisite rules

Within each chapter, use this order where applicable:

1. motivation or qualitative “why”;
2. definition/model and validity conditions;
3. core relationships/formulas;
4. representation translations;
5. common contrasts and misconceptions;
6. model-selection cues;
7. worked example;
8. faded or independent application;
9. cross-topic integration using earlier chapters.

Do not rely on concepts introduced only in later chapters. Earlier chapters may use prerequisite mathematics, but kinematics should not require energy, and forces should precede energy and momentum arguments. Later chapters should build on earlier concepts instead of redefining them.

## 5. Wording and interference rules

- Use stable, natural wording. Do not add ornamental prose.
- Avoid prompts like “What is everything you know about X?”
- Avoid unordered lists. Split them or ask for a meaningful structure/comparison.
- Do not encode both directions of a relationship automatically. Add a reverse card only when the reverse retrieval is useful in real problem solving.
- Give similar concepts contrasting cues. A pair of near-identical definitions invites interference.
- Use consistent notation: arrows for vectors, plain symbols for magnitudes, hats for unit vectors.
- State the object on which a force acts. Third-law pairs must name both objects.
- Say “net external impulse is negligible” for collision momentum conservation when that is the actual approximation.
- Treat empirical models as approximations: simple dry friction, ideal strings/pulleys, linear springs, drag laws, point masses, rigid bodies, and small-angle pendulums all have limits.
- Avoid historical anecdotes unless they teach physics accurately. In particular, do not present the Tacoma Narrows collapse as elementary resonance; its destructive torsional motion was aeroelastic flutter.

## 6. Parser and repository format

Each file begins with TOML metadata and then a single chapter heading.

```toml
+++
order = 1
subject = "physics"
tags = ["mechanics", "physics", "topic"]
+++
```

Supported cards:

```markdown
Q: Specific question?
A: Concise answer.

C: Context with [one retrievable deletion].

P: Problem statement.

S:
**IDENTIFY**: ...
**PLAN**: ...
**EXECUTE**: ...
**EVALUATE**: ...
```

Rules:

- Separate cards with a blank line; do not use `---` separators.
- Every `Q:` must have an `A:` and every `P:` must have an `S:`.
- Every `C:` must contain at least one valid deletion.
- Use `$...$` for inline math and `$$...$$` for display math.
- Literal square brackets inside cloze math must be escaped as `\lbrack` and `\rbrack` so they are not parsed as deletions.
- Image Markdown is not a deletion. Place setup-only figures after the question; place figures containing a solution after the answer.
- Preserve frontmatter order and lowercase subject metadata.

Every card block in this deck has a stable `card-id`. The accompanying `card-alias` records its original content hash so existing FSRS state can migrate without being reset. During an audit:

- preserve the existing `card-id` for figures, formatting, clearer feedback, and corrections that test the same underlying retrieval;
- assign a new `card-id` when the front now asks for materially different knowledge or a new visual retrieval task;
- never remove generated `card-alias` lines merely for tidiness, because a device may still need them for migration;
- fix incorrect, ambiguous, or harmful cards even when the change is substantive;
- do not rewrite a correct card merely for stylistic preference;
- record substantive edits in the commit message;
- run the parser/validation checks before committing.

## 7. FSRS review behavior

Grade the retrieval attempt, not how familiar the answer feels after reveal:

- **Again:** no answer, materially wrong model, wrong direction/sign that changes the physics, or answer obtained only after reveal.
- **Hard:** essentially correct but effortful, incomplete in a noncritical detail, or corrected before reveal after substantial hesitation.
- **Good:** correct core answer and reasoning with ordinary effort.
- **Easy:** immediate, confident, complete retrieval with no meaningful reconstruction cost.

Additional rules:

- Say the answer before revealing it; silent familiarity is not retrieval.
- For a problem card, write or mentally commit to the governing setup before reveal.
- Do not press Easy merely because the back looks obvious.
- If a card repeatedly fails, diagnose the card before blaming memory: ambiguity, excessive scope, missing prerequisite, interference, or a false premise may make it a leech.
- SRS maintains component skills; it does not replace solving novel mixed problems on paper.

## 8. Audit rubric

Audit every card in this order.

### Gate A — correctness

- Is every statement technically correct?
- Are idealizations and validity conditions explicit?
- Are vector directions, signs, axes, and reference levels unambiguous?
- Are empirical rules described as models rather than universal laws?
- Does the answer avoid common textbook myths?

Any failure here requires revision or deletion.

### Gate B — retrieval quality

- Does the front require generation rather than recognition?
- Is there one schedulable judgment?
- Is the cue specific without leaking the answer?
- Does the back begin with the direct answer?
- Could a learner answer correctly for the wrong reason?

### Gate C — learning value

- Is this knowledge used to explain, predict, choose, calculate, or check mechanics?
- Is it foundational enough to merit long-term maintenance?
- Is it already tested adequately by another card?
- Would a contrast, graph translation, or model-selection prompt transfer better than another definition?

Delete low-value trivia and redundant prompts.

### Gate D — integration

- Are prerequisites earlier in the deck?
- Does the card distinguish neighboring concepts?
- Does the chapter contain qualitative, quantitative, representational, and diagnostic retrieval where appropriate?
- Is there at least one path from core principles to an applied problem family?

### Gate E — operational validation

- Does the Markdown parse into the intended number and type of cards?
- Are cloze brackets and LaTeX valid?
- Are variables defined?
- Are metadata, headings, and filenames consistent?
- Does `git diff --check` pass?

## 9. Evidence base and scope of claims

The rules above are applications of learning research, not claims that one card template has been uniquely proven optimal. Laboratory results do not specify an exact universal word count, cloze quota, or number of cards per chapter. Those are engineering judgments guided by the mechanisms below.

Core sources:

- Roediger & Karpicke (2006), retrieval practice versus restudy, *Psychological Science*. https://doi.org/10.1111/j.1467-9280.2006.01693.x
- Karpicke & Blunt (2011), retrieval practice and conceptual science learning, *Science*. https://doi.org/10.1126/science.1199327
- Butler (2010), retrieval practice and transfer, *Journal of Experimental Psychology: Learning, Memory, and Cognition*. https://doi.org/10.1037/a0019902
- Butler, Karpicke, & Roediger (2008), corrective feedback and confidence, *Journal of Experimental Psychology: Learning, Memory, and Cognition*. https://doi.org/10.1037/0278-7393.34.4.918
- Cepeda et al. (2006), distributed-practice meta-analysis, *Psychological Bulletin*. https://doi.org/10.1037/0033-2909.132.3.354
- Rohrer, Dedrick, & Burgess (2014), interleaved mathematics practice and strategy selection, *Psychonomic Bulletin & Review*. https://doi.org/10.3758/s13423-014-0588-3
- Richland, Kornell, & Kao (2009), pretesting and subsequent learning, *Journal of Experimental Psychology: Applied*. https://doi.org/10.1037/a0016496
- Chen, Retnowati, & Kalyuga (2020), worked-example sequencing, element interactivity, and prior knowledge, *British Journal of Educational Psychology*. https://doi.org/10.1111/bjep.12317
- Watkins & Watkins (1975), cue overload and retrieval interference, *Journal of Experimental Psychology: Human Learning and Memory*. https://doi.org/10.1037/0278-7393.1.4.442
- Hu et al. (2020), sleep and targeted memory reactivation meta-analysis, *Psychological Bulletin*. https://doi.org/10.1037/bul0000223

Technical reference for this deck:

- OpenStax, *University Physics Volume 1*. https://openstax.org/details/books/university-physics-volume-1

The evidence supports retrieval, feedback, spacing, appropriate interleaving, and scaffold fading. It does **not** support padding the deck, turning every sentence into a cloze, or substituting flashcard review for authentic problem solving.
