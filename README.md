# Dynamic Characteristics Interactive Toolkit

**Course:** ENCS4380 – Interfacing Techniques  
**University:** Birzeit University  
**Instructor:** Dr. Wasel Ghanem  
**Homework 2 status:** Checkpoint – P1 and P2

## Live website

https://deyaliqassem.github.io/encs4380-dynamics-21-1/

## Project overview

This client-side educational toolkit demonstrates the dynamic behavior of measurement systems and sensors through mathematical models, interactive controls, numerical simulations, plots, prediction activities, and validation checks.

Homework 2 extends the original four-module toolkit with a **Control** section containing P1 and P2. Modules 1–4 are retained.

## Existing modules (Homework 1)

1. **First-Order Time Response** – adjustable gain and time constant, step/ramp inputs, response plots, response markers, error visualization, prediction, and validation.
2. **Frequency Response** – sinusoidal response, amplitude ratio, phase lag, Bode plots, cutoff frequency, prediction, and validation.
3. **Second-Order Systems** – damping ratio, natural frequency, step response, poles, state-space model, and RK4 simulation.
4. **Guess the Sensor** – randomized sensor scenarios, noisy measurements, parameter estimates, hints, and scoring.

## Homework 2 checkpoint modules

### P1 – PID Playground

- Select a first-order or second-order plant.
- Adjust plant parameters, setpoint, and PID gains `Kp`, `Ki`, and `Kd`.
- Adjust the actuator/control-signal limit.
- View the closed-loop output and control signal.
- View rise time, overshoot, settling time, and steady-state error.
- Use the closed-loop PID block diagram and Predict, then check activity.
- Review the assignment validation cases, including P-only time constant and steady-state error, and the PI parameter check.

### P2 – Slow Sensor in the Loop

- Adjust the sensor time constant and plant time constant.
- Adjust PID gains and control-signal limit.
- Compare true plant output with the sensor's measured output.
- View the control signal, true-output overshoot, final error, and sensor lag.
- Use the Predict, then check activity to reason about increasing sensor lag.

## Team and responsibilities

The Homework 1 module owners remain documented in the original project report:

| Team member | Homework 1 responsibility |
|---|---|
| Deyali Qassem | Module 1 – First-Order Time Response |
| Malak Odeh | Module 2 – Frequency Response |
| Rahaf Barakat | Module 3 – Second-Order Systems |
| Noor Shawamreh | Module 4 – Guess the Sensor |

**Homework 2 P1 owner:** Add the assigned team member's name.  
**Homework 2 P2 owner:** Add the assigned team member's name.

Create one GitHub Issue for P1 and one for P2, assign each issue to its module owner, and update the names above before submitting.

## Technologies

- HTML5, CSS3, JavaScript
- Chart.js 4.4.1 (loaded from jsDelivr)
- Git, GitHub, GitHub Pages

The application runs in the browser and does not require a server. An internet connection is required to load Chart.js from the CDN.

## Local testing

1. Download the repository ZIP or clone the repository.
2. Open `index.html` in a modern browser.
3. Check Modules 1–4.
4. Open **Control** in the top navigation.
5. Open P1 and move each PID slider; confirm the response and control plots redraw.
6. Open P2 and increase the sensor time constant; compare the true output and measured output.
7. Test both prediction activities and resize the browser to check the mobile layout.

## Deployment

The existing project is hosted with GitHub Pages from the `main` branch. Keep the same repository and deployment configuration. Back up the current `index.html` before replacing it with the updated checkpoint file, then commit and push the changes.

**Live URL:** https://deyaliqassem.github.io/encs4380-dynamics-21-1/

## AI assistance disclosure

ChatGPT and Claude were used as supporting tools for interface design, HTML/CSS styling, JavaScript structure, debugging, and code organization. Team members must review the code, verify the mathematical models, test the live application, and be able to explain the equations and implementation during the demo.

## Checkpoint note

This package is for the Homework 2 checkpoint (P1 and P2). It is not the final Homework 2 release. The assignment's final release is expected to be tagged `v2.0` after P3, P4, and the remaining requirements are completed.
