# HackRF

This repository contains hardware designs and software for HackRF,
a low cost, open source Software Defined Radio platform.

![HackRF One](https://raw.github.com/arsscriptum/sdr.hackrf/master/docs/images/HackRF-One-fd0-0009.jpeg)

Information on HackRF and purchasing HackRF: https://greatscottgadgets.com/hackrf/

--------------------

# Documentation

Documentation for HackRF can be viewed on [Read the Docs](https://hackrf.readthedocs.io/en/latest/). The raw documentation files for HackRF are in the [docs folder](https://github.com/mossmann/hackrf/tree/master/docs) in this repository and can be built locally by installing [Sphinx Docs](https://www.sphinx-doc.org/en/master/usage/installation.html) and running `make html`. Documentation changes can be submitted through pull request and suggestions can be made as GitHub issues. 

To create a PDF of the HackRF documentation from the HackRF repository while on Ubuntu:
* run `sudo apt install latexmk texlive-latex-extra`
* navigate to hackrf/docs on command line
* run the command `make latex`
* run the command `make latexpdf`
