+++
order = 11
subject = "physics"
tags = ["mechanics", "physics", "oscillations", "shm", "pendulum"]
+++

# Classical Mechanics — Oscillations

## 11.1 Periodic Motion

<!-- card-id: card-a4eaaa93-3a19-4f2d-b65e-e79f8bdc1a5d -->
<!-- card-alias: b5a821485ef66362ad17a4ff84a3b63badf7b6e62fe72b7aaf75ccbb34d8fb14 -->
Q: What defines periodic motion?
A: Periodic motion repeats after a fixed time $T$, called the period. Frequency is the number of cycles per unit time, so $f=1/T$.

<!-- card-id: card-d91764e7-c093-4ebd-a399-9d9f3fbdc78c -->
<!-- card-alias: ae856ccd1b478223327d1117deae01736bd6448e78c56f6f8eaf38f79705a8b7 -->
Q: How do angular frequency and amplitude describe an oscillation?
A: Angular frequency $\omega=2\pi f$ measures phase advance in radians per second. Amplitude $A$ is the maximum magnitude of displacement from equilibrium.

<!-- card-id: card-6896caa6-b2d0-4178-89af-3eda109233a7 -->
<!-- card-alias: ec2ec0beed4023872f1475b0fe34221ee040a5ba142efe729d8d1b6013c53535 -->
<!-- card-alias: 492e53806dd9261188709ff20413fffd503d820626814b5f445f7f140ce4aea5 -->
C: Period $T$, frequency $f$, and angular frequency $\omega$ are related by $f = 1/T$ and $\omega = [2\pi f] = [2\pi/T]$.

<!-- card-id: card-a3516cb2-0748-4acd-9b5c-b673b7044641 -->
<!-- card-alias: 43b1f97bd9b7bde41b6ee50630b6ff94abdc3723b54d3cf26c5160c9d086928a -->
C: The SI unit of frequency is the [hertz] (Hz), equal to one cycle per second.

## 11.2 SHM Condition

<!-- card-id: card-c0311a82-685e-4ab7-a087-00fe7212afb4 -->
<!-- card-alias: 30e689202ce91401e36829b773ee55f26d17b59bf7a29f79432ad7adbfc69331 -->
Q: What physical condition produces simple harmonic motion (SHM)?
A: A restoring force proportional to displacement: $F = -kx$, where $k > 0$ is a positive constant (the effective stiffness) and $x$ is displacement from equilibrium. The negative sign ensures the force always points back toward equilibrium. This condition is equivalent to the equation of motion $\ddot{x} = -\omega^2 x$ with $\omega^2 = k/m$.

<!-- card-id: card-bf11c957-07dc-4ee3-aaf7-852dbe8c0b1c -->
<!-- card-alias: 9c1aa698032299762d71a6eab3f94045af90986c43e5d5d94ab613f1627dae43 -->
Q: Why is the restoring force criterion $F = -kx$ called a "linear" restoring force?
A: $F$ is linear in displacement $x$ (first power only). This linearity produces pure single-frequency oscillation. Nonlinear restoring forces (e.g., $F \propto -x^3$) produce anharmonic oscillations with multiple frequencies.

<!-- card-id: card-3caeba79-8d7d-475d-9f26-e3bbec60c217 -->
<!-- card-alias: ea1cae29666b90041b124b3ffc992909aaa2ebc41f2d56243eb8f512f4b69795 -->
<!-- card-alias: 2db7dc114433c2e7e3dfb21f7a436d9d9e62d9614fdd797a636b870dd5f6f03e -->
C: SHM requires a restoring force $F = -kx$. The equation of motion becomes $\ddot{x} = [-\omega^2 x]$, where $\omega^2 = [k/m]$.

## 11.3 SHM Solution

<!-- card-id: card-97345d70-a4b1-4e0f-a552-572718086552 -->
<!-- card-alias: f1486d40b8771067f973b54bcb15af9d4f760c222229cc7e670e2d2042a70e2b -->
Q: What is the general solution for position in SHM, and what determines the constants?
A: $x(t) = A\cos(\omega t + \phi)$, where $A$ is the amplitude (m), $\omega = \sqrt{k/m}$ (rad/s), and $\phi$ is the phase constant (rad). Initial conditions determine $A$ and $\phi$: $x(0) = A\cos\phi$ and $\dot{x}(0) = -A\omega\sin\phi$.

<!-- card-id: card-ef2d090e-ef70-4897-8511-bdf31db27d4b -->
<!-- card-alias: 3393e0a2d4f121d70951745a4ce80146f0250df4066a3e3205a0fda4d8e0c1ba -->
Q: A mass on a spring is released from $x_0 = A$ at $t = 0$ with zero velocity. What is $\phi$?
A: $x(0) = A\cos\phi = A$ requires $\cos\phi = 1$, so $\phi = 0$. The solution simplifies to $x(t) = A\cos(\omega t)$, starting at maximum positive displacement.

<!-- card-id: card-85678bbd-51bd-4e1a-b077-05b81532e21b -->
<!-- card-alias: c040fe543dd925be44b87aa4e276eca3ec18e8dc364e6c6bc9f20813fa084ec2 -->
C: The general SHM position is $x(t) = A\cos(\omega t + \phi)$. The amplitude $A$ and phase constant $\phi$ are determined by the [initial conditions] $x(0)$ and $\dot{x}(0)$.

## 11.4 SHM Velocity and Acceleration

<!-- card-id: card-aaec9bf3-9042-4f92-b6a7-53509ea44d30 -->
<!-- card-alias: a2bd54d8ec78bcc5031470347c732079e5602fef50b254f9aace99f908a6fd60 -->
Q: Derive the velocity and acceleration in SHM from $x(t) = A\cos(\omega t + \phi)$.
A: $v(t) = \dot{x} = -A\omega\sin(\omega t + \phi)$. $a(t) = \ddot{x} = -A\omega^2\cos(\omega t + \phi) = -\omega^2 x(t)$. Acceleration is always proportional to $-x$, confirming the SHM condition $a = -\omega^2 x$.

<!-- card-id: card-654f4d76-5360-4e12-833a-7ff6dd8be75d -->
<!-- card-alias: d279c83cdb461b39562bcd918e3d3cb5765d1e48e29c5dfa5d304c3d64e3f203 -->
Q: Where in SHM is the speed maximum, and where is the magnitude of acceleration maximum?
A: Maximum speed $v_{max} = A\omega$ occurs at $x = 0$ (equilibrium), where the restoring force is zero. Maximum acceleration $a_{max} = A\omega^2$ occurs at $x = \pm A$ (turning points), where the restoring force is greatest.

<!-- card-id: card-741f1ae4-a2db-414b-acd0-00cdc302e053 -->
<!-- card-alias: 68dc59b0dce3222f50fd28ec878947c3b4ac350a07fe994328c050b3d535f8c4 -->
<!-- card-alias: e9a3db3589ae9b6d5adfa586c651e7e59fb38abd7d72558c976a94c555ead43f -->
C: In SHM, speed is [maximum] at $x = 0$ and [zero] at $x = \pm A$.

<!-- card-id: card-9e166624-fadd-48ab-9f41-68dfc3dda136 -->
<!-- card-alias: 54ca14204511f7dbfd8f93817ccfd77f6e51e1d81d31bea2ab1b0ef3877f8cb7 -->
<!-- card-alias: 97b95ccb3950ad4a528459e050d773db873fca9d0414a29c13ac1f5efd88b69d -->
C: In SHM, acceleration magnitude is [maximum] at $x = \pm A$ and [zero] at $x = 0$.

## 11.5 Spring-Mass System

<!-- card-id: card-fa39d467-945e-42a7-bc6e-51c4fdeb70bf -->
<!-- card-alias: 38e1bea120a8d87f151255e4d98aef6183a3e16aaeb6dc06976540325f2207ea -->
Q: What are the angular frequency and period of an ideal horizontal spring-mass oscillator?
A: For a mass $m$ and linear spring constant $k$, $\omega=\sqrt{k/m}$ and $T=2\pi\sqrt{m/k}$. Within this ideal SHM model the period is independent of amplitude.

<!-- card-id: card-8fa0b562-e2c7-443d-9fa2-8b33eb974aae -->
<!-- card-alias: f3ecb9622e02aebebe9bce3dddfa713000ae0174549ae8e965be8491929d8a8d -->
<!-- card-alias: bdadeda87702a6ada863bbe6d511812ad1914f78e31f52aec01aee6e94205c05 -->
C: The period of a spring-mass system is $T = 2\pi\sqrt{m/k}$. It is [independent] of amplitude. A stiffer spring (larger $k$) gives a [shorter] period.

## 11.6 Energy in SHM

<!-- card-id: card-5b513338-5b66-4bb0-ad35-68181b3a68e1 -->
<!-- card-alias: 7cc861f6bc7acbba9b9442b551d4c344b95df81da3fca817cbcf4d19021794a2 -->
Q: How is energy distributed between kinetic and potential energy throughout one cycle of SHM?
A: At position $x$: $K = \frac{1}{2}m\omega^2(A^2 - x^2)$ and $U = \frac{1}{2}kx^2$. Total: $E = K + U = \frac{1}{2}kA^2$ (constant). At $x = 0$: all energy is kinetic. At $x = \pm A$: all energy is potential. Energy oscillates between $K$ and $U$ at twice the frequency of the motion.

<!-- card-id: card-193df46b-c4b0-4088-9b16-f54f12266722 -->
<!-- card-alias: 573bf60e99f6d20943d3b3c315f533ad16a7d67ca184a2efcc913b6b4b49a035 -->
Q: How does total energy in SHM depend on amplitude?
A: $E = \frac{1}{2}kA^2$. Total energy is proportional to the square of amplitude. Doubling the amplitude quadruples the total energy.

<!-- card-id: card-cab88b5f-02fa-40c2-8f19-8b7695ac6dfa -->
<!-- card-alias: ec5bc8b5344aa0dea00eec4fcbb5bd13db6bec6c414cdc5821ef9f2b5ee7de48 -->
C: Total mechanical energy in SHM is $E = \frac{1}{2}kA^2$ (constant). Doubling the amplitude [quadruples] the total energy, because $E \propto \lbrack A^2\rbrack $.

## 11.7 Simple Pendulum

<!-- card-id: card-911a139e-11c4-4461-8279-0a77c7f0a3a8 -->
<!-- card-alias: 2703c8cd717f2908c604f5590f39b53cbc79c74f120779e852c79e090c83e280 -->
Q: Under what approximation does a simple pendulum exhibit SHM, and why?
A: When the angular amplitude is small enough that $\sin\theta\approx\theta$ with $\theta$ in radians. Then $F_t=-mg\sin\theta\approx-(mg/L)s$, which is linear in arc displacement $s=L\theta$. “Small enough” depends on the tolerated error; it is not a universal cutoff angle.

<!-- card-id: card-6d434311-d02d-472c-be72-2139ef1d6df3 -->
<!-- card-alias: 2f20a88732316d06dfd885949715b7d0d982fcffe709c5b3a1872ebdaca2023b -->
Q: What are the angular frequency and period of a simple pendulum for small angles?
A: $\omega = \sqrt{g/L}$ and $T = 2\pi\sqrt{L/g}$, where $L$ is the pendulum length (m) and $g$ is the gravitational acceleration (m/s²). The period is independent of mass and, for small angles, independent of amplitude.

<!-- card-id: card-4fe38a10-743e-4d35-9df0-f0d288764d63 -->
<!-- card-alias: 2647ffe701085bab6fc32ce7feff28b58b5fb7af167dd2546aa0160bfae306d1 -->
<!-- card-alias: 66885cc14898582c4fad6b6e35b6ae0b29a85854acc106d5f12e8c0072e511d0 -->
C: The period of a simple pendulum is $T = 2\pi\sqrt{L/g}$. It is independent of [mass] and (for small angles) independent of [amplitude].

<!-- card-id: card-859dd72e-7f08-4775-b2db-70752eb02cef -->
<!-- card-alias: fffa30b9231529b2d84eb5adea1e253cf2726edb2fb08b5f8ce2a7d019ecffb6 -->
C: For a simple pendulum with period $T = 2\pi\sqrt{L/g}$, a longer pendulum has a [longer] period.

## 11.8 Physical Pendulum

<!-- card-id: card-94908486-b8bd-4c57-ab3c-0ace4ef4baa0 -->
<!-- card-alias: c404a08bec153486ddf8b2d1ec5da6657ce106b12d5c78eac66f6ce0b8d78cfd -->
Q: How does a physical pendulum differ from a simple pendulum, and what is its period?
A: A physical pendulum is any rigid body swinging about a pivot that is not at the CM. Its period is $T = 2\pi\sqrt{I/(mgd)}$, where $I$ is the moment of inertia about the pivot (kg·m²), $m$ is total mass (kg), $d$ is the distance from the pivot to the CM (m). Reduces to simple pendulum when $I = mL^2$ and $d = L$.

<!-- card-id: card-90cfa217-2ec1-4b43-b253-a6f1151d192b -->
<!-- card-alias: 2aae53afb6b6a3fcf7629a49621fa714fe35e0dd50a7cb6a017cd1a84a032e3b -->
<!-- card-alias: 3d64de51aadeb3cca6cabe80f3ed05c3526ad1a85c46375307fc35ece825806b -->
C: For a physical pendulum, $T = 2\pi\sqrt{I/(mgd)}$, where $I$ is the [moment of inertia about the pivot] and $d$ is the distance from the pivot to the [center of mass].

## 11.9 Damped Oscillations

<!-- card-id: card-14707ad5-1930-4ecb-bcd1-1af8e19ff110 -->
<!-- card-alias: 5ba36624381c14509b7300538bea3a9b9c927ef7c3a2f3539eabd9b5b57f6402 -->
Q: What form does the damping force take in a linearly damped oscillator, and what new term does it add to the equation of motion?
A: $F_{damp} = -bv$, where $b \geq 0$ is the damping coefficient (N·s/m) and $v$ is the velocity. Newton's second law becomes $m\ddot{x} = -kx - b\dot{x}$, or equivalently $\ddot{x} + 2\gamma\dot{x} + \omega_0^2 x = 0$ with $\gamma = b/(2m)$ and $\omega_0^2 = k/m$.

<!-- card-id: card-08550711-86ed-41cf-b9f8-443464e577d9 -->
<!-- card-alias: fd5a456502688948cc8f7dd7624d50457e0bc950fd0b952282229a4268db9bd8 -->
Q: What characterizes the underdamped regime?
A: The condition is $b^2 < 4km$ (equivalently $\gamma < \omega_0$). The system still oscillates, but its amplitude decays exponentially: $A(t) = A_0 e^{-\gamma t}$, where $\gamma = b/(2m)$. The oscillation frequency is slightly reduced: $\omega_d = \sqrt{\omega_0^2 - \gamma^2}$.

<!-- card-id: card-1b7daf32-5fc6-4c11-af1d-a4fbf5697060 -->
<!-- card-alias: a2a9d8c5e3d0e550dba0bbe158f50171df81eb6db6f566f2a03c703823ee7e76 -->
Q: What characterizes the critically damped regime?
A: The condition is $b^2 = 4km$ (equivalently $\gamma = \omega_0$). The system returns to equilibrium as quickly as possible without overshooting or oscillating. Critical damping is the design target for many shock absorbers and measurement instruments.

<!-- card-id: card-491caaba-3f7f-464c-b29c-4bcaae36bfd8 -->
<!-- card-alias: 2a87939a048736d0ff304b9690dc78ef21057bfd53a0252b1fe76b36e38394c1 -->
Q: What characterizes the overdamped regime?
A: The condition is $b^2 > 4km$ (equivalently $\gamma > \omega_0$). The system returns to equilibrium slowly, without oscillating — slower than the critically damped case, because excess damping impedes motion toward equilibrium.

<!-- card-id: card-7647493d-89a6-48e7-95e5-b9c16687908c -->
<!-- card-alias: 07bb311f0759b2c163b930dbdad8be63a2838f088eb5a30913e473bd1f1beaad -->
C: In an underdamped oscillator, amplitude decays as $A(t) = A_0 e^{\lbrack -\gamma t\rbrack }$ where $\gamma = b/(2m)$ and $b$ is the damping coefficient. Critical damping gives the [fastest] return to equilibrium without oscillation.

## 11.10 Resonance

<!-- card-id: card-4ffd3f91-2324-4338-a509-d2cb6f124d74 -->
<!-- card-alias: b0cee8eae76dfd327027dc8246440945f699e0ae407096b507f8dcd7919e0c74 -->
Q: For a damped oscillator driven sinusoidally, where does the displacement-amplitude resonance peak occur?
A: It occurs near the undamped natural frequency $\omega_0=\sqrt{k/m}$. For linear damping $2\gamma\dot x$, the peak is at $\omega_r=\sqrt{\omega_0^2-2\gamma^2}$ when that peak exists, so weak damping makes $\omega_r\approx\omega_0$.

<!-- card-id: card-7ed7c186-17cc-4481-a07e-4ff79d6ea9cb -->
<!-- card-alias: b52721f4d9f08a12d38bfa224f1ca9f1358b0f153f370d76746e639f4873b570 -->
Q: What controls the steady-state amplitude of a driven oscillator near resonance?
A: The drive amplitude, frequency mismatch, and damping. With damping the response is finite; in the ideal undamped model, exact resonant driving makes the amplitude grow with time rather than approach a finite steady value.

<!-- card-id: card-c2623cd8-80bd-4f0f-a1ff-bcd4068d80c5 -->
<!-- card-alias: dcb531af86acb86515d75d74e161424c3d5558cb9417bb92448c2e9436faa2b4 -->
Q: Why does pushing a playground swing once per cycle at the right phase build a large amplitude?
A: Each push does positive work in step with the swing, so energy accumulates over many cycles. Driving near the natural frequency keeps the pushes phase-coherent; damping removes some energy each cycle.

<!-- card-id: card-5b1345a3-48b4-4294-ba26-61940f8c1389 -->
<!-- card-alias: 63fd7040d24c1f2f59c56c404791bd7699876db0ff6bb8fd777d7b71db802ece -->
Q: Why is the Tacoma Narrows Bridge collapse not a clean example of elementary forced resonance?
A: Its destructive torsional motion was a self-excited aeroelastic flutter instability involving feedback between wind and bridge motion, not simply a periodic external force matching one natural frequency.

<!-- card-id: card-486e705f-979d-4b22-bbc1-0a5c7e28932c -->
<!-- card-alias: 5fe783c62a127a14f935264a70231c8fd304687ce6dab4bacd93c2065cace6e5 -->
C: For a weakly damped driven oscillator, the displacement response peaks at a driving frequency [near] the undamped natural frequency $\omega_0$.

<!-- card-id: card-784a0d8a-7273-47dc-9fd9-de055be056cd -->
<!-- card-alias: bdfd32c0ec65f3930199683527b426a4ccead3a6a807e0ed3031bd8f6226e54c -->
<!-- card-alias: 9f8dd4cfa9bbba6b35b1dd72972706e1f528ab22a6b86c3aae16e0fe52a17193 -->
C: For a driven oscillator, greater damping produces a [lower] and [broader] resonance peak.

## 11.10a Pattern Recognition: Oscillations

<!-- card-id: card-4f00d34f-10d9-45a2-9940-a77e5b343c2a -->
<!-- card-alias: 870ce929cd24092ee86d04f732934a5d9e5eb256c98b5a310b45d9aaff5a5cbf -->
Q: A problem describes a system with restoring force; asks for period. What technique?
A: Identify effective $k$ and $m$ (or $I$ and $d$ for pendulum), then $T = 2\pi\sqrt{m/k}$ (or $2\pi\sqrt{L/g}$, $2\pi\sqrt{I/(mgd)}$).

<!-- card-id: card-07640545-24e8-4de9-85df-a26931f2f17a -->
<!-- card-alias: 0603f76f2c94a2cab847415d7abd9825a7dfe64e631824237121ce3c7c516e00 -->
Q: A problem describes oscillator amplitude decaying. What technique?
A: Damped SHM: amplitude $A_0 e^{-\gamma t}$ with $\gamma = b/(2m)$. Check whether under/critical/overdamped via $b^2$ vs $4km$.

<!-- card-id: card-ca39415a-7c2b-4577-b3b4-29eb3090b9c2 -->
<!-- card-alias: f5e122e9db600fb862be8bcd73cf319f6261f718405c80272137f73856f135d7 -->
Q: A problem mentions "small angle" or "small oscillation about equilibrium." What technique?
A: Linearize the restoring force ($\sin\theta \approx \theta$), reducing to SHM with effective $k$.

<!-- card-id: card-e40c32ff-4d19-401b-a4b4-6934a16061dd -->
<!-- card-alias: 39e25ff5576c6983760f8615ea40547675cd7f28dde70bf0062ebf0e99330bb2 -->
Q: A problem describes a driven system whose response peaks at a specific frequency. What technique?
A: Analyze the driven response and damping. For weak damping, the displacement-amplitude peak lies near $\omega_0=\sqrt{k/m}$, but not generally exactly at it.

## 11.11 Procedural: Spring-Mass SHM Analysis

<!-- card-id: card-d382918a-5071-4930-aa01-24ddb90f8225 -->
<!-- card-alias: eff287151b3753e5e3cbf21b9e13f94cafbedb2c1f74e5adef46f8d8b0bfcd6d -->
P: A spring-mass system has $k = 50$ N/m and $m = 0.5$ kg. Initial conditions: $x_0 = 0.2$ m, $v_0 = 0$. Find: (a) $\omega$ and $T$, (b) the full expression for $x(t)$, (c) maximum speed, (d) total mechanical energy.

S: **Identify:** Spring-mass SHM. $k = 50$ N/m, $m = 0.5$ kg, $x(0) = 0.2$ m, $v(0) = 0$. Find $\omega$, $T$, $x(t)$, $v_{max}$, $E$.

**Plan:** (a) $\omega = \sqrt{k/m}$, $T = 2\pi/\omega$. (b) Since $v(0) = 0$ and $x(0) = A > 0$, the mass is at a turning point: $\phi = 0$ and $A = x_0$. (c) $v_{max} = A\omega$. (d) $E = \frac{1}{2}kA^2$.

**Execute:**
(a) $\omega = \sqrt{50/0.5} = \sqrt{100} = 10$ rad/s.
$T = 2\pi/10 = 0.628$ s.

(b) $A = 0.2$ m, $\phi = 0$.
$x(t) = 0.2\cos(10t)$ m.

(c) $v_{max} = A\omega = (0.2)(10) = 2.0$ m/s.

(d) $E = \frac{1}{2}(50)(0.2)^2 = \frac{1}{2}(50)(0.04) = 1.0$ J.

**Evaluate:** Check energy at equilibrium: $K_{max} = \frac{1}{2}mv_{max}^2 = \frac{1}{2}(0.5)(4) = 1.0$ J. Matches $E$ — consistent. Check $v(0) = -A\omega\sin(0) = 0$ — matches initial condition. Period is reasonable ($\approx 0.6$ s for typical lab spring-mass).
