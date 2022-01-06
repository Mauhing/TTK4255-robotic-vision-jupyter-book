# Welcome to TTK4255-robotic-vision-jupyter-book
These jupyter-(note)book servers as supplementary and does not define the syllabus.
It is handful to use it **during** the lecture.

You can also use binder to change the code and see the effect immidiately. It is completely web browser based and not packages need to be install.
However, if you want to run it locally, you can click the githud hyperlink at the top
right corner.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Mauhing/TTK4255-robotic-vision-jupyter-book/main)

```{caution}
This jupyter notebooks does not cover everything of the lecture slide.
It is just a supplementary in a interactive way.
```
## Use it online (The most easy way)
Just click the badge under.  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Mauhing/TTK4255-robotic-vision-jupyter-book/main)

## Use it offline (Run much faster than binder)
### Installation
You should have `conda` package management. If you do not have it install, i suggest you download and install it with anaconda. To install anaconda, click [here](https://www.anaconda.com/products/individual). Now, you can do the following in your terminal:
1. `git clone https://github.com/Mauhing/TTK4255-robotic-vision-jupyter-book.git`
2. `cd TTK4255-robotic-vision-jupyter-book`
3. `conda env create -f environment_local.yml` NB!!! It is `environment_local.yml`, not `environment.yml`.

### Use jupyter-notebook
5. `jupyter-lab .`
6. Open the jupyter-notebook you want and paly

### Compiler jupyter-book
7. `jupyter-book build . --all`
8. Use your browser to open `_build/html/index.html`
9. Enjoy.
