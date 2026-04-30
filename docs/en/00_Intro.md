# Section 0: Mathematical Foundations – Solutions

# Task 01 – Vector Algebra

## Problem Statement

Two vectors are given in three-dimensional space:

$$
\vec{a} = 
\begin{pmatrix}
2 \\
1 \\
-3
\end{pmatrix}
$$

$$
\vec{b} = 
\begin{pmatrix}
4 \\
-2 \\
1
\end{pmatrix}
$$

The magnitudes, dot product, cross product, and the angle between the vectors must be calculated.

## Theory

The magnitude of a vector $\vec{v}$ is determined by the square root of the sum of the squares of its components:

$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}
$$

The dot product (scalar product) of two vectors is the sum of the products of their corresponding components:

$$
\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z
$$

The cross product (vector product) yields a vector perpendicular to both original vectors, determined by the determinant of their components:

$$
\vec{a} \times \vec{b} = 
\begin{pmatrix}
a_y b_z - a_z b_y \\
a_z b_x - a_x b_z \\
a_x b_y - a_y b_x
\end{pmatrix}
$$

The angle $\theta$ between the two vectors is derived from the geometric definition of the dot product:

$$
\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}
$$

## Step-by-Step Solution

First, the magnitudes of both vectors are computed.

$$
\begin{align}
|\vec{a}| &= \sqrt{2^2 + 1^2 + (-3)^2} \\
&= \sqrt{4 + 1 + 9} \\
&= \sqrt{14}
\end{align}
$$

$$
\begin{align}
|\vec{b}| &= \sqrt{4^2 + (-2)^2 + 1^2} \\
&= \sqrt{16 + 4 + 1} \\
&= \sqrt{21}
\end{align}
$$

Next, the dot product is calculated:

$$
\begin{align}
\vec{a} \cdot \vec{b} &= (2)(4) + (1)(-2) + (-3)(1) \\
&= 8 - 2 - 3 \\
&= 3
\end{align}
$$

The cross product is computed using the formula:

$$
\vec{a} \times \vec{b} = 
\begin{pmatrix}
(1)(1) - (-3)(-2) \\
(-3)(4) - (2)(1) \\
(2)(-2) - (1)(4)
\end{pmatrix}
$$

$$
\vec{a} \times \vec{b} = 
\begin{pmatrix}
1 - 6 \\
-12 - 2 \\
-4 - 4
\end{pmatrix}
$$

$$
\vec{a} \times \vec{b} = 
\begin{pmatrix}
-5 \\
-14 \\
-8
\end{pmatrix}
$$

Finally, the angle is found using the cosine relation:

$$
\begin{align}
\cos\theta &= \frac{3}{\sqrt{14} \sqrt{21}} \\
&= \frac{3}{\sqrt{294}} \\
&= \frac{3}{7\sqrt{6}}
\end{align}
$$

## Final Result

a) Magnitudes: $|\vec{a}| = \sqrt{14}$, $|\vec{b}| = \sqrt{21}$.

b) Dot product: $\vec{a} \cdot \vec{b} = 3$.

c) Cross product: 

$$
\vec{a} \times \vec{b} = 
\begin{pmatrix}
-5 \\
-14 \\
-8
\end{pmatrix}
$$

d) Angle: $\theta = \arccos\left( \frac{3}{7\sqrt{6}} \right) \approx 79.9^\circ$.

## Interpretation

The positive dot product indicates that the angle between the two vectors is acute (less than $90^\circ$). The resulting cross product vector is geometrically orthogonal to the plane containing both $\vec{a}$ and $\vec{b}$.

# Task 02 – Systems of Equations

## Problem Statement

The values of $x$ and $y$ that satisfy the following system of linear equations must be determined:

$$
2x + 3y = 12
$$

$$
x - y = 1
$$

## Theory

A system of linear equations can be solved using substitution or elimination. In substitution, one equation is rearranged to isolate a variable, which is then substituted into the other equation to solve for the remaining unknown.

## Step-by-Step Solution

The second equation is rearranged to isolate $x$:

$$
x = y + 1
$$

This expression is substituted into the first equation:

$$
2(y + 1) + 3y = 12
$$

$$
2y + 2 + 3y = 12
$$

Like terms are combined:

$$
5y + 2 = 12
$$

$$
5y = 10
$$

$$
y = 2
$$

The value of $y$ is substituted back into the rearranged second equation:

$$
x = 2 + 1
$$

$$
x = 3
$$

## Final Result

The solution to the system is:

$$
x = 3
$$

$$
y = 2
$$

## Interpretation

Geometrically, the coordinates $(3, 2)$ represent the precise point of intersection between the lines $2x + 3y = 12$ and $x - y = 1$ on a Cartesian plane.

# Task 03 – Proportionality

## Problem Statement

The Universal Law of Gravitation is given by:

$$
F = G \frac{m_1 m_2}{r^2}
$$

The change in the force $F$ must be determined when the distance $r$ is doubled, and both masses $m_1$ and $m_2$ are halved.

## Theory

Proportionality allows the analysis of formulas by observing how scaling the input variables affects the output. The force is directly proportional to the product of the masses and inversely proportional to the square of the distance.

## Step-by-Step Solution

New variables are defined according to the conditions:

$$
m_1' = \frac{m_1}{2}
$$

$$
m_2' = \frac{m_2}{2}
$$

$$
r' = 2r
$$

These new parameters are substituted into the original gravitational formula to find the new force $F'$:

$$
\begin{align}
F' &= G \frac{m_1' m_2'}{(r')^2} \\
   &= G \frac{(\frac{m_1}{2}) (\frac{m_2}{2})}{(2r)^2}
\end{align}
$$

The numerator and denominator are expanded:

$$
F' = G \frac{\frac{m_1 m_2}{4}}{4r^2}
$$

The scalar multipliers are factored out:

$$
F' = \frac{1}{16} \left( G \frac{m_1 m_2}{r^2} \right)
$$

Substituting the original force $F$:

$$
F' = \frac{1}{16} F
$$

## Final Result

The gravitational force $F$ changes by a factor of $\frac{1}{16}$.

## Interpretation

The inverse-square law dictates that doubling the distance reduces the force by a factor of 4. Simultaneously, halving both masses reduces the force by another factor of 4. Combined, these effects reduce the total gravitational attraction to one-sixteenth of its original value.

# Task 04 – Rearranging Formulas

## Problem Statement

The formula for the period of a simple pendulum is:

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

This equation must be rearranged to isolate $g$ (acceleration due to gravity).

## Theory

Algebraic manipulation requires performing inverse operations on both sides of the equation. To isolate a variable located inside a square root, the equation must be squared.

## Step-by-Step Solution

Both sides are divided by $2\pi$ to isolate the radical:

$$
\frac{T}{2\pi} = \sqrt{\frac{L}{g}}
$$

Both sides are squared to eliminate the square root:

$$
\left( \frac{T}{2\pi} \right)^2 = \frac{L}{g}
$$

$$
\frac{T^2}{4\pi^2} = \frac{L}{g}
$$

To isolate $g$, the reciprocal of both sides can be taken:

$$
\frac{4\pi^2}{T^2} = \frac{g}{L}
$$

Both sides are multiplied by $L$:

$$
g = \frac{4\pi^2 L}{T^2}
$$

## Final Result

The rearranged formula for the acceleration due to gravity is:

$$
g = \frac{4\pi^2 L}{T^2}
$$

## Interpretation

This expression is fundamental in experimental physics. By measuring the length $L$ of a pendulum and its period of oscillation $T$, the local acceleration due to gravity $g$ can be calculated with high precision.

# Task 05 – Trigonometry

## Problem Statement

A vector $\vec{A}$ has a magnitude of $15$ and makes an angle of $60^\circ$ with the horizontal axis. Its horizontal and vertical components must be calculated.

## Theory

In a 2D Cartesian coordinate system, a vector is resolved into its orthogonal components using trigonometric functions. 

The horizontal component is:

$$
A_x = A \cos(\theta)
$$

The vertical component is:

$$
A_y = A \sin(\theta)
$$

## Step-by-Step Solution

The standard trigonometric values for $60^\circ$ are known:

$$
\cos(60^\circ) = \frac{1}{2}
$$

$$
\sin(60^\circ) = \frac{\sqrt{3}}{2}
$$

The horizontal component is calculated:

$$
\begin{align}
A_x &= 15 \cdot \cos(60^\circ) \\
    &= 15 \cdot \frac{1}{2} \\
    &= 7.5
\end{align}
$$

The vertical component is calculated:

$$
\begin{align}
A_y &= 15 \cdot \sin(60^\circ) \\
    &= 15 \cdot \frac{\sqrt{3}}{2} \\
    &= 7.5\sqrt{3}
\end{align}
$$

## Final Result

The vector components are:

$$
A_x = 7.5
$$

$$
A_y = 7.5\sqrt{3} \approx 12.99
$$

## Interpretation

Since the angle $60^\circ$ is greater than $45^\circ$, the vector points more vertically than horizontally. Consequently, the magnitude of the vertical component ($12.99$) is strictly greater than the horizontal component ($7.5$).

# Task 06 – Function Analysis

## Problem Statement

The local maxima or minima of the following quadratic function must be identified:

$$
f(x) = 3x^2 - 12x + 7
$$

## Theory

Extrema occur at critical points where the first derivative of the function equals zero. 

$$
f'(x) = 0
$$

The second derivative test determines the nature of the extremum. If $f''(x) > 0$, the point is a local minimum. If $f''(x) < 0$, it is a local maximum.

## Step-by-Step Solution

The first derivative of the function is computed:

$$
f'(x) = 6x - 12
$$

The derivative is set to zero to find the critical point:

$$
6x - 12 = 0
$$

$$
6x = 12
$$

$$
x = 2
$$

The second derivative is computed to confirm the concavity:

$$
f''(x) = 6
$$

Since $f''(2) = 6 > 0$, the function has a local minimum at $x = 2$. The corresponding $y$-value is calculated by substituting $x$ into the original function:

$$
\begin{align}
f(2) &= 3(2)^2 - 12(2) + 7 \\
     &= 3(4) - 24 + 7 \\
     &= 12 - 24 + 7 \\
     &= -5
\end{align}
$$

## Final Result

The function has one local minimum at the coordinates:

$$
(2, -5)
$$

## Interpretation

The function represents an upward-opening parabola (since the coefficient of $x^2$ is positive). Such parabolas naturally possess a single global minimum and no local maxima, which is consistent with the calculus-based derivation.

# Task 07 – Logic & Series

## Problem Statement

A bicycle is $10\text{ m}$ from a wall, moving towards it at $1\text{ m/s}$. A fly flies between the bicycle and the wall continuously at $2\text{ m/s}$ until the bicycle hits the wall. The total distance the fly travels must be determined.

## Theory

While this can be modeled as an infinite geometric series summing the paths between bounces, it is solved much more efficiently using basic kinematics. Distance is simply speed multiplied by time:

$$
d = v \cdot t
$$

The total flight time of the fly is exactly equal to the time it takes for the bicycle to reach the wall.

## Step-by-Step Solution

First, the time it takes for the bicycle to hit the wall is calculated:

$$
t = \frac{d_{bike}}{v_{bike}}
$$

$$
t = \frac{10}{1}
$$

$$
t = 10\text{ s}
$$

The fly is in continuous motion for this exact duration of $10\text{ s}$ at a constant speed of $2\text{ m/s}$. The total distance traveled by the fly is:

$$
d_{fly} = v_{fly} \cdot t
$$

$$
d_{fly} = 2 \cdot 10
$$

$$
d_{fly} = 20\text{ m}
$$

## Final Result

The total distance the fly travels is:

$$
20\text{ m}
$$

## Interpretation

This problem is a classic example of lateral thinking in physics. By shifting the frame of reference from the complex spatial path (the infinite zigzag) to the shared scalar variable (time), the complexity collapses into a trivial arithmetic calculation.

# Task 08 – Definite Integrals

## Problem Statement

The area under the curve of $f(x) = \sin(x)$ from $x=0$ to $x=\pi$ must be calculated.

## Theory

The definite integral of a continuous positive function represents the geometric area bounded by the curve and the x-axis over a given interval.

$$
A = \int_a^b f(x) \, dx
$$

By the Fundamental Theorem of Calculus, this is evaluated using the antiderivative $F(x)$.

## Step-by-Step Solution

The integral is set up:

$$
A = \int_0^\pi \sin(x) \, dx
$$

The antiderivative of $\sin(x)$ is $-\cos(x)$. The limits of integration are applied:

$$
A = \left[ -\cos(x) \right]_0^\pi
$$

The boundaries are substituted into the antiderivative:

$$
A = (-\cos(\pi)) - (-\cos(0))
$$

Using the known values $\cos(\pi) = -1$ and $\cos(0) = 1$:

$$
\begin{align}
A &= -(-1) - (-1) \\
  &= 1 + 1 \\
  &= 2
\end{align}
$$

## Final Result

The area under the curve is:

$$
A = 2
$$

## Interpretation

The exact integer value of $2$ for the area under the first half-period of a sine wave is a deeply fundamental result in calculus, frequently utilized when computing average values of alternating currents and harmonic oscillators.

# Task 09 – Optimization Problem

## Problem Statement

The dimensions of a rectangle bounded by the x-axis, the y-axis, and the curve $y = 3 - x^2$ in the first quadrant that maximize the area must be found.

## Theory

Optimization requires defining an objective function (in this case, area) and finding its critical points by taking the first derivative and setting it to zero. 

The area of a rectangle with a corner at $(x, y)$ on the curve is:

$$
A = x \cdot y
$$

## Step-by-Step Solution

The height $y$ is constrained by the curve, so $3 - x^2$ is substituted into the area formula:

$$
A(x) = x(3 - x^2)
$$

$$
A(x) = 3x - x^3
$$

The first derivative with respect to $x$ is taken:

$$
A'(x) = 3 - 3x^2
$$

To find the maximum, the derivative is set to zero:

$$
3 - 3x^2 = 0
$$

$$
3x^2 = 3
$$

$$
x^2 = 1
$$

Since the rectangle is in the first quadrant, only the positive root is valid:

$$
x = 1
$$

The corresponding $y$ dimension is found by substituting $x$ back into the curve equation:

$$
y = 3 - (1)^2
$$

$$
y = 2
$$

## Final Result

The dimensions of the rectangle that maximize the area are:

$$
\text{Width} = 1
$$

$$
\text{Height} = 2
$$

## Interpretation

At these dimensions, the maximum area is $1 \times 2 = 2$. Any wider rectangle would be forced to be excessively short by the parabolic boundary, and any taller rectangle would be too narrow, making $1 \times 2$ the optimal geometrical configuration.

# Task 10 – Infinite Series

## Problem Statement

An ant starts at the origin $(0,0)$ and moves: $1\text{ m}$ East, $1/2\text{ m}$ North, $1/3\text{ m}$ West, $1/4\text{ m}$ South, $1/5\text{ m}$ East, continuing infinitely. The final coordinate position must be determined.

## Theory

The movement can be split into two independent infinite alternating series for the x-axis (East/West) and the y-axis (North/South). These series correspond to well-known Taylor series expansions evaluated at specific points.

The expansion for arctangent is:

$$
\arctan(x) = x - \frac{x^3}{3} + \frac{x^5}{5} - \frac{x^7}{7} + \dots
$$

The expansion for the natural logarithm is:

$$
\ln(1+x) = x - \frac{x^2}{2} + \frac{x^3}{3} - \frac{x^4}{4} + \dots
$$

## Step-by-Step Solution

The movements on the x-axis are East $(+)$ and West $(-)$:

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots
$$

This matches the Gregory-Leibniz series for $\arctan(1)$:

$$
x = \arctan(1)
$$

$$
x = \frac{\pi}{4}
$$

The movements on the y-axis are North $(+)$ and South $(-)$:

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots
$$

Factoring out $1/2$ yields:

$$
y = \frac{1}{2} \left( 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots \right)
$$

The term in the parentheses is the alternating harmonic series, which evaluates to $\ln(2)$:

$$
y = \frac{1}{2} \ln(2)
$$

## Final Result

The final position of the ant converges to the coordinates:

$$
\left( \frac{\pi}{4}, \frac{\ln(2)}{2} \right)
$$

## Interpretation

This problem elegantly bridges discrete 2D random walks with continuous calculus. The ant's spiraling path eventually stabilizes at a precise transcendental coordinate point, demonstrating the convergence of infinite alternating sequences.