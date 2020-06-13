---
layout: post
title:  "Blockchain Journey: What is Blockchain, How it Works and Why We Should Care"
date:   2020-05-26 15:14:54 -0700
categories: Blockchain
---

This post is intended as a non-technical overview of what blockchain technology is, how it works and why we care. 

### What is Blockchain? 
It is difficult to start a conversation about blockchain unless first talking about Bitcoin, as this is usually how most people learn about the existence of the blockchain. 
In the abstract of Satoshi Nakamoto's original [whitepaper](https://bitcoin.org/bitcoin.pdf), Bitcoin is introduced as "a purely peer-to-peer version of electronic cash [that] would allow online payments to be sent directly from one party to another without going through a financial institution." That sentence is the essence of why bitcoin was created. It was created in order to decentralize finance. 

One important thing to understand is that Bitcoin is not Blockchain. Rather, Blockchain can be thought of as the protocol used to power Bitcoin. As such, it has a much wider array of possible applications. 

Along with decentralized finance, it enables innovations on identity management, proof of authenticity, automated smart contracts, proof of provenance, voting processes and much more. These characteristics enable it to transform our models of trust and verification across all industries from centralized models requiring an intermediating authority to one where there is no intermediation needed. 
 
Walmart has recently used blockchain technology to enhance its capabilities to [track lettuce](https://www.nytimes.com/2018/09/24/business/walmart-blockchain-lettuce.html). 
IBM has leveraged blockchain in order to provide a decentralized option to [identity management](https://www.ibm.com/blockchain/solutions/identity), the insurance company AIG is using it to add intelligence to its [smart insurance platform](https://www.reuters.com/article/us-aig-blockchain-insurance/aig-teams-with-ibm-to-use-blockchain-for-smart-insurance-policy-idUSKBN1953CD) and the creator of Javascript and the Firefox web browser is using blockchain technology to transform internet marketing models through the use of a new BAT token in the [Brave web browser](https://brave.com/). 

Essentially, blockchain provides a means to remove central authorities from being a part of your transactions, allowing for a new model of trust in a way that was not possible before.

### How Blockchain Works
The idea of blockchain is not new, there [have been many attempts](https://www.investopedia.com/tech/were-there-cryptocurrencies-bitcoin/) to create decentralized forms of consensus. The blockchain just happened to be the most effective solution. At the heart of it is an algorithm called "proof of work" that solved a problem that is now well known in the computer science world as the [double spending problem](https://www.youtube.com/watch?v=7etOh0YYqcc). 

![](/assets/images/whatisblockchain.png)

The blockchain is primarily a global ledger of transactions that records a history of all activity on it since the beginning of time. It is immutable, meaning that any information created on this ledger cannot be changed. Any attempts to re-write history will not be successful. 

If we think about it, the financial systems as we know them are really just a ledger of transactions. In order to create a financial system we just need to have a system that can satisfy the [properties of money](https://money.visualcapitalist.com/infographic-the-properties-of-money/) and have a secure means of tracking the exchange of this money between private accounts. 

Once we have this, we have a workable financial system. 

What makes the blockchain unique lies in how it handles transactions on this ledger and how we verify that they reflect what actually happened without having to use a trusted third party (like chase bank) to verify it for us.

The way the validations are performed on a blockchain happen via a consensus protocol. This is where the true innovation of blockchain is at the core. The consensus protocol that Bitcoin uses is called the ["proof of work"](https://www.khanacademy.org/economics-finance-domain/core-finance/money-and-banking/bitcoin/v/bitcoin-proof-of-work) algorithm. 
This algorithm, released in 2009, is the first ever solution implemented to solve what is known as the [Byzantine Generals Problem](https://www.youtube.com/watch?v=kZXXDp0_R-w). This is a problem of trying to get all nodes in a network to communicate in a trustable fashion even when one or more nodes in the network cannot be trusted.  

Through the proof of work algorithm machines throughout the network participate in the validation of transactions through a process called mining. Every miner in the network has a full copy of the blockchain's ledger. Whenever a new series of transactions enters the system, they are encoded into a block that needs to be validated. In order to validate a block, miners perform some amount of computational work in exchange for a reward. Once this work is completed the block of transactions is validated and propogated throughout all of the ledgers in the network, all of which are also re-validating the transaction. There is a lot more to this algorithm and other consensus algorithms as well such as ["proof of stake"](https://www.youtube.com/watch?v=M3EFi_POhps). In this blog, there will be future posts that explain these algorithms in detail. 

### Why We Should Care
Bitcoin and other cryptocurrencies has spurred a revolution in finance. Through our current centralized financial systems we have seen much injustice. Capitalism has spurred ever increasing [income inequality](https://www.pewresearch.org/fact-tank/2017/11/01/how-wealth-inequality-has-changed-in-the-u-s-since-the-great-recession-by-race-ethnicity-and-income/). 

In 2008, we saw a great financial crime in the housing market. 
Subprime mortgages were handed out to large populations of borrowers seeking to own a home. These are loans that were given to people with low credit scores (often below 600) to pay for houses. These homes were then bundled into what is known as a [collateralized debt obligation (CDO)](https://www.investopedia.com/ask/answers/032315/were-collateralized-debt-obligations-cdo-responsible-2008-financial-crisis.asp) and sold to investors who were misled to believe that these were secure financial products. This led to an economic recession hurting millions of people. During the aftermath, no policies were enacted to help these people. Instead, the banks were bailed out. 

This financial crime was [subtly recognized](https://www.thetimes03jan2009.com/) in the creation of Bitcoin. When creating the first bitcoin block, called the "origin block", Satoshi Nakamoto timestamped it with the following message "The Times 03/Jan/2009 Chancellor on brink of second bailout for banks". This message suggests that a "liberal" capitalist system rescuing the banks during the financial fallout was a problem for Satoshi, just as it was for many around the world. 

Blockchain is a way to add true liberalism to our economic system. One in which no powerful minority can have authority over the economic systems that drives all of our lives. 

Currently, approximately 2 billion of the worlds 7 billion population [remains without access to a bank account](https://www.businessinsider.com/the-worlds-unbanked-population-in-6-charts-2017-8). They are effectively without the option to participate in the economy and gain the resources needed to create prosperous lives. Of these 2 billion, [many of them have smartphones](https://en.wikipedia.org/wiki/List_of_countries_by_number_of_mobile_phones_in_use). Blockchain enables these indiividuals to turn their cell phones not just into bank accounts but also into their own banks. With Blockchain, the power of banking is now in the hands of every individual.

Currently, there are many challenges to still overcome for Blockchain technology to be feasible enough to transform our global economies as we know them. There are challenges in making it scalable, interoperable, easy to use and many more. At this point, it is not a matter of if, but when these challenges will be overcome to make cryptocurrencies the de-facto standard of what will be used to power our global economies. 

There is a wave of activity happening in the world of [decentralized finance](https://defiprime.com/) (de-fi). As of September 2018, the [total amount of money locked in the decentralized finance world](https://coin.dance/stats/marketcaphistorical) was 200 billion. As of the time of this writing in 2020, the current value locked in is 300 
Billion. 

This is still modest in relation to global capital merkets. The current global equity market is valued at approxomately 80 trillion, the global debt and bond markets at 250 trillion and the global holdings of gold are at about 7 trillion. 

At the same time, we are in the beginning of the story, it is my belief that is it just a matter of time for the world of decentralized finance to start being a serious threat to these global markets. As blockchain technology matures and becomes widely adopted we are likely to see large network effects take place that will exponentially increase its usage in a similar way in which the world saw other pivotal inventions transform our lives such as the radio, the telephone and the internet.


