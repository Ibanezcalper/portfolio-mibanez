# Professional portfolio of Mario Ibañez

This repository contains the codebase and configuration for the professional portfolio website of Mario Ignacio Ibañez Castro. The site is designed as an interactive, high-performance platform to showcase his work experience, data science and development projects, education, and certifications.

## General description

The project is built using a modern architecture based on Astro, a web framework focused on performance and fast delivery of interfaces by minimizing client-side JavaScript. The visual design is implemented using Tailwind CSS, ensuring a clean, responsive layout optimized for mobile and desktop screens.

Additionally, the repository integrates a structured YAML data file that serves as the source of truth for the developer's resume, facilitating professional information updates and ensuring consistency between the website and printed or PDF versions of the resume.

## Problem it solves

Data science, economics, and cloud engineering professionals often require a centralized, dynamic, and professional way to demonstrate their skills. This repository solves the following common challenges:

- **Lack of interactive visibility**: It allows recruiters and interested parties to directly explore machine learning, cartographic automation, and cloud development projects, bypassing the limitations of traditional static resumes.
- **Complex updates**: Centralizing professional data in a readable YAML format avoids the need to edit HTML or Astro code directly for routine career timeline updates.
- **Poor web performance**: By utilizing Astro, the resulting web page loads almost instantaneously, optimizing the user experience and improving search engine optimization (SEO).

## Technologies used

The portfolio is supported by a set of modern technologies for web development and configuration management:

- **Astro (version 5.17.3)**: Used as the web framework to generate optimized static pages.
- **Tailwind CSS (version 3.4.1)**: Used for responsive layout and visual styling via utility classes.
- **TypeScript (version 5.3.3)**: Used to add static typing and improve code robustness.
- **YAML**: Used in the `mario_master.yaml` file to structure professional and personal details in a readable way.
- **Astro robots-txt**: Used to automatically generate the `robots.txt` file, optimizing search engine indexing.

## Repository structure

The organization of the main directories and files in this project is detailed below:

- **`src/`**: Main source code directory for the Astro application.
  - **`src/components/`**: Reusable user interface components, including `Header.astro`, `Experience.astro`, `Projects.astro`, `AboutMe.astro`, `Education.astro`, and `Technologies.astro`.
  - **`src/layouts/`**: Base layouts to structure the page content.
  - **`src/pages/`**: Application pages. The main entry point is defined in `index.astro`.
- **`public/`**: Static assets directly accessible by the browser, such as project screenshots, icons, and visual assets.
- **`mario_master.yaml`**: Master configuration file compiling profile summary, strengths, work history, projects, certifications, and education.
- **`Mario Ibañez.pdf` and `Mario_Ibanez_CV_2026_Analista.pdf`**: PDF versions of the resume available for download directly from the portfolio.
- **`package.json`**: Node.js dependency configuration and build scripts.
- **`astro.config.mjs`**: Configuration file for the Astro framework build steps and integrations.
- **`tailwind.config.mjs`**: Configuration file defining custom rules and options for Tailwind CSS.

## Specific use cases

This repository is designed for the following specific scenarios:

- **Web portfolio deployment**: Hosting the site on static deployment platforms (such as Netlify, Vercel, GitHub Pages, or Oracle Cloud Infrastructure) to provide an online professional profile accessible from any browser.
- **Technical skill showcase**: Providing evidence of modern web development practices, responsive design, and performance tuning for a profile focused on cloud engineering and data analytics.
- **Resume portability**: Accessing structured details in the master YAML file to import data or feed other resume builders.

## When to use this repository

It is recommended to use or clone this repository if you want to:

- Deploy a local or production instance of the portfolio website.
- Update the work experience timeline, projects, or certifications shown in the portfolio of Mario Ibañez.
- Review a practical example of modern frontend development using independent Astro components paired with Tailwind CSS.

## Instructions for installation and local usage

Follow these steps to set up and run the development environment on your local machine.

### Prerequisites

Ensure you have the following tools installed on your system:

- Node.js (version 18 or higher recommended)
- A Node package manager such as npm (included with Node.js)

### Configuration steps

1. Install the project dependencies using the package manager:
   ```bash
   npm install
   ```

2. Start the local development server:
   ```bash
   npm run dev
   ```
   Or alternatively:
   ```bash
   npm start
   ```

3. Open your browser and navigate to the address shown in your terminal, which typically defaults to `http://localhost:4321`.

4. Modify any file in the `src/` directory. Astro will automatically reflect changes in your browser via its hot module replacement system.

5. To build the project for production deployment, run:
   ```bash
   npm run build
   ```

6. To preview the production build locally before deploying, run:
   ```bash
   npm run preview
   ```

## Data and single source of truth

The information displayed on the website matches the structured data in `mario_master.yaml`. Keeping this file updated is critical when updating professional details. While the web UI layout relies on individual Astro files like `Experience.astro` or `Projects.astro`, the YAML file serves as the master record to maintain alignment with the distributed PDF resume versions.

## License

This project is licensed under the terms described in the `LICENSE.md` file located in the root of this repository.
