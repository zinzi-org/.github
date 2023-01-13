# Project Zinzi


The goal of Project Zinzi is to implement and maintain a series of Solidity smart contracts that will provide the structure for anyone to build a fully functioning organization that exists on chain. The contracts will include governance, member boards, members, proposals and projects for members to bid on that can be potentially monetized. We want to borrow all possible structures that can be observed in modern day corporations and nonprofit organizations and implement them into a defined smart contract protocol and make it open source and free for anyone to build organizations that have defined and maintained membership. 


### [Core Contracts](https://github.com/zinzi-org/core-contracts)

- Governor Board Factory
- Governor Board
- Members (ERC721 Soulbound Membership Token)
- Members Vote (ERC20 Token Implementing the ERC20Votes Interface)

## Governor Board & Factory

Before we can have membership we must have the ability to create governor boards that will manage the orgnization. We have the governor board factory which allows anyone to create a new governor board with just a name. 

The governors board is the home for memebers of the orgnization. It gives governors and normal members many unique abilities.


        TEXT_BASED_PROPOSAL, //external outcome
        ADD_GOVERNOR, // we need an address
        REMOVE_GOVERNOR, // we need an address
        SET_BOARD_URL, // we need a string
        REMOVE_MEMBER, // we need an address
        SET_PROP_DURATION, // need a number
        SET_PROP_DELAY, // need a number
        SET_DELEGATION_PERCENTAGE, // need a number
        SET_DELEGATION_THRESHOLD // need a number

- addGovernor
- addMember
- getTotalMembers
- memberHasDelegation
- getGovWhoApprovedMember
- castVote
- propose
- isGovernor
- setBoardURL
- getMemberVotesAddress
- proposalVotes
- hasVoted
- hashProposal
- state
- proposalSnapshot
- proposalDeadline
- votingDelay
- votingPeriod
- getVotes


## Member NFT

## Member Vote ERC20

## Project NFT

After a Project NFT is awarded to a member bidder the contract becomes unlocked. A Project NFT can have many types. 

- Crowd Loan Project Type
- One Time Funded Project Type
- Agile Project Type

When a bid is accepted and the proposal is accepted by the member the project type will unlock a series of functions  based on the needs of the individual or group that created the proposal and the individual or groups who accepted the proposal with a winning bid. 

----------

### [Core Contracts](https://github.com/zinzi-org/core-contracts)

-----------

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

### [Scheme Run](https://github.com/zinzi-org/scheme)

[https://www.scheme.run](https://www.scheme.run)

Scheme dot run is a web app where users can request quick funded projects with little fuss. 












