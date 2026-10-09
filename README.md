# Svelte Bodylight — web simulators

Simulators of physiological systems that run in the browser: Modelica models compiled to
WebAssembly, delivered as one HTML file with no server and no network.

- `latest/` — the current version, updated as the project goes on.
- frozen folders (e.g. `medsoft2026/`) — the version an article links to; never changed.

Open `index.html` (Czech) or `en.html` (English) for links to every experiment. A link opens one
experiment in one language: `fmu-lab.html?experiment=<model>/<experiment>&lang=cs`, and a drawn
view with `&view=<name>`.

Built by `cli/build-publish.mjs` from the Svelte Bodylight project; nothing here is edited by hand.
