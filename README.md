# YDSE

Young's Double Slit Experiment (YDSE) is an interactive educational simulator that visualizes the classic wave-particle duality experiment in real time. The project renders a 3D-inspired quantum scene where particles pass through a double-slit apparatus and build up an interference pattern on a screen.

It is designed as a visual, browser-based demo for learning how wavelength, coherence, emission rate, and particle type influence the observed result.

## Features

- Interactive 3D-style double-slit particle simulation
- Switch between photon and electron modes
- Adjustable wavelength, emission rate, and coherence
- Real-time interference pattern visualization
- Intensity graph for observing fringe behavior
- Responsive control panel for experimentation
- Educational physics feedback in the UI
- Static HTML/CSS/JavaScript implementation with no framework required

## Live Demo

The project is configured for deployment on Vercel and includes static rewrites for the main app entry point.

## Project Structure

```text
YDSE/
├── index.html          # Main app entry point
├── YDSE.html          # Alternate app entry (same simulation)
├── vercel.json         # Vercel static deployment config
├── README.md           # Project documentation
└── .gitignore          # Optional repo metadata (if added later)
```

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Canvas rendering
- Vercel static hosting

## Run Locally

Because this is a static web project, you can run it in a few simple ways:

### Option 1: Open directly in a browser

1. Clone the repository.
2. Open `index.html` directly in your browser.

### Option 2: Use a local web server

From the project folder:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

This repository is compatible with Vercel static hosting. The `vercel.json` file routes the app root to `index.html` and exposes the alternative `YDSE.html` page via URL rewrites.

## How to Use

- Pick a particle type: photon or electron
- Adjust wavelength to change interference spacing
- Increase or decrease emission rate
- Change coherence to influence clarity of the pattern
- Observe the pattern build-up and intensity curve

## Physics Summary

The simulation demonstrates the core idea behind Young's double-slit experiment:

- Particles behave like waves when passing through the slits
- Over time, individual impacts still appear as discrete events
- The accumulated distribution creates an interference pattern
- Changing experimental parameters directly affects the observed pattern

This makes the project a useful visual aid for understanding wave-particle duality and quantum behavior.

## License

This project does not currently include a license file. If you plan to share or distribute it publicly, consider adding an appropriate open-source license such as MIT.

## Author

Project repository: `Pawanraje-kadam/YDSE`

## Notes

This is a front-end physics visualization and educational demo. It is intended for learning and demonstration rather than scientific simulation accuracy.
