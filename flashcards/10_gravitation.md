+++
order = 10
subject = "Physics"
tags = ["mechanics", "physics", "gravitation", "orbits", "Kepler"]
+++

# Classical Mechanics — Gravitation

## 10.1 Newton's Law of Universal Gravitation

Q: Why is gravity called an "inverse-square law," and what is its physical implication?
A: The gravitational force $F_g \propto 1/r^2$: doubling the distance between two masses reduces the force by a factor of 4; tripling the distance reduces it by a factor of 9. This means gravity weakens rapidly with distance but never reaches zero — it is infinite in range.

Q: State Newton's law of universal gravitation.
A: $F_g = G\dfrac{m_1 m_2}{r^2}$, where $G = 6.674\times10^{-11}$ N·m²/kg² is the gravitational constant, $m_1$ and $m_2$ are the two masses (kg), and $r$ is the distance between their centers (m). The force is always attractive and acts along the line joining the centers.

C: In Newton's law of gravitation, $F_g = Gm_1m_2/r^2$, doubling the separation $r$ reduces the gravitational force by a factor of [4], because $F_g \propto \lbrack 1/r^2\rbrack $.

## 10.2 Deriving $g$ from $G$

Q: How is the surface gravitational acceleration $g$ derived from Newton's law of universal gravitation?
A: Set gravitational force equal to $mg$: $mg = G\dfrac{Mm}{R^2}$, so $g = \dfrac{GM}{R^2}$. For Earth: $M_E = 5.97\times10^{24}$ kg, $R_E = 6.37\times10^6$ m, giving $g \approx 9.8$ m/s². This shows $g$ is a local approximation valid only near Earth's surface.

Q: How does gravitational acceleration change with altitude above Earth's surface?
A: $g(h) = \dfrac{GM_E}{(R_E + h)^2}$, where $h$ is the altitude above the surface. As $h$ increases, $g$ decreases. At altitude $h = R_E$ (one Earth radius up), $g$ is reduced to one-quarter of its surface value.

C: Gravitational acceleration at altitude $h$ is $g(h) = GM_E/(R_E+h)^2$. At $h = R_E$, the value of $g$ decreases to [$g/4$] compared to the surface value.

## 10.3 Gravitational Potential Energy (General Form)

Q: Why is the general gravitational potential energy $U_g = -Gm_1m_2/r$ negative, and what does that signify?
A: The reference is chosen at $r = \infty$ where $U_g = 0$. Moving masses closer releases energy (gravity does positive work), so $U_g$ must decrease below zero as $r$ decreases. A negative $U_g$ means the system is gravitationally bound — energy must be added to separate the masses to infinity.

Q: How does the general form $U_g = -Gm_1m_2/r$ reduce to the familiar $U_g = mgh$ near Earth's surface?
A: For $h \ll R_E$: $U_g(R_E + h) - U_g(R_E) = -\dfrac{GMm}{R_E+h} + \dfrac{GMm}{R_E} \approx \dfrac{GMm}{R_E^2}h = mgh$, using the approximation $(1 + h/R_E)^{-1} \approx 1 - h/R_E$. The linear approximation is valid because $R_E \approx 6400$ km $\gg h$ for everyday altitudes.

C: The general gravitational PE is $U_g = -Gm_1m_2/r$. This is [negative] for all finite $r$, and approaches [zero] as $r \to \infty$.

## 10.4 Escape Velocity

Q: Derive the escape velocity from the surface of a body of mass $M$ and radius $R$.
A: Set total energy to zero (minimum energy to just reach $r = \infty$ with zero speed): $K + U = 0$, so $\frac{1}{2}mv_{esc}^2 - \dfrac{GMm}{R} = 0$. Solving: $v_{esc} = \sqrt{\dfrac{2GM}{R}}$. The $m$ of the escaping object cancels, so escape velocity is independent of the projectile's mass.

C: Escape velocity is $v_{esc} = \sqrt{2GM/R}$. It is [independent] of the mass of the escaping object. For Earth, $v_{esc} \approx \lbrack 11.2\rbrack $ km/s.

## 10.5 Circular Orbits

Q: How is the orbital speed of a circular orbit determined?
A: Gravity provides the centripetal force: $\dfrac{GMm}{r^2} = \dfrac{mv^2}{r}$. Solving (the orbiting mass $m$ cancels): $v_{orb} = \sqrt{\dfrac{GM}{r}}$, where $r$ is the orbital radius. A higher orbit has a lower orbital speed — counterintuitively, going "up" means going slower.

Q: Derive the orbital period $T$ of a circular orbit at radius $r$.
A: $T = \dfrac{2\pi r}{v_{orb}} = \dfrac{2\pi r}{\sqrt{GM/r}} = 2\pi\sqrt{\dfrac{r^3}{GM}}$, where $G$ is the gravitational constant, $M$ is the central body's mass, and $r$ is the orbital radius.

C: The orbital speed in a circular orbit is $v = \sqrt{GM/r}$. Increasing $r$ [decreases] the orbital speed and [increases] the orbital period.

## 10.6 Orbital Energy

Q: What is the total mechanical energy of a circular orbit of radius $r$?
A: $E = K + U = \dfrac{1}{2}mv^2 - \dfrac{GMm}{r} = \dfrac{GMm}{2r} - \dfrac{GMm}{r} = -\dfrac{GMm}{2r}$. The total energy is negative (bound orbit), equal to half the potential energy in magnitude, and half of $U$ in sign.

Q: What does the sign of the total orbital energy $E$ indicate?
A: $E < 0$: bound orbit (ellipse or circle). $E = 0$: parabolic trajectory (escaping with zero final speed). $E > 0$: hyperbolic trajectory (escaping with leftover kinetic energy). Moving to a higher orbit requires adding energy (making $E$ less negative).

C: The total energy of a circular orbit is $E = -GMm/(2r)$. This is [negative], indicating a [bound] orbit. Raising the orbit (increasing $r$) [increases] the total energy (makes it less negative).

## 10.7 Kepler's First Law

Q: State Kepler's first law and define the key geometric features of an ellipse.
A: Kepler's First Law: every planet orbits the Sun in an ellipse with the Sun at one focus. An ellipse has two foci, semi-major axis $a$ (half the long axis), and eccentricity $e$ ($0 \leq e < 1$). The point closest to the Sun is the perihelion; the farthest is the aphelion. A circle is a special case with $e = 0$.

C: Kepler's First Law: planets orbit in [ellipses] with the Sun at one [focus]. The closest orbital point to the Sun is called [perihelion].

## 10.8 Kepler's Second Law

Q: State Kepler's second law and identify its physical origin.
A: A line drawn from the Sun to a planet sweeps out equal areas in equal time intervals. Physical origin: gravity is a central force (directed along $\vec{r}$ toward the Sun), so it exerts no torque on the planet, meaning angular momentum $L = $ constant. Conservation of $L$ forces the planet to speed up when closer to the Sun.

Q: Using Kepler's second law, compare the planet's speed at perihelion versus aphelion.
A: The planet moves fastest at perihelion (closest to Sun) and slowest at aphelion (farthest). At both points velocity is perpendicular to $\vec{r}$, so $L = mv_p r_p = mv_a r_a$, giving $v_p/v_a = r_a/r_p > 1$.

C: Kepler's Second Law is a consequence of conservation of [angular momentum]. The planet moves [fastest] at perihelion and [slowest] at aphelion.

## 10.9 Kepler's Third Law

Q: State Kepler's third law and give its modern (Newtonian) form.
A: $T^2 = \dfrac{4\pi^2}{GM}a^3$, where $T$ is the orbital period (s), $a$ is the semi-major axis (m), $G$ is the gravitational constant, and $M$ is the mass of the central body (kg). This gives $T^2 \propto a^3$.

Q: How can Kepler's third law be used to determine the mass of a planet or star?
A: Observe the orbital period $T$ and semi-major axis $a$ of a natural or artificial satellite, then solve $M = \dfrac{4\pi^2 a^3}{GT^2}$. This is how planetary masses, the Sun's mass, and masses of distant stars in binary systems are determined.

C: Kepler's Third Law states $T^2 \propto \lbrack a^3\rbrack $. It can be used to calculate the [mass] of the central body from the period and semi-major axis of any orbiting object.

## 10.9a Pattern Recognition: Gravitation

Q: A problem says "find escape speed from planet X." What technique?
A: $v_{esc} = \sqrt{2GM/R}$ — derived from $K + U = 0$ (just barely reaches infinity).

Q: A problem says "satellite at altitude $h$, find orbital period." What technique?
A: $T = 2\pi\sqrt{r^3/(GM)}$ where $r = R + h$ (Kepler's third in Newtonian form).

Q: A problem gives perihelion/aphelion distances and asks about speed ratios. What technique?
A: Angular momentum conservation: $v_p r_p = v_a r_a$ (Kepler's second).

Q: A problem asks "how does $g$ change at altitude $h$?" What technique?
A: $g(h) = GM/(R+h)^2$. Use binomial expansion if $h \ll R$.

## 10.10 Worked Example — ISS Orbital Parameters

P: The International Space Station orbits Earth at an altitude $h = 400$ km. Using $G = 6.67\times10^{-11}$ N·m²/kg², $M_E = 5.97\times10^{24}$ kg, and $R_E = 6.37\times10^6$ m, find: (a) the orbital radius, (b) the orbital speed, (c) the orbital period in minutes.

S:
**IDENTIFY**: Circular orbit around Earth. Gravity supplies the centripetal force. Given altitude $h$, find orbital radius $r$, speed $v$, and period $T$.

**PLAN**:
- Orbital radius: $r = R_E + h$
- Orbital speed: $v = \sqrt{GM_E/r}$ (from equating $GM_Em/r^2 = mv^2/r$)
- Orbital period: $T = 2\pi r/v$

**EXECUTE**:

(a) $r = R_E + h = 6.37\times10^6 + 4.00\times10^5 = 6.77\times10^6$ m

(b) First compute $GM_E$:
$$GM_E = (6.67\times10^{-11})(5.97\times10^{24}) = 3.98\times10^{14} \text{ m}^3/\text{s}^2$$

$$v = \sqrt{\frac{GM_E}{r}} = \sqrt{\frac{3.98\times10^{14}}{6.77\times10^6}} = \sqrt{5.88\times10^7} \approx 7670 \text{ m/s} \approx 7.67 \text{ km/s}$$

(c) $T = \dfrac{2\pi r}{v} = \dfrac{2\pi(6.77\times10^6)}{7670} \approx 5545$ s $\approx 92.4$ min

**EVALUATE**:
- ISS orbital speed is known to be $\approx 7.7$ km/s ✓
- ISS period is known to be $\approx 90$ min (16 orbits per day) ✓
- Units: $[GM/r] = (\text{m}^3/\text{s}^2)/\text{m} = \text{m}^2/\text{s}^2$, so $\sqrt{\cdot}$ has units m/s ✓
- The orbit is only 6% higher than Earth's radius, so $v$ is close to surface-level circular speed $\sqrt{gR_E} \approx 7.9$ km/s ✓
