+++
order = 7
subject = "physics"
tags = ["mechanics", "physics", "energy", "work", "conservation"]
+++

# Classical Mechanics — Work and Energy

## 7.1 Work

<!-- card-id: card-d9365fd2-a000-42fc-a2ea-0dc73f32eba9 -->
<!-- card-alias: 933cda5f9bca24efadd63686da201eac809fe96ec9e05ac6ea23628acfb79a15 -->
Q: Why is work defined as a dot product rather than just $F \times d$?
A: Because only the component of force along the displacement does work. A force perpendicular to motion (e.g., normal force on a horizontal surface) causes no change in speed, so it should contribute zero work. The dot product automatically extracts the parallel component.

<!-- card-id: card-58cd6ed5-cf9f-40d7-9094-0d1a013621bd -->
<!-- card-alias: f4db9879e80c4394e417f02843521f04851fdc7f157d1361537229adb7b4fc3d -->
Q: What is the definition of work done by a constant force?
A: $W = \vec{F} \cdot \vec{d} = Fd\cos\theta$, where $F$ is the force magnitude (N), $d$ is the displacement magnitude (m), and $\theta$ is the angle between the force vector and the displacement vector. Work is a scalar. Its SI unit is the joule (J = N·m).

<!-- card-id: card-6117ebc4-b7ea-42af-9e11-4ceca19a5acb -->
<!-- card-alias: f6d199639732a9ad4902766e4ea46e5d0eff006cbae54c1e8ddcb01c7b56a95e -->
C: Work is [positive] when the force has a component along the direction of motion.

<!-- card-id: card-39c86a97-aa28-4e84-bcac-4175e5f0eb85 -->
<!-- card-alias: 6d55cd856fe5bb4c45cfd3d98b624803977f4fb909469eb723c2666d6f93353b -->
C: Work is [negative] when the force opposes the motion.

<!-- card-id: card-4f930364-982c-4abc-bea9-65f070f41a8b -->
<!-- card-alias: e5dc9b0241c5dea48c1f8389afd52859bf9fde852bdb45621c139d1ec8624f7b -->
C: Work is [zero] when the force is perpendicular to the displacement.

<!-- card-id: card-9c884476-b3a5-449e-9985-379e12afc1cb -->
<!-- card-alias: 460f9c9f7c8172deb9974b53e0fb3c3d2de9802e80a829e684a53d49e9cc223d -->
Q: A box is pushed 4 m along a floor by a 10 N force directed 60° above horizontal. How much work does the pushing force do?
A: $W = Fd\cos\theta = (10)(4)\cos 60° = 40 \times 0.5 = 20$ J.

## 7.2 Work by a Variable Force

<!-- card-id: card-752d1596-b7f4-4723-bc96-959a68744dd9 -->
<!-- card-alias: 3ae645bdcd892d6c8394544a19420f9bf6ebdba3a00771e8cee5a54d28be8b20 -->
Q: Why must an integral be used to compute work when force varies with position?
A: With a variable force, $F$ changes over each infinitesimal displacement $dx$, so work cannot be found by simple multiplication. Summing infinitesimal contributions gives $W = \int_{x_i}^{x_f} F(x)\,dx$, which equals the area under the $F$-vs-$x$ graph.

<!-- card-id: card-1476c60a-636c-4d70-982b-4576f1b544de -->
<!-- card-alias: 8e19162d51679793feaf5cbc94302b5e3421648d2ff42dd8a9ce1e13d7ccdf91 -->
C: The work done by a variable force equals the [area under the $F$-vs-$x$ graph] between the initial and final positions.

<!-- card-id: card-6d6c40d4-2f1a-4a54-9be8-06df5358c744 -->
<!-- card-alias: a7b3fffceebe89dc7d408d762964f8f9990fa528f57ed94eaa61e81b5853cf73 -->
Q: What is the work done by a spring when it is compressed or stretched?
A: $W_{spring} = \frac{1}{2}kx_i^2 - \frac{1}{2}kx_f^2$, where $k$ is the spring constant (N/m) and $x_i$, $x_f$ are the initial and final displacements from equilibrium. Equivalently, $W_{spring} = -\Delta U_e = -(\frac{1}{2}kx_f^2 - \frac{1}{2}kx_i^2)$.

## 7.3 Kinetic Energy

<!-- card-id: card-099e57b5-8312-44fc-9446-1c5f6be626a9 -->
<!-- card-alias: 572f7f0345cb909458cfad180822a531ddf57f2da421e69c4515f3dd3df1d366 -->
Q: Why is kinetic energy always non-negative?
A: $K = \frac{1}{2}mv^2$, where $m$ is mass (kg) and $v$ is speed (m/s). Both $m$ and $v^2$ are never negative, so $K \geq 0$. A stationary object has $K = 0$; kinetic energy reaches zero only when the object stops.

<!-- card-id: card-ccb79022-515c-4b88-8a94-895285428e34 -->
<!-- card-alias: 0ef11dee1207c9c04ede1fa312a95af2613ef79673954362d90347ba352d7aeb -->
C: Kinetic energy is $K = \frac{1}{2}mv^2$. Doubling an object's speed [quadruples] its kinetic energy, because $K \propto v^2$.

## 7.4 Work-Energy Theorem

<!-- card-id: card-3a52b713-6a17-4dcb-8d5a-a53d259e42dd -->
<!-- card-alias: 72bedca87328167d4e2179e79acc0d379de0242620ccc8c85e033137590ad0d9 -->
Q: How should the net work done on an object relate to its kinetic energy?
A: They should be equal — work has units of energy, and applying force over distance is precisely how speed (and thus $K$) is built up.

<!-- card-id: card-98f513a6-a5f6-4b43-a9dd-e808d28b2cfe -->
<!-- card-alias: ea26220797135e63126768ef7fc1e6638b36fbe4f3a1709308717df9607cecde -->
Q: State the work-energy theorem and explain its significance.
A: $W_{net} = \Delta K = K_f - K_i$. Net work on an object equals its change in kinetic energy. Holds for any net force, constant or variable.

<!-- card-id: card-a33d085b-1c4b-4f86-952e-5155a940fd29 -->
<!-- card-alias: f1b50740715d2aae2d94916ea148dd2b5d9d0d6f2970284e92cf400c3e18155c -->
Q: A 2 kg object at rest has a net force of 6 N applied over 3 m. What is its final speed?
A: $W_{net} = F \cdot d = 18$ J. By the work-energy theorem: $\frac{1}{2}mv_f^2 = 18$ J, so $v_f = \sqrt{2(18)/2} = \sqrt{18} \approx 4.24$ m/s.

## 7.5 Conservative Forces

<!-- card-id: card-cf72db1f-7137-476e-bf50-e69c7ae7dd42 -->
<!-- card-alias: 15a5e275193465af5b597a4cca62260aa17f7963124ed3e20494b647f36ae475 -->
Q: What distinguishes a conservative force from a non-conservative force?
A: A conservative force does work that depends only on the starting and ending positions, not the path taken. A round trip always yields zero net work: $\oint \vec{F}\cdot d\vec{r} = 0$. Examples: gravity, spring force, electrostatic force. Non-conservative forces (friction, drag) dissipate energy as heat and depend on path length.

<!-- card-id: card-92644ebd-055d-44b5-830c-37ee5f3c496d -->
<!-- card-alias: 46a236efea13a2afa1d99bae710b094583edad0afb601a4de079bd4e838c94e7 -->
<!-- card-alias: fb2061447290ce31ef6f8edfd379b0088f6bb1994b9c3b2a60b839a95479b99a -->
C: Gravity and spring forces are [conservative]; friction and drag are [non-conservative], because the latter dissipate mechanical energy into heat along the path.

## 7.6 Gravitational Potential Energy

<!-- card-id: card-579081c2-40d4-4d87-9101-9518564ac5fd -->
<!-- card-alias: 8b664df7749cf6bf3ca2627dafbd3f8bfe1e4b8d5dd5836a28c99005cf6fa5ed -->
Q: Why can gravitational potential energy be defined at all?
A: Because gravity is a conservative force, the work it does is path-independent. This allows us to assign a scalar potential energy $U_g$ to each position so that $W_{gravity} = -\Delta U_g$. Non-conservative forces cannot be assigned a potential energy.

<!-- card-id: card-a851b42a-814f-4591-b4c7-4b4748ba3a96 -->
<!-- card-alias: 52d619189f0e4191cef2b2ff02dbc13be3c6bcaa64f47be49708a15a6e708fd1 -->
Q: What is the expression for gravitational potential energy near Earth's surface, and what determines the reference level?
A: $U_g = mgh$, where $m$ is mass (kg), $g = 9.8$ m/s², and $h$ is height above the chosen reference level (m). The reference level is arbitrary; only changes $\Delta U_g = mg\Delta h$ have physical meaning.

<!-- card-id: card-9b47549d-a18b-477b-9703-362e81857010 -->
<!-- card-alias: 826d55a3e08a072d8d3094d2b8f5a95dd3a849a9eec73969b9807353e0b205de -->
<!-- card-alias: 41531213d548067ec99fe6a334bd297bd12a21bb4d7d8440ef2fa4b7903e10d9 -->
C: Work done by gravity equals $-\Delta U_g$. If gravity is the only force doing work, falling gravitational PE [decreases] while kinetic energy [increases].

## 7.7 Elastic Potential Energy

<!-- card-id: card-934bc9ff-df52-4e4c-85ee-6451d69aa140 -->
<!-- card-alias: 5adccf78a8544cb56856ba7e6b8deb5a815849f7f04f8aa64c24144ecb3be2b1 -->
Q: What is the elastic potential energy stored in a spring, and why is it always non-negative?
A: Choosing $U_e=0$ at the unstretched equilibrium, an ideal linear spring has $U_e=\frac12kx^2\geq0$. Compression and extension store the same energy at equal $|x|$.

<!-- card-id: card-58d9685c-9ff0-43fb-b94d-029ba697f900 -->
<!-- card-alias: 313870be53605c1e6d0d9db2e37c3c32e4fa04a81e7c13053b338e14ee04c984 -->
C: The work done by a spring force equals $-\Delta U_e = -(\frac{1}{2}kx_f^2 - \frac{1}{2}kx_i^2)$. When the spring returns to equilibrium ($x_f = 0$), it does [positive] work equal to $\frac{1}{2}kx_i^2$.

## 7.8 Conservation of Mechanical Energy

<!-- card-id: card-7b9c7feb-3144-4917-a54a-a33fa350f041 -->
<!-- card-alias: 3a07c5f2af74aca537d62ce0a88d71c9003b53648aacea8141dd869a7e34e765 -->
Q: State the law of conservation of mechanical energy and identify when it applies.
A: $E_{mech} = K + U = \text{constant}$ when only conservative forces do work on the system. Equivalently, $K_i + U_i = K_f + U_f$. It applies only when friction, drag, and other non-conservative forces are absent or do no work.

<!-- card-id: card-c7c347d2-8baa-489b-b843-614d986e04f0 -->
<!-- card-alias: fc0c5813e005bdd6b6e8499677507470559e42d185ddd18a8123d3c023c8c2e5 -->
Q: How is conservation of mechanical energy modified when non-conservative forces act?
A: With the system and potential energies defined, $\Delta E_{mech}=W_{nc}$. For a block sliding across a stationary rough surface, kinetic friction does negative work on the block and mechanical energy becomes thermal energy.

<!-- card-id: card-5de1d91d-dd48-4c74-8a98-81d055429c86 -->
<!-- card-alias: 557e79ac1473b95b86199cd8b349bcfe9b62c15be9f0baf8f890d375ba301439 -->
Q: Friction reduces mechanical energy. Does that violate conservation of energy?
A: No. Friction converts organized mechanical energy into internal/thermal energy. The total energy of a closed system remains conserved even though $K+U$ is not.

<!-- card-id: card-fff1fb7b-6338-4f3d-b97e-a93244476831 -->
<!-- card-alias: 7a55c22217b6f7d5c981a0389af0fa6e3c5268d7a2edb6bc35a54ee9f1099171 -->
<!-- card-alias: d2b4259e82dd851ef84cfc0dd2dc91badd45f908495a3145d28bf59e2217f6a0 -->
C: For a block sliding on a stationary rough surface, kinetic friction makes the block's mechanical energy [decrease] while thermal energy [increases].

## 7.9 Power

<!-- card-id: card-171abd77-8ef8-4590-9b00-94a12153818f -->
<!-- card-alias: b20a7392ad7aca891aa732447d579048d579b1f34c6187a13e2224420d928fd6 -->
Q: What is power, and why is it useful in addition to work?
A: Power is the rate of doing work or transferring energy: $P = dW/dt$. Its unit is the watt (W = J/s). Work only measures total energy transferred; power measures how quickly. Two motors can do the same work, but a more powerful one does it faster.

<!-- card-id: card-609a932e-5d8e-4758-8114-e72a8782c8c5 -->
<!-- card-alias: d8ba3be1bbbc459ace4f25cca34b961662a9f1cebac5ada89e0d22688917ace6 -->
Q: What is the instantaneous power delivered by a force $\vec{F}$ to a moving object?
A: $P = \vec{F}\cdot\vec{v}$, where $\vec{v}$ is the velocity of the object. This follows from $P = dW/dt = \vec{F}\cdot(d\vec{r}/dt) = \vec{F}\cdot\vec{v}$.

<!-- card-id: card-4d93f451-b604-41a0-8dd9-7144e992325d -->
<!-- card-alias: 4498ebb5dcdacf3deab707514b1228a949a9f1bea8586f1771743894ce966b30 -->
C: Average power is $\bar{P} = W/\Delta t$. One horsepower equals [746] W.

## 7.9a Pattern Recognition: Energy Methods

<!-- card-id: card-5de2faf0-2a4c-47b2-8918-594d052cea21 -->
<!-- card-alias: 1ede34f7aa84bb2da4e2dade1688a600079f3f5ceaff33201448a124d2fd23de -->
Q: A problem asks "find speed at point B given height/spring extension." What technique?
A: Energy conservation: $K_A + U_A = K_B + U_B$ (only if no friction). One unknown, one equation.

<!-- card-id: card-1104efc1-93ac-4196-92e9-73fdcb4b3c8f -->
<!-- card-alias: 4223bd00cd8337b2c6ddab5f920d5c6409471f048588e0502b49338fa07fd8cf -->
Q: A problem mentions friction or drag and asks for final speed/distance. What technique?
A: Use work–energy with non-conservative work, $\Delta K+\Delta U=W_{nc}$. Determine the sign from $\int\vec F\cdot d\vec r$ rather than assuming every friction force does negative work.

<!-- card-id: card-4cb4b1b7-5b3d-4e65-8cee-08c07bfbb5af -->
<!-- card-alias: ba818a471f1b1eb775130b55f4b1c0a2c41b6b2b61a7a7e49e635ee15f49195e -->
Q: A problem says "find force exerted by surface on object" and gives kinematic info. Use energy or Newton's 2nd?
A: Energy methods don't yield force directly — use $\sum F = ma$. Reach for energy when speeds and heights are the unknowns.

## 7.10 Procedural: Energy Conservation with Friction

<!-- card-id: card-48fccacb-e418-4a00-85dc-b540fa0b575d -->
<!-- card-alias: 7d9ab2ffff9b9cfb9075368563dbc54ba93e6a25e461ec7a986a6eeeb7a76936 -->
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
