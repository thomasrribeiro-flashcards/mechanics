+++
order = 8
subject = "physics"
tags = ["mechanics", "physics", "momentum", "impulse", "collisions"]
+++

# Classical Mechanics — Momentum and Collisions

## 8.1 Linear Momentum

<!-- card-id: card-74f7cf87-6d5d-461f-bd67-4d2877e1a455 -->
<!-- card-alias: d891c3eca8c30e8ef3527456c49f3761ae89ff4b80d249545773709a51ed7335 -->
Q: Why is momentum especially useful for collisions compared with kinetic energy?
A: Momentum is a vector and is conserved for an isolated system in every collision. Kinetic energy is conserved only in elastic collisions, so it cannot generally determine an inelastic collision by itself.

<!-- card-id: card-c7f50117-e533-42c1-a51a-2e0ab645741c -->
<!-- card-alias: 5e484d47efb66698ce38cfe04f99f5b7ebdb9593c7b75fb72666badd76272942 -->
Q: What is the definition of linear momentum?
A: $\vec{p} = m\vec{v}$, where $m$ is the mass (kg) and $\vec{v}$ is the velocity (m/s). Momentum is a vector in the same direction as $\vec{v}$. Its SI unit is kg·m/s. A larger mass or higher speed produces greater momentum.

<!-- card-id: card-5e89d550-a357-4def-a1ea-7e3dbf95485b -->
<!-- card-alias: 22641a2762f136e76fb29e78c882df6c652b196c8c47b2ddea2a16b966d6e27d -->
<!-- card-alias: e0789af8c9be466a16bb92685e652bacd9305649c694ba3ddddd292c4f44d275 -->
C: Linear momentum $\vec{p} = m\vec{v}$ is a [vector] quantity with SI unit [kg·m/s], always pointing in the same direction as the velocity.

## 8.2 Newton's Second Law via Momentum

<!-- card-id: card-b8d15911-2d32-4733-ab3f-1e1cf86690c3 -->
<!-- card-alias: 7dc4fce654d2fe711baaf74bfd840536d6ad100525a1b0be9d86b75a761d93ee -->
Q: For what system is $\vec F_{ext}=d\vec p/dt$ directly valid, and why do rockets require extra care?
A: It applies directly to a fixed set of particles, reducing to $m\vec a$ when its mass is constant. A rocket is an open system: expelled fuel carries momentum across the chosen boundary, so a momentum-flux term must be included rather than blindly differentiating $m\vec v$ for the remaining rocket.

<!-- card-id: card-f29cab9f-136f-41be-ba3f-5147adf953a1 -->
<!-- card-alias: b928b1914cf0a561eabcc439602317b35a4b3b81ccc7bca22727b8afb2fd5ec7 -->
C: For a fixed set of particles, $\vec{F}_{ext}=d\vec p/dt$ reduces to $\vec{F}_{ext}=m\vec a$ when [mass is constant].

## 8.3 Impulse

<!-- card-id: card-08cf83f7-6b78-43c4-bc4a-29c453ed6f28 -->
<!-- card-alias: 1f088d3954366cdafedc05bf7531b60558062e02ba4bd43b35c3e58f57a905bc -->
Q: What is impulse, and how does it relate to momentum?
A: Impulse is $\vec{J} = \int_{t_1}^{t_2}\vec{F}\,dt$. The impulse-momentum theorem states $\vec{J} = \Delta\vec{p} = \vec{p}_f - \vec{p}_i$. For a constant force: $\vec{J} = \vec{F}\Delta t$. Unit: N·s = kg·m/s. Impulse is a vector.

<!-- card-id: card-77d6b07c-820f-4812-af5f-80cfb776759d -->
<!-- card-alias: 078ba87a2bb8f304976940231a22717153c26693778e6b20e246274fa6f6b773 -->
Q: Why do airbags and padded helmets reduce injury, using the concept of impulse?
A: The change in momentum $\Delta\vec{p}$ (and therefore the impulse) is fixed by the crash. Airbags increase the collision time $\Delta t$, and since $F_{avg} = \Delta p / \Delta t$, a longer $\Delta t$ produces a smaller average force on the occupant, reducing injury.

<!-- card-id: card-5549119c-bbcf-4acf-bb49-e6561d0d865a -->
<!-- card-alias: 53be1324e1c8b2586eba475868241d454e603cba4fd52d30cf562ccfbf0b08a2 -->
<!-- card-alias: 62e5277b0ecfc3247df54d38b3d65722704342878723a90e746c7b10f1179ab4 -->
C: Impulse equals [change in momentum]: $\vec{J} = \Delta\vec{p}$. Extending the collision time [decreases] the average force for a given impulse.

## 8.4 Conservation of Linear Momentum

<!-- card-id: card-c97bd10a-3dc8-42ba-b9af-4dd7eb058317 -->
<!-- card-alias: c94fe4364999f30a268f7e85daf2999b0bf29dff3013c00ce642d67aca9de12b -->
Q: State the law of conservation of linear momentum and identify when it holds.
A: A system's momentum change equals its net external impulse. Thus $\vec p_{total}$ is conserved over an interval when the net external impulse is zero or negligible; this can hold component by component.

<!-- card-id: card-eb74fcb9-f6e2-482d-9424-5b1c988a5e10 -->
<!-- card-alias: e4de7065d3d679e6a24d6bf2beef53f4b5e9f3a6fdd95b84ef0853789d1cd6b3 -->
Q: Why is momentum often approximately conserved during a brief collision even when external forces such as weight exist?
A: The collision time is so short that the external impulse is often negligible compared with the exchanged internal impulses. Including all colliding objects makes the internal impulse pairs cancel in the system's total momentum balance.

<!-- card-id: card-fd056757-2df6-4270-8b08-af41e28554a4 -->
<!-- card-alias: 13988b0fa152498fe24ce7004fb35cf0acee29a78cfca762f3ffc6c473593146 -->
<!-- card-alias: 302b3136450e1ee00a4885b307ccb01a7afe8309c0a015712c828c6f376214ed -->
C: Conservation of momentum over a collision requires negligible [net external impulse]. Internal collision forces [cancel] in Newton's third-law pairs when the whole interacting system is included.

## 8.5 Types of Collisions

<!-- card-id: card-dc6b649b-289b-45de-8c67-c70f85527419 -->
<!-- card-alias: 2e35ff7153e08e355becad99e487ed64669d97846e9c5a69eb2ce03f511d04c3 -->
Q: What is conserved in an elastic collision?
A: Both momentum and kinetic energy.

<!-- card-id: card-688d5d50-0bfc-4ff1-9e3d-39deb439bdb9 -->
<!-- card-alias: 458752fda64d95559e11061a2f3fd30c194bd2b2dc2fc8355e556869563c8384 -->
Q: What is conserved in an inelastic collision?
A: For an isolated system, momentum is conserved but kinetic energy is not generally conserved. Total energy is still conserved; some kinetic energy becomes deformation, internal energy, or sound.

<!-- card-id: card-0a0ab3b6-ba09-41a8-9945-d4bf6b5407e1 -->
<!-- card-alias: c1bc0cb661e699a196134aa0b8e08e0151df90411d0a4ba4c61e6b2474e0265d -->
Q: What defines a perfectly inelastic collision?
A: Objects stick together with a common final velocity; maximum KE loss consistent with momentum conservation.

<!-- card-id: card-9bd22d96-a59c-4a72-94e0-a3749939ab60 -->
<!-- card-alias: 856a6865ce6e5210f91c072d2d9bb606564a83708b201cbbbfc907a60f4b9ff9 -->
<!-- card-alias: 1dd0e900b7ac7379516578c5fe2ce6187eb24c3fd206dc5a543b875102a834b4 -->
C: In an elastic collision both [momentum] and [kinetic energy] are conserved.

<!-- card-id: card-306510f0-01fa-4529-b986-60f6fe079871 -->
<!-- card-alias: c356b479339cb4ab15f8bca1f966367418ebb0041e1837914dc526365a2cde85 -->
C: In any collision, [momentum] is conserved as long as there is no net external force.

## 8.6 Perfectly Inelastic Collision

<!-- card-id: card-f4839da0-459a-4ee4-9571-67fc51f50ef4 -->
<!-- card-alias: 8b5ceb4a8dcc3070abab4489d417c76daff919d05c8f73711ff8eb1b2bd3a626 -->
Q: Write the equation for a perfectly inelastic collision and explain what happens to kinetic energy.
A: Objects combine after impact: $m_1v_1 + m_2v_2 = (m_1 + m_2)v_f$, where $v_1$, $v_2$ are initial velocities (signed) and $v_f$ is the common final velocity. KE lost $= K_i - K_f > 0$; the lost kinetic energy converts to heat, sound, and deformation.

<!-- card-id: card-38be776a-668d-4559-b244-fa9ad60dd138 -->
<!-- card-alias: b5bbd062fc578958acea59b41ab8a067c5c7d54c9495b324b08aacf2d04edb9a -->
Q: Two objects of equal mass $m$ undergo a perfectly inelastic collision. Object 1 moves at $v$; object 2 is stationary. What is the final speed and what fraction of kinetic energy is lost?
A: $v_f = mv/(2m) = v/2$. $K_i = \frac{1}{2}mv^2$. $K_f = \frac{1}{2}(2m)(v/2)^2 = \frac{1}{4}mv^2$. KE lost $= \frac{1}{2}mv^2 - \frac{1}{4}mv^2 = \frac{1}{4}mv^2$. Fraction lost $= 50\%$.

<!-- card-id: card-a32717cc-3262-4199-819e-d2821aeaf37d -->
<!-- card-alias: 760186c9a491ee2ba9c263b5e9e083cb8bd0f48e688a38db5e8ccd2999d7f231 -->
<!-- card-alias: e5d7faf67360e5a4dbc707ec4e014428daf7e105043f3908432c35002a7e55db -->
C: In a perfectly inelastic collision the two objects [stick together] and move with a [common final velocity], with maximum kinetic energy loss.

## 8.7 Elastic Collision in 1D (Target at Rest)

<!-- card-id: card-0670b330-3bb8-41f8-be2a-2bbaad2dab7b -->
<!-- card-alias: d2f4ac7b82a637ce3bbd1b966ca5891cb99bf36e2b2227fe35e2ce8d3220bcb1 -->
Q: What are the final velocities in a 1D elastic collision when the target is initially at rest?
A: $v_1' = \dfrac{m_1 - m_2}{m_1 + m_2}v_1$ and $v_2' = \dfrac{2m_1}{m_1 + m_2}v_1$, where $v_1$ is the initial speed of the projectile (mass $m_1$) and the target (mass $m_2$) is at rest. Derived by simultaneously solving conservation of momentum and conservation of kinetic energy.

<!-- card-id: card-6c4950f6-a430-43e8-aca3-d0966351fe0a -->
<!-- card-alias: e0afa6f1b795553c6e3666aa7f71ad8051c080a43ad7972b6d2fce176ed9b01e -->
Q: In a 1D elastic collision with an equal-mass target initially at rest, what happens?
A: The velocities exchange: the projectile stops and the target leaves with the projectile's initial velocity.

<!-- card-id: card-2549fa2c-8965-4981-a10a-1c4a5dee524f -->
<!-- card-alias: a50b90177e8fd6ea01d44b539ba38c2417ffe821fc217dd398b3f49700b82f14 -->
Q: In a 1D elastic collision with a stationary target much lighter than the projectile, what happens approximately?
A: The heavy projectile continues at nearly its original velocity, while the light target leaves at nearly twice that velocity.

<!-- card-id: card-fed2d64e-aefe-4078-a6ac-2b3d21ae7153 -->
<!-- card-alias: 47db82b0a307a4c18319524dd546ee7a22361a5923476efc34f6bbee4487b025 -->
Q: In a 1D elastic collision with a stationary target much heavier than the projectile, what happens approximately?
A: The light projectile reverses with nearly its original speed, while the heavy target barely moves.

<!-- card-id: card-c960e7d8-0538-49b0-b1ac-c1e46a6aa195 -->
<!-- card-alias: b88793632ca02ed32a866ed84134792662befcfc07fa02104af3b03dd79f6a33 -->
<!-- card-alias: 61364a4675bf3fe3180f868a05811898db3d0cc673223414b0dcecba909d388d -->
C: When two equal masses collide elastically (target at rest), the projectile [stops] and the target moves away at the [original speed of the projectile].

## 8.8 Center of Mass

<!-- card-id: card-0b2cd689-2978-4d81-b9e5-e8274fc42d91 -->
<!-- card-alias: a3432b0dc068b268e9690d5a8e84cb108de9035050e0b74a7c3723681fbf907e -->
Q: What is the center of mass (CM) of a system, and why does it matter dynamically?
A: $\vec{r}_{cm} = \dfrac{\sum m_i\vec{r}_i}{\sum m_i}$, the mass-weighted average position. It matters because the CM of a system obeys $\vec{F}_{ext} = M\vec{a}_{cm}$ (Newton's 2nd for a system), where $M = \sum m_i$. External forces determine the CM motion; internal forces (collisions, explosions) cannot change $\vec{a}_{cm}$.

<!-- card-id: card-056a9e8d-807e-4182-b265-d8d8b23ae049 -->
<!-- card-alias: 89b1d54cf7724b4a6a867ec0e2d6b1834713a64d533be43971d9e5add900216b -->
Q: What is the velocity of the center of mass, and how does it behave when no external force acts?
A: $\vec{v}_{cm} = \dfrac{\sum m_i\vec{v}_i}{M} = \dfrac{\vec{p}_{total}}{M}$. When $\vec{F}_{ext} = 0$, $\vec{v}_{cm}$ is constant — the CM moves at constant velocity (or stays at rest) regardless of internal explosions or collisions.

<!-- card-id: card-33f25bba-b33b-4b7c-a66e-8bd80c101b9a -->
<!-- card-alias: 52c8747b5150cf4b9fd355f8173b0315d9c464313879602f402cdf29d1425500 -->
<!-- card-alias: 1299f905431a2935628b647435959bfa35225f96a44bd6f9b83ef2650ccaa2b6 -->
C: In an isolated system (no external forces), the center of mass moves at [constant velocity]. Internal forces like collisions and explosions [cannot] change the velocity of the center of mass.

<!-- card-id: card-10f96a02-62bc-449b-8406-6c4bc7760a8e -->
<!-- card-alias: 938548c754be13650073e690c54cd98f622f95bb562139b9d7a1876eb6e65a20 -->
Q: How do you apply momentum conservation to a two-dimensional collision?
A: Choose axes and conserve momentum separately: $\sum p_{x,i}=\sum p_{x,f}$ and $\sum p_{y,i}=\sum p_{y,f}$, provided the external impulse is negligible in those directions.

## 8.8a Pattern Recognition: Collisions

<!-- card-id: card-496e3922-24ab-45be-8539-16f71a20b29f -->
<!-- card-alias: 322adc8d961a2963a7aa7fb9b7d99f7b6c8c8cc6c1406673f29336a2a82f72d7 -->
Q: A problem says "two objects collide and stick together." What technique?
A: Momentum conservation only ($v_f = (m_1 v_1 + m_2 v_2)/(m_1+m_2)$). KE is NOT conserved — don't try energy conservation.

<!-- card-id: card-50c0ebd3-0c7e-4318-829c-d8997eba707c -->
<!-- card-alias: adcd4a0d23ed638d35b2f8e155c5b332f2ccb605c8b45e82efe8355a7e80f738 -->
Q: A problem says "elastic collision, target at rest." What technique?
A: Use the special-case formulas $v_1' = \frac{m_1-m_2}{m_1+m_2}v_1$ and $v_2' = \frac{2m_1}{m_1+m_2}v_1$ — derived from solving momentum + KE conservation simultaneously.

<!-- card-id: card-8a8929ee-5ce4-4d4b-931c-f789ec6d3acc -->
<!-- card-alias: aac2dfe2bcd91c6bd9635fc59a45bb1d60e268596d92c6a6b6c40d806671e287 -->
Q: A problem describes an explosion (one object splits into pieces). What technique?
A: Momentum conservation. Total $\vec{p}_{before} = 0$ (if at rest), so the pieces' momenta must sum to zero.

## 8.9 Procedural: Perfectly Inelastic Collision Energy Analysis

<!-- card-id: card-580ca423-f8c1-4cd2-8406-ab2490efac0e -->
<!-- card-alias: 7ffe4be4f5cf09444d5c269bec543f5735ae2dc0086af2116ebb4399f0dbc526 -->
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
