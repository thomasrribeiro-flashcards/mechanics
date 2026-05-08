+++
order = 2
tags = ["mechanics", "physics", "vectors", "math", "dot product", "cross product"]
+++

# Classical Mechanics — Vectors

## 2.1 Scalars vs Vectors

Q: Why do physicists distinguish scalars from vectors?
A: Many physical quantities (force, velocity, displacement) have a direction that affects how they combine. Treating them as pure numbers would give wrong results; the direction must be tracked explicitly.

Q: What is a scalar quantity?
A: A quantity fully described by a magnitude alone, with no direction. Examples: mass, temperature, speed, energy.

Q: What is a vector quantity?
A: A quantity that has both magnitude and direction. Examples: velocity, force, displacement, acceleration.

C: A scalar has [magnitude only], while a vector has both magnitude and [direction].

Q: What is the parallelogram rule for vector addition?
A: Place the two vectors tail-to-tail. The diagonal of the parallelogram formed by the two vectors is their vector sum.

C: The notation $\vec{v}$ or $\hat{v}$ is used for vectors, where $\hat{v}$ specifically denotes a [unit vector] (magnitude = 1).

## 2.2 Cartesian Components

Q: Why decompose a vector into Cartesian components?
A: Component form replaces geometric constructions with algebra, making calculations systematic and exact regardless of the angle.

C: A vector in 3D is written $\vec{A} = A_x\hat{i} + A_y\hat{j} + A_z\hat{k}$, where $\hat{i}, \hat{j}, \hat{k}$ are [unit vectors] along the $x$, $y$, and $z$ axes.

C: For a vector at angle $\theta$ from the $x$-axis, the $x$-component is $A_x = [A\cos\theta]$, where $A$ is the magnitude.

C: For a vector at angle $\theta$ from the $x$-axis, the $y$-component is $A_y = [A\sin\theta]$, where $A$ is the magnitude.

C: The magnitude of a 2D vector with components $A_x$ and $A_y$ is $A = [\sqrt{A_x^2 + A_y^2}]$.

Q: How do you find the angle $\theta$ a 2D vector makes with the positive $x$-axis?
A: $\theta = \arctan(A_y / A_x)$, where $A_y$ is the $y$-component and $A_x$ is the $x$-component. Use the quadrant of $(A_x, A_y)$ to resolve the ambiguity.

## 2.3 Vector Addition

Q: Why is the component method more reliable than the graphical (tip-to-tail) method for vector addition?
A: Graphical methods depend on accurate drawing and measurement, introducing geometric errors. Component addition is exact arithmetic.

Q: How do you add two vectors $\vec{A}$ and $\vec{B}$ using components?
A: Add corresponding components: $\vec{A} + \vec{B} = (A_x + B_x)\hat{i} + (A_y + B_y)\hat{j} + (A_z + B_z)\hat{k}$.

Q: What is the tip-to-tail (triangle) method for vector addition?
A: Place the tail of $\vec{B}$ at the tip of $\vec{A}$. The vector from the tail of $\vec{A}$ to the tip of $\vec{B}$ is $\vec{A} + \vec{B}$.

C: Vector subtraction is defined as adding the [negative] of the second vector: $\vec{A} - \vec{B} = \vec{A} + (-\vec{B})$.

## 2.4 Scalar (Dot) Product

Q: Before defining the dot product: predict what kind of operation extracts "how much of $\vec{A}$ points along $\vec{B}$"?
A: A scalar-valued projection; for perpendicular vectors it should be zero, for parallel it should be $|\vec{A}||\vec{B}|$. That's the dot product.

Q: Why is the dot product useful in physics?
A: It extracts the component of one vector along another. Work is $W = \vec{F}\cdot\vec{d}$, capturing only the force component in the direction of motion.

C: The dot product $\vec{A}\cdot\vec{B} = AB\cos\theta$, where $A$ and $B$ are the magnitudes, and $\theta$ is [the angle between the two vectors].

C: In component form, $\vec{A}\cdot\vec{B} = [A_xB_x + A_yB_y + A_zB_z]$.

Q: What is the result type of a dot product?
A: A scalar (a pure number, not a vector).

Q: When is the dot product of two vectors zero?
A: When the two vectors are perpendicular ($\theta = 90°$), so $\cos 90° = 0$.

C: The dot product is [commutative]: $\vec{A}\cdot\vec{B} = \vec{B}\cdot\vec{A}$.

C: $\vec{A}\cdot\vec{A} = [A^2]$, where $A$ is the magnitude of $\vec{A}$.

## 2.5 Vector (Cross) Product

Q: Why is the cross product useful in physics?
A: It produces a vector perpendicular to both inputs, capturing rotational or torsional effects. Torque is $\vec{\tau} = \vec{r}\times\vec{F}$, where $\vec{r}$ is the position vector and $\vec{F}$ is the force.

C: The magnitude of the cross product is $|\vec{A}\times\vec{B}| = [AB\sin\theta]$, where $A$ and $B$ are magnitudes and $\theta$ is the angle between the vectors.

Q: What is the direction of $\vec{A}\times\vec{B}$?
A: Perpendicular to both $\vec{A}$ and $\vec{B}$, determined by the right-hand rule: curl the fingers of the right hand from $\vec{A}$ toward $\vec{B}$; the thumb points in the direction of the cross product.

C: The cross product is [anticommutative]: $\vec{A}\times\vec{B} = -(\vec{B}\times\vec{A})$.

Q: When is the cross product of two vectors zero?
A: When the vectors are parallel (or anti-parallel), so $\theta = 0°$ or $180°$ and $\sin\theta = 0$.

Q: How is the cross product computed using the determinant formula?
A: $$\vec{A}\times\vec{B} = \begin{vmatrix}\hat{i} & \hat{j} & \hat{k} \\ A_x & A_y & A_z \\ B_x & B_y & B_z\end{vmatrix} = (A_yB_z - A_zB_y)\hat{i} - (A_xB_z - A_zB_x)\hat{j} + (A_xB_y - A_yB_x)\hat{k}$$

## 2.6 Unit Vectors and Decomposition

Q: What is a unit vector?
A: A vector with magnitude equal to 1, used to specify direction only.

C: The unit vector in the direction of $\vec{A}$ is $\hat{A} = [\vec{A}/A]$, where $A = |\vec{A}|$ is the magnitude.

Q: Why write any vector as magnitude times unit vector?
A: It cleanly separates the "how much" (magnitude) from the "which way" (unit vector), making direction and size independently clear.

Q: What are the radial and tangential unit vectors in polar coordinates?
A: $\hat{r}$ points outward from the origin along the radial direction; $\hat{\theta}$ points perpendicular to $\hat{r}$ in the direction of increasing angle $\theta$.

## 2.7 Worked Example — Vector Operations

P: Given $\vec{A} = 3\hat{i} - 4\hat{j}$ and $\vec{B} = -\hat{i} + 2\hat{j}$, find: (a) $|\vec{A}|$, (b) $\vec{A} + \vec{B}$, (c) $\vec{A}\cdot\vec{B}$.

S:
**IDENTIFY**: Vector magnitude, vector addition, and dot product.

**PLAN**:
- Magnitude: $|\vec{A}| = \sqrt{A_x^2 + A_y^2}$
- Addition: add $x$- and $y$-components separately
- Dot product: $\vec{A}\cdot\vec{B} = A_xB_x + A_yB_y$

**EXECUTE**:

(a) $|\vec{A}| = \sqrt{3^2 + (-4)^2} = \sqrt{9 + 16} = \sqrt{25} = 5$

(b) $\vec{A} + \vec{B} = (3 + (-1))\hat{i} + (-4 + 2)\hat{j} = 2\hat{i} - 2\hat{j}$

(c) $\vec{A}\cdot\vec{B} = (3)(-1) + (-4)(2) = -3 - 8 = -11$

**EVALUATE**:
- Magnitude is positive: $|\vec{A}| = 5$ ✓ (a 3-4-5 right triangle)
- Sum is a vector, dot product is a scalar — types are consistent ✓
- Negative dot product confirms the angle between $\vec{A}$ and $\vec{B}$ is greater than 90°
