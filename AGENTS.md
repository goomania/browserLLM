# AGENTS.md

## Project Conventions

- This project is a static frontend-only web app. Do not add any backend code, server logic, or build tooling.
- Keep the entire app in a single `index.html` file containing all HTML, CSS, and JavaScript.
- Use WebLLM via CDN and import it from `https://esm.run/@mlc-ai/web-llm`.
- Use ES modules with `<script type="module">`.
- Use modern CSS and define theme values with CSS custom properties.
- Do not add `npm`, `node_modules`, `package.json`, or any Node-based setup.
- The app must work without any API keys.

## Local Testing

- Serve the app locally with `python -m http.server 3000`.
- Test the app through that local HTTP server rather than opening the file directly.
