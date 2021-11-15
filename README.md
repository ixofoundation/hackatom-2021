# HackAtom 2021

Welcome HackAtom Teams! This is a living document to which we will be adding links and instructions that can help with your quest.


Please feel free to start a Github discussion to request more information, or make a PR if you want to add more tips, tools or resources to this repo.

[Slides from the HackAtom Keynote & Workshop](https://app.pitch.com/app/presentation/a9202eb5-e2f5-4345-8c98-307f6ba95e02/39f4ebe0-7c28-410c-9b89-468ad3e3bb3d).

## Support
- Join the HackAtom Discord (TBC) for general discussions and support requests to mentors for the Earth Prize track and related **Earth Tokens** and **Earth Crisis** challenges.
- Join the [ixo Discord](https://discord.gg/4FytdewG8D) where you are welcome to request that we create a private channel for your team, in which you can discuss your project with domain experts and receive more focused support from the ixo team.
- Weekly Challenge Room on Discord - tbc

## Issues and bugs
- General issues may be posted in this repo and will be managed by the ixo team and collaborators through [this Github Project](https://github.com/ixofoundation/hackatom-2021/projects/1)
- Issues and discussions relating to a specific component of the ixo software stack and protocol should please first be posted as discussions in the relevant Github sub-repo.
- You are welcome to contribute fixes, improvements, or new features, by making a PR in the relevant repo. 

## Documentation
We will continue adding to the documentation over the course of the HackAtom month. 

If you feel motivated to improve the documentation across any of the sub-repos, the ixo team will welcome your contributions and send you some IXO tokens for making significant contributions!
### Blockchain SDK 
If you are building a Cosmos Go module, or adding features to an existing module, check out the /x directories in the relevant Github repos for:
* [Core Cosmos SDK modules](https://github.com/cosmos/cosmos-sdk/tree/master/x)
* [ixo Blockchain SDK modules](https://github.com/ixofoundation/ixo-blockchain/tree/master/x)
* Other Cosmos projects - go explore!

Generally, the expected pattern for module documentation is that you will find this in the `/x/{module}/specs` folder for each module.

### Resources

1. [The ixo Foundation Github Repo](https://github.com/ixofoundation) contains code and documentation for all the necessary base software components for the Internet of Impact and related Impact Stack.
2. [ixo Developer Documentation](https://docs.ixo.foundation/ixo/)
3. [Risk-Adjusted Bonding Curves](https://github.com/BlockScience/Risk-Adjusted-Bonding-Curves)
4. [Pandora Testnet](https://testnet.ixo.world)
5. [ixo Web Application UAT](https://app-uat.ixo.world/) instance
6. [ixo Discord community](https://discord.gg/mCJue97UZa) 
7. ixo [Discourse discussion forum](https://forum.ixo.world) 
8. [Developers Slack for HackAtom](https://join.slack.com/share/enQtMjY2ODY2NzYyMDU3Ni0yMmRjNWNjY2U2ZmQyZDg0YmJhYzkzMWYxMzg3MzM2MWNlMjU1MDhkMTk1ZTQ4NTMxNmJlMGQzZTA2NjMyYjA5)
9. [Code with Us](https://www.youtube.com/watch?v=pIpVDJLbKFQ) workshop on the ixo Bonds Module
10. [AI for Good Neural Network](https://aiforgood.itu.int/neural-network/) - connecting problem owners to problem solvers
11. [Interchain Identifiers Specification ](https://w3id.org/earth/identifiers)
12. [Interchain Tokens Specification](https://w3id.org/earth/tokens)
13. [Cosmos SDK Modules](https://docs.cosmos.network/v0.42/building-modules/intro.html)
14. [InterWork Alliance Token Taxonomy Framework](https://github.com/InterWorkAlliance/TokenTaxonomyFramework)
15. [BlockScience Community Currencies](https://github.com/BlockScience/Community_Inclusion_Currencies) 
15. [Peoples Money](https://unsdg.un.org/resources/peoples-money-harnessing-digitalization-finance-sustainable-future) describes the call-to-action from the UN, to create sustainable digital finance ecosystems


## The **Earth Crisis** challenge
Humanity is on the brink of a fundamental state-transition into planetary chaos. Erratic weather patterns and natural disasters resulting from flooding, droughts and wild-fires are becoming more frequent each year, as climate-change accelerates.  Mass human migrations away from disaster zones are already beginning and we see conflicts and famine as the aftermath. Re-emerging tropical diseases and lethal new infectious agents, such as Covid-19, threaten human and animal life. Natural resources are being depleted at an alarming rate, way beyond the planetary boundaries for sustainability, and imperial wars to control and own these resources have already begun! 

What can we do to avoid mass extinctions of life-forms on Earth and to reverse the threat of losing centuries of human progress?

With the ixo Internet of Impact, we believe that solutions can crafted on the Cosmos blockchain to address these problems, with early and scalable sensing and response mechanisms that enable us to gather intelligence, flow resources to where these are needed, coordinate action, and verify changes in the state of the Earth. ixo describes this multi-chain Internet of Impact as a global digital immune system for humanity.

We invite you to join this Hackatom challenge, to build and demonstrate applications using the Internet of Impact, or software components that add capabilities to The Impact Stack, for preventing and responding to specific types of real-world Earth Crisis events. 

You will collaborate with Problem-owners who have place-based or domain-specific knowledge and expertise about use cases that may range from making earth state observations for early-warning systems, to financing earth state-changes, to enable local citizen action, and to create global change. 

This is an enormous, urgent opportunity space of the highest priority, in which to apply your skills, connect and interoperate with existing systems, integrate the latest AI technologies, and build better alternative decentralised financing and data verification mechanisms.
### Requirements for the **Earth Crisis** Challenge
1. **Connect your solution to a specific real-world use-case** that is ideally built in collaboration with a problem-owner who understands an Earth Crisis events domain. For instance, The Red Cross International Disaster Bonds insurance mechanism for rapidly delivering relief financing to communities threatened by natural disasters. The Earth Crisis problem space is rich with opportunities, so we look forward to seeing really interesting use cases that address real needs.  
2. **Build your solution on the Internet of Impact** using the ixo-Blockchain SDK. The blockchain base layer can either use the current Go modules and capabilities implemented in the ixo Pandora-4 Testnet (which has the same configuration as the ImpactHub-3 main-net), or you can build and configure new chains that include base ixo-Blockchain modules, with additional modules imported from the Cosmos SDK, or other projects. You may even decide to build your own custom module/s, using the Cosmos SDK framework, or implement smart contracts –for instance using the Cosmwasm module.  
3. **Create entities with specific roles and capabilities** in your solution, using ixo Decentralised Identifiers (DIDs) and combinations of the following entity types:
    * **Agents** that are Individuals or groups with Self-sovereign Digital Identity.
    * **Projects** for managing agents to finance, deliver, claim and verify pre-defined results. 
    * **Investments** for forming and distributing capital assets to invest into other entities, using sustainable DeFi mechanisms, such as ixo Alphabonds.
    * **Oracles** that provide trusted information from the real-world, or offer prediction services for proofing and verifying claims, personalising services, prescribing interventions, preventing risks, protecting against threats, and enabling more effective human participation in decision-making. 
    * **Assets** that are tokenized using Interchain Identifiers, to represent any digital asset types such as tokenized Carbon Credits or other classes of Impact Tokens, tokenized titles and rights over physical assets, tokenized data assets, etc.
    * **Templates** that encode the claims and data models for the Internet of Impact Linked-data Graph, which enable users to quickly configure new entities from template libraries.
    * **Cells** for coordinating groups of agents with a shared purpose, including through DAOs mechanisms.
4. **Provide a compelling user interface** to demonstrate from the target user’s perspective how the solution works to meet their needs. Using personas and user journey maps would be helpful in your presentation of the solution. You can build your interface using the ixo-Webclient (React, Typescript), with the option to add new features and systems integrations into the current version of the web-client. Alternatively, you can build entirely new client applications, using the ixo-Client SDK and javascript libraries. For instance, an IoT device client that feeds information into the  integrating IoT devices with the ixo system.
5. **Consider building service integrations** that extend the capabilities of the Internet of Impact to receive information and services from other Web3 or Web 2.0 networks, and/or to provide information and services into other networks.

### Who should join the Earth Crisis Challenge?
* **Builders** including frontend software developers, blockchain engineers, AI engineers and data scientists, token economics experts, systems engineers, UI/UX designers, etc...
* **Earth Crisis Problem Owners** including Social and commercial enterprises, non-profits and civic organisations, activists, impact investors, philanthropists, government agencies, etc...

## The **Earth Tokens** Challenge
For this challenge “Earth Tokens” are defined as classes of tokens that are created and used for the purpose of sustainable socio-economic development, climate action, and ecological regeneration.

Tokenization is transforming how people are incentivised, how decentralised economies and communities are secured and governed, how capital gets formed and allocated, how products and services are financed, and how digital or physical assets are used for financial or non-financial applications. 
Across this wide range of applications there are many different classes of tokens. 
Each token class has a unique set of token properties and token behaviours.
The Interchain Identifier (IID) Specification describes how to configure various classes of tokens, using token templates and standards that are designed to be interoperable across all blockchain networks, and addressable from the web.
Consider these 3 use-cases as examples of how different classes of Earth Tokens could be configured,:
* **Community Currency Tokens** enable people to exchange their time, goods and services to grow a local economy. Among many other configurations, a token issuer may define this as a class of fungible, fixed-supply tokens that can only be transacted between identified accounts with verifiable credentials.
* **Mutual credit Tokens** enable small businesses to transact with less reliance on external capital / markets. This token class may have many of the characteristics of non-fungible tokens, when these are linked to verifiable claims about the provenance of goods produced–for instance, in sustainable supply-chains, or if these tokens accord the holder an automated right to be paid for invoices when orders are delivered.
* **Renewable Energy Tokens** enable independent power producers to sell certified green electricity, or to claim Carbon Credits that can be sold as offsets. Non-fungible Renewable Energy Certificate (REC) tokens may include the right for a token-holder to mint fungible fractional units of the REC tokens, to trade for electricity supply.

These examples only begin to demonstrate the incredible potential for configuring classes of tokens for different Earth Token use-cases. For this challenge you will build and demonstrate innovative ways for Earth Tokens to be issued, traded and used in Sustainable DeFi and Regenerative Finance (ReFi) applications. 
Suggested areas for innovation include (but are not limited to):
* Great UX for creating and using Token Templates to mint and issue different classes of Earth Tokens.
* Decentralised marketplace mechanisms for trading different classes of Earth Tokens. This may include new types of services that enable tokens of different classes to be bought or sold, auctioned, used as collateral, lent or borrowed, used as offsets, etc. 
* Automated market-makers for trading homogenous and/or heterogeneous token classes, such as a liquidity mechanism for pooling fungible with non-fungible token classes.
* Authorisation Capabilities (zCaps) to provide secure delegated authorisation mechanisms for interacting with token services.
* Clever ways of using Liquid Staking or other token derivatives, to unlock capital for sustainable development and ecological regeneration.
* Software tooling or integrations that further enable Earth Token use-cases. 

### Requirements for the Earth Tokens challenge
1. Address a real-world need that is relevant to the Interchain Earth Mission, based on a real or fictitious use-case that has a great user story.
2. Implement the Interchain Identifiers (IID) specification and Token Templates.
3. Use the standard Cosmos SDK modules, and/or add new features to existing Cosmos modules, and/or create new module/s.
4. (Optionally) build on the ixo-Webclient, with the possibility of adding new features and/or integrations. 
5. (Optionally) contribute new software tooling for implementers of Earth Token applications.

