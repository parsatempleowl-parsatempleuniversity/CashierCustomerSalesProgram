# Cashier Customer Sales Program
Cashier Customer Sales Program

## Project Abstraction
At least one paragraph description of the overall project. Include a UML use case diagram or other helpful diagram.

This project consists of the following interfaces: Cashier, BasicCalculator, SalesTaxCalculator, SalesPercentOffCalculator, Customer, SalesCalculator(subtotal), ChangeCalculator, TotalSalesCalculator, and Receipt. This project also consists of the following classes: CashierImpl, BasicCalculatorImpl, SalesTaxCalculatorImpl, SaleSalesCalculatorImpl(subtotal), ChangeCalculatorImpl, ItemsAndPRices, ReceiptImpl, TotalSalesCalculatorImpl, Main, and MainForUnitTest. The cashier has access to the following parts of its system: Basic Calculator, Sales Tax Calculator, Sales Percent Off Calculator, Sales Calculator(subtotal), Change Calculator, Total Sales Calculator, Receipt, and Items And Prices. The customer has access to Receipt and Items And Prices.

## Project Relevance
A one paragraph explanation of how the proposal is linked to the educational goals of this class and why this goal is important goal.

Goal - Mockito Testing In Java: 

This test allows me to verify that the code being tested works, regardless of its dependencies. The theory is that if the code that I write works as designed and my dependencies work as designed, then they should work together as designed. It is used to mock interfaces so that a dummy functionality can be added to a mock interface that can be used in unit testing.

## Conceptual Design
A one-paragraph description of your proposed contribution.

I will be doing this project all by myself for the last 4 - 5 weeks of the semster. I will begin with implementing all of the calculator classes for this project. Then, I will implelemt the receipt class for this project. And then I will implement the customer and cashier classes for this project. Then, I will create the ItemsAndPrices class. At the end, I will be unit testing using Mockito Testing and I made a MainForUnitTest class for it. And also create the user interface using the Main class that I have created for this project.

## Background
A URL reference to the project. Add text on how to build and run succesfully.

<https://github.com/parsatempleowl-parsatempleuniversity/CashierCustomerSalesProgram.git>

**Building**
- Step 1: Download and install IntelliJ IDEA Community (Download Link: <https://www.jetbrains.com/idea/download/#section=mac>)
- Step 2: Download and install Java JDK (Download Link: <https://www.oracle.com/technetwork/java/javase/downloads/jdk13-downloads-5672538.html>)
- Step 3: Download the following files: junit4.11.jar (Download Link: <https://mvnrepository.com/artifact/junit/junit/4.11>), hamcrest-core-1.2.1.jar (Download Link: <https://mvnrepository.com/artifact/org.hamcrest/hamcrest-core/1.2.1>), and mockito-all-2.0.2-beta.jar (Download Link: <https://mvnrepository.com/artifact/org.mockito/mockito-all/2.0.2-beta>)
- Step 4: Clone into this repository
- Step 5: Open IntelliJ IDEA and create a new project and call it MockTest1 and click Finish (accept defaults for the first two steps)
  - Will change the name of the project to CashierCustomerSalesProgram after I started working on it for a bit of time
  - Step 1: Click on File
  - Step 2: Click on Project Structure
  - Step 3: Click on Modules
  - Step 4: Click on the + sign to add the downloaded jar files one by one
  - Step 5: Click on Apply
  - Step 6: Select 13.0.2 (java version "13.0.2") as your Module SDK
  - Step 6: Click on Apply again
  - Step 7: Click on Finish
- Step 6: Drag and Drop the Project Files From The Repo Folder on your PC into the src folder of the newly created project in IntelliJ IDEA
- Step 7: Click on Build
- Step 8: Click on Build Project

**Running** 
- Step 1: Click on the arrow to the left of src folder
- Step 2: Right-Click on PortfolioTester file
- Step 3: Click on Run 'PortfolioTester.main()'