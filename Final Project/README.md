# Final project for Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: https://lenjeriidelux-pucioasa.ro

Tools used: JIRA, Zephyr Squad

# Functional specifications

The below 2 Stories were created in JIRA and describe the functional specifications of the Huse module, for which the final project is performed upon


![Story 1](https://github.com/user-attachments/assets/5eb69dc1-1603-4fea-836e-916cb0e0411e)



![Story 2](https://github.com/user-attachments/assets/92787184-e1fc-4012-8321-fd11a431be47)


The detailed report is available here: [Story.csv]()



# Testing section
## 1.1 Test Planning
The Test Plan is designed to describe all details of testing for the Huse module from the lenjeriidelux-pucioasa application. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

#### 1.1.1 Roles assigned to the project and persons allocated

* Software Developer - Nicu Apetrei 
* Product Owner	     - Sandra Alexei  
* Project Manager    - Delia Pruteanu 
* QA Engineer        - Irina Gosav    
* Senior QA Engineer - Radu Molocea

#### 1.1.2 Entry criteria defined
* Business documentation should be available.
* Functional specifications are defined
* Roles and responsibilities have been established.
* The test plan has been created.
* Initial project risks were identified and defined.


#### 1.1.3 Exit criteria defined
* All tests from the plan have been completed.
* Number of unresolved bugs is insignificant or they have low priority
* All bugs were identified, documented, and resolved if was possible.
* Created and reviewed test reports and documentation.
* Business documentation was covered and met.
* The established deadline was reached.


#### 1.1.4 Test scope
* **Tests in scope:** All the feature of Huse module which were defined in software requirement specifications need to be tested: functional testing and GUI testing. Successfully obtaining a product purchase by completing the product selection and to add them to the cart and add vouchers if the case.
* **Tests not in scope:** Non-functional testing encompasses performance, security, and compatibility testing;Payment steps are not tested;Testing on specific hardware configurations or devices;Testing functionalities that refer to other types of account options or products (except: “Huse”);Automated testing is not covered.


#### 1.1.5 Risks detected

**Project risks:**
  
1.	The risk of not having enough people to work on the project.
2.  The risk that the team is not sufficiently prepared for projects involving order placements.
3.  The risk of exceeding the budget due to additional requirements.
4.	The risk of having incomplete requirements.
5.	The risk of poor communication with the client and not receiving the necessary information regarding products, prices, and active coupons.

  
**Product risks:**
  
6.	The site content might not be updated or could be incomplete.
7.	Vulnerable security that could expose user data.
8.	The risk of the site’s compatibility with different browsers and devices.
9.	The risk of poor site performance leading to a negative user experience.
10.	Integration issues with the payment system or inventory management.
11.	The risk of having an unfriendly user interface, causing users to abandon the purchasing process.
12.	Functionality issues with key elements such as adding to the cart, payment, etc."

![RISK MATRIX](https://github.com/user-attachments/assets/9371246d-91d8-4963-b00e-7290bc2a98bf)

#### 1.1.6 Evaluating entry criteria
The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.

## 1.2 Test Monitoring and Control

Regular tests status reports will be generated weekly to reflect testing progress and identify new project risk for mitigation.

## 1.3 Test Analysis
Based on the above requirements, for the Huse module, the testing process will be executed based on the following test conditions:

*	Ensure the correct main interface is displayed. 
* Validate the “ Huse Menu” button and ensure the Huse module is created/updated.
* Make sure that the next buttons from Huse module are functional: “Filtreaza”, "Sorteaza dupa” and “Adauga in cos”.
* Enter data for the required field to choose the desired quantity of the product and validate if it is correctly registered.
* Make sure that the next buttons from Huse module are functional: “Continua cumparaturile”, “Actualizeaza cosul”, “Aplica cupon and “Plaseaza comanda”.

## 1.4 Test Design

*	The Zephyr Squad tool aims to streamline the creation of functional test cases. Techniques such as positive testing, negative testing, and use case testing will be utilized for crafting test cases through specification analysis.
*	Test scenarios and cases will align with identified acceptance criteria.
*	Each test case will establish the necessary data and expected outcomes.
*	Prioritization of test cases will be based on risk and significance.


![TEST LIST 1](https://github.com/user-attachments/assets/45b87f67-6960-41d7-b859-b7b746b91a28)


![TEST LIST 2](https://github.com/user-attachments/assets/488ebbbe-cf39-4b21-b6ab-97740d37fbc6)

The test cases with steps can be viewed here: [Jira reports/Tests Huse Module access and navigation.csv]() and [Jira reports/Tests Huse module purchase order.csv]()

## 1.5 Test Implementation

* Ensure the test environment is operational at: https://lenjeriidelux-pucioasa.ro
*	Create a cycle summary titled: GUI Testing” containing the designed test cases.
*	Ensure the application is running and ready for testing.
*	Configure required test data and environment.
*	Prepare testing tools and resources for utilization.
*	Organize the necessary test data required for executing test cases.


## 1.6 Test Execution

*	Execute test cases according to the designated test cycle summary.
*	Identify errors based on performed tests and compile comprehensive bug reports.
*	Execute test cases as per the test plan schedule.
*	Compare actual and expected results.
*	Document any encountered problems or issues during testing.
*	Perform additional tests to validate defect resolutions.

Test cases are executed:  [Jira reports/Traceability_matrix.csv]()

![Traceability](https://github.com/user-attachments/assets/84fc49b7-07cf-446f-b099-bcddf50a1513)

Bugs have been created based on the failed tests. The complete bug reports can be found here: [Jira reports/BUGS.csv]()

**BUG LIST:** 


![BUG  LIST](https://github.com/user-attachments/assets/0bdf8776-001a-4206-afa2-fbdc396b5a35)

1.


![BUG 1](https://github.com/user-attachments/assets/94a35e9f-9811-467e-b3d3-69ab4236061a)

2.


![BUG 2](https://github.com/user-attachments/assets/cbc53c42-eb9a-4000-b7a4-6b9007d3d3ae)

3.


![BUG 3](https://github.com/user-attachments/assets/79d2e9eb-cc49-4859-88c7-3b853104a7f3)


## 1.7 Test Completion

Based on Jira tool, a test execution report focused on the "GUI Testing" cycle was generated. From 2 stories covered with 11 performed tests, 3 tests failed. For the failed tests we identified 1 test with low severity and 2 tests with medium severity. We recommend a careful and focused approach to these failures, including the following aspects: identifying the underlying causes for each failure, determining the impact of each failure on the user experience, and taking the necessary measures for the prompt correction of the identified problems. Our goal is to provide an improved experience in order to avoid users from abandoning the order.

* As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.
* The traceability matrix was generated and can be found here: [Jira reports/Traceability_matrix.csv]()
* Test execution chart was generated, the final report shows that a number 3 tests have failed of a total of 11. A number of 11 test cases were planned for execution and all of them were executed. A number of 3 total bugs were found, from which the priority is: 2 are medium and 1 is low.
  
![Dashboards](https://github.com/user-attachments/assets/17af81a5-f313-4f23-81af-115be88994cf)

