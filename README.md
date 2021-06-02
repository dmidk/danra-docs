# DANRA Documentation
This repository is the source of the documentation of the DANish ReAnalysis.

The documentation can be found here: [dmidk.github.io/danra-docs/](https://dmidk.github.io/danra-docs/)

## Build documentation locally
To build the documentation locally run `./make_docs`

This will generate the webfiles in `doc/_build/html/`. To check the output you can start a simple web server from that directory using the python module http.server with the command: `python -m http.server` and go to your [localhost](http://0.0.0.0:8000/).

## Dependencies
The documentation is build using [sphinx](https://www.sphinx-doc.org/en/master/) with the [furo theme](https://github.com/pradyunsg/furo) by pradyunsg. Also, [myst-parser](https://myst-parser.readthedocs.io/en/latest/) is used to be able to write markdown for sphinx. If you have [conda](https://docs.conda.io/en/latest/miniconda.html) installed you can create a new python environment that will work by running:

`conda env create -f danra-docs.yml`