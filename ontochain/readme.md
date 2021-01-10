# Meta-Belarus Core Ecosystem
## Introduction
### Meta-Belarus Ecosystem
Meta-Belarus is an ecosystem of services and ledgers, that should automate self-governance for Belarusian society based on direct and liquide democracy.

Out main approach is not to mirror the existing delegative democracies, that stands on document based bureaucracies, but to rebuild everytihng based on internet infromation flow and structures, leveraging total distruction of rights and government institutes in Republic of Belarus.

### Meta-Belarus Core Ecosystem
Meta-Belarus Core is a minimal set of basic services that are required to organize scalable self-governement.

Core services includes:
1. Citizen Register
2. Voting System
3. Inititatives and Decisions System
4. Fiscal System
5. Decentral Bank

Principles that Meta-Belarus Core is based on:
1. Decentralization — all core services are decentralized ledgers;
2. Users manage admins — users vote for and downvote serivces that allowed to have administrative rights in the core;
3. Free for users — transactions in ledgers are free for users, Decentral bank rewards infrastructure providers (Validators)

## Meta-Belarus Core
This sections provides short overview of core services.
### Overview
Every service in the core is a crypto-governance blockchain ledger. Main pecularities of such ledgers is that they are not self sufficient. 

* The economy of such ledger is based on the Decentral bank capabilities, that should be fueled by the Fiscal system and extenral funds, that are linked to the core as external services.
* Initiatives and decision system relays on the Voting system and can lead to registration of new services with admin capabilities (that should represnet gov. oranizations, fundations, etc.)
* Fiscal System uses Decentral bank to operate Meta-Belarus currency.
* Citizen Register provides authentication and identitfication data for the core services.

### Abstract Core Ledger 
Every Core Service has common architecture:
![Abstract Core Ledger](./mbcore_abstract.png "Abstract Core Ledger")

It has:
1. A mechanism to register external services as a gov. services with admin rights in the ledger. 
2. A module that allows to ligitimise transactions only by citizens from the citizen register.
3. Set of customized modules of the Cosmos SDK, that supports crypto-gov economy.

Every core service is based on Cosmos SDK and Tendermint BFT enigne.

### Citizen Register
Citizen Register represents the ledger that contains people IDs.

Its main responsibilities are:
1. To guranty identity and deduplication of citizens to protect from abuse of Meta-Belarus services and core by intruders;
2. To provide verifiable data about citizens that can be used by other services;

### Voting system
Voting system represnets the ledger that allows to manage and protect voting about any decision in the sociaty.

Its main responsibilities are:
1. To organize voting by any Meta-Belarus participant with clearly regulated requirements;
2. To provide voting capability for citizens;
3. To guranty protection of voting from intruders;

### Inititatives and Decisions System
Initiatives and Decisions System is required to help people and organizations to start initiatives from courtyard imprvments and law changes to intercity road building and foreign policy decisions.

Its main purposes are:
1. To define and automatize the process of an initiative definition and discussion;
2. To define quorum for voting for decision or initiative and provide input for voting system;
3. To help organizing funding and executive comity;
4. To provide clear report about progress and performance to the interested persons;

### Fiscal system
Fiscal System is a service that regulates financial and tax relations between participant of economy transactions (including Meta-Belarus as a governance entity).

Its main purposes are:
1. To define the product and service in categories of tax and law;
2. To register transactions and distibute payments and fees between participating parties (including taxation);
3. To guaranty instant deductions to appropriate fundations and iniatives;

### Decental bank
Decenatal Bank is an entity that issues and regulates Meta-Belarus currency. 

Its main purposes are:
1. Issuing and regulation Meta-Belarus currency based on the capabilities of the economy and linked funds;
2. To collect taxes to support Meta-Belarus core and non-core services;
3. To reward infrastructure holdes (validators) of core and non-core services;

## Citizen Register
Right now we are in the process of development of Citizen Register ledger.

Citizen Resiger Service is a basic service of Meta-Belarus core. It's main responsibility is identification of citizens and prevention of intrusions in the Meta-Belarus Core using malicious practices like: duplication of accounts and false-identity.

### Architecture of Citizen Register
![Citizen Register Architecture](./cr_architecture.png "Citizen Register Architecture")

### Main Use-Case of Citizen Register

### Transactions of Citizen Register

### Further Development and additional Software