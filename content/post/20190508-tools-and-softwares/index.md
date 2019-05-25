+++
date = "2019-05-08T9:00:00"
draft = false
tags = ["tools", "softwares"]
title = "Tools and Softwares for adademic reserach"
math = true
summary = """
Here I list some tools and softwares that I used in my research.
"""
+++

## Server command

- GPU server at Stanford **ssh -Y yufeng@10.109.1.20**
- GPU server at CUPB **ssh -X wyf@192.168.187.103** (IP: 192.168.187.x)
- CPU server at CUPB **ssh -X zhouhui@192.168.100.x** (IP: 192.168.102.x)

- **kill -9 PID** to kill process on GPUs with PID in nvidia-smi.

- **evince text.pdf** to display pdf.

- [rsync](https://en.wikipedia.org/wiki/Rsync) is a utility for efficiently transferring and synchronizing files between a computer and an external hard drive and across networked computers by comparing the modification times and sizes of files. 
    
    **rsync -r -v ./text.md yufeng@10.109.1.20:/home/yufeng/** 
    
    **rsync -r -v yufeng@10.109.1.20:/home/yufeng/ ./text.md**


## Programming language

- [Rstudio](https://www.rstudio.com/) [How to install](https://www.cnblogs.com/orange-lover/p/7400878.html)

- [Python](https://www.python.org/)

- [CME 193 - Introduction to Scientific Python](http://web.stanford.edu/~schmit/cme193/index.html)

- [Scipy](https://scipy.org/) is a Python-based ecosystem of open-source software for mathematics, science, and engineering. In particular, these are some of the core packages:

    - [NumPy](http://www.numpy.org/) is the fundamental package for scientific computing with Python.
    - [Matplotlib]()
    - [SciPy library]()
    - [pandas]()
    
- [C++](http://www.cplusplus.com)




## General tools 

- [Library Genesis](http://gen.lib.rus.ec/) for downloading books.

- [Scihub](http://sci-hub.tw/) for downloading journal papers.

- [slides](https://slides.com/) is a place for creating, presenting and sharing slide decks.

- [Inkscape](https://inkscape.org/) is a professional vector graphics editor for Windows, Mac OS X and Linux. It's free and open source.

- [pdftk](https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/) is our friendly graphical tool for quickly merging and splitting PDF documents and pages. 

- [The Convert Command](https://people.debian.org/~naoliv/misc/imagemagick/link/www/convert.html)

- [Texlive]() and [Texmaker]() for Latex.

- [TeXmacs](http://www.texmacs.org/tmweb/home/welcome.en.html)

- [Sublime]()

- [Visual Studio Code](https://code.visualstudio.com/) 

- [Overleaf](https://www.overleaf.com/) is the easy to use, online, collaborative LaTeX editor.

- [Beamer theme Matrix](https://hartwork.org/beamer-theme-matrix/)

- [Beamer theme gallery](http://deic.uab.es/~iblanes/beamer_gallery/individual/AnnArbor-beaver-default.html)

- [Latex symbols](http://www.mohu.org/info/symbols/symbols.htm)

- [Quizlet](https://quizlet.com/latest) is the easiest way to study, practice and master what you're learning.


- [Anaconda]()

- [Jupyter nbviewer](https://nbviewer.jupyter.org/) is A simple way to share Jupyter Notebooks.


- [Pandoc](https://pandoc.org/)

- [Markdown]()

    - [Dillinger](https://dillinger.io/) is an online Markdown editor.
    - [Typora](https://www.typora.io/) is Markdown editor, Markdown reader.

- [Git](https://git-scm.com/) is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

    - [Bitbucket](https://www.atlassian.com/git/tutorials)
    

- [brew](https://brew.sh/)

- [Matlab]()

- [CUDA]()



- [Chebfun](https://www.chebfun.org/) is an open-source package for computing with functions to about 15-digit accuracy.

- [Intel Parallel Studio XE 2015](https://software.intel.com/en-us/parallel-studio-xe) ([How to Install](https://blog.csdn.net/sowhatgavin/article/details/71055032?locationNum=6&fps=1))
  
    ```bash
    tar zxvf parallel_studio_xe_2015.tgz
    cd  parallel_studio_xe_2015
    ./install.sh
    ```
    ```bash
    source $HOME/intel/composer_xe_2015.0.090/bin/iccvars.shintel64
    source $HOME/intel/composer_xe_2015.0.090/bin/ifortvars.shintel64
    source $HOME/intel/composer_xe_2015.0.090/mkl/bin/mklvars.sh intel64
    ```

## Algorithms

- [cuFFT](https://docs.nvidia.com/cuda/cufft/)

- [P3DFFT](http://www.p3dfft.net/)

- [SFFT](http://groups.csail.mit.edu/netmit/sFFT/index.html)




## Specific softwares in Geophysics

- [Madagascar]()

- [SeismicUnix]()

- [Obspy](https://www.geophysik.uni-muenchen.de/~megies/www_obsrise/index.html#description) is an open-source project dedicated to provide a Python framework for processing seismological data.
