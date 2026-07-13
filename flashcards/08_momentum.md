+++
order = 8
subject = "physics"
tags = ["mechanics", "physics", "momentum", "impulse", "collisions"]
+++

# Classical Mechanics — Momentum and Collisions

## 8.1 Linear Momentum

Q: Why is momentum especially useful for collisions compared with kinetic energy?
A: Momentum is a vector and is conserved for an isolated system in every collision. Kinetic energy is conserved only in elastic collisions, so it cannot generally determine an inelastic collision by itself.

Q: What is the definition of linear momentum?
A: $\vec{p} = m\vec{v}$, where $m$ is the mass (kg) and $\vec{v}$ is the velocity (m/s). Momentum is a vector in the same direction as $\vec{v}$. Its SI unit is kg·m/s. A larger mass or higher speed produces greater momentum.

C: Linear momentum $\vec{p} = m\vec{v}$ is a [vector] quantity with SI unit [kg·m/s], always pointing in the same direction as the velocity.

## 8.2 Newton's Second Law via Momentum

Q: For what system is $\vec F_{ext}=d\vec p/dt$ directly valid, and why do rockets require extra care?
A: It applies directly to a fixed set of particles, reducing to $m\vec a$ when its mass is constant. A rocket is an open system: expelled fuel carries momentum across the chosen boundary, so a momentum-flux term must be included rather than blindly differentiating $m\vec v$ for the remaining rocket.

C: For a fixed set of particles, $\vec{F}_{ext}=d\vec p/dt$ reduces to $\vec{F}_{ext}=m\vec a$ when [mass is constant].

## 8.3 Impulse

Q: What is impulse, and how does it relate to momentum?
A: Impulse is $\vec{J} = \int_{t_1}^{t_2}\vec{F}\,dt$. The impulse-momentum theorem states $\vec{J} = \Delta\vec{p} = \vec{p}_f - \vec{p}_i$. For a constant force: $\vec{J} = \vec{F}\Delta t$. Unit: N·s = kg·m/s. Impulse is a vector.

Q: Why do airbags and padded helmets reduce injury, using the concept of impulse?
A: The change in momentum $\Delta\vec{p}$ (and therefore the impulse) is fixed by the crash. Airbags increase the collision time $\Delta t$, and since $F_{avg} = \Delta p / \Delta t$, a longer $\Delta t$ produces a smaller average force on the occupant, reducing injury.

C: Impulse equals [change in momentum]: $\vec{J} = \Delta\vec{p}$. Extending the collision time [decreases] the average force for a given impulse.

## 8.4 Conservation of Linear Momentum

Q: State the law of conservation of linear momentum and identify when it holds.
A: A system's momentum change equals its net external impulse. Thus $\vec p_{total}$ is conserved over an interval when the net external impulse is zero or negligible; this can hold component by component.

Q: Why is momentum often approximately conserved during a brief collision even when external forces such as weight exist?
A: The collision time is so short that the external impulse is often negligible compared with the exchanged internal impulses. Including all colliding objects makes the internal impulse pairs cancel in the system's total momentum balance.

C: Conservation of momentum over a collision requires negligible [net external impulse]. Internal collision forces [cancel] in Newton's third-law pairs when the whole interacting system is included.

## 8.5 Types of Collisions

Q: What is conserved in an elastic collision?
A: Both momentum and kinetic energy.

Q: What is conserved in an inelastic collision?
A: For an isolated system, momentum is conserved but kinetic energy is not generally conserved. Total energy is still conserved; some kinetic energy becomes deformation, internal energy, or sound.

Q: What defines a perfectly inelastic collision?
A: Objects stick together with a common final velocity; maximum KE loss consistent with momentum conservation.

C: In an elastic collision both [momentum] and [kinetic energy] are conserved.

C: In any collision, [momentum] is conserved as long as there is no net external force.

## 8.6 Perfectly Inelastic Collision

Q: Write the equation for a perfectly inelastic collision and explain what happens to kinetic energy.
A: Objects combine after impact: $m_1v_1 + m_2v_2 = (m_1 + m_2)v_f$, where $v_1$, $v_2$ are initial velocities (signed) and $v_f$ is the common final velocity. KE lost $= K_i - K_f > 0$; the lost kinetic energy converts to heat, sound, and deformation.

Q: Two objects of equal mass $m$ undergo a perfectly inelastic collision. Object 1 moves at $v$; object 2 is stationary. What is the final speed and what fraction of kinetic energy is lost?
A: $v_f = mv/(2m) = v/2$. $K_i = \frac{1}{2}mv^2$. $K_f = \frac{1}{2}(2m)(v/2)^2 = \frac{1}{4}mv^2$. KE lost $= \frac{1}{2}mv^2 - \frac{1}{4}mv^2 = \frac{1}{4}mv^2$. Fraction lost $= 50\%$.

C: In a perfectly inelastic collision the two objects [stick together] and move with a [common final velocity], with maximum kinetic energy loss.

## 8.7 Elastic Collision in 1D (Target at Rest)

Q: What are the final velocities in a 1D elastic collision when the target is initially at rest?
A: $v_1' = \dfrac{m_1 - m_2}{m_1 + m_2}v_1$ and $v_2' = \dfrac{2m_1}{m_1 + m_2}v_1$, where $v_1$ is the initial speed of the projectile (mass $m_1$) and the target (mass $m_2$) is at rest. Derived by simultaneously solving conservation of momentum and conservation of kinetic energy.

Q: In a 1D elastic collision with an equal-mass target initially at rest, what happens?
A: The velocities exchange: the projectile stops and the target leaves with the projectile's initial velocity.

Q: In a 1D elastic collision with a stationary target much lighter than the projectile, what happens approximately?
A: The heavy projectile continues at nearly its original velocity, while the light target leaves at nearly twice that velocity.

Q: In a 1D elastic collision with a stationary target much heavier than the projectile, what happens approximately?
A: The light projectile reverses with nearly its original speed, while the heavy target barely moves.

C: When two equal masses collide elastically (target at rest), the projectile [stops] and the target moves away at the [original speed of the projectile].

## 8.8 Center of Mass

Q: What is the center of mass (CM) of a system, and why does it matter dynamically?
A: $\vec{r}_{cm} = \dfrac{\sum m_i\vec{r}_i}{\sum m_i}$, the mass-weighted average position. It matters because the CM of a system obeys $\vec{F}_{ext} = M\vec{a}_{cm}$ (Newton's 2nd for a system), where $M = \sum m_i$. External forces determine the CM motion; internal forces (collisions, explosions) cannot change $\vec{a}_{cm}$.

Q: What is the velocity of the center of mass, and how does it behave when no external force acts?
A: $\vec{v}_{cm} = \dfrac{\sum m_i\vec{v}_i}{M} = \dfrac{\vec{p}_{total}}{M}$. When $\vec{F}_{ext} = 0$, $\vec{v}_{cm}$ is constant — the CM moves at constant velocity (or stays at rest) regardless of internal explosions or collisions.

C: In an isolated system (no external forces), the center of mass moves at [constant velocity]. Internal forces like collisions and explosions [cannot] change the velocity of the center of mass.

Q: How do you apply momentum conservation to a two-dimensional collision?
A: Choose axes and conserve momentum separately: $\sum p_{x,i}=\sum p_{x,f}$ and $\sum p_{y,i}=\sum p_{y,f}$, provided the external impulse is negligible in those directions.

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
