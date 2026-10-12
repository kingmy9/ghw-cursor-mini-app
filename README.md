# SG90 Servo Calculator

A single-page web app (plain HTML/CSS/JS) built with **Cursor** (Agent, Grok 4.6 model) for MLH Global Hack Week — *CHALLENGE 1: Build a Mini App with Cursor*.

## Features
- Angle slider + number input (0–180°)
- PWM pulse width (default 500–2400 µs) and duty cycle at 50 Hz
- Arduino lines: `servo.write(angle)` and `servo.writeMicroseconds(us)`
- Animated servo horn dial
- Presets 0 / 45 / 90 / 135 / 180°, min/max pulse calibration, dark/light toggle

## Run
Open `index.html` in any browser.

## How Cursor helped
Cursor scaffolded the whole page from one prompt, then added presets, calibration and the theme toggle on request — and fixed a bug where the min/max calibration fields overwrote each other.
