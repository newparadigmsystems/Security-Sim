# 2323 Bravo #1 — Security Control v1.2

A standalone, fictional security dashboard. Open `index.html` in a modern browser, or serve the directory with `python3 -m http.server 8000` and open `http://localhost:8000`. No dependencies or build step are required. For Netlify, deploy this directory as a static site (no build command; publish directory `.`).

- **Quiet** runs normal monitoring checks and does not generate new incidents. Existing incidents remain until resolved.
- **Active** generates one random incident 10–15 minutes after entering the mode or resolving the previous incident.
- **Test** lets you choose and trigger an incident immediately. Resolve the open incident before starting another.
- Select a system or individual item for its details. Select System activity for the full scrolling log; click a column heading to sort it.
- Select the highlighted item to respond to an incident. Response progress continues when the dialog is closed. Some incidents pause for additional actions; the incident remains open until every step is completed.
- Sound is off by default; use the sound button to enable it. Browsers require a user interaction before audio can play.
- Reloading resets the simulation. This is a simulation and does not monitor or control real systems.
