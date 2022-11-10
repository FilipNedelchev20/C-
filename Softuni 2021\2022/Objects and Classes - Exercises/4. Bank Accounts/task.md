Create a class called BankAccount. The class should have properties: Id (integer), Balance (double) and
methods: Deposit(double amount) and Withdraw(double amount). Until the "End" command, you will receive one
of the following commands:
 Create {Id} – you should create new account with empty balance.
 Deposit {Id} {Amount} – you should add the given amount to the balance of the account the given Id.
 Withdraw {Id} {Amount} – you should subtract the given amount of the balance of the account the given Id
 Print {Id} – print information about the account with the given Id.
If you try to create an account with existing Id, print "Account already exists".
If you try to perform an operation on non‐existing account, print "Account does not exist".
If you try to withdraw an amount larger than the balance, print "Insufficient balance".
Print command should print "Account ID {id}, balance {balance}". Round the balance to the second digit
after the decimal separator.
