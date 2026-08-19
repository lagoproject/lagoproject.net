# LAGO Website Source

This repository contains the source code and documentation content for the public website of the **Latin American Giant Observatory (LAGO)**.

LAGO is a distributed astroparticle observatory operating at continental scale, with detector sites across Latin America and the Iberian region. The collaboration focuses on three main scientific lines:

- Extreme Universe studies
- Space weather phenomena
- Atmospheric radiation at ground level

The website is built with MkDocs and Material for MkDocs, and it publishes collaboration information, research outputs, detector activities, teaching resources, and historical news.

## About the LAGO Collaboration

LAGO is a decentralized collaboration of researchers and institutions across multiple countries in Latin America and Spain. Its detector network spans very different geomagnetic and altitude conditions, from sea level to high mountain sites, enabling a broad scientific program in cosmic-ray and astroparticle physics.

In addition to research, LAGO supports education and training through detector-based teaching activities and open, collaborative scientific practices.

## Project Scope in This Repository

This repository includes:

- Website pages and content under `docs/`
- Site configuration in `mkdocs.yml`
- Theme customizations, templates, and assets
- Tooling for front-end/theme build tasks

Main public sections currently published include:

- About (collaboration and sites)
- Publications (articles, talks, theses, and documents)
- Activities (detectors, teaching, calendar)
- News and milestones
- LAGO-INDICA information
- Contact

## Contributing Content

Contributions should preserve scientific accuracy and consistency with the collaboration's public communication.

- Edit or add Markdown files in `docs/`
- Keep links and navigation aligned with `mkdocs.yml`
- Use clear, concise English for public-facing pages

For contribution workflow and code of conduct, see `CONTRIBUTING.md` and `CODE_OF_CONDUCT.md`.

## Build the Website

### 1. Install Python dependencies

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 2. Run locally (development)

```bash
mkdocs serve
```

The local site is served by default at `http://127.0.0.1:8000`.

### 3. Create a production build

```bash
mkdocs build
```

The generated static site is written to the `site/` directory.

### Optional: rebuild theme/assets tooling

This repository also contains Node.js tooling inherited from Material for MkDocs customization.

```bash
npm install
npm run build
```

## License

**MIT License**

Copyright (c) 2026 LAGO

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to
deal in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
sell copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
