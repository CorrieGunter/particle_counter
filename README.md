### particle_counter

#### A set of simple tools for obtaining particle size distributions from em images

This repo contains two simple jupyter notebooks containing step-by-step scripts which allow one to obtain distributions
of spherical particle sizes in either a single electron microscope image, or a folder containing multiple images. Each
notebook contains detailed step-by-step instructions, and the repo contains an example image on which included scripts can
be run.

#### Installation

These scripts utilize the opencv implementation of the [Hough Circle detection algorithm](http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_imgproc/py_houghcircles/py_houghcircles.html).
As a result the following packages are necessary to run the scripts:

 - python 3.5
 - opencv3 (with all dependencies)
 - matplotlib
 - jupyter notebook

For ease we recommend installing and managing packages via the [Anaconda package manager](https://www.continuum.io/downloads) for python.

#### Further development

These tools are an active work in progress. Please contact us with any comments, suggestions or queries!

Enjoy!