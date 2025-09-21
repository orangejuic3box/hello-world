# hello-world

doing the github tuturial cause i dont know how
to do my assignment. how do i create a one line shell script that 
compiles and runs a file? please send help
-mags from 2020


# README

## @Author: Maggie Lacson
## @ID: 1591850

This readme describes how to use the `1591850-global.py` and `1591850-local.py` files. Please make sure to read to the end.

To run either of alignment programs, please navigate to the folder where the .py file is located. The input file (which must end with .in) must also be in the same folder as the .py and this folder is where the corresponding output files will be written to.

Use the following command in the terminal:

` python 1591850-global.py --filename FILENAME `
or
` python 1591850-local.py --filename FILENAME `

where FILENAME must be of the format ```[FILENAME].in``` and assumes `[FILENAME]` is the PREFIX where the corresponding output files will be named:

```
PREFIX.o1
PREFIX.o2
PREFIX.o3
PREFIX.o4
PREFIX.o5
```

Notably, if both the -global.py and -local.py files are in the same folder and the same input file is used to run an alignment one after another, their output will overwrite each other since both programs have the same output naming scheme. i.e. output files do not have a "-global" or "-local" filename identififier.

You may also choose to print the output to the terminal (output files will still be written), by setting the `--print_output` flag.

Example:
`python 1591850-local.py --filename 2.in --print_output`

Note: There is automatic output written to the terminal even without the `--print_output` flag. The PREFIX for the output files is written out along with extra prints for ease of understanding what the ouput files will be named. Using the `--print_output` flag just displays the content of written output files to the terminal on top of this.

Thank you.
