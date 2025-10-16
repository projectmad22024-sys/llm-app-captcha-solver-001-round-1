# CAPTCHA Solver

This simple web application allows you to input a CAPTCHA image URL and simulates solving it.

## Features
- Accepts custom CAPTCHA image URLs via URL parameter `?url=`.
- Clicks the "Solve CAPTCHA" button to generate a fake solution.
- Displays the solution under "Solved Captcha:" after a 10-second delay.
- Automatically starts solving if `?url=` parameter is provided.

## How to run
1. Save the `index.html` file locally.
2. Open `index.html` in a web browser.
3. Enter the CAPTCHA image URL or include it as a URL parameter, e.g.
   
   `file:///path/to/index.html?url=https://alpha.example.com/captcha.png`

4. Click the "Solve CAPTCHA" button.
5. The simulated answer "TEST" will appear after approximately 10 seconds.

## Note
This is a mock-up demo simulating CAPTCHA solving for instructional purposes. No real CAPTCHA processing occurs.

## License
This project is licensed under the MIT License.
