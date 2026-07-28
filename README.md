# SPECTRUM — Interactive Harmonic Analysis Laboratory

An experimental web project with a scientific aesthetic, visualizing waves, spectra, and complex oscillatory systems in real time.  
Designed for exploring physics, mathematics, signal processing, and for creative experiments with abstract forms.

![SPECTRUM](images/spectrum.png)

---

## What is a “spectrum” and why does it matter?

In physics and mathematics, a **spectrum** is the decomposition of a complex signal into simple harmonic components (sine waves) with different frequencies and amplitudes.  
Our site lets you **see this process** interactively:

- generate waves with various parameters;
- observe their superposition;
- view the frequency composition (spectrum);
- explore Lissajous figures and phase portraits.

This is not just a “nice animation” but a **visual demonstration of the fundamentals of harmonic analysis**, useful for students, engineers, artists, and the curious alike.

---

## Features

### 7 Visualization Modes (switchable via buttons)

| Mode | Description |
|------|-------------|
| Wave | Classic oscilloscope – several stacked waves with adjustable number of harmonics. |
| Spectrum | Frequency spectrum (harmonic amplitudes) as bars – like a spectrum analyser display. |
| Lissajous | Lissajous figures – trajectories of the sum of two perpendicular oscillations. Visualise frequency ratios. |
| 3D Surface | Pseudo‑3D surface showing a wave in time and space. |
| Polar | Polar coordinates – amplitude as radius, time as angle. |
| Phase | Phase portrait – velocity (derivative) vs. displacement. Demonstrates a damped oscillator. |
| Spectrogram | Running spectrogram (time‑frequency map) – a heatmap of the spectrum changing over time. |

---

### Interactive Parameters (sliders)

- **Frequency** – base oscillation frequency.
- **Amplitude** – signal “volume”.
- **Harmonics** – number of additional harmonics (1 to 5).
- **Speed** – animation tempo.
- **Phase** – global phase shift of all waves (0–2π).
- **Damping** – damping coefficient (for the phase portrait).
- **Frequency Ratio** – for Lissajous figures (ratio of two frequencies).

---

### Controls

- **Auto** – automatic parameter variation mode (generative animation).
- **Pause** – freeze time for detailed inspection.
- **Invert** – invert colours (black ↔ white).
- **PNG** – save the current frame as an image.
- **Reset** – restore all parameters to defaults.

---

### Interactivity

- Mouse movement or touch (on phones) changes the wave phase in **Wave** and **Lissajous** modes – you can “play” with the shape just by dragging your finger across the screen.

---

## Responsive Design

The interface automatically adapts to any screen size:
- on desktop – a full control panel at the bottom right;
- on tablets and phones – compact elements optimised for touch input.

---

## Technical Details

- **Stack:** pure HTML, CSS, JavaScript (no external libraries).
- **Graphics:** Canvas 2D with phosphor‑glow and shadow effects.
- **Style:** minimalist, with emphasis on geometry and contrast, black‑and‑white palette (with inversion).
- **Performance:** optimised for smooth operation even on mobile devices.

---

## How to Run

1. Download the `index.html` file.
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge).
3. Enjoy!

---

## License

This project is freely distributed for non‑commercial use.  
Author — **MORAITTI**.

---

## Contributions and Development

If you have ideas for improvement (new modes, audio synthesis, data export) – send suggestions, fork, and experiment.

---

*Science begins with observation. Observe and be amazed.*