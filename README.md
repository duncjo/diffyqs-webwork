# Notes on Diffy Qs WeBWorK Problems

A set of WeBWorK problems for courses teaching a class with
the *Notes on Diffy Qs* textbook.
Currently should be treated as **beta** quality.

Coverage is Chapters 0, 1, 2, 3, 6, 7, 8.  It should have enough for a normal
ODE course which uses 0, 1, 2, 6, 7 or perhaps 0, 1, 2, 3, 8 if doing systems.
Chapter 8 is somewhat sparse.  Chapters 4 and 5 will be coming soon to some
degree, but probably will also be a little more sparse.

## How to use

To use, download the *diffyqs-webwork.tgz* and upload it to WeBWorK.  It should automatically unpack and create the right directory structure.  Then in
homework editor go to import and then import sets from the diffyqs-webwork
directory.

You could also just unpack this directory into your templates directory, or
even clone it directly from github.  In this case, make sure the directory 
is named exactly `diffyqs-webwork` for the set def files to work.

## What is it exactly

The problems were picked off from the Open Problem Library and somewhat (some
more than others) modified to fit the style and notation of the book.
They are essentially the same problems as those that are in the Edfinity
Notes on Diffy Qs course.

I've cleaned off the OPL tags as they are no longer needed, and some of them
were downright confusing and many were just wrong, and just made editing a
pain.

## Miscellanea

*make-defs.sh* creates the basic .def files from the files.  So do not edit
the .def files

*make-tar.sh* creates a tar file useful for uploading into webwork.  This
will create all the right directory structure.

*diffyqs-webwork.tgz* is the tarfile suitable for uploading.  This is
of course not contained in itself.  Check the date.  I'll rerun *make-tar.sh*
when needed, but it could be out of date.
