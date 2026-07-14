+++
order = 12
subject = "physics"
tags = ["mechanics", "physics", "synthesis", "model-selection", "problem-solving"]
+++

# Classical Mechanics — Model Selection and Synthesis

## 12.1 Choosing the System and Model

<!-- card-id: card-0aab733d-7a75-4c7d-aa6e-3878842c5a30 -->
<!-- card-alias: 8955708958a84200923aee50441af2190a37cd8da2c00e28c50926e4327c477e -->
Q: Why should a mechanics solution define the system before choosing a conservation law?
A: The system boundary determines which interactions are internal and which transfer energy or momentum across the boundary. A quantity may be conserved for a larger system but not for one object inside it.

<!-- card-id: card-cbe009f6-4e7a-4834-8473-dcbd9c2b7ccf -->
<!-- card-alias: 2749e197747e670032135074fd0361f1efe10429fb81b0d07ca5b436756e4095 -->
Q: A question asks for acceleration at an instant and gives the forces acting then. Which framework is the direct choice, and why?
A: Draw a free-body diagram and use $\sum\vec F=m\vec a$. The requested acceleration is determined by the net force at that instant.

<!-- card-id: card-d76c6217-0b4e-4770-9ade-a37c5b80b97c -->
<!-- card-alias: 8b90ed7049ef78b9f4107fbdbac21a34c63d241b8a074eb10bd608430ba616b5 -->
Q: A question asks only for speed after a known displacement, while forces may vary with position. Which framework often avoids unnecessary work?
A: Use work–energy, $\Delta K=W_{net}$, or energy accounting with potential energy. It relates speed to displacement without first finding time or acceleration as a function of time.

<!-- card-id: card-2e5b09f5-95ee-4a63-adaa-693ec48e21a7 -->
<!-- card-alias: 6770edae1868527854875c44fd9dfebadaf1481e47ac37a1e2765ab32fd55246 -->
Q: A very short collision has large internal forces but negligible external impulse. Which quantity should organize the solution?
A: The total momentum of the chosen collision system is approximately conserved during the impact. Kinetic energy is conserved only if the collision is also elastic.

<!-- card-id: card-60dde531-2ee0-49fa-87c4-3101cca684e6 -->
<!-- card-alias: 90753bd87bba301d3b184df1c8c6f2d450e3201b9c0b8022c1a88994911d2cb5 -->
Q: Motion has known constant acceleration and the question connects position, velocity, and time. What model is sufficient?
A: Constant-acceleration kinematics. It describes the motion without explaining what forces produced the acceleration.

<!-- card-id: card-d0ce86cc-bcea-493f-b204-db65535d788b -->
<!-- card-alias: 93cde20f002f29586d08cf6d49b907d6429087765ffa94af2ca1180efdfaf3f4 -->
Q: A rigid body's angular speed changes because forces act away from an axis. What two steps connect those forces to the angular motion?
A: Compute each torque about the chosen axis, then use $\sum\tau=I\alpha$ when the body and fixed-axis assumptions make $I$ constant.

<!-- card-id: card-8a2f3388-ccc8-404b-afde-5af2e38a42c6 -->
<!-- card-alias: 531eafc25da7d9eed58d93a6788f043f2b6fb2cc50aa94c7a9d8a80063257a9e -->
Q: A system makes small oscillations about a stable equilibrium. How can its leading-order motion be tested for SHM?
A: Expand or approximate the restoring force near equilibrium. If $F\approx-k_{eff}x$ with $k_{eff}>0$, then $\omega=\sqrt{k_{eff}/m}$ for translational motion.

## 12.2 Discriminating Similar Ideas

<!-- card-id: card-ce35aa7c-9717-4bb3-9679-9467d40c6e03 -->
<!-- card-alias: 475104b05c6e2f73573ef141e25ae2402dfc9cf97d5e1be076319a99ce9198c8 -->
Q: When is Newton's second law more informative than energy conservation for the same motion?
A: Use Newton's law when forces, acceleration, direction, contact conditions, or time dependence are required. Energy is often shorter for endpoint speeds but does not by itself give force direction or elapsed time.

<!-- card-id: card-377ea325-ac70-431c-b76a-58f6e73eb85f -->
<!-- card-alias: c687050f1c8990b5e71185917e609965e0b2b21812909a9ae89ffba2b70988b6 -->
Q: During a collision, how do the conservation tests for momentum and kinetic energy differ?
A: Momentum is conserved when the net external impulse is negligible. Kinetic energy is conserved only for an elastic collision; in a closed-system account, an inelastic collision converts some of it to internal energy while total energy remains conserved.

<!-- card-id: card-9b5f37c5-316b-4ebf-b55e-6fe239fd3948 -->
<!-- card-alias: a754e17398e646db5d21d737eb9923510b0a756cdc2fabdae98fe007358e3f12 -->
Q: Does constant speed imply zero net force?
A: No. Constant speed fixes only the magnitude of velocity. Uniform circular motion has constant speed but an inward net force that continuously changes the velocity's direction.

<!-- card-id: card-a4f0c729-bfbe-46ce-b066-ebc001e4300b -->
<!-- card-alias: 92ee78bbeb2436f5e5d78456d9692cd8df28f055975246276cf23caf7f29569d -->
Q: Is “centripetal force” an additional force to draw on a free-body diagram?
A: No. It is the name for the inward component of the net real force, $\sum F_r=mv^2/r$. Identify which real forces—such as tension, gravity, or friction—produce that net component.

<!-- card-id: card-dc3a9c37-66d9-4abc-b61c-d154bf77ef7a -->
<!-- card-alias: cdacb97ee50aac9deefb9a971d4027eb4e17e3e9ccb510f0291b07a84ed4f152 -->
Q: A student sets the normal force equal to $mg$ in every contact problem. What condition did they fail to check?
A: They must apply the force equation perpendicular to the surface. $N=mg$ only in special geometries with no other perpendicular force components and no perpendicular acceleration.

<!-- card-id: card-238e4839-44cc-4ff0-b845-f152d43a8152 -->
<!-- card-alias: 0b9f8b2c2f557a7233428c834b6e7c7869243e069ac21c699ce71560da88d8bd -->
Q: What is the difference between translational equilibrium and static equilibrium for a rigid body?
A: Translational equilibrium requires $\sum\vec F=0$. Static equilibrium also requires $\sum\vec\tau=0$ and zero initial motion, so the body neither translates nor rotates.

<!-- card-id: card-dc771a0e-92f6-456b-b683-60483a5ed4fe -->
<!-- card-alias: 0e7beef326c696d76257ff605233c76d73efacba6caf5b7689fb5ac31c4093c9 -->
Q: Why is dimensional consistency necessary but not sufficient evidence that a mechanics result is correct?
A: A wrong equation can still have matching units. After checking dimensions, also test sign, direction, scale, limiting cases, and any relevant conservation law.

<!-- card-id: card-f6cad108-db1a-4b74-8af4-20dc25a08c09 -->
<!-- card-alias: 87af23bcf5c970d5590ab20d26b2d4fe16206fef308864dccbad7e4c9c840fb6 -->
Q: How does a limiting-case check expose a faulty symbolic answer?
A: Set a parameter to a physically simple extreme—such as friction $\mu\to0$, mass ratio $m/M\to0$, or radius $r\to\infty$. The formula should reduce to the known behavior of that simpler system.

## 12.3 Translating Representations

<!-- card-id: card-75758d79-048f-4aec-8b8e-6075d69e1c99 -->
<!-- card-alias: 8e088d56463090bf26fddf7486eb5093b9373f3bef9dc5cd6dca8b8561c4330e -->
Q: On a velocity-versus-time graph, what do the slope and signed area represent?
A: The slope is acceleration, and the signed area over a time interval is displacement. Distance requires accounting for the magnitude of velocity rather than simply using signed area.

<!-- card-id: card-68b68120-7186-462d-9cb6-16a59fd1e715 -->
<!-- card-alias: afd42b85aaabc6b7a5d8b8d0976d3d9524ec5ff8cd7e6e3d339978f5e220367d -->
Q: On a force-versus-position graph, what does the signed area represent?
A: The work done by that force, $W=\int F_x\,dx$. An area below the position axis is negative work for motion in the positive direction.

<!-- card-id: card-818d4c9c-0e31-4fd5-87ac-31929cd02409 -->
<!-- card-alias: 59fb0cb72bbd70cb2f13023a98c7053ec2c7e69d53616c27ddd9b87479952c84 -->
Q: What does the curvature of a position-versus-time graph reveal before any calculation?
A: Concave up means positive acceleration and concave down means negative acceleration, for the chosen positive axis. The graph's slope gives velocity, so curvature describes how that slope changes.

<!-- card-id: card-3d043ee7-5128-40dc-b998-fc9c8933d148 -->
<!-- card-alias: 6c45e3b67c6041ac7bd5d4de48dec9b62dc0eaaf812074e9ea1978c2de0aba78 -->
Q: A symbolic result for a speed contains a negative quantity under a square root. What should be concluded first?
A: The assumed motion is impossible under the stated parameters or an earlier sign/model choice is wrong. Do not discard the sign merely to force a numerical answer.

## 12.4 Mixed Physical Situations

<!-- card-id: card-c9cd0d43-d278-4644-a46e-3b66bd0ca6ed -->
<!-- card-alias: c8a2d96e16f716645bb71e0f7d49024e37da874e2ce63fc8c9cbaa32ccc20e16 -->
Q: A projectile embeds in a hanging block, and the combined object then swings upward. Why must the motion be split into two models?
A: During the brief inelastic collision, momentum is approximately conserved but mechanical energy is not. During the later swing, mechanical energy is conserved if pivot friction and air drag are negligible.

<!-- card-id: card-6bb60878-f26c-477e-b1c5-c259532199f3 -->
<!-- card-alias: 734d3154645fbd8c4a6ebf2d2ce84ee59b941b3a92942bdbcb32a9b15aa6c996 -->
Q: A block slides down a rough incline and only its speed after distance $d$ is requested. What are two valid approaches, and which is usually shorter?
A: Newton's law along the incline followed by kinematics is valid if acceleration is constant; work–energy with friction is usually shorter because it connects the endpoints directly.

<!-- card-id: card-ef8fe428-4241-49b7-8b60-3dd6b6e79ec0 -->
<!-- card-alias: 87ab8c0c606ce16177b6436ffb7755b8930a44e34e54ff177acd74331aec7dec -->
Q: A rolling object descends without slipping. Why are energy conservation and the rolling constraint both needed to find its speed?
A: Energy must include translational and rotational kinetic energy, while $v_{cm}=R\omega$ connects the two unknown speeds. The constraint is kinematic; it does not mean friction dissipates energy.

<!-- card-id: card-60b63d69-ff48-498b-a7ea-eed19c1ec179 -->
<!-- card-alias: 0ed944454440691a5b10b4e83f093caa818ba4a7e1fc24ec1f0172f0226af871 -->
Q: In a circular satellite orbit, how do force and energy descriptions complement each other?
A: Gravity supplying $mv^2/r$ determines $v=\sqrt{GM/r}$. Substituting that speed into $K+U$ gives the bound-orbit energy $E=-GMm/(2r)$.

<!-- card-id: card-7574de0d-0bee-4f8a-a653-33da8857c1fe -->
<!-- card-alias: aaccb340cadb965963ad0eac996ba43a3b544020f790276dd3be9be9ca6f5d5a -->
Q: Two blocks are connected by an ideal taut string over a massless frictionless pulley. What constraint and force fact couple their equations?
A: The blocks have equal acceleration magnitudes along the string, and the tension has the same magnitude on both sides. Their acceleration directions are opposite along a single signed coordinate around the string.

## 12.5 Faded Integrative Problems

<!-- card-id: card-346cfc42-9109-46c0-9b33-48650b1ae6f9 -->
<!-- card-alias: b3257e8853a470705fc60230e8fb508e73433e9169be55187955c7167654bc80 -->
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

<!-- card-id: card-99dc1b08-19a7-4f96-b915-e48ecd6b3ddf -->
<!-- card-alias: c678608f2b7918fff3729fc534bb9418e0ca7fbf133290fde42aeaa219787698 -->
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
