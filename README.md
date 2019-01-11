Initial code that hopefully some day will become an (chemical) ocr
engine. At the very least, hopefully it can serve as a way to vectorize
chemical images into mol files, preserving the 2D layout as much as 
possible. The code is still very raw in terms of utility. Please forward
questions and/or problems to nguyenda@mail.nih.gov.

To build the code, you'll need to install Apache ant (http://ant.apache.org).
Once ant is installed, simply type ant in this directory. If all goes well
(and it should), a simple window will popup demonstrating the various image
and geometry primitives currently available in the code. Of course, the
next step is to turn these primitives into meaningful geometric objects and
beyond.

![Primitives](sample1.png)