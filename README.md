# Holi-World project page

Website for **Holi-World: Building Holistic World Intelligence from Human-Ego Experience**.

This branch contains the static project page, figures and videos. The `main` branch is reserved for project code.

## Local preview

Run from the repository root:

```sh
python3 -m http.server 8000
```

Open [localhost:8000](http://localhost:8000). No build step is required.

- `index.html`: page content, styles and interactions.
- `assets/img/`: logos and research figures.
- `assets/video/`: project video, clips and posters.

Relative asset paths support hosting under a repository subdirectory. `.nojekyll` supports direct static hosting on GitHub Pages.
