class_spec
==========

A unit-test to class documentation generator.

This command line utility will take a path or set of paths and traverse it looking for
unit test files. These are then parsed and turned into readable specifications of the
class behavior. It snoops the class-under-test and it's docstring and reformations test
names from `test_should_clone_superman` into a sentence in the form "ClassUnderTest should 
clone superman"

Initial version will just output well-formatted plain text to stdout, but one can imagine
creating various output modules for rst, md, wiki-markup, latex, html etc.
