# Trivia source code and binary files, 1976 - 1977
This repository contains the source code and binary files for 1976-1977 versions of [Trivia](https://alum.mit.edu/slice/even-more-groundbreaking-alumni-developed-video-games), a user-contribution trivia game created by Tim Anderson, Marc Blank, and Dave Lebling as part of the MIT Lab for Computer Science's Dynamic Modeling Group. The game was widely played on the ARPANET. The files are a part of the [Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection](https://archivesspace.mit.edu/repositories/2/resources/1265) at the MIT Libraries Department of Distinctive Collections (DDC).
## File organization and details
### [trivia](../main/trivia)
The files within this directory are the Trivia specific files from multiple tape images from different points in 1976 and 1977. They are from the ```100260.tap```, ```7005366.tap```, ```9005143.tap```, ```9005183.tap```, ```9005201.tap```, and ```9006234.tap``` tape image files within the ```/tots/recovered/vol1```, ```/tots/recovered/vol2```, ```/tots/recovered/vol7``` directories and the extracted files in the ```/tots/part5/its20x/7005372``` directory of the [ToTS collection](https://archivesspace.mit.edu/repositories/2/resources/1265). Most files are written in the MDL programming language and were originally created on a PDP-10 timeshare computer running the ITS operating system.

Most files were extracted from the tape image using the [itstar program](https://github.com/PDP-10/itstar). The filenames have been adapted to Unix conventions, as per the itstar translation. The original filename syntax would be formatted like, ```SYS; TS TRIVIA```, for example. All files have been placed into this artificial trivia directory for organizational purposes. The files extracted from the tape images were put into sub-folders with a corresponding name to the tapes listed above. Files in the ```7005366``` folder are from the pre-extracted set done by MIT CSAIL in 2009.

The ```sys```, ```taa```, ```marc```, ```madman```, ```mudtmp```, and ```mudsav``` directories in each sub-folder contain the source code, documentation, and binary files for the game.

The ```}msgs}``` directories contain files where messages were posted to users, ```trivia.curfew``` files were messages to trivia users. The [```trivia.curfew```](../main/trivia/9005201/}msgs}/trivia.curfew) file in the ```9005201``` directory states that Trivia became unavailable by October 1977.

The [```art2.tv```](../main/trivia/9005143/taa/ar2.tv), [```art2.tv```](../main/trivia/9005183/taa/ar2.tv), and [```art1.tv```](../main/trivia/9006234/marc/ar1.tv) files are ITS archive files. Researcher Lars Brinkhoff extracted their contents to directories of the same name using the [itsarc program](https://github.com/larsbrinkhoff/pdp10-its-disassembler/blob/master/itsarc.c). They were added to their corresponding tape directory along with a txt file showing the original file timestamps.

### [codemeta.json](../main/codemeta.json)
This file is metadata about the Trivia files, using the [CodeMeta Project](https://codemeta.github.io/) schema.
### [LICENSE.md](../main/LICENSE.md)
This file describes the details about the rights to this code. See [Rights](#rights) for additional information.
### [README.md](../main/README.md)
This file is the readme detailing the content and context for this repository.
### [tree.txt](../main/tree.txt)
A file tree listing the files in the [```trivia```](../main/trivia) directory showing the original file timestamps as extracted from the tape image.

## Preferred Citation
[filename], Trivia source code and binary files, 1976-1977, Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection, MC-0741. Massachusetts Institute of Technology, Department of Distinctive Collections, Cambridge, Massachusetts. [swh:1:dir:283300b55fb2213b7a92d303af038927cfad0944](https://archive.softwareheritage.org/swh:1:dir:283300b55fb2213b7a92d303af038927cfad0944)
## Rights
To the extent that MIT holds rights in these files, they are released under the terms of the [MIT No Attribution License](https://opensource.org/licenses/MIT-0). See the ```LICENSE.md``` file for more information. Any questions about permissions should be directed to [permissions-lib@mit.edu](mailto:permissions-lib@mit.edu)
## Acknowledgements
Thanks to [Lars Brinkhoff](https://github.com/larsbrinkhoff) for help with identifying these files and with extracting them using the itstar program mentioned above.
