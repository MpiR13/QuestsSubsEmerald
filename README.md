# QuestsSubsEmerald

## Chapter 1 Day 1

1.Explain what the Blockchain is in your own words. You can read this to help you, but you don't have to: https://www.investopedia.com/terms/b/blockchain.asp

Answer 1.. The blockchain is a public ledger of shared (database info on blocks instead of tables) that keeps immutable data time stamped in 'blocks' that connect to one another using hash cryptography to ensure that each block is truthful and trusted based on the previous blocks by a peer-to-peer system of decentralized nodes where multiple user solve complicated mathmatical equations to solidify each transaction that cannot be altered, deleted or destroyed.

2.Explain what a Smart Contract is. You can read this to help you, but you don't have to: https://www.ibm.com/topics/smart-contracts

Answer 2.. Smart contracts are designed by developers to follow a certain set of guidelines that once implemented will react by taking in certain sets of data for which the function asks for , then saves and stores this data, then sends all this updated information to the blockchain. They are simple programs that execute only when these predetermined rules are met and then stored on the chain. They automate once the agreement is met by all parties, are fast, secure and lets every participant know when the condtions are met without the need for a third party and happens almost immediately. 

3.Explain the difference between a script and a transaction.

Answer 3.. A script is a 'free' set of commands used to automate actions or tasks within a program whereas a transaction is a PAID function that changes data on the blockchain and therefore cost money.

## Chapter 1 Day 2

1. What are the 5 Cadence Programming Language Pillars?

Answer 1..

1) Safety & Security
2) Clarity
3) Approachability
4) Developer Experience
5) Resource Oriented Programming 

2. In your opinion, even without knowing anything about the Blockchain or coding, why could the 5 Pillars be useful (you don't have to answer this for #5)?

Answer 2..
1) (provides maximum effectiveness while maintaining high levels of security based on a strong type system format)
2) (ease of readability)
3) (similar to other languages and therefore easy to understand and learn quickly)
4) (deubugging is clear and allows for error messaging to be easily recognizable)
5) (uses Recources that define how things work in Cadence)

## Chapter 2 Day 1

screenshots added in quests submission on discord 8-17-22

![Screen Shot 2022-08-17 at 4 45 42 PM](https://user-images.githubusercontent.com/29616399/185259125-e60a9802-7467-4d0e-90bc-77ee1c784407.png)

![Screen Shot 2022-08-17 at 4 46 22 PM](https://user-images.githubusercontent.com/29616399/185259199-8d2b77f9-d4fc-456b-b3ff-496e3e056dc7.png)

## Chapter 2 Day 2

1. Explain why we wouldn't call changeGreeting in a script.

Answer 1..  Because a script is READ ONLY in the contract and if we are trying to change the greeting, we would need to enact a transaction in order to alter the blockchain or change it in this case. A transaction would therefore modifiy the state and cost money "gas".

2. What does the AuthAccount mean in the prepare phase of the transaction?

Answer 2..  It means we want to access the data in your account, the information living there.

3. What is the difference between the prepare phase and the execute phase in the transaction?

Answer 3..  The prepare phase accesses your account (to see what data/information is stored in your account) so that the execute phase can call functions and interact to change the data on the blockchain.

4. This is the hardest quest so far, so if it takes you some time, do not worry! I can help you in the Discord if you have questions.

* Add two new things inside your contract:

    ** A variable named myNumber that has type Int (set it to 0 when the contract is deployed)
    
    ** A function named updateMyNumber that takes in a new number named newNumber as a parameter that has type Int and updates myNumber to be newNumber

![Screen Shot 2022-08-17 at 6 27 41 PM](https://user-images.githubusercontent.com/29616399/185257761-7656690d-6334-4d30-9a10-d6c07bd1fd81.jpeg)

* Add a script that reads myNumber from the contract

![Screen Shot 2022-08-17 at 6 27 31 PM](https://user-images.githubusercontent.com/29616399/185258324-31d6a27a-3fe4-4b6f-9c4c-52c899f2ec50.jpeg)

* Add a transaction that takes in a parameter named myNewNumber and passes it into the updateMyNumber function. Verify that your number changed by running the script again.

![Screen Shot 2022-08-17 at 6 34 55 PM](https://user-images.githubusercontent.com/29616399/185258587-ba378217-de6b-4494-ac47-a81c21802abb.jpeg)

![Screen Shot 2022-08-17 at 6 35 03 PM](https://user-images.githubusercontent.com/29616399/185259271-c95e1aad-39b6-4ced-9a55-ea26b11ca686.jpeg)



Quests submissions for Emerald Academy 
# This will be my ReadME file for my Emerald Academy Quests Submissions
