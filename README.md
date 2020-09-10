# Link-of-trust
Simplified Level-2 protocol for digital identity management on top of blockchains and social networks.

- A chain agnostic protocol 
- With multiple implementations (Bismuth and Nyzo being first)
- Cross chain features
- Oracles
- Freedom of interpretation: no consensus nor centralized source of truth, but immutable data powering user defined algorithms and settings
- Digital identity management
- Reputation engine
- Pseudo-uniqueness of digital personas

## References and genesis

- Derives from Bismuth abstract transactions, execution model, and layer-2 protocols.
- Similar in some ways to Web of trust (decentralized pki)
- Oracles (as in blockchain oracles) concept
- Identity centric crypto-currencies

This concept and protocol is something I think of since a long time and have many notes upon.  
Now is the time I make it public and will start implementing for real world use.

## First use case

First use case will be an answer to an urging issue Nyzo currently encounters:

- Any in-cycle verifier can issue cycle transaction to vote upon, with any amount to be paid by the cycle funds.
- Malicious or undiscussed transactions can be put to vote that way, and do get votes
- How do users know there are important cycle transactions to vote upon?
- How do users know what transactions are legit or not?
- un-ironically, we came up to the conclusion that "we need a centralized thing to get decentralized voting to work".

The "Link of trust" protocol aims to solve this problem while avoiding any centralization, invite, co-optation or such censorship.
