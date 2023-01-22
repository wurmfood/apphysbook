# AP Physics I book

Jupyter-Book version of AP Physics I information for my class.

Requirements:
- `venv` with `jupyter-book`, `matplotlib`
    - `python3 -m venv .venv`
    - `source .venv/bin/activate`
    - `python3 -m pip install --upgrade pip`
    - `pip install -U matplotlib`
- texlive
    - Install things appropriate to the system. I just install as root, leaving
        out most of the optional languages and some of the packages.
    - It helps to set up the extra links.

## LaTeX figures

In the `figures` directory there is a script that will take the Tikz figures
that are in there and turn them into images. You'll need to run that before
building everything.

