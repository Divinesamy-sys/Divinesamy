

# Blockchain Transactions: How a Crypto Transaction Works

## Overview

When someone sends cryptocurrency to another person, the transaction does not simply move from one digital wallet to another.

Instead, the transaction is created, digitally signed, broadcasted to a blockchain network, verified by network participants, and eventually recorded on the blockchain.

Understanding this process provides a useful foundation for understanding how cryptocurrencies work.

## What Is a Blockchain?

A blockchain is a distributed digital ledger that records transactions across a network of computers.

Unlike a traditional financial database controlled by a single or specific organization, a public blockchain is maintained by multiple independent participants.

Transactions are grouped into blocks, and these blocks are linked together chronologically.

Which creates a history of transactions that can be independently verified.

## What Happens When You Send Crypto?

A typical cryptocurrency transaction involves several stages:

1. The transaction is created.
2. The transaction is digitally signed.
3. The transaction is broadcast to the network.
4. The network validates the transaction.
5. The transaction is included in a block.
6. The blockchain reaches the required confirmation state.

Let's look at each stage.

## 1. Creating the Transaction

Suppose Person A wants to send cryptocurrency to Person B.

Person A enters Person B's wallet address and specifies the amount he wants to send.

The transaction generally contains information such as:

* Sender information
* Recipient address
* Amount
* Transaction fee
* Other network-specific data 

The exact structure depends on the specific blockchain in use.

## 2. Signing the Transaction

Before the transaction can be submitted to the network, Person A's wallet signs it using her private key.

The private key is a cryptographic credential that allows the wallet to prove that the transaction was authorized by the owner of the relevant assets.

The private key itself should not be shared with anyone.

> **Important:** A wallet address can easily be shared to receive cryptocurrency assets. However, a private key or recovery phrase should be kept secured by the owner.

## 3. Broadcasting the Transaction

After signing, the wallet broadcasts the transaction to the blockchain network.

The transaction is then distributed to participating network nodes.

At this stage, the transaction has been submitted but may be temporarily recorded on the blockchain.

## 4. Transaction Validation

Network participants verify whether the transaction follows the blockchain's rules.

Depending on the network, validation can include checks such as:

* Whether the transaction is properly signed
* Whether the sender has sufficient funds
* Whether the transaction follows the network's rules
* Whether the transaction has already been processed
**
Invalid transactions are rejected.
**
## 5. Inclusion in a Block

Valid transactions are selected for inclusion in a block.

How blocks are created and validated depends on the blockchain's consensus mechanism.

For example, Bitcoin uses Proof of Work, while Ethereum currently uses Proof of Stake.

Once a transaction is included in a block, it becomes part of the blockchain's recorded history.

## 6. Confirmations

After a transaction is included in a block, additional blocks may be added to the chain.

These additional blocks provide further confirmation that the transaction has been recorded.

The number of confirmations considered sufficient can vary depending on the blockchain, application, and risk tolerance.

## What Is a Transaction Fee?

Most blockchain networks require users to pay a transaction fee.

The fee compensates network participants for processing and securing transactions.

Transaction fees vary depending on factors such as:

* Blockchain network
* Network activity
* Transaction complexity
* Current demand for block space

A busy network can result in higher fees or longer processing times.

## Why Can't a Blockchain Transaction Usually Be Reversed?

One of the first things you should understand about cryptocurrency is that **blockchain transactions are usually irreversible once they have been confirmed**.

When you send cryptocurrency, the transaction is verified by the blockchain network and recorded on its public ledger. After confirmation, there is generally no button you can press to cancel or undo the transaction.

This is mainly because public blockchains do not have a central authority, such as a bank or payment provider, that can simply reverse a completed transaction. Instead, transactions are processed according to the rules of the blockchain network.

For example, imagine you want to send 0.1 ETH to a friend but accidentally enter the wrong wallet address. If the transaction is confirmed, the blockchain records the transfer to that address. Your wallet cannot normally reverse it or retrieve the funds. If the recipient controls the wallet, you would generally need them to send the cryptocurrency back to you.

This is different from traditional payment systems. With a bank transfer or card payment, the bank or payment provider may have procedures for cancelling, reversing, or disputing certain transactions.

 With cryptocurrency, recovery is often much more difficult because there is no central authority with the power to simply undo a confirmed blockchain transaction.


`The process would look roughly like this:

```text
you creates transaction
        ↓
Wallet signs transaction
        ↓
Transaction broadcast to network
        ↓
Network validates transaction
        ↓
Transaction included in block
        ↓
Additional blocks provide confirmations
        ↓
recepient's wallet reflects the received funds
```

The exact process varies between blockchains, but the general concept remains similar.
`
### What Should You Check Before Sending Crypto?

Because blockchain transactions are usually difficult to reverse, it is important to check the details carefully before confirming a transaction. In particular, verify the **recipient's wallet address, the amount you are sending, the blockchain network, and the transaction fee**.

You should also remember that sending crypto to the wrong network or an unsupported address can create additional recovery problems, depending on the assets, networks, and platforms involved.

The key point is simple: **always verify a crypto transaction before confirming it**. Once the transaction has been confirmed, correcting a mistake may not be possible.

## Key Takeaways

* A blockchain is a distributed ledger maintained by a network of participants.
* A crypto transaction is created and digitally signed before being broadcast.
* Network participants validate transactions according to the blockchain's rules.
* Valid transactions are included in blocks.
* Additional blocks can provide further confirmation.
* Transaction fees vary depending on the blockchain and network conditions.
* Users should carefully verify transaction details before signing.

## Related Topics

* Crypto Wallets
* Private Keys and Recovery Phrases
* Blockchain Consensus
* Smart Contracts
* Transaction Fees
