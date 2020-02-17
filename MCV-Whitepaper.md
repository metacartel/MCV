![](https://lh6.googleusercontent.com/dewpC5CzM1_doEq8aEU7aqf-hU46c_ywnmdYQgNEZUkNikTWhKC23DbghudPsfunpeDBS9P7NmdM5Ir5v-5se1nB4aBQFz58iNhEAZiXuWEqqfoPOoNC56Dd1ES-tC-W8HMe7wQp)

MetaCartel Ventures

Gabriel Shapiro, Peter 'pet3rpan', Ameen Soleimani

v1.0 DECEMBER 2019

______

[NOTE: This document is subject to important legal and informational disclaimers provided at the end of this document. Please carefully review such disclaimers and bear them in mind when interpreting this document. MCV's arrangements are under continuing negotiation, study and refinement. MCV may, but will not be required to and does not promise to update this document based on subsequent developments.]

*Big shout out to James Waugh, Cooper Turley, Eva Beylin, Drew Harding, Garrett MacDonald, James Young and Alex Masmej for editing and adding to the paper
==========================================================================================================================================================

Preface
=======

A distributed autonomous organisation (DAO) is a cryptonative and remote-first way for people to coordinate funding, labor, time and social capital. The governance of DAOs is distributed, with all funds and assets managed on-chain via smart contracts. There's no board of directors, nor is there central control of the organisation. DAOs coordinate components of the soft human-facing layer of crypto: money, social capital, reputation and attention; they give power to individuals upon crowd consensus, and are inherently a political tool.

In 2016, 'The DAO' was created. It was one of Ethereum's first major decentralized applications and also marked the first time the Ethereum community attempted to coordinate through a DAO. While it never was able to operate at scale, it has captured the minds of an entire generation. After the DAO hack, projects such as Aragon and DAOStack continued their efforts in bringing DAOs to the world. These projects carried the torch and made sure DAOs stayed relevant and top of mind within the Ethereum community. 

More recently in early 2019, we have seen Moloch DAO sparking a new wave of widespread interest into DAOs, leading to forks such as MetaCartel DAO (R&D), Yang DAO (political campaigns), Orochi DAO (events sponsorship), The LAO (legal DAOs) and Marketing DAO. From the very beginning, the Ethereum's community ethos has driven compatibility and interested around DAOs. Just like how the open publication of Whitfield Diffie, Martin Hellman and Ralph Merkle's work around public key cryptography in 1976 brought an entire area of research into the public light, sparking the imagination of an entire generation---we will likely see the spirit and philosophy of 'The DAO' and Moloch ripple forward for decades to come. MetaCartel stands on the shoulders of giants and finds itself honored to be part of the contributing frontier of Web 3.

Acknowledgements

Thank you to those who have backed the MetaCartel community, from the old to the new, from the MetaCartel DAO members to the community members in our telegram chats, it is only because of you and the community that we are able to do what we do. Thank you to those work have put in significant driving efforts behind the project, including Ameen Soleimani for leading the efforts on the Moloch v2 smart contracts, Gabriel Shapiro for masterminding the legal innovations, Ross Campbell for his advisory role as shadow counsel, Q for designs, James Duncan for scouting ahead and also to James Waugh, Cooper Turley, Eva Beylin, Drew Harding, Garrett MacDonald, James Young and Alex Masmej for your contributions.

You have all made this possible.

"If you want to go fast, go alone. If you want to go far, go together."

Context
=======

The MetaCartel community started during the [September of 2018](https://www.metacartel.org/folklore) as a technical working group around meta transaction technologies, a solution that allows users to interact with decentralized applications on the Ethereum Blockchain without the need to own Ether. This working group consisted of participants from a range of projects including Universal Logins, Gnosis, Status.im, ChronoLogic, SpankChain, Shipl, ENS,  Argent, and ETHWorks --- all of which, coordinated together through online video calls and offline workshops to standardise technical specifications and solve cryptoeconomic research problems surrounding meta transactions ([Github: Harbour MVP](https://github.com/metacartel/Harbour-MVP/issues)). In late 2018, TabooKey make a key research breakthrough to the relay collision problem ([EIP-1613](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1613.md#attacks-and-mitigations)). MetaCartel's community then came together to build the [Gas Station Network](https://gasstation.network/), a decentralized network of gas relay nodes. This project later spun out from the community as the Gas Station Network Alliance.

As this spin-out happened in early 2019, MetaCartel evolved into a community focused around driving UX innovations and discovering new crypto use-cases on the Ethereum application layer. During February and March of 2019, the community worked on plans of launching of a DApp incubator. In early April, these plans transformed into the idea of MetaCartel DAO and would become known as the first fork of Moloch DAO. It's purpose was to setup an ecosystem grant fund that would drive experimentation around crypto use cases and cryptonative business models. 

MetaCartel DAO's smart contracts were deployed to the Ethereum mainnet on the 5th of June with initial backers including Matic Network, NuCypher, SpankChain, Gnosis, AdEx, The Graph, Abridged, Odyssey and Giveth, along with 10+ other individual contributors. From the start of the DAO in July, the DAO has since raised over 1,100+ ETH and deployed $44,450  to over 13 projects, with experiments including [NFT conference ticketing](https://forum.metacartel.org/t/1-funded-dao-proposal-metacarel-demo-day-tickets/36), [DAO reputation systems](https://forum.metacartel.org/t/9-funded-dao-proposal-metacartel-member-cards-cartel-cards/134), [DeFi based business models for DApps](https://forum.metacartel.org/t/15-pending-dao-proposal-rdai-new-interest-based-business-models-for-dapp/200), and [DAOs for coordinating meatspace events](https://forum.metacartel.org/t/orochidao-devcon5-new-event-idea-format/147). With now over 60+ DAO participants, and over 800+ community members, we are taking what we have learned from launching DApp experiments and DAOs to launch MetaCartel Ventures. Incubated by the SpankHouse, MetaCartel Ventures aims to be a project that aims to deepen MetaCartel's existing commitment to furthering the progress within the Ethereum DApp ecosystem and Web 3.

In this paper, we explore the concept of MetaCartel Ventures, a for-profit investment DAO coupled with a legal entity. This is MetaCartel's very own unique brew of cryptoanarchy.

NOTE: This document is subject to important legal and informational disclaimers provided at the end of this document. Please carefully review such disclaimers and bear them in mind when interpreting this document. MCV's arrangements are under continuing negotiation, study and refinement. MCV may, but will not be required to and does not promise to update this document based on subsequent developments.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Introduction
============

​​MetaCartel Ventures (MCV) is a for-profit DAO created by the MetaCartel community for the purposes of making investments into early-stage Decentralized Applications (DApps). It embodies a community-oriented membership structure and offers radical participation as well as flexibility that is unparalleled by traditional "venture capital fund" models.

The members of the DAO are the designated investors of the DAO: they will be the ones sourcing, diligencing,  proposing, and voting on investments. The admission of new members is permissioned and member-curated, while the ability to exit the DAO is completely permissionless, allowing exiting members to receive their full pro rata share of the DAO's assets at any time. The initial members of MCV will consist of trusted Ethereum community founders, builders, investors, and existing participants of the MetaCartel community.

MCV is made up of a code and law pairing, where the DAO's business entity is tightly coupled with its smart contracts and token technology deployed on the Ethereum mainnet. The technology half of MCV will consist of an instance of the [Moloch v2 smart contract standard](https://github.com/MolochVentures/moloch) and the legal half consisting a member-managed Delaware limited liability company governed primarily by the Grimoire (the "Limited Liability Company Agreement") and the statutes of the Delaware Limited Liability Company Act. The general philosophy behind this pairing of blockchain technology with law to augment organisations can be found in further detail in the [Zerolaw Augmentation Paper](https://github.com/zerolawtech/ZAP-Tech/blob/master/docs/papers-and-research/ZAP-Whitepaper.md).

Why use a DAO?
--------------

We are fascinated by DAOs as a community, yet our understanding is in constant flux. With an uncertain future ahead with DAOs, the only way we will discover it is by plunging headfirst into the chaos. The narrative of MetaCartel Ventures will be shaped by those who join it. Those who join should expect this project to be highly experimental. MetaCartel Ventures is organised and coordinated as a DAO as opposed to a traditional hierarchical organizational structure for a range of reasons including:

-   Diverse due diligence: MCV will be able to conduct product and technical due diligence by leveraging the DAO members' varying areas of expertise to provide unique and exclusive insight to investment opportunities (dApp builders, founders and investors).

-   Distributed decision making: MCV's membership, investment decisions and assets are managed by its members. This contrasts starkly with traditional VC funds, in which passive, non-expert limited partner investors, rarely consult with the small cadre of experts who direct investments on behalf of the firm.

-   Incentivised aggregation of deal flow: MCV's members will be aligned to contribute exclusive deal flow, resources, and insights to help guide the DAO's investments. The DAO's ability to align a greater cross section of the Ethereum ecosystem will allow MCV to drive deals from the fringes of the industry, effectively scaling exposure to early investment opportunities.

-   Low participation risk: Each of MCV's members are able to leave the DAO at anytime with their pro rata share of the DAO's assets through the RageQuit functionality. This enables membership dynamics that protects members from governance capture by an adverse majority and obviates traditional legal models for minority protection such as fiduciary duties.

Trade-offs
----------

In light of these advantages, it's important to recognize that they do come with their own set of trade-offs, including:

-   Asset management: MCV cannot be managed like a traditional hedge fund or venture capital firm as members are able to leave the DAO anytime with their economic interests. Typical firms have lockup and redemption periods, MCV does not.

-   Majority based decision making: Due to MCV's majority based decision making and ever present possibility of membership RageQuit, it will be difficult to pass controversial proposals that contradict wider consensus.

MetaCartel's positioning
------------------------

MetaCartel's community has been around since the September of 2018 and has since drawn infamy through its memes. Our community is made up of over 800+ builders, founders and creators, has since helped launch several DAOs and is in a unique position to facilitate MCV.

Community

Since inception, MetaCartel has emphasized the importance of community and has spent significant  effort on community building, content creation and ecosystem knowledge sharing. Since its inception, it has:

-   Held over 30+ online virtual community calls around technical research problems, working group agendas and development topics.

-   Held over 20+ offline meetups all around the world across most of Ethereum's major community conferences in cities such as: SF, Berlin, Prague, Denver, Paris, NYC, Osaka.

-   Recorded and hosted over 26+ weekly podcast episodes with the creator of DApps\
    (Wizard of DApps), including the release of over weekly 30+ newsletter editions. 

-   Held its first Demo Day conference during Berlin Blockchain Week 2019 focused exclusively on DApps, which over 200 of its community members attended.

With its position unparalleled in the crypto space, it attracts some of the best developers, product people and early stage projects to its community.

Grants DAO

In July 2019, the MetaCartel launched the Ethereum community's first ever DApp focused grant program focused on funding and supporting the launch of minimum viable DApps and furthering experimentation of new crypto use-cases and cryptonative business models. It has since:

-   Provided grant funding and support to over 13 projects, that range from: NFT conference ticketing (Mintbase), DAO Infrastructure (PocketMoloch, DAOHaus), DAO reputation systems (Pepper4D), DeFi based business models (rDAI), Smart contract automation (Gelato Finance), and Events sponsorship coordination DAOs (Orochi DAO)

-   The operators of MetaCartel provides assistance and support alongside grants to projects in sourcing initial pilots opportunities as well as  initial customers and partners.

With its current efforts to support such projects, MetaCartel Ventures is in a unique vantage point to identify as well as attract high potential investment opportunities at the earliest stages.

"Start by doing what's necessary; then do what's possible; and suddenly you are doing the impossible"\
---Francis of Assisi

Market Opportunities
====================

While the members of the DAO will be deciding MCV's activities on an ongoing, dynamic basis, the initial mission of MetaCartel Ventures is oriented around the application layer of Ethereum, undeniably the leading smart contract ecosystem.

Early signs of product market fit with Ethereum DApps
-----------------------------------------------------

-   Defi Protocols---In 2019, DeFi experienced initial signs of product fit when locked participating value in DeFi grew from $160 Million USD to over $650M+ from Dec '18 to '19. A third of this growth was driven by Compound, which grew in TVL from [$100k to $125M from Oct'18-19](https://defipulse.com/compound)

-   Defi Interfaces---Interface products that aggregated user friendly access to composable DeFi DApps and tokenized systems are experiencing meaningful traction eg. InstaDApp, which facilitated over [$44M of migrations](https://www.decentralised.co/in-numbers-instadapp/) from the MakerDAO to Compound during a single quarter

-   Tokenized Marketplaces---Tokenized marketplaces are beginning to prove successful in bootstrapping supply markets, with examples being Nexus Mutual, a smart contract insurance market that launched in May of 2019. Since then, the protocol was able to secure over [10,000 ETH](https://defipulse.com/nexus-mutual) through its bonding curve, and now covers over $700,000 USD worth of insured smart contracts

-   NFT Marketplaces---Web 3 gaming products are also finding traction with NFT marketplaces such as OpenSea generating upwards of [$1.8M in monthly marketplace sales](https://opensea.io/blog/announcements/bringing-on-additional-strategic-investors-to-opensea/). 

-   Cryptonative Games---Gods Unchained generated over over [$6.2 Million USD in revenue](https://coinmetrics.substack.com/p/coin-metrics-state-of-the-network-44c) from trading card pack sales in the last 18 months, and managed to scale well beyond the magnitude of Crypto-kitties, where more recently the game's NFT transactions exceeded all Ethereum mainnet ERC-20 token transfers.

-   New Gaming Business Models---Many other crypto games are following this business model, and are successfully generating pre-game sales ranging from $15,000 to over $88,000 USD. Social NFT art platforms such as [KnownOrigin](https://knownorigin.io/) are generating a consistent $4,000-$5,000 MRR and similar products such as SuperRare are beginning to facilitate over [$15,000 USD worth of purchases at a 10%+ MoM](https://superrare.co/) increase in total marketplace growth.

Predictions

MetaCartel believes that this growth will only increase from here on out, with such opportunities being unique and native to Ethereum's application layer. As more projects penetrate viable markets, make business model breakthroughs, and discover UX innovations, we believe the Ethereum application layer will prove to become the leading venture ecosystem to focus on.

An immature, yet rapidly growing venture environment
----------------------------------------------------

-   In the last three months of Q4 2019, $11+M in early stage capital was deployed into key areas of DeFi and crypto gaming, with notable examples including: 

-   Zerion's [$2M Seed (Dec '19)](https://blog.zerion.io/zerion-raises-2m-to-fuel-next-phase-of-defi-edee2e030ca2) 

-   Axie Infinity [$1.5M Seed Round (Nov '19)](https://medium.com/axie-infinity/sky-mavis-raises-1-5m-to-accelerate-the-development-of-axie-infinity-d43bb95f4985)

-   OpenSea [$2.1 Round (Nov '19)](https://opensea.io/blog/announcements/bringing-on-additional-strategic-investors-to-opensea/)

-   InstaDApp's [$2.4M Seed (Oct '19)](https://medium.com/instadapp/seed-round-503b689fc71c)

-   Nuo Network's [$3M Raise for new Juno product (Oct '19).](https://messari.io/article/nuo-protocol-founders-raise-3-million-to-launch-a-new-ethereum-based-banking-platform)

-   Despite increasing flow of capital, crypto investors still lack data around early stage investments in DApps and tokenized systems, with projects severely hindered by long development cycles and the necessary legal advisory required to launch both token systems and DApps.

Predictions

MetaCartel believes that the builders of DApps and Web 3 projects in the Ethereum ecosystem have greater information asymmetry and relevant operational insight on early stage investment opportunities. If paired with with relevant investing experience, we will be able to identify high value early opportunities that other investors are oblivious to.

New Experiments in Hypercapitalism
----------------------------------

-   DApps are enabling an increasing amount of high upside cryptonative experimentals that the DAO would be able to partake in. As cryptonatives, we are the best positioned group to facilitate, encourage these experiments as well as make returns from them, including: 

-   Making OTC trades for unlisted assets

-   Investing in managed trading funds such as BeToken and Melonport funds

-   Sponsoring teams to play crypto games (eg. Cheeze Wizards prize was 100k USD)

-   Investing in digital assets (eg. Unisocks and digital artworks)

-   Buying ISA (income-sharing agreements) & personal time tokens of individuals 

-   Investing in communities and providing seed capital to DAOs

Predictions

MetaCartel believes that we will likely see another highly profitable cryptonative asset class emerge.

"The next big thing will likely start out looking like a toy." --- Chris Dixon

The Grimoire
============

MetaCartel Ventures (MCV) will be a Delaware Limited Liability Company (LLC) that consists of two key legal components:

-   The DAO's "Grimoire", a Limited Liability Company Agreement, that constitutes a voluntary, legally binding agreement among the members of the DAO

-   The Delaware Limited Liability Company Act, which is a statute (set of laws) determining the default governance rules and meta-rules for LLCs formed in Delaware. 

The Grimoire constitutes a pact among MCV's members. Meanwhile, the Delaware Limited Liability Company Act prescribes meta-rules about how that pact should be written and interpreted. 

Through the LLC, MCV will be able to enter into legal contracts and engage in investment opportunities without the risk of individual personal liability beyond the capital in the DAO. It will also allow registered legal entities to participate in the DAO's membership as well as the issuance of securities to the DAO.

Unlike the Limited Liability Company Aggreement of a typical LLC, the Grimoire enables MCV's governance to be tightly coupled with a unique deployment of Moloch DAO v2 smart contracts. Thus, when a person follows the on-chain procedures for acquiring DAO shares from MCV's smart contracts (specifically, Moloch.sol), the person will also legally become a member of MCV, with rights and obligations determined by the terms of the Grimoire and the Delaware Limited Liability Company Act.

IMPORTANT: This paper's summary of the Grimoire, the Delaware LLC Act and any other laws referenced in this paper is not intended to be complete and may become inaccurate based on subsequent developments. The summary is qualified in its entirety by the actual contents of the Grimoire and the LLC Act. To the extent that the summaries contained herein conflict with the terms of the Grimoire or the LLC Act, the terms of those writings will control and be determinative as to the outcome of the relevant issues, not the contents of this paper. Please review the disclaimers at the back of this paper and bear them in mind when reviewing the summaries set forth herein. 

The goals of the Grimoire
-------------------------

MCV's goal is to facilitate a DAO with a focus on open participation where its members are enabled to have radical level of flexibility in their continued involvement, all while having a right to participate in the management of the DAO (investment decisions, asset management, membership admissions). These goals are naturally in tension: If MCV becomes  too open too quickly, the community runs a high risk of either lapsing into a traditional leader/follower org structure or fragmenting into dysfunctional cliques. If MCV is too rigid, it will miss critical opportunities to build the community. MCV will carefully consider all such social, legal and technical factors to enable a continuous, dynamic readjustment of this delicate balance. 

Community Governance from a Social Perspective
----------------------------------------------

Although MCV's fundraising and asset management will happen on-chain, many of its decisions will be coordinated through social consensus, using "off-chain" communication channels such as group chats, video meetings, and in-person meetings. These interactions help the members develop and evaluate ideas, initiatives and values together long before they are submitted as formal proposals to a vote of the members. In the cypherpunk tradition that shaped maxims such as "don't trust, verify," the culture of this DAO is one of personal responsibility. Every DAO member will be expected to take an active community role in remaining fully informed about the DAO's developments and progress. 

As such, all DAO members are recognised as managing members of the LLC  and will have full economic, informational and governance rights in the LLC. Within the DAO, there are three main recognised categories of membership,  which a DAO member may fall in and out of depending on the member's level of activity at a given time:

Mages

Mages are DAO members that are considered to be actively participating in the members' shared management efforts, including activities such as sourcing investment opportunities, conducting deal due diligence and managing the DAO's assets. DAO members that are not "accredited investors" under applicable securities laws must participate as Mages and should be promptly expelled from the DAO (see "Member expulsion" below) if their level of participation falls below their expected managerial responsibilities. You can think of Mages as the ones who actively study the laws of Magick and practice their knowledge in the battlefields alongside their melee and ranged based comrades, weaving in and out, casting powerful spells and providing strategic advice to field commanders.

Goblins

Goblins are DAO members that may choose not to exercise such rights and powers to the same extent as Mages do, despite legally having all the same managerial rights and powers under the Grimoire. Although Goblins may still be expelled from the DAO at any time, there is no expectation that Goblins will be expelled for inactivity and lack of participation. For legal reasons, Goblins must be deemed as  ("accredited investors"). These Goblins, despite holding a passive role in the DAO, can also become Mages if they choose, and may go from a Goblin-Mage to a pure Goblin. You can think of Goblins as having the right to hide away in their moldy dens, hoarding their gold, deciding to live within the shadows. But, at any time, they may get restless for knowledge, study the laws of magick and don the Mage's gowns to work their will upon the world.

Summoners

Summoning team members are operational delegates responsible for performing legal, financial and coordination-related tasks which are approved, directed and supervised by Mages. Delegates can be, but not need not be members. Summoners' tasks may include but are not limited to:

-   Coordination

-   Making sure all other DAO members are aware of proposals

-   Making sure the standard of participation is enforced

-   Initiating or encouraging guildKick proposals regarding members that fall below minimum participation

-   Managing bailouts in the event of an exiting member who suffers 'stuck funds'

-   Managing notice mechanism to ensure DAO members are notified about pending proposal votes in time to participate

-   Entering into approved legal contracts representing the the DAO

-   Taking approved actions with respect to off-chain funds/assets of the DAO

-   Recruiting service providers such as outside accountants, lawyers, etc.

-   Coordinating the DAO's public relations

-   Taking actions to register DAO's off-chain property, if any 

The summoning team are incentivised to participate with fees to be negotiated and determined by the initial founding DAO members at the start of the DAO and with future services to be paid out of the DAO's payment tokens (eg. cash equivalents) to avoid accruing any long term liabilities. You can think of the summoning team as a chaotic neutral group of mercenaries and pirates who fight for gold and glory, hunt for bounties and go on long ranging raid parties to take down the occasional dragon. They aid the Mages of the DAO and provide additional operating support.

![](https://lh5.googleusercontent.com/DiOrYnONv-i7audHWOjefPfNa2OrZcHZTsdMc9P5sLhEpc-6ZUfvZukSP7aKa92jE_qjlCzU5wrBLS6CxePEgNStL5jldbrpiVICztC4SwgazJpPJ9FpvlK03YzYpApJXbhQHt4u)

Community Governance from a Technological Perspective
-----------------------------------------------------

The Moloch DAO v2 smart contract standard is inherently well suited to facilitate MCV's community governance goals by virtue of several features: 

_**Membership is Permissioned**_

-   _Membership Admission is Permissioned_: Membership for MCV is a permissioned processes which reflects the wisdom of MCV's existing membership. Before new membership proposals are submitted on-chain and voted on, candidates must first be championed by an existing member of MCV and undergo internal member-driven evaluation where various aspects of their membership are considered: culture fit, expertise, legal viability, etc...

-   _Continuing Membership is Permissioned and Community-Policed_: For a person to continue being a member of MCV, that person must implicitly have the consent of an economic majority of MCV members. Any member may at any time propose that another member be expelled from the DAO, and if that proposal is approved by sufficient other members, the person will lose their MCV shares and governance rights while receiving (through one of the mechanisms as described under "Exiting Members" below) payment tokens and claims tokens representing the percentage of MCV's property to which the member is entitled under the Grimoire.

Membership shares, although they can potentially be viewed as "tokens" in a loose sense (because they are intangibles with balances tracked on Ethereum), are non-transferable. The Grimoire also prohibits sharing of private keys of the address that "owns" MCV shares on Ethereum, except in the event of a change in ownership by operation of law, such as when a member dies or, if the shares are community property in a marriage, upon a divorce. 

**Membership Resignation/Reduction is Permissionless**

Moloch DAO v2 smart contracts embodies the cypherpunk design principle of "opt-in" and self-sovereign choice, and thus exit from the DAO has been made as easy, trustless and economically riskless as possible. Hence, each MCV is member is able to RageQuit at any time with respect to all or any portion of the member's shares and receive payment tokens and claims tokens representing the percentage of MCV's property to which the member is entitled under the Grimoire by virtue of the number of shares the member holds in the DAO.

Community Governance from a Legal Perspective
---------------------------------------------

MCV's focus on community governance, combined with its mission of investing in the Ethereum ecosystem on a for-profit basis, has led to a number of legal structuring choices. The highlights of these choices are summarized below. 

**Grimoire - Qualified Code Deference Approach**

In general, the Grimoire is informed by a belief that traditional legal mechanisms for handling governance issues can be substantially augmented, streamlined and/or eliminated by leveraging blockchain technology that has been designed to minimize transaction costs and execution risks, such as the MolochDAO smart contract system. Many past DAO projects, touting the principle of "code is law", have abandoned legal structuring altogether and sought to defer all legal results to the operation of software. This approach has been described as "absolute code deference." 

We believe it is more appropriate to continue to utilize legal structures, but to modify them to defer to the outcome of operating software--or refer out to data structures and events that are used in or generated by that software--when appropriate. This approach has been described as "qualified code deference."

For example, traditional organizations typically struggle with how to provide members with a "fair exit". Many LLC agreements provide that, when a member exits the organization, that member is entitled to be paid the "fair market value" of the member's membership interests--in many ways, it is as if the LLC is repurchasing the membership interests and needs to establish a fair price.

However,  "fair market value" is a "fuzzy logic" concept in many contexts. To use blockchain lingo, there is no market-based "price feed" or "price oracle" we can use to accurately price the value of an illiquid membership interest in a privately held company in realtime. 

Traditionally, this issue is often dealt with by including in the Limited Liability Company Agreement or other applicable contract extensive notification, negotiation and arbitration procedures and appraisal standards for determining what "fair market value" means. These provisions will potentially be ambiguous and thus could lead to disputes, requiring a exiting member to be tied up in legal procedures and potentially even court battles for long periods before getting paid. 

In contrast, due to the flexibility and freedoms provided through Moloch DAO v2 smart contracts, such complex and litigation-prone contractual mechanisms are not necessary to ensure that members receive fair exit terms. Instead, an exiting member of MCV can immediately and trustlessly receive tokens representing the member's entire pro rata interest in each of the DAO's individual assets at the time of exit. See below under "Grimoire - Resignation and Expulsion of Members" and "Asset Management - Exiting Members" for more on the legal and technological details of this process. 

Below we will see some other examples of how qualified code deference and the other features of MCV play out in theory and practice. Readers who wish to appreciate the full details should review the full Grimoire once it is published. 

**Grimoire - Overview of Membership Rights**

Both Mages and Goblins are able to do all of the following by  permissionlessly calling functions on MCV's Moloch.sol smart contract:

-   submit DAO Proposals;

-   vote on DAO Proposals; and/or 

-   rageQuit to burn some or all of their DAO shares and receive their corresponding percentage interest in each of the DAO's assets (see below under "Grimoire - Resignation and Expulsion of Members").

Additionally, each member will have the full rights of a "managing member" provided for under the Grimoire and/or the Delaware LLC Act, including being entitled to know the identity of all other members, receive all information about the LLC's activities and participate in the LLC's management, planning, decision-making and day-to-day operations. 

**Grimoire - Voting Standards**

Proposals are of two types: ordinary and extraordinary. 

-   Ordinary: Ordinary proposals include membership admission, membership expulsion, proposed payments to service providers, and proposed investments in other projects. Ordinary proposals are handled entirely on-chain through MCV's Moloch.sol smart contract. They must be sponsored by an existing member, but may be proposed by anyone through Moloch.sol. The outcome of ordinary proposals is decided by a majority of the votes cast on the proposal, with no quorum requirement. See below under "Asset Management - Proposal Types" for a more in-depth discussion of ordinary proposal types.

-   Extraordinary: Extraordinary proposals pertain to MCV's meta-rules and cannot be handled purely on-chain. If such a proposal is made on-chain and approved without the requisite legal formalities, it will be invalid and will not be honored, and the members responsible should be expelled. Extraordinary proposals require approval by 69% of MCV's then-current shares. Examples of extraordinary proposals include any proposal to amend the Grimoire in any material respect (aside from specified exceptions), sell more than 50% of MCV's investment assets to a third party, merge MCV as an LLC with or into another business entity, acquire a majority of the assets or securities of another business entity / organization or commence or participate in any legal proceeding.

**Grimoire - Admission of Members**

Admission of members under the Grimoire strongly ties into the on-chain mechanics of the MolochDAO implementation. Once a membership proposal for an individual is approved on-chain, the individual will become a DAO member and receive the proposed number of shares from Moloch.sol. Each DAO share represents a percentage membership interest in the LLC. Potential members will also be asked to complete certain legal formalities either in advance of the proposal or after it is approved, including electronically signing the Grimoire or a Joinder Agreement, and should be expelled if they fail to comply.

Note: technically it is possible under MolochDAO v2 for shares to represent a different voting percentage than they do an economic percentage. Pure economic interests are referred to as "loot". For legal and operational simplicity and predictability, the initial version of MCV will not utilize this capability, but it may be added later by amending the Grimoire upon approval of the members. 

**Grimoire - Resignation and Expulsion of Members**

Members may resign from the DAO at any time by RageQuitting or may also be expelled if a membership proposal known as a GuildKick is approved by the members. In both cases, the relevant functions are called through the Ethereum blockchain and trigger an on-chain distribution of tokens from the DAO's GuildBank smart contract to the member's recorded Ethereum address. These tokens represent the exiting member's percentage interest in MCV's assets.

In the typical case, the exiting member will receive a mix of: 

-   "RageTokens": Freely trading payment tokens such as ETH and DAI; and

-   "RageClaims": Non-transferable, personal, economic tokens that represents the exiting DAO member's remaining economic pro rata claim to the DAO's future income from the revenue-generating assets the DAO holds at the time of the member's exit.

The Grimoire provides that the members all agree that the RageTokens and RageClaim represent the fair market value of an exiting member's membership interest in MCV, and that no exiting member may contest that value under any circumstances.

To give a simplified example, a member holding 5% of the LLC's membership interests can leave at any time and give up all governance rights but receive 5% of the LLC's cash and cash equivalents at the time of exit, alongside a continuing right to collect 5% of any profits from the LLC's then-current revenue-generating assets. 

This is very similar to how traditional LLCs normally handle a member's unexpected death: the deceased member's interests in the DAO are converted into a pure, non-transferable economic interest with no other membership or governance rights, but which may be inherited by the member's heirs without fear of disrupting the LLC's governance.

**Grimoire - Obligations of Mages**

DAO members who do not meet the definition of "accredited investor" under applicable securities laws are obligated to have relevant managerial expertise and maintain a robust managerial role within MCV at all relevant times. MCV describes members who actively participate in management as "Mages". These DAO members fully utilize their maangerial rights and thus act as a 'general partner' of the other Mages. They are participating in the DAO as a means of collaboration and co-managing the DAO's assets with other Mages as opposed to seeking passive financial returns. The roles of Mages may include some but not necessarily all of the following activities, including:

-   Participation in the DAO's telegram group chat other communication channels with relevant and meaningful engagements.

-   Careful evaluation, discussion and voting on all substantially material DAO proposals, with a minimum of one vote per month. 

-   Appearance in person or electronically once a year with all other Mages

-   Actively participating to help support or champion meaningful DAO initiatives:

-   Conducting technical due diligence with projects

-   Interviewing potential investment opportunities

-   Sharing insights and provide analysis around investment opportunities

-   Coordinating with other members, champion and support investment opportunities

-   Helping to admit and champion a new valuable DAO member into the DAO

-   Helping to organise or sponsor a worthwhile event or service for DAO members or it's adjacent activities

-   Providing other DAO members opportunities for networking and introductions to specific investment opportunities (but without acting as broker/dealers or investment advisors unless so licensed) 

The DAO will implement a reputation system to track and evaluate each Mage's performance, duties and contributions to the DAO. Mages who will not be active for a limited period of time for good reason due to life circumstances may arrange to have the absence approved and appoint a proxy member to participate in governance on behalf while they are absent. Otherwise, Mages that are found to be inactive or providing insufficient value to the DAO will be expelled through a GuildKick proposal. Alternatively, if the Mage is considered to be an "accredited investor", they may be downgraded into the category of Goblin and thrown back in their moldy dens with their gold.

It is also expected that the persons who have mandatory Mage status--i.e., unaccredited investors--will be limited to a relatively small group. Securities laws issues aside, there are scaling constraints on partnership-style governance structures. If the group of Mages becomes too large, it may become difficult for each Mage to participate as fully in the governance of MCV as is required for the role. Over time, as MCV's off-chain social procedures for encouraging communication and information flow among members improve, the upper bound of the number of Mages who may robustly participate without reducing governance quality should increase.

**Grimoire - Liabilities of Members**

In general, the Delaware Limited Liability Company Act enables the members to invest in an LLC and participate in an LLC's affairs with the protection of "limited liability." This means that individuals are not personally liable for a debt or other obligation or liability incurred by the LLC. However, a member may have liability for receiving distributions of assets from the DAO at a time when MCV as an entity did not have a sufficient surplus of assets over liabilities. To maintain the legality of permissionless exit through rageQuit, MCV should always be managed on a net-positive-asset basis so that there are sufficient net assets in excess of liabilities to cover distributions to members when they exit. 

Limited liability also does not apply in connection with actions a member takes without authorization (e.g., signing a SAFT for MCV before a proposal for the SAFT has been approved), illegal actions or actions that disregard the separateness of the LLC (e.g., using the Guild Bank as a substitute for their personal bank account and regularly rotating into and out of membership). 

**Grimoire - Fiduciary Duties & Indemnification**

Traditionally (though not always), non-managerial members of an LLC are protected through the fiduciary duties on the LLC's managers where they exercise loyalty to and/or provide professional care on behalf of non-managerial members. Upon breaches of trust, aggrieved members can then sue the LLC's managers for the breach of fiduciary duties and mismanagement. This can even be the case in member-managed LLCs or in full-blown general partnerships where all partners have equal information. However, fiduciary duties are a "fuzzy" standard, and are often displaced, even in traditional corporate law and deal-making, with more negotiated, tailored contractual arrangements. 

Consistent with this modernization of corporate law, under the MolochDAO spirit, we believe free exit is the ultimate minority protection mechanism; accordingly, all fiduciary duties will be waived and eliminated under the Grimoire as permitted by the Delaware Limited Liability Company Act. Accordingly, the members of the DAO will be expected to participate actively in the DAO's affairs and RageQuit if they are unhappy with the manner in which the DAO is managed by the economic majority of members. The non-waivable covenant of good faith and fair dealing will continue to apply to members under the Delaware Limited Liability Company Act and require them to faithfully and fairly implement the terms of the Grimoire.

Consistent with the Moloch DAO's individualistic and simple design philosophy, no member or manager will have a right of indemnification from the LLC or the other members. Each member and manager is solely responsible for any liabilities that member or manager personally incurs in connection with involvement in the DAO, unless otherwise specifically agreed through a binding proposal approved by the DAO members.

**Securities Law Issues - MCV Buying Other Issuer's Securities / MCV's Accredited Investor Status **

MetaCartel Ventures aims to participate in a wide range of investment opportunities ranging from cryptonative tokens which may not be securities to SAFEs, SAFTs, revenue-sharing arrangements and other types of debt or equity securities. Because many projects rely on the exemptions from securities registration provided by Rule 506(c)(3) under Regulation D, which requires that all the participating investors be "accredited investors," MCV requires to be recognised as an "accredited investor" under the applicable standards for the accreditation of legal entities under Regulation D. This will be the case if MCV either only has members who are "accredited investors" under the net worth or income tests of Rule 501 of Regulation D or if MCV itself has assets in excess of $5M.

This means that MetaCartel Venture's initial membership will be limited to individuals satisfying the financial tests for being an "accredited investor." Such individuals must either have individual net worth, or joint net worth with a spouse, exceeding $1,000,000 or must have income exceeding $200,000 in each of the two most recent years or joint income with a  spouse exceeding $300,000 in each of those years and have a reasonable expectation of reaching the same income level in the current year. Only once MCV manages more than $5,000,000 USD in assets, could individuals that are deemed to be "unaccredited investors" potentially become members of MCV (as Mages), without adversely affecting MCV's ability to invest in other projects.

**Securities Law Issues - MCV Issuing MCV Shares - Members' Accredited Investor Status**

As MCV issues out membership interests to its members, it must ensure that its transactions are either registered or exempt from registration (eg. pursuant to Rule 506(c)) under applicable securities laws.

Because of the extensive management and information rights of MCV's members, along with MCV's small scale, MCV may be and in fact is intended to be--a general partnership for securities law purposes. Accordingly, it is possible that its membership interests are not securities for purposes of U.S. federal securities laws. "The general rule [eg. presumption -ed. .] is that units in general partnerships are not investment  contracts and therefore not securities..." (Shiner, 268 F.Supp.2d at 1340). Moreover, it is arguable whether MCV's membership interests implicate the policy concerns underlying securities laws as strongly as a conventional  securities transaction, given the non-transferability of membership interests, the radical right of "free exit" afforded to MCV members and the lack of information asymmetries among members. Nevertheless, because MCV wishes to encourage the extensive use of such rights and to set a particularly strong example of quality governance and legal compliance, MCV goes further by assuming that its membership interests could be securities and requiring all membership interest transactions to comply with U.S. federal securities laws.

While MCV may choose to avail itself of any securities law compliance path, it is currently anticipated to operate as follows: 

-   persons who are "accredited investors" under the net asset or income tests of Rule 501(a) of Regulation D  may become either Mages or Goblins, as desired, pursuant to Rule 506(c); 

-   persons who have the competence and willingness to serve as Mages and thus function as general partners of MCV may become Mages and may remain Mages for as long as they fulfill their Mage responsibilities, and either their membership interests will not be securities or, if they are, the transaction will be exempt because the Mages qualify as general partners and thus accredited investors under Rule 501(a)(4) of Regulation D or because the transaction is exempt under Rule 701.

**Tax Law Issues**

The LLC will be taxed as a U.S. partnership, meaning that the LLC pays no taxes but its members do. As a result, each member's pro rata share of the profits and losses of the LLC will be reportable as the member's individual income or loss each year. The Mages will be responsible for ensuring that each year the LLC engages tax accountants to prepare a Schedule K-1 for each member setting forth the member's share of the LLC's profits and losses for that year. The Mages will also be responsible for causing each Schedule K-1 to be filed with the IRS each year. Every member will need to submit a Form W-9 or Form W-8BEN, as applicable, as part of the member's onboarding, to certify that the member is exempt from backup withholding on distributions of funds from the DAO.

![](https://lh4.googleusercontent.com/6dhBDKPMrj-suRbt5FKiR6pC62O0G98_erNlNxF6--p8BDKRfo18WJDLM_gagijzt_uaOm37MSq0hxbBoX8iWZEVw6o0b3dZ1lESTJ0J2XBRiIpMdQyvSXpV7_UmvTDbli3TpI38)

COUNTERING OPPONENT SPELLS 

Asset Management
================

Most of the technical differences between Moloch v1 and [Moloch v2 smart contracts](https://github.com/MolochVentures/moloch) including the composed claims token functionality are explained in greater detail with [OpenLaw's post here](https://medium.com/@thelaoofficial/the-lao-joins-forces-with-moloch-dao-and-metacartel-to-begin-to-standardize-dao-related-smart-b6ee4b0db071?utm_campaign=OpenLaw&utm_content=108985829&utm_medium=social&utm_source=twitter&hss_channel=tw-3129477561).

MCV's intention is for the DAO to mainly manage its assets via its on-chain smart contracts to limit administrative overhead, the main key technical components of the DAO being:

-   GuildBank: The DAO smart contract (GuildBank.sol) manages the tokens of the DAO. These funds are used for investments by the DAO in other projects, payments to service providers of the DAO, or for membership redemptions to members who RageQuit or are expelled.

-   Claims tokens: Claims token contracts (ERC-1843) are smart contracts that allocate claims on the future revenue that is deposited into the claims token contracts via specific ERC-20 tokens. Instances of the claims token contract allows the DAO to represent either revenue-generating assets or non-cryptonative assets such as SAFTs which are not live yet, and equity stakes in traditional companies.

-   Off-chain: Off-chain assets used for purposes of paying service providers are held in the LLC's bank account, with its ownership of companies secured through legal contracts.

Exiting Members
---------------

A member who is partially or completely leaving MCV: whether because that member wishes to reduce its stake in MCV, that member wishes to cease to be a member of MCV entirely, or that member is being expelled from MCV by the other members, must redeem their membership interest in the DAO and, in return, will receive their pro rata share of the DAO's then current assets as full and final payment for that membership interest.

Assets are of two types: cash and cash equivalents, which in most cases will be tradable cryptonative tokens ("RageTokens"), or revenue-generating assets ("RageClaims"). 

**RageTokens**

A percentage of cryptonative tokens then currently held in the GuildBank equal to the member's percentage membership interest in the DAO. These will be immediately tradable and do not represent any contractual right against the DAO.

**RageClaims**

A percentage of claims tokens then currently held in the Guildbank equal to the member's percentage membership interest in the DAO. Although these may be a variety of tokens corresponding to different ClaimsToken.sol contracts existing at the time of the exit, they are best conceived of as a jumbo economic remainder interest in the DAO that represents a contractual claim to receive future proceeds of the specific investments that the DAO has at the time of the member's exit. These tokens/rights are non-transferable and are personal to the exiting member.

The exiting member will not be entitled to receive the securities of the companies that the DAO has invested in and will not have any direct rights against those companies; rather, the exiting member will have a right to claim a percentage of the DAO's proceeds from those securities.

**Hybrid RageToken/RageClaim**

RageClaims relating to a SAFT may end up being redeemable for either the exiting member's pro rata share of a refund or the exiting member's pro rata amount of a cryptonative token to be issued in the future. In the latter case, the RageClaim token will need to be redeemed in exchange for the relevant cryptonative tokens once they are delivered to the ClaimsContract pursuant to the converted SAFT (or once the cryptonative tokens become tradeable, if they are subject to a lock-up).

**RageQuits**

As discussed above under "Grimoire," a member may "RageQuit" (voluntarily resign as a member), in whole or in part, at any time, by calling the RageQuit function with reference to a specific number of the member's shares. A partial RageQuit is a reduction in shares. A complete RageQuit is a resignation of membership. In most cases, a RageQuit or RageKick will work seamlessly. However, there are several game theoretical edge cases that are addressed with MolochDAO v2: 

Because there is an up to two-week delay between a proposal being voted on and being fully implemented (voting period of one week, grace period of one week), a member could vote to approve various proposals which adversely impact the other members and leave the DAO without experience the consequences. This effectively means that members were directing proposals with funds they were not entitled to managing, and thus a potential source of conflict and moral hazard. Members are not allowed to leave the DAO if they have voted "YES" on proposals that have not been fully processed.

Moloch DAO v2 smart contracts are dependant on the external ERC-20 smart contracts controlled by third parties, therefore we must always hold the assumption that the smart contracts that MCV calls, are at all times untrusted and potentially adversarial. An example of this would be with a whitelisted GuildBank token that happens to blacklist an existing DAO member. In this case, if the blacklisted DAO member attempts to RageQuit, the RageQuit function will revert and result in an error as the GuildBank would be unable to call the transfer function to distribute the adversarial set of RageTokens to the blacklisted DAO member. As a result, the DAO member will be unable to leave the DAO. In order to deal with this problem and preserve the power of free exit (while also honoring any potentially important third-party restrictions that may have been imposed on a member for legal reasons), MolochDAO v2 includes a SafeRageQuit function. By calling SafeRageQuit instead of RageQuit, a quitting member may (by setting the parameters) choose to avoid receiving the problematic type of RageToken, but still receive all the RageTokens and RageClaims from which the member is not blacklisted. 

Proposal types
--------------

In the Moloch v2 smart contracts, there are 8 proposal types which must pass a voting and grace period, similar to Moloch v1, including:

-   Membership admission proposals: A successful membership proposal admits a new member into the DAO through the issuance of DAO shares. These DAO shares, provide members governance rights and a claim of the assets under the GuildBank's management. The flow for membership proposals is as follows:

-   A DAO membership applicant's tribute funds are escrowed in the Moloch.sol smart contract as their membership proposal passes through voting and grace periods

-   When the DAO proposal passes, the DAO membership tribute funds are moved from Moloch.sol into the GuildBank, where a non-transferable membership interest will be minted and assigned to the newly approved DAO member. 

-   "Membership" proposals can also offer cryptonative tokens (instead of shares) as payment. Legally speaking, these are not membership proposals but simply a mechanic for receiving payment from the DAO for some property or service.

-   Membership expulsion (GuildKick) proposals: Any member may at any time propose that another member (the 'target member') be expelled from the DAO by submitting a guildKickProposal. If that proposal is approved by sufficient other members, then one of two events will occur:

-   Possibility #1:  If the member has not voted previously voted "YES" on any proposal that is still pending (eg. being voted on or already approved but in the grace period), then the target member will immediately be rageQuitted with the same effect as if the target member had rageQuitted voluntarily (eg. member receives all RageTokens and RageClaims, pro rata).

-   Possibility #2:  If the member has voted "YES" on any proposal that is still pending (eg. being voted on or already approved but in the grace period), the member cannot be force-rageQuitted immediately (for the same reason that we do not allow members to voluntarily rageQuit in the same circumstance), therefore, the member is "jailed".

-   Jailing & Ragekick: In the case that a member has been the target of a GuildKick, but have previously voted "YES" on pending proposals, they are not allowed to immediately RageQuit the DAO. Just as if this were a voluntary RageQuit, they are "Jailed" and held in the DAO with "loot" (non-voting shares) temporarily with a maximum sentence of two weeks for proposals to pass and to ensure that the target member remain responsible for the effects of the proposals they have voted "YES" on.

-   Until the proposals that the Jailed member voted "YES" on are processed, they are Jailed and cannot vote upon any other proposals. Essentially, the GuildKicked member is no longer a full member, but is stuck holding a pure economic claim to the relevant RageTokens and RageClaims for a period of time before it actually receives the distribution. 

-   Once all of the relevant pending proposals have been fully processed, any member can call the "RageKick" function on the target member, or the Jailed member can call the "RageQuit" function on themselves. Either action will trigger the appropriate distribution of RageTokens and RageClaims to the target member. 

-   In the unlikely, but possible event that the target member is blacklisted from receiving a particular RageToken (as in the hypothetical explored above under "RageQuits") and does not "safeRageQuit" soon enough (within 2 weeks), the target member will require a "bailout".

-   Bailouts: Bailouts are a failsafe mechanism intended to allow a custodian to facilitate the exit of a member when the funds become stuck in the DAO due to a glitch caused by the third-party smart contract governing one or more RageTokens.

-   In a guildKicked member has been sitting in jail for too long (more than two weeks), their "YES" approved proposals were processed, and haven't SafeRageQuitted, they may be bailed out.  This means their funds are "bailed out" to a multisig smart contract controlled by a group of trusted members and/or summoners, who act much like receivers or trustees in a legal proceeding. The Grimoire (along with basic courtesy) will require that this trusted group work to distribute the RageTokens and RageClaims to the exiting member.

-   Token whitelist proposals: A successful whitelist proposal which adds a new ERC-20 token address to the token whitelist. These proposals determine what tokens the DAO can manage, invest and take membership tribute in. It is critically important that the smart contracts of tokens proposed to the whitelist are carefully scrutinized for potential transfer restrictions that may cause them to hinder or halt the operation of the DAO.

-   Investment proposals: A proposal that transfers funds based on the DAO's agreement to enter into an investment contract. In this case, the DAO receives a whitelisted token in return for the payment to a specified address in the form of shares, a whitelisted token, or any combination.

-   OTC/Trade proposals: A proposal that offers tribute and receives payment in another token for the purposes of asset management.

-   Grant proposals: A purely output proposal detailing the payment in the form of shares, a whitelisted token, or any combination thereof to a specified address.

Investment flow of funds
------------------------

![](https://lh3.googleusercontent.com/Ye64KPlPYuv4nw_jwC9hXf2Qlc9HviVaZBkunErvPKjRXR0T80TdD_0lK0cc92SnhUTW6jgJHMceX9PiQANJacXdBkdekh7rD63K6lXZlpnahdwWfJSWmnUSryJSzkJmgYJqmuXt)

**Investment in a cryptonative token (Ethereum mainnet ERC-20 tokens)**

The DAO may invest directly into live ERC-20 cryptonative tokens or manage its portfolio through conducting an OTC trade with a liquidity supplier. If such a proposal passes, the cryptonative tokens to be accepted by the DAO as "tribute", and the GuildBank will send either a specified whitelisted token in return as payment or potentially also decide to award DAO membership in exchange.

**Investment in a SAFT or a security of a company**

When the DAO is making an investment into securities or revenue generating assets, its flow of funds is similar to cryptonative token investments. Instead of an cryptonative token being accepted as tribute, a specified ERC-20 token corresponding with an instance of that investment's claims tokens contract is accepted by the GuildBank. 

1.  A Mage (or summoner(s) acting on behalf of one or more Mages) proposing the investment, will deploy an instance of ClaimsToken.sol

2.  Next, the corresponding claims token contract ERC-20 is whitelisted as via the proposal

3.  After that, an investment proposal is made in exchange for the Claims Tokens as tribute in exchange for DAO membership shares or a specified whitelisted token as payment for the investment.

4.  If the proposal is approved, the GuildBank will receive the Claims Tokens, and the payment would be either distributed to the application or go under custody of a Mage or Summoner as any pending legal documents are prepared and executed.

Assuming all paperwork has been finalised and signed, the Mages or summoning team will release the payment to the seller to pay for the investment. 

**SAFT Waiting period**

If the initial investment is a SAFT, then there is theoretically an undetermined waiting period between the time of investment and the realisation of the desired liquid tokens (including token lockup conditions). This waiting period could be either be short or quite lengthy, depending on the terms of the investment and/or the ensuing series of events. During this period, DAO members that RageQuit with their RageClaims may redeem such cryptonative tokens once the SAFT converts into the right to receive such tokens and the issuer delivers them through the claims token contract. 

**Revenue from equity securities**

If the investment is an non-cryptonative equity or debt security, the investment transaction is considered immediate as the DAO enters into a legal contract. These may include securities which may steadily pay dividends over time, or may remain illiquid for a long period, until there is a "liquidity event" such as an acquisition or IPO of the issuing company (in the case of an equity security) or "maturity date" (in the case of a debt security).

In all such cases, it is possible that DAO members could RageQuit or be RageKicked during a waiting period or a period where equities don't generate profit or revenue. In such a case, exited members will be entitled to pro-rata claims, further maintaining the integrity of the minority protections contemplated enabled by the Moloch v2 smart contracts.

In the case of significant returns from certain equity positions eg. when a DAO's portfolio company is acquired and results in a 20x return, the DAO may also decide to sell a certain portion of those returns back into the DAO. While usually, future revenue of a corresponding claims token contract are deposited so that all exited DAO members with RageClaims are able to realise the same financial gain, the DAO may decide to re-invest its entitled share of profits back into the DAO and manage the distribution of Rage Claims manually to their entitled holders off-chain managed by Mages or Summoners.

Disclaimers
-----------

THIS PAPER IS NOT INTENDED TO CONSTITUTE AN OFFER TO SELL, OR SOLICITATION OF AN OFFER TO BUY, ANY SECURITIES.

ANY AND ALL SECURITIES REFERRED TO HEREIN HAVE NOT BEEN REGISTERED UNDER THE SECURITIES ACT OF 1933, AS AMENDED, OR UNDER APPLICABLE U.S. STATE OR FOREIGN SECURITIES LAWS. 

NEITHER THE SECURITIES AND EXCHANGE COMMISSION NOR ANY U.S. STATE OR FOREIGN SECURITIES COMMISSION HAS PASSED UPON THE ACCURACY OR ADEQUACY OF THE CONTENTS HEREOF. 

NO REPRESENTATION, WARRANTY OR ASSURANCE IS MADE REGARDING THE ACCURACY OF THE INFORMATION CONTAINED HEREIN, AND IT IS NOT INTENDED TO BE RELIED UPON BY ANY PERSON. THE INFORMATION CONTAINED HEREIN MAY NOT REFLECT SUBSEQUENT DEVELOPMENTS. NOTHING SET FORTH HEREIN IS INTENDED TO BE LEGAL, TAX OR FINANCIAL ADVICE TO ANY PERSON. 

THE FORWARD-LOOKING STATEMENTS IN THIS PAPER ARE SUBJECT TO NUMEROUS ASSUMPTIONS, RISKS AND UNCERTAINTIES WHICH ARE SUBJECT TO CHANGE OVER TIME. THERE ARE MANY RISK FACTORS, INCLUDING THOSE RELATING TO BLOCKCHAIN AND CRYPTOGRAPHIC TECHNOLOGY GENERALLY, AS WELL METACARTEL'S BUSINESS, OPERATIONS AND RESULTS OF OPERATIONS, THAT COULD CAUSE ACTUAL RESULTS OR DEVELOPMENTS ANTICIPATED BY US NOT TO BE REALIZED IN WHOLE OR IN [PART OR, EVEN IF SUBSTANTIALLY REALIZED](https://www.youtube.com/watch?v=JwhWKqS13DY), TO FAIL TO ACHIEVE ANY OR ALL OF THE BENEFITS THAT COULD BE EXPECTED THEREFROM. WE RESERVE THE RIGHT TO CHANGE THE PLANS, EXPECTATIONS AND INTENTIONS STATED HEREIN AT ANY TIME AND FOR ANY REASON, IN OUR SOLE AND ABSOLUTE DISCRETION, AND, EXCEPT AS MAY BE OTHERWISE REQUIRED BY APPLICABLE LAW,  WE UNDERTAKE NO OBLIGATION TO UPDATE PUBLICLY OR REVISE ANY FORWARD-LOOKING STATEMENT, WHETHER AS A RESULT OF NEW INFORMATION, FUTURE DEVELOPMENTS OR OTHERWISE. ACCORDINGLY, WE RECOMMEND THAT YOU DO NOT RELY ON, AND DO NOT MAKE ANY FINANCIAL DECISION OR INVESTMENT BASED ON, THE STATEMENTS CONTAINED IN THIS PAPER --- INCLUDING BUT NOT LIMITED TO ANY SELLING OR TRADING OF  ETHER OR ANY OTHER CRYPTOGRAPHIC OR BLOCKCHAIN TOKEN, OR THE SECURITIES OF ANY COMPANY OR OTHER ORGANIZATION OR GROUP.\
WE ARE THE CARTEL DE LA META\
![](https://lh4.googleusercontent.com/W2TDleo6oBGADWxR7SK67vna0gKCLE4YmMqw_9mN8gMKbIzgqS10dDsJ_kQQ3y3mfX39opRc3WlodL46Cx96huQ-WSge7cwFTqSpyTsm1_xSPABW_C3DVsXjltt5ufx_8IaUWOtX)
