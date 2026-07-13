+++
order = 9
subject = "physics"
tags = ["mechanics", "physics", "rotation", "torque", "angular-momentum"]
+++

# Classical Mechanics — Rotational Motion

## 9.1 Angular Position and Displacement

Q: Why are radians the natural unit for angle in physics rather than degrees?
A: Radians make the arc-length formula dimensionally clean: $s = r\theta$, where $s$ is arc length (m), $r$ is radius (m), and $\theta$ is in radians (dimensionless ratio). Using degrees would require a conversion factor everywhere, cluttering equations. Radians also appear naturally in derivatives of trigonometric functions.

Q: Define angular position, angular displacement, and the sign convention for rotation.
A: Angular position $\theta$ is measured in radians from a reference direction. Angular displacement $\Delta\theta = \theta_f - \theta_i$. By convention, counterclockwise (CCW) is positive and clockwise (CW) is negative. Full circle: $2\pi$ rad $= 360°$.

C: Arc length and angle are related by $s = r\theta$, where $s$ is arc length (m), $r$ is radius (m), and $\theta$ is in [radians]. One full revolution equals [$2\pi$] radians.

## 9.2 Angular Velocity and Acceleration

Q: Define angular velocity $\omega$ and angular acceleration $\alpha$, and state their SI units.
A: Angular velocity: $\omega = d\theta/dt$ (rad/s). Angular acceleration: $\alpha = d\omega/dt$ (rad/s²). Both are signed scalars for rotation about a fixed axis (positive = CCW, negative = CW).

Q: What are the linear-angular kinematic relationships for a point on a rotating body?
A: For a point at radius $r$ from the axis: tangential speed $v_t = r\omega$; tangential acceleration $a_t = r\alpha$; centripetal acceleration $a_c = r\omega^2 = v_t^2/r$. The total linear acceleration is $a = \sqrt{a_t^2 + a_c^2}$.

C: For a point at radius $r$ from the rotation axis, the tangential relationships are $v_t = r[\omega]$ and $a_t = r[\alpha]$.

C: For a point moving in a circle at radius $r$, the inward centripetal acceleration is $a_c = [r\omega^2] = [v_t^2/r]$.

## 9.3 Angular Kinematic Equations

Q: Write the three angular kinematic equations for constant $\alpha$ and state the translational analogues for each.
A: (1) $\omega = \omega_0 + \alpha t$ (analogous to $v = v_0 + at$). (2) $\theta = \theta_0 + \omega_0 t + \frac{1}{2}\alpha t^2$ (analogous to $x = x_0 + v_0 t + \frac{1}{2}at^2$). (3) $\omega^2 = \omega_0^2 + 2\alpha\Delta\theta$ (analogous to $v^2 = v_0^2 + 2a\Delta x$). Valid only when $\alpha$ is constant.

C: The constant-angular-acceleration equations follow from the 1D kinematic equations under the substitutions [$x \to \theta$, $v \to \omega$, and $a \to \alpha$].

## 9.4 Torque

Q: Why is torque defined using the perpendicular distance (moment arm) rather than the direct distance to the force?
A: Only the component of force perpendicular to the position vector $\vec{r}$ causes rotation. A force directed exactly along $\vec{r}$ (radially) produces no rotation, so its torque should be zero. The cross product $\vec{\tau} = \vec{r} \times \vec{F}$ with magnitude $\tau = rF\sin\phi$ automatically gives zero when force is radial ($\phi = 0$).

Q: State the three equivalent expressions for the magnitude of torque.
A: $\tau = rF\sin\phi = r_\perp F = rF_\perp$, where $r$ is the distance from the pivot to the point of force application (m), $F$ is the force magnitude (N), $\phi$ is the angle between $\vec{r}$ and $\vec{F}$, $r_\perp = r\sin\phi$ is the perpendicular (moment arm) distance, and $F_\perp = F\sin\phi$ is the perpendicular component of force. Unit: N·m.

C: From $\tau = rF\sin\phi$, the torque magnitude is [zero] when the force is parallel or antiparallel to $\vec r$.

C: For fixed $r$ and $F$, $\tau = rF\sin\phi$ is [maximum] when the force is perpendicular to $\vec r$.

## 9.5 Moment of Inertia

Q: What is moment of inertia, and why does it depend on the choice of rotation axis?
A: $I = \sum m_i r_i^2$ (discrete) or $I = \int r^2\,dm$ (continuous), where $r_i$ is the perpendicular distance of each mass element from the rotation axis. Unit: kg·m². It is the rotational analogue of mass (resistance to angular acceleration). The same object has different $I$ values about different axes because the distances $r_i$ change.

Q: What is the moment of inertia of a point mass $m$ at perpendicular distance $R$ from the axis?
A: $I = mR^2$. This is the building block from which all other moments of inertia are derived by summation or integration.

Q: What is the moment of inertia of a thin hollow ring of mass $M$ and radius $R$ about its central (symmetry) axis?
A: $I = MR^2$. Because every mass element sits at the same distance $R$ from the axis, the ring has the same $I$ as a point mass $M$ at radius $R$.

Q: What is the moment of inertia of a uniform solid disk (or cylinder) of mass $M$ and radius $R$ about its central axis?
A: $I = \frac{1}{2}MR^2$. It is less than $MR^2$ because much of the disk's mass is closer to the axis than $R$.

Q: What is the moment of inertia of a uniform solid sphere of mass $M$ and radius $R$ about a diameter?
A: $I = \frac{2}{5}MR^2$.

Q: What is the moment of inertia of a uniform thin rod of mass $M$ and length $L$ about an axis through its center perpendicular to the rod?
A: $I = \frac{1}{12}ML^2$.

C: A solid disk has $I = \frac{1}{2}MR^2$ and a hollow ring has $I = \lbrack MR^2\rbrack $ about the central axis. The hollow ring has a [larger] moment of inertia because all its mass is at the maximum radius.

## 9.6 Newton's Second Law for Rotation

Q: Under what conditions may Newton's second law for rotation be written $\tau_{net}=I\alpha$?
A: For a rigid body rotating about a fixed axis in an inertial frame, so $I$ about that axis is constant. In general, the safer law is $\vec\tau_{ext}=d\vec L/dt$.

C: For a rigid body about a fixed axis with constant $I$: $\tau_{net} = \lbrack I\alpha\rbrack $. The rotational analogue of mass is [moment of inertia $I$].

## 9.7 Parallel Axis Theorem

Q: State the parallel axis theorem and explain when it is useful.
A: $I = I_{cm} + Md^2$, where $I_{cm}$ is the moment of inertia about the axis through the center of mass (CM), $M$ is the total mass, and $d$ is the perpendicular distance between the new parallel axis and the CM axis. Useful when $I_{cm}$ is known from a table and the rotation axis is displaced from the CM.

Q: What does the parallel axis theorem tell us about which axis gives the minimum moment of inertia?
A: Among axes parallel to a specified CM axis, $I=I_{cm}+Md^2\geq I_{cm}$. The parallel member of that family passing through the center of mass has the minimum $I$.

C: By the parallel axis theorem, $I = I_{cm} + Md^2$. The moment of inertia is [minimum] for an axis through the [center of mass].

## 9.8 Rotational Kinetic Energy and Rolling

Q: What is the rotational kinetic energy of a rigid body?
A: $K_{rot} = \frac{1}{2}I\omega^2$, where $I$ is the moment of inertia (kg·m²) and $\omega$ is the angular speed (rad/s). It is the direct analogue of $K_{trans} = \frac{1}{2}mv^2$.

Q: What is the total kinetic energy of an object rolling without slipping, and what constraint connects $v_{cm}$ to $\omega$?
A: $K_{total} = \frac{1}{2}mv_{cm}^2 + \frac{1}{2}I_{cm}\omega^2$, where $v_{cm}$ is the speed of the center of mass (m/s) and $I_{cm}$ is the moment of inertia about the CM axis. The rolling constraint is $v_{cm} = R\omega$, where $R$ is the radius. Rolling objects reach the bottom of an incline slower than a frictionless sliding object from the same height because some energy is in rotation.

Q: Does static friction necessarily do work on a rigid object rolling without slipping on a stationary surface?
A: No. At the instantaneous contact point the velocity is zero, so ideal static friction transfers no energy there even though it can exert a nonzero force and torque. Its direction must be found from the no-slip constraint, not guessed from the center-of-mass motion.

C: For rolling without slipping, $v_{cm} = R\omega$. A solid disk ($I = \frac{1}{2}MR^2$) reaches the bottom of an incline [faster] than a hollow ring ($I = MR^2$) from the same height, because the disk stores [less] energy in rotation.

## 9.9 Angular Momentum

Q: Define angular momentum for a particle and state its relation to external torque.
A: About a chosen origin, $\vec L=\vec r\times m\vec v$ and $\vec\tau_{ext}=d\vec L/dt$. For rotation about a fixed principal axis, the component along that axis is $L=I\omega$. Unit: kg·m²/s.

Q: State the law of conservation of angular momentum and give an example.
A: If the net external torque on a system is zero, its total angular momentum is constant. A figure skater pulling in their arms reduces $I$, so $\omega$ increases to keep $L=I\omega$ constant about the spin axis.

C: With zero net external torque and fixed spin-axis direction, conservation of angular momentum gives $I_i\omega_i = [I_f\omega_f]$.

C: A figure skater who pulls in their arms [decreases] $I$ and therefore [increases] $\omega$, keeping angular momentum constant.

## 9.9a Static Equilibrium

Q: What two independent conditions must a rigid body satisfy for static equilibrium?
A: Its net external force and net external torque must both vanish: $\sum\vec F=0$ prevents translational acceleration, and $\sum\vec\tau=0$ prevents angular acceleration.

Q: Why may torques be summed about any convenient origin for a body in static equilibrium?
A: Because $\sum\vec F=0$, shifting the torque origin changes the net torque by a term proportional to the net force, which is zero. Choose an origin that eliminates unknown lever arms or forces.

## 9.9b Pattern Recognition: Rotation

Q: A problem says "find angular speed after some torque is applied for time $t$." What technique?
A: $\tau_{net} = I\alpha$, then $\omega = \omega_0 + \alpha t$.

Q: A problem describes a skater pulling in arms or a star collapsing. What technique?
A: Angular momentum conservation: $I_i \omega_i = I_f \omega_f$ (no external torque).

Q: A problem says "object rolls without slipping down a ramp; find speed at bottom." What technique?
A: Energy conservation with both translational and rotational KE: $mgh = \tfrac{1}{2}mv^2 + \tfrac{1}{2}I\omega^2$, with constraint $v = R\omega$.

Q: A problem gives an axis NOT through the CM. What technique?
A: Parallel axis theorem: $I = I_{cm} + Md^2$.

## 9.10 Procedural: Applying $\tau_{net} = I\alpha$

P: A solid disk has mass $M = 2$ kg and radius $R = 0.5$ m. Starting from rest, a constant torque $\tau = 4$ N·m is applied about its center axis. Find: (a) angular acceleration $\alpha$, (b) angular velocity $\omega$ after $t = 3$ s, (c) rotational kinetic energy after 3 s.

S: **Identify:** Solid disk, rotation about center. $M = 2$ kg, $R = 0.5$ m, $\tau = 4$ N·m, $\omega_0 = 0$, $t = 3$ s. Find $\alpha$, $\omega(3)$, $K_{rot}(3)$.

**Plan:** (a) Use $\tau = I\alpha$; find $I$ from table. (b) Use $\omega = \omega_0 + \alpha t$. (c) Use $K_{rot} = \frac{1}{2}I\omega^2$.

**Execute:**
(a) $I = \frac{1}{2}MR^2 = \frac{1}{2}(2)(0.5)^2 = \frac{1}{2}(2)(0.25) = 0.25$ kg·m².
$\alpha = \tau/I = 4/0.25 = 16$ rad/s².

(b) $\omega = 0 + (16)(3) = 48$ rad/s.

(c) $K_{rot} = \frac{1}{2}(0.25)(48)^2 = \frac{1}{2}(0.25)(2304) = 288$ J.

**Evaluate:** Check with work-energy: $W = \tau\Delta\theta$. $\Delta\theta = \frac{1}{2}\alpha t^2 = \frac{1}{2}(16)(9) = 72$ rad. $W = 4 \times 72 = 288$ J. Matches $K_{rot}$ — consistent. Units: (N·m)(rad) = J.
