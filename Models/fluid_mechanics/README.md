# Data Analytics Project - Fluid Mechanics Analysis
This data analytics work focuses on fluid dynamics analysis using Python. Specifically, it involves the calculation of viscosity `(μ)`, Reynolds numbers `(Re)`, and transitional velocity `(Vt)` for a fluid flowing through a pipe.<br>
The analysis is based on provided data, and it uses Python libraries such as NumPy and SciPy for data manipulation and linear regression.<br>

## Code Description
The Python script in this analysis performs the following tasks:

1. **Data Import and Linear Regression:**
   - Imports the necessary Python libraries, including `NumPy` and `SciPy.`<br>
   - Defines and uses provided data, `ln_v` (natural logarithm of velocity) and `ln_i` (natural logarithm of current).<br>
   - Performs a linear regression analysis to determine the slope and intercept, which correspond to `ln(8μ)`.<br>

2. **Viscosity Calculation:**
   - Calculates the viscosity `(μ)` using the intercept obtained from the linear regression. Viscosity is a crucial parameter in fluid dynamics.<br>

3. **Calculating f for Each Data Point:**
   - Calculates the friction factor `(f)` for each data point using the obtained μ and other parameters.<br>
   - The acceleration due to gravity `(g)` and fluid characteristics are considered in the calculation.<br>

4. **Calculating Reynolds Number (Re):**
   - Calculates the Reynolds number (Re) for each measurement.<br>
   - The pipe diameter (D) and fluid properties are used in the calculation.<br>

5. **Calculating Transitional Velocity (Vt):**
   - Identifies the transition point from laminar to turbulent flow by analyzing the relationship between `ln(Re)` and `ln(f)`.<br>
   - Calculates the transitional velocity `(Vt)` and transitional Reynolds number `(Re_t)`.<br>

## Libraries Used
The analysis relies on the following Python libraries:
- **NumPy**: Used for numerical operations and data manipulation.<br>
- **SciPy**: Used for performing linear regression and other scientific calculations.<br>

## Data Used
The analysis uses the following datasets:
- ln_v: Natural logarithm of velocity (ln_v)
- ln_i: Natural logarithm of current (ln_i)

