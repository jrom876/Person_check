# Person_check
Person_check

This repository is a Person structure with a C Unit automated test framework.

Its data structure and basic functionality are defined in personExample.c and personExample.h. 

The createHuman branch is used to develop and test new features such as passwords.

It has two make files, make.mk and make-test.mk. The make.mk version updates all dependencies in the main directory, 
while the make-test.mk version creates executable automated tests which immediately run on the command line. 

To run make-test on the linux command line, use these commands:

checkmk personExample-test.check >personExample-test.c

make -f make-test.mk pstest

or

make -f make-test.mk chtest
//=====================

To update all dependencies, use:

make -f make.mk

or 

make -f make.mk main
//=====================
