##How to ensure the quality of a software system##
In order to ensure the quality of a software system, the most important job is to do a good test. The major test activities include the following in roughly chronological order:

Step 1：Test planning and preparation, which set the goals for testing, select an overall testing strategy, and prepare specific test cases and the general test procedure.

Step 2：Test execution and related activities, which also include related observation and measurement of product behavior.

Step 3：Analysis and follow-up, which include result checking and analysis to determine if a failure has been observed, and if so, follow-up activities are initiated and monitored to ensure removal of the underlying causes, or faults, that led to the observed failures in the first place.


As to DianDian, I can design a test like following:

1 A Software Test Plan

Firstly, according to user's needs and report on the performance of the functional requirements specification , software testing needs to define the corresponding report , namely define the highest standard of black box testing ,all future work of software testing will focus on the testing requirements. If application meets requirements, that is qualified , whereas that is unqualified ; meanwhile we also need choose test content, arrange software testers , test time and test resources appropriately.

Maybe I can set a goal for testing like this:

Through testing, to achieve the following objectives: 

Test whether the product meets the design requirements, including: whether each function is realized, and whether the business process is correct. 

Whether the operations of the product is running stable. 

Bugs and rate of defect is controled within the range of acceptable.

As to DianDian, I can test if the buttons is effective, after I clicked all buttons, whether there are bugs, whether the software is running stable, and so on.

2 Software test design

Decompose test requirements, subdivide into a number of executable test process , and select the appropriate test cases for each test procedure ( test case selection will directly affect the validity of the test results ).

Test case refers to a particular software product testing task description, reflecting the test program, methods, techniques and strategies. Including test objectives, test environment, input data, test steps, expected results, test scripts, etc., and then form a document. 

Different types of software, test cases are different. Unlike such systems, tools, controls, game software, management software, the user needs more non-uniform, changing bigger and faster.

As to DianDian, I can write test cases to test if each of the function is in good condition.

3 Software Test Development

Create automated test procedure that can be reused.

4 Software Test Execution

Execute automatic test process that created  in test development stage, track and manage defects discovered. Test execution generally consist of unit testing, combinatorial testing , integration testing, system testing, system integration and test and regression testing. Testers should be based on science and responsible attitude, test step by step .

Unit testing, refers to the minimum in the software testing unit for inspection and verification.

Combinatorial test can guarantee under the premise of error detection using fewer test cases to test system.

Dintegration testing is on the basis of unit tests, assemble all modules into a subsystem or system based on design requirements.

Regression testing means:after changing the old code, re-test to confirm the changes do not introduce new errors or cause other code generates an error.

We can test DianDian step by step using unit testing, combinatorial testing , integration testing, system testing, system integration and test and regression testing.

5 Software Test Evaluation

Combines  quantized test coverage domain and defect tracking reports, conduct a comprehensive assessment for the quality of application software and the progress and efficiency of the development team.

Clearly, black box testing only in strict accordance with the steps , it may be the quality of the application checks . However , without the help of an excellent testing tool , simply by virtue of manual testing , not only to spend a lot of manpower, material and financial resources, and there are a lot of testing is difficult or even impossible to achieve.
