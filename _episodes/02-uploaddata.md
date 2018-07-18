---
title: "Upload Input Data"
teaching: 05
exercises: 10
questions:
- "How do I upload input data?"
objectives:
- "Explain the file format and upload process."
keypoints:
- "File format is zip."
- "The directory structure of the zip archive must contain one subdirectory
that contains the input data."
---

All Tools in NSG Portal take input code/data in the form of a zip archive.

To create a zip archive from an existing directory, do the following:
~~~
$ cd datadir
$ cd ..
$ zip -r input datadir
~~~
{: .language-bash}

This should create an input.zip file.  That file would be selected for
upload to NSG Portal in the data upload process.

This file (or one downloaded from [JonesEtAl2009 from ModelDB](https://senselab.med.yale.edu/modeldb/eavBinDown.cshtml?o=136803&mime=application/zip) can
be used as input.

Create a Folder.  Folders contain sections for Data and Tasks.
[Folder Management](https://nsgdev.sdsc.edu:8443/portal2/folder!list.action)

Go to the [Data Upload section](https://nsgdev.sdsc.edu:8443/portal2/data!list.action) and click on Upload Data, then browse to the desired input.zip file
and confirm.  The file should show up in the data list.



