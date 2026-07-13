+++
order = 5
subject = "physics"
tags = ["mechanics", "physics", "newton", "forces", "dynamics", "inertia"]
+++

# Classical Mechanics — Newton's Laws of Motion

## 5.1 What is a Force?

Q: What is a force in the context of Newtonian mechanics?
A: A force is an interaction between two objects (or between an object and a field) that can produce an acceleration — i.e., change the object's velocity. Forces are vector quantities with both magnitude and direction.

Q: What distinguishes contact forces from field forces?
A: Contact forces (normal force, friction, tension, spring force) require physical touching between surfaces. Field forces (gravity, electrostatic, magnetic) act at a distance through fields without direct contact.

C: The SI unit of force is the [newton (N)], defined as $1\,\text{N}=1\,\text{kg}\cdot\text{m}/\text{s}^2$.

C: The net force on an object is the [vector sum] of all individual forces acting on it.

## 5.2 Newton's First Law — Law of Inertia

Q: A puck moves at constant velocity across an ideal frictionless surface. Must a forward net force keep it moving?
A: No. Constant velocity requires zero net force; a nonzero forward net force would make the puck accelerate.

Q: State Newton's First Law.
A: An object at rest remains at rest, and an object moving at constant velocity continues to move at that constant velocity, unless acted upon by a net external force.

C: Newton's First Law defines the concept of [inertia] — the tendency of an object to resist any change in its state of motion.

Q: What is an inertial reference frame?
A: A frame in which a force-free object moves at constant velocity. Frames moving at constant velocity without rotation relative to an inertial frame are also inertial; accelerating or rotating frames are not.

## 5.3 Inertial vs Non-Inertial Reference Frames

Q: Why do fictitious forces appear in non-inertial frames?
A: The frame itself accelerates, so a force-free object appears to accelerate relative to it. Newton's law can retain its usual form only by adding inertial terms, such as $-m\vec a_{frame}$ for a translating frame and centrifugal/Coriolis terms for a rotating frame.

C: Examples of fictitious forces in non-inertial frames are the [centrifugal force] (rotating frame) and the [Coriolis force] (rotating frame).

Q: Is Earth's surface a perfect inertial frame?
A: No — Earth rotates, introducing small Coriolis and centrifugal effects. For most laboratory mechanics problems these are negligible, so Earth's surface is treated as approximately inertial.

## 5.4 Newton's Second Law

Q: Why is mass the measure of inertia in Newton's Second Law?
A: The same net force produces less acceleration on a more massive object. Mass quantifies how strongly an object resists changes in velocity; a larger mass requires a larger force to produce the same acceleration.

C: For a constant-mass object, Newton's Second Law is $\vec{F}_{net} = [m\vec{a}]$, where $\vec{F}_{net}$ is the vector sum of all external forces.

C: In component form, Newton's Second Law gives $\sum F_x = [ma_x]$ and $\sum F_y = [ma_y]$, where $m$ is mass (kg) and $a_x$, $a_y$ are the components of acceleration (m/s²).

Q: What is the direction of the acceleration produced by a net force?
A: The acceleration is in the same direction as the net force. If multiple forces act, you must find their vector sum first.

Q: What happens when the net force on an object is zero?
A: The acceleration is zero. The object either remains at rest or continues at constant velocity (Newton's First Law is the special case $\vec{F}_{net} = 0$ of the Second Law).

## 5.5 Newton's Third Law — Action and Reaction

Q: State Newton's Third Law precisely.
A: If object A exerts a force $\vec{F}_{A\to B}$ on object B, then object B simultaneously exerts a force $\vec{F}_{B\to A} = -\vec{F}_{A\to B}$ on object A — equal in magnitude, opposite in direction.

Q: Why don't Newton's Third Law pairs cancel each other out?
A: The two forces act on different objects. When analyzing a single object (free body diagram), you only include forces acting on that object. The reaction force acts on the other object and never appears in the same FBD.

C: Newton's Third Law force pairs always involve [two different objects] and are always the same type of force (both gravitational, both normal, etc.).

Q: Give an example of a Newton's Third Law pair.
A: When you push a wall with force $\vec{F}$, the wall pushes back on your hand with force $-\vec{F}$. Both forces are normal (contact) forces, equal in magnitude, opposite in direction, and acting on different bodies.

## 5.6 Free Body Diagrams

Q: What is the purpose of a free body diagram (FBD)?
A: To isolate a single object and show every force acting on it, making it clear what to include in $\sum\vec{F} = m\vec{a}$. It prevents including forces that the object exerts on others, which would be wrong.

Q: What is rule 1 of drawing a free body diagram?
A: Isolate one object — show only forces acting *on* it, never forces it exerts on others.

Q: What is rule 2 of drawing a free body diagram?
A: Draw one arrow for every external force acting on the object and label its type or symbol. Unknown magnitudes remain symbolic.

Q: What is rule 3 of drawing a free body diagram?
A: Choose convenient coordinate axes—often along a surface, constraint, or known acceleration—to minimize component algebra.

C: A free body diagram shows only forces acting on the object of interest, not forces [it exerts on other objects].

## 5.7 Applying Newton's Second Law — Strategy

Q: A problem gives a block on an incline with friction; asks for acceleration. What's your first step?
A: Free body diagram of the block, axes parallel/perpendicular to the incline.

Q: What is the systematic procedure for applying Newton's Second Law to a problem?
A: Define the system, draw its FBD, choose convenient axes, resolve forces, write $\sum F_i=ma_i$ for each axis, then solve and check signs and constraints.

## 5.8 Worked Example — Block on a Frictionless Incline

P: A block of mass $m = 5$ kg is released on a frictionless incline of angle $\theta = 30°$. Find its acceleration down the incline and the normal force. Use $g = 10$ m/s².

S:
**IDENTIFY**: Newton's second law applied to a block on an incline. Two forces: weight $\vec{W} = mg$ downward and normal force $\vec{N}$ perpendicular to the surface. No friction.

**PLAN**:
- Choose axes: $x$ along the incline (positive downhill), $y$ perpendicular to incline (positive away from surface).
- Decompose weight: $W_x = mg\sin\theta$ (down the incline), $W_y = -mg\cos\theta$ (into surface).
- Normal force: $N$ in the $+y$ direction.
- Apply $\sum F_x = ma_x$ and $\sum F_y = 0$ (no acceleration perpendicular to surface).

**EXECUTE**:

Along incline ($x$): $mg\sin\theta = ma$
$$a = g\sin\theta = 10 \times \sin 30° = 10 \times 0.5 = 5 \text{ m/s}^2$$

Perpendicular to incline ($y$): $N - mg\cos\theta = 0$
$$N = mg\cos\theta = 5 \times 10 \times \cos 30° = 50 \times \frac{\sqrt{3}}{2} \approx 43.3 \text{ N}$$

**EVALUATE**:
- If $\theta = 0°$ (flat): $a = 0$ and $N = mg = 50$ N ✓ (no motion, full weight supported)
- If $\theta = 90°$ (vertical wall): $a = g = 10$ m/s² (free fall) and $N = 0$ ✓
- Acceleration $5$ m/s² is half of $g$ — sensible for $30°$ ✓
- Normal force ($43.3$ N) $< mg = 50$ N — the incline supports less than full weight ✓
