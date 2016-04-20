##Testing

* Test can be automated using test oracles.

###Test objectives:
* Functional test: To check whether the software works as per the requirement. (Collect i/p values, produce expected o/p value)
* Performance test: To check whether the performance is acceptable. (Response time, execution time, throughput, space requirements, communication delays)
* Stress test: To test the effect of overload (How many users, records, machines)
* Structural test: All the statements are executed atleast once.
* Security test: test for security offered. (Against penetrative usage)

###Types of testing:
* Blackbox testing: Tested externally according to specification. Test for the absence of featues.
* Whitebox testing: Tester ahs knowledge of code. This cannot find missing features in the specification. This will test the coding struture.

###Need for test coverage:
* An error may get masked in the parts of the program that are not executed.
* One can try to reduce the number of test cases, such that all statements are yet covered.



##Definitions:
* Cyclomatic Complexity: It is a software metric, used to indicate the complexity of a program. It is quantitatively measured based on the number of linearly independent paths through a program's source. It is correlated to the number of coding errors. This will be the upper bound on the number of tests to be conducted. Lower the program's cyclomatic complexity, lower the risk to modify and easier to understand.  
 - CC = Number of predicate nodes + 1
 - CC = Number of edges - number of vertices + 2
Resulting value will be the number of independent paths.

* Data flow testing strategy: It is a test strategy, such paths through the program is selected such that we can explore the status of variables and data objects. 
 - Can pin point if variable is declared and never used within the program.
 - A variable, that is used and never declared.
 - A variable defined multiple times, before it is used.
 - Deallocation of variables, before it is used.



