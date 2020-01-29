## solidity_homework

In this project three ProfitSplitter contracts were created.


AssociateProfitSplitter:  Accepts Ether into the contract and divide the Ether evenly among the associate level employees


TieredProfitSplitter: Distributes different percentages of incoming Ether to employees at different tiers/levels.  The CEO gets paid 60%, CTO 25%, and Bob gets 15%.


DeferredEquityPlan: This contract automatically manages 1000 shares with an annual distribution of 250 over 4 years for a single employee.

# AssociateProfitSplitter

In Remix a 3 Ether transaction was schedule using the local server and the transaction when through. Sending 1 Ether to each employee. As corroborated in Ganache transactions

![supply_chain](/images/f.png)
![supply_chain](/images/d.png)

# TieredProfitSplitter

For the Tiered contract 10 Ether were transacted using the local server. 

CEO Account 0x6e2A721c2f78C6E63bd284e91FDcEcae725bCF65

CTO Account 0x68d1a75A371721F16cC5117F927a957Fe96Df1F2

Bob's account 0x12Cb9f596aE01fE041d5e766C340b91D798891B9

This transactions can also be seen on the Ganache image shown above.

After this the contracts were deployed to the Ropsten network. and the same transaction were made again, after recharging ether from the faucet. This time the wallets were managed in MyCrypto. Below the three images show the 10 ether deposited to the CEO, CTO and Bob. The tier distribution again was performed by the contract, so that 60%, 25% and 15% of Ether was distributed accordingly

![supply_chain](/images/a.png)
![supply_chain](/images/b.png)
![supply_chain](/images/c.png)

# DeferredEquityPlan

Finally, for the deferred equity plan, time was forwarded by 1 year. The number of distributed shares the employee has is 250, as shown below.

![supply_chain](/images/dist.png)

