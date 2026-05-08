+++
order = 11
tags = ["mechanics", "physics", "oscillations", "SHM", "pendulum"]
+++

# Classical Mechanics — Oscillations

## 11.1 Periodic Motion

Q: What defines periodic motion, and what quantities describe its time behavior?
A: Periodic motion repeats exactly after a fixed time interval. Period $T$ (s) is the time for one complete cycle. Frequency $f = 1/T$ (Hz = cycles/s) is the number of cycles per second. Angular frequency $\omega = 2\pi f = 2\pi/T$ (rad/s) converts cycles to radians. Amplitude $A$ is the maximum displacement from the equilibrium position.

C: Period $T$, frequency $f$, and angular frequency $\omega$ are related by $f = 1/T$ and $\omega = [2\pi f] = [2\pi/T]$. The unit of frequency is the [hertz] (Hz).

## 11.2 SHM Condition

Q: What physical condition produces simple harmonic motion (SHM)?
A: A restoring force proportional to displacement: $F = -kx$, where $k > 0$ is a positive constant (the effective stiffness) and $x$ is displacement from equilibrium. The negative sign ensures the force always points back toward equilibrium. This condition is equivalent to the equation of motion $\ddot{x} = -\omega^2 x$ with $\omega^2 = k/m$.

Q: Why is the restoring force criterion $F = -kx$ called a "linear" restoring force?
A: $F$ is linear in displacement $x$ (first power only). This linearity produces pure single-frequency oscillation. Nonlinear restoring forces (e.g., $F \propto -x^3$) produce anharmonic oscillations with multiple frequencies.

C: SHM requires a restoring force $F = -kx$. The equation of motion becomes $\ddot{x} = [-\omega^2 x]$, where $\omega^2 = [k/m]$.

## 11.3 SHM Solution

Q: What is the general solution for position in SHM, and what determines the constants?
A: $x(t) = A\cos(\omega t + \phi)$, where $A$ is the amplitude (m), $\omega = \sqrt{k/m}$ (rad/s), and $\phi$ is the phase constant (rad). Initial conditions determine $A$ and $\phi$: $x(0) = A\cos\phi$ and $\dot{x}(0) = -A\omega\sin\phi$.

Q: A mass on a spring is released from $x_0 = A$ at $t = 0$ with zero velocity. What is $\phi$?
A: $x(0) = A\cos\phi = A$ requires $\cos\phi = 1$, so $\phi = 0$. The solution simplifies to $x(t) = A\cos(\omega t)$, starting at maximum positive displacement.

C: The general SHM position is $x(t) = A\cos(\omega t + \phi)$. The amplitude $A$ and phase constant $\phi$ are determined by the [initial conditions] $x(0)$ and $\dot{x}(0)$.

## 11.4 SHM Velocity and Acceleration

Q: Derive the velocity and acceleration in SHM from $x(t) = A\cos(\omega t + \phi)$.
A: $v(t) = \dot{x} = -A\omega\sin(\omega t + \phi)$. $a(t) = \ddot{x} = -A\omega^2\cos(\omega t + \phi) = -\omega^2 x(t)$. Acceleration is always proportional to $-x$, confirming the SHM condition $a = -\omega^2 x$.

Q: Where in SHM is the speed maximum, and where is the magnitude of acceleration maximum?
A: Maximum speed $v_{max} = A\omega$ occurs at $x = 0$ (equilibrium), where the restoring force is zero. Maximum acceleration $a_{max} = A\omega^2$ occurs at $x = \pm A$ (turning points), where the restoring force is greatest.

C: In SHM, speed is [maximum] at $x = 0$ and [zero] at $x = \pm A$. Acceleration magnitude is [maximum] at $x = \pm A$ and [zero] at $x = 0$.

## 11.5 Spring-Mass System

Q: What are the angular frequency and period of a spring-mass system, and what is unique about the period in SHM?
A: $\omega = \sqrt{k/m}$, $T = 2\pi\sqrt{m/k}$, where $k$ is the spring constant (N/m) and $m$ is the mass (kg). The period is independent of amplitude — a hallmark of SHM. A heavier mass oscillates more slowly; a stiffer spring oscillates more quickly.

C: The period of a spring-mass system is $T = 2\pi\sqrt{m/k}$. It is [independent] of amplitude. A stiffer spring (larger $k$) gives a [shorter] period.

## 11.6 Energy in SHM

Q: How is energy distributed between kinetic and potential energy throughout one cycle of SHM?
A: At position $x$: $K = \frac{1}{2}m\omega^2(A^2 - x^2)$ and $U = \frac{1}{2}kx^2$. Total: $E = K + U = \frac{1}{2}kA^2$ (constant). At $x = 0$: all energy is kinetic. At $x = \pm A$: all energy is potential. Energy oscillates between $K$ and $U$ at twice the frequency of the motion.

Q: How does total energy in SHM depend on amplitude?
A: $E = \frac{1}{2}kA^2$. Total energy is proportional to the square of amplitude. Doubling the amplitude quadruples the total energy.

C: Total mechanical energy in SHM is $E = \frac{1}{2}kA^2$ (constant). Doubling the amplitude [quadruples] the total energy, because $E \propto [A^2]$.

## 11.7 Simple Pendulum

Q: Under what approximation does a simple pendulum exhibit SHM, and why?
A: For small angles ($\theta < 15°$), $\sin\theta \approx \theta$ (in radians). The tangential restoring force is $F = -mg\sin\theta \approx -mg\theta$. Using arc length $s = L\theta$ (so $\theta = s/L$), this becomes $F \approx -(mg/L)s$ — linear in displacement $s$, satisfying the SHM condition with effective stiffness $k_{eff} = mg/L$.

Q: What are the angular frequency and period of a simple pendulum for small angles?
A: $\omega = \sqrt{g/L}$ and $T = 2\pi\sqrt{L/g}$, where $L$ is the pendulum length (m) and $g$ is the gravitational acceleration (m/s²). The period is independent of mass and, for small angles, independent of amplitude.

C: The period of a simple pendulum is $T = 2\pi\sqrt{L/g}$. It is independent of [mass] and (for small angles) independent of [amplitude]. A longer pendulum has a [longer] period.

## 11.8 Physical Pendulum

Q: How does a physical pendulum differ from a simple pendulum, and what is its period?
A: A physical pendulum is any rigid body swinging about a pivot that is not at the CM. Its period is $T = 2\pi\sqrt{I/(mgd)}$, where $I$ is the moment of inertia about the pivot (kg·m²), $m$ is total mass (kg), $d$ is the distance from the pivot to the CM (m). Reduces to simple pendulum when $I = mL^2$ and $d = L$.

C: For a physical pendulum, $T = 2\pi\sqrt{I/(mgd)}$, where $I$ is the [moment of inertia about the pivot] and $d$ is the distance from the pivot to the [center of mass].

## 11.9 Damped Oscillations

Q: What form does the damping force take in a linearly damped oscillator, and what new term does it add to the equation of motion?
A: $F_{damp} = -bv$, where $b \geq 0$ is the damping coefficient (N·s/m) and $v$ is the velocity. Newton's second law becomes $m\ddot{x} = -kx - b\dot{x}$, or equivalently $\ddot{x} + 2\gamma\dot{x} + \omega_0^2 x = 0$ with $\gamma = b/(2m)$ and $\omega_0^2 = k/m$.

Q: What characterizes the underdamped regime?
A: The condition is $b^2 < 4km$ (equivalently $\gamma < \omega_0$). The system still oscillates, but its amplitude decays exponentially: $A(t) = A_0 e^{-\gamma t}$, where $\gamma = b/(2m)$. The oscillation frequency is slightly reduced: $\omega_d = \sqrt{\omega_0^2 - \gamma^2}$.

Q: What characterizes the critically damped regime?
A: The condition is $b^2 = 4km$ (equivalently $\gamma = \omega_0$). The system returns to equilibrium as quickly as possible without overshooting or oscillating. Critical damping is the design target for many shock absorbers and measurement instruments.

Q: What characterizes the overdamped regime?
A: The condition is $b^2 > 4km$ (equivalently $\gamma > \omega_0$). The system returns to equilibrium slowly, without oscillating — slower than the critically damped case, because excess damping impedes motion toward equilibrium.

C: In an underdamped oscillator, amplitude decays as $A(t) = A_0 e^{[-\gamma t]}$ where $\gamma = b/(2m)$ and $b$ is the damping coefficient. Critical damping gives the [fastest] return to equilibrium without oscillation.

## 11.10 Resonance

Q: What is resonance, and when does it occur in a driven oscillator?
A: Resonance occurs when the driving frequency matches the natural frequency $\omega_0 = \sqrt{k/m}$ of the oscillator. At resonance, energy is transferred most efficiently from the driver to the oscillator, and the amplitude reaches its maximum value. The maximum amplitude at resonance is limited only by damping.

Q: Give two examples where resonance is useful and one where it is destructive.
A: Useful: (1) MRI machines use resonance to excite hydrogen nuclei at their Larmor frequency. (2) Tuned mass dampers in skyscrapers absorb vibrational energy at the building's natural frequency. Destructive: The 1940 Tacoma Narrows Bridge collapsed when wind-induced oscillations matched the bridge's natural frequency.

C: In a driven oscillator, resonance occurs when the driving frequency [equals] the natural frequency $\omega_0 = \sqrt{k/m}$. Greater damping produces a [lower] and [broader] resonance peak.

## 11.10a Pattern Recognition: Oscillations

Q: A problem describes a system with restoring force; asks for period. What technique?
A: Identify effective $k$ and $m$ (or $I$ and $d$ for pendulum), then $T = 2\pi\sqrt{m/k}$ (or $2\pi\sqrt{L/g}$, $2\pi\sqrt{I/(mgd)}$).

Q: A problem describes oscillator amplitude decaying. What technique?
A: Damped SHM: amplitude $A_0 e^{-\gamma t}$ with $\gamma = b/(2m)$. Check whether under/critical/overdamped via $b^2$ vs $4km$.

Q: A problem mentions "small angle" or "small oscillation about equilibrium." What technique?
A: Linearize the restoring force ($\sin\theta \approx \theta$), reducing to SHM with effective $k$.

Q: A problem describes a driven system whose response peaks at a specific frequency. What technique?
A: Resonance: peak occurs at $\omega_{drive} = \omega_0 = \sqrt{k/m}$.

## 11.11 Procedural: Spring-Mass SHM Analysis

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
