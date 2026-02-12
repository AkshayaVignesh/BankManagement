****Bank Management System ****

**📌 Project Overview****

The Bank Management System is a Java-based application developed to manage basic banking operations in a structured and efficient manner. This project follows a layered architecture design including Bean, DAO, Service, Util, and Main packages.

The system allows users to perform banking transactions such as fund transfer, balance validation, and exception handling. The main goal of this project is to demonstrate real-world banking logic implementation using Java and JDBC connectivity.

**🎯 Objectives**

To implement core banking operations using Java

To apply layered architecture (Bean, DAO, Service pattern)

To connect Java application with database using JDBC

To handle exceptions like insufficient balance

To demonstrate proper package structuring in Java


**🛠️ Technologies Used**

Programming Language: Java (JDK 22)

Database: Oracle

JDBC Driver: ojdbc17.jar

IDE Used: Eclipse

Architecture Pattern: Layered Architecture (DAO Pattern)

**🗂️ Project Structure**

The project is organized into multiple packages for better maintainability:

com.wipro.bank.bean
TransferBean.java – Contains data members and getter/setter methods

com.wipro.bank.dao
BankDAO.java – Handles database operations

com.wipro.bank.service
BankService.java – Contains business logic

com.wipro.bank.util
DBUtil.java – Database connection utility
InsufficientFundsException.java – Custom exception handling

com.wipro.bank.main
BankMain.java – Entry point of the application

**⚙️ Features**

💳 Fund Transfer between accounts

🏦 Database connectivity using JDBC

⚠️ Custom exception for insufficient balance

🧩 Proper package separation (Bean, DAO, Service, Util)

🔄 Clean layered architecture

**Output**
<img width="1658" height="423" alt="image" src="https://github.com/user-attachments/assets/4144fc97-6fec-45b9-8b2a-c5b49d3bda61" />


**📌 Conclusion**

The Bank Management System project successfully demonstrates how Java can be used to build a structured and practical banking application. By implementing layered architecture (Bean, DAO, Service, and Util packages), the project maintains clean code organization and follows good programming practices.
Through this project, important concepts such as JDBC connectivity, database operations, exception handling, and object-oriented programming were applied effectively. The use of a custom exception like InsufficientFundsException improves reliability and ensures proper error handling during transactions.
