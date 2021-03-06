// README.txt (copy of ABOUT.adoc)
:author: Tom Swan
:email: <tom@tomswan.com>
:stylesheet: normalize.css

// -----------------------------------------------------------------
== About Menus-in-Asciidoc (mia) Project

.2016-07-04
- This is a demonstration of creating web-page menus in asciidoc documents. The demonstration is standalone, and can be distributed in a single zip file, generated as explained here. 

* See www.tomswan.com/blog/posts/2015-07-10-menus-in-asciidoc.html 
* I will also post this to github for cloning

- All development files (ABOUT, TODO, and others) are in the outer directory (mia-dev). The files in mia are the ones to be distributed to end users in mia.zip. 

// -----------------------------------------------------------------
=== Creating the ZIP File

Verify that all files in mia are ready for publishing, and then:

* Run make from mia-dev to build the demo and create mia.zip. Unpacking the zip file recreates the mia folder

* To recompile from scratch, execute these two commands:

  $ make clean
  $ make

* Copy mia.zip to the site or blog post distribution page. Tell users to unpack the archive to mia, go to that folder, and then open index.html in their browsers. 
