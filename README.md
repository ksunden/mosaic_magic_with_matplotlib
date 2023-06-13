# Mosaic Magic with Matplotlib

## Scipy 2023 Tutorial

Communicating scientific data often relies on making comparisons between multiple datasets.
Join the Matplotlib team to learn about creating multi-axis figures to display such data side-by-side.
This intermediate level tutorial will cover a variety of tools for making multi-axis figures.
Of particular focus will be the subplot_mosaic and the layout engines: tight, constrained, and compressed.
This tutorial will emphasize the use of Matplotlib's Object Oriented (OO) API and why that is generally recommended over the pyplot (plt) API.

This tutorial is designed for users of Matplotlib who want to learn more about how to lay out complicated figures.
Bring a figure you like that you want to replicate the layout of or one that you'd like to improve.

### Installation

#### Conda (Recommended)

If you do not yet have conda (or mamba) installed, please [install miniconda](https://docs.conda.io/en/latest/miniconda.html).

- Clone this repository:

```bash
$ git clone https://github.com/ksunden/mosaic_magic_with_matplotlib
$ cd mosaic_magic_with_matplotlib
```

- Create a conda envioronment:

```bash
$ conda env create -f envioronment.yml
$ conda activate mosaic_magic_mpl
```

- Start jupyter lab

```bash
$ jupyter lab
```

#### pip

- Clone this repository:

```bash
$ git clone https://github.com/ksunden/mosaic_magic_with_matplotlib
$ cd mosaic_magic_with_matplotlib
```

- Create a virtual envioronment:

```bash
$ python -m venv mosaic_magic_mpl
$ # Linux/macos
$ source mosaic_magic_mpl/bin/activate
$ # windows cmd
$ mosaic_magic_mpl\Scripts\activate.bat
$ # windows powershell
$ mosaic_magic_mpl\Scripts\Activate.psi
```

- Install the requirements:

```bash
$ python -m pip install -r requirements.txt
```

- Start jupyter lab

```bash
$ jupyter lab
```



### Outline

This tutorial is designed for users of Matplotlib who want to learn more about how to lay out complicated figures.
Bring a figure you like that you want to replicate the layout of or one that you'd like to improve.

 - Introduction (10 mins) (part 00)
 - Parts of a figure. What makes up a figure (20 mins) (part 01)
   - (Build up to: https://matplotlib.org/stable/gallery/showcase/anatomy.html)
 - Creating a figure with a single axes (10 mins) (part 02)
 - Object oriented model of interacting with axes (20 mins) (part 02)
    - e.g. Prefer ax.plot over plt.plot
 - Multi axes figures (~1.5 hr) (part 03-04):
    - subplots (10 mins)
    - subplot_mosaic (30 mins)
    - grid_spec (20 mins)
    - subplot2grid (5 mins)
    - add_axes (5 mins)
    - add_subplot (5 mins)
    - Inset and zoomed axes (5 mins)
 - Layout engines (30 mins) (part 05)
    - Introduction (10 mins)
    - Constrained Layout (10 mins)
    - Compressed Layout (5 mins)
    - Tight Layout (5 mins)
 - Labeling figures (20 mins) (part 06)
    - Axis/figure labels (10 mins)
    - Legends (5 mins)
    - Colorbars (5 mins)
 - Subfigures (10 mins) (part 07)
 - Conclusions/questions (20 mins) (part 08)

