# Email Application
This Java program is designed to manage employee email accounts within a company. It allows for setting up email addresses, generating random passwords, and managing mailbox capacities.

## Features
* **Email Generation:** Automatically creates a company email address based on the employee's first and last name and department.
* **Random Password Generation:** Generates a random password for each new email account.
* **Department Assignment:** Prompts the user to assign a department to the employee using a simple code.
* **Mailbox Management:** Allows setting a custom mailbox capacity and an alternate email.
* **Password Management:** Enables changing the account password.
  
## Requirements
* Java Development Kit (JDK) 8 or higher.
 
## Usage
1. Clone or download this repository to your local machine.

2. Compile the Java program:
*javac emailApp/email.java*

3. Run the program:
*java emailApp.email*

4. Follow the prompts to enter the first name, last name, and department code for the new employee.

5. The program will display the generated email address and password.

## Class Overview
* **email:** Main class for handling email generation and management.
* **Attributes:**
  * firstName, lastName: Employee's first and last name.
  * password: Randomly generated password.
  * department: Department of the employee.
  * email: Generated email address.
  * mailboxCapacity: Mailbox capacity in megabytes.
  * alternateEmail: Alternate email address for the employee.
* **Methods:**
  * setDepartment(): Prompts user for department and returns it.
  * randomPassword(int length): Generates a random password.
  * setMailboxCapacity(int capacity): Sets the mailbox capacity.
  * setAlternateEmail(String altEmail): Sets an alternate email.
  * changePassword(String password): Changes the account password.
  * showInfo(): Displays employee's email information.
  * 
## Customization
* Modify companySuffix to change the company's email domain.
* Adjust defaultPasswordLength to change the default password length.
* Add or modify department codes and names in the setDepartment() method.

