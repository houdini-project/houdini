Houdini – The numerical simulation framework
============================================

Are you a researcher on numerical methods or physical simulation?
Houdini framework can make your life easier!

Developed by a group of scientists and PhD students, Houdini was designed with two objectives:

* Make it easier to build numerical simulation programs.
* Promote collaboration among researchers with average programming skills.

Dive in the overview and when you are ready to code, read the installation guide and tutorial.


Overview
--------

Houdini is designed to make common numerical simulation tasks fast and easy and to promote collaboration among researchers. The framework consists of two types of objects: applications (apps) and modules (mods). An app represents a numerical simulation program and is built by a set of mods. Each mod is a highly configurable piece that performs an specific task such as: generate a mesh, evaluate the variables, implement a numerical method or graph results.

In each app the user specifies which mods to use and how to configure them. Apps are writen in [JSON](http://www.json.org/), a light weight data format for information storage and exchange. Don't be scared if you have no experience with this format, [JSON](http://www.json.org/) is easy for humans to read and write.

Mods are the heart of Houdini and can be writen in any scientific programming language (C, Fortran, Python, R, Octave...) spiced with a simple template system. This structure is intended to enable collaboration between researchers with different backgrounds and average programming skills. The framework comes with a set of mods ready-to-use covering the basic tasks on numerical simulation. If you need to extend a mod or create a new one, the framework is designed to make this job easy. Read the contributing tutorial if you are interested in mod developing and do not forget to share your improvements with the community, we will all thank you!


Installation guide
------------------

Download [the latest release](http://github.com/houdini-project/houdini/zipball/master).

    wget http://github.com/houdini-project/houdini/zipball/master

...


Tutorial
--------

Here is an informal overview of how to write an application in the Houdini framework.

...


Contributing
------------

...


Copyright and license
---------------------

Houdini framework is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
See the file `COPYING` in this directory or  http://www.gnu.org/licenses/, for a description of the GNU General Public License terms under which you can copy the files.
