# RoboFAPE project page

Project website for **RoboFAPE: Failure-Aware Progress Estimation for Robot Manipulation**.

- Website: https://luyingxi35.github.io/RoboFAPE/
- Code: https://github.com/luyingxi35/RoboFAPE-code
- Paper: [PDF](paper/RoboFAPE.pdf)

A static site with no build dependencies. `index.html` contains the page, styles, and keyboard-accessible result tabs. Paper figures are under `figures/`; the current PDF is under `paper/`. Local asset paths are relative for GitHub Pages project-site hosting.

Preview from this directory:

```sh
python3 -m http.server 8765
```

Open http://localhost:8765. GitHub Pages serves the `main` branch from `/ (root)`.

The code release covers trajectory collection, progress labeling, task configurations, and reproduction instructions. Policy checkpoints are supplied by the user; the trajectory dataset is not yet public.
