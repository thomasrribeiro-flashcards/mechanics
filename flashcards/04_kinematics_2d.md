+++
order = 4
subject = "physics"
tags = ["mechanics", "physics", "kinematics", "projectile", "circular", "relative motion"]
+++

# Classical Mechanics — Kinematics in Two Dimensions

## 4.1 Position and Velocity in 2D

Q: Why can the x and y components of motion be treated independently in 2D kinematics?
A: Newton's second law acts independently along each axis. An acceleration in the x-direction changes only $v_x$; it has no effect on $v_y$. This independence is the key principle that makes 2D kinematics tractable.

C: Position in 2D is written $\vec{r}(t) = x(t)\hat{i} + y(t)\hat{j}$, where $x(t)$ and $y(t)$ are the [Cartesian components] of position as functions of time.

C: Velocity in 2D is $\vec{v} = d\vec{r}/dt = \dot{x}\hat{i} + \dot{y}\hat{j}$, where the dot notation $\dot{x}$ means [the derivative of $x$ with respect to time].

C: Acceleration in 2D is $\vec{a} = d\vec{v}/dt = \ddot{x}\hat{i} + \ddot{y}\hat{j}$, where each component is the [second derivative] of the corresponding position component with respect to time.

## 4.2 Projectile Motion — Setup

Q: Why is projectile motion a good model for thrown objects near Earth's surface?
A: Near the surface, gravity provides a constant downward force and there is no horizontal force (ignoring air resistance). This makes the horizontal motion uniform and the vertical motion free fall — both solvable with the kinematic equations.

C: For a projectile launched at speed $v_0$ and angle $\theta$ above horizontal, the initial horizontal component is $v_{0x} = [v_0\cos\theta]$, where $v_0$ is the launch speed and $\theta$ is the launch angle.

C: For a projectile launched at speed $v_0$ and angle $\theta$ above horizontal, the initial vertical component is $v_{0y} = [v_0\sin\theta]$, where $v_0$ is the launch speed and $\theta$ is the launch angle.

Q: What are the horizontal and vertical accelerations of a projectile (no air resistance)?
A: Horizontal: $a_x = 0$ (no horizontal force, so uniform motion). Vertical: $a_y = -g = -9.8$ m/s² (gravity only, taking upward as positive).

## 4.3 Projectile Trajectory Equations

C: Horizontal position of a projectile: $x = [v_0\cos\theta \cdot t]$, where $v_0$ is the launch speed, $\theta$ is the launch angle, and $t$ is elapsed time. This reflects uniform horizontal motion.

C: Vertical position of a projectile: $y = v_0\sin\theta \cdot t - \frac{1}{2}gt^2$, where $v_0$ is launch speed, $\theta$ is the launch angle, $g = 9.8$ m/s² is gravitational acceleration, and $t$ is [elapsed time].

C: Horizontal velocity of a projectile is $v_x = [v_0\cos\theta]$ — constant throughout the flight, because there is no horizontal acceleration.

C: Vertical velocity of a projectile is $v_y = v_0\sin\theta - gt$, where $g = 9.8$ m/s² and $t$ is time, showing [velocity decreasing due to gravitational acceleration].

C: The range formula for a projectile launched from and landing at the same height is $R = [v_0^2\sin(2\theta)/g]$, where $v_0$ is launch speed and $g$ is gravitational acceleration.

Q: At what launch angle is the horizontal range of a projectile maximized?
A: At $\theta = 45°$, because $\sin(2\theta)$ is maximized when $2\theta = 90°$. This assumes level ground and no air resistance.

## 4.4 Uniform Circular Motion

Q: Why does an object moving at constant speed in a circle still have an acceleration?
A: Acceleration is the rate of change of the velocity vector, not just its magnitude. In circular motion, the direction of $\vec{v}$ changes continuously even though $|\vec{v}|$ is constant, so $d\vec{v}/dt \neq 0$.

C: In uniform circular motion, the centripetal acceleration is $a_c = [v^2/r]$ directed toward the center, where $v$ is the speed (m/s) and $r$ is the radius of the circle (m).

C: In uniform circular motion, the period $T = [2\pi r/v]$, where $r$ is the radius (m) and $v$ is the speed (m/s). $T$ is the time for one complete revolution.

C: Angular frequency $\omega = [2\pi/T] = v/r$, where $T$ is the period (s), $v$ is the speed (m/s), and $r$ is the radius (m). Units of $\omega$ are rad/s.

C: Centripetal acceleration in terms of angular frequency: $a_c = [\omega^2 r]$, where $\omega$ is the angular frequency (rad/s) and $r$ is the radius (m).

Q: In uniform circular motion, what direction is the centripetal acceleration?
A: Always toward the center of the circle (centripetal = center-seeking). It is perpendicular to the velocity, so it changes the direction of $\vec{v}$ without changing its magnitude.

## 4.5 Why Centripetal Acceleration Points Inward

Q: Before deriving it: predict what direction $\Delta\vec{v}$ should point if the velocity rotates around a circle.
A: Toward the center. Each $\vec{v}$ is tangent; subtracting two nearby tangents leaves a vector aimed at the circle's center.

Q: Derive qualitatively why the acceleration of an object in uniform circular motion points toward the center.
A: $\vec{v}$ is always tangent. Over $\Delta t$, $\vec{v}$ rotates by the same angle as the position. $\Delta\vec{v} = \vec{v}_2 - \vec{v}_1$ points inward, so $\vec{a} = \Delta\vec{v}/\Delta t$ also points inward.

## 4.5a Pattern Recognition

Q: A problem says "object launched at angle $\theta$ from level ground; find range." What technique?
A: Range formula $R = v_0^2 \sin(2\theta)/g$ — only valid when launch and landing heights are equal.

Q: A problem gives projectile launch from a cliff (lands below launch point). Why can't you use $R = v_0^2 \sin(2\theta)/g$?
A: It assumes equal launch/landing height. Use full $y(t)$ equation, solve for $t$ when $y$ = landing height, then $x = v_{0x} t$.

Q: A problem gives constant speed in a circle and asks for the force needed. What technique?
A: Centripetal: $F_{net} = m v^2 / r$ directed toward center. Identify which real force(s) provide it.

## 4.6 Non-Uniform Circular Motion

Q: What is the difference between centripetal and tangential acceleration in circular motion?
A: Centripetal acceleration $a_c = v^2/r$ is perpendicular to velocity and changes only the direction of motion (toward the center). Tangential acceleration $a_t = |dv/dt|$ is parallel to velocity and changes the speed. Both occur in non-uniform circular motion.

C: The total acceleration magnitude in non-uniform circular motion is $a = [\sqrt{a_c^2 + a_t^2}]$, where $a_c = v^2/r$ is the centripetal component and $a_t = |dv/dt|$ is the tangential component.

## 4.7 Relative Motion (Galilean)

Q: What does "velocity of A relative to C" mean?
A: It is the velocity of object A as measured by an observer moving with frame C, i.e., how fast and in what direction A appears to move to someone at rest in C.

C: Galilean velocity addition: $\vec{v}_{A/C} = [\vec{v}_{A/B} + \vec{v}_{B/C}]$, where $\vec{v}_{A/B}$ is the velocity of A relative to B and $\vec{v}_{B/C}$ is the velocity of B relative to C.

Q: A boat heads north at 5 m/s relative to still water. The river flows east at 3 m/s. What is the boat's velocity relative to the ground?
A: $\vec{v}_{boat/ground} = \vec{v}_{boat/water} + \vec{v}_{water/ground} = 5\hat{j} + 3\hat{i}$ m/s. Magnitude $= \sqrt{25+9} = \sqrt{34} \approx 5.8$ m/s at an angle $\arctan(3/5) \approx 31°$ east of north.

## 4.8 Worked Example — Projectile Range

P: A ball is launched at $\theta = 30°$ above horizontal with $v_0 = 40$ m/s from level ground. Use $g = 10$ m/s² to find: (a) maximum height, (b) time of flight, (c) horizontal range.

S:
**IDENTIFY**: Projectile motion launched from and landing at the same height. Horizontal and vertical components are independent.

**PLAN**:
- Initial components: $v_{0x} = v_0\cos\theta$, $v_{0y} = v_0\sin\theta$
- Max height: at the apex $v_y = 0$, use $v_y^2 = v_{0y}^2 - 2gy_{max}$
- Time of flight: $y = v_{0y}t - \frac{1}{2}gt^2 = 0$ at landing
- Range: $x = v_{0x} \cdot t_{flight}$

**EXECUTE**:

Initial components:
$$v_{0x} = 40\cos 30° = 40 \times \frac{\sqrt{3}}{2} = 20\sqrt{3} \approx 34.6 \text{ m/s}$$
$$v_{0y} = 40\sin 30° = 40 \times \frac{1}{2} = 20 \text{ m/s}$$

(a) Maximum height: $v_y = 0$ at apex
$$0 = v_{0y}^2 - 2g y_{max} \implies y_{max} = \frac{v_{0y}^2}{2g} = \frac{(20)^2}{2(10)} = \frac{400}{20} = 20 \text{ m}$$

(b) Time of flight: $v_{0y}t - \frac{1}{2}gt^2 = 0 \implies t(v_{0y} - \frac{1}{2}gt) = 0$
Taking $t \neq 0$: $t = \frac{2v_{0y}}{g} = \frac{2(20)}{10} = 4$ s

(c) Range: $R = v_{0x} \cdot t = 20\sqrt{3} \times 4 = 80\sqrt{3} \approx 138$ m

Check with formula: $R = v_0^2\sin(2\theta)/g = (1600)\sin 60°/10 = 160 \times 0.866 = 138.6$ m ✓

**EVALUATE**:
- Max height (20 m) is less than half the range (69 m) — sensible for $30° < 45°$ ✓
- Time of flight is symmetric: 2 s up, 2 s down ✓
- Range formula cross-check agrees ✓
