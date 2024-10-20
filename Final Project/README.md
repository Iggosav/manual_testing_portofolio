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
The following elements are needed to be ready before the test execution phase begins:

======enter here what needs to be ready for the test execution to begin

## 1.6 Test Execution
Test cases are executed on the created test Cycle summary:  cycle_summary_execution.pdf ===== (pt acest pdf am link)
Bugs have been created based on the failed tests. The complete bug reports can be found here: created_bugs.pdf (am link)
enter here bug titles -   sam inspir din modelu gata facut

## 1.7 Test Completion
====Exit criteria was evaluated and passed
The traceability matrix was generated and can be found here: Traceability_matrix.csv (am link)
Test execution chart was generated, the final report shows.... -> describe the final report
-> enter here test execution report/chart ======= sa ma folosesc de  exemplul din model 



