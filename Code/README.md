To use the code:

1. Use the Makefile to "make tess".

2. Set the control file tesseract.txt to the desired parameters and pathnames.

3. Run HHM on a corpus (see https://github.com/MatthewAKelly/BEAGLE-HHM for MatLab Code or https://github.com/moojan/Python-BEAGLE-HHM for Python code).

4. test_file2017.txt is the set of test sentences used to evaluate the simple exemplar model in the word ordering task.

5. Give tess the memory vectors from the desired level of HHM to represent words and test_file2017.txt in order to evaluate the ability of the vectors to order words into sentences using a simple exemplar model.