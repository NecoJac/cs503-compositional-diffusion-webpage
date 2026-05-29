# Test-Time Compositional Control for Diffusion Models

This repository contains the source code for our EPFL 2026 Spring CS-503 Visual Intelligence project webpage:

**Test-Time Compositional Control for Diffusion Models**  
Bridge-Correction and SMC / FKC-PoE for Panoramic Text-Prompt Composition

The webpage summarizes the project motivation, related work, method, experiments, conclusions,
individual contributions, and references.

## Links

- Project code: [NecoJac/cs503-compositional-diffusion](https://github.com/NecoJac/cs503-compositional-diffusion)
- Website source: [NecoJac/cs503-compositional-diffusion-webpage](https://github.com/NecoJac/cs503-compositional-diffusion-webpage)
- Course: EPFL CS-503 Visual Intelligence, Spring 2026

## Authors

- [Yunyi Chen](https://github.com/C-Yunyi)
- [Xinran Wang](https://github.com/AmbitiousOcean)
- [Shengze Jiang](https://github.com/NecoJac)
- [Hantao Zhang](https://github.com/kanydao)

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
