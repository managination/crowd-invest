# crowd-invest
Use the wisdom of crowds to make investment decisions and store the data in [Ethereum](https://www.ethereum.org/)'s blockchain to provide a verifiable history of predictions.

## Principles

- Create a contract with a question. E.g. `how much will the Apple share be worth in 2 weeks?`
- Enroll 500 people to give an educated guess and pledge a minimum amount of money to back their opinion
- Keep the answers secret until the end of the poling period which can vary from 1 day to 1 month
- If at the end of the polling period enough guesses were submitted, the decision is made based on their average
- Buy leveraged investment opportunities like options on securities for the total amount of all the pledges
- Await result with trepidation
- Either the bet pays off, in which case everyone gets their share based on the pledged amount, or it does not in which case everyone looses. In the case of options, everything is lost

## The case for the blockchain

Like any applicatoin, this could be done with a regular database. So why on earth would we want to store data and logic on a blockchain?

### Guaranteed logic

The contract is made public and all participants have the possibility to check if the description is accurate. As there must be one contract for every question, this is important to know what you are buying.

### Verifiable outcome and history

When money is involved it is important that the outcome can not be rigged. Or else, it could be a rip off. Imagine how easy it would be to earn money if someone could manipulate the outcome of the guesses.

New users can be confident that the history of successes and failures has not been embelished to persuade them to participate.

### No one has an edge

The contract is the same for everyone and as such, the administrator of the application has no way of getting early results, if the contract is written properly. 

## The case for te crowd

It is not possible to get crowd wisdom without the crowd. But also, the transaction fees will be much lower if the buying is pooled.

Ideally we should have an account with a bank or a trader to enable rapid order execution. 
