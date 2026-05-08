+++
order = 9
tags = ["mechanics", "physics", "rotation", "torque", "angular momentum"]
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

C: For a point at radius $r$ from the rotation axis: tangential speed $v_t = r[\omega]$, tangential acceleration $a_t = r[\alpha]$, and centripetal acceleration $a_c = r[\omega^2]$.

## 9.3 Angular Kinematic Equations

Q: Write the three angular kinematic equations for constant $\alpha$ and state the translational analogues for each.
A: (1) $\omega = \omega_0 + \alpha t$ (analogous to $v = v_0 + at$). (2) $\theta = \theta_0 + \omega_0 t + \frac{1}{2}\alpha t^2$ (analogous to $x = x_0 + v_0 t + \frac{1}{2}at^2$). (3) $\omega^2 = \omega_0^2 + 2\alpha\Delta\theta$ (analogous to $v^2 = v_0^2 + 2a\Delta x$). Valid only when $\alpha$ is constant.

C: The angular kinematic equations are identical in form to the 1D equations with substitutions: $x \to [\theta]$, $v \to [\omega]$, $a \to [\alpha]$.

## 9.4 Torque

Q: Why is torque defined using the perpendicular distance (moment arm) rather than the direct distance to the force?
A: Only the component of force perpendicular to the position vector $\vec{r}$ causes rotation. A force directed exactly along $\vec{r}$ (radially) produces no rotation, so its torque should be zero. The cross product $\vec{\tau} = \vec{r} \times \vec{F}$ with magnitude $\tau = rF\sin\phi$ automatically gives zero when force is radial ($\phi = 0$).

Q: State the three equivalent expressions for the magnitude of torque.
A: $\tau = rF\sin\phi = r_\perp F = rF_\perp$, where $r$ is the distance from the pivot to the point of force application (m), $F$ is the force magnitude (N), $\phi$ is the angle between $\vec{r}$ and $\vec{F}$, $r_\perp = r\sin\phi$ is the perpendicular (moment arm) distance, and $F_\perp = F\sin\phi$ is the perpendicular component of force. Unit: N·m.

C: Torque $\tau = rF\sin\phi$. The torque is zero when $\phi = [0°]$ or $[180°]$ (force is parallel or anti-parallel to $\vec{r}$), and maximum when $\phi = [90°]$.

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

C: A solid disk has $I = \frac{1}{2}MR^2$ and a hollow ring has $I = [MR^2]$ about the central axis. The hollow ring has a [larger] moment of inertia because all its mass is at the maximum radius.

## 9.6 Newton's Second Law for Rotation

Q: State Newton's second law for rotation about a fixed axis and identify its translational analogue.
A: $\tau_{net} = I\alpha$, where $\tau_{net}$ is the net torque about the axis (N·m), $I$ is the moment of inertia about that same axis (kg·m²), and $\alpha$ is the angular acceleration (rad/s²). This is the direct rotational analogue of $F_{net} = ma$.

C: For rotation about a fixed axis: $\tau_{net} = [I\alpha]$. The rotational analogue of mass is [moment of inertia $I$].

## 9.7 Parallel Axis Theorem

Q: State the parallel axis theorem and explain when it is useful.
A: $I = I_{cm} + Md^2$, where $I_{cm}$ is the moment of inertia about the axis through the center of mass (CM), $M$ is the total mass, and $d$ is the perpendicular distance between the new parallel axis and the CM axis. Useful when $I_{cm}$ is known from a table and the rotation axis is displaced from the CM.

Q: What does the parallel axis theorem tell us about which axis gives the minimum moment of inertia?
A: The term $Md^2 \geq 0$, so $I \geq I_{cm}$ for any axis parallel to the CM axis. The moment of inertia is always minimum for an axis passing through the center of mass ($d = 0$).

C: By the parallel axis theorem, $I = I_{cm} + Md^2$. The moment of inertia is [minimum] for an axis through the [center of mass].

## 9.8 Rotational Kinetic Energy and Rolling

Q: What is the rotational kinetic energy of a rigid body?
A: $K_{rot} = \frac{1}{2}I\omega^2$, where $I$ is the moment of inertia (kg·m²) and $\omega$ is the angular speed (rad/s). It is the direct analogue of $K_{trans} = \frac{1}{2}mv^2$.

Q: What is the total kinetic energy of an object rolling without slipping, and what constraint connects $v_{cm}$ to $\omega$?
A: $K_{total} = \frac{1}{2}mv_{cm}^2 + \frac{1}{2}I_{cm}\omega^2$, where $v_{cm}$ is the speed of the center of mass (m/s) and $I_{cm}$ is the moment of inertia about the CM axis. The rolling constraint is $v_{cm} = R\omega$, where $R$ is the radius. Rolling objects reach the bottom of an incline slower than a frictionless sliding object from the same height because some energy is in rotation.

C: For rolling without slipping, $v_{cm} = R\omega$. A solid disk ($I = \frac{1}{2}MR^2$) reaches the bottom of an incline [faster] than a hollow ring ($I = MR^2$) from the same height, because the disk stores [less] energy in rotation.

## 9.9 Angular Momentum

Q: Define angular momentum for a rigid body rotating about a fixed axis, and state Newton's second law in angular momentum form.
A: For a rigid body: $L = I\omega$, where $I$ is the moment of inertia (kg·m²) and $\omega$ is the angular speed (rad/s). For a particle: $\vec{L} = \vec{r}\times m\vec{v}$. Newton's second law: $\vec{\tau}_{net} = d\vec{L}/dt$. Unit: kg·m²/s.

Q: State the law of conservation of angular momentum and give an example.
A: If $\vec{\tau}_{net} = 0$ on a system, then $\vec{L} = I\omega = \text{constant}$. Example: a figure skater pulling in their arms reduces $I$, so $\omega$ must increase to keep $L$ constant. Other examples: a gyroscope resisting tipping, a diver tucking for faster rotation, planetary orbital speed increasing at perihelion.

C: Conservation of angular momentum: when net torque is zero, $I_i\omega_i = [I_f\omega_f]$. A figure skater who pulls in their arms [decreases] $I$ and therefore [increases] $\omega$.

## 9.9a Pattern Recognition: Rotation

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
