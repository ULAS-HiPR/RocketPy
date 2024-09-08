# Motor Parameters

## SolidMotor

---

### Grain Density calculation

#### Step-by-Step Calculation

1. **Given Values**:
   - **Total mass (launch mass)** = 3.752 kg
   - **Dry mass** = 1.608 kg
   - **Number of grains** = 3
   - **Grain geometry**:
     - Outer radius: 37.5 mm = 0.0375 m
     - Inner radius: 29 mm = 0.029 m
     - Grain height: 157 mm = 0.157 m

2. **Calculate propellant mass**:
   \[
   m_{\text{propellant}} = \text{Total mass} - \text{Dry mass}
   \]
   \[
   m_{\text{propellant}} = 3.752 \, \text{kg} - 1.608 \, \text{kg} = 2.144 \, \text{kg}
   \]

3. **Calculate the volume of a single grain**:
   The volume of a hollow cylinder is:
   \[
   V_{\text{grain}} = \pi \times h \times (r_{\text{outer}}^2 - r_{\text{inner}}^2)
   \]
   Substitute the values:
   \[
   V_{\text{grain}} = \pi \times 0.157 \, \text{m} \times (0.0375^2 - 0.029^2)
   \]
   \[
   V_{\text{grain}} \approx \pi \times 0.157 \, \text{m} \times (0.00140625 - 0.000841)
   \]
   \[
   V_{\text{grain}} \approx \pi \times 0.157 \times 0.00056525 \approx 0.000279 \, \text{m}^3
   \]

4. **Calculate total propellant volume**:
   \[
   V_{\text{total}} = 3 \times V_{\text{grain}} = 3 \times 0.000279 \, \text{m}^3 \approx 0.000837 \, \text{m}^3
   \]

5. **Calculate grain density**:
   The density \( \rho \) is calculated as:
   \[
   \rho = \frac{m_{\text{propellant}}}{V_{\text{total}}}
   \]
   \[
   \rho = \frac{2.144 \, \text{kg}}{0.000837 \, \text{m}^3} \approx 2561 \, \text{kg/m}^3
   \]

