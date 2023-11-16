# OOAD
 
## Domain: Banking
 
Use case : When a customer attempts to deposit money, the list of all accounts which the customers possess should be listed so that the customer can select to which account he would like to deposit the money. Customer can have the following accounts
 
#### SavingsMaxAccount
 
#### CurrentAccount
 
#### LoanAccount
 
· Customer(customerCode, customerName, List<Account>)
 
· Account(accountNo, accountType, balance, Product).
 
· Product(productCode, productName, List<Service>)
 
· SavingsMaxAccount is a Product(minimumBalance of Rs.1000 should be maintained in the account)
 
· CurrentAccount is a Product
 
· LoanAccount is a Product.(chequeDeposit should be chargeable ie 3%).
 
· Service(serviceCode, serviceName,rate)
 
### Default services
 
SavingsMaxAccount(CashDeposit, ATMWithdrawl, OnlineBanking)
 
CurrentAccount(CashDeposit, OnlineBanking, ATMWithdrawl, MobileBanking)
 
LoanAccount(CashDeposit, ChequeDeposit)
 
 
## Class Diagram
![image](https://github.com/sreelachu22/OOAD/assets/71555915/a67017f2-2573-4180-b509-2915b09c95dd)
