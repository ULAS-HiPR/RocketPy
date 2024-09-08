# Motor Parameters

## SolidMotor

### Grain Density calculation

1. **Calculate propellant mass**:
   \[m_{\text{propellant}} = \text{Total mass} - \text{Dry mass}\]

2. **Calculate the volume of a single grain**:
   The volume of a hollow cylinder is:
   \[V_{\text{grain}} = \pi \times h \times (r_{\text{outer}}^2 - r_{\text{inner}}^2)\]
  
3. **Calculate total propellant volume**:
   \[V_{\text{total}} = 3 \times V_{\text{grain}} = 3 \times 0.000279 \, \text{m}^3 \approx 0.000837 \, \text{m}^3\]

4. **Calculate grain density**:
   The density \( \rho \) is calculated as:
   \[\rho = \frac{m_{\text{propellant}}}{V_{\text{total}}}\]
