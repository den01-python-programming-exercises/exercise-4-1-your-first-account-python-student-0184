[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=3477891&assignment_repo_type=AssignmentRepo)
# Exercise 4.1 Your First Account

The exercise template comes with a ready-made class named `Account`. The `Account` object represents a bank account that has balance (i.e. one that has some amount of money in it). The accounts are used as follows:

```python
artos_account = Account("Arto's account", 100)
artos_swiss_account = Account("Arto's account in Switzerland", 1000000)

print("Intial state")
print(artos_account)
print(artos_swiss_account)

artos_account.withdraw(20)
print("The balance of Arto's account is now: " + str(artos_account.balance()))
artos_swiss_account.deposit(200)
print("The balance of Arto's other account is now: " + str(artos_swiss_account.balance()))

print("End state")
print(artos_account)
print(artos_swiss_account)
```

Write a program that creates an account with a balance of 100, deposits 20 in it, and finally prints the balance.

**NB!** Perform all the operations in this exact order.
