+++
order = 1
tags = ["mechanics", "physics", "measurement", "units", "dimensional analysis"]
+++

# Classical Mechanics — Foundations

## 1.1 Why Classical Mechanics

Q: What does "classical" mean in "classical mechanics"?
A: Non-quantum and non-relativistic. It describes the motion of everyday macroscopic objects at speeds much less than the speed of light ($v \ll c$).

Q: Why is classical mechanics studied before quantum or relativistic mechanics?
A: It is built on Galileo's experimental foundation and Newton's laws, which accurately describe everyday phenomena. It provides the conceptual framework that quantum and relativistic theories extend or correct.

Q: What is the practical validity range of classical mechanics?
A: Objects that are macroscopic (not atomic-scale) and moving at speeds much less than the speed of light. Outside this range — very small scales or very high speeds — quantum or relativistic corrections are required.

C: Classical mechanics is organized around [Newton's laws] as its central framework.

## 1.2 The Scientific Method

Q: Why is falsifiability essential in physics?
A: A claim that cannot in principle be disproved by experiment provides no predictive power and is outside the domain of science. Falsifiability ensures theories can be tested and potentially overturned by evidence.

C: The scientific method follows the cycle: [observation] → hypothesis → experiment → theory.

Q: What distinguishes a "theory" in physics from a guess?
A: A physical theory is a well-tested model that has survived repeated experimental scrutiny and makes quantitative predictions. In everyday language "theory" implies uncertainty; in physics it implies established, validated explanation.

Q: What is the difference between a hypothesis, a theory, and a law in physics?
A: A hypothesis is a testable initial conjecture. A theory is a well-tested explanatory model. A law is a concise description of an observed regularity (often mathematical), but does not by itself explain why.

## 1.3 SI Units and Base Quantities

Q: Why does physics use a standardized unit system?
A: Standardization ensures measurements are reproducible and comparable worldwide. Without agreed units, numerical results cannot be shared or verified across laboratories.

C: The SI system has [7] base quantities from which all other units are derived.

C: The SI unit of mass is the [kilogram (kg)].

C: The SI unit of length is the [meter (m)].

C: The SI unit of time is the [second (s)].

Q: Name the seven SI base quantities and their units.
A: Mass (kg), length (m), time (s), electric current (A), thermodynamic temperature (K), amount of substance (mol), luminous intensity (cd).

Q: What are derived units in SI?
A: Units formed by combining base units through multiplication or division. For example, velocity has units m/s, force has units kg·m/s² (called the Newton, N).

## 1.4 Dimensional Analysis

Q: Why must every valid physical equation be dimensionally consistent?
A: Because you cannot add or equate quantities of different physical kinds — adding a length to a time is meaningless. Dimensional consistency is a necessary (though not sufficient) condition for a correct equation.

C: The notation $[v] = \text{L/T}$ means the [dimension] of velocity is length divided by time.

Q: How do you check whether a proposed equation is dimensionally consistent?
A: Replace every quantity with its dimensions (L, M, T, etc.) and verify that the dimensions on the left-hand side equal those on the right-hand side.

Q: How can dimensional analysis be used to derive a relationship (without full physics)?
A: By identifying which physical quantities are relevant and requiring the combination to have the correct dimensions, you can determine the form of the equation up to a dimensionless constant. Example: distance must combine speed and time as $d \sim v \cdot t$ because $[\text{L}] = [\text{L/T}]\cdot[\text{T}]$.

C: Dimensional analysis can check equations and [derive relationships] between physical quantities up to a dimensionless constant.

## 1.5 Order-of-Magnitude Estimation

Q: Why estimate before calculating exactly?
A: An order-of-magnitude estimate reveals the scale of the answer, catches setup errors early, and builds physical intuition. An exact answer that is orders of magnitude off likely indicates a conceptual mistake.

Q: What is the Fermi estimation technique?
A: Break a complex quantity into simpler sub-quantities you can estimate individually (each to one significant figure or nearest power of 10), then multiply or divide them. The product gives an order-of-magnitude answer.

C: In Fermi estimation, quantities are expressed as [powers of 10] and combined to give an order-of-magnitude result.

Q: What are the steps in an order-of-magnitude estimate?
A: Identify the key quantities needed, estimate each to the nearest power of ten using known facts or reasonable guesses, then combine them to get the final estimate.

## 1.6 Significant Figures

Q: What do significant figures represent?
A: The precision of a measurement. Reporting more significant figures than the measurement device can resolve is misleading; reporting fewer discards real information.

Q: What is the rule for significant figures in addition and subtraction?
A: The result should have the same number of decimal places as the measurement with the fewest decimal places.

Q: What is the rule for significant figures in multiplication and division?
A: The result should have the same number of significant figures as the measurement with the fewest significant figures.

C: In multiplication and division, the result keeps as many significant figures as the measurement with the [fewest] significant figures.

C: In addition and subtraction, the result is rounded to the [least number of decimal places] among all measurements.

Q: Why must precision in a final answer be justified by the measurements?
A: Writing extra digits implies a precision that was never measured, which is misleading. Physical results can only be as precise as the least precise input.

## 1.7 Worked Example — Dimensional Analysis of Free Fall

P: A stone is released from rest at height $h$ above the ground. Without using the kinematic equations, use dimensional analysis alone to determine how the time of fall $t$ depends on $h$ and the gravitational acceleration $g$, up to a dimensionless constant.

S:
**IDENTIFY**: We want $t$ as a function of $h$ (dimension L) and $g$ (dimension L/T²). Assume a power-law form $t = C\,h^a g^b$, where $C$ is a dimensionless constant and $a$, $b$ are unknown exponents.

**PLAN**:
- Write the dimensional equation: $[t] = [h]^a[g]^b$.
- Expand and collect powers of each base dimension (L and T).
- Match the powers on both sides and solve for $a$ and $b$.

**EXECUTE**:

Dimensions: $[t] = T$, $[h] = L$, $[g] = L/T^2 = LT^{-2}$.

$$T = L^a(LT^{-2})^b = L^{a+b}\,T^{-2b}$$

Matching powers of each base dimension:
- Powers of $L$: $a + b = 0$
- Powers of $T$: $-2b = 1 \implies b = -\tfrac{1}{2}$

Substitute back: $a = -b = +\tfrac{1}{2}$.

Therefore $t \sim h^{1/2}g^{-1/2} = \sqrt{h/g}$.

**EVALUATE**:
- The exact kinematic result is $t = \sqrt{2h/g}$, so the dimensionless constant is $C = \sqrt{2} \approx 1.41$ — of order unity as expected ✓
- Dimensional analysis cannot pin down $C$, only the functional form. This is the generic limitation of the method.
- Sanity check: doubling $h$ multiplies $t$ by $\sqrt{2}$, not by 2 — consistent with intuition that falling twice as far takes less than twice as long because the object speeds up ✓
