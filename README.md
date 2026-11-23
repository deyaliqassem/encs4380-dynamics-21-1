# Dynamic Characteristics Interactive Toolkit

**ENCS4380 – Interfacing Techniques**  
Birzeit University  
Instructor: Dr. Wasel Ghanem

## Live website

[Open the toolkit](https://deyaliqassem.github.io/encs4380-dynamics-21-1/)

## Project overview

The toolkit demonstrates sensor dynamics and feedback control through interactive models, simulations, plots, and prediction activities. Open **Control · Homework 2** in the main navigation to access the PID modules and the Micromouse motor example.

## Homework 1 modules

| Module | Owner | Features |
|---|---|---|
| 1 – First-Order Time Response | Deyali Qassem | Step and ramp inputs, adjustable gain and time constant, response markers, and error plots |
| 2 – Frequency Response | Malak Odeh | Sinusoidal response, amplitude ratio, phase lag, Bode plots, and cutoff frequency |
| 3 – Second-Order Systems | Rahaf Barakat | Damping ratio, natural frequency, poles, state-space model, and RK4 simulation |
| 4 – Guess the Sensor | Noor Shawamreh | Random sensor scenarios, noisy measurements, parameter estimation, hints, and scoring |

## Homework 2 modules

| Module | Owner | Features |
|---|---|---|
| P1 – PID Playground | Rahaf Barakat | First- and second-order plants, adjustable setpoint and PID gains, actuator limits, response metrics, and reference validation cases |
| P2 – Slow Sensor in the Loop | Deyali Qassem | Adjustable sensor and plant time constants, overlaid true and measured outputs, and a control-signal plot |
| P3 – Digital PID | Malak Odeh | Adjustable sampling time and PID gains, an anti-windup toggle, a stair-step control plot, and generated Arduino loop code with a copy button |
| P4 – Tuning Challenge | Noor Shawamreh | A hidden random first-order plant, adjustable PID gains, pass/fail results for overshoot, settling time, and final error, and a score out of three |

Each PID module includes a **Predict, then check** activity.

## My system – Micromouse drive motor

This section illustrates a first-order motor model and a PI controller. It plots the simulated speed and PWM duty against the design target. The example uses assumed model parameters. The encoder step test and identification of the physical motor parameters remain pending.

## Running the toolkit

Open the live site or open `index.html` in a modern browser. The toolkit uses HTML, CSS, JavaScript, and Chart.js 4.4.1. An internet connection is needed to load Chart.js from jsDelivr. GitHub Pages serves the site from the `main` branch.

## AI assistance disclosure

ChatGPT and Claude assisted with interface styling, JavaScript implementation and debugging, and simulation checks.
