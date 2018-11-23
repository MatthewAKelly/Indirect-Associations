Code for the word ordering task (Experiments 3 and 4).

To use the code:

1. Use the Makefile to "make tess".

2. Set the control file tesseract.txt to the desired parameters and pathnames.

3. Run HHM on a corpus (see https://github.com/MatthewAKelly/BEAGLE-HHM for MatLab Code or https://github.com/moojan/Python-BEAGLE-HHM for Python code).

4. test_file2017.txt is the set of test sentences used to evaluate the exemplar model in the word ordering task.

5. Give tess the memory vectors from the desired level of HHM to represent words and test_file2017.txt. The executable tess then uses the exemplar model to evalute the ability of the give vectors to order words in the sentences in test_file2017.txt us. Exemplar model is based on the Exemplar Production Model from Johns et al. (2016) "The Combinatorial Power of Experience" <http://btjohns.com/pubs/JJCJM_cogsci_2016.pdf>.
