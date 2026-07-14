+++
order = 3
subject = "physics"
tags = ["mechanics", "physics", "kinematics", "motion", "calculus", "free-fall"]
+++

# Classical Mechanics — Kinematics in One Dimension

## 3.1 Position and Displacement

<!-- card-id: card-f07298d7-d964-4594-b8f1-7c7862ccf468 -->
<!-- card-alias: 58ac5420827e526710a5c01e2b5b7f685e049bef0a48f58f51dafdc16ee99d29 -->
Q: Why is a reference frame necessary when describing position?
A: Position is a coordinate, not an absolute location. It requires an agreed-upon origin and positive direction. Two observers with different reference frames assign different numbers to the same point.

<!-- card-id: card-372f8f1c-4a9e-4325-a376-2a34512296a1 -->
<!-- card-alias: 1febb4dc5394a48d0d6ebcaf6bd70d863245ec28a4b0318a183a4f30df285bad -->
C: Position $x(t)$ gives the [coordinate] of an object at time $t$ relative to a chosen origin and direction.

<!-- card-id: card-dd882fd4-cd10-4717-b7c9-d5d09b593aca -->
<!-- card-alias: 18ce423b168ff9830051c8bec351fdc72fce4fc5552c3dd34e93f2d73a548646 -->
Q: What is displacement, and how does it differ from distance?
A: Displacement $\Delta x = x_f - x_i$ is the change in position — a vector quantity with sign indicating direction. Distance is the total path length traveled, always non-negative (a scalar).

<!-- card-id: card-3af14a47-a9ea-459d-8a1c-5198a3250de8 -->
<!-- card-alias: 93255f14919b3dc6e359cf73a57ba10d41bbcadb024ec210313820b5ae5b7d1b -->
C: Displacement $\Delta x = [x_f - x_i]$, where $x_f$ is the final position and $x_i$ is the initial position.

<!-- card-id: card-e5b0ef6a-f98d-41f7-b40f-d25410639307 -->
<!-- card-alias: b278a4fb48ea2b40b054421e0c7a72271efabcac22115652ab4057d6e88d80bd -->
Q: Give an example where displacement and distance differ.
A: A runner completes a full lap of a 400 m track. Distance = 400 m. Displacement = 0 m (returns to starting point).

## 3.2 Velocity

<!-- card-id: card-24288818-0698-4a41-9713-c0512add521b -->
<!-- card-alias: 91e43097d07f37d61a6668c10ff020441b8760f9014d2b335078de8c50532d3d -->
Q: Why distinguish average velocity from instantaneous velocity?
A: Average velocity describes net displacement over an interval and can hide reversals or pauses. Instantaneous velocity describes the motion at one instant and is the slope of $x(t)$ there.

<!-- card-id: card-ebe5fd98-25bf-4016-8c67-83278d56e720 -->
<!-- card-alias: e7860596e97b491ce28ffdde1402d71ebce4621a1c482a8b73a8d306d789b955 -->
C: Average velocity is $\bar{v} = [\Delta x / \Delta t]$, where $\Delta x$ is displacement and $\Delta t$ is the time interval.

<!-- card-id: card-45680ff7-2cd2-47ad-a36e-a31c8c23a2d9 -->
<!-- card-alias: 23cbdec5fab395881cae3a4aa2058e72d2be582f9b03a930186b2826c41b3dde -->
C: Instantaneous velocity is $v = [dx/dt]$ — the derivative of position with respect to time.

<!-- card-id: card-2c216452-da4d-4ad0-afc8-885415cfc73a -->
<!-- card-alias: d7005c6a8fc16f3a26564050d4736f69704e4752088de7898d77ccd1d1d6866b -->
Q: What is the difference between velocity and speed?
A: Velocity is a signed (or vector) quantity that includes direction. Speed is $|v|$, the magnitude of velocity, always non-negative. An object moving left has negative velocity but positive speed.

<!-- card-id: card-7d4bfa80-afa8-4a9e-9c14-d1dd3bb07ada -->
<!-- card-alias: 9914547211022151adc48f301c5972e9604103f250ab4900257687000f0f2dce -->
<!-- card-alias: 86437184a8aecf24f469b95266a5a8bb6e7667f727e328570b0147bc6f5fac05 -->
C: Speed is always [non-negative]; velocity can be [negative] (indicating direction opposite to the positive reference).

## 3.3 Acceleration

<!-- card-id: card-efb7f937-7d91-4a57-9b2c-d74db310421d -->
<!-- card-alias: dc870acecd17aa965fc1e9991e5ac7e198450f9a47d6378180813bc37da12c92 -->
Q: Why can an object be decelerating even when its acceleration is positive?
A: Deceleration means slowing down, i.e., $|v|$ is decreasing. If the object moves in the negative direction ($v < 0$) and acceleration is positive, $v$ increases toward zero — the object slows down.

<!-- card-id: card-599d6d18-6c0c-4c7c-8bd7-ed70b188ab9b -->
<!-- card-alias: bb9df42ebfec4634b2a4b5ae212070f6bf26b5221ad663655179c8bfb218ff56 -->
C: Average acceleration is $\bar{a} = [\Delta v / \Delta t]$, where $\Delta v$ is the change in velocity and $\Delta t$ is the elapsed time.

<!-- card-id: card-a4dfb38d-ac95-42be-915c-25d5e2e1cecf -->
<!-- card-alias: 0b28e0c6eb53f6010b884b4ff21bb598e9865a57533a164705b6ae9df1e994e1 -->
C: Instantaneous acceleration is $a = [dv/dt] = d^2x/dt^2$ — the second derivative of position with respect to time.

<!-- card-id: card-0ca875da-0cc7-4489-8689-9ecc451d0da6 -->
<!-- card-alias: 5339a5e816b0ab2039b67ad07a7306a66f889b672d69638036ac9b122323a078 -->
Q: What are the SI units of acceleration?
A: m/s² (meters per second squared).

## 3.4 Constant Acceleration Equations

<!-- card-id: card-ca4dbc1e-a6c8-44a4-b740-7dd576938e27 -->
<!-- card-alias: 6303a1ca12205bcb6d74e86d4f0b10cf2a88cac020614d1aaa156b23bfa2e806 -->
Q: Under what single condition do the kinematic equations apply?
A: The acceleration must be constant (uniform) throughout the motion.

<!-- card-id: card-0c93708a-3d16-485d-ad66-10f2386f44cc -->
<!-- card-alias: 2031aaf92604ab5a9761f29703a9ef66404a268cbb3e943c7c06ca3bb8e124cb -->
Q: Before deriving the first kinematic equation, predict: if acceleration is constant, how should velocity change with time?
A: Linearly. Constant slope on a $v$-$t$ graph means $v(t) = v_0 + at$.

<!-- card-id: card-46862814-3783-4de0-ae0e-cfb654df1333 -->
<!-- card-alias: 3a672d904d7c545d04c459b5adbd3547d002efe9a3b73612ac8e314c2c4b529c -->
Q: How is the first kinematic equation derived?
A: Integrate $a = dv/dt$ with $a$ constant: $v = v_0 + at$, where $v_0$ = initial velocity, $a$ = constant acceleration, $t$ = elapsed time.

<!-- card-id: card-3b14f6a9-ff10-47b2-a7cf-72cca83a4cee -->
<!-- card-alias: 3f01b34566835990a02b80d43e9eb206c0da5519c328b1dd57856a6f6abce483 -->
C: First kinematic equation: $v = [v_0 + at]$, where $v_0$ = initial velocity (m/s), $a$ = constant acceleration (m/s²), $t$ = elapsed time (s).

<!-- card-id: card-90c8afd5-6d7d-460f-8fce-d13a03b2255c -->
<!-- card-alias: 9ae69075e649a2a0d0515e7daef832bc8b41b6c6d8cb0be6df9d8e2c8db535ac -->
C: Second kinematic equation: $x = x_0 + v_0 t + \frac{1}{2}at^2$, where $x_0$ is the [initial position], $v_0$ is the initial velocity, $a$ is the constant acceleration, and $t$ is the elapsed time.

<!-- card-id: card-7296f581-1aaf-41ff-b921-b3c61ae0eabf -->
<!-- card-alias: 22b6f1c17fa218c8e42e39350dbc44c943e7e89232e029a180da0dd76b7f25a2 -->
C: Third kinematic equation (time-independent): $v^2 = [v_0^2 + 2a\Delta x]$, where $\Delta x = x - x_0$ is the displacement.

<!-- card-id: card-56680465-bd98-4744-a2de-8cc5a6437824 -->
<!-- card-alias: 3bddfed87d83f16cd09cd94b682628c7e6888d83de403cf3039778701afc6881 -->
C: Fourth kinematic equation: $x = x_0 + \frac{v_0 + v}{2}t$, which uses the [average velocity] $\frac{v_0+v}{2}$ when acceleration is constant.

<!-- card-id: card-df891c9d-8378-4f60-9c56-244ded5eb415 -->
<!-- card-alias: 896cf024837c257f3c9e74cbf38ae574e1d9a531c3e241e53a9503661fd2ed1d -->
Q: Which kinematic equation should you use when time is unknown?
A: $v^2 = v_0^2 + 2a\Delta x$, since it does not contain $t$.

<!-- card-id: card-ec46a3d8-e9ae-4f07-8536-c962ad739485 -->
<!-- card-alias: a5c8d96e2c7c1bc4622454abe97e469d3a3c0459df6350ed3a9e14fe267bfdff -->
Q: Which kinematic equation should you use when final velocity is unknown?
A: $x = x_0 + v_0 t + \frac{1}{2}at^2$, since it does not contain $v$.

<!-- card-id: card-9f0576eb-5a75-4dac-8833-f195b0c10336 -->
<!-- card-alias: d3d4ac520302f3031639b62524700a600486b29e74a254849298d53195686a7e -->
Q: A problem gives you initial velocity, acceleration, and final position; asks for final velocity. Which equation?
A: $v^2 = v_0^2 + 2a\Delta x$ — time-independent, all four given/asked variables present.

<!-- card-id: card-8426f36d-ece2-4148-a8b4-cd8cbd8448e5 -->
<!-- card-alias: dd39e7f0590b22b384901a22bd9cf1ffd7b614d83c08265ad2c03e25eeb6415d -->
Q: A problem gives you initial velocity, acceleration, and time; asks for displacement. Which equation?
A: $x = x_0 + v_0 t + \tfrac{1}{2}at^2$ — final velocity not needed.

## 3.5 Free Fall

<!-- card-id: card-35f15753-4fa9-40cc-9ce7-a03be69efb33 -->
<!-- card-alias: 8ce1da49f46687445338eee7c48e83491fa87bf6b62acea79feff54dd95fd317 -->
Q: What did Galileo discover about falling objects?
A: Near Earth's surface, all objects fall with the same constant downward acceleration regardless of their mass, provided air resistance is negligible.

<!-- card-id: card-62ceae68-5b11-4e31-9177-e3ebba2a6978 -->
<!-- card-alias: 579ef4c870cfb081bc41e68f5385b9ea8def634266f7b0a11a095f0c5963b44c -->
C: Near Earth's surface, free-fall acceleration is $g = [9.8 \text{ m/s}^2]$ directed downward, independent of mass.

<!-- card-id: card-0eb6c73c-e59a-4034-bb99-e7ebebef8659 -->
<!-- card-alias: 2d381e22a666797f365c28fbba4c47f7db3639ea59d7b205471f395df2a47508 -->
Q: What is the standard sign convention for free-fall problems?
A: Take upward as positive. Then the acceleration due to gravity is $a = -g = -9.8$ m/s², and the kinematic equations apply with this substitution.

<!-- card-id: card-235b7118-40d9-4393-8a0b-040e57973910 -->
<!-- card-alias: 4e641c8c842639368e308d3646ab926c1495bc31613e9478cad1c777dd709e53 -->
Q: For an object thrown straight upward, what are its velocity and acceleration at the highest point?
A: Its velocity is momentarily zero, but its acceleration remains $-g$ downward. Zero velocity at an instant does not imply zero acceleration.

<!-- card-id: card-af89ac5d-b0b5-4b0f-b001-2c51d088a232 -->
<!-- card-alias: 52e55cfa779e2f4b023e1222780b497b1d0e6db96354a51c94e5232f0e7f5e04 -->
Q: Why does a stone thrown upward take the same time to rise as to fall back to the same height?
A: With constant gravitational acceleration and negligible air resistance, the kinematic equations are time-reversal symmetric: at a given height the upward and downward speeds have equal magnitude, so the time intervals are equal.

## 3.6 Interpreting Position-Time Graphs

<!-- card-id: card-fa71db92-26c5-463c-96ae-1447035768cb -->
<!-- card-alias: a71eb5d4cf7321a161552ae6587e49f7e7510c124dca4c296ce3750ae8c60c1e -->
Q: What does the slope of a position-time graph represent?
A: Velocity. A steeper slope means higher speed; a negative slope means the object moves in the negative direction.

<!-- card-id: card-4facb14e-359d-45e4-a7c7-00b272202462 -->
<!-- card-alias: 4fafab5300fcaae1fb902f1171c51d2b576d77ef18b59b19fd43b04e370bbd24 -->
Q: What shape does a position-time graph have for constant acceleration?
A: A parabola, because $x(t) = x_0 + v_0 t + \frac{1}{2}at^2$ is quadratic in $t$.

<!-- card-id: card-fc98040d-fbd7-404c-8ab0-b6ef1554c337 -->
<!-- card-alias: c44f535566d0ac2e84173ee874a705e9a7ad7499690d4a6ca5d94a6beb8d19bf -->
C: On a position-time graph, a [horizontal line] indicates that velocity is zero (object at rest).

## 3.7 Interpreting Velocity-Time Graphs

<!-- card-id: card-d8e7d1d4-5e96-4358-8880-2016a8e96448 -->
<!-- card-alias: 20f027fb7d9b4a392844e73623d1a5bb601eb005163c47c8e324a19fa3bbb2ab -->
Q: What does the slope of a velocity-time graph represent?
A: Acceleration. Constant slope means constant acceleration; a horizontal line means zero acceleration (constant velocity).

<!-- card-id: card-d8d792b7-8161-434b-9e86-586f808439ef -->
<!-- card-alias: 9ee676066a39cb1369113c67d913b62167349e788751fe51d8bd44aafbe4c5ca -->
Q: What does the area under a velocity-time curve represent?
A: Displacement. Area = $\int v\,dt = \Delta x$.

<!-- card-id: card-4de1c743-c8a0-4e08-857b-d90ac85ba319 -->
<!-- card-alias: 624fe787fc95736f23382cdfb1c8bb3b402c38b058b9e2ab5a613e0b041d988d -->
C: On a velocity-time graph, the [area under the curve] equals the displacement.

<!-- card-id: card-be413c10-c8dc-4d56-bed4-017840c69bdb -->
<!-- card-alias: 4634768c49a08a2250a738ae96fd157deb4854170b28e5c799b2ea62821ff486 -->
C: On a velocity-time graph, a [constant slope] indicates constant acceleration, for which the kinematic equations apply.

## 3.8 Worked Example — Free Fall from a Cliff

<!-- card-id: card-16a2487a-b6b3-4d5e-b053-3034d59574fe -->
<!-- card-alias: 27a0268bf792081dae0b8bfd6cea41e704240ed8679dfd5392ddad9167918087 -->
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
