# Test-Time Compositional Control for Diffusion Models

This repository contains the source code for our EPFL 2026 Spring CS-503 Visual Intelligence project webpage:

**Test-Time Compositional Control for Diffusion Models**  
Bridge-Correction and SMC / FKC-PoE for Panoramic Text-Prompt Composition

The webpage summarizes the project motivation, related work, method, experiments, conclusions,
individual contributions, and references.

## Links

- Project code: [NecoJac/cs503-compositional-diffusion](https://github.com/NecoJac/cs503-compositional-diffusion)
- Website source code: [NecoJac/cs503-compositional-diffusion-webpage](https://github.com/NecoJac/cs503-compositional-diffusion-webpage)
- Website: [cs503-compositional-diffusion-webpage](https://necojac.github.io/cs503-compositional-diffusion-webpage/)
- Course: [EPFL CS-503 Visual Intelligence, Spring 2026](https://edu.epfl.ch/coursebook/en/visual-intelligence-CS-503)

## Authors and Contributions

- [Hantao Zhang](https://github.com/kanydao)  &mdash; developed the bridge-correction theoretical
              formalism (DiffCollage as $R\equiv 1$ projection, identification of $\nabla\log R$),
              adapted the FKC-PoE sampler to the SD 1.5 bridge composition setting, and led the
              50+ configuration sweep design.
- [Yunyi Chen](https://github.com/C-Yunyi)  &mdash; implemented the bridge-worker framework on top of
              Stable Diffusion 1.5; managed window slicing, slerp prompt interpolation, and the
              per-method composition rules.
- [Shengze Jiang](https://github.com/NecoJac) &mdash; co-implemented the bridge-worker framework;
              integrated the Tweedie corrector and DDIM scheduler; executed the 50+ configuration
              sweep and the three-prompt panorama runs.
- [Xinran Wang](https://github.com/AmbitiousOcean)  &mdash; designed the seam-MSE / seam-max evaluation
              protocol, curated the prompt set, and produced the qualitative comparison grids.
- All four authors discussed scope decisions and jointly wrote this report, the slides,
              and this webpage.


## Repository Structure

- `index.html` - main webpage content
- `static/figures/slides/` - slide images used throughout the page
- `static/slides.pdf` - project slides linked from the webpage
- `static/css/` - Bulma, template, and page styling
- `static/js/` - template JavaScript dependencies
- `assets/` - static assets such as the EPFL logo

## Local Preview

Because this is a static webpage, it can be previewed by opening `index.html` directly in a browser.
For a local server preview:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Acknowledgements

This webpage is based on the
[EPFL-VILAB CS-503 project webpage template](https://github.com/EPFL-VILAB/cs503-project-webpage-template),
which is adapted from the
[Nerfies website template](https://github.com/nerfies/nerfies.github.io).
