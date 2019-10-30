# Project 2
A parser for the Quack language.

## To build
After downloading the repo use the following command to create a docker image:

`docker build --tag=proj2 .`

Then to run the image:

`docker run -it proj2`

## To run
Once in the docker image use the binary lexer in bin to scan and parse a text
file and then print something that might be the AST.
For example using the sample Pt.qk file:

`bin/parser samples/Pt.qk`
