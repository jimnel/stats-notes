# Stats Notes

A short course on probability and statistics, taught through hands-on [NumPy](https://numpy.org) code in Jupyter notebooks.

📖 **Read the course online:** https://jimnel.github.io/stats-notes/

## About

Each notebook covers one idea. It builds the idea from scratch with simulation and small NumPy implementations, so you can see how it works rather than calling a library function. The notebooks are run on every push to `main` and published with [Jupyter Book](https://jupyterbook.org). Every page on the site shows real, up-to-date output.

## Running locally

```bash
pip install -r requirements.txt

# Open the notebooks
jupyter lab notebooks/

# Or preview the full site (executes the notebooks)
jupyter book start --execute
```

## Repository layout

| Path | Contents |
| --- | --- |
| `notebooks/` | Course notebooks. Each one is added to the site automatically. |
| `index.md` | Landing page of the site |
| `myst.yml` | Jupyter Book configuration |
| `.github/workflows/deploy.yml` | Runs the notebooks, then builds and deploys the site to GitHub Pages |

## Adding a notebook

1. Add a `.ipynb` file to `notebooks/`.
2. Add any new packages it imports to `requirements.txt`.
3. Push to `main`. If any cell raises an error, the build fails and the site isn't updated.
