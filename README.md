ssg
-------------------------------------------------------------------

This is a static site generator written in C.
It relies on the cmark library for parsing commonmark and dirent.h functionality for navigating directories.

Configuration can be done by modifying the parameters in config.h
When the application is run it generates an index.html.
It also copies the contents of resourcesdir into the htmldir recursively, so any images/css/static html/other files you want ot host should go in there.
