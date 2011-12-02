This is a common repo for storing javascript (and some css) vendor libraries
for use as a submodule across a variety of Open Knowledge Foundation (or other)
projects.

## Repository layout

Repository layout is as follows::

  /{library-name}/{version}/{library-name}.js

* **Minification**: In general always include **non**-minified versions of
  libraries (you may also, optionally, include minified versions).
* **Version numbering**: should follow semver.org but without leading 'v' e.g.
  1.0.0 rather than v1.0.0.
* **Library name**: should always be lower case. Do not include version number
  in library name (obviously!)

Example (jquery)::

  /jquery/1.7.2/jquery.js
  /jquery/1.7.2/jquery.min.js <-- optional

## Adding this to your repository

To add this to your repository at e.g. directory /vendor do the following::

  git submodule add ....

## Copyright Licensing

Only open-source libraries are included here. All libraries are copyright their
respective authors / communities. Details of license for a specific library can
usually be seen in the header of each library file. 

