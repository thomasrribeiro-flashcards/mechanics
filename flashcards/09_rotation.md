+++
order = 9
subject = "physics"
tags = ["mechanics", "physics", "rotation", "torque", "angular-momentum"]
+++

# Classical Mechanics — Rotational Motion

## 9.1 Angular Position and Displacement

<!-- card-id: card-9b48e0dd-cdf7-4803-9516-bc6a83b6a47a -->
<!-- card-alias: 3e1a1bc444924dcaa4349fa923cdab525362f04add3b3a49c3bc91ca222dc2c6 -->
Q: Why are radians the natural unit for angle in physics rather than degrees?
A: Radians make the arc-length formula dimensionally clean: $s = r\theta$, where $s$ is arc length (m), $r$ is radius (m), and $\theta$ is in radians (dimensionless ratio). Using degrees would require a conversion factor everywhere, cluttering equations. Radians also appear naturally in derivatives of trigonometric functions.

<!-- card-id: card-a12a9bd9-5383-46a9-ab09-5b4062f52e9b -->
<!-- card-alias: 0bae5e0f27ded87c7e00aaceb01230f3167557c629aade092cd3ac8efc5ade84 -->
Q: Define angular position, angular displacement, and the sign convention for rotation.
A: Angular position $\theta$ is measured in radians from a reference direction. Angular displacement $\Delta\theta = \theta_f - \theta_i$. By convention, counterclockwise (CCW) is positive and clockwise (CW) is negative. Full circle: $2\pi$ rad $= 360°$.

<!-- card-id: card-a45c1f22-a02f-4406-8b1a-485879d9b840 -->
<!-- card-alias: 608a892ef06afc23448ea49d602f3508397a4f5db45c823467622dd2e4722192 -->
<!-- card-alias: 6b4de274c2aa0ac35948770c54ba74a05ecdea7048b0061671a7bec92471f3cf -->
C: Arc length and angle are related by $s = r\theta$, where $s$ is arc length (m), $r$ is radius (m), and $\theta$ is in [radians]. One full revolution equals [$2\pi$] radians.

## 9.2 Angular Velocity and Acceleration

<!-- card-id: card-3b2b6eb8-e4c7-435c-807d-696e489644bd -->
<!-- card-alias: ec30475e60e8e29c82a0ab43f4fc1806e9105ef8581b1a6b23bb0cbee0fb9a19 -->
Q: Define angular velocity $\omega$ and angular acceleration $\alpha$, and state their SI units.
A: Angular velocity: $\omega = d\theta/dt$ (rad/s). Angular acceleration: $\alpha = d\omega/dt$ (rad/s²). Both are signed scalars for rotation about a fixed axis (positive = CCW, negative = CW).

<!-- card-id: card-e8af0abf-a517-4d3c-b0c2-f88f19470b48 -->
<!-- card-alias: 36d08b9abf616e8862720bc885b9ad2f1ca912ea7d768d64f7e14ab4a9393413 -->
Q: What are the linear-angular kinematic relationships for a point on a rotating body?
A: For a point at radius $r$ from the axis: tangential speed $v_t = r\omega$; tangential acceleration $a_t = r\alpha$; centripetal acceleration $a_c = r\omega^2 = v_t^2/r$. The total linear acceleration is $a = \sqrt{a_t^2 + a_c^2}$.

<!-- card-id: card-8fcdfffc-ba8c-4874-ba39-bee1b74d6482 -->
<!-- card-alias: 7e5c50506d268161553376e65f79a5c9ac5d0c1b1d9e31f07c925a806c835642 -->
<!-- card-alias: 183de2d655e00b931caf6ce998e35eef2dc7d7373bd8e7eafee602c4e688b232 -->
C: For a point at radius $r$ from the rotation axis, the tangential relationships are $v_t = r[\omega]$ and $a_t = r[\alpha]$.

<!-- card-id: card-fddaf71c-4313-4078-8182-0e12db1b3028 -->
<!-- card-alias: f01fa05dfc7d7a9080e80e294a45efb660e6ad6a25a92ab6062ce14258784cb9 -->
<!-- card-alias: c64eed5d84dc5edc996bf8f4491f6bef4ee83a9f408dddbce69f29f08fd284da -->
C: For a point moving in a circle at radius $r$, the inward centripetal acceleration is $a_c = [r\omega^2] = [v_t^2/r]$.

## 9.3 Angular Kinematic Equations

<!-- card-id: card-0bfa5010-b92b-49ca-a848-2e1e7b281948 -->
<!-- card-alias: aca85366f7c6e3c1f679768b1c0be968ab407118dd82995b7ea5b4595130a212 -->
Q: Write the three angular kinematic equations for constant $\alpha$ and state the translational analogues for each.
A: (1) $\omega = \omega_0 + \alpha t$ (analogous to $v = v_0 + at$). (2) $\theta = \theta_0 + \omega_0 t + \frac{1}{2}\alpha t^2$ (analogous to $x = x_0 + v_0 t + \frac{1}{2}at^2$). (3) $\omega^2 = \omega_0^2 + 2\alpha\Delta\theta$ (analogous to $v^2 = v_0^2 + 2a\Delta x$). Valid only when $\alpha$ is constant.

<!-- card-id: card-6e9f6bc4-a183-4eeb-8e4e-1119287d2059 -->
<!-- card-alias: 0533b4b7861086ac4634ad44ec3bf1e33d09fdcc2486627f956da1c3f4630f8a -->
C: The constant-angular-acceleration equations follow from the 1D kinematic equations under the substitutions [$x \to \theta$, $v \to \omega$, and $a \to \alpha$].

## 9.4 Torque

<!-- card-id: card-e7aee36d-a807-4820-8aa0-1717afe51646 -->
<!-- card-alias: 908cf16649ab9a9876243e489741402e1b426c497785461715dd0424431f3519 -->
Q: Why is torque defined using the perpendicular distance (moment arm) rather than the direct distance to the force?
A: Only the component of force perpendicular to the position vector $\vec{r}$ causes rotation. A force directed exactly along $\vec{r}$ (radially) produces no rotation, so its torque should be zero. The cross product $\vec{\tau} = \vec{r} \times \vec{F}$ with magnitude $\tau = rF\sin\phi$ automatically gives zero when force is radial ($\phi = 0$).

<!-- card-id: card-36f0b242-802e-4d80-a61a-b2aac22affa6 -->
<!-- card-alias: 67802454890d2fefda81912d23c17b2e2ec2a87ff8a3f950843126f037d445bb -->
Q: State the three equivalent expressions for the magnitude of torque.
A: $\tau = rF\sin\phi = r_\perp F = rF_\perp$, where $r$ is the distance from the pivot to the point of force application (m), $F$ is the force magnitude (N), $\phi$ is the angle between $\vec{r}$ and $\vec{F}$, $r_\perp = r\sin\phi$ is the perpendicular (moment arm) distance, and $F_\perp = F\sin\phi$ is the perpendicular component of force. Unit: N·m.

<!-- card-id: card-17800f85-2d61-44fa-aab5-c4a59d401c2b -->
<!-- card-alias: 2405751022e3a2cd6f308da2a409a56a5bf7d14599c1d3f877637c81362f967e -->
C: From $\tau = rF\sin\phi$, the torque magnitude is [zero] when the force is parallel or antiparallel to $\vec r$.

<!-- card-id: card-526afe99-87f0-423b-9693-d6aceb3c7b7c -->
<!-- card-alias: 43de029a7cf7dc776e94493c8c7286cf3e6b483ff2cc5849ffe15aef6c088269 -->
C: For fixed $r$ and $F$, $\tau = rF\sin\phi$ is [maximum] when the force is perpendicular to $\vec r$.

## 9.5 Moment of Inertia

<!-- card-id: card-679294ed-a230-4029-bf48-1ecfdaa5f7db -->
<!-- card-alias: 8eb8d0edea399e1adc0a165faf55278e1dbf70592db72df10643ce9ff0b5dfb9 -->
Q: What is moment of inertia, and why does it depend on the choice of rotation axis?
A: $I = \sum m_i r_i^2$ (discrete) or $I = \int r^2\,dm$ (continuous), where $r_i$ is the perpendicular distance of each mass element from the rotation axis. Unit: kg·m². It is the rotational analogue of mass (resistance to angular acceleration). The same object has different $I$ values about different axes because the distances $r_i$ change.

<!-- card-id: card-a066ec9e-97ed-4568-b9a1-f93f029138a2 -->
<!-- card-alias: 3929f489513ff7ea45de91c5940101b65a7a5f77522d828e1e768416f7af285b -->
Q: What is the moment of inertia of a point mass $m$ at perpendicular distance $R$ from the axis?
A: $I = mR^2$. This is the building block from which all other moments of inertia are derived by summation or integration.

<!-- card-id: card-1b9713c3-35f9-46a9-8e9b-3006b12dca4b -->
<!-- card-alias: 9ef5b9047fb42b5014a7776287d1a7d08cc46299db878d822771690ce46f0de7 -->
Q: What is the moment of inertia of a thin hollow ring of mass $M$ and radius $R$ about its central (symmetry) axis?
A: $I = MR^2$. Because every mass element sits at the same distance $R$ from the axis, the ring has the same $I$ as a point mass $M$ at radius $R$.

<!-- card-id: card-3c49fb16-9259-4f93-9e5f-993f4a06facc -->
<!-- card-alias: 4956d60309ad46aa17d95262e23d9e59a91d30e207c3f097d4f5651f1368117c -->
Q: What is the moment of inertia of a uniform solid disk (or cylinder) of mass $M$ and radius $R$ about its central axis?
A: $I = \frac{1}{2}MR^2$. It is less than $MR^2$ because much of the disk's mass is closer to the axis than $R$.

<!-- card-id: card-28456f5e-b8f3-4466-91cd-5d8ead0a30e5 -->
<!-- card-alias: acfc5b2b4bcadfa3b4c02048adcc649c9fc6b202d3da16165fa84a10eb7c1740 -->
Q: What is the moment of inertia of a uniform solid sphere of mass $M$ and radius $R$ about a diameter?
A: $I = \frac{2}{5}MR^2$.

<!-- card-id: card-22eaf235-df19-4411-b733-1ff64dbef514 -->
<!-- card-alias: a05c340eb948c4c82780d84c3d842dab8c0ab239e1215e4331cefb2266c527f2 -->
Q: What is the moment of inertia of a uniform thin rod of mass $M$ and length $L$ about an axis through its center perpendicular to the rod?
A: $I = \frac{1}{12}ML^2$.

<!-- card-id: card-bc2dbc4e-8efe-4c38-8391-9550ecd518e6 -->
<!-- card-alias: 2b4d0cf0ed2fcbcc7fe3e4289e22fb6cfa04463e7799fa2ea4ab6b353251fd51 -->
C: A solid disk has $I = \frac{1}{2}MR^2$ and a hollow ring has $I = \lbrack MR^2\rbrack $ about the central axis. The hollow ring has a [larger] moment of inertia because all its mass is at the maximum radius.

## 9.6 Newton's Second Law for Rotation

<!-- card-id: card-54d99691-a232-4905-b78d-77d96115c0b6 -->
<!-- card-alias: adcb5f8590201f7e43c28e84613e12b49d9a8ca70a8110fec8e90b213ecf6699 -->
Q: Under what conditions may Newton's second law for rotation be written $\tau_{net}=I\alpha$?
A: For a rigid body rotating about a fixed axis in an inertial frame, so $I$ about that axis is constant. In general, the safer law is $\vec\tau_{ext}=d\vec L/dt$.

<!-- card-id: card-bcbb9dfa-c720-495b-98f5-6984bb44e7ed -->
<!-- card-alias: 657ef977e68038d7a2ec89069f06899b40f5e78f32db9e48a7e90f1990570a6f -->
C: For a rigid body about a fixed axis with constant $I$: $\tau_{net} = \lbrack I\alpha\rbrack $. The rotational analogue of mass is [moment of inertia $I$].

## 9.7 Parallel Axis Theorem

<!-- card-id: card-2aae0f36-0f6f-43a5-8450-c1a9af07ae47 -->
<!-- card-alias: 6d6bca9e4519d0d18425316191b28d53403155f9aacf7f5c27483588e528fffc -->
Q: State the parallel axis theorem and explain when it is useful.
A: $I = I_{cm} + Md^2$, where $I_{cm}$ is the moment of inertia about the axis through the center of mass (CM), $M$ is the total mass, and $d$ is the perpendicular distance between the new parallel axis and the CM axis. Useful when $I_{cm}$ is known from a table and the rotation axis is displaced from the CM.

<!-- card-id: card-5f1cbe7e-3b09-476d-8227-00f9e8d59b6f -->
<!-- card-alias: 7ffa312fddec91fd9cb6fcbcf70cf454f3df14389c641fc48613b8b77ef5c466 -->
Q: What does the parallel axis theorem tell us about which axis gives the minimum moment of inertia?
A: Among axes parallel to a specified CM axis, $I=I_{cm}+Md^2\geq I_{cm}$. The parallel member of that family passing through the center of mass has the minimum $I$.

<!-- card-id: card-11864cb9-5507-44d4-a282-37f8eb4b1270 -->
<!-- card-alias: dd39019707f1017047937f048ce3993ca2e25fcbdac7df0437f7b57ae5e97dcf -->
<!-- card-alias: 01efb1ed0ae4a7761d59a47b07833f9c4801c9699634d677594158f6a58c2e10 -->
C: By the parallel axis theorem, $I = I_{cm} + Md^2$. The moment of inertia is [minimum] for an axis through the [center of mass].

## 9.8 Rotational Kinetic Energy and Rolling

<!-- card-id: card-2caa3789-8349-4563-88b9-4b4ff76af60a -->
<!-- card-alias: c29d593f7fba40742eaa38f1b53f8a41997aa347b17f5a665e3ca0cbfb8a9b58 -->
Q: What is the rotational kinetic energy of a rigid body?
A: $K_{rot} = \frac{1}{2}I\omega^2$, where $I$ is the moment of inertia (kg·m²) and $\omega$ is the angular speed (rad/s). It is the direct analogue of $K_{trans} = \frac{1}{2}mv^2$.

<!-- card-id: card-6618685c-69f0-4913-b1cc-5bf691a87dd1 -->
<!-- card-alias: d948062323d72a45708f5dc52c94aaff855d72aba6d8ce6f6340de963d3df63c -->
Q: What is the total kinetic energy of an object rolling without slipping, and what constraint connects $v_{cm}$ to $\omega$?
A: $K_{total} = \frac{1}{2}mv_{cm}^2 + \frac{1}{2}I_{cm}\omega^2$, where $v_{cm}$ is the speed of the center of mass (m/s) and $I_{cm}$ is the moment of inertia about the CM axis. The rolling constraint is $v_{cm} = R\omega$, where $R$ is the radius. Rolling objects reach the bottom of an incline slower than a frictionless sliding object from the same height because some energy is in rotation.

<!-- card-id: card-c5df30aa-e3a5-40e9-bcb6-abe1f8f7705a -->
<!-- card-alias: ae1aceda24a0e44b95077fcb3a852cb6fba680a8845b48585dc0e6c6b75f206d -->
Q: Does static friction necessarily do work on a rigid object rolling without slipping on a stationary surface?
A: No. At the instantaneous contact point the velocity is zero, so ideal static friction transfers no energy there even though it can exert a nonzero force and torque. Its direction must be found from the no-slip constraint, not guessed from the center-of-mass motion.

<!-- card-id: card-347078e8-3ea2-47bd-bcbc-5e1f148367a9 -->
<!-- card-alias: 39c59086311b1d0d603147778bcc378a3e041dbb16a66832d44e4cf54b5e35a6 -->
<!-- card-alias: 9c899978e0b4f48a056ac4d43504ee57c89d9544ae7132686d54a4eed362f78f -->
C: For rolling without slipping, $v_{cm} = R\omega$. A solid disk ($I = \frac{1}{2}MR^2$) reaches the bottom of an incline [faster] than a hollow ring ($I = MR^2$) from the same height, because the disk stores [less] energy in rotation.

## 9.9 Angular Momentum

<!-- card-id: card-25b49e9a-dd0f-4a9f-b4c2-2c3aeaaf5a9f -->
<!-- card-alias: aae5f9d1140429aff0eca6d010831c2ab7fa2b8529a6e9e64b48bcb77930de12 -->
Q: Define angular momentum for a particle and state its relation to external torque.
A: About a chosen origin, $\vec L=\vec r\times m\vec v$ and $\vec\tau_{ext}=d\vec L/dt$. For rotation about a fixed principal axis, the component along that axis is $L=I\omega$. Unit: kg·m²/s.

<!-- card-id: card-e3ee75b7-f015-422d-bdbb-72e11dccc2bb -->
<!-- card-alias: 47f59a4da221a5adb1d19e190e2a2e3e5b237e33422ee61b06e8b742ca11a7ae -->
Q: State the law of conservation of angular momentum and give an example.
A: If the net external torque on a system is zero, its total angular momentum is constant. A figure skater pulling in their arms reduces $I$, so $\omega$ increases to keep $L=I\omega$ constant about the spin axis.

<!-- card-id: card-028ae593-21f7-43a9-94c6-a694e6d7487a -->
<!-- card-alias: e6c15ce4dd023767d99c4c57cacc920a3eb698dc5430888c359777f09d8634c3 -->
C: With zero net external torque and fixed spin-axis direction, conservation of angular momentum gives $I_i\omega_i = [I_f\omega_f]$.

<!-- card-id: card-d9d54796-17bf-4776-ac63-5b59f247bae6 -->
<!-- card-alias: 3979709c760107ee48585fb6d2c064daf322048ae8bee0caddda122b759fbd1e -->
<!-- card-alias: cdca91a5c0890c3d915af0ec6aa0c37102c160d17471d8a5c4c3779b899409fa -->
C: A figure skater who pulls in their arms [decreases] $I$ and therefore [increases] $\omega$, keeping angular momentum constant.

## 9.9a Static Equilibrium

<!-- card-id: card-e4cc59b7-1586-4e6f-b6ca-5c8fe3329d4a -->
<!-- card-alias: 5e0897ec35d41e2e5d7aee9cec69ff8602dc9c0d5ef73bed227ee9f387e176b6 -->
Q: What two independent conditions must a rigid body satisfy for static equilibrium?
A: Its net external force and net external torque must both vanish: $\sum\vec F=0$ prevents translational acceleration, and $\sum\vec\tau=0$ prevents angular acceleration.

<!-- card-id: card-b2c42fdd-294a-447e-8b31-56f49a5941bc -->
<!-- card-alias: 0a4a8d65d8520f7b1828dfd914884ca4fcda12639299413db69f0b0e8fb2e680 -->
Q: Why may torques be summed about any convenient origin for a body in static equilibrium?
A: Because $\sum\vec F=0$, shifting the torque origin changes the net torque by a term proportional to the net force, which is zero. Choose an origin that eliminates unknown lever arms or forces.

## 9.9b Pattern Recognition: Rotation

<!-- card-id: card-f60f2afd-6fd2-4a39-8eb1-5aa56ae91540 -->
<!-- card-alias: ea6bbe04de9675399487d563cfaa12b3a5b33fb95328dd11450175a554c09591 -->
Q: A problem says "find angular speed after some torque is applied for time $t$." What technique?
A: $\tau_{net} = I\alpha$, then $\omega = \omega_0 + \alpha t$.

<!-- card-id: card-78e90470-99eb-4fab-b442-b0c5f556f7e9 -->
<!-- card-alias: 7414e5555f3b6246e3542c2101e903fdc2eea5e076040d8dcba74974668bb12e -->
Q: A problem describes a skater pulling in arms or a star collapsing. What technique?
A: Angular momentum conservation: $I_i \omega_i = I_f \omega_f$ (no external torque).

<!-- card-id: card-089d1929-285b-4eab-b989-e6d7faebbd13 -->
<!-- card-alias: 2204d0864fe0da2d6c4db0587df72b8b329b7252c0b439a1b4b424e2aed22b87 -->
Q: A problem says "object rolls without slipping down a ramp; find speed at bottom." What technique?
A: Energy conservation with both translational and rotational KE: $mgh = \tfrac{1}{2}mv^2 + \tfrac{1}{2}I\omega^2$, with constraint $v = R\omega$.

<!-- card-id: card-e0551902-d0c6-4b14-abaa-f67cb950d4cf -->
<!-- card-alias: 27b96f4e97e33160a375f851771453067050589079fa589e4d3853193bbf92c0 -->
Q: A problem gives an axis NOT through the CM. What technique?
A: Parallel axis theorem: $I = I_{cm} + Md^2$.

## 9.10 Procedural: Applying $\tau_{net} = I\alpha$

<!-- card-id: card-deef2e74-b6b6-4abd-aadf-3b47d44d0fcc -->
<!-- card-alias: d16605971c58fc2a8325194470ecd9e585c29e09c3a62f4787248f3f5c186e92 -->
P: A solid disk has mass $M = 2$ kg and radius $R = 0.5$ m. Starting from rest, a constant torque $\tau = 4$ N·m is applied about its center axis. Find: (a) angular acceleration $\alpha$, (b) angular velocity $\omega$ after $t = 3$ s, (c) rotational kinetic energy after 3 s.

S: **Identify:** Solid disk, rotation about center. $M = 2$ kg, $R = 0.5$ m, $\tau = 4$ N·m, $\omega_0 = 0$, $t = 3$ s. Find $\alpha$, $\omega(3)$, $K_{rot}(3)$.

**Plan:** (a) Use $\tau = I\alpha$; find $I$ from table. (b) Use $\omega = \omega_0 + \alpha t$. (c) Use $K_{rot} = \frac{1}{2}I\omega^2$.

**Execute:**
(a) $I = \frac{1}{2}MR^2 = \frac{1}{2}(2)(0.5)^2 = \frac{1}{2}(2)(0.25) = 0.25$ kg·m².
$\alpha = \tau/I = 4/0.25 = 16$ rad/s².

(b) $\omega = 0 + (16)(3) = 48$ rad/s.

(c) $K_{rot} = \frac{1}{2}(0.25)(48)^2 = \frac{1}{2}(0.25)(2304) = 288$ J.

**Evaluate:** Check with work-energy: $W = \tau\Delta\theta$. $\Delta\theta = \frac{1}{2}\alpha t^2 = \frac{1}{2}(16)(9) = 72$ rad. $W = 4 \times 72 = 288$ J. Matches $K_{rot}$ — consistent. Units: (N·m)(rad) = J.
