+++
order = 5
subject = "physics"
tags = ["mechanics", "physics", "newton", "forces", "dynamics", "inertia"]
+++

# Classical Mechanics — Newton's Laws of Motion

## 5.1 What is a Force?

<!-- card-id: card-be484e6f-bda6-40fb-9c2a-fba9fc0f37f1 -->
<!-- card-alias: b012c35b7fdbebc8f2c99e997678f2561329a0c51c484b50297fa4ffe17ce7c2 -->
Q: What is a force in the context of Newtonian mechanics?
A: A force is an interaction between two objects (or between an object and a field) that can produce an acceleration — i.e., change the object's velocity. Forces are vector quantities with both magnitude and direction.

<!-- card-id: card-07d5481c-4e16-41e8-90cc-975b1f5000d2 -->
<!-- card-alias: 557a78ee09ef56edef70afe503182e16d938ad503e9fe37764b603016179a5d2 -->
Q: What distinguishes contact forces from field forces?
A: Contact forces (normal force, friction, tension, spring force) require physical touching between surfaces. Field forces (gravity, electrostatic, magnetic) act at a distance through fields without direct contact.

<!-- card-id: card-cadfe648-1f5d-48b5-b6e2-9eff2124a1b9 -->
<!-- card-alias: c861493a73c610530a438ce1fb061ff8d4b4ee14cc1abc63491f9b117729eb13 -->
C: The SI unit of force is the [newton (N)], defined as $1\,\text{N}=1\,\text{kg}\cdot\text{m}/\text{s}^2$.

<!-- card-id: card-65889928-885a-455f-a12f-5bace59058b0 -->
<!-- card-alias: ceefad7eb2dc88c2eb34169ba4103dec23c0fbd8c02796ef830c2e06161aaa06 -->
C: The net force on an object is the [vector sum] of all individual forces acting on it.

## 5.2 Newton's First Law — Law of Inertia

<!-- card-id: card-d8bd7415-102f-423f-86f9-2ebc4e83f5cd -->
<!-- card-alias: f146409fa652a17c7192ff9b2d7e689f74dfe23545e5e85ab3583623abd0c1c2 -->
Q: A puck moves at constant velocity across an ideal frictionless surface. Must a forward net force keep it moving?
A: No. Constant velocity requires zero net force; a nonzero forward net force would make the puck accelerate.

<!-- card-id: card-eedc4d1e-6957-4c55-8b18-9caa7f3a4514 -->
<!-- card-alias: dd34b472ad12da71c7860223a6f4e6894f75e17dfd660bdebbfee68102d46e36 -->
Q: State Newton's First Law.
A: An object at rest remains at rest, and an object moving at constant velocity continues to move at that constant velocity, unless acted upon by a net external force.

<!-- card-id: card-5acc402e-ef98-4d65-80b4-948e9d82b19b -->
<!-- card-alias: c2dfcd7ccf137414a3c013e005fde94ff93fb35df60da3ad76ef843e70e9b6de -->
C: Newton's First Law defines the concept of [inertia] — the tendency of an object to resist any change in its state of motion.

<!-- card-id: card-9efb49ad-0419-4347-8d23-9f4bfa7b5336 -->
<!-- card-alias: f4cf9151590ab80f1f636e66ae4762d352bf9102ea449e1116aa3d4921b26df6 -->
Q: What is an inertial reference frame?
A: A frame in which a force-free object moves at constant velocity. Frames moving at constant velocity without rotation relative to an inertial frame are also inertial; accelerating or rotating frames are not.

## 5.3 Inertial vs Non-Inertial Reference Frames

<!-- card-id: card-1bca02a8-4c98-4339-bb95-cb7990bc7701 -->
<!-- card-alias: 87a81e8ec87e8edeea3108e7735cf3f63d655a022007718afd5ac72a2919ca35 -->
Q: Why do fictitious forces appear in non-inertial frames?
A: The frame itself accelerates, so a force-free object appears to accelerate relative to it. Newton's law can retain its usual form only by adding inertial terms, such as $-m\vec a_{frame}$ for a translating frame and centrifugal/Coriolis terms for a rotating frame.

<!-- card-id: card-3d4cb7b9-ea4f-4303-a984-484e352b63e6 -->
<!-- card-alias: b783ee9b34878c0dc61eec4675aeba72a55f53ed712720698232c7ca268dc4f5 -->
<!-- card-alias: f418ab3047a00b27a389821cda6ce53c790edc829002df4d8e7c84c29d381159 -->
C: Examples of fictitious forces in non-inertial frames are the [centrifugal force] (rotating frame) and the [Coriolis force] (rotating frame).

<!-- card-id: card-bf7a8d17-be10-4a70-be67-39fcef0dfd75 -->
<!-- card-alias: 14d653c24372bd0dbe3f750f002691137042452334509a5424f548ce4d68bba4 -->
Q: Is Earth's surface a perfect inertial frame?
A: No — Earth rotates, introducing small Coriolis and centrifugal effects. For most laboratory mechanics problems these are negligible, so Earth's surface is treated as approximately inertial.

## 5.4 Newton's Second Law

<!-- card-id: card-ff6afb5b-6fd1-4980-8c0d-d4f207eddcb3 -->
<!-- card-alias: 3cd056ac3cc7bcc287840237973304dc7d78b563c9eaeacb9d0228f6cb602659 -->
Q: Why is mass the measure of inertia in Newton's Second Law?
A: The same net force produces less acceleration on a more massive object. Mass quantifies how strongly an object resists changes in velocity; a larger mass requires a larger force to produce the same acceleration.

<!-- card-id: card-51f3b4b2-5a49-43c2-906a-9d267c812f76 -->
<!-- card-alias: 2e7cb57a8b4e0c785a14d95a76ed4be4b88b38ccdd919c08befb4bd224d490ba -->
C: For a constant-mass object, Newton's Second Law is $\vec{F}_{net} = [m\vec{a}]$, where $\vec{F}_{net}$ is the vector sum of all external forces.

<!-- card-id: card-910c6e3d-f278-47c7-94be-8f8de8c3867b -->
<!-- card-alias: 163b1cfa2781c304fb91075a7cd820c5a864d219903592c84f337d4f38767de7 -->
<!-- card-alias: c3e5ac682fd5d097775f574610a54a47c8f487a11b73a656c91a6fd0d7deac72 -->
C: In component form, Newton's Second Law gives $\sum F_x = [ma_x]$ and $\sum F_y = [ma_y]$, where $m$ is mass (kg) and $a_x$, $a_y$ are the components of acceleration (m/s²).

<!-- card-id: card-c8bdd58f-80ac-42fa-a701-660a886fa874 -->
<!-- card-alias: 65b68d88aad4cde13fa58b5982b8defa8983797bf7537f675bd5146657685ea5 -->
Q: What is the direction of the acceleration produced by a net force?
A: The acceleration is in the same direction as the net force. If multiple forces act, you must find their vector sum first.

<!-- card-id: card-ef6c8ecd-9080-4964-a9eb-1b696f24962c -->
<!-- card-alias: dd6dc06b87544a5240ba6ed8f6752c97b6586a3bda6a3041441cf48afb56daa5 -->
Q: What happens when the net force on an object is zero?
A: The acceleration is zero. The object either remains at rest or continues at constant velocity (Newton's First Law is the special case $\vec{F}_{net} = 0$ of the Second Law).

## 5.5 Newton's Third Law — Action and Reaction

<!-- card-id: card-199d767b-fde3-473f-a167-f6a36266819d -->
<!-- card-alias: 1ef751a40a165d1e8e7c80d0a05b4f869f2664781b3489c30ec722a09d6d6a2d -->
Q: State Newton's Third Law precisely.
A: If object A exerts a force $\vec{F}_{A\to B}$ on object B, then object B simultaneously exerts a force $\vec{F}_{B\to A} = -\vec{F}_{A\to B}$ on object A — equal in magnitude, opposite in direction.

<!-- card-id: card-0e9629c1-b194-415e-8b79-43f3aeae2b79 -->
<!-- card-alias: 6d7baad3a1a94039d04680631d794e6fe55d6334df5d673f43fce061b7a682a9 -->
Q: Why don't Newton's Third Law pairs cancel each other out?
A: The two forces act on different objects. When analyzing a single object (free body diagram), you only include forces acting on that object. The reaction force acts on the other object and never appears in the same FBD.

<!-- card-id: card-2649f939-b2b6-4e49-adfe-42ef0b3b2f8c -->
<!-- card-alias: 3e657970520bd027ea5696a0c37efdf3d5a76257088ca4fee6a77a429359969f -->
C: Newton's Third Law force pairs always involve [two different objects] and are always the same type of force (both gravitational, both normal, etc.).

<!-- card-id: card-ae5eac61-b092-4d0e-be75-f79fb096d36b -->
<!-- card-alias: 0b0de945ebfea44371827e2078416d04cd22f8fb2fea68ff4f57bf0d3d27f8bc -->
Q: Give an example of a Newton's Third Law pair.
A: When you push a wall with force $\vec{F}$, the wall pushes back on your hand with force $-\vec{F}$. Both forces are normal (contact) forces, equal in magnitude, opposite in direction, and acting on different bodies.

## 5.6 Free Body Diagrams

<!-- card-id: card-125876c1-156b-4852-9fdf-fd783a325dbf -->
<!-- card-alias: 49ce95b4c4f6c6903f2a82faa93b82bee8d18b3026ed999ccd19d92d0f2d0282 -->
Q: What is the purpose of a free body diagram (FBD)?
A: To isolate a single object and show every force acting on it, making it clear what to include in $\sum\vec{F} = m\vec{a}$. It prevents including forces that the object exerts on others, which would be wrong.

<!-- card-id: card-162f5937-535e-4014-a601-30d832e0d377 -->
<!-- card-alias: 8876516700d2ce53bff5e54f60fc1e1fd08fa8ec70f4ca9e6a9988dbc2d50fb2 -->
Q: What is rule 1 of drawing a free body diagram?
A: Isolate one object — show only forces acting *on* it, never forces it exerts on others.

<!-- card-id: card-77610542-fad5-42be-a496-ced2c8269a93 -->
<!-- card-alias: 0a481d4353d6e5798c93073f4a9033f6df3609c7beabdc191c65bef6500d9446 -->
Q: What is rule 2 of drawing a free body diagram?
A: Draw one arrow for every external force acting on the object and label its type or symbol. Unknown magnitudes remain symbolic.

<!-- card-id: card-7e1e76d9-4bab-4508-98f5-719288a507c5 -->
<!-- card-alias: acd5c1045675b6f6082e3d08544949bdeeb9028441ae8babbcad58042ad83564 -->
Q: What is rule 3 of drawing a free body diagram?
A: Choose convenient coordinate axes—often along a surface, constraint, or known acceleration—to minimize component algebra.

<!-- card-id: card-2b90e350-81c3-4cb5-81e6-49b59fed71c5 -->
<!-- card-alias: 3138059863d3891e3026e04addb974a0797d02f93e62c7f20d51e0733f0e17a5 -->
C: A free body diagram shows only forces acting on the object of interest, not forces [it exerts on other objects].

## 5.7 Applying Newton's Second Law — Strategy

<!-- card-id: card-a62d4a89-eecb-4a85-8a3b-b5c0352967f9 -->
<!-- card-alias: f3fce751f51c4316adab677bc1969ff2617b9b383c461f37ea8fd9f46ee87c5d -->
Q: A problem gives a block on an incline with friction; asks for acceleration. What's your first step?
A: Free body diagram of the block, axes parallel/perpendicular to the incline.

<!-- card-id: card-2e3d1b0e-a470-4baa-a356-ebc229405739 -->
<!-- card-alias: b75fa86907ae23c76c74cb0fd29a6537bdcb9d48013541e19adbdc33085362a0 -->
Q: What is the systematic procedure for applying Newton's Second Law to a problem?
A: Define the system, draw its FBD, choose convenient axes, resolve forces, write $\sum F_i=ma_i$ for each axis, then solve and check signs and constraints.

## 5.8 Worked Example — Block on a Frictionless Incline

<!-- card-id: card-063c09e0-a602-4bd3-b5cd-3234e36fda81 -->
<!-- card-alias: df386f9cbe00c97229de8a06a39f4bfe6b5abdca076ca10fa6d2e138f8517113 -->
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
