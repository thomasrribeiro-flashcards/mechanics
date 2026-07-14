+++
order = 4
subject = "physics"
tags = ["mechanics", "physics", "kinematics", "projectile", "circular", "relative-motion"]
+++

# Classical Mechanics — Kinematics in Two Dimensions

## 4.1 Position and Velocity in 2D

<!-- card-id: card-89d545ea-79c5-4d5d-85d3-3efcfe4d22c7 -->
<!-- card-alias: 39ed772fa518163b0bf9022e38c5d8a8eb37b6f5a8c8fdcd90a4e9bf2da67966 -->
Q: Why can the x and y components of motion be treated independently in 2D kinematics?
A: The vector equations hold component by component: $a_x$ changes $v_x$ and $a_y$ changes $v_y$. The components share the same time but can be solved separately once their accelerations and initial conditions are known.

<!-- card-id: card-a32ca23f-b4a4-4c28-8763-91a705d94b5f -->
<!-- card-alias: 8c65e623f1c22f19686e3464d4c2265dd18fdb8521b974530ee04d940bf9ee5c -->
C: Position in 2D is written $\vec{r}(t) = x(t)\hat{i} + y(t)\hat{j}$, where $x(t)$ and $y(t)$ are the [Cartesian components] of position as functions of time.

<!-- card-id: card-003e7687-0e45-435c-9318-a53f90df85fa -->
<!-- card-alias: d708d87f2b9a7c7949a66ed970cbd90ea95a01f88f8dd57a4d9419ac2cf5f8bd -->
C: Velocity in 2D is $\vec{v} = d\vec{r}/dt = \dot{x}\hat{i} + \dot{y}\hat{j}$, where the dot notation $\dot{x}$ means [the derivative of $x$ with respect to time].

<!-- card-id: card-103fdb0c-410a-44fe-a36a-ff39911ec425 -->
<!-- card-alias: 6ac7f20c0f738d860fcee1d860630bce66a5b18d8c9b7dd5dbe33fbf36a22219 -->
C: Acceleration in 2D is $\vec{a} = d\vec{v}/dt = \ddot{x}\hat{i} + \ddot{y}\hat{j}$, where each component is the [second derivative] of the corresponding position component with respect to time.

## 4.2 Projectile Motion — Setup

<!-- card-id: card-38ab0ef4-c273-4bab-8eca-928b3da3be37 -->
<!-- card-alias: 49502f1b67bac331bb39f82cd7455cc3b1be273b61615cd874c46cbce1c56159 -->
Q: Why is projectile motion a good model for thrown objects near Earth's surface?
A: Near the surface, gravity provides a constant downward force and there is no horizontal force (ignoring air resistance). This makes the horizontal motion uniform and the vertical motion free fall — both solvable with the kinematic equations.

<!-- card-id: card-eac16d5b-baef-49b5-8a5d-2760b0194cba -->
<!-- card-alias: 0b62c2ce5e83ebdcd9d83b1c23e4e386ed401479dbc2c68f2e073c41c485f3c0 -->
C: For a projectile launched at speed $v_0$ and angle $\theta$ above horizontal, the initial horizontal component is $v_{0x} = [v_0\cos\theta]$, where $v_0$ is the launch speed and $\theta$ is the launch angle.

<!-- card-id: card-fd48dbdc-c44f-44bd-9c87-789ba160da5b -->
<!-- card-alias: 686effdff0e25cee578e4c64d81f28eeb88ed60d96e288b0cb7ff29a4248619f -->
C: For a projectile launched at speed $v_0$ and angle $\theta$ above horizontal, the initial vertical component is $v_{0y} = [v_0\sin\theta]$, where $v_0$ is the launch speed and $\theta$ is the launch angle.

<!-- card-id: card-98802481-3844-44c8-afcb-46bc49f0f186 -->
<!-- card-alias: 75e1d801c06d61e7905fe1de7f85bf7bb81fc77e96ab79576e354c93a3d6bbf9 -->
Q: What are the horizontal and vertical accelerations of a projectile (no air resistance)?
A: Horizontal: $a_x = 0$ (no horizontal force, so uniform motion). Vertical: $a_y = -g = -9.8$ m/s² (gravity only, taking upward as positive).

## 4.3 Projectile Trajectory Equations

<!-- card-id: card-92d550c0-a719-4a89-9137-30386bf46c28 -->
<!-- card-alias: 1aeedf9fe587351c13e5f8280eb8721db4f7ebe79ff0f4dbb262fbbf759ff118 -->
C: With no air resistance, a projectile's horizontal position is $x(t) = [x_0 + (v_0\cos\theta)t]$, where $x_0$ is initial horizontal position, $v_0$ is launch speed, and $\theta$ is launch angle.

<!-- card-id: card-4ed06c4d-3cd6-4c01-a1d2-3e6fdffe4ce8 -->
<!-- card-alias: ecf110507b5b029afc19b0157033fd30c21e1000fb42a10d184a58d6911c4fdc -->
C: With upward positive, a projectile's vertical position is $y(t) = [y_0 + (v_0\sin\theta)t - \frac{1}{2}gt^2]$, where $y_0$ is initial height and $g$ is gravitational acceleration magnitude.

<!-- card-id: card-63962cfb-5396-437f-9164-d86658e5dfcb -->
<!-- card-alias: a2dc97dabb69a0ef48989eabbe2446e74bfacc5b637955ccb74da01ac1b082f5 -->
C: Horizontal velocity of a projectile is $v_x = [v_0\cos\theta]$ — constant throughout the flight, because there is no horizontal acceleration.

<!-- card-id: card-bcd78c7d-f9cc-4b3a-9ab4-a8b7c5c32bad -->
<!-- card-alias: 756fb1bbfc4e75fec2e779d0bfb6ac08583f9d90ae484e57c89f6bedd16ecd7c -->
C: Vertical velocity of a projectile is $v_y = v_0\sin\theta - gt$, where $g = 9.8$ m/s² and $t$ is time, showing [velocity decreasing due to gravitational acceleration].

<!-- card-id: card-d88af59f-f880-4d52-8ceb-cca63b2ea767 -->
<!-- card-alias: f73647f93602f35b908604cdac6d4549db70b748d7229d15d20b0102e1f98c5f -->
Q: At the highest point of an angled projectile's path, which velocity component is zero?
A: Only $v_y$ is zero. The horizontal component remains $v_x=v_0\cos\theta$, so the projectile is not momentarily at rest unless it was launched vertically.

<!-- card-id: card-5592cfcd-648d-45f1-9902-f0553ba1d910 -->
<!-- card-alias: 5ffab31bd25c1b4500fd48f3cb6e19d47bcfe11fe26ebdbcbe0d46a8d8d9c08d -->
Q: Why is the no-drag projectile trajectory a parabola?
A: Eliminate $t$ using $t=(x-x_0)/v_{0x}$ in the quadratic vertical equation. The result has the form $y=y_0+a(x-x_0)-b(x-x_0)^2$.

<!-- card-id: card-25b7feee-0f33-4e50-9cdd-a1b3711c2a09 -->
<!-- card-alias: 40b6219d29e5546ccad4f4869b6545c5a37841ecabfabc97c8645480af132e71 -->
C: The range formula for a projectile launched from and landing at the same height is $R = [v_0^2\sin(2\theta)/g]$, where $v_0$ is launch speed and $g$ is gravitational acceleration.

<!-- card-id: card-08c7407a-7a8f-4949-8119-5a81ec395a4d -->
<!-- card-alias: af5907f0188895cbeec37fb9f69d34c679aa3c406869a0c489ebaaf66314400d -->
Q: At what launch angle is the horizontal range of a projectile maximized?
A: At $\theta = 45°$, because $\sin(2\theta)$ is maximized when $2\theta = 90°$. This assumes level ground and no air resistance.

## 4.4 Uniform Circular Motion

<!-- card-id: card-0fa25ac7-92e8-4934-b5ce-8e5b0ce0dd31 -->
<!-- card-alias: e19442cc1bf138578467fd52d4ad4ae1d3a4c069a1447dff65f56739b9a6d6ea -->
Q: Why does an object moving at constant speed in a circle still have an acceleration?
A: Acceleration is the rate of change of the velocity vector, not just its magnitude. In circular motion, the direction of $\vec{v}$ changes continuously even though $|\vec{v}|$ is constant, so $d\vec{v}/dt \neq 0$.

<!-- card-id: card-fada2ad8-6079-44ea-aff1-ada7aba090d4 -->
<!-- card-alias: 82fd6186a2481a4970c15dd7bb9789bf682c7a16ce8eb3ab48365c1826238a02 -->
C: In uniform circular motion, the centripetal acceleration is $a_c = [v^2/r]$ directed toward the center, where $v$ is the speed (m/s) and $r$ is the radius of the circle (m).

<!-- card-id: card-3aa82b36-f303-495c-96ae-58bf9ea190dc -->
<!-- card-alias: 4d0f8683a7dc1aba5f62557c79aad62f2d18476e904c042b35202de5890118f8 -->
C: In uniform circular motion, the period $T = [2\pi r/v]$, where $r$ is the radius (m) and $v$ is the speed (m/s). $T$ is the time for one complete revolution.

<!-- card-id: card-ed69e67b-5856-4548-86f0-80df3bd6e9ab -->
<!-- card-alias: 1c86737c0af127d228934596ce7bbb4d2a1683813f5bb6ae7f6d7b6f9dabd0c6 -->
C: Angular frequency $\omega = [2\pi/T] = v/r$, where $T$ is the period (s), $v$ is the speed (m/s), and $r$ is the radius (m). Units of $\omega$ are rad/s.

<!-- card-id: card-6b0d65e3-146b-424a-b5fb-2fc632fce50a -->
<!-- card-alias: 2e0ee35d6ea225a618f4fc46c03458317760ec4a6a34476be05c3b08f1094a33 -->
C: Centripetal acceleration in terms of angular frequency: $a_c = [\omega^2 r]$, where $\omega$ is the angular frequency (rad/s) and $r$ is the radius (m).

<!-- card-id: card-6891f2c7-5513-4547-b683-5f3cab4b8dc3 -->
<!-- card-alias: 99ab1b5e96335734f264bb41cecb0edfd0cb74d2d976b2567c267923d24eff39 -->
Q: In uniform circular motion, what direction is the centripetal acceleration?
A: Always toward the center of the circle (centripetal = center-seeking). It is perpendicular to the velocity, so it changes the direction of $\vec{v}$ without changing its magnitude.

## 4.5 Why Centripetal Acceleration Points Inward

<!-- card-id: card-b0ff5733-6ef7-4a52-8b1a-ddf8a1d02e37 -->
<!-- card-alias: 5d29bad8742d6ae6caad7626c173833f69997881c998687f2e0897273845df04 -->
Q: Before deriving it: predict what direction $\Delta\vec{v}$ should point if the velocity rotates around a circle.
A: Toward the center. Each $\vec{v}$ is tangent; subtracting two nearby tangents leaves a vector aimed at the circle's center.

<!-- card-id: card-60365edd-2b20-402c-b168-cfcd1af18ea4 -->
<!-- card-alias: 47570589a62ca9a367ebd67c2959bda307aefc4a305e12772cbe695d31ec228e -->
Q: Derive qualitatively why the acceleration of an object in uniform circular motion points toward the center.
A: $\vec{v}$ is always tangent. Over $\Delta t$, $\vec{v}$ rotates by the same angle as the position. $\Delta\vec{v} = \vec{v}_2 - \vec{v}_1$ points inward, so $\vec{a} = \Delta\vec{v}/\Delta t$ also points inward.

## 4.5a Pattern Recognition

<!-- card-id: card-2496e66d-8939-4e35-8777-c5f2c818ae33 -->
<!-- card-alias: 20d5e03d51db2e92c6ab5e34bc3a2bba0f92eaa3faf26d908d8a0b438a452a76 -->
Q: A problem says "object launched at angle $\theta$ from level ground; find range." What technique?
A: Range formula $R = v_0^2 \sin(2\theta)/g$ — only valid when launch and landing heights are equal.

<!-- card-id: card-f9cca077-3167-4a68-91f0-ddee07a81310 -->
<!-- card-alias: 857f5028a3a373279bbbd18541bb6511cab9eff49a864b5330d2ed8f991f6f4c -->
Q: A problem gives projectile launch from a cliff (lands below launch point). Why can't you use $R = v_0^2 \sin(2\theta)/g$?
A: It assumes equal launch/landing height. Use full $y(t)$ equation, solve for $t$ when $y$ = landing height, then $x = v_{0x} t$.

<!-- card-id: card-04368742-d420-445e-b90b-ab8dbc0551f0 -->
<!-- card-alias: 0fd6324287fe717c41f07b11fa882c1f90207ead799be38e5cd0ac9f34f4fc4b -->
Q: A problem gives constant speed in a circle and asks for the force needed. What technique?
A: Centripetal: $F_{net} = m v^2 / r$ directed toward center. Identify which real force(s) provide it.

## 4.6 Non-Uniform Circular Motion

<!-- card-id: card-23320c57-e176-411f-89d2-78a46b99a0f9 -->
<!-- card-alias: 3f5874c9232292e1383680ee13c2d3adfd3a025ee043a0670b296965579ab94c -->
Q: What is the difference between centripetal and tangential acceleration in circular motion?
A: Centripetal acceleration $a_c=v^2/r$ points inward and changes velocity's direction. Tangential acceleration has signed component $a_t=dv/dt$: it points with the velocity when speeding up and against it when slowing down.

<!-- card-id: card-5f5a300d-e909-49e2-86d5-74d72af509d1 -->
<!-- card-alias: f16b05b95fae552722412c075e23d1946049f2521ecbfcd704fc5866f5215132 -->
C: The total acceleration magnitude in non-uniform circular motion is $a = [\sqrt{a_c^2 + a_t^2}]$, where $a_c = v^2/r$ is the centripetal component and $a_t = |dv/dt|$ is the tangential component.

## 4.7 Relative Motion (Galilean)

<!-- card-id: card-66df1648-e064-475b-9fae-335da944e37f -->
<!-- card-alias: 66fc5d781ae2c666223022117610914ab6cd52536bc5d1fc5843183626ec54ec -->
Q: What does "velocity of A relative to C" mean?
A: It is the velocity of object A as measured by an observer moving with frame C, i.e., how fast and in what direction A appears to move to someone at rest in C.

<!-- card-id: card-6070299c-ec80-4bcb-84ba-61b71149300c -->
<!-- card-alias: b01a1aac3ff097483bcf55016fc288b4b4eb589e633b4bedc3caa8d84a47aa4f -->
C: Galilean velocity addition: $\vec{v}_{A/C} = [\vec{v}_{A/B} + \vec{v}_{B/C}]$, where $\vec{v}_{A/B}$ is the velocity of A relative to B and $\vec{v}_{B/C}$ is the velocity of B relative to C.

<!-- card-id: card-345f1ace-e533-4b2e-b1d0-7f25fa26b3fa -->
<!-- card-alias: 4ac90487b55f2f57937bae45df60d8ef7799cd7dae77fe6251867b2776810ce4 -->
Q: A boat heads north at 5 m/s relative to still water. The river flows east at 3 m/s. What is the boat's velocity relative to the ground?
A: $\vec{v}_{boat/ground} = \vec{v}_{boat/water} + \vec{v}_{water/ground} = 5\hat{j} + 3\hat{i}$ m/s. Magnitude $= \sqrt{25+9} = \sqrt{34} \approx 5.8$ m/s at an angle $\arctan(3/5) \approx 31°$ east of north.

## 4.8 Worked Example — Projectile Range

<!-- card-id: card-e17884dc-dc96-42b6-a2a0-cca9f77b6120 -->
<!-- card-alias: cf947976de23159afc985eac99466439923eadcfac93226d69a21340e8bd0686 -->
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
