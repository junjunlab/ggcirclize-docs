# ggcirclize Reference

Sphinx / Read the Docs source for the **ggcirclize** reference manual.

* Package: <https://github.com/junjunlab/ggcirclize>
* Built docs: <https://ggcirclize.readthedocs.io/>

## Build locally

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
sphinx-build -b html . _build/html
```

## Structure

- `conf.py` — Sphinx configuration (MyST + sphinx-book-theme).
- `index.md` — landing page and table of contents.
- `chapters/*.md` — one page per chapter (converted from the original bookdown).
- `images/` — figures referenced by the chapters.
- `.readthedocs.yaml` — Read the Docs build configuration.
