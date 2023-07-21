Module 20 Challenge

Description:

This challenge involved creating a contract which allows the user to deposit and withdraw Ether to their joint savings accounts. This contract has three functions inside of it: withdraw, deposit, and another to set addresses to their accounts. There is also the fallback function which allows Ether sent outside of the deposit function to the address to still be caught.

Details:

This is the code for the withdraw function:

![screenshot1]()

Then we add the deposit function:

![screenshot2]()

Then to finish the contract we add the function to add the addresses for the savings accounts, the fallback function is also added:

![screenshot3]()

After completing the code, the contract was compiled and deployed to test. First, we set the addresses for the accounts:

![setaccounts]()

Then we deposited 1 ether as wei:

![transaction1]()

Another deposit was transacted for 10 ether as wei:

![transaction2]()

The last deposit was for 5 ether:

![transaction3]()

To test the withdrawal function we withdrew 5 ether into accountOne, and 10 ether into accountTwo, these screenshots also showcase the lastToWithdraw and LastWithdrawAmount functions working:

![withdraw1]()

![withdraw2]()

Author: Nahin Hayat https://www.linkedin.com/in/nahinhayat/