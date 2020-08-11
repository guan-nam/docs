## Tutorial for Test Sheets on the Web

1.1 Motivation for Test Sheets

Testing is an integral part of software engineering. And tests define the expected behaviour of systems. It is an important part of documentation. There are usually numerous stakeholders such as developers, domain-experts, sales and marketing personnel, customers and so on. But code-based testing technologies are not suitable for non-developers. Therefore, we need an understandable and user-friendly test definition and reporting approach. 

1.2 Goal of Test Sheets
The goal of Test Sheets is to develop a web-based environment for the definition and execution of test sheets, with an interface for uploading code to be tested, input/output of CVS files (e.g. Excel) , and creation of Junit files.

1.3 Test sheet language description
Test Definitions (Junit)
Tests are defined by writing code. The main examples are Junit. Tests are very powerful as all features of programming language are supported. Junit is not suitable for non-developers. Test results separated from test definition. 

1.4 Framework for Integrated Test (FIT)
Test cases which are written in tabular form, they are usable by domain experts and customers. 
Test developer bridges gap between tables and executable code.
The FIT has limited descriptive power, it’s not semantically self-contained. 


1.5 Test Sheets
FIT and JUnit represent extremes of the abstraction spectrum. Test Sheets: positioned in between descriptive power of JUnit and tabular definition of test data (FIT). It is a spreadsheet metaphor. Test Sheets can automatic transformation into executable code. Test results also displayed as test sheet.
Overall, Test Sheets provide a simple, concise, easy-to-understand yet executable description of what a component should do.
