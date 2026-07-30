# Lab Protocols

An internal protocol library built with Zensical.

## Develop in a container

With Docker and the VS Code Dev Containers extension installed:

1. Open this repository in VS Code.
2. Run **Dev Containers: Reopen in Container** from the command palette.
3. In the container terminal, run:

   ```bash
   uv run zensical serve --dev-addr 0.0.0.0:8000
   ```

The environment installs the locked dependencies automatically and opens the
forwarded preview on port 8000. The same configuration can be used by GitHub
Codespaces.

## Preview locally

```bash
uv sync
uv run zensical serve
```

Then open <http://127.0.0.1:8000>.

## Validate

```bash
uv run zensical build --strict
```

## Deploy to GitHub Pages

Pushes to `main` deploy the static site with GitHub Actions. In the GitHub
repository settings, set **Pages > Build and deployment > Source** to
**GitHub Actions**. The published site URL is:

<https://WaymentSteeleLab.github.io/hws-lab-docs/>

Protocol content lives in `docs/`. Copy
`docs/protocols/_template.md` when starting a new protocol.

The project retains `mkdocs.yml` as Zensical's supported compatibility
configuration. This avoids an unnecessary content or configuration rewrite
during the transition.
