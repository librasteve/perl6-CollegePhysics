## perl6-CollegePhysics
Uses (https://github.com/p6steve/perl6-Physics-Measure)

## College Physics - Coding Companion

This Jupyter Notebook forms part of a follow along coding companion to the openstax Textbook College Physics (cnx.org). It is independently developed and maintained and is not endorsed by openstax. For more information, please see https://github.com/p6steve/perl6-CollegePhysics.

The aim is to help intermediate students of physics to learn modern coding techiques and to apply them to perform interactive calculations alongside the source text.

The author has chosen perl6 over other programming languages, such as Python or Go, for a number of reasons: (i) Unicode makes it more natural to express physical formulae, (ii) Rational numbers are more suitable for physics problems, (iii) it combines Object Oriented, Functional and Procedural programming in a expressive way that matches the needs of physics problems and (iv) it has a basic set of commands 'baby perl' that can be grasped quickly by newcomers to programming.

No prior knowledge of physics or coding are needed to start - the concepts are introduced gradually by example.

More on perl6 language can be found at http://perl6.org and http://docs.perl6.org. I highly recommend 'Think Perl 6' by Laurent Rosenfeld, with Allen Downey (https://greenteapress.com/wp/think-perl-6/) as an excellent introduction to modern programming for beginningers without any prior knowledge of coding.

# Instructions
To use follow these examples:

1. Jupyter Notebook hosted on Binder
- Click this badge => [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/p6steve/perl6-CollegePhysics/master)
- If a Built image is found (click Build logs 'show') then this takes approx 45secs. If you are the first to build e.g. a new version this can take 30 mins or so and the Binder browser UI may lose hope - please just be patient (do not reload as this restarts the build) or maybe follow option #2.
- Go to /eg and click Synopsis.ipynb, then Run each cell - explore & enjoy!

2. Jupyter Notebook local
- *zef install --verbose Physics::Measure* (10 mins)
- *git clone https://github.com/p6steve/perl6-Physics-Measure-JupyterBinder.git* this repo on your machine
- Do the Quick Start here Brian Duggan perl6 jupyter-notebook at <https://github.com/bduggan/p6-jupyter-kernel>
- From the root directory run *jupyter-notebook*
- Go to /eg and click Synopsis.ipynb, then Run each cell - explore & enjoy!

# Inspired by
* Brian Duggan's perl6 jupyter-notebook at <https://github.com/bduggan/p6-jupyter-kernel>
