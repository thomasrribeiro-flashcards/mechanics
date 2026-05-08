+++
order = 8
tags = ["mechanics", "physics", "momentum", "impulse", "collisions"]
+++

# Classical Mechanics — Momentum and Collisions

## 8.1 Linear Momentum

Q: Why is momentum a more fundamental quantity than kinetic energy when describing "quantity of motion"?
A: Momentum $\vec{p} = m\vec{v}$ is a vector that captures both the magnitude and direction of motion. Two objects with the same kinetic energy can have opposite momenta that cancel, while kinetic energies always add. Momentum is directly linked to Newton's original second law and is conserved even in inelastic collisions where kinetic energy is not.

Q: What is the definition of linear momentum?
A: $\vec{p} = m\vec{v}$, where $m$ is the mass (kg) and $\vec{v}$ is the velocity (m/s). Momentum is a vector in the same direction as $\vec{v}$. Its SI unit is kg·m/s. A larger mass or higher speed produces greater momentum.

C: Linear momentum $\vec{p} = m\vec{v}$ is a [vector] quantity with SI unit [kg·m/s], always pointing in the same direction as the velocity.

## 8.2 Newton's Second Law via Momentum

Q: How does expressing Newton's second law as $\vec{F}_{net} = d\vec{p}/dt$ make it more general than $\vec{F}_{net} = m\vec{a}$?
A: $\vec{F}_{net} = d\vec{p}/dt = d(m\vec{v})/dt$. When mass is constant this reduces to $m\vec{a}$. But for variable-mass systems (rockets expelling fuel, a raindrop collecting mass), mass changes with time and $d\vec{p}/dt \neq m\vec{a}$. The momentum form is Newton's original statement and is always valid.

C: Newton's second law in its most general form is $\vec{F}_{net} = d\vec{p}/dt$, which reduces to $\vec{F}_{net} = m\vec{a}$ only when [mass is constant].

## 8.3 Impulse

Q: What is impulse, and how does it relate to momentum?
A: Impulse is $\vec{J} = \int_{t_1}^{t_2}\vec{F}\,dt$. The impulse-momentum theorem states $\vec{J} = \Delta\vec{p} = \vec{p}_f - \vec{p}_i$. For a constant force: $\vec{J} = \vec{F}\Delta t$. Unit: N·s = kg·m/s. Impulse is a vector.

Q: Why do airbags and padded helmets reduce injury, using the concept of impulse?
A: The change in momentum $\Delta\vec{p}$ (and therefore the impulse) is fixed by the crash. Airbags increase the collision time $\Delta t$, and since $F_{avg} = \Delta p / \Delta t$, a longer $\Delta t$ produces a smaller average force on the occupant, reducing injury.

C: Impulse equals [change in momentum]: $\vec{J} = \Delta\vec{p}$. Extending the collision time [decreases] the average force for a given change in momentum.

## 8.4 Conservation of Linear Momentum

Q: State the law of conservation of linear momentum and identify when it holds.
A: If the net external force on a system is zero ($\vec{F}_{net,ext} = 0$), then the total linear momentum $\vec{p}_{total} = \sum m_i\vec{v}_i$ is constant. Conservation holds component by component, so one direction can be conserved even if another is not. It applies even when internal forces (during collisions) are enormous.

Q: Why is momentum conservation the most important principle for solving collision problems?
A: During a collision, internal forces between objects are very large but cancel in Newton's third law pairs, leaving $\vec{F}_{ext} \approx 0$ over the short collision time. Momentum is therefore conserved regardless of the collision's complexity, even when energy is not. It provides one or more equations relating initial and final velocities.

C: Conservation of momentum requires that the [net external force] on the system equals zero. Internal forces between colliding objects [cancel] in Newton's third law pairs.

## 8.5 Types of Collisions

Q: What is conserved in an elastic collision?
A: Both momentum and kinetic energy.

Q: What is conserved in an inelastic collision?
A: Momentum only — kinetic energy decreases (converts to heat/sound/deformation).

Q: What defines a perfectly inelastic collision?
A: Objects stick together with a common final velocity; maximum KE loss consistent with momentum conservation.

C: In an elastic collision both [momentum] and [kinetic energy] are conserved. In any collision, [momentum] is conserved as long as there is no net external force.

## 8.6 Perfectly Inelastic Collision

Q: Write the equation for a perfectly inelastic collision and explain what happens to kinetic energy.
A: Objects combine after impact: $m_1v_1 + m_2v_2 = (m_1 + m_2)v_f$, where $v_1$, $v_2$ are initial velocities (signed) and $v_f$ is the common final velocity. KE lost $= K_i - K_f > 0$; the lost kinetic energy converts to heat, sound, and deformation.

Q: Two objects of equal mass $m$ undergo a perfectly inelastic collision. Object 1 moves at $v$; object 2 is stationary. What is the final speed and what fraction of kinetic energy is lost?
A: $v_f = mv/(2m) = v/2$. $K_i = \frac{1}{2}mv^2$. $K_f = \frac{1}{2}(2m)(v/2)^2 = \frac{1}{4}mv^2$. KE lost $= \frac{1}{2}mv^2 - \frac{1}{4}mv^2 = \frac{1}{4}mv^2$. Fraction lost $= 50\%$.

C: In a perfectly inelastic collision the two objects [stick together] and move with a [common final velocity], with maximum kinetic energy loss.

## 8.7 Elastic Collision in 1D (Target at Rest)

Q: What are the final velocities in a 1D elastic collision when the target is initially at rest?
A: $v_1' = \dfrac{m_1 - m_2}{m_1 + m_2}v_1$ and $v_2' = \dfrac{2m_1}{m_1 + m_2}v_1$, where $v_1$ is the initial speed of the projectile (mass $m_1$) and the target (mass $m_2$) is at rest. Derived by simultaneously solving conservation of momentum and conservation of kinetic energy.

Q: Describe the three special cases of the elastic collision formula for a target at rest.
A: (1) $m_1 = m_2$: $v_1' = 0$, $v_2' = v_1$; velocities swap — the projectile stops and the target moves off at the original speed. (2) $m_1 \gg m_2$: $v_1' \approx v_1$, $v_2' \approx 2v_1$; heavy projectile barely slows. (3) $m_1 \ll m_2$: $v_1' \approx -v_1$, $v_2' \approx 0$; light projectile bounces back with nearly the same speed.

C: When two equal masses collide elastically (target at rest), the projectile [stops] and the target moves away at the [original speed of the projectile].

## 8.8 Center of Mass

Q: What is the center of mass (CM) of a system, and why does it matter dynamically?
A: $\vec{r}_{cm} = \dfrac{\sum m_i\vec{r}_i}{\sum m_i}$, the mass-weighted average position. It matters because the CM of a system obeys $\vec{F}_{ext} = M\vec{a}_{cm}$ (Newton's 2nd for a system), where $M = \sum m_i$. External forces determine the CM motion; internal forces (collisions, explosions) cannot change $\vec{a}_{cm}$.

Q: What is the velocity of the center of mass, and how does it behave when no external force acts?
A: $\vec{v}_{cm} = \dfrac{\sum m_i\vec{v}_i}{M} = \dfrac{\vec{p}_{total}}{M}$. When $\vec{F}_{ext} = 0$, $\vec{v}_{cm}$ is constant — the CM moves at constant velocity (or stays at rest) regardless of internal explosions or collisions.

C: In an isolated system (no external forces), the center of mass moves at [constant velocity]. Internal forces like collisions and explosions [cannot] change the velocity of the center of mass.

## 8.8a Pattern Recognition: Collisions

Q: A problem says "two objects collide and stick together." What technique?
A: Momentum conservation only ($v_f = (m_1 v_1 + m_2 v_2)/(m_1+m_2)$). KE is NOT conserved — don't try energy conservation.

Q: A problem says "elastic collision, target at rest." What technique?
A: Use the special-case formulas $v_1' = \frac{m_1-m_2}{m_1+m_2}v_1$ and $v_2' = \frac{2m_1}{m_1+m_2}v_1$ — derived from solving momentum + KE conservation simultaneously.

Q: A problem describes an explosion (one object splits into pieces). What technique?
A: Momentum conservation. Total $\vec{p}_{before} = 0$ (if at rest), so the pieces' momenta must sum to zero.

## 8.9 Procedural: Perfectly Inelastic Collision Energy Analysis

P: A 0.1 kg ball moving at 5 m/s collides and sticks with a stationary 0.4 kg ball. Find: (a) final velocity, (b) initial KE, (c) final KE, (d) KE lost.

S: **Identify:** Perfectly inelastic collision. $m_1 = 0.1$ kg, $v_1 = 5$ m/s; $m_2 = 0.4$ kg, $v_2 = 0$. Momentum is conserved; kinetic energy is not.

**Plan:** Use momentum conservation to find $v_f$, then compute KE before and after.

**Execute:**
(a) $m_1v_1 = (m_1+m_2)v_f$
$v_f = \dfrac{(0.1)(5)}{0.1+0.4} = \dfrac{0.5}{0.5} = 1.0$ m/s.

(b) $K_i = \frac{1}{2}(0.1)(5)^2 = \frac{1}{2}(0.1)(25) = 1.25$ J.

(c) $K_f = \frac{1}{2}(0.5)(1.0)^2 = 0.25$ J.

(d) $\Delta K = K_f - K_i = 0.25 - 1.25 = -1.0$ J. KE lost $= 1.0$ J (80% of initial KE).

**Evaluate:** Momentum check: $0.5$ kg·m/s before $= (0.5)(1.0) = 0.5$ kg·m/s after. Units consistent. 80% KE loss is large but typical for very unequal masses with the lighter one being the projectile — sensible.
