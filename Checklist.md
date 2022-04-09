# Compound Asset Listing - Checklist

## Info that needs to be submitted by the proposer

### General

- [ ] Name.
- [ ] Description.
- [ ] Social Media Links.

### Market Risk Assessment

- [ ] Market Cap of the token.
- [ ] On which exchanges is the token listed and what is its respective liquidity?
- [ ] Indicate volatility of the token using Gauntlet formula.

### Decentralization

- [ ] How is this asset distributed amongst token holders? List the top 5 holders of the token and tag them in case they are known.
- [ ] List all the the privilege roles in the token contract.
- [ ] Is pauseable?
- [ ] Has a blacklist?

### Smart contract risk

- [ ] Etherscan links with verified contracts (token, cToken and new oracle).
- [ ] Public repo link (Underlying token).
- [ ] What audits, if any, have been done?
- [ ] Age of the token in days.
- [ ] Number of transactions in the contract.
- [ ] Provide emergency contacts.
- [ ] List of all monitoring services used by the token, if any.
- [ ] Does the token have more than one address?
- [ ] Provide test suite with code coverage.
- [ ] Does the token use a compiler version greater than 0.8.0 or the SafeMath?
- [ ] During the execution of the token's functions, does the token execute external code chosen by the caller or receiver?
- [ ] Provide documentation.
- [ ] Does it have an active bug bounty program?
- [ ] Formal verification
- [ ] How much does the token contract deviate from a standard implementation of ERC20? Any additional features anyone should know about?
- [ ] Is it burneable?
- [ ] Does it have a fixed supply? If no, who can mint?
- [ ] Is it a Rebase token?
- [ ] Does the token charge fees on transfers?
- [ ] Is the contract performing arbitrary `delegatecall`s?
- [ ] Is it flash mintable?
- [ ] Is it flash loanable?
- [ ] Is it upgradeable?
  - [ ] Who is authorized to make an upgrade?
  - [ ] Can an upgrade happen instantaneously or is there a time-lock delay?
  - [ ] Which components can be upgraded?
  - [ ] How the upgradeability design work? Who manages it and how upgrades are done?


## Community Check

- [ ] Veracity or the info provided.
- [ ] Correct configuration of the contracts (cToken, oracle, etc.).
- [ ] Run eth-saddle or any tool to check if the implemented contract matches the base implementation with the expected parameters.
- [ ] Execute available test suite and simulations.
- [ ] Check documentation quality.

## Initial Requirements

- [ ] Collateral factor to 0.
- [ ] Borrow cap set.

### Considerations

- [ ] Proposals must be first in the Compound forum in the *New Markets* category.
- [ ] The proposal must have a link that directs to the corresponding thread in the forum.
- [ ] One token per proposal.
- [ ] Do not deploy contracts without first submitting the proposal to the forum.
- [ ] Use markdown in the description of the proposal in the transaction, add links and start with # Add market: NAME.
- [ ] This checklist can be modified with new items as the community deems necessary. It can be through the same or similar mechanisms as GitHub's Pull Request.