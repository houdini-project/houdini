Houdini – The numerical simulation framework
============================================

Are you a researcher on numerical methods or physical simulation?
Houdini framework can make your life easier!

Developed by a group of scientists and PhD students, Houdini was designed with two objectives:

* Make it easier to build numerical simulation programs.
* Promote collaboration between researchers with average programming skills.

Dive in the overview and when you are ready to code, read the installation guide and tutorial.


Overview
--------

Houdini was designed to make common numerical simulation tasks fast and easy.

Houdini focuses on automating as much as possible and adhering to the [DRY principle](http://c2.com/cgi/wiki?DontRepeatYourself).

The Houdini framework consists of two types of objects: applications (apps) and modules (mods). An app represents a numerical simulation program, built with a set of mods. Each mod performs an specific task such as: generate a mesh, evaluate the variables, implement a numerical method or graph results.

The content of each app is writen in [JSON](http://www.json.org/) and specifies which mods are used and how they are configured. [JSON](http://www.json.org/) is a light weight data format for information storage and exchange. Please, don't be scared if you have no experience with this format, [JSON](http://www.json.org/) is really easy to understand and learn.

Mods are the heart of Houdini and can be writen in any scientific programming language (C, Fortran, Python, R, Octave...). This structure is intended to enable collaboration between researchers with different backgrounds and average programming skills. The framework comes with a set of mods covering the basic tasks on numerical simulation but if you need to extend a module or create a new one, the framework is designed to make this easy.

Here is an informal overview of how to write an application in the Houdini framework.

...


Installation guide
------------------

Download [the latest release](http://github.com/houdini-project/houdini/zipball/master).

    wget http://github.com/houdini-project/houdini/zipball/master

...


Tutorial
--------

...


Contributing
------------

...


Copyright and license
---------------------

Houdini framework is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
See the file `COPYING` in this directory or  http://www.gnu.org/licenses/, for a description of the GNU General Public License terms under which you can copy the files.
