#  Temprature-Conversion🌡

Here we have a program that converts temperatures between Celsius, Fahrenheit, and Kelvin scales. The program should prompt the user to input a temperature value and the original unit of measurement. It should then convert the temperature to the other two units and display the converted values to the user. For example, if the user enters a temperature of 25 degrees Celsius, the program should convert it to Fahrenheit and Kelvin, and present the converted values as outputs.

## Steps to Build a Temperature Conversion Program:

Understand Temperature Scales: Temperature can be measured in Celsius (°C), Fahrenheit (°F), and Kelvin (K). Celsius is commonly used in scientific contexts, Fahrenheit in some countries like the US, and Kelvin in scientific and engineering fields.

#### Conversion Formulas: Celsius to Fahrenheit: F=95×C+32F=59​×C+32 👈👈👈

✔ Celsius to Kelvin: K=C+273.15K=C+273.15
✔ Fahrenheit to Celsius: C=59×(F−32)C=95​×(F−32)
✔ Fahrenheit to Kelvin: K=59×(F−32)+273.15K=95​×(F−32)+273.15
✔ Kelvin to Celsius: C=K−273.15C=K−273.15
✔ Kelvin to Fahrenheit: F=95×(K−273.15)+32F=59​×(K−273.15)+32
Building the Program: Input: Prompt the user to enter a temperature value and specify the original unit (C, F, or K). Conversion: Depending on the original unit entered, convert the temperature to the other two units using the appropriate formula. Output: Display the converted temperatures in a user-friendly format.

#### Handling Edge Cases: Ensure the program handles invalid inputs gracefully (e.g., non-numeric temperature, incorrect unit).

#### Example Scenario 💻

User Prompt: "Please enter the temperature value and its unit (C, F, or K)." Input: User enters "25 C" (25 degrees Celsius). Output: Program calculates and displays: "25 degrees Celsius is equal to:" "77 degrees Fahrenheit" "298.15 Kelvin"

### Benefits 🧠;

Educational: Helps understand temperature scales and conversion formulas.

Practical: Useful for engineering, scientific calculations, and everyday temperature conversions.

Versatile: Can be expanded or modified to include more units or functionalities.

By following these steps, you can create a functional and informative Temperature Conversion Program in Python. This approach focuses on understanding the concepts and steps involved without delving into the specific code implementation details.
