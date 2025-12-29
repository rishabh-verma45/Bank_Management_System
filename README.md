# Bank Management System (ATM Simulator)

A robust, modular desktop application developed in **Java** that simulates core banking functionalities and ATM operations. This system features a secure multi-stage onboarding process, real-time transaction simulation, and persistent data storage using **MySQL**.

## 🚀 Features

### **User Onboarding & Security**

* 
**Three-Stage Sign-Up:** Comprehensive data collection including personal details, additional financial info, and service preferences.


* 
**Credential Generation:** Automatically generates a secure 16-digit Card Number and 4-digit PIN upon successful registration.


* 
**Secure Authentication:** PIN-based login system to access banking services.



### **ATM Operations**

* 
**Deposits & Withdrawals:** Real-time balance updates with mandatory balance checking for all withdrawals.


* 
**Balance Inquiry:** Instant access to current account standing.


* 
**Mini Statement:** View recent transaction history including date, type (Deposit/Withdrawal), and amount.


* 
**PIN Change:** Functional utility to update security credentials.



---

## 🛠 Tech Stack

* 
**Language:** Java (JDK 8 or higher).


* 
**Frontend:** Java Swing & AWT for the Graphical User Interface.


* 
**Database:** MySQL Server for persistent data storage.


* 
**Connectivity:** JDBC (Java Database Connectivity) with MySQL Connector/J.



---

## 📋 Requirements

### **Software**

* Java Development Kit (JDK) 8+.


* IDE (VS Code, Eclipse, or IntelliJ IDEA).


* MySQL Server.


* MySQL JDBC Connector (.jar file).



### **Hardware (Recommended)**

* 
**Processor:** Dual-Core (Intel i3 equivalent or better).


* 
**RAM:** 4 GB (minimum 2 GB).


* 
**Storage:** 5 GB free space.



---

## ⚙️ Installation & Setup

1. **Clone the Repository:**
```bash
git clone https://github.com/rishabh-verma45/Bank_Management_System.git

```





2. **Database Configuration:**
* Install MySQL Server.
* Create a database named `banksystem` or `bank_db`.


* Update the `Connn.java` file with your MySQL root username and password.




3. **Setup Project Libraries:**
* Add the `mysql-connector-java.jar` to your project build path.


* Ensure the `jcalendar` library is included for the date chooser in the signup form.




4. **Run the Application:**
* Execute `Login.java` to start the application.





---

## 🏗 Future Enhancements

* 
**Fund Transfers:** Direct money transfers between bank accounts.


* 
**Loan Module:** Integrated loan applications and repayment tracking.


* 
**Real-time Alerts:** Integration with SMS/Email APIs for transaction notifications.


* 
**UI Overhaul:** Transition from Swing to a more modern framework for a professional aesthetic.



---

## 👥 Contributors

* 
**Rishabh Verma** (Roll No. 2401331550098).


* 
**Sameer Patel** (Roll No. 2401331550103).


* 
**Shreya** (Roll No. 2401331550114).



**Supervisor:** Mr. Sachin Chawla, Professor, CSE(IOT).
