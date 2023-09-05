## DAO and Governance

# Author: k77

# Steps
1. We are going to have a contract controlled by a DAO
2. Every transaction that the DAO wants to send has to be voted on
3. We will use ERC20 tokens for voting(bad model, please research better models, plutocracy issue)

## Break down of MyGovernor.sol
# Governor
Core of the governance system, designed to be extended though various modules.
 *
 * This contract is abstract and requires several functions to be implemented in various modules:
 *
 * - A counting module must implement {quorum}, {_quorumReached}, {_voteSucceeded} and {_countVote}
 * - A voting module must implement {_getVotes}
 * - Additionally, {votingPeriod} must also be implemented

# GovernorSettings
Extension of {Governor} for settings updatable through governance.

# GovernorCountingSimple
Extension of {Governor} for simple, 3 options, vote counting.

# GovernorVotes
Extension of {Governor} for voting weight extraction from an {ERC20Votes} token, or since v4.5 an {ERC721Votes} token.

# GovernorVotesQuorumFraction
Extension of {Governor} for voting weight extraction from an {ERC20Votes} token and a quorum expressed as a
 * fraction of the total supply.
