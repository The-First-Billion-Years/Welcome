# Computing Tips

## General

- [Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Backup/large file storage

- [ERDA](https://erda.ku.dk) is a free ~TB file storage system for University of Copenhagen. I recommend you setup an account (easy) and mount it as a local drive on your laptop via SSHFS (harder) -- follow the instructions clicking on the green head, then "Setup".
- [MODI](https://erda.dk/public/MODI-user-guide.pdf) is the UCPH cluster you can use for larger jobs, linked to ERDA. Ting-Yi and Charlotte wrote some guides/scripts for running jobs on [MODI](https://github.com/The-First-Billion-Years/MODI_scripts)

## OS / bash

- [ssh]

## Python

- [Anaconda](https://docs.anaconda.com/anaconda/install/): If you haven't already gotten a working Python installation set up, Anaconda is the easiest and most flexible option. Its particularly useful for setting up new environments with different Python versions etc.
- [Astropy](https://docs.astropy.org/en/stable/): Before trying to code up a common task in Python, its always worth checking whether there is already a function or class that does the same in Astropy. These will usually be more efficient or flexible than doing it you're own way. The coordinates, fits IO and fitting sub-modules will likely be particularly useful.
- [Python style guide](https://docs.python-guide.org/writing/style/)
- [Timing and memory profiling](https://pynash.org/2013/03/06/timing-and-profiling/) - save your time *and* the environment!! :)
- [How to make a pip installable python package](https://nsls-ii.github.io/scientific-python-cookiecutter/index.html)
- [Python for Astronomers tutorials](https://prappleizer.github.io/index.html) - mostly plotting and some interactions
- [Python for Astronomers tutorials #2](https://python4astronomers.github.io/index.html#) - more astro related, fits files, astropy etc
- [Custom fonts for matplotlib on linux](https://andresabino.com/2015/08/18/fonts-and-matplotlib/)
- ['Cheat sheet' for Matplotlib](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/Python_Matplotlib_Cheat_Sheet.pdf)
- [Jupyter notebook extensions](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html) - make a table of contents, time each cell etc.

## Other tools

- [Topcat](http://www.star.bris.ac.uk/~mbt/topcat/): While Python should be the main approach for most analysis tasks, it's not the easiest for exploring the data. Topcat is really useful for loading catalogues, cross-matching between multiple datasets and performing quick plots.

