# jupyter-scala-bt
Templates for build tools integration of jupyter-scala notebooks

Each template uses ammonite script to load jars from appropriate directory.

### Dependencies
[jupyter-scala](https://github.com/alexarchambault/jupyter-scala)

### Available templates
* plain
* SBT (uses assembly plugin)

### How to use it (for existing project)
Put appropriate directories at toplevel of your project. Specify project's jar location in *notebooks/scripts/importer.sc* (default is *lib*).
See *example.ipynb* for how to use importer.
