**********************
cookiecutter-djl-pypkg
**********************

.. image:: https://img.shields.io/badge/license-Apache%202-cb2533.svg
    :target: https://www.apache.org/licenses/LICENSE-2.0
    :alt: Licensed under the Apache License, Version 2.0

This is a `cookiecutter`_ for my personal project Python packages.

.. _cookiecutter: https://github.com/audreyr/cookiecutter

To create a new package skeleton:

1. Activate the ``cookiecutter`` conda environment::

     $ conda activate cookiecutter

   or create it, then activate it::

     $ conda env create -f cookiecutter-djl-pypkg/env/environment.yaml
     $ conda activate cookiecutter

2. Run this cookie cutter, and answer the prompts, either from a local copy::

     (cookiecutter)$ cookiecutter cookiecutter-djl-pypkg/

   or from `its repository`_ on GitHub::

     (cookiecutter)$ cookiecutter git+ssh://git@github.com:douglatornell/cookiecutter-djl-pypkg.git

   .. _its repository: https://github.com/douglatornell/cookiecutter-djl-pypkg


License
=======

.. image:: https://img.shields.io/badge/license-Apache%202-cb2533.svg
    :target: https://www.apache.org/licenses/LICENSE-2.0
    :alt: Licensed under the Apache License, Version 2.0

This Python package cookiecutter is copyright 2019-2020 by Doug Latornell.

It is licensed under the Apache License, Version 2.0.
https://www.apache.org/licenses/LICENSE-2.0.
Please see the LICENSE file for details of the license.
