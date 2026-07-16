# Chapter 3 cold-start audit: one-dimensional kinematics

Audit date: 2026-07-16

Scope: flashcards/03_kinematics_1d.md only. The scan treated scheduled cards in
Chapters 1–2 and the declared learner mathematics as the entire inbound
knowledge base. No later chapter supplied a prerequisite.

## Learner contract frozen for this scan

- Confirmed mathematics: algebra, signed arithmetic, ratios, equation
  rearrangement, square roots, function graphs, trigonometry, and introductory
  calculus awareness.
- Confirmed Chapter 1 physics: physical models and assumptions; predictions and
  evidence; quantity values; SI metre and second; units, dimensions, scientific
  notation, and elementary reporting.
- Confirmed Chapter 2 physics: scalar/vector distinction; coordinate axes and
  signed vector components; coordinate dependence; vector magnitude and
  direction. Dot and cross products are established but unused here.
- Unconfirmed physics: all motion vocabulary, graph meanings, kinematic models,
  free-fall language, and later mechanics concepts.

## Chapter-boundary dependency ledger

| Inbound dependency | Scheduled source | Chapter 3 use | Boundary result |
|---|---|---|---|
| Quantity values, metre, second, unit products and powers | Chapter 1 F04–F11 | Position, elapsed time, velocity, acceleration, and dimensional checks | ready |
| Signed arithmetic, algebra, functions, limits, derivatives, and definite-integral notation | Declared learner mathematics; physical meanings are still bridged on F13, F18, F23, and F26 | Rates, slopes, areas, and model derivations | ready |
| Physical model, assumption, prediction, and applicability range | Chapter 1 F01–F03 | Constant-velocity, constant-acceleration, and free-fall models | ready |
| Scalar/vector distinction and signed coordinate axis | Chapter 2 F01, F05–F07 | One-dimensional components and sign conventions | ready |
| Coordinate dependence under axis choice | Chapter 2 F12, narrowed and retrieved at Chapter 3 F01–F05 | Position/displacement signs and upward-positive free fall | ready |
| Later mechanics vocabulary | Not allowed inbound | Force, Newton's laws, energy, momentum, drag laws, projectile motion, and two-dimensional trajectories are not used | excluded |

## Front-only scan method

The chapter was read in scheduled order with only Q: and P: blocks exposed.
For each front, the required vocabulary, symbols, graph grammar, alt text, and
procedure were mapped below before its A: or S: block was inspected. Answers
were then scanned in a second pass for terms that later fronts rely on. Repairs
made during the scan:

- F01 now defines motion and distinguishes the spatial and time origins.
- F04 alt text no longer uses turning-point vocabulary before F16.
- F19 was narrowed to one independently graded derivative target.
- F29–F30 now establish concave-down and concave-up graph language before use.
- F31 supplies the constant-velocity equation as a bridge and retrieves only
  the graph signatures.
- F44 defines air effects before later free-fall problems use the term.
- Signed-area alt text was corrected to match the actual fill and line-style
  cues.
- The free-fall figure's initially curved guide was replaced with a strictly
  vertical one-dimensional motion line.

## Front-by-front dependency findings

| Front | Dependencies required to parse and attempt | Confirmed source or establishment | Result |
|---|---|---|---|
| F01 | Motion, straight line, spatial/time origins, signed position, x(t), metre; coordinate figure grammar | Motion and all new kinematic terms defined on the front; axes/signs from Chapter 2; metre from Chapter 1 | ready |
| F02 | Clock reading, initial/final events, Δt, positive elapsed time | Clock reading/time origin F01; subscripts and Δt defined on the front; algebra inbound | ready |
| F03 | Interval, displacement, Δx, endpoint subtraction | Elapsed interval F02; displacement and notation defined on the front | ready |
| F04 | Distance traveled, path length, initial/final positions; path figure | Displacement F03; distance and accumulation defined on the front; alt text uses only established position language | ready |
| F05 | Shifted origin versus reversed axis; position/displacement/distance | Coordinate choices F01 and the three quantities F01–F04 | ready |
| F06 | Average velocity, displacement per elapsed time, m/s | Δx F03, Δt F02, units Chapter 1; velocity defined on the front | ready |
| F07 | Average speed, magnitude, reversal | Distance F04, average velocity F06, vector magnitude Chapter 2; speed defined on the front | ready |
| F08 | Round-trip positions; choose displacement versus distance | F01–F07; all givens and total elapsed time stated | ready |
| F09 | Position–time axes, graph point, spatial-path discrimination | Position/time F01–F02; graph axes inbound mathematics; graph grammar defined on the front | ready |
| F10 | Secant slope Δx/Δt as average velocity; graph reading | Graph F09 and average velocity F06; secant meaning stated on the front | ready |
| F11 | Segment, increasing/constant/decreasing position, velocity sign | Graph F09–F10 and velocity F06 | ready |
| F12 | Endpoint displacement, accumulated distance, average velocity from graph | F03–F11; all axes, values, and interval bounds visible | ready |
| F13 | Shrinking interval, limit, derivative notation, tangent slope | Average velocity/secant F10; calculus syntax inbound; full physical limit/tangent meaning established on the front and figure | ready |
| F14 | Position function, derivative as instantaneous velocity, evaluation | F13 plus inbound polynomial differentiation; units stated | ready |
| F15 | Instantaneous speed as the magnitude of v and velocity sign | Instantaneous velocity F13; magnitude Chapter 2; speed defined on the front | ready |
| F16 | Turning point, differentiability, velocity sign change | Velocity F13 and direction F15; turning point and the necessary sign-change condition defined on the front | ready |
| F17 | Average acceleration, Δv/Δt, m/s² | Velocity F13, elapsed time F02, units Chapter 1; acceleration defined on the front | ready |
| F18 | Instantaneous acceleration, dv/dt, d²x/dt², velocity tangent | F13 derivative bridge and F17 average acceleration; all new physical meanings established on the front and figure | ready |
| F19 | Differentiate v(t) to find instantaneous acceleration | F18 plus inbound polynomial differentiation; one requested result | ready |
| F20 | Velocity/acceleration sign pairs and speed change | Velocity/speed F13–F15; acceleration F17–F18 | ready |
| F21 | v=0 versus acceleration; turning-point condition | Acceleration F17–F18, sign logic F20, turning point F16 | ready |
| F22 | Velocity–time vertical value versus tangent slope | Velocity F13, acceleration F18, graph axes F09; both operations stated on the front | ready |
| F23 | Thin rectangles, signed area, integral of v, negative region | Displacement F03, velocity F13, graph F22; the sum-to-integral bridge is on the front | ready |
| F24 | Add positive and negative v–t rectangle areas | Signed-area rule and figure grammar F23; all numerical values stated | ready |
| F25 | Distance as area under speed | Distance F04, speed F15, signed area F23–F24 | ready |
| F26 | Acceleration–time value, signed area, integral, velocity-change units | Acceleration F18 and velocity change F17; area bridge established on the front | ready |
| F27 | Add a–t areas and apply v_f=v_i+Δv | Velocity change and notation F17/F26; graph values and initial velocity stated | ready |
| F28 | Discriminate x-slope, v-slope, v-area, and a-area | Separately established at F10/F13, F18/F22, F23, and F26 | ready |
| F29 | Concave down; translate x(t) tangent slopes to candidate v(t) | Tangent/velocity F13 and graph discrimination F28; concave down defined on the front; candidate labels visible | ready |
| F30 | Linear v(t), constant slope, concave-up x(t), no position origin | Graph meanings F22/F28–F29; concave up defined on the front; numerical endpoints stated | ready |
| F31 | Constant-velocity model, x_f=x_i+vΔt, three graph signatures | Model Chapter 1; position/velocity/acceleration and graphs F01–F30; equation supplied on front before use | ready |
| F32 | Apply constant velocity with initial/final clock readings | Model/equation F31, elapsed time F02, position F01 | ready |
| F33 | Constant-acceleration model and x/v/a graph family | Acceleration/graphs F17–F30 and constant velocity F31; constant-a condition defined on the front | ready |
| F34 | Derive v_f=v_i+aΔt from average acceleration | Average acceleration F17, constant-a condition F33, algebra inbound | ready |
| F35 | Straight-line v(t), trapezoid area, arithmetic mean velocity | Velocity area F23, linear v graph F33–F34, geometry/algebra inbound | ready |
| F36 | Substitute the velocity relation into displacement relation | Established equations F34–F35 and algebra inbound | ready |
| F37 | Eliminate Δt to obtain the no-time relation | Established equations F34–F36 and algebra inbound | ready |
| F38 | Curved v(t), changing slope, average versus instantaneous acceleration, model validity | Graph slope F18/F22, average acceleration F17, constant-a condition F33 | ready |
| F39 | Select equation from knowns/unknowns after model check | Constant-a equations derived F34–F37; validity F38 | ready |
| F40 | Analyzed constant-a execution for v_f and Δx | Selection F39 and equations F34/F36; all givens stated | ready |
| F41 | Faded no-time selection and displacement calculation | No-time relation F37, selection F39, analyzed example F40 | ready |
| F42 | Independent elapsed-time calculation and positive-root choice | Position relation F36, elapsed time positivity F02, faded practice F41 | ready |
| F43 | Mixed constant-v versus nonzero constant-a model choice from equal-time increments | Graph/model signatures F31–F33 and worked constant-a sequence F40–F42 | ready |
| F44 | Near-Earth free fall, gravity, air effects, g, vertical y sign, approximation limits; setup figure | Constant-a model F33–F43; every free-fall term and air-effects gloss established on the front; figure uses only vertical geometry | ready |
| F45 | Dropped, thrown upward, top turning point, v and a signs | Dropped/thrown defined on front; turning point F16; upward sign and a=-g F44 | ready |
| F46 | Analyzed drop: rest, Δy, a=-g, position equation, positive elapsed time | Free-fall model/sign F44–F45, equation F36, elapsed time F02; all givens stated | ready |
| F47 | Faded upward throw: top means v_f=0; use velocity equation | F44–F46 plus turning point F16/F45 and equation F34 | ready |
| F48 | Independent drop: no-time relation, square-root magnitude, downward sign | F44–F47, no-time relation F37, vector magnitude/sign Chapter 2/F15 | ready |
| F49 | Mixed free-fall graph family, concave down, velocity zero, nonzero acceleration at top | Concavity F29–F30, graph models F33, turning-point misconception F21/F45, free fall F44–F48 | ready |

## Answer and later-dependency scan

The second pass found no answer-only term that a later front requires without an
earlier scheduled bridge. Answer-only refinements such as trapezoid area,
arithmetic-mean velocity under constant acceleration, variation of g, and
positive-root rejection are either inbound mathematics, immediately explained,
or not assumed later without the corresponding earlier card.

## Figure and representation check

All 11 chapter figures were compiled from repository-root-path TikZ sources to
same-named SVGs. Each SVG has a viewBox, title, and description. At 390 pixels
wide, all axis labels, line styles, points, and signs were legible. Blue/orange
distinctions are redundant with solid/dashed outlines, placement, labels, or
shape. Front figures contain setup information only. No figure imports a later
chapter representation, and the free-fall setup remains one-dimensional.

cold_start_status: pass
unresolved_dependencies: 0
