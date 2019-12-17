The CarboDebt conract directory.
A smart contract/ dApp framework for tracking  emission responsabilities associated with the consumption of hydrocarbon resources. 

Not a carbon credit program. It is a debt contract. The pupose of the contracts are to provide a scientifically rigorous account of where emission debt is coming from and how it is being traded. 

There is no explicit value attributed to the contract, however the holder may have reason to pay a fee to abate their emissions through an approved carbon sinker, such as sequestration, reforestation ...

Sinkers can 'stamp' the CarboDebt to issue CarboGold, converting it into a neutral emission: an amount of carbon removed from the atmosphere based on agreements between debt participants. The value of carbon gold could reflect the marginal cost of the carbon sinker, or some perceived value that a producer/consumer may be willing to pay to receive CarboGold rather than CarboDebt, as proof of offset emissionsl


We summarize the function of the carbo-debt contract in the 5 points below.

1.  anyone can create a carbo debt wallet to issue carbon budget attributed to production ownership of commodity with a known energy content/intput 

2.  Each participant in a contract is defined by a given decentralized identifier (DiD)
    supplier (hydrocarbon producers). Usually the first creators of carbon debt
    consumer (can voluntarily create debt contract if not initiated further upstream)
    carbon sinker (sequestration, reforestation, ,,,)

    sinkers also play the role of converting Carbon debt into carbon gold ...

3.  Can request to send/receive carbo debt from a counter-party, with the all parties approval (signature)

4.  The debt contract is transferred on 
        sale of commodity, 
        paying sinker to offload the responsability

5.  Contract participants can fund contract use by carbon manager to off-take the debt

6.  Recipients can decline to receive the debt, and contract may communicate the additional charge for retaining the debt. Or sender cna offer the option to receive CarboGold in exchange for an additional fee.


There are two strategies for implementing carbo-debt;
    1. a trustless and voluntary carbon management game (more complex network dynamics, easier institutional framework)
    2. a trusted/permissioned binding contract  (less complicated network design, more challenging institutional design). 


Trustless game, anonymous voluntary participation. 
    a. A non-binding carbon management game
    b. designed to operate on a permissionless network (e.g. ethereum). More copmlex network dynamics
    c. Anyone can create a wallet to voluntarily issue debt contracts
    d. Wallet owners are free to choose the DID used to represent it in a debt contracts as
    e. Within the game there is no trust held in the the role of each contract participant. They can not be held accountable for their stated role. This are non-binding.Does not guarantee that a contract participant conforms to the DID it has selected
    f. Network scalability becomes a challenge under this design
    g. decentralized but trustless. anyone can create a DID and therefore offload any accumulated debt by owning keys to both a carbon consumers , and management DID. 
    h. Need to establish rules that encourage fair competition. For example most creative strategies for offloading debt

Trusted identity network . Legally accountable contracts.

    a. Operate under a permissioned ID network (e.g. hyperledger Indy) where stewards are selected to issue trusted decentralized identifiers (DIDs)
    b. Only stewards can issue verified DIDs (trusted) 
    c Greater network scalability and efficiency
    d. must establish an independent governance body to ensure fair and decentralized DID registration
    e. easier network to operate, but requires development of multilateral institutions on how to manage trust in carbon debt contracts
    f. fair representation/registration of producers and consumer's  
    g. independent environmental institutions to regulate DID fo carbon managers
    h. Efforts needed to avoid centralization of the trusted DID network
    can be legally binding as there is an element of trust in DID ownership and issuance
    i. Cheating is less of an issue (trust) but must invest in oversight and complex rules to govern the issuance and expiry of DIDs and contract terms.


See below a list of proposed Carbon credit schemes (competitors?)

https://medium.com/@robertgreenfieldiv/blockchain-enabled-carbon-credit-markets-1a195520f0e1

https://medium.com/@rzurrer/the-carbon-token-ecosystem-white-paper-a-decentralized-p2p-self-organizing-consensus-mechanism-and-aa218bdeeb64

https://drive.google.com/file/d/1D4jmU_TQ3TnEaBhMNpM-phs1tZvRwttn/view
