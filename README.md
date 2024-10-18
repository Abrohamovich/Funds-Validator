# Java Project Documentation

---

This project implements a functionality to check whether there are enough funds on the balance before making a purchase.

The programme specifies the current account balance and requests the purchase amount, 
after which it checks whether there are enough funds for payment. 
If there are enough funds, the purchase is confirmed and the balance is updated. 
Otherwise, a message about insufficient funds is displayed. 

The method of checking if there are enough funds is implemented using the if-else construct, 
where in case of insufficient funds we are thrown to the `try-catch` block, 
where it throws a custom `FundsException` error using the `throw` keyword.



