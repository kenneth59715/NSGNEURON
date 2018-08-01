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

This should create an input.zip file.  That file would be selected for
upload to NSG Portal in the data upload process.

This file (or one downloaded from [JonesEtAl2009 page on ModelDB](https://senselab.med.yale.edu/modeldb/ShowModel.cshtml?model=136803)) can be used as input.  To retrieve the JonesEtAl2009_r31.zip file, click
the "Download zip file" button.  The JonesEtAl2009 model is a network of neurons and scales well.

> **Log in to your NSG account at the [Login Page](https://nsgdev.sdsc.edu:8443/portal2).**
> **Create a Folder.**

***

![Image of Folder Page](../fig/folderspage.png)

***

> **Folders contain sections for Data and Tasks.**

{% comment %}
[Folder Management](https://nsgdev.sdsc.edu:8443/portal2/folder!list.action)
{% endcomment %}

> **Go to the Data section and click on Upload Data, then browse to the desired input.zip file and confirm.**

***

![Image of Upload Page](../fig/uploaddatapage.png)

***

> **The file should show up in the data list.**

***

![Image of Data List Page](../fig/datalistpage.png)

***



