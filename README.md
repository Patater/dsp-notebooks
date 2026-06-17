# DSP Notebooks

Here you'll find my Jupyter notebooks exploring various DSP concepts. I mainly
use numpy, scipy.signal, and matplotlib.


## A note on using Quarto to create and render these notebooks

If you want to make html and render from the qmd files, you must first have
quarto installed on your system. Download the latest version from the [official
Quarto website](https://quarto.org/docs/get-started/index.html).
Afterwards, (on Debian/Ubuntu)

```shell
  sudo dpkg -i <directory_where_deb_was_downloaded>
```

Then, I recommend creating a python virtual environment and pip installing
all the modules in this folder.
```shell
python3 -m venv venv
source ./venv/bin/activate
# Use source ./venv/bin/activate.fish for the fish shell

pip install quarto
pip install -r requirements.txt
```

To view a live render of the Quarto document while in your text editor, run
`quarto render <file_you're_making>`

### Open Source License

The notebooks are licensed with AGPL-3.0-or-later.
