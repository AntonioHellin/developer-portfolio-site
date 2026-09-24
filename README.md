# developer-portfolio-site

A developer portfolio and project showcase website styled with custom Sass/SCSS architecture, featuring automated CSS compilation and multi-page layouts.

## Project Overview

`developer-portfolio-site` is a personal portfolio website presenting developer achievements, project case studies, biography, and contact inquiries. Styled using modular SCSS files with variable definitions and mixins, the build toolchain compiles SCSS source code into high-performance distribution CSS within `dist/css`.

## Features

- **Multi-Page Site Layout**:
  - `dist/index.html`: Hero introduction and welcome banner.
  - `dist/about.html`: Detailed professional biography, skills overview, and career timeline.
  - `dist/work.html`: Project portfolio showcase with interactive demo/source links.
  - `dist/contact.html`: Contact coordinates, social media links, and inquiry form.
- **Sass Architecture**: Modular partials for variables, typography, layouts, and mixins.
- **Live SCSS Compilation**: Build script watching for SCSS edits and recompiling in real-time.

## Prerequisites

- Node.js (version 14.x or newer).
- npm (Node Package Manager).

## Installation/Build

1. Clone the repository:
   ```bash
   git clone https://github.com/AntonioHellin/developer-portfolio-site.git
   cd developer-portfolio-site
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Compile and watch Sass stylesheets:
   ```bash
   npm run sass
   ```

## Usage

1. Open `dist/index.html` in your web browser, or serve using a static web server:
   ```bash
   npx serve dist
   ```
2. Navigate between Home, About, My Work, and Contact pages.

## License

This project is licensed under the [ISC License](LICENSE).
