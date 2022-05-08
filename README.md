# Joint Savings Account

This is an smart contract application that allows to emulate the features, processes and functionality between different financial accounts, such as hosting joint savings accounts. 
For demonstration purposes and to automate the creation of joint savings accounts, it has been created a Solidity smart contract that accepts two user addresses. These addresses are able to control a joint savings account. The smart contract uses ether management functions to implement a financial institution’s requirements for providing the features of these accounts. These features consists of the ability to deposit and withdraw funds from the account.
</br>
</br>
In the following steps, it is explained how the smart contract works:

1. Once the the smart contract script has been finished, we proceed to compile it.
</br>

![Compilation](Execution_Results/compilation.png)

</br>
</br>

2. After the compilation, the smart contract is deployed.
</br>

![Deployed Contract](Execution_Results/deployed_contract.png)
<br/>
</br>

3. Verify the account where the deposits come from
</br>

![Initial Balance](Execution_Results/remix_initial_blce.png)
</br>
</br>

4. The first deposit of 1 ether in wei is completed
</br>

![First deposit](Execution_Results/deposit_1.png)
</br>
</br>

5. The second deposit of 10 ether in wei is completed
</br>

![Second deposit](Execution_Results/deposit_2.png)
</br>
</br>

6. The third deposit of 5 ETH is completed. The total balance is 16 ETH.
</br>

![Third deposit](Execution_Results/deposit_3.png)
</br>
</br>


7. There is a withdraw of 5 ETH from the joint savings account to account One.
</br>

![First withdraw](Execution_Results/withdraw_1.png)
</br>
</br>

8. There is a withdraw of 10 ETH from the joint savings account to account Two.
</br>

![Second withdraw](Execution_Results/withdraw_2.png)
</br>
</br>

9. After the withdraws, the final balance of the contract is 1 ETH
</br>

![Final Balance](Execution_Results/remix_end_blce.png)


