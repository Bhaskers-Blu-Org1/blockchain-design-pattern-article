# blockchain-design-pattern-article

Blockchain is a shared, immutable ledger for recording transactions, tracking assets and building trust.  An asset can be tangible (a house, a car, cash, land) or intangible (intellectual property, patents, copyrights, branding). Virtually anything of value can be tracked and traded on a blockchain network, reducing risk and cutting costs for all involved. This article will point to a set of design patterns for blockchain-based applications. Blockchain has unique properties including immutability, non-repudiation, data integrity, andtransparency.

Blockchain is an emerging technology that enables new forms of decentralized software architectures, where distributed components can reach agreements on shared system states without trusting a
central integration point. Blockchain provides a shared infrastructure to execute programs, called smart contracts, and to store data.   This emerging technology requires patterns for using blockchain in the design of software architecture or applications.


## Why are design patterns important to software developers?

In general, design patterns define development best practices for software developers. The patterns themselves serve as solutions to general problems; in this case, within the Blockchain space. In software engineering, a design pattern is a reusable solution to a problem that commonly occurs within a given context during software design. A design pattern defines constraints that restrict the roles of architectural elements (processing, connectors and data) and the interaction among those elements.  

There are two main applications for design patterns:

### Define a Common platform

Design patterns provide a standard terminology to a specific scenario.

### Best practices

Design patterns have been around since the start of object oriented programming. Less experienced developers learn software design faster and easier by leveraging the best practices documented within a design pattern. Developers should be familar with Programming/Sofware Design Principles.


## Blockchain design patterns

IBM Developer is starting with three design patterns; but we expect the list to grow over time. The context of these design patterns can be applied to end to end applications. Below, is a description of each design pattern:

* [Non Blocking UI design for Blockchain based applications](https://github.ibm.com/BlockchainDesignPattern/BlockchainDevelopmentDesignPatterns/blob/master/docs/design_patterns/UIResponsivenessPattern.md) - This design pattern starts by taking the reader through the problems that plague a traditional user interface when interacting with complex backend APIs with high response times. The design pattern then presents some key concepts/approaches that can be used to alleviate the problem at hand and follows up by providing an end to end architecture and solution overview of how the different solution components can come together to create an interactive user interface.

* [Asynchronous API design for Blockchain based applications](https://github.ibm.com/BlockchainDesignPattern/BlockchainDevelopmentDesignPatterns/blob/master/docs/design_patterns/AsyncAPIPattern.md) - this is a continuation of the non-blocking UI design pattern above.  This pattern dives deeper into the asynchronous backed API and discusses the API design and its interaction with other components such as off chain storage and the events service.

* [Secure sync API Pattern](https://github.ibm.com/BlockchainDesignPattern/BlockchainDevelopmentDesignPatterns/blob/master/docs/design_patterns/SecureSyncPattern.md) - This pattern covers the design of the event service that can be used to securely sync Blockchain with an application’s off chain store. This off chain store can then be leveraged for running functional queries/searches. The event service can also be used as an integration point to setup a data warehouse or provide streaming data as input to a computing framework such as Apache spark for learning and analytics.



## Learn More

*  Learn more about Blockchain at [IBM Developer](https://developer.ibm.com/technologies/blockchain/)

* Learn more about the Blockchain design patterns at [IBM Blockchain Design Patterns](https://github.ibm.com/BlockchainDesignPattern/BlockchainDevelopmentDesignPatterns)
