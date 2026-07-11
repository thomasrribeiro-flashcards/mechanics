+++
order = 7
subject = "physics"
tags = ["mechanics", "physics", "energy", "work", "conservation"]
+++

# Classical Mechanics — Work and Energy

## 7.1 Work

Q: Why is work defined as a dot product rather than just $F \times d$?
A: Because only the component of force along the displacement does work. A force perpendicular to motion (e.g., normal force on a horizontal surface) causes no change in speed, so it should contribute zero work. The dot product automatically extracts the parallel component.

Q: What is the definition of work done by a constant force?
A: $W = \vec{F} \cdot \vec{d} = Fd\cos\theta$, where $F$ is the force magnitude (N), $d$ is the displacement magnitude (m), and $\theta$ is the angle between the force vector and the displacement vector. Work is a scalar. Its SI unit is the joule (J = N·m).

C: Work is [positive] when the force has a component along the direction of motion.

C: Work is [negative] when the force opposes the motion.

C: Work is [zero] when the force is perpendicular to the displacement.

Q: A box is pushed 4 m along a floor by a 10 N force directed 60° above horizontal. How much work does the pushing force do?
A: $W = Fd\cos\theta = (10)(4)\cos 60° = 40 \times 0.5 = 20$ J.

## 7.2 Work by a Variable Force

Q: Why must an integral be used to compute work when force varies with position?
A: With a variable force, $F$ changes over each infinitesimal displacement $dx$, so work cannot be found by simple multiplication. Summing infinitesimal contributions gives $W = \int_{x_i}^{x_f} F(x)\,dx$, which equals the area under the $F$-vs-$x$ graph.

C: The work done by a variable force equals the [area under the $F$-vs-$x$ graph] between the initial and final positions.

Q: What is the work done by a spring when it is compressed or stretched?
A: $W_{spring} = \frac{1}{2}kx_i^2 - \frac{1}{2}kx_f^2$, where $k$ is the spring constant (N/m) and $x_i$, $x_f$ are the initial and final displacements from equilibrium. Equivalently, $W_{spring} = -\Delta U_e = -(\frac{1}{2}kx_f^2 - \frac{1}{2}kx_i^2)$.

## 7.3 Kinetic Energy

Q: Why is kinetic energy always non-negative?
A: $K = \frac{1}{2}mv^2$, where $m$ is mass (kg) and $v$ is speed (m/s). Both $m$ and $v^2$ are never negative, so $K \geq 0$. A stationary object has $K = 0$; kinetic energy reaches zero only when the object stops.

C: Kinetic energy is $K = \frac{1}{2}mv^2$. Doubling an object's speed [quadruples] its kinetic energy, because $K \propto v^2$.

## 7.4 Work-Energy Theorem

Q: How should the net work done on an object relate to its kinetic energy?
A: They should be equal — work has units of energy, and applying force over distance is precisely how speed (and thus $K$) is built up.

Q: State the work-energy theorem and explain its significance.
A: $W_{net} = \Delta K = K_f - K_i$. Net work on an object equals its change in kinetic energy. Holds for any net force, constant or variable.

Q: A 2 kg object at rest has a net force of 6 N applied over 3 m. What is its final speed?
A: $W_{net} = F \cdot d = 18$ J. By the work-energy theorem: $\frac{1}{2}mv_f^2 = 18$ J, so $v_f = \sqrt{2(18)/2} = \sqrt{18} \approx 4.24$ m/s.

## 7.5 Conservative Forces

Q: What distinguishes a conservative force from a non-conservative force?
A: A conservative force does work that depends only on the starting and ending positions, not the path taken. A round trip always yields zero net work: $\oint \vec{F}\cdot d\vec{r} = 0$. Examples: gravity, spring force, electrostatic force. Non-conservative forces (friction, drag) dissipate energy as heat and depend on path length.

C: Gravity and spring forces are [conservative]; friction and drag are [non-conservative], because the latter dissipate mechanical energy into heat along the path.

## 7.6 Gravitational Potential Energy

Q: Why can gravitational potential energy be defined at all?
A: Because gravity is a conservative force, the work it does is path-independent. This allows us to assign a scalar potential energy $U_g$ to each position so that $W_{gravity} = -\Delta U_g$. Non-conservative forces cannot be assigned a potential energy.

Q: What is the expression for gravitational potential energy near Earth's surface, and what determines the reference level?
A: $U_g = mgh$, where $m$ is mass (kg), $g = 9.8$ m/s², and $h$ is height above the chosen reference level (m). The reference level is arbitrary; only changes $\Delta U_g = mg\Delta h$ have physical meaning.

C: Work done by gravity equals $-\Delta U_g$, so as an object falls, gravitational PE [decreases] and kinetic energy [increases].

## 7.7 Elastic Potential Energy

Q: What is the elastic potential energy stored in a spring, and why is it always non-negative?
A: $U_e = \frac{1}{2}kx^2$, where $k$ is the spring constant (N/m) and $x$ is the displacement from equilibrium (m). It is always $\geq 0$ because $x^2 \geq 0$, whether the spring is compressed or stretched.

C: The work done by a spring force equals $-\Delta U_e = -(\frac{1}{2}kx_f^2 - \frac{1}{2}kx_i^2)$. When the spring returns to equilibrium ($x_f = 0$), it does [positive] work equal to $\frac{1}{2}kx_i^2$.

## 7.8 Conservation of Mechanical Energy

Q: State the law of conservation of mechanical energy and identify when it applies.
A: $E_{mech} = K + U = \text{constant}$ when only conservative forces do work on the system. Equivalently, $K_i + U_i = K_f + U_f$. It applies only when friction, drag, and other non-conservative forces are absent or do no work.

Q: How is conservation of mechanical energy modified when non-conservative forces act?
A: $\Delta E_{mech} = W_{nc}$, where $W_{nc}$ is the work done by non-conservative forces. Kinetic friction does negative work ($W_{nc} < 0$), so mechanical energy decreases; the lost energy becomes thermal energy.

C: When friction acts, $\Delta E_{mech} = W_{friction} < 0$, meaning mechanical energy [decreases] and is converted to [thermal energy].

## 7.9 Power

Q: What is power, and why is it useful in addition to work?
A: Power is the rate of doing work or transferring energy: $P = dW/dt$. Its unit is the watt (W = J/s). Work only measures total energy transferred; power measures how quickly. Two motors can do the same work, but a more powerful one does it faster.

Q: What is the instantaneous power delivered by a force $\vec{F}$ to a moving object?
A: $P = \vec{F}\cdot\vec{v}$, where $\vec{v}$ is the velocity of the object. This follows from $P = dW/dt = \vec{F}\cdot(d\vec{r}/dt) = \vec{F}\cdot\vec{v}$.

C: Average power is $\bar{P} = W/\Delta t$. One horsepower equals [746] W.

## 7.9a Pattern Recognition: Energy Methods

Q: A problem asks "find speed at point B given height/spring extension." What technique?
A: Energy conservation: $K_A + U_A = K_B + U_B$ (only if no friction). One unknown, one equation.

Q: A problem mentions friction or drag and asks for final speed/distance. What technique?
A: Work-energy theorem with non-conservative work: $\Delta K + \Delta U = W_{nc}$ (negative for friction).

Q: A problem says "find force exerted by surface on object" and gives kinematic info. Use energy or Newton's 2nd?
A: Energy methods don't yield force directly — use $\sum F = ma$. Reach for energy when speeds and heights are the unknowns.

## 7.10 Procedural: Energy Conservation with Friction

P: A 2 kg block slides from rest down a frictionless curved ramp of height $h = 5$ m, then onto a flat surface where $\mu_k = 0.4$. Use $g = 10$ m/s² to find: (a) the speed at the bottom of the ramp, and (b) how far the block slides on the flat before stopping.

S: **Identify:** Block starts at rest at height $h$. On ramp: only conservative forces (frictionless). On flat: kinetic friction acts. Find $v$ at bottom and stopping distance $d$.

**Plan:** (a) Apply conservation of mechanical energy on the ramp: $K_i + U_i = K_f + U_f$. (b) Apply work-energy theorem on the flat: $W_{friction} = \Delta K$.

**Execute:**
(a) $0 + mgh = \frac{1}{2}mv^2 + 0$
$v = \sqrt{2gh} = \sqrt{2(10)(5)} = \sqrt{100} = 10$ m/s.

(b) At the bottom: $K = \frac{1}{2}(2)(10)^2 = 100$ J.
Friction force: $f_k = \mu_k mg = (0.4)(2)(10) = 8$ N.
$W_{friction} = -f_k d = \Delta K = 0 - 100$ J.
$d = 100/8 = 12.5$ m.

**Evaluate:** Units check (J/N = m). The ramp height converts entirely to KE at the bottom. Friction dissipates all KE over 12.5 m. Larger $\mu_k$ would give shorter stopping distance — sensible.
