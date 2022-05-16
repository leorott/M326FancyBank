#M326 Bank

In this Readme are several different use cases and class diagrams to all Bank-tasks to find.

## Bank 2
### Class Diagram
![](classDiagram1.png)
### Use-Case
#### Account Creation
| Name            | Customer creates an account at the bank register         |
|-----------------|----------------------------------------------------------|
| Description     | The banker opens an account                              |
| Actor           | Customer, Banker                                         |
| Initiator       | The Customer wants an account                            |
| Prerequisites   | The Customer has to be allowed by law to open an account |
| Input Data      | Personal details of the customer                         |
| Result          | Confirmation of the account creation                     |
| Post-requisites | An account is opened for the customer                    |
| Process         | 1. account opened <br/> 2. confirm account               |
#### Payment
| Name            | The customer makes a payment                                                |
|-----------------|-----------------------------------------------------------------------------|
| Description     | The banker makes a payment for the customer                                 |
| Actor           | Customer, Banker                                                            |
| Initiator       | The customer wants to do a pament.                                          |
| Prerequisites   | The customer must have an account                                           |
| Input Data      | Account, Amount of Money                                                    |
| Result          | Confirmation of the payment                                                 |
| Post-requisites | The payment is done                                                         |
| Process         | 1. identify account  <br/> 2. Check amount of money <br/> 3. Make a payment |
#### Bank Statement
| Name              | **Kunde erhält einen Kontoauszug für sein Bankkonto** |
|-------------------|-------------------------------------------------------|
| Description       | The banker gives a bank statement to the customer     |
| Actor             | Customer, Banker                                      |
| Initiator         | The Customer wants a bank statement.                  |
| Prerequisites     | The customer must have an account                     |
| Input Data        | Account                                               |
| Result            | Customer receives bank statement                      |
| Post-requisites   | -                                                     |
| Process           | 1. identify account <br/> 2. give the bank statement  |
## Bank 3
### Class Diagram
![](classDiagram2.png)
#### Booking trigger
| Name            | Customer triggers a booking                     |
|-----------------|-------------------------------------------------|
| Description     | The customers shares his booking with the baker |
| Actor           | Customer, Banker                                |
| Initiator       | The Customer wants to trigger the booking       |
| Prerequisites   | The customer must have an account               |
| Input Data      | Account, Amount of money                        |
| Result          | Amount of money is deposited or withdrawed      |
| Post-requisites | -                                               |
| Process         | 1. identify account <br/> 2. trigger booking    |
## Bank 4
### Class Diagram
![](classDiagram3.png)
#### Open a Salary-, Save- and Youth savings account
| Name            | Customer opens a Salary-, Save- and Youth savings account        |
|-----------------|------------------------------------------------------------------|
| Description     | The Customer shares his prefered type of account with the banker |
| Actor           | Customer, Banker                                                 |
| Initiator       | The Customer wants to open his type of account                   |
| Prerequisites   | The customer must have an account                                |
| Input Data      | Account, type of account                                         |
| Result          | A Salary-, Save- and Youth savings account is opened             |
| Post-requisites | -                                                                |
| Process         | 1. identify customer <br/> 2. open account                       |
