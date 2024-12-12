PROJECT NAME: BANK MANAGEMENT SYSTEM

I. A brief project overview : 
      Our  project is built in java programming language with text base approach  and the name of our text base project is banking system  that  the user can create new account , check their  balance, deposit amount, withdrawing amount, and view the client profile. 

II. Explanation of how oop principles were applied on this system : 
Encapsulation:  The BankAccount and SavingsAccount classes encapsulate data related to a bank account  like account name, address, contact information, and balance and the operations that can be performed on them such as deposit, withdraw, balanceInquiry.so  that’s why the system use encapsulations .

      Abstractions: The BankAccount and SavingsAccount classes abstract away the details of how accounts are handled. On this system the user doesn't need to know how the balanceInquiry() method works internally or how the accountNo is generated. They only need to know that these methods can be called to interact with the account.
The SavingsAccount class extends the BankAccount class, adding specific behavior (like interest calculation) but still adheres to the common behaviors (deposit, withdrawal, balance inquiry) defined in the parent class.

    Inheritance: on the system The SavingsAccount class inherits from the BankAccount class. This means that the SavingsAccount inherits properties like accountName , address, birthday, and contactNumber of the user from BankAccount and can use methods like getClientDetails() like what is said before the name,address,birthday,and contact number , without needing to re-implement those functionalities.
 
   Polymorphism: The SavingsAccount class overrides the deposit method of         BankAccount to add interest after depositing the amount. The same method (deposit)   works differently depending on whether it’s called on a BankAccount object or a SavingsAccount object it means the system can do method of overriding the savings and accounts of the user and overloading method which means it can use for depositing and withdrawing amount like 500 minimum deposits . 

III. Details of the choses SDG  and ints integration into the project : 
     This codes promotes the SDG 8 : Decent work and economic Growth because this  code can use for the processing like the banksystem By enabling deposits and savings, the system can contribute to the flow of capital within the economy, supporting investments and generating interest for economic growth.

Iv. Instructions for running the program: 
     First  you need to input the code on the vscode (BankSystem.java)  then run the code, 
     
-First There’s  have an options for the menu you can choose ,”new account” , “balance inquiry” , “deposit” , “withdraw” , “client profile” , “close account” and “exit” 
 choose  new account if to create  account for the user for the creating account you need to input this  details info of the user  (NAME, ADDRESS, BIRTHDAY, and Enter the deposit amount with the minimum of 5000 

-Second  options is balance inquiry  you need to input number 2 to select  and now  you can now check the balance on your bank account

-Third  is deposit  just input 3 to deposit  new amount or additional amount on your back account 

-Fourth withdraw just input 4 to withdraw the amount you want make sure you withdraw the amount not exceed on the balance on your account. 

-Fifth client profile just input 5 to see the profile and make sure you  can input the right account number for  your account to access it so are you can see the remaining balance of your  account 

-And  last is close account and exit. 

