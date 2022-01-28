# Lab 2 - Remote Access

## Example 3
[Link to failure-inducuing input](lab-2-test-files/test-file8.md)

Screenshot of the code change:
![Change 3](images/lab-report-2/github-change-3.png)

Screenshot of the symptom:
![Failure3](images/lab-report-2/failure3.png)

The bug was that invalid links that contained spaces in them were also being counted as links themselves, and therefore was being outputted by the program. The symptom was that during our JUnit tests, the test for test-file8.md didn't return the expected output of an empty arraylist. Therefore, we had to add a check to see if there were any spaces between the two parenthesis in order to determine if the link was valid.