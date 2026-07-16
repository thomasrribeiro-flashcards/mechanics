# Chapter 2 cold-start audit: vectors

Audit date: 2026-07-15

Scope: flashcards/02_vectors.md and its chapter-boundary dependencies

Learner: independent adult novice in physics

Allowed prerequisites: the scheduled cards in 01_foundations.md, the declared
algebra and trigonometry prerequisites, plane geometry, and general literacy

## Method

The scan followed the scheduled order. For each card, the front—including
image alt text, symbols, givens, and requested procedure—was inspected and its
dependencies were recorded before the corresponding answer or solution was
checked. The answer was then checked for terms or representations exported to
later fronts. Unscheduled headings, prose, display equations, and figures were
not credited as establishment points.

## Chapter-boundary dependency ledger

| Allowed inbound dependency | Evidence | Limit applied in this audit |
|---|---|---|
| Arithmetic, signed numbers, algebraic rearrangement, square roots | Declared algebra prerequisite | No vector operation or notation inferred |
| Plane geometry, Pythagorean theorem, right triangles, sine/cosine/tangent and inverse trigonometry | Declared algebra and trigonometry prerequisites | No axes, quadrant numbering, direction-angle convention, or component formula inferred |
| Quantity value, numerical value, unit, SI spacing, and dimensions \(L,M,T\) | Scheduled chapter-1 F04–F18 | No scalar/vector classification inferred |
| Powers-of-ten scale, resolution, uncertainty, and significant figures | Scheduled chapter-1 F19–F28 | Available but not required by a chapter-2 front |
| Ordinary arrows, tables, and grid counting | General literacy | Tail/head vector grammar, vector equality, projections, and page-normal symbols required explicit chapter-2 bridges |

No chapter after chapter 1 was used as an inbound source. Motion quantities,
forces, work, torque, energy, momentum, polar coordinates, and later-mechanics
representations were excluded from all fronts.

## Front-by-front audit

| Front | Card ID | Dependencies recorded from the front | Allowed source or earlier establishment | Answer export and status |
|---:|---|---|---|---|
| F01 | 2c581265-26a2-4f41-84f2-154c557d9105 | arrow, length, magnitude, direction, equal vectors | Ordinary arrow/length literacy; front defines vector encoding and the equality decision | Answer adds no new dependency; resolved |
| F02 | 7e9e7b45-cec0-400e-9949-853af87923bc | P/Q/R labels, translated arrows, visual equality | F01; alt text states all setup geometry without naming the answer | “Opposite direction” is ordinary language and supports F05; resolved |
| F03 | 522ff6f7-d850-49a7-8d00-9dd9ec6a7b05 | scalar, vector, magnitude, direction, meter/unit | Front defines scalar/vector; F01 defines magnitude/direction; chapter-1 F04/F06 establishes units and meter | Answer only applies the stated distinction; resolved |
| F04 | 9880553d-2c01-49b1-bd1f-a711ff619f60 | \(\vec A\), \(A=|\vec A|\), nonnegative magnitude | Front defines notation; F01 establishes magnitude as arrow length; signed numbers inbound | Answer exports \(A\ge0\), already inferable from length; resolved |
| F05 | 2bd5b2b2-fcd6-4b5b-858b-cfc932829e19 | opposite vector, \(-\vec A\) | Front explicitly defines reversal without length change; F01/F04 | Answer exports the compact magnitude equality for later use; resolved |
| F06 | ce6aeeff-3115-46c6-bfec-23aeebb4d77c | scalar multiplication, absolute value, negative scale factor | Front states both magnitude and direction effects; algebra prerequisite; F05 | Answer is a direct application; resolved |
| F07 | 39907800-42f3-4d37-800a-b12c3f709ecf | Cartesian grid, +x/+y, signed scalar components, origin, dashed projections | Front defines axis directions and components as horizontal/vertical tail-to-head changes; grid counting and signed numbers inbound | Answer supplies the first component values and sign explanation; resolved |
| F08 | 9684151a-da32-48bd-b1b7-d651586147da | axes, four numbered quadrants, quadrant II, component signs | Front defines quadrant numbering and upper-left location; F07 establishes axes/components | Answer exports the left/right and up/down sign rule used later; resolved |
| F09 | 63c72303-bdee-41be-ad2b-ddc9458ee50f | unit vector, \(\hat{\mathbf i}\), \(\hat{\mathbf j}\), component form | Front defines unit-vector magnitude and directions; F07 establishes components; algebra inbound | Answer supplies the first supported symbolic translation; resolved |
| F10 | 8d237cf6-f47b-486e-8a24-ed2386a3b23d | direction angle from +x, counterclockwise convention, component formulas, sign/magnitude checks | Front gives the convention and \(A_x=A\cos\theta,\ A_y=A\sin\theta\); trigonometry inbound; F07–F09 | Solution exports the Pythagorean magnitude check and analyzed decomposition method; resolved |
| F11 | 18ef7bbf-78a9-42b8-ac2f-ecb760c25ead | \(120^\circ\) direction angle, components, quadrant sign check | F08 establishes quadrant II; F10 establishes angle convention/formulas | Answer is an independent quadrant-II execution; resolved |
| F12 | 64ad7ad7-c9ab-408c-8085-8db8af9568c4 | magnitude and direction from components, reference angle, quadrant selection | Front names the Pythagorean and inverse-tangent methods; mathematics inbound; F07/F08/F10 | Solution establishes a complete reconstruction and substitution/sign checks; resolved |
| F13 | b499087a-b030-4d39-9f92-5d4b6e6c34b8 | rotated axes, components/direction angle versus geometric vector | F01 establishes geometric-vector invariance under translation; F07 and F10 establish axis-relative descriptions | Answer states the coordinate-dependent/invariant distinction; resolved |
| F14 | 62ac7ea9-9e87-4645-8049-56ad2a1887d2 | vector quantity, meters, component units/dimensions, unit vectors | Chapter-1 quantity/unit/dimension cards; F03 scalar/vector distinction; F07/F09 | Answer exports the same-unit/same-dimension rule; resolved |
| F15 | 112da66d-3555-4cc2-b477-6ffe0e2e33f7 | tail-to-head addition, translation without rotation/stretching, resultant | Front defines the construction and resultant; F01/F02 establish movable equal arrows | Answer and back figure reveal the completed start-to-finish arrow only after retrieval; resolved |
| F16 | 3abc47bb-0b69-4182-840e-3e3c81bca8bb | sum components \(R_x,R_y\) | Front bridges horizontal and vertical changes; F07 establishes components; F15 establishes sum | Answer gives the componentwise rule used by F17; resolved |
| F17 | 240cf3e4-7bd0-401a-b1dc-8d3e7469b8a2 | ordered-pair component shorthand, component addition, magnitude check | Front defines tuple order; F16 gives addition; F12 gives magnitude reconstruction | Full IPEE execution exports no unexplained term; resolved |
| F18 | 3af48404-eafa-43c5-bdbb-c0909a261913 | subtraction as addition of the opposite, graphical construction | Front defines subtraction; F05 establishes opposite vector; F15 establishes tail-to-head addition | Answer applies the construction; resolved |
| F19 | 3ca7686b-6606-46ce-b6d7-95d32c414e3c | ordered pairs, component subtraction, inverse-operation check | F17 tuple convention; F18 subtraction; algebra prerequisite | Answer verifies by addition, already established at F16; resolved |
| F20 | dc1d4af6-8fab-45da-b813-0625f5442067 | sum magnitude versus sum of magnitudes, direction/cancellation | F01/F04 magnitudes; F05 opposite; F15–F19 vector addition | Answer states the same-direction boundary and repairs scalar-addition interference; resolved |
| F21 | 9565c515-a2f7-4cc0-950e-9d9e7e2a0eac | tail-to-tail angle, nonzero vectors, dot product, scalar output, cosine sign | Front defines the product, angle domain, and output type; F03/F04; trigonometry inbound | Answer supplies the obtuse-angle sign boundary; resolved |
| F22 | 3d21a554-6b79-493f-9e5e-86a22f409baf | perpendicular vectors and zero dot product | Plane geometry inbound; F21 formula and angle convention | Answer connects zero to both cosine and zero aligned component; resolved |
| F23 | 045fc394-69ad-44b4-a64a-f8c5b6b0298e | signed projection \(B_{\parallel}\), dashed perpendicular, alignment | Front defines projection; F07 components; F21 dot product; perpendicular geometry inbound | Answer exports \(\vec A\boldsymbol\cdot\vec B=A B_\parallel\); resolved |
| F24 | 6189fad3-8c79-4696-9acd-334183782c56 | component dot-product formula, tuple notation, scalar/vector discrimination | Front gives the formula; F17 tuple convention; F21 output type | Answer exports the product-of-input-units rule later used for product units; resolved |
| F25 | dea2fd3a-9931-439d-aa5f-3f08e2b22c11 | magnitudes from components, dot product, inverse cosine | F12 reconstruction; F21 angle formula; F24 component formula; trigonometry inbound | Answer is an independent angle-recovery execution; resolved |
| F26 | affcc093-4ee8-4dc8-b233-eb0fde49d499 | order reversal, angle and component definitions | F21 and F24; ordinary-number multiplication inbound | Answer establishes dot-product commutativity for later contrast; resolved |
| F27 | 72a8c3e7-6a06-4add-9346-ab5d1bb9f8ee | right-handed x/y/z convention, cross product, perpendicular output, right-hand rule, \(\hat{\mathbf i},\hat{\mathbf j}\), page direction | Front defines the 3-D convention, output, and procedure; F09 establishes i/j unit vectors; plane perpendicularity inbound | Answer establishes \(\hat{\mathbf k}\) as +z and the out-of-page \(\odot\) cue for F28 onward; a learner may answer “+z, out of page”; resolved |
| F28 | 9383ff7a-be3d-4ab3-862e-02401ab38c7c | cross-product order reversal, \(\hat{\mathbf k}\), into-page direction | F27 answer establishes k/out-of-page; front states reversal | Answer exports anticommutative notation and \(\otimes\); resolved |
| F29 | 44373b92-0bd7-433a-a01c-81fb05318668 | cross magnitude, sine, parallel/opposite vectors, zero product | Front gives formula; trigonometry and parallel geometry inbound; F05 opposite; F21 angle symbol/domain | Answer exports zero spanned area, supporting F30; resolved |
| F30 | 3fa79b08-b730-49d7-a433-032547da7b5b | parallelogram, dashed height, \(AB\sin\phi\) | Plane geometry inbound; F29 answer introduces the spanned-area connection; figure contains setup only | Answer derives base-times-height interpretation; resolved |
| F31 | 04f774f0-59c1-4909-8b44-a14587861a7b | maximum cross magnitude at fixed inputs | F29 formula; sine behavior from trigonometry | Answer gives the \(90^\circ\) boundary used to check F32; resolved |
| F32 | c111e5df-414a-49f0-866a-43f582004c0f | right-handed xy-plane, cross magnitude/direction, right-hand rule, product units | F27 convention/rule; F29 formula; F31 bound; chapter-1 units and F24 product-unit rule | Full IPEE solution checks perpendicularity and the \(AB\) upper bound; resolved |
| F33 | 157334e2-12db-417e-92d6-87cc9e490e9b | xyz ordered triple, supplied cross-component formula, i/j/k, dot-product perpendicularity check | Front defines triple order and supplies formula; F27–F28 establish axes/unit vectors; F24 dot computation | Answer executes and checks both zero dot products; resolved |
| F34 | fd7ed1b5-edc4-4978-9df7-b29759e949fb | scalar signed alignment versus perpendicular vector/spanned area | F21–F26 establish dot product; F27–F33 establish cross product | Mixed discrimination uses only established products; resolved |

## Repair record

The first scan identified ten first-use defects before acceptance: premature
component wording on F04; an implicit opposite-vector definition on F05;
unexplained quadrant numbering on F08; missing decomposition formulas on F10;
missing reconstruction guidance on F12; an undefined resultant on F15; an
unstated component-addition bridge on F16; unexplained tuple notation on F17;
an unstated component dot-product formula on F24; and an unexplained
three-component tuple convention on F33. Each was repaired on the affected
scheduled front and the scan was repeated from F01.

No answer introduces a dependency required by an earlier front. The only
answer-to-later-front exports are explicit in the table and occur in order.

cold_start_status: pass
unresolved_dependencies: 0
