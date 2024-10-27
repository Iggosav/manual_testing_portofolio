# Final project for Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: https://lenjeriidelux-pucioasa.ro

Tools used: JIRA, Zephyr Squad

# Functional specifications

The below Stories were created in JIRA and describe the functional specifications of the Huse module, for which the final project is performed upon



![Stories List](https://github.com/user-attachments/assets/98596077-c0ad-4310-9063-2f0204a130e3)


![Story 1](https://github.com/user-attachments/assets/cb11a22e-e476-410b-ac0c-66b846be45d3)
![Story 2](https://github.com/user-attachments/assets/cbddc883-3cf7-4fc9-8361-1c3f838697d9)
![Story 3](https://github.com/user-attachments/assets/ef9a618f-1963-4c37-a78a-ff090a2d6f68)
![Story 4](https://github.com/user-attachments/assets/532c4f12-f35f-4092-addf-7652c9c46de3)
![Story 5](https://github.com/user-attachments/assets/e7bbd75e-b20a-4eda-a2b4-38a58da79d2e)
![Story 6](https://github.com/user-attachments/assets/ecae8145-ed6b-4fd9-9c36-4f99e0d737f6)
![Story 7](https://github.com/user-attachments/assets/64d120bc-c1b8-4914-8e8c-6e174f93240f)
![Story 8](https://github.com/user-attachments/assets/254ad8a1-74f6-48ac-a714-ed66853770eb)
![Story 9](https://github.com/user-attachments/assets/130f08f9-5bf9-40eb-b22c-218fca687ba1)
![Story 10](https://github.com/user-attachments/assets/360aeb9c-a567-49cb-8e69-78ab8d7727f3)
![Story 11](https://github.com/user-attachments/assets/fc432059-8e80-4f65-98fe-009cab4dfe88)


The detailed stories report is available here: [Jira reports/Stories Jira Export CSV (all fields) 20241027080116.csv]()


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
  
6.	In case that the training provided to the team is not complete the site content might not be updated or could be incomplete 
7.	Vulnerable security that could expose user data.
8.	The risk of the site’s compatibility with different browsers and devices.
9.	The risk of poor site performance leading to a negative user experience.
10.	Integration issues with the payment system or inventory management.
11.	The risk of having an unfriendly user interface, causing users to abandon the purchasing process.
12.	Functionality issues with key elements such as adding to the cart, payment, etc."


![RISK MATRIX](https://github.com/user-attachments/assets/2861d0ae-ec2d-466f-9cb2-c1e35001b3d3)

#### 1.1.6 Evaluating entry criteria
The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.

## 1.2 Test Monitoring and Control

Regular tests status reports will be generated weekly to reflect testing progress and identify new project risk for mitigation.

## 1.3 Test Analysis

For the Huse module, the testing process will be executed based on the following test conditions:

* Understand the essential functionalities required by the business and the expectations for user satisfaction
* Set up the test method, test categories, and techniques used.
* Outline the conditions that need to be tested.
* Test the UI (Graphic User Interface)to confirm that all interactive elements, like buttons and input fields perform as expected.

## Techniques used for GUI (Graphical user interface) testing include:

* Positive testing: Confirms that input fields and elements work correctly when valid data is entered, meeting specified requirements.
* Negative testing: Verifies that fields do not accept invalid or incorrect data, ensuring improper inputs are blocked.
* Boundary value analysis testing: Test the extreme limits of input fields by entering the smallest and largest acceptable values.
* Equivalent Partitioning Testing: Organizes input data into categories or groups, with each group represented by test cases to nsure consistent behavior across all variations.

## Test Conditions for "Huse" module:


* Validation of Correct Interface Display - Ensures that the interface is displayed properly, providing a smooth and intuitive user experience..
* Testing of the "Huse Menu" button - This condition focuses on ensuring that the “Huse Menu” button works correctly and performs the intended functionality.
* Testing of the "Filtreaza" button - This condition focuses on ensuring that the “Filtreaza” button works correctly and performs the intended functionality.
* Testing of the "Sorteaza dupa" button - This condition focuses on ensuring that the “Sorteaza dupa” button works correctly and performs the intended functionality.
* Testing of the "Adauga in cos" button - This condition focuses on ensuring that the “Adauga in cos” button works correctly and performs the intended functionality.
* Enter data for the required field to choose the desired quantity of the product and validate if it is correctly registered.
* Testing of the "Continua cumparaturile" button - This condition focuses on ensuring that the “Continua cumparaturile” button works correctly and performs the intended functionality.
* Testing of the "Actualizeaza cosul" button - This condition focuses on ensuring that the “Actualizeaza cosul” button works correctly and performs the intended functionality.
* Recording discounts with valid Information - Checks that the discount is successfully applied when the inserted code from "Cod cupon" filed is valid.
* Non-Recording of discounts with invalid information: Ensures that the discount is not recorded if incorrect or invalid code is entered in "Cod cupon" field. When the user enters incorrect or invalid data in the field, we will check that an error message will be generated and the discount is not recorded.
* Testing of the "Aplica cupon" button - This condition focuses on ensuring that the “Aplica cupon” button works correctly and performs the intended functionality.
* Confirmation of Required Field Indicators: Verifies that all mandatory fields in the form are clearly marked, indicating that they are required for submission.
* Testing of the "Plaseaza comanda" button - This condition focuses on ensuring that the “Plaseaza comanda” button works correctly and performs the intended functionality.

    These conditions provide a structured approach to verifying that all essential functionalities work as expected for a seamless user experience.

  
  ![Test condition](https://github.com/user-attachments/assets/61f0eb77-280b-4cb4-8ab9-1dbfb9623a0f)

  The test cases can be viewed here: [Jira reports/Test cases- Jira Export CSV (all fields) 20241027061524.csv]()


## 1.4 Test Design

*	The Zephyr Squad tool aims to streamline the creation of functional test cases. Techniques such as positive testing, negative testing, and use case testing will be utilized for crafting test cases through specification analysis.
*	Test scenarios and cases will align with identified acceptance criteria.
*	Each test case will establish the necessary data and expected outcomes.
*	Prioritization of test cases will be based on risk and significance.

  
![Test 1](https://github.com/user-attachments/assets/272831ce-cf59-4568-82fb-a1c4988cc045)
![Test 2](https://github.com/user-attachments/assets/a16b0358-57da-4897-a78d-d1f9784d1078)
![Test 3](https://github.com/user-attachments/assets/ad1e0d66-4340-4309-b7d8-e04cc7331d3a)
![Test 4](https://github.com/user-attachments/assets/56a7ccd2-07b6-4200-ac61-ac6c7a4b8055)
![Test 5](https://github.com/user-attachments/assets/d20af88f-385f-4a1a-8439-e751deaabe40)
![Test 6](https://github.com/user-attachments/assets/929c11d2-7929-4ff9-b271-157e8e99b4d7)
![Test 7 1](https://github.com/user-attachments/assets/0c2c8ba8-12dd-46b9-8b9e-e36a06636744)
![Test 7 2](https://github.com/user-attachments/assets/98ac3c67-f381-4d15-9f87-329ccfb0ab6a)
![Test 8 1](https://github.com/user-attachments/assets/7c3523de-8544-423d-8964-9feb8e63dfcc)
![Test 8 2](https://github.com/user-attachments/assets/65717302-22b8-4845-878c-9ca546f034ab)
![Test 9](https://github.com/user-attachments/assets/7a5b7ff5-6278-4b53-bd08-505c3904687d)
![Test 10](https://github.com/user-attachments/assets/ce34d1db-7371-49c0-9b12-568505436375)
![Test 11](https://github.com/user-attachments/assets/448277ff-ec63-4e81-ab2e-19db589777c6)


The test cases with steps can be viewed here: [Jira reports/Huse Module access and navigation - Cycle Summary  ZFJ-Cycles-10-26-2024.csv]() and [Jira reports/Huse module purchase order Cycle Summary ZFJ-Cycles-10-26-2024.csv]() 


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

Traceability matrix report can be viewed here:  [Jira reports/Forward Traceability_27_10_2024.xlsx]()

![Taceability](https://github.com/user-attachments/assets/0b04b25d-9144-4bf4-aa77-14dcbb4c6be2)

According to the Traceability matrix 7 stories covered with 7 performed tests passed and 3 stories covered with 3 performed tests failed.
Bugs have been created based on the failed tests. The complete bug reports can be found here: [Jira reports/BUGS - Jira Export CSV (all fields) 20241027053429.csv]()

**BUG LIST:** 


![BUG  LIST](https://github.com/user-attachments/assets/0bdf8776-001a-4206-afa2-fbdc396b5a35)

1.


![BUG1](https://github.com/user-attachments/assets/08bf9a7a-7f53-43a9-8583-db417ee50589)

2.


![BUG2](https://github.com/user-attachments/assets/b6480442-8b86-404e-ae61-5e60e6277ad4)

3.


![BUG3](https://github.com/user-attachments/assets/b99580d2-63dd-4624-9c24-19dfd1045c4a)


## 1.7 Test Completion

Based on Jira tool, a test execution report focused on the "GUI Testing" cycle was generated. From 11 stories covered with 11 performed tests, 3 tests failed. For the failed tests we identified 1 test with low severity and 2 tests with medium severity. We recommend a careful and focused approach to these failures, including the following aspects: identifying the underlying causes for each failure, determining the impact of each failure on the user experience, and taking the necessary measures for the prompt correction of the identified problems. Our goal is to provide an improved experience in order to avoid users from abandoning the order.

* As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.
* The traceability matrix was generated and can be found here:  [Jira reports/Forward Traceability_27_10_2024.xlsx]()
* Test execution chart was generated, the final report shows that a number 3 tests have failed of a total of 11. A number of 11 test cases were planned for execution and all of them were executed. A number of 3 total bugs were found, from which the priority is: 2 are medium and 1 is low.
  
![Test Execution](https://github.com/user-attachments/assets/f90516fc-b142-4b8d-9446-f3b84ff62579)

