# Racket-GradingScript

## Description
To test Racket, .rkt, programs.

The required files for the script to run is as follows:

0. A running version of racket.
	1. The location of racket executable will most likely need to be changed within racket_grader. The location can be specified by changing the string value of **racket_loc**, the 5th line within the script.
1. A racket source file with the extension .rkt.
2. A testcase directory containing:
	1. A .in file 	
	2. A .out file
	3. A .err file

**Note:** The **testcase** dir, **.in**, **.out**, **.err** files/extensions can be changed to what is desired. In addition, the **.err** file can be omitted if no errors are expected to occur within the program.

To run the script, the command **chmod +x** may need to be run before executing.

#### Example File Structure 
.
+-- racket.rkt
+-- testcases
|	+-- inputs.in
|	+-- expected_outputs.out
|	+-- expected_errors.err
+-- racket_grader.sh

#### Example Input / Output
[user]:~$ ./racket_grader.sh

----- Running Testcase -----

*********************************
* TESTCASE 'testcase_name' PASSED
*********************************

## Author
Nicholas Kunzler

