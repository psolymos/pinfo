pinfo
=====

Distributed project management using dcf files


Background
----------

I have struggled with keeping myself up-to-date regarding my projects and collaborations.
The goal of this simple tool is to allow for a distributed management system, instead of
a centralized one (e.g. project database).

Each project contains a pinfo.dcf file in its root. The .dcf stands for Debian Control File Format.
Each if these file share a common standardized format with standard field names.

Project management is implemented via the parse.dcf R function after scanning the
hard drive for pinfo.dcf files. These files then assembled into a project summary document
that describes a current snapshot of ongoing projects and their inheritance structure.
