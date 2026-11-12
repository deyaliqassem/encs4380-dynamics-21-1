# Dynamic Characteristics Interactive Toolkit

**Course:** ENCS4380 – Interfacing Techniques  
**University:** Birzeit University  
**Instructor:** Dr. Wasel Ghanem  
**Project Status:** Final Version – Modules 1–4

## Live Website

**[Launch the Interactive Toolkit](https://deyaliqassem.github.io/encs4380-dynamics-21-1/)**

## Project Overview

The Dynamic Characteristics Interactive Toolkit is a web-based educational application designed to demonstrate the dynamic behavior of measurement systems and sensors.

The toolkit provides mathematical models, interactive controls, real-time graphical visualizations, prediction activities, and numerical validation checks to help students understand first-order and second-order dynamic systems.

The final application integrates four interactive modules into a single website.

## Team Members and Module Responsibilities

| Team Member | Primary Module Responsibility |
|---|---|
| Deyali Qassem | Module 1 – First-Order Time Response |
| Malak Odeh | Module 2 – Frequency Response |
| Rahaf Barakat | Module 3 – Second-Order Systems |
| Noor Shawamreh | Module 4 – Guess the Sensor |

### Team Collaboration

The project was developed collaboratively by all four team members.

Each member had primary responsibility for coordinating and reviewing an assigned module. The team collaborated on implementation, interface improvements, debugging, mathematical verification, integration, and testing.

Module ownership represents responsibility and coordination rather than exclusive individual development.

## Project Modules

### Module 1 – First-Order Time Response

**Primary Owner:** Deyali Qassem

This module demonstrates the time-domain response of a first-order measurement system.

**Features:**
- Adjustable sensor gain (K) and time constant (τ).
- Step and ramp input selection.
- Interactive input and output response plots.
- Response markers at 63.2% and approximately 95%.
- Ramp lag and steady-state error calculations.
- Logarithmic error-fraction visualization.
- Predict-then-check activity.
- Numerical validation checks.

### Module 2 – Frequency Response

**Primary Owner:** Malak Odeh

This module explores how a first-order sensor responds to sinusoidal inputs at different frequencies.

**Features:**
- Adjustable time constant and input frequency.
- Interactive input and output sine-wave plots.
- Amplitude ratio and phase lag calculations.
- Bode magnitude and phase plots.
- Cutoff-frequency visualization.
- Dynamic-error calculator.
- Predict-then-check activity.
- Numerical validation checks.

### Module 3 – Second-Order Systems

**Primary Owner:** Rahaf Barakat

This module demonstrates second-order dynamic behavior using a mass-spring-damper model.

**Features:**
- Adjustable damping ratio and natural frequency.
- Interactive mass, damping, and stiffness parameters.
- Step-response visualization.
- Pole locations in the complex s-plane.
- Rise time, peak time, overshoot, and settling time.
- State-space representation.
- Eigenvalue and transfer-function pole comparison.
- Numerical simulation using the fourth-order Runge–Kutta (RK4) method.
- Predict-then-check activities and validation checks.

### Module 4 – Guess the Sensor

**Primary Owner:** Noor Shawamreh

This module provides an interactive learning activity where users estimate hidden sensor parameters from simulated measurements.

**Features:**
- Randomly generated mystery sensor scenarios.
- Noisy sensor measurements.
- First-order step, first-order sine, and second-order response scenarios.
- Parameter estimation through interactive input fields.
- Optional estimation hints.
- Comparison between true and estimated responses.
- Relative-error-based scoring.
- Session score and completed-round tracking.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Chart.js
- Git and GitHub
- GitHub Pages

The application is implemented as a client-side website and uses Chart.js for graphical visualization.

## Mathematical Validation

The toolkit includes numerical checks and interactive demonstrations of important dynamic-system properties.

These include:

- First-order step response at one and three time constants.
- First-order sinusoidal amplitude attenuation and phase lag.
- Frequency-response cutoff behavior and dynamic-error limits.
- Second-order overshoot for underdamped systems.
- Critical damping with zero overshoot.
- Agreement between state-space eigenvalues and transfer-function poles.

## Project Structure

- `index.html` – Main application integrating Modules 1–4.
- `README.md` – Project documentation.
- `Module_1_First_Order_Time_Response.html` – Preserved Module 1 checkpoint version.
- Additional HTML file – Earlier integrated checkpoint version containing Modules 1–3.

## Deployment

The project is hosted through GitHub Pages using the `main` branch.

**Live URL:**  
https://deyaliqassem.github.io/encs4380-dynamics-21-1/

## AI Assistance Disclosure

ChatGPT and Claude were used as supporting tools during development, including assistance with interface design, HTML/CSS styling, JavaScript structure, debugging, and code organization.

The team reviewed the generated suggestions, evaluated the mathematical models, and tested the functionality and numerical results of the toolkit.

## Screenshots

Screenshots of all four modules can be added to the repository to demonstrate the final interface and main features.

## Final Release

The completed project is prepared for release as **v1.0**, including all four integrated modules.

## Conclusion

This project provides an interactive educational environment for exploring sensor dynamics, connecting mathematical equations with graphical simulations, and strengthening understanding through experimentation and prediction activities.
