# quest-submissions
Submissions for Emerald Bootcamp

# Chapter 1 day 1 submissions

## 1. Explain what a blockchain is, in my own words:

A blockchain is a trustless shared database that ideally doesn't have a single point of failure (other than the internet in entirety.) It can allow people to transact resources in the form of "tokens" (fungible or non,) in a manner that can't be exploited, easily anyhow.

## 2. Explain what a smart contract is:

A smart contract is a program that runs on the blockchain. The perks are being able to form a pool of custom-made tokens, fungible or non, and perhaps shouldering some server costs by offloading mission critical code to that virtual machine.

## 3. Explain the difference between a transaction and a script:

A transaction changes the data of a smart contract in some way. A script only views the data, without modifying it.

# Chapter 1 day 2 submissions

## 1. What are the five pillars of the Cadence programming language?

1: Safety and security: It has an insanely strong type system, seperation between contracts and transactions, and resource-oriented programming.

2: Clarity: The code is easy to read because it is declarative, so intent can be expressed clearly, which makes it easy to audit and review.

3: Approachability: It is written similarly to other programming languages, so adoption is easier.

4: Developer experience: Error messages are clear, so the contracts are easy to debug.

5: Resource oriented programming: Basically information that can't be in two places at once without causing an error in Cadence.

## 2. Without looking it up, why would these pillars be useful in coding?

These pillars seem to make for an advantageous and approchable means of utilizing the blockchain for your app.

# Chapter 2 Day 1 submissions

## 1. Deploy a contract to account 0x03 called "JacobTucker". Inside that contract, declare a constant variable named is, and make it have type String. Initialize it to "the best" when your contract gets deployed.

Done.

## 2. Check that your variable is actually equals "the best" by executing a script to read that variable. Include a screenshot of the output.

![Screenshot 2022-05-25 at 16-32-43 Try out this Playground project](https://user-images.githubusercontent.com/38636207/170386380-2c12fc7e-6f54-43c4-99b0-8c3ed43829a5.png)

# Chapter 2 Day 2 submissions

## 1. Explain why we wouldn't call changeGreeting in a script

changeGreeting changes the state, a script can't do that.

## 2. What does Authaccount mean in the 'prepare' phase of the transaction?

It authorizes the smart contract to access the information in your account.

## 3. What is the difference between the prepare phase and the execute phase in the transaction?

Prepare reads info/data in your account, and execute modifies blockchain data.

