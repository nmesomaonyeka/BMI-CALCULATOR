# BMI Calculator

This Python program calculates the Body Mass Index (BMI) based on the user's input of weight (in pounds) and height (in inches). It then provides a health status message based on the BMI value.



## Features
- Prompts the user to enter their name, weight, and height.
- Calculates BMI using the formula:

BMI = (weight * 703) / (height^2)

- Outputs the BMI value and a personalized health status message based on the calculated BMI.



## How to Use
1. Run the program in a Python environment.
2. Enter your **name** when prompted.
3. Enter your **weight** in pounds when prompted.
4. Enter your **height** in inches when prompted.
5. View the calculated BMI and health status message.



## Output Messages
Depending on the calculated BMI, the program outputs one of the following messages:
- **Underweight:** BMI < 18.5
- **Normal weight:** BMI 18.5–24.9
- **Overweight:** BMI 25–29.9
- **Obese:** BMI 30–34.9
- **Severely obese:** BMI 35–39.9
- **Morbidly obese:** BMI ≥ 40

If the inputs are invalid, the program prompts the user to enter valid values.





## Notes
- Ensure the inputs are numeric to avoid errors.
- The formula uses the imperial system (pounds and inches). For metric values, modify the formula accordingly.
- This is a simple calculator intended for educational purposes. For precise health assessments, consult a healthcare professional.


## Enhancements
Future improvements to this program could include:
- Adding input validation to handle non-numeric values.
- Allowing users to input their weight and height in metric units (kilograms and meters).
- Providing recommendations for improving health based on the BMI category.

