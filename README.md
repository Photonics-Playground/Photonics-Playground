<p align="center"><img src="src/brand/social-preview.png" alt="Photonics Playground" width="720"></p>

# Photonics Playground

**Learn integrated photonics hands-on.** Every page is a live simulation that runs entirely in your browser, on any device, with nothing to install.

**▶ Open the playground: https://photonics-playground.github.io/photonics-playground/**

## What's inside

| Chapter | Tools |
|---|---|
| 1 · How light is guided | How Light Is Guided, Waveguide Mode Solver |
| 2 · Classic building blocks | Component Workshop (directional coupler, Y-splitter, MMI, ring resonator, grating coupler) |
| 3 · Inverse design | How Inverse Design Works, Inverse Design 2D, Grating Coupler Optimizer, Design Studio |

Under the hood

- a finite-difference eigenmode solver for waveguide cross-sections (quasi-TE and quasi-TM)
- a 2D frequency-domain finite-difference (FDFD) wave solver with absorbing boundaries and mode sources and monitors
- adjoint gradients with an Adam optimizer, density filtering and projection for inverse design

All computation happens locally in the browser (JavaScript and Web Workers). There is no server and no account.

## Run it locally

Open `docs/index.html` in a browser.


## License

- Code under the [MIT License](LICENSE).
- Texts, figures, images and videos under [CC BY 4.0](LICENSE-CONTENT).
- Fonts Instrument Sans and IBM Plex Mono under the SIL Open Font License 1.1.

## Citation

If you use Photonics Playground in teaching or research, please cite it. GitHub shows a "Cite this repository" button based on [CITATION.cff](CITATION.cff).

Feedback and bug reports are welcome as [issues](../../issues).
