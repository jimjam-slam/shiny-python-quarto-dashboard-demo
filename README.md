# Shiny for Python in Quarto demo

This is a basic Shiny for Python app embedded in a Quarto document.

To run locally, ensure [Quarto](https://quarto.org) and [uv](https://docs.astral.sh/uv/getting-started/installation/) (for Python dependency management) are installed. Then:

```bash
uv sync
source .venv/bin/activate
quarto serve index.qmd
```

Or, to start a new, similar project:

```bash
quarto create # choose a default project, not a website
uv init
uv pip install --upgrade shiny shinywidgets jupyter # and other python packages you need
```
