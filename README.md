#Project Taö: Frictionless collaboration

##Primary Goals: 
 - Incentivize actors in broader ecosystem: users, partners, third-party developers, community representatives, etc.
 - Enable broader ecosystem (beyond core team) involved in overall direction, and form a stronger network
 - Allow granular slice & dice of rights for different contributors
 - Raise funding via share issuance

##Summary
Any organization could distribute crypto tokens as a way to attract its extended stakeholders/community to participate and contribute.
These crypto tokens would be extremely 


##Scenarios
1) An early-stage startup that is building its platform software,  hopes to attract third-party developers to develop on top of it, and indirectly attract users. 
2) An online community startup, of which its community members are its most important asset and responsible for generating content(posts). 

##Primary features
 - Create a new organization (potential mappings: legal entity, github repo/org, twitter/fb profile, or a Ethereum DO)
 - Issue new crypto tokens that represent specific rights. Issuance could be targeted, conditioned, for sale, or to general public (free or random).
 - Generate legal  documents that the startup need to sign in order to make crypto tokens legally binded to the underlying rights
 - Tokens vested upon certain triggering events or time 

## Product Design
### Entity and relationships

### Rights:
 - Parent Entity options/shares
 - Subentity/SPV Entity options/shares
 - Revenue sharing
 - Digital Asset & Intellectual property co-ownership
 - Governance participation / approval / veto 
 - Fund withdrawal
 
### Internal Assets:
 - Bitocins
 - Other Crypto Tokens (e.g. Ether, BitUSD, Tether, etc.)
-  Fiat corporate banking account (alternative: ripple, feeds of bank)
 - Intellectual properties
 - Reputation
- ?

### Policies/Governance
authorization of fund use

### Tasks / Triggers for rewards
 - Tradle Software Development 
 - Investment
 - Promotion and Marketing
 - BD leads and deal-making

Different type of Actors
 - Tradle core team
    - Executives
 - Governance board (core, community, independent, etc.)
 - Tradle software contributors
 - Partners
 - Community contributors (marketing / bd)
 - Investors in general
 - Auditors
 
Open questions
- legal: reselling
double taxation
- intl: 
- monetization w/o being an intermediary
- vesting
 * cliff
 * timing
- consulting



Below is a thought piece for the future, not for immediate projects we are discussing. We looked through assembly.com and liked a lot their model.
 
1. Ownership Model. Love that they are using appcoins to track ownership in projects. 5% of the coins are allocated to the founders of the project, 10% to assembly.com. The rest of coins needs to be earned by via bounties, even by project owners. Bounties are approved by project owners, so there is a possibility for fraud - allocating bounties for themselves. But since the work is done in the open - transparency becomes a deterrent for fraud.

2. Revenue sharing. Ongoing revenues, and proceeds from the sale of the project, are distributed proportional to coin ownership.

3.  Legal. In the US a Series LLC (SLLC) could map easily into this model. According to Houman Shadab, professor of Law at NY School of Law, the appcoins-based share distribution within the LLC is perfectly legal as long as all participants are effectively partners/employees and not speculators. There is no limit on a number of participants either. Other countries have a similar corporate formation model. Yet, a mix of participants from different countries could be a problem, especially with taxes. I have several tax accountants contacts that I will consult with on this.

3. Concerns. 
- their system of allocating appcoins via bounties is extremely simple to understand. But I am afraid it does not cover more complex projects that require more than one-off type of work. I know that bounties work for bug hunting, security reviews. But bounties failed for mastercoin to produce code that was evolving cohesively with other components and was maintained on a long term basis. Assembly uses

- It is possible that the finer granularity of projects is the key to make it work, e.g. current development trend is to have github repo for every small project, as you can see on https://github.com/tradle, we use this approach.

- bounties are good for time-based work, but they do not cover expenses - equipment, travel, lease, insurance, and other payments to outside parties.

Still - this model is compatible with a DAO, eliminating any need to trust assembly.com (central entity), so I feel we can evolve it with more complex policies as smart contracts. For example, Assembly is using bounties for long time work, e.g. “4 hours a day of social marketing”. This type of work needs vesting period or vesting benchmarks (like number of twitter followers, number of github forks) and can be implemented via a smart contract.



