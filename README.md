# halchemylab.github.io

This is the personal portfolio website of Henry Pai, showcasing expertise in fullstack development, data science, AI/ML, RPA, marketing, and business strategy. It's continuously updated to reflect new projects and skills.

**URL:** [halchemylab.github.io](https://halchemylab.github.io)

---

## Key Features

-   Showcase of professional expertise and portfolio projects.
-   Detailed case studies for various projects.
-   Information about Halchemy Labs.
-   Contact information.

---

## Technologies Used

This project leverages a combination of static site generation with modern front-end development tools:

*   **Jekyll:** A static site generator for building the website.
*   **HTML5/CSS3/JavaScript:** Core web technologies.
*   **Bootstrap:** Front-end component library for responsive design.
*   **Sass:** CSS preprocessor for maintainable stylesheets.
*   **Prettier:** Code formatter for consistent code style across HTML, CSS, and JavaScript.
*   **ESLint:** Linter for identifying and reporting patterns in JavaScript code.
*   **Stylelint:** Linter for enforcing consistent conventions and avoiding errors in CSS.
*   **Git:** Version control system.

---

## Project Structure

The repository follows a standard Jekyll structure, augmented with a `package.json` for managing front-end development dependencies and scripts.

```
.
├── _config.yml               # Jekyll site configuration
├── _includes/                # Reusable HTML snippets (e.g., header, footer, sections)
├── _layouts/                 # Jekyll layout templates (e.g., default.html)
├── assets/                   # Static assets like CSS, JS, images, and vendor libraries
│   ├── css/
│   ├── img/
│   └── js/
│   └── vendor/
├── case-study-1.html         # Example project page
├── index.html                # Main landing page
├── package.json              # Node.js dependencies and scripts for linting/formatting
├── README.md                 # This file
└── ...                       # Other project/portfolio pages
```

---

## Running Locally

To view the website on your local machine, you need to have Ruby, Jekyll, and Node.js installed.

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/halchemylab/halchemylab.github.io.git
    cd halchemylab.github.io
    ```

2.  **Install Ruby Dependencies:**
    Open your terminal and navigate to the repository's root directory. Then, run the following command to install the required gems:
    ```bash
    bundle install
    ```

3.  **Install Node.js Dependencies:**
    Install development dependencies for linting and formatting:
    ```bash
    npm install
    ```

4.  **Run the Jekyll Server:**
    After installations are complete, run the following command to start the Jekyll server:
    ```bash
    bundle exec jekyll serve
    ```

5.  **View Your Website:**
    Open your web browser and navigate to `http://localhost:4000`.

---

## Linting and Formatting

This project uses Prettier, ESLint, and Stylelint to maintain code quality and consistency.

*   **Format Code:** Automatically formats HTML, CSS, and JavaScript files.
    ```bash
    npm run format
    ```
*   **Lint CSS:** Checks CSS files for style errors and enforces conventions.
    ```bash
    npm run lint:css
    ```
*   **Lint JavaScript:** Checks JavaScript files for errors and enforces style guidelines.
    ```bash
    npm run lint:js
    ```

---