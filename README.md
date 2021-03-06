# Data Science in Practice Site
[![Project Status: Active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

Data science in practice is a collection of materials & assignments for learning and practice introductory data science.

## Overview

This repository is the source repository for creating the [Data Science in Practice](https://datascienceinpractice.github.io/) website.

These materials serve as a public version of materials developed for the [COGS108](https://github.com/COGS108) class.

This repository has the tools for building the website, by accessing, updating, and building from the materials from the COGS 108 organization.
The built version of book is then posted to the
[website repository](https://github.com/DataScienceInPractice/datascienceinpractice.github.io)
for hosting.

## Dependencies

This project uses the Python programming language, and requires Python >= 3.6. 

Materials are written and available as [Jupyter Notebooks](https://jupyter.org/). 

Tutorials & assignments require packages from the scientific Python ecosystem. These dependencies can all be installed using the 
[Anaconda distribution](https://www.anaconda.com/products/individual). Details and instructions on the dependencies
and how to get them are available in the materials.

The website is created using [JupyterBook](https://github.com/executablebooks/jupyter-book).

## Organization

This repository contains the following sections:

- `dsip/` contains the content of the website, including sub-sections:
    - `docs/` contains the source for written sections of the site
    - `tutorials/` contains tutorial notebooks which introduce key topics for doing data science
    - `assignments/` contains assignment notebooks with problem sets that can be worked through
    - `projects/` contains information on how to pursue independent analysis projects
- `paper/` contains a draft paper, describing these materials, and submitted to [JOSE](https://jose.theoj.org/)

## License

These materials are made freely available, and are licensed under a [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license.
