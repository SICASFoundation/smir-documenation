---
title: Scala 
taxonomy:
    category: docs
---

! [Scala VSDClient on github](https://github.com/unibas-gravis/VSDClient)


VSDClient is a library providing  a client to the [REST interface](https://www.smir.ch/api/Help) provided by the [SMIR)](https://www.smir.ch/)


The vision of the project is to provide an environment where :

* The VSD concepts, such as Objects, Folders, Links, Modalities, Ontologies, etc.. are implemented in classes against which the user can program and script
* The set of JSON serialization/deserialization protocols allowing to communicate with the VSD REST interface are already implemented and allow to retrieve and push the classes mentioned above

* Recurrent tasks such as uploading a Dicom directory, downloading a folder, creating object links etc.. are already implemented in an intuitive manner. 

The VSDClient is intended to be used as a Software library to be included in the user's software project.

Although the library is written in [Scala](http://www.scala-lang.org/) (which of course makes it accessible to Scala projects), it is compatible with any JVM-based language, and **can notably be used from wihtin Java projects.**

## API Documentation

[The latest project API doc](http://unibas-gravis.github.io/VSDClient/latest/api/index.html#ch.unibas.cs.gravis.vsdclient.VSDClient)

## Using VSDClient

To use VSDClient in your own project, you can either : add the following lines to your build.sbt
```
libraryDependencies  ++= Seq(
            // other dependencies here
            "ch.unibas.cs.gravis" %% "vsdclient" % "0.2.+"
)
```


## Quick Start : 

Please read the README on [github](https://github.com/unibas-gravis/VSDClient)