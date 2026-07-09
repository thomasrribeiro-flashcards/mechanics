+++
order = 6
subject = "Physics"
tags = ["mechanics", "physics", "forces", "friction", "gravity", "tension", "springs", "drag"]
+++

# Classical Mechanics — Common Forces

## 6.1 Weight

Q: What is weight, and how does it differ from mass?
A: Weight is the gravitational force exerted on an object by Earth (or another astronomical body) — it is a force, measured in Newtons. Mass is the intrinsic measure of inertia, measured in kilograms. Mass is the same everywhere; weight depends on local gravitational acceleration $g$.

C: Weight is $W = [mg]$ directed downward, where $m$ is mass (kg) and $g$ is local gravitational acceleration (m/s²; $g \approx 9.8$ m/s² near Earth's surface).

Q: Why does weight change on the Moon but mass does not?
A: Mass is an intrinsic property of the object (amount of matter). Weight $W = mg$ depends on $g$, which is $\approx 1.6$ m/s² on the Moon versus $9.8$ m/s² on Earth. A 70 kg person weighs $\approx 686$ N on Earth and $\approx 112$ N on the Moon, but their mass is 70 kg in both places.

## 6.2 Normal Force

Q: What is the normal force and why is it called "normal"?
A: The normal force is a contact force that a surface exerts on an object perpendicular to the surface. "Normal" is the geometric term for perpendicular — the force is always perpendicular (normal) to the contact surface.

Q: Why is the normal force not always equal to $mg$?
A: The normal force adjusts to whatever value is needed to prevent the object from penetrating the surface — it satisfies $\sum F_{\perp} = 0$ (or $ma_{\perp}$ if accelerating). On a horizontal surface at rest $N = mg$, on an incline $N = mg\cos\theta$, and in an elevator accelerating upward at $a$, $N = m(g + a)$.

C: For a block at rest on a horizontal surface, the normal force is $N = [mg]$, where $m$ is mass (kg) and $g$ is gravitational acceleration (m/s²).

C: For a block on a frictionless incline at angle $\theta$, the normal force is $N = [mg\cos\theta]$, where $m$ is mass, $g$ is gravitational acceleration, and $\theta$ is the incline angle.

## 6.3 Tension

Q: What is tension and in which direction does it act on an object?
A: Tension is the pulling force exerted by a taut string, rope, or cable along its length. It acts away from the object toward the string — tension can only pull, never push.

C: For a massless inextensible string, the tension magnitude is [the same throughout] the entire string, regardless of the string's shape.

Q: How does a massless frictionless pulley affect tension in a rope?
A: It changes only the direction of the rope (and thus the direction the tension pulls), but does not change the magnitude of the tension. The same tension acts throughout both segments of the rope.

Q: Why can a string not push?
A: A string can only be taut (under tension) or slack. When compressed, a string simply goes slack and exerts zero force. To push, a rigid rod or spring is needed.

## 6.4 Static Friction

Q: What is static friction and when does it act?
A: Static friction is a contact force that acts between two surfaces that are stationary relative to each other. It opposes the tendency of the surfaces to slide and adjusts its magnitude to prevent relative motion.

C: Static friction satisfies $f_s \leq [\mu_s N]$, where $\mu_s$ is the dimensionless coefficient of static friction and $N$ is the normal force. The friction force equals whatever is needed, up to this maximum.

Q: What determines the maximum value of static friction?
A: The maximum static friction force is $f_{s,max} = \mu_s N$, where $\mu_s$ is the coefficient of static friction (dimensionless, depends on the material pair) and $N$ is the normal force (N). Once applied force exceeds this maximum, the surfaces begin to slide.

Q: Why does static friction have no fixed value until the maximum is reached?
A: Static friction is a reaction force. It adjusts to exactly match the applied tangential force until the applied force exceeds $\mu_s N$. Below that threshold, the friction force is self-adjusting, not fixed at $\mu_s N$.

## 6.5 Kinetic Friction

Q: How does kinetic friction differ from static friction?
A: Kinetic friction acts between surfaces already sliding relative to each other. Unlike static friction (which is self-adjusting), kinetic friction has a fixed magnitude $f_k = \mu_k N$ independent of speed (for most surfaces) and always opposes the direction of sliding.

C: Kinetic friction is $f_k = [\mu_k N]$, where $\mu_k$ is the coefficient of kinetic friction (dimensionless) and $N$ is the normal force (N).

C: The coefficient of kinetic friction is always [less than] the coefficient of static friction for the same surface pair: $\mu_k < \mu_s$.

Q: Why does $\mu_k < \mu_s$ (kinetic friction is less than maximum static friction)?
A: When surfaces are stationary, surface asperities (microscopic bumps) can interlock more deeply. Once sliding begins, contact time is shorter, fewer asperities engage simultaneously, so the resistive force is smaller.

Q: In which direction does kinetic friction act?
A: Always opposite to the velocity of the sliding surface — it opposes relative motion between the surfaces.

## 6.6 Hooke's Law

Q: What is Hooke's Law and under what condition is it valid?
A: For a spring displaced from its natural length, the restoring force is proportional to the displacement: $F_s = -kx$. It is valid within the elastic limit — if stretched or compressed beyond this, the spring deforms permanently and Hooke's Law breaks down.

C: Hooke's Law: $F_s = [-kx]$, where $k$ is the spring constant (N/m, larger $k$ = stiffer spring), $x$ is the displacement from the natural length (m), and the negative sign means the force is a [restoring force] opposing the displacement.

Q: What does a large spring constant $k$ mean physically?
A: A large $k$ means a stiff spring — a given displacement requires a larger force (or equivalently, a given force produces a smaller displacement). Units of $k$ are N/m.

C: Two springs in series have an effective spring constant $1/k_{eff} = [1/k_1 + 1/k_2]$, where $k_1$ and $k_2$ are the individual spring constants (N/m). The combined spring is softer than either alone.

C: Two springs in parallel have an effective spring constant $k_{eff} = [k_1 + k_2]$, where $k_1$ and $k_2$ are the individual spring constants (N/m). The combined spring is stiffer than either alone.

## 6.6a Pattern Recognition: Friction

Q: A problem says "block is at rest on rough surface, what's the friction force?" What's your first move?
A: Check applied tangential force. Static friction equals it (up to $\mu_s N$); only the maximum is $\mu_s N$, not the actual value.

Q: A problem says "block sliding on rough surface, find acceleration." What technique?
A: Kinetic friction: $f_k = \mu_k N$ (fixed, opposing velocity). Then $\sum F = ma$.

Q: A problem asks "what is the maximum push force before the block slides?" What technique?
A: Set applied force = $\mu_s N$ — the threshold where static friction maxes out and slipping starts.

## 6.7 Drag and Terminal Velocity

Q: What is drag force, and in which direction does it act?
A: Drag is the resistive force exerted by a fluid (air or liquid) on a moving object. It always acts opposite to the object's velocity relative to the fluid, because it arises from the fluid pushing back on the object as the object pushes fluid out of the way.

Q: How does the high-speed (quadratic) drag force depend on speed?
A: $F_d = \frac{1}{2}C_d\rho A v^2$, where $C_d$ is the dimensionless drag coefficient (shape-dependent), $\rho$ is the fluid density (kg/m³), $A$ is the object's cross-sectional area perpendicular to the motion (m²), and $v$ is its speed (m/s). Because $F_d \propto v^2$, doubling speed quadruples drag.

Q: What is terminal velocity and how is it reached?
A: Terminal velocity is the constant speed reached when the drag force grows to equal the gravitational force: $F_d = mg$, so net force $= 0$ and acceleration $= 0$. The object falls (or moves) at constant velocity from that point on.

C: At terminal velocity, the condition $[mg = F_d]$ holds, where $mg$ is the weight (N) and $F_d$ is the drag force (N), giving zero net force and zero acceleration.

Q: Why do heavier objects have a higher terminal velocity than lighter objects of the same shape?
A: Terminal velocity is reached when $F_d = mg$. In the high-speed drag regime, $F_d = \frac{1}{2}C_d\rho A v_t^2$, so $v_t = \sqrt{2mg/(C_d\rho A)}$. A larger mass $m$ requires a higher speed $v_t$ before drag can balance weight.

## 6.8 Worked Example — Box on Rough Floor

P: A 10 kg box is pushed along a horizontal floor with a horizontal force $F = 50$ N. The coefficient of kinetic friction is $\mu_k = 0.3$ and $g = 10$ m/s². Find the acceleration of the box.

S:
**IDENTIFY**: Newton's second law in 1D (horizontal). Forces on box: applied force $F$ (horizontal, forward), kinetic friction $f_k$ (horizontal, backward), weight $mg$ (downward), normal force $N$ (upward).

**PLAN**:
- Vertical equilibrium gives $N$.
- Compute $f_k = \mu_k N$.
- Apply $\sum F_x = ma$ horizontally.

**EXECUTE**:

Vertical: $\sum F_y = 0 \implies N - mg = 0 \implies N = mg = 10 \times 10 = 100$ N

Kinetic friction: $f_k = \mu_k N = 0.3 \times 100 = 30$ N (opposing motion)

Horizontal: $\sum F_x = F - f_k = ma$
$$50 - 30 = 10 \times a \implies 20 = 10a \implies a = 2 \text{ m/s}^2$$

**EVALUATE**:
- If $\mu_k = 0$: $a = F/m = 5$ m/s² (frictionless — faster) ✓
- Friction force (30 N) $<$ Applied force (50 N), so the box accelerates forward ✓
- If $F = f_k = 30$ N: $a = 0$ (constant velocity) — consistent ✓
- Units: $[F/m] = \text{N/kg} = \text{kg·m/s}^2/\text{kg} = \text{m/s}^2$ ✓
