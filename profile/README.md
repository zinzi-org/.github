# Project Zinzi


The goal of Project Zinzi is to implement and maintain a series of Solidity smart contracts that will provide the structure for anyone to build a fully functioning organization that exists on chain. The contracts will include governance, member boards, members, proposals and projects for members to bid on that can be potentially monetized. We want to borrow all possible structures that can be observed in modern day corporations and nonprofit organizations and implement them into a defined smart contract protocol and make it open source and free for anyone to build organizations that have defined and maintained membership. 

The Zinzi Governance Contract will meet all interface requirements outlined by [Tally DAO](https://www.tally.xyz/)  and [OZ](https://docs.openzeppelin.com/contracts/4.x/api/governance)  
Zinzi governance contract will tightly couple with the Member Board Smart Contract. This will allow organizations to function democratically. 

Each Member Board smart contract can have up to three board members. These board members will be subject to elections and other proceedings from the member base via the governance proposal system. 

New users can submit proposals to become members of the organizations. The organizations will be encouraged to build out the interview process for their organization via a UI designed and maintained by Zinizi Org. 

Members will be minted a NFT from the Member Contract. This NFT will show up in their wallet and they can show in any open marketplace to show they are indeed a professional in their trade and worthy of hire or whatever their membership might indicate they are worthy of.


### [Core Contracts](https://github.com/zinzi-org/contract-core)

- Zinzi Governance (Open Zeppelin / Compound Governance Modules with Member Board Hooks)
- Member Board (Ethereum Based Governance  Smart Contract)
- Member (ERC721 Soulbound Membership Token)
- Project (ERC721 Transferable Token)

## Member Board Smart Contract

Before someone can claim to be a member of an organization, the organization must be defined. 

A member board is something that anyone can create, all you need is a name.

When a new user creates a member board he is calling the Member Board Factory smart contract which in turn deploys a new Member Board smart contract into the ethereum network.

A Member Board smart contract can have up to three board members.  The person who created the board initially will be marked as the first board member.

Board members will be voted on annually and are subject to flash impeachment proceedings. 

Each contract can accept new member applicants who must meet the interview criteria defined by the board members. 

Board members are required to create and maintain a group's interview process. Members who are being admitted are subject to peer review via internal ethics reviews and impeachment proceedings. 


## Member NFT

Once an applicant is admitted to a board by a member after an interview process he will be minted a soulbound NFT. 

This NFT has a variety of benefits, for instance if the board of members you belong to is prestigious it could help you find work and other social benefits. Helping people find work is something the Zinzi foundation wants to focus on.

We will accomplish the goal of providing work to members. Project zinzi will maintain a variety of Project NFTs. These projects will be auctioned on open NFT markets where members can place bids on the projects. If a project requires a big undertaking and two board members agree a NFT can project, NFT can be bid on by an organization. Individual members can submit independent bids as well.

## Project NFT

After a Project NFT is awarded to a member bidder the contract becomes unlocked. A Project NFT can have many types. 

- Crowd Loan Project Type
- One Time Funded Project Type
- Agile Project Type

When a bid is accepted and the proposal is accepted by the member the project type will unlock a series of functions  based on the needs of the individual or group that created the proposal and the individual or groups who accepted the proposal with a winning bid. 


## Navigating The Source Code

### [Core Contracts](https://github.com/zinzi-org/proj-team)

All smart contracts developed by zinzi.org

### [Zinzi](https://github.com/zinzi-org/zinzi)

[https://www.zinzi.org](https://www.zinzi.org)

Zinzi is the root foundation website where all documentation and news will be displayed.

### [Board Studio](https://github.com/zinzi-org/brd-studio)

[https://www.brd.studio](https://www.brd.studio)

A place for members to create and maintain their member board.

### [Team Project](https://github.com/zinzi-org/proj-team)

[https://www.proj.team](https://www.proj.team)

Team Project is a place where users can apply to join a group and existing members can maintain their current groups.

### [Proposal Camp](https://github.com/zinzi-org/prop-camp)

[https://www.prop.camp](https://www.prop.camp)

Proposal Camp is where Proposal/Project NFTs will be designed and auctioned.

### [Bird Pizza](https://github.com/zinzi-org/brd-pizza)

[https://www.brd.pizza](https://www.brd.pizza)

brd-pizza is an experimental social network using member board smart contracts. 

### [Scheme Run](https://github.com/zinzi-org/scheme)

[https://www.scheme.run](https://www.scheme.run)

Scheme dot run is a web app where users can request quick funded projects with little fuss. 












