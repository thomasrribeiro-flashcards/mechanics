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

The deck assumes algebra and trigonometry. It assumes vectors only after
chapter 2 and introduces elementary calculus where its physical meaning first
matters. It does not assume physics vocabulary or later mechanics chapters as
prerequisites for earlier ones.

## Chapter 1 pilot gate

`01_foundations` is the novice-first pilot. Until a human approves its completed
cold-start audit, no later chapter may be authored or revised.

### Allowed inbound knowledge

| Inbound knowledge | Source of confirmation | Boundary |
|---|---|---|
| Arithmetic, fractions, ratios, powers, and algebraic rearrangement | Learner contract | No physics meaning may be attached without explanation |
| Scientific notation at the level of powers of ten | Learner contract's algebra prerequisite, refreshed on the first scheduled scientific-notation front | No order-of-magnitude convention is assumed |
| Plane geometry, including rectangle area | Learner contract's algebra and trigonometry prerequisites | No vector or coordinate convention is assumed |
| Reading ordinary tables and left-to-right process arrows | General literacy | Every technical axis, scale, and symbol is still introduced |

Everything else—including “model,” “quantity,” “measurement,” SI, unit
symbols, prefixes, dimensions, resolution, uncertainty, and significant
figures—is new.

### Concept-dependency ledger (planned before authoring, reconciled after scan)

| New dependency | First explanation or analyzed example | First supported retrieval | Later faded or independent use | Status |
|---|---|---|---|---|
| Physical model; prediction; observation; evidence | Teaching definition embedded in F01; F02 supplies the model–evidence loop | F01–F02 | F03 diagnoses overclaiming from agreement | resolved |
| Physical quantity; measurement; unit; numerical value; quantity value | Teaching definition and mechanics unit examples embedded in F04 | F04 | F05 translates the same length across units | resolved |
| SI mechanics unit symbols m, kg, s; derived area unit; symbol writing | F04 establishes the symbols; F09 and F10 include their needed bridges | F06–F10 | Later chapter use | resolved |
| Prefixes and conversion factors | Relations are explicit givens; teaching definition embedded in F11 | F11 | F12–F13 perform conversions | resolved |
| Dimension; L/T notation; dimensional consistency | Teaching definitions embedded in F14 and F15 | F14–F15 | F16–F18 and mixed F28 | resolved |
| Scientific notation and powers-of-ten scale | Teaching definition embedded in F19; algebra prerequisite refreshed through F20 | F19–F20 | F21 compares scales | resolved |
| Resolution | Teaching definition and figure grammar embedded in F22 | F22 | F24 contrasts resolution with uncertainty | resolved |
| Best estimate; uncertainty interval; `±` notation | Teaching definition and unlabeled interval embedded in F23 | F23 | F24 and F27 | resolved |
| Significant figures; leading/trailing zeros; exact conversions | Teaching distinction embedded in F25 | F25 | F26–F27 | resolved |

Rejected early examples: free fall, speed or velocity, force, energy, momentum,
vectors, graphs of motion, and physical constants. Each would borrow vocabulary
or representations from later chapters without adding value to the chapter 1
target.

### Chapter design ledger (planned before authoring)

| Retrieval family | Planned forms | Problem progression | Authentic representations |
|---|---|---|---|
| Models, predictions, and evidence | Bounded `Q:/A:` interpretation and diagnosis | No calculation; supported interpretation followed by misconception diagnosis | Cyclic process diagram and plain-language scenario |
| Quantity–number–unit grammar and SI | `Q:/A:` translation plus compact `C:` recall for m, kg, and s | Identification before use | Symbolic quantity value, unit table, same length in two units |
| Prefixes and conversions | `Q:/A:` method choice and `P:/S:` transfer | Analyzed example → completion choice → independent conversion | Powers-of-ten table, conversion-factor algebra |
| Dimensions | `Q:/A:` meaning/limit and `P:/S:` discrimination | Analyzed rectangle example → equation check → independent derived-unit construction | Symbolic equations and base-dimension notation |
| Scientific notation and scale | `Q:/A:` translation and short `P:/S:` comparison | Refresher → exponent-step inference → independent scale comparison | Power-of-ten scale |
| Resolution, uncertainty, and significant figures | `Q:/A:` interpretation/contrast and `P:/S:` reporting | Instrument reading → interval translation → independent reporting decision | Marked measuring scale, uncertainty number line, `±` notation |

Planned inventory: basic cards are the default for interpretation and
diagnosis; three clozes are justified for exact m/kg/s recall after explanation;
problems are reserved for conversion, dimensional, scale, and reporting
decisions. Exact counts will follow the smallest sufficient set and will be
reconciled after the cold-start scan.

### Figure-opportunity ledger (planned before authoring)

| Opportunity | Decision | Retrieval role or omission reason |
|---|---|---|
| Model → prediction → measurement → comparison loop | Include | Trace how evidence can retain or revise a model on F02 |
| Same physical length expressed in centimeters and meters | Include | Separate invariant quantity from unit-dependent numerical value |
| Complete seven-base-unit SI network | Omit | It adds five unused quantities and invites glossary memorization; chapter 1 retrieves only m, kg, and s |
| Prefix/power-of-ten ladder | Include | Count exponent steps and infer multiplicative scale without a later physics context |
| Conversion-factor cancellation | Omit | The authentic representation is the written algebra; a decorative arrow diagram adds no new decision |
| Dimensional-consistency balance | Omit | Symbolic equations are the authentic representation and are clearer at phone width |
| Marked measuring scale | Include | Read the smallest marked increment from an instrument-like display |
| Uncertainty interval on a number line | Include | Translate `estimate ± uncertainty` into endpoints; use the unlabeled retrieval asset on the scheduled front without leaking endpoints |
| Accuracy-versus-precision target plots | Omit | Accuracy, trueness, and repeatability are outside this pilot's minimum dependency path |

### Chapter 1 inventory reconciliation

| Inventory | Planned | Actual | Reconciliation |
|---|---|---:|---|
| Basic `Q:/A:` | Default for interpretation, discrimination, and diagnosis; no quota | 19 | Every basic card carries one bounded decision; no planned family is missing |
| Cloze `C:` | Exactly useful compact recall for meter, second, and kilogram after explanation | 3 | One cloze per mechanics base unit; no formula clozes added |
| Problem `P:/S:` | Conversion, dimensional, scale, and reporting transfer | 6 | Two conversion, two dimensional, one scale, and one reporting problem realize the plan |
| Problem progression | Supported → faded/independent where repetition pays | 6 scheduled problems | Explicit givens and earlier scheduled answers support conversion, dimensions, scale, and reporting without relying on unscheduled prose |
| Figure opportunities | Five included visual targets; four explicit omissions | 5 targets in 6 SVG assets | The uncertainty target needs a labeled teaching figure and an unlabeled retrieval front; no expected target is unexplained |

Chapter 1 therefore contains 28 cards: 19 basic, 3 cloze, and 6 problem
blocks. It references the five planned visual targets. The six original SVG
assets reflect one retrieval/reference pair for the uncertainty target, not an added
figure quota.

## Chapter 2 build ledger

`02_vectors` is a novice-first bridge from concrete geometric arrows to the
vector operations later mechanics chapters may use. It assumes only chapter
1's scheduled cards and the declared algebra and trigonometry prerequisites.
Later mechanics quantities are deliberately unavailable as examples.

### Allowed inbound knowledge at the chapter boundary

| Inbound knowledge | Source of confirmation | Boundary |
|---|---|---|
| Arithmetic, algebraic rearrangement, square roots, and signed numbers | Learner contract | No vector notation or component rule is assumed |
| Plane geometry, right triangles, the Pythagorean theorem, and sine/cosine/tangent | Learner contract's algebra and trigonometry prerequisites | No coordinate-axis, direction-angle, or quadrant convention is assumed |
| Physical quantity, numerical value, unit, SI writing, and dimension | Scheduled chapter 1 cards F04–F18 | No physical quantity is assumed to be scalar or vector until chapter 2 establishes the distinction |
| Powers of ten, measurement resolution, and uncertainty | Scheduled chapter 1 cards F19–F28 | Available for checks but not required by the core vector path |
| Reading ordinary arrows and tables | General literacy | Arrow tail/head grammar, vector equality, page-normal symbols, and every mathematical arrow convention are new |

Everything else is unseen. In particular, no later mechanics quantity, law,
graph, or diagram may support a chapter-2 front.

### Concept-dependency ledger (planned before authoring)

| New dependency | First explanation or analyzed example | First supported retrieval | Later faded or independent use | Status |
|---|---|---|---|---|
| Geometric arrow tail/head; magnitude and direction; vector equality | F01 scheduled front defines the arrow grammar | F01–F02 | F05–F06 and all later diagrams | resolved |
| Scalar versus vector; vector and magnitude notation; opposite vector | F03–F05 scheduled fronts supply concrete definitions before symbolic use | F03–F05 | F06 and later operation cards | resolved |
| Multiplication of a vector by a scalar | F06 states the magnitude and direction effects | F06 | Subtraction and later algebra | resolved |
| Cartesian origin and perpendicular x/y axes; signed scalar components; quadrants | F07 scheduled front defines axes, projections, and signs with a grid | F07–F08 | F09–F21 | resolved |
| Unit vectors \(\hat{\mathbf i}\), \(\hat{\mathbf j}\); component form | F09 defines unit vector and component notation | F09 | F10–F21 and vector products | resolved |
| Direction angle measured counterclockwise from +x; component trigonometry | F10 analyzed problem states the convention and method | F10 | F11–F13 | resolved |
| Magnitude and direction reconstructed from components; quadrant check | F12 gives the first full reconstruction with a genuine check | F12 | Later vector interpretation | resolved |
| Coordinate dependence of components versus invariance of the geometric vector | F13 supplies the rotated-axis contrast | F13 | Later coordinate choices | resolved |
| Component units and dimensions | F14 bridges chapter-1 unit/dimension knowledge | F14 | All numerical vector problems | resolved |
| Tail-to-head addition; resultant; componentwise addition | F15 front teaches the graphical construction; F16 states the analytical rule | F15–F16 | F17 and later vector sums | resolved |
| Vector subtraction as addition of the opposite | F18 defines the operation | F18 | F19 and later differences | resolved |
| Dot product, angle between tail-to-tail vectors, scalar output, projection, and commutativity | F21 front gives the definition; F22–F23 establish boundary and projection meaning | F21–F23 | F24–F26 | resolved |
| Three-dimensional z-axis; \(\hat{\mathbf k}\); out-of-page dot and into-page cross | F27 front defines the right-handed page convention; F27–F28 answers establish k and both page symbols | F27–F28 | F29–F33 | resolved |
| Cross product, perpendicular direction, right-hand rule, magnitude, order reversal, and parallelogram area | F27 defines direction and output; F28–F31 retrieve order and magnitude structure | F27–F31 | F32–F33 | resolved |
| Three-dimensional component form and cross-product component calculation | F33 supplies the formula as an execution scaffold | F33 | Later mechanics chapters | resolved |
| Dot-product versus cross-product discrimination | Dot product is established by F26 and cross product by F32; F34 asks for the decisive output/geometry distinction | F34 | Later model selection | resolved |

Rejected scaffolds include motion quantities, forces, work, torque, energy,
momentum, polar coordinates, and later-mechanics diagrams. Abstract directed
lengths and grid arrows test the same vector decisions without borrowing future
knowledge.

### Chapter design ledger (planned before authoring)

| Retrieval family | Planned forms | Problem progression | Authentic representations |
|---|---|---|---|
| Arrow grammar and scalar/vector distinction | Bounded `Q:/A:` interpretation and discrimination | Concrete equal-arrow comparison before notation | Geometric arrows, written quantity values, vector/magnitude notation |
| Components and coordinate conventions | `Q:/A:` diagram reading plus `P:/S:` execution | Supported grid reading → analyzed trigonometric decomposition → independent quadrant case → reconstruction | Cartesian grid, dashed projections, component pairs, unit-vector form, right triangles |
| Addition, subtraction, and scalar multiplication | `Q:/A:` construction/method cards and `P:/S:` component transfer | Visual construction → component rule → independent sum → independent difference | Tail-to-head diagram, component equations, translated arrows |
| Dot product | `Q:/A:` meaning, sign, projection, and order; `P:/S:` calculation | Definition-supported qualitative sign → projection interpretation → component calculation → angle recovery | Tail-to-tail angle, signed projection, component expression |
| Cross product | `Q:/A:` direction, order, limiting cases, area, and product discrimination; `P:/S:` magnitude and components | Right-hand direction → order reversal → geometric magnitude/area → numerical magnitude → scaffolded component execution | Page-normal symbols, right-handed axes, parallelogram area, three-component notation |

Planned inventory: 26 basic `Q:/A:` cards, zero clozes, and 8 `P:/S:` cards
(34 total). Basic cards carry the bounded geometric and representational
decisions; problems carry decomposition, reconstruction, addition/subtraction,
dot-product, and cross-product transfer. No compact target benefits from exact
cloze recall before its meaning is understood.

### Figure-opportunity ledger (planned before authoring)

| Opportunity | Decision | Retrieval role or omission reason |
|---|---|---|
| Equal arrows translated to different locations | Include | Decide equality from magnitude and direction rather than page position |
| Scalar/vector decorative comparison | Omit | The scheduled verbal contrast is clearer; a picture would not add a spatial decision |
| Cartesian components on a grid | Include | Translate one arrow into signed horizontal and vertical components |
| Quadrant sign pattern | Include | Infer component signs from arrow direction without formula substitution |
| Unit-circle or polar-coordinate diagram | Omit | Polar coordinates are outside the requested chapter boundary; the direction-angle convention needs only Cartesian axes and right-triangle trigonometry |
| Tail-to-head vector addition | Include as front/back pair | Construct the resultant without leaking it on the front, then compare with the completed construction |
| Parallelogram addition | Omit | Tail-to-head geometry and component addition already test the same sum; a second construction adds review cost without a new decision |
| Dot-product projection | Include | Connect the algebraic product to signed alignment along one vector |
| Cross-product page-normal direction | Include | Choose out of versus into the page from vector order using redundant dot/cross page symbols |
| Cross-product parallelogram area | Include | Translate \(AB\sin\phi\) into a geometric area rather than memorize an isolated formula |
| General perspective drawing of two arbitrary 3-D vectors | Omit | Perspective ambiguity is unnecessary; right-handed axes and page-normal cues establish the required direction convention more reliably at phone width |
| Determinant mnemonic | Omit | The explicit component formula is the authentic calculation scaffold and avoids turning determinant expansion into an unestablished prerequisite |

Planned figure inventory: seven distinct retrieval targets in eight original
SVG assets; vector addition uses separate setup and answer assets. This is a
role inventory, not a quota.

### Chapter 2 inventory reconciliation

| Inventory | Planned | Actual | Reconciliation |
|---|---|---:|---|
| Basic Q:/A: | 26 bounded interpretation, representation, and discrimination cards | 25 | The quadrant-II component target became an execution problem after cold-start review; no retrieval family was dropped |
| Cloze C: | 0 | 0 | Exact compact recall was not a separate durable target; symbols and formulas are retrieved through meaning and use |
| Problem P:/S: | 8 decomposition, reconstruction, operation, and product problems | 9 | Three component problems, two addition/subtraction problems, two dot-product problems, and two cross-product problems provide an analyzed-to-independent progression; the extra quadrant-II decomposition makes sign selection independently gradable |
| Problem progression | Supported decomposition → independent quadrant case/reconstruction; visual operation bridge → independent component operations; definition-supported products → numerical/component transfer | 9 scheduled problems | F10 is the analyzed decomposition; F11–F12 fade support; F17/F19 execute sum/difference; F24–F25 and F32–F33 move from supplied formulas to transfer and checks |
| Figure opportunities | 7 retrieval targets in 8 SVG assets | 7 targets in 8 original SVGs | Every included opportunity was realized; addition alone needs a setup/answer pair, and all planned omissions remain justified |

Chapter 2 therefore contains 34 cards: 25 basic, zero cloze, and 9 problem
blocks. It uses seven visual retrieval targets: vector equality, component
reading, quadrant signs, tail-to-head addition, dot projection, cross direction,
and cross area. The source register, design ledger, and cold-start audit account
for every actual and intentionally omitted representation.

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
