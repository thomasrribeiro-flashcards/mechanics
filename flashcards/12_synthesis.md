+++
order = 12
subject = "physics"
tags = ["mechanics", "physics", "synthesis", "model-selection", "problem-solving"]
+++

# Classical Mechanics — Model Selection and Synthesis

## 12.1 Choosing the System and Model

Q: Why should a mechanics solution define the system before choosing a conservation law?
A: The system boundary determines which interactions are internal and which transfer energy or momentum across the boundary. A quantity may be conserved for a larger system but not for one object inside it.

Q: A question asks for acceleration at an instant and gives the forces acting then. Which framework is the direct choice, and why?
A: Draw a free-body diagram and use $\sum\vec F=m\vec a$. The requested acceleration is determined by the net force at that instant.

Q: A question asks only for speed after a known displacement, while forces may vary with position. Which framework often avoids unnecessary work?
A: Use work–energy, $\Delta K=W_{net}$, or energy accounting with potential energy. It relates speed to displacement without first finding time or acceleration as a function of time.

Q: A very short collision has large internal forces but negligible external impulse. Which quantity should organize the solution?
A: The total momentum of the chosen collision system is approximately conserved during the impact. Kinetic energy is conserved only if the collision is also elastic.

Q: Motion has known constant acceleration and the question connects position, velocity, and time. What model is sufficient?
A: Constant-acceleration kinematics. It describes the motion without explaining what forces produced the acceleration.

Q: A rigid body's angular speed changes because forces act away from an axis. What two steps connect those forces to the angular motion?
A: Compute each torque about the chosen axis, then use $\sum\tau=I\alpha$ when the body and fixed-axis assumptions make $I$ constant.

Q: A system makes small oscillations about a stable equilibrium. How can its leading-order motion be tested for SHM?
A: Expand or approximate the restoring force near equilibrium. If $F\approx-k_{eff}x$ with $k_{eff}>0$, then $\omega=\sqrt{k_{eff}/m}$ for translational motion.

## 12.2 Discriminating Similar Ideas

Q: When is Newton's second law more informative than energy conservation for the same motion?
A: Use Newton's law when forces, acceleration, direction, contact conditions, or time dependence are required. Energy is often shorter for endpoint speeds but does not by itself give force direction or elapsed time.

Q: During a collision, how do the conservation tests for momentum and kinetic energy differ?
A: Momentum is conserved when the net external impulse is negligible. Kinetic energy is conserved only for an elastic collision; in a closed-system account, an inelastic collision converts some of it to internal energy while total energy remains conserved.

Q: Does constant speed imply zero net force?
A: No. Constant speed fixes only the magnitude of velocity. Uniform circular motion has constant speed but an inward net force that continuously changes the velocity's direction.

Q: Is “centripetal force” an additional force to draw on a free-body diagram?
A: No. It is the name for the inward component of the net real force, $\sum F_r=mv^2/r$. Identify which real forces—such as tension, gravity, or friction—produce that net component.

Q: A student sets the normal force equal to $mg$ in every contact problem. What condition did they fail to check?
A: They must apply the force equation perpendicular to the surface. $N=mg$ only in special geometries with no other perpendicular force components and no perpendicular acceleration.

Q: What is the difference between translational equilibrium and static equilibrium for a rigid body?
A: Translational equilibrium requires $\sum\vec F=0$. Static equilibrium also requires $\sum\vec\tau=0$ and zero initial motion, so the body neither translates nor rotates.

Q: Why is dimensional consistency necessary but not sufficient evidence that a mechanics result is correct?
A: A wrong equation can still have matching units. After checking dimensions, also test sign, direction, scale, limiting cases, and any relevant conservation law.

Q: How does a limiting-case check expose a faulty symbolic answer?
A: Set a parameter to a physically simple extreme—such as friction $\mu\to0$, mass ratio $m/M\to0$, or radius $r\to\infty$. The formula should reduce to the known behavior of that simpler system.

## 12.3 Translating Representations

Q: On a velocity-versus-time graph, what do the slope and signed area represent?
A: The slope is acceleration, and the signed area over a time interval is displacement. Distance requires accounting for the magnitude of velocity rather than simply using signed area.

Q: On a force-versus-position graph, what does the signed area represent?
A: The work done by that force, $W=\int F_x\,dx$. An area below the position axis is negative work for motion in the positive direction.

Q: What does the curvature of a position-versus-time graph reveal before any calculation?
A: Concave up means positive acceleration and concave down means negative acceleration, for the chosen positive axis. The graph's slope gives velocity, so curvature describes how that slope changes.

Q: A symbolic result for a speed contains a negative quantity under a square root. What should be concluded first?
A: The assumed motion is impossible under the stated parameters or an earlier sign/model choice is wrong. Do not discard the sign merely to force a numerical answer.

## 12.4 Mixed Physical Situations

Q: A projectile embeds in a hanging block, and the combined object then swings upward. Why must the motion be split into two models?
A: During the brief inelastic collision, momentum is approximately conserved but mechanical energy is not. During the later swing, mechanical energy is conserved if pivot friction and air drag are negligible.

Q: A block slides down a rough incline and only its speed after distance $d$ is requested. What are two valid approaches, and which is usually shorter?
A: Newton's law along the incline followed by kinematics is valid if acceleration is constant; work–energy with friction is usually shorter because it connects the endpoints directly.

Q: A rolling object descends without slipping. Why are energy conservation and the rolling constraint both needed to find its speed?
A: Energy must include translational and rotational kinetic energy, while $v_{cm}=R\omega$ connects the two unknown speeds. The constraint is kinematic; it does not mean friction dissipates energy.

Q: In a circular satellite orbit, how do force and energy descriptions complement each other?
A: Gravity supplying $mv^2/r$ determines $v=\sqrt{GM/r}$. Substituting that speed into $K+U$ gives the bound-orbit energy $E=-GMm/(2r)$.

Q: Two blocks are connected by an ideal taut string over a massless frictionless pulley. What constraint and force fact couple their equations?
A: The blocks have equal acceleration magnitudes along the string, and the tension has the same magnitude on both sides. Their acceleration directions are opposite along a single signed coordinate around the string.

## 12.5 Faded Integrative Problems

P: Two masses $m_1$ and $m_2$ with $m_2>m_1$ hang from an ideal massless string over a massless frictionless pulley. Starting from the force laws for each mass, derive the magnitude of their acceleration.

S:
**IDENTIFY**: Include both masses as the system. The ideal string imposes one acceleration magnitude $a$ and one tension $T$.

**PLAN**: Take positive along the motion: upward for $m_1$ and downward for $m_2$. Write Newton's second law for each mass, then add the equations to eliminate the internal tension.

**EXECUTE**:
$$T-m_1g=m_1a$$
$$m_2g-T=m_2a$$
Adding gives $(m_2-m_1)g=(m_1+m_2)a$, so
$$a=\frac{m_2-m_1}{m_1+m_2}g.$$

**EVALUATE**: The result has units of acceleration, is positive for $m_2>m_1$, becomes zero when the masses are equal, and approaches $g$ when $m_2\gg m_1$.

P: A projectile of mass $m$ moving horizontally at unknown speed $u$ embeds in a stationary pendulum block of mass $M$. The combined mass rises through vertical height $h$. Neglect external impulse during impact and losses during the swing. Derive $u$.

S:
**IDENTIFY**: This is a two-stage process. The impact is perfectly inelastic; the subsequent swing is conservative.

**PLAN**: Let $V$ be the speed just after impact. Use momentum conservation to connect $u$ to $V$, then mechanical-energy conservation to connect $V$ to $h$.

**EXECUTE**:
$$mu=(M+m)V$$
$$\frac12(M+m)V^2=(M+m)gh$$
Thus $V=\sqrt{2gh}$ and
$$u=\frac{M+m}{m}\sqrt{2gh}.$$

**EVALUATE**: $u>V$ because the projectile's momentum is shared with the larger combined mass. If $h\to0$, both speeds approach zero; the dimensions are those of speed.
