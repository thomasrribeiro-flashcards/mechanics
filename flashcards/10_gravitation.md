+++
order = 10
subject = "physics"
tags = ["mechanics", "physics", "gravitation", "orbits", "kepler"]
+++

# Classical Mechanics — Gravitation

## 10.1 Newton's Law of Universal Gravitation

Q: Why is gravity called an "inverse-square law," and what is its physical implication?
A: The gravitational force $F_g \propto 1/r^2$: doubling the distance between two masses reduces the force by a factor of 4; tripling the distance reduces it by a factor of 9. This means gravity weakens rapidly with distance but never reaches zero — it is infinite in range.

Q: State Newton's law of universal gravitation.
A: For point masses—or spherically symmetric bodies that do not overlap—$F_g=Gm_1m_2/r^2$, where $r$ is their center-to-center separation. The force is attractive and acts along the line joining their centers.

C: In Newton's law of gravitation, $F_g = Gm_1m_2/r^2$, doubling the separation $r$ reduces the gravitational force by a factor of [4], because $F_g \propto \lbrack 1/r^2\rbrack $.

## 10.2 Deriving $g$ from $G$

Q: How is the surface gravitational acceleration $g$ derived from Newton's law of universal gravitation?
A: Outside a spherically symmetric body, set $mg=GMm/R^2$ at its surface, giving $g=GM/R^2$. Treating this value and direction as constant is the near-surface approximation; the inverse-square field itself is not limited to the surface.

Q: What is the distinction between gravitational field strength and the gravitational force on an object?
A: The field produced by a spherical mass is $\vec g=-GM\hat r/r^2$, independent of a test object. A test mass $m$ placed there experiences $\vec F_g=m\vec g$.

Q: How does gravitational acceleration change with altitude above Earth's surface?
A: $g(h) = \dfrac{GM_E}{(R_E + h)^2}$, where $h$ is the altitude above the surface. As $h$ increases, $g$ decreases. At altitude $h = R_E$ (one Earth radius up), $g$ is reduced to one-quarter of its surface value.

C: Gravitational acceleration at altitude $h$ is $g(h) = GM_E/(R_E+h)^2$. At $h = R_E$, the value of $g$ decreases to [$g/4$] compared to the surface value.

## 10.3 Gravitational Potential Energy (General Form)

Q: Why is the general gravitational potential energy $U_g = -Gm_1m_2/r$ negative, and what does that signify?
A: The reference is chosen at $r=\infty$, where $U_g=0$. Moving the masses closer lets gravity do positive work, so $U_g$ decreases below zero. Negative potential energy alone does not prove the motion is bound; binding is determined by the total energy $E=K+U$.

Q: How does the general form $U_g = -Gm_1m_2/r$ reduce to the familiar $U_g = mgh$ near Earth's surface?
A: For $h \ll R_E$: $U_g(R_E + h) - U_g(R_E) = -\dfrac{GMm}{R_E+h} + \dfrac{GMm}{R_E} \approx \dfrac{GMm}{R_E^2}h = mgh$, using the approximation $(1 + h/R_E)^{-1} \approx 1 - h/R_E$. The linear approximation is valid because $R_E \approx 6400$ km $\gg h$ for everyday altitudes.

C: The general gravitational PE is $U_g = -Gm_1m_2/r$. This is [negative] for all finite $r$, and approaches [zero] as $r \to \infty$.

## 10.4 Escape Velocity

Q: Derive the escape velocity from the surface of a body of mass $M$ and radius $R$.
A: With no atmosphere, no further propulsion, and a nonrotating spherical body, set total energy to zero: $\frac12mv_{esc}^2-GMm/R=0$. Thus $v_{esc}=\sqrt{2GM/R}$; the escaping mass cancels.

C: Escape velocity is $v_{esc} = \sqrt{2GM/R}$. It is [independent] of the mass of the escaping object. For Earth, $v_{esc} \approx \lbrack 11.2\rbrack $ km/s.

## 10.5 Circular Orbits

Q: How is the orbital speed of a circular orbit determined?
A: For an orbiting mass negligible relative to the spherical central mass $M$, gravity supplies the centripetal force: $GMm/r^2=mv^2/r$. Thus $v_{orb}=\sqrt{GM/r}$; a larger circular orbit has lower orbital speed.

Q: Derive the orbital period $T$ of a circular orbit at radius $r$.
A: $T = \dfrac{2\pi r}{v_{orb}} = \dfrac{2\pi r}{\sqrt{GM/r}} = 2\pi\sqrt{\dfrac{r^3}{GM}}$, where $G$ is the gravitational constant, $M$ is the central body's mass, and $r$ is the orbital radius.

C: The orbital speed in a circular orbit is $v = \sqrt{GM/r}$. Increasing $r$ [decreases] the orbital speed and [increases] the orbital period.

## 10.6 Orbital Energy

Q: What is the total mechanical energy of a circular orbit of radius $r$?
A: $E=K+U=GMm/(2r)-GMm/r=-GMm/(2r)$. Thus $E=U/2=-K$: the total energy is negative and the circular orbit is bound.

Q: What does the sign of the total orbital energy $E$ indicate?
A: $E < 0$: bound orbit (ellipse or circle). $E = 0$: parabolic trajectory (escaping with zero final speed). $E > 0$: hyperbolic trajectory (escaping with leftover kinetic energy). Moving to a higher orbit requires adding energy (making $E$ less negative).

C: The total energy of a circular orbit is $E = -GMm/(2r)$. This is [negative], indicating a [bound] orbit.

C: For a circular orbit with total energy $E = -GMm/(2r)$, raising the orbit (increasing $r$) [increases] the total energy (makes it less negative).

## 10.7 Kepler's First Law

Q: State Kepler's first law and define the key geometric features of an ellipse.
A: Kepler's First Law: every planet orbits the Sun in an ellipse with the Sun at one focus. An ellipse has two foci, semi-major axis $a$ (half the long axis), and eccentricity $e$ ($0 \leq e < 1$). The point closest to the Sun is the perihelion; the farthest is the aphelion. A circle is a special case with $e = 0$.

C: Kepler's First Law: planets orbit in [ellipses] with the Sun at one [focus].

C: In an elliptical orbit, the orbital point closest to the Sun is called [perihelion].

## 10.8 Kepler's Second Law

Q: State Kepler's second law and identify its physical origin.
A: A line drawn from the Sun to a planet sweeps out equal areas in equal time intervals. Physical origin: gravity is a central force (directed along $\vec{r}$ toward the Sun), so it exerts no torque on the planet, meaning angular momentum $L = $ constant. Conservation of $L$ forces the planet to speed up when closer to the Sun.

Q: Using Kepler's second law, compare the planet's speed at perihelion versus aphelion.
A: The planet moves fastest at perihelion (closest to Sun) and slowest at aphelion (farthest). At both points velocity is perpendicular to $\vec{r}$, so $L = mv_p r_p = mv_a r_a$, giving $v_p/v_a = r_a/r_p > 1$.

C: Kepler's Second Law is a consequence of conservation of [angular momentum].

C: By Kepler's Second Law, a planet moves [fastest] at perihelion and [slowest] at aphelion.

## 10.9 Kepler's Third Law

Q: State Kepler's third law and give its modern (Newtonian) form.
A: For two masses $M$ and $m$, $T^2=4\pi^2a^3/[G(M+m)]$, where $a$ is the semi-major axis of their relative orbit. If $M\gg m$, this reduces to $T^2\approx4\pi^2a^3/(GM)$.

Q: How can Kepler's third law be used to determine the mass of a planet or star?
A: Measuring the relative orbit's $T$ and $a$ gives the system's total mass $M+m=4\pi^2a^3/(GT^2)$. When the satellite mass is negligible, this is approximately the central body's mass.

C: Kepler's Third Law states $T^2 \propto \lbrack a^3\rbrack $. The measured period and relative semi-major axis determine the system's [total mass].

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
