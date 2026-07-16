# Chapter 1 pilot cold-start audit

cold_start_status: pass
unresolved_dependencies: 0

## Audit boundary and learner contract

- Deck: `physics/mechanics`
- Chapter: `flashcards/01_foundations.md` only
- Audit date: 2026-07-15
- Learner: independent adult with algebra and trigonometry and no assumed physics vocabulary
- Allowed inbound mathematics: arithmetic, fractions, ratios, powers, algebraic rearrangement, scientific notation at an algebra-prerequisite level, and rectangle geometry
- Allowed inbound general literacy: ordinary tables and left-to-right arrows
- Not allowed inbound: any physics term, symbol, unit convention, diagram grammar, model, measurement procedure, vector, calculus concept, or later-chapter example

The scan followed scheduled card order, not Markdown reading order. The
application parser ignores headings, lesson prose, tables, equations, and
figures outside `Q:/A:`, `C:`, and `P:/S:` blocks, so none of that material was
credited as prior instruction. For each card, the scheduled front—including
alt text, symbols, givens, and figure labels—was read and its dependencies
recorded before the answer was consulted. Answers were then checked only for
terms that a later front might assume.

## Completed dependency ledger

| Dependency | Required fronts | Inbound source or earlier establishment | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| Model, prediction, observation, evidence, tested conditions | F01–F03 | Teaching definitions embedded in F01; F02 supplies the labeled loop | F01–F02 | F03 | resolved |
| Quantity value, numerical value, unit, meter, second, kilogram | F04–F08 | Teaching definition and mechanics unit examples embedded in F04 | F04 | F05–F08 | resolved |
| Derived area unit and SI symbol writing | F09–F10 | Plane geometry is inbound; each scheduled front supplies its needed convention | F09–F10 | Later chapter use | resolved |
| Prefix relations, conversion factor, unit cancellation | F11–F13, F26 | Relations are explicit givens; teaching definition embedded in F11 | F11 | F12–F13, F26 | resolved |
| Dimension, L/T notation, dimensional consistency, necessary-not-sufficient check | F14–F18, F28 | Teaching definitions embedded in F14 and F15; later answers extend them | F14–F15 | F16–F18, F28 | resolved |
| Scientific notation, normalized coefficient, exponent, power-of-ten scale | F19–F21 | Scientific notation is declared inbound and explicitly refreshed on F19–F20 | F19–F20 | F21 | resolved |
| Instrument, marked scale, resolution | F22, F24 | Teaching definition and figure grammar embedded in F22 | F22 | F24 | resolved |
| Best estimate, uncertainty, symmetric interval, `±` notation | F23–F24, F27 | Teaching definition and unlabeled interval embedded in F23 | F23 | F24, F27 | resolved |
| Significant figures, leading/trailing zeros, exact conversion, matching decimal places | F25–F27 | Teaching distinction embedded in F25; later answers extend it | F25 | F26–F27 | resolved |

No front depends on force, motion terminology, vectors, energy, momentum,
calculus, or any representation introduced in chapters 2–12.

## Front-by-front scan

Front labels follow file order and map to stable IDs.

| Front | Stable card ID | Dependencies needed before answer | Establishment available before front | Finding |
|---:|---|---|---|---|
| F01 | `a690d74f-c012-4c62-ae07-aa3f84877e0a` | simplified description, physical model, prediction, observation | Definitions embedded on the scheduled front | pass |
| F02 | `2c130f1c-7de5-4d91-bbdc-b77a83ee237a` | loop arrows, model, compare, measurement, disagreement | F01 plus the labeled figure on F02 | pass |
| F03 | `06358250-f5d7-45d5-9176-f66e451b7e6a` | model, prediction, agreement, tested condition | F01–F02 answers establish iterative testing and bounded use | pass |
| F04 | `04c3b227-e83a-49bf-9f3d-d3a24fd84efb` | unit, quantity value, numerical value, mechanics unit symbols | Definitions and examples embedded on the scheduled front | pass |
| F05 | `b1ad52fa-a210-4322-b926-8656cc4d6cd7` | bar/scale grammar, cm, m, invariant quantity | F04 plus explicit values and figure on F05 | pass |
| F06 | `59a25f74-cc2c-4268-bf56-02749c208eb0` | SI, base unit, length | F04 explicitly gives meter (m) for SI length | pass |
| F07 | `062d9073-888b-458e-b20e-fa5d7a054dfc` | SI, base unit, time | F04 explicitly gives second (s) for SI time | pass |
| F08 | `e2f0c0c2-4428-489a-9fb2-120c855a0542` | SI, base unit, mass | F04 explicitly gives kilogram (kg) for SI mass | pass |
| F09 | `f7634bc0-25ae-4d28-a771-bdd7e984e2c4` | rectangle geometry, area, product, m² | Geometry is inbound; the front supplies both side units | pass |
| F10 | `a351bf58-a90e-48b4-b2c4-3ebf500749f0` | SI symbol, centimeter, number–unit spacing | Writing conventions embedded on the scheduled front | pass |
| F11 | `f09a9c12-c887-44b2-b533-40898de14e05` | conversion factor, old/new unit, cancellation | Definition and equality embedded on the scheduled front | pass |
| F12 | `0157c655-706a-4c70-9a2b-2dc2df8989f6` | km/m relation, conversion factor, check | Relation is an explicit given; F11 establishes factor orientation | pass |
| F13 | `38c77cf8-229d-4cf9-bfc1-784777cdacc3` | mm/m relation, cancellation, numerical increase/decrease | Relation is an explicit given; F11–F12 establish the method | pass |
| F14 | `63f24a70-ba97-49d8-ab82-eb3169908b13` | dimension, unit, physical quantity | Definitions embedded on the scheduled front; F04 establishes units | pass |
| F15 | `9b2cdf42-7277-4922-9fa3-cf0f2a7d900c` | dimensions, addition, equation | Consistency rule embedded on the scheduled front | pass |
| F16 | `af2d3be5-415a-48f4-85bf-72be6ea02924` | rectangle/area, declared symbols, dimensional method | Geometry inbound; F14–F15 establish the physics meanings | pass |
| F17 | `f62bbcda-a10c-4591-9f99-aa0076027970` | declared symbols, division, SI unit, L/T notation | Algebra inbound; F04 and F14 establish units and dimensions | pass |
| F18 | `f64f6c7a-0910-43c7-8793-061afc15c311` | consistency and proof/limit distinction | F15–F17 establish what the check can reject | pass |
| F19 | `592595ee-f3af-4f38-9b11-f8e0d335ae24` | coefficient, integer exponent, normalized notation | Scientific notation is inbound; definition refreshed on the front | pass |
| F20 | `0d9f2d8d-203a-4d7d-b8c0-829d6f928258` | decimal movement and signed power of ten | Declared inbound plus F19 | pass |
| F21 | `2fdc606b-5cf5-4d52-9263-7221c63885b7` | exponent-step scale, P/Q markers, multiplicative comparison | F19–F20 plus explicit instruction and figure on F21 | pass |
| F22 | `82278597-b23a-41f8-ab7a-2425a034feb7` | marked-scale grammar, resolution, centimeters | Definition and inspection method embedded on the front | pass |
| F23 | `ccade793-ab41-48ad-ac3a-8cba6c05af87` | best estimate, uncertainty, `±`, interval endpoints | Definition embedded on the front; retrieval figure omits endpoint values | pass |
| F24 | `3fe0f766-a70f-48ef-8c9f-1b601d0170d0` | instrument, resolution, total uncertainty | F22–F23 establish the two neighboring ideas | pass |
| F25 | `e4701dd9-9cc3-485d-9a10-0889b83be19f` | precision, significant figures, leading/trailing zeros | Distinction embedded on the scheduled front | pass |
| F26 | `b7797989-5c1e-4783-9e34-ce79bcd53bce` | exact definition, conversion, significant figures | F11–F13 and F25 | pass |
| F27 | `6eb791ac-a16b-4ff2-b628-6c4aa81d6b21` | best estimate, rounded uncertainty, decimal place | F23 and F25–F26 | pass |
| F28 | `3caad80e-66f7-43ff-8eea-8c172a6f4974` | equation, unlike units/dimensions, conversion versus dimensional analysis | F11–F18 establish both tools | pass |

## Repairs made during the scan

1. F13 originally requested a “magnitude check” without establishing that
   phrase. The front now asks explicitly whether the numerical value should
   increase or decrease.
2. F22's alt text originally stated the number of minor intervals and weakened
   the visual retrieval. It now describes unlabeled minor marks without giving
   the count.
3. F23 originally reused the labeled teaching figure and exposed the requested
   endpoints. The scheduled card now uses `uncertainty_interval_front.svg`,
   which shows only the center/endpoint structure.
4. The initial audit incorrectly credited prose outside parser-recognized card
   blocks as teaching. Every learning sequence now begins with a scheduled
   front that embeds its minimum teaching bridge; F10 and F15 were also repaired
   to carry the convention each asks the learner to apply.

After dependencies were recorded, answers were checked for downstream terms.
No answer introduces an unexplained term later assumed by a front.

## Figure audit

All assets are original SVGs with a `viewBox`, meaningful `<title>` and
`<desc>`, high contrast, and a shape, dash, label, or pattern cue beyond color.
Each was rasterized and visually inspected at 720 × 360.

| Asset | Learning/retrieval role | Front/back discipline | Result |
|---|---|---|---|
| `model_evidence_loop.svg` | Trace the iterative model–prediction–measurement–comparison relationship | Labels provide setup; explicit arrowheads show direction without stating the repair decision | pass |
| `same_length_two_units.svg` | Translate one physical length across two unit scales | Values are givens; the invariant-quantity explanation remains the target | pass |
| `power_of_ten_scale.svg` | Infer a multiplicative factor from exponent distance | Exponents and P/Q are givens; factor is not labeled | pass |
| `marked_scale.svg` | Read the smallest marked increment | Minor marks are visible; alt text does not state their count | pass |
| `uncertainty_interval.svg` | Readable chapter-reference illustration of center and numeric endpoints | Not credited as scheduled instruction | pass |
| `uncertainty_interval_front.svg` | Retrieve endpoints from `estimate ± uncertainty` | Structural labels only; numeric endpoints are absent | pass |

## Planned-versus-actual inventory

| Item | Planned | Actual | Finding |
|---|---|---:|---|
| Basic cards | Default for bounded interpretation, translation, and diagnosis | 19 | All six retrieval families represented; no filler reversals |
| Clozes | Exact recall only for m, s, and kg after explanation | 3 | Plan matched; no parser-ambiguous math clozes |
| Problems | Conversion, dimensions, scale, and reporting | 6 | Two conversion, two dimension, one scale, one reporting |
| Problem progression | Supported before independent work | 6 scheduled problems | Explicit givens and earlier scheduled answers support each problem family without relying on unscheduled examples |
| Figure targets | Five included; complete SI network, conversion decoration, dimensional decoration, and accuracy/precision plots omitted | 5 targets in 6 SVG assets | One extra asset is the no-leak retrieval version of the uncertainty target, not a new quota-driven target |

The omitted figures remain intentional: their authentic decision is clearer in
symbols, or their terminology lies outside the pilot. No planned card form,
problem family, or visual target is missing without explanation.

## Gate decision

Chapter 1 is parse-ready, cold-start complete under the application's actual
scheduling semantics, and limited to its declared scope. Chapters 2–12 remain
unchanged. The deck must stop here until explicit human approval of the pilot.
