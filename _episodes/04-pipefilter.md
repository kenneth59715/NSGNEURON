---
title: "Download Output"
teaching: 05
exercises: 05
questions:
- "How can I download my output data?"
objectives:
- "Through the web portal, download the output.tar.gz file to the local machine."
keypoints:
- "The name of the output file is output.tar.gz."
- "The format of the archive is a tarred, gzipped file."
- "The archive contains the complete input data set, standard out and error, and working directory."
---

Go to the Task List and
click on the "View Output" button for a completed Task.  A list of possible
downloads is presented.  Click on "Download" for output.tar.gz.  Follow browser
prompts of putting the file in a desired location on your local machine.  Once
downloaded, you will need to unzip and untar the archive.  For a Linux machine,
this can be down with

~~~
$ mkdir output
$ cd output
$ tar zxf ../output.tar.gz
~~~
{: .language-bash}

