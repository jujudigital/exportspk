# Export SPK

A simple Node.js based command-line utility for exporting and creating a DroidScript project SPK file from a git repo.

# Installation

Download the latest release, unpack and `cd` into the project root and run the following commandL

`npm install -g`

# Usage
The utility takes three arguments:
* _source_  -- the path to the folder with the source files.
* _destination_ -- the path to the destination folder.
* _[name]_ -- Optional project name; default is the folder name of the source folder.

## Example

`exportspk ./src ./dist MyProject`