# jupyter-scala-bt
Templates for build tools integration of jupyter-scala notebooks

Each template uses ammonite script to load jars from appropriate directory.

### Dependencies
[jupyter-scala](https://github.com/alexarchambault/jupyter-scala)

### Available templates
* plain (specify project's jar directory in notebooks/scripts/importer.sc - default is lib/)
* SBT (uses assembly plugin)
