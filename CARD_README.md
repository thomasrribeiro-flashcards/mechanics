# Mechanics card blueprint

This file contains only mechanics-specific retrieval decisions. Universal rules
live in the flashcards repository's `CARD_STANDARD.md` and
`AUTHORING_PLAYBOOK.md`; reusable physics guidance lives in `physics.md`.

## Learner and outcome

The deck targets introductory, calculus-aware classical mechanics. The learner
should be able to:

1. choose a system, frame, model, and governing principle;
2. translate among situations, diagrams, graphs, vectors, and equations;
3. predict signs, directions, scaling, and limiting behavior;
4. solve representative problems without copying surface patterns;
5. detect impossible results, hidden assumptions, and common misconceptions.

The deck assumes algebra, trigonometry, vectors after chapter 2, and elementary
calculus where the chapter introduces its physical meaning. It does not assume
later mechanics chapters as prerequisites for earlier ones.

## Chapter progression

Within a new problem family, use this progression when it adds value:

1. establish the phenomenon, system, representation, and validity conditions;
2. ask for a qualitative prediction;
3. analyze one worked example with the model choice made explicit;
4. fade setup support in a completion problem;
5. require independent setup;
6. mix the problem with neighboring models and ask which applies.

Early cards must teach the representation or idea before later cards test its
application. A first encounter may orient and explain; it must not rely on an
`Again` rating as the only instruction.

## Mechanics retrieval portfolio

For each chapter, select the smallest useful set across:

- model and validity-condition recall;
- qualitative prediction and scaling;
- graph/diagram/equation translation;
- system, frame, axis, and sign selection;
- method selection from physical cues;
- misconception or error diagnosis;
- one analyzed example followed by faded application where appropriate;
- a real evaluation check: dimensions, direction, limit, conservation, or
  order of magnitude.

Do not convert every source exercise, vary only numbers, or add a formula card
without testing when the formula applies. Long mixed problems remain external
paper practice; cards maintain their model triggers and fragile subskills.

## Solution contract

For nontrivial `P:/S:` cards, IPEE should expose the physical chain:

- **IDENTIFY:** system boundary, frame, model, knowns, and regime;
- **PLAN:** axes or representation and governing principle before algebra;
- **EXECUTE:** symbolic structure first when useful, then values and units;
- **EVALUATE:** a physically independent check.

Full IPEE belongs on the first representative example. Fade sections once the
learner can retrieve them. A correct number from a physically wrong setup is a
failed target.

## Interference map

Prioritize contextual contrasts for:

- position, displacement, and distance;
- speed, velocity, and acceleration;
- mass and weight;
- equilibrium and constant velocity;
- static friction and its maximum value;
- interaction pairs and two forces on one object;
- centripetal and tangential acceleration;
- force, work, energy, power, impulse, and momentum;
- momentum conservation and kinetic-energy conservation;
- torque, angular momentum, and rotational energy;
- resonance and aeroelastic instability.

Ask for the decisive system, direction, unit, dependency, or validity condition.
Do not repeat the Tacoma Narrows myth as elementary resonance; its destructive
torsional motion involved aeroelastic flutter.

## Figures

Use original SVGs for free-body diagrams, motion graphs, vector geometry,
before/after states, energy accounting, orbits, oscillations, and model-choice
comparisons. Use the deck's black, white, gray, and gold palette, with a
non-color cue for every distinction.

Put setup geometry and givens on the front. Put the requested force, path,
component, label, or construction on the back. Preserve a card ID when a figure
clarifies the same target; create a new ID when the learner must now retrieve
new visual information.

## Accuracy boundaries

- State frames, axes, vector directions, and reference levels.
- Treat point masses, rigid bodies, ideal strings/pulleys, dry friction, linear
  springs, drag laws, and small-angle motion as models with limits.
- Use “net external impulse is negligible” when that is the collision
  approximation.
- Verify dimensions, signs, limits, and order of magnitude.
- Prefer correction over preserving a learned but false card; make the stable-ID
  decision explicit.

## Audit feedback

Use repeated `Again` ratings, slow responses, and leech behavior to locate cards
that may have ambiguous cues, excessive scope, interference, or missing
prerequisites. Telemetry is a diagnostic signal, not proof that the learner or
card is at fault. Record deck-wide evidence and identity decisions in the audit
record rather than expanding this blueprint.

## Practice outside SRS

Regularly solve unfamiliar mixed problems on paper without chapter labels.
Include estimation, derivation, diagram construction, experimental reasoning,
and explanation of model breakdown. Flashcards maintain the components; they do
not constitute full mechanics practice.
