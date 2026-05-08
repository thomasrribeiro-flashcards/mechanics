+++
order = 3
tags = ["mechanics", "physics", "kinematics", "motion", "calculus", "free fall"]
+++

# Classical Mechanics — Kinematics in One Dimension

## 3.1 Position and Displacement

Q: Why is a reference frame necessary when describing position?
A: Position is a coordinate, not an absolute location. It requires an agreed-upon origin and positive direction. Two observers with different reference frames assign different numbers to the same point.

C: Position $x(t)$ gives the [coordinate] of an object at time $t$ relative to a chosen origin and direction.

Q: What is displacement, and how does it differ from distance?
A: Displacement $\Delta x = x_f - x_i$ is the change in position — a vector quantity with sign indicating direction. Distance is the total path length traveled, always non-negative (a scalar).

C: Displacement $\Delta x = [x_f - x_i]$, where $x_f$ is the final position and $x_i$ is the initial position.

Q: Give an example where displacement and distance differ.
A: A runner completes a full lap of a 400 m track. Distance = 400 m. Displacement = 0 m (returns to starting point).

## 3.2 Velocity

Q: Why distinguish average velocity from instantaneous velocity?
A: Average velocity describes overall motion over a time interval; it can miss momentary details. Instantaneous velocity describes motion at a single instant, which is what Newton's laws relate to forces.

C: Average velocity is $\bar{v} = [\Delta x / \Delta t]$, where $\Delta x$ is displacement and $\Delta t$ is the time interval.

C: Instantaneous velocity is $v = [dx/dt]$ — the derivative of position with respect to time.

Q: What is the difference between velocity and speed?
A: Velocity is a signed (or vector) quantity that includes direction. Speed is $|v|$, the magnitude of velocity, always non-negative. An object moving left has negative velocity but positive speed.

C: Speed is always [non-negative]; velocity can be [negative] (indicating direction opposite to the positive reference).

## 3.3 Acceleration

Q: Why can an object be decelerating even when its acceleration is positive?
A: Deceleration means slowing down, i.e., $|v|$ is decreasing. If the object moves in the negative direction ($v < 0$) and acceleration is positive, $v$ increases toward zero — the object slows down.

C: Average acceleration is $\bar{a} = [\Delta v / \Delta t]$, where $\Delta v$ is the change in velocity and $\Delta t$ is the elapsed time.

C: Instantaneous acceleration is $a = [dv/dt] = d^2x/dt^2$ — the second derivative of position with respect to time.

Q: What are the SI units of acceleration?
A: m/s² (meters per second squared).

## 3.4 Constant Acceleration Equations

Q: Under what single condition do the kinematic equations apply?
A: The acceleration must be constant (uniform) throughout the motion.

Q: Before deriving the first kinematic equation, predict: if acceleration is constant, how should velocity change with time?
A: Linearly. Constant slope on a $v$-$t$ graph means $v(t) = v_0 + at$.

Q: How is the first kinematic equation derived?
A: Integrate $a = dv/dt$ with $a$ constant: $v = v_0 + at$, where $v_0$ = initial velocity, $a$ = constant acceleration, $t$ = elapsed time.

C: First kinematic equation: $v = [v_0 + at]$, where $v_0$ = initial velocity (m/s), $a$ = constant acceleration (m/s²), $t$ = elapsed time (s).

C: Second kinematic equation: $x = x_0 + v_0 t + \frac{1}{2}at^2$, where $x_0$ is the [initial position], $v_0$ is the initial velocity, $a$ is the constant acceleration, and $t$ is the elapsed time.

C: Third kinematic equation (time-independent): $v^2 = [v_0^2 + 2a\Delta x]$, where $\Delta x = x - x_0$ is the displacement.

C: Fourth kinematic equation: $x = x_0 + \frac{v_0 + v}{2}t$, which uses the [average velocity] $\frac{v_0+v}{2}$ when acceleration is constant.

Q: Which kinematic equation should you use when time is unknown?
A: $v^2 = v_0^2 + 2a\Delta x$, since it does not contain $t$.

Q: Which kinematic equation should you use when final velocity is unknown?
A: $x = x_0 + v_0 t + \frac{1}{2}at^2$, since it does not contain $v$.

Q: A problem gives you initial velocity, acceleration, and final position; asks for final velocity. Which equation?
A: $v^2 = v_0^2 + 2a\Delta x$ — time-independent, all four given/asked variables present.

Q: A problem gives you initial velocity, acceleration, and time; asks for displacement. Which equation?
A: $x = x_0 + v_0 t + \tfrac{1}{2}at^2$ — final velocity not needed.

## 3.5 Free Fall

Q: What did Galileo discover about falling objects?
A: Near Earth's surface, all objects fall with the same constant downward acceleration regardless of their mass, provided air resistance is negligible.

C: Near Earth's surface, free-fall acceleration is $g = [9.8 \text{ m/s}^2]$ directed downward, independent of mass.

Q: What is the standard sign convention for free-fall problems?
A: Take upward as positive. Then the acceleration due to gravity is $a = -g = -9.8$ m/s², and the kinematic equations apply with this substitution.

Q: What are the velocity and acceleration of a projectile at its highest point?
A: Instantaneous velocity is zero ($v = 0$), but acceleration is still $-g = -9.8$ m/s² downward. The object is momentarily at rest, but gravity continues to act.

Q: Why does a stone thrown upward take the same time to rise as to fall back to the same height?
A: By time-reversal symmetry of the kinematic equations: the speed at any given height is the same on the way up as on the way down, so the time intervals are equal.

## 3.6 Interpreting Position-Time Graphs

Q: What does the slope of a position-time graph represent?
A: Velocity. A steeper slope means higher speed; a negative slope means the object moves in the negative direction.

Q: What shape does a position-time graph have for constant acceleration?
A: A parabola, because $x(t) = x_0 + v_0 t + \frac{1}{2}at^2$ is quadratic in $t$.

C: On a position-time graph, a [horizontal line] indicates that velocity is zero (object at rest).

## 3.7 Interpreting Velocity-Time Graphs

Q: What does the slope of a velocity-time graph represent?
A: Acceleration. Constant slope means constant acceleration; a horizontal line means zero acceleration (constant velocity).

Q: What does the area under a velocity-time curve represent?
A: Displacement. Area = $\int v\,dt = \Delta x$.

C: On a velocity-time graph, the [area under the curve] equals the displacement.

C: On a velocity-time graph, a [constant slope] indicates constant acceleration, for which the kinematic equations apply.

## 3.8 Worked Example — Free Fall from a Cliff

P: A stone is thrown upward at $v_0 = 20$ m/s from a cliff edge 45 m above the ground. When does it hit the ground and at what speed? Take $g = 10$ m/s² and upward as positive.

S:
**IDENTIFY**: 1D kinematics with constant acceleration (free fall). The stone starts at height $y_0 = 45$ m, initial velocity $v_0 = +20$ m/s (upward), acceleration $a = -g = -10$ m/s², final position $y = 0$ (ground).

**PLAN**:
- Use $y = y_0 + v_0 t + \frac{1}{2}at^2$ to find the time $t$ when $y = 0$.
- Then use $v = v_0 + at$ to find the final speed.

**EXECUTE**:

Setting $y = 0$:
$$0 = 45 + 20t - \frac{1}{2}(10)t^2 = 45 + 20t - 5t^2$$

Rearrange: $5t^2 - 20t - 45 = 0$, divide by 5: $t^2 - 4t - 9 = 0$

Quadratic formula: $t = \frac{4 \pm \sqrt{16 + 36}}{2} = \frac{4 \pm \sqrt{52}}{2} = \frac{4 \pm 7.21}{2}$

Taking the positive root: $t = \frac{4 + 7.21}{2} \approx 5.6$ s

Final velocity: $v = 20 + (-10)(5.6) = 20 - 56 = -36$ m/s

Speed at impact: $|v| = 36$ m/s

**EVALUATE**:
- Positive root is physically meaningful (negative root gives time before launch) ✓
- Stone hits the ground moving downward ($v < 0$) ✓
- Speed at impact ($36$ m/s) is greater than launch speed ($20$ m/s) — sensible, since it fell an extra 45 m ✓
