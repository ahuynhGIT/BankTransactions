###### BankTransactions

####### Account.java

The purpose of this class is to take in values for a bank account number, pin number, and the balance within the account. It verifies the validity of said data and manipulates it accordingly. It then outputs the data as well as checks to see if the first account's contents are equal to the third account's contents. This class acts as the superclass to the Transaction class.

####### Transaction.java

The purpose of this class is to be able to take in 5 data fields and initialize them as variables. This class then uses the data to output a message regarding the comparison between two objects. Specifically in this case, we compare two objects of type Transaction that is defined by a transaction number, transaction type, and account ID. Finally, in this program, this class acts as the superclass to both the Withdrawal and Deposit classes while being a child class of the Account class.

####### Deposit.java

The purpose of this class is to be able to deposit funds into a bank account.Given 6 data fields, 5 of which are derived from a seperate class, this class modifies the balance of the account depending on the amount deposited and the transaction type. This class is a child class of Transaction.java.

####### Withdrawal.java

The purpose of this class is to be able to withdraw an amount of money, assuming enough funds are available. Given 6 data fields, 5 of which are derived from the transaction class, this class modifies the balance based on the desired amount withdrawn and the transaction type. This class is a child class of Transaction.java.


