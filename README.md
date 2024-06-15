# tts_vue3
This is a simple example to test LaTeX rendering:
This is a simple example to test LaTeX rendering:

Inline math: $E = mc^2$

Block math:
$a^2 + b^2 = c^2$

Another block math example:
$F = G \\frac{m_1 m_2}{r^2}$
## Solution Approach:

### (1) Determining the density of the liquid in the container (\( \rho \)):

To find the density of the liquid, we can use the formula for liquid pressure \( P = \rho g h \), where:
- \( P \) is the pressure at the bottom of the container,
- \( \rho \) is the density of the liquid,
- \( g \) is the acceleration due to gravity,
- \( h \) is the depth of the liquid.

Since the pressure at the bottom is due solely to the weight of the liquid, we can also express this pressure as:
\[ P = \frac{G}{S} \]

Equating both expressions for pressure:
\[ \rho g h = \frac{G}{S} \]

Thus,
\[ \rho = \frac{G}{Sgh} \]

### (2) Finding the pressure the container exerts on the table when object A is submerged:

When the object A is submerged, it displaces an equivalent volume of liquid. The buoyant force exerted by the liquid on object A is equal to the weight of the displaced liquid.

The buoyant force \( F_b \) can be calculated as:
\[ F_b = \rho_{liquid} \cdot V_{displaced} \cdot g \]

Where:
- \( \rho_{liquid} \) is the density of the liquid determined in part (1),
- \( V_{displaced} = \text{Volume of } A = \frac{G_0}{\rho_0 g} \)
- \( g \) is the acceleration due to gravity.

Therefore:
\[ F_b = \rho_{liquid} \cdot \frac{G_0}{\rho_0 g} \cdot g = \rho_{liquid} \cdot \frac{G_0}{\rho_0} \]

The weight the container exerts on the table when A is submerged would be the sum of the weight of the liquid (G) and the effective weight of A in the liquid. The effective weight of A is its actual weight minus the buoyant force.

Thus, the pressure \( P_{container} \) is:
\[ P_{container} = \frac{G + (G_0 - F_b)}{S} \]
