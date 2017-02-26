# jupyter-scala-bt

You can add project/notebooks dependencies in ```build.sbt```
To setup jar run ```sbt assembly```.

Then in notebook run
```scala
import $file.scripts.importer

importer.loadProjectDependencies
```
