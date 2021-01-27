# Trivia source code and binary files, 1976 - 1977
This repository contains the source code and binary files for 1976-1977 versions of [Trivia](https://alum.mit.edu/slice/even-more-groundbreaking-alumni-developed-video-games), a user-contribution trivia game created by Tim Anderson, Marc Blank, and Dave Lebling as part of the MIT Lab for Computer Science's Dynamic Modeling Group. The game was widely played on the ARPANET. The files are a part of the [Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection](https://archivesspace.mit.edu/repositories/2/resources/1265) at the MIT Libraries Department of Distinctive Collections (DDC).
## File organization and details
### [trivia](../main/trivia)
The files within this directory are the Trivia specific files from multiple tape images from different points in 1976 and 1977. They are from the ```100260.tap```, ```7005366.tap```, ```9005143.tap```, ```9005183.tap```, ```9005201.tap```, and ```9006234.tap``` tape image files within the ```/tots/recovered/vol1```, ```/tots/recovered/vol2```, and ```/tots/recovered/vol7``` directories of the [ToTS collection](https://archivesspace.mit.edu/repositories/2/resources/1265). Most files are written in the MDL programming language and were originally created on a PDP-10 timeshare computer running the ITS operating system.

The files were extracted from the tape image using the [itstar program](https://github.com/PDP-10/itstar). The filenames have been adapted to Unix conventions, as per the itstar translation. The original filename syntax would be formatted like, ```SYS; TS TRIVIA```, for example. All files have been placed into this artificial trivia directory for organizational purposes. The files extracted from the tape images were put into sub-folders with a corresponding name to the tapes listed above.

The ```sys```, ```taa```, ```marc```, and ```madman```, directories in each sub-folder contain the source code, documentation, and binary files for the game.

The ```}msgs}``` directories contain files where messages were posted to users, ```trivia.curfew``` files were messages to trivia users. The [```trivia.curfew```](../main/trivia/9005201/}msgs}/trivia.curfew) file in the ```9005201``` directory states that Trivia became unavailable by October 1977.

### [codemeta.json](../main/codemeta.json)
This file is metadata about the Trivia files, using the [CodeMeta Project](https://codemeta.github.io/) schema.
### [README.md](../main/README.md)
This file is the readme detailing the content and context for this repository.
### [tree.txt](../main/tree.txt)
A file tree listing the files in the [```trivia```](../main/trivia) directory showing the original file timestamps as extracted from the tape image.

## Preferred Citation
[filename], Trivia source code and binary files, 1976-1977, Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection, MC-0741. Massachusetts Institute of Technology, Department of Distinctive Collections, Cambridge, Massachusetts. [swh:1:dir:d89e3daaf9f4fdf1918ff6917ca189725b90e081](https://archive.softwareheritage.org/swh:1:dir:d89e3daaf9f4fdf1918ff6917ca189725b90e081/)
## Rights
The ownership status of these files is not entirely clear. To the extent that MIT holds rights in these files, we are happy to support their broad public use.  Any questions about permissions should be directed to [permissions-lib@mit.edu](mailto:permissions-lib@mit.edu)
## Acknowledgements
Thanks to [Lars Brinkhoff](https://github.com/larsbrinkhoff) for help with identifying these files and with extracting them using the itstar program mentioned above.
