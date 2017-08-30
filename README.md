# Bitcoin and Cryptocurrency Technologies Tests

### Summary:
- Test cases for the assignments of the Coursera course "Bitcoin and Cryptocurrency Technologies".
- Test cases are the same as used in the coursera grader.
- The test cases are ported form what's available at http://bitcoinbook.cs.princeton.edu/
- Purpose is to enable local debugging, as the hosted grader sometimes gives meaningless output.
- For now, I only added test cases for Assignment 3 "Blockchain".


### Modifications:
- Changed test numbering so that it's in alignment with the coursera grader
- Changed the RSA key handling and signing so that it works with standard (java.security.*) classes (so that the tests don't have dependencies to external libraries)
- Changed class used for random number generation to java.util.Random

### Usage:
- Copy file "Assignment3.java" into your project folder
- Run Assignment3.java




