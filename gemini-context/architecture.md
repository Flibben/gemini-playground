# Project Architecture

* **Framework:** Astro (Latest)
* **Styling:** Standard Scoped CSS (No Tailwind/Bootstrap). CSS lives inside `<style>` tags in .astro files.
* **Interactivity:** Zero-JS by default. Use CSS animations where possible.
* **Images:** stored in `src/assets/`. Use Astro `<Image />` component.
* **Content:** Blog posts are Markdown (`.md`) files in `src/pages/blog/`.
* **Deployment:** GitHub Pages (Static).