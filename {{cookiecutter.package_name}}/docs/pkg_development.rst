.. Copyright {{ cookiecutter.project_creation_year }}, {{ cookiecutter.full_name }}
..
.. Licensed under the Apache License, Version 2.0 (the "License");
.. you may not use this file except in compliance with the License.
.. You may obtain a copy of the License at
..
..    https://www.apache.org/licenses/LICENSE-2.0
..
.. Unless required by applicable law or agreed to in writing, software
.. distributed under the License is distributed on an "AS IS" BASIS,
.. WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
.. See the License for the specific language governing permissions and
.. limitations under the License.


.. _{{ cookiecutter.package_slug }}PackagedDevelopment:

**********************************************************
:kbd:`{{ cookiecutter.package_slug }}` Package Development
**********************************************************


.. image:: https://img.shields.io/badge/license-Apache%202-cb2533.svg
    :target: https://www.apache.org/licenses/LICENSE-2.0
    :alt: Licensed under the Apache License, Version 2.0
.. image:: https://img.shields.io/badge/python-{{ cookiecutter.min_python_version }}+-blue.svg
    :target: https://docs.python.org/{{ cookiecutter.dev_python_version }}/
    :alt: Python Version

The {{ cookiecutter.package_name }} package (:kbd:`{{ cookiecutter.package_slug }}`) is {{ cookiecutter.project_short_description }}


.. _{{ cookiecutter.package_slug }}PythonVersions:

Python Versions
===============

.. image:: https://img.shields.io/badge/python-{{ cookiecutter.min_python_version }}+-blue.svg
    :target: https://docs.python.org/{{ cookiecutter.dev_python_version }}/
    :alt: Python Version

The :kbd:`{{ cookiecutter.package_slug }}` package is developed and tested using `Python`_ {{ cookiecutter.dev_python_version }} or later.
The package uses some Python language features that are not available in versions prior to 3.6,
in particular:

* `formatted string literals`_
  (aka *f-strings*)
* the `file system path protocol`_

.. _Python: https://www.python.org/
.. _formatted string literals: https://docs.python.org/3/reference/lexical_analysis.html#f-strings
.. _file system path protocol: https://docs.python.org/3/whatsnew/3.6.html#whatsnew36-pep519


License
=======

.. image:: https://img.shields.io/badge/license-Apache%202-cb2533.svg
    :target: https://www.apache.org/licenses/LICENSE-2.0
    :alt: Licensed under the Apache License, Version 2.0

The code and documentation of the {{ cookiecutter.project_name }} project
are copyright {{ cookiecutter.project_creation_year }} by {{ cookiecutter.full_name }}.

They are licensed under the Apache License, Version 2.0.
https://www.apache.org/licenses/LICENSE-2.0
Please see the LICENSE file for details of the license.
