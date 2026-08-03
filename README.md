# TITAN — platform microsite

Single-page site for the TITAN heavy-lift UAV platform.
Static HTML, no build step. Open `index.html` or serve the folder.

    index.html      whole site — markup, styles and scripts inline
    media/          hero video, poster, payload configuration renders

**Configurator** — five payload configurations that auto-advance every 4.8s,
pause on hover, stop on click and resume after 14s idle. Only runs while the
section is on screen, and respects `prefers-reduced-motion`.

**Theming** — change `--accent` at the top of the `<style>` block.
