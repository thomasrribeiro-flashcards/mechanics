+++
order = 10
subject = "physics"
tags = ["mechanics", "physics", "gravitation", "orbits", "kepler"]
+++

# Classical Mechanics — Gravitation

## 10.1 Newton's Law of Universal Gravitation

<!-- card-id: card-69627d55-620e-4a29-8051-e46575a5b7da -->
<!-- card-alias: 8dd7229301e80fa2000bf22e110ae8889376200700eb95df562013fb7df86e9c -->
Q: Why is gravity called an "inverse-square law," and what is its physical implication?
A: The gravitational force $F_g \propto 1/r^2$: doubling the distance between two masses reduces the force by a factor of 4; tripling the distance reduces it by a factor of 9. This means gravity weakens rapidly with distance but never reaches zero — it is infinite in range.

<!-- card-id: card-8ddfae11-a3e3-4125-8c19-1d037d17e318 -->
<!-- card-alias: a8d6e90a2f4b464637de79bd5d69b390a0875077958f0470e9aa7733a3c28070 -->
Q: State Newton's law of universal gravitation.
A: For point masses—or spherically symmetric bodies that do not overlap—$F_g=Gm_1m_2/r^2$, where $r$ is their center-to-center separation. The force is attractive and acts along the line joining their centers.

<!-- card-id: card-ff517d9b-1f55-4fd1-ae59-6979c2045cdc -->
<!-- card-alias: d4a546f96c9d4b1692dd6c3201e7206f53e0a33c82275958a780a0bdb372e389 -->
C: In Newton's law of gravitation, $F_g = Gm_1m_2/r^2$, doubling the separation $r$ reduces the gravitational force by a factor of [4], because $F_g \propto \lbrack 1/r^2\rbrack $.

## 10.2 Deriving $g$ from $G$

<!-- card-id: card-c26ab510-94a6-4f1f-98a4-45d81636dab2 -->
<!-- card-alias: dc228d02d2c48647b75daef4ef455a4ad11857a2e5772be0d5fade0c8d53118a -->
Q: How is the surface gravitational acceleration $g$ derived from Newton's law of universal gravitation?
A: Outside a spherically symmetric body, set $mg=GMm/R^2$ at its surface, giving $g=GM/R^2$. Treating this value and direction as constant is the near-surface approximation; the inverse-square field itself is not limited to the surface.

<!-- card-id: card-c1338e75-0784-4c1b-a0f5-ca8f00668a8e -->
<!-- card-alias: 4ee3fcf221fdc7abb77b1a266d6c19294ed48a4415febc7cab9782ed3345554b -->
Q: What is the distinction between gravitational field strength and the gravitational force on an object?
A: The field produced by a spherical mass is $\vec g=-GM\hat r/r^2$, independent of a test object. A test mass $m$ placed there experiences $\vec F_g=m\vec g$.

<!-- card-id: card-83dc4dcd-d9f6-4e11-8ead-f3946df7fb5e -->
<!-- card-alias: 59468646c963f9f959c9fe6dd71ceb9ea70b726cd2b35bd3206aa151aa134f99 -->
Q: How does gravitational acceleration change with altitude above Earth's surface?
A: $g(h) = \dfrac{GM_E}{(R_E + h)^2}$, where $h$ is the altitude above the surface. As $h$ increases, $g$ decreases. At altitude $h = R_E$ (one Earth radius up), $g$ is reduced to one-quarter of its surface value.

<!-- card-id: card-63edce15-1b89-46cc-8bab-f9ebffe71911 -->
<!-- card-alias: c85fb6f71b0a846eb18bb70efb2991e5501246490a00c8a9ac1d310b29f367cc -->
C: Gravitational acceleration at altitude $h$ is $g(h) = GM_E/(R_E+h)^2$. At $h = R_E$, the value of $g$ decreases to [$g/4$] compared to the surface value.

## 10.3 Gravitational Potential Energy (General Form)

<!-- card-id: card-43bdeb16-a0ae-4e20-b253-596d5d8faf2e -->
<!-- card-alias: a7619532fe5b94c12192a8e6b449b918f2d14c5268f6ae0d8cea7070c46fc5b9 -->
Q: Why is the general gravitational potential energy $U_g = -Gm_1m_2/r$ negative, and what does that signify?
A: The reference is chosen at $r=\infty$, where $U_g=0$. Moving the masses closer lets gravity do positive work, so $U_g$ decreases below zero. Negative potential energy alone does not prove the motion is bound; binding is determined by the total energy $E=K+U$.

<!-- card-id: card-3c5533b0-6afe-445d-ab6f-90754a7be9a0 -->
<!-- card-alias: a1e10784852c98f22dfaf166ebc8dc606254721d5f0f23e645e00213acfd336c -->
Q: How does the general form $U_g = -Gm_1m_2/r$ reduce to the familiar $U_g = mgh$ near Earth's surface?
A: For $h \ll R_E$: $U_g(R_E + h) - U_g(R_E) = -\dfrac{GMm}{R_E+h} + \dfrac{GMm}{R_E} \approx \dfrac{GMm}{R_E^2}h = mgh$, using the approximation $(1 + h/R_E)^{-1} \approx 1 - h/R_E$. The linear approximation is valid because $R_E \approx 6400$ km $\gg h$ for everyday altitudes.

<!-- card-id: card-fc691c35-5684-4e3c-8a69-485d5f379cb7 -->
<!-- card-alias: 846835ced759e25b1db6e7886eee906fadcb085a4a2cd909f770c2131cff4f0d -->
<!-- card-alias: 977269c4a28f061650fb3909177d4ae720d4924b2c42aba5e27bb1aac9297ca7 -->
C: The general gravitational PE is $U_g = -Gm_1m_2/r$. This is [negative] for all finite $r$, and approaches [zero] as $r \to \infty$.

## 10.4 Escape Velocity

<!-- card-id: card-bd62e238-1b8b-4673-bbf0-439d8413183d -->
<!-- card-alias: 477fdaaca932ed7c2d6dd6340f3e55c8fcccea104018af3b1d1aea4582ddd599 -->
Q: Derive the escape velocity from the surface of a body of mass $M$ and radius $R$.
A: With no atmosphere, no further propulsion, and a nonrotating spherical body, set total energy to zero: $\frac12mv_{esc}^2-GMm/R=0$. Thus $v_{esc}=\sqrt{2GM/R}$; the escaping mass cancels.

<!-- card-id: card-c1825225-7284-4dd5-b359-052125a91e4c -->
<!-- card-alias: 6e137d0ee1406f7829d7fd02d991b0a39081e369fe6e4890fddcbf25a7af4062 -->
C: Escape velocity is $v_{esc} = \sqrt{2GM/R}$. It is [independent] of the mass of the escaping object. For Earth, $v_{esc} \approx \lbrack 11.2\rbrack $ km/s.

## 10.5 Circular Orbits

<!-- card-id: card-6c380614-2cf9-4fec-8192-7dd639169474 -->
<!-- card-alias: 1ae034e107fc285b478c4b7daf70ef0ff6df2475e4e87dc963672eae4146495a -->
Q: How is the orbital speed of a circular orbit determined?
A: For an orbiting mass negligible relative to the spherical central mass $M$, gravity supplies the centripetal force: $GMm/r^2=mv^2/r$. Thus $v_{orb}=\sqrt{GM/r}$; a larger circular orbit has lower orbital speed.

<!-- card-id: card-a803ab39-3621-4373-8530-0947c4fa9c41 -->
<!-- card-alias: 16835467041e3759ab0457f460dff9a2ff3d4a7d75fd4de6eeef027f720a0612 -->
Q: Derive the orbital period $T$ of a circular orbit at radius $r$.
A: $T = \dfrac{2\pi r}{v_{orb}} = \dfrac{2\pi r}{\sqrt{GM/r}} = 2\pi\sqrt{\dfrac{r^3}{GM}}$, where $G$ is the gravitational constant, $M$ is the central body's mass, and $r$ is the orbital radius.

<!-- card-id: card-1c01354a-5568-465c-984c-b2d1e38f479c -->
<!-- card-alias: 9f6a1c442ab1e1a485bb54a8cc51ea6e8c0d5b598ef2ee9cfcaa7aaa0b6ae8b7 -->
<!-- card-alias: 90e64a85bd9b369a260bbe3c5c06ea5cfd36de903771ea1728a886a3f932483d -->
C: The orbital speed in a circular orbit is $v = \sqrt{GM/r}$. Increasing $r$ [decreases] the orbital speed and [increases] the orbital period.

## 10.6 Orbital Energy

<!-- card-id: card-27a87c61-760d-4292-bfd5-2f205054045f -->
<!-- card-alias: 19b62d4657ad00eef557564af9a9fdc9eb8d0dd0ef7a400043b6ea3d9b2339fb -->
Q: What is the total mechanical energy of a circular orbit of radius $r$?
A: $E=K+U=GMm/(2r)-GMm/r=-GMm/(2r)$. Thus $E=U/2=-K$: the total energy is negative and the circular orbit is bound.

<!-- card-id: card-2aa97ec6-e199-4a04-9cd7-2969a10848a5 -->
<!-- card-alias: 524512731333d903ab2393798719bb7a9c3c3e215b1463378400eb6176542dee -->
Q: What does the sign of the total orbital energy $E$ indicate?
A: $E < 0$: bound orbit (ellipse or circle). $E = 0$: parabolic trajectory (escaping with zero final speed). $E > 0$: hyperbolic trajectory (escaping with leftover kinetic energy). Moving to a higher orbit requires adding energy (making $E$ less negative).

<!-- card-id: card-901864b4-1982-4a43-942d-e34892388dc7 -->
<!-- card-alias: 269ae7ccfa4c5ef14a4ca72664327e899fec6a556b82b66eef9ede18cb11c580 -->
<!-- card-alias: 34e7ff325c8d0d7792dd2c31ee8b227bd1c818449ccab85b25c7714cfb87723f -->
C: The total energy of a circular orbit is $E = -GMm/(2r)$. This is [negative], indicating a [bound] orbit.

<!-- card-id: card-d20c07d1-6e92-44d3-acf4-debdcb9862e9 -->
<!-- card-alias: 91f33c5c93b78263fd9e3222689dc8f22f2b6796d1c6d8ae1507a6edb1ba1444 -->
C: For a circular orbit with total energy $E = -GMm/(2r)$, raising the orbit (increasing $r$) [increases] the total energy (makes it less negative).

## 10.7 Kepler's First Law

<!-- card-id: card-9bf6a78d-752e-4cbe-ba4b-456abe09f47f -->
<!-- card-alias: c5b263f274adacf84e2d859dc6b87a1fc0e9be8731438735bc2fe3a2ccd87288 -->
Q: State Kepler's first law and define the key geometric features of an ellipse.
A: Kepler's First Law: every planet orbits the Sun in an ellipse with the Sun at one focus. An ellipse has two foci, semi-major axis $a$ (half the long axis), and eccentricity $e$ ($0 \leq e < 1$). The point closest to the Sun is the perihelion; the farthest is the aphelion. A circle is a special case with $e = 0$.

<!-- card-id: card-1c78f870-f392-45c8-aa9f-026ef9e9dc12 -->
<!-- card-alias: c7b9e1570091dbcc853d8ce46d9c368ac1ba96ab787f7dd00a3aea06ebd36be4 -->
<!-- card-alias: de47ec9ea53cedfab8bf9d8804b2653bcc049d32595be570c3acee0acc4b8497 -->
C: Kepler's First Law: planets orbit in [ellipses] with the Sun at one [focus].

<!-- card-id: card-1c63d311-d619-454d-a4c1-89792eec75cf -->
<!-- card-alias: 4d2aa862752df692b0716be25d459891092d4475ca9ca0206916ecb2bbc24629 -->
C: In an elliptical orbit, the orbital point closest to the Sun is called [perihelion].

## 10.8 Kepler's Second Law

<!-- card-id: card-d7f9ecdc-cd66-4dc1-b1bd-9779d25ba11f -->
<!-- card-alias: f3f9c54004d40b855aa5fa337341e1eac7dfe8dd29bb7478defa7f6b0261ef0f -->
Q: State Kepler's second law and identify its physical origin.
A: A line drawn from the Sun to a planet sweeps out equal areas in equal time intervals. Physical origin: gravity is a central force (directed along $\vec{r}$ toward the Sun), so it exerts no torque on the planet, meaning angular momentum $L = $ constant. Conservation of $L$ forces the planet to speed up when closer to the Sun.

<!-- card-id: card-bf6100a6-bc1a-419f-8ceb-b0f1ab9c89f4 -->
<!-- card-alias: 8f89ea7f3649c96864ff7af2401be9ca5845caba9a03dc4c2e94d74edf460309 -->
Q: Using Kepler's second law, compare the planet's speed at perihelion versus aphelion.
A: The planet moves fastest at perihelion (closest to Sun) and slowest at aphelion (farthest). At both points velocity is perpendicular to $\vec{r}$, so $L = mv_p r_p = mv_a r_a$, giving $v_p/v_a = r_a/r_p > 1$.

<!-- card-id: card-a11d7da2-c347-4ec8-b1ba-3c0f6ae5eb46 -->
<!-- card-alias: 609e9b517eab1ea2e000f6015133affd30ea03bc3bf83d83657a68d979b44caf -->
C: Kepler's Second Law is a consequence of conservation of [angular momentum].

<!-- card-id: card-0922d86d-7933-423f-8e86-944ab62226ea -->
<!-- card-alias: d01d2c587188b3a03006d5944d493184eae7ecf4e0a58758d55564e459577446 -->
<!-- card-alias: 6858a0fdd49a7fa53ce85d7100bc2e8f6e64124880e307aef39a970ff843fca8 -->
C: By Kepler's Second Law, a planet moves [fastest] at perihelion and [slowest] at aphelion.

## 10.9 Kepler's Third Law

<!-- card-id: card-f9bd5302-1b04-4e57-8cb8-0bec5e8dd270 -->
<!-- card-alias: dd0b0b0c501eff7461b3bfa8dea8aa9fe90fe3570755e8e5243beb616c502a9d -->
Q: State Kepler's third law and give its modern (Newtonian) form.
A: For two masses $M$ and $m$, $T^2=4\pi^2a^3/[G(M+m)]$, where $a$ is the semi-major axis of their relative orbit. If $M\gg m$, this reduces to $T^2\approx4\pi^2a^3/(GM)$.

<!-- card-id: card-81deee11-0884-4ab5-b08f-553cf9b81c70 -->
<!-- card-alias: c62c55818fa1669713e385dc4d4f6702d82b6651e471cd2f104b4ebe96d67d50 -->
Q: How can Kepler's third law be used to determine the mass of a planet or star?
A: Measuring the relative orbit's $T$ and $a$ gives the system's total mass $M+m=4\pi^2a^3/(GT^2)$. When the satellite mass is negligible, this is approximately the central body's mass.

<!-- card-id: card-822ee1e4-35dc-449a-843e-144d89ddc53d -->
<!-- card-alias: 5b050cafa4e8b55ae4b7eee34360ecb88824f85d1043957dd67d197710f06657 -->
C: Kepler's Third Law states $T^2 \propto \lbrack a^3\rbrack $. The measured period and relative semi-major axis determine the system's [total mass].

## 10.9a Pattern Recognition: Gravitation

<!-- card-id: card-15d4e6ad-6614-43dd-883d-1ed9ffbc0978 -->
<!-- card-alias: cdcecf5298a2192251508c20dc5b9b32dd3c271ac7c269ccd977bb08ecbf812c -->
Q: A problem says "find escape speed from planet X." What technique?
A: $v_{esc} = \sqrt{2GM/R}$ — derived from $K + U = 0$ (just barely reaches infinity).

<!-- card-id: card-dd917a74-5608-404c-bb87-24509e57f6d9 -->
<!-- card-alias: 920a4e5119cd7a58cfd4e9add65a416ff45c347428fefcdce445a94e22b3078b -->
Q: A problem says "satellite at altitude $h$, find orbital period." What technique?
A: $T = 2\pi\sqrt{r^3/(GM)}$ where $r = R + h$ (Kepler's third in Newtonian form).

<!-- card-id: card-f4de4cc1-26da-4a29-9b79-5635cf0f003b -->
<!-- card-alias: 30eff78d5a8ec25322e1fb5e5b457ef2f27bc1df03a352cf506cfc4704f343a8 -->
Q: A problem gives perihelion/aphelion distances and asks about speed ratios. What technique?
A: Angular momentum conservation: $v_p r_p = v_a r_a$ (Kepler's second).

<!-- card-id: card-17e02785-ff18-4d36-aca0-1cfe5fe79fd7 -->
<!-- card-alias: 2b0056af1ae85c3acd04506f10b9d2105412c66a20ceb80ee3ac64f7e5e0c069 -->
Q: A problem asks "how does $g$ change at altitude $h$?" What technique?
A: $g(h) = GM/(R+h)^2$. Use binomial expansion if $h \ll R$.

## 10.10 Worked Example — ISS Orbital Parameters

<!-- card-id: card-9d5a102d-961a-4cb2-b2d7-a993e270326a -->
<!-- card-alias: d8dcf745ab174ee74e82c4a60fb9f081e5576b9991d73ad1f51fb004bc2defe2 -->
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
