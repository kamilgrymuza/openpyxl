openpyxl
========

A Python library to read/write Excel 2007 xlsx/xlsm files. Forked from https://bitbucket.org/ericgazoni/openpyxl

Rationale
-----------------

This is the fork of the original Bitbucket repository
https://bitbucket.org/ericgazoni/openpyxl by Eric Gazoni.

All credit goes to him and other people listed in the AUTHORS file.

This fork has been created to fix few issues (I prefer GitHub to Bitbucket):

* allow class-based tests to be discovered (by inheriting from unittest.TestCase)
* make Worksheet.get_highest_column() return integer rather than string in iter mode 