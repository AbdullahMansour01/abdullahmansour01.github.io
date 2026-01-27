# Abdullah Mansour - Academic Portfolio

This repository contains the source code for my personal academic website and portfolio. It showcases my education at the University of Houston, my professional experience in management and real estate, and my technical skills in Computer Science.

The site is built using **Jekyll** and hosted on **GitHub Pages**, based on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template.

## 🚀 Getting Started

You can view the live website at: **[Insert your GitHub Pages URL here]**

## 💻 Running Locally

To preview changes on your own machine, you can use Docker (recommended) or a local Ruby environment.

### Option 1: Using Docker (Easiest)

If you have Docker Desktop installed, you don't need to install Ruby manually.

1.  Open your terminal in the project folder.
2.  Run the command:
    ```powershell
    docker compose up
    ```
3.  Open your browser to `http://localhost:4000`.

### Option 2: Using Ruby (Windows/Linux/Mac)

1.  **Prerequisites:** Ensure you have Ruby, Bundler, and Node.js installed.
    *   *Windows:* Install Ruby+Devkit.
2.  **Install Dependencies:**
    ```bash
    bundle install
    ```
    *(Note: If you are on Windows and see a timezone error, run `bundle add tzinfo-data`)*
3.  **Start Server:**
    ```bash
    bundle exec jekyll serve
    ```
4.  Access at `http://localhost:4000`.

## 📂 Project Structure

*   **`_config.yml`**: Main site configuration (title, author, social links).
*   **`_pages/`**: Content pages (e.g., `about.md`, `cv.md`).
*   **`files/`**: Static files for download (e.g., PDF resume).
*   **`images/`**: Images used on the site.

## 📝 Credits

----
*   Original Template: Academic Pages
*   Theme: Minimal Mistakes
