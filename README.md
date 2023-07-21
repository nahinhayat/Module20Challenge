Module 20 Challenge

Description:

This challenge involved creating a contract which allows the user to deposit and withdraw Ether to their joint savings accounts. This contract has three functions inside of it: withdraw, deposit, and another to set addresses to their accounts. There is also the fallback function which allows Ether sent outside of the deposit function to the address to still be caught.

Details:

This is the code for the withdraw function:

![screenshot1](https://github.com/nahinhayat/Module20Challenge/blob/main/module20screenshots/screenshot1.png)

Then we add the deposit function:

![screenshot2](https://github.com/nahinhayat/Module20Challenge/blob/main/module20screenshots/screenshot2.png)

Then to finish the contract we add the function to add the addresses for the savings accounts, the fallback function is also added:

![screenshot3](https://github.com/nahinhayat/Module20Challenge/blob/main/module20screenshots/screenshoit3.png)

After completing the code, the contract was compiled and deployed to test. First, we set the addresses for the accounts:

![setaccounts](https://github.com/nahinhayat/Module20Challenge/blob/main/module20screenshots/setaccounts.png)

Then we deposited 1 ether as wei:

![transaction1](https://github.com/nahinhayat/Module20Challenge/blob/main/module20screenshots/transaction1.png)

Another deposit was transacted for 10 ether as wei:

![transaction2](https://github.com/nahinhayat/Module20Challenge/blob/main/module20screenshots/transaction2.png)

The last deposit was for 5 ether:

![transaction3](https://github.com/nahinhayat/Module20Challenge/blob/main/module20screenshots/transaction3.png)

To test the withdrawal function we withdrew 5 ether into accountOne, and 10 ether into accountTwo, these screenshots also showcase the lastToWithdraw and LastWithdrawAmount functions working:

![withdraw1](https://github.com/nahinhayat/Module20Challenge/blob/main/module20screenshots/withdraw1.png)

![withdraw2](https://github.com/nahinhayat/Module20Challenge/blob/main/module20screenshots/withdraw2.png)

Author: Nahin Hayat https://www.linkedin.com/in/nahinhayat/