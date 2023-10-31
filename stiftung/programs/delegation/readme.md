# ICF Delegation Program
Contributors and Cosmos community members have been asking for a responsible and impactful ICF delegation policy since 2019. 
In 2022, ICF revised its policy. The updated delegation policy for Cycle 2 was published on September 2023.

The ICF delegation [disclaimer](https://github.com/interchainio/delegation/tree/master/delegations) reads:
> The ICF reserves the right to change its delegations at any time. It may withdraw delegations from some or all of the validators it has delegated to and/or redelegate to specific validators at any point in time without any reason. Further, no validator may assert any claims against the ICF to delegate ATOMs to them. The ICF is under no obligation to delegate its ATOMs.

Given that ICF delegations can change at any time, [@piyush4](https://github.com/piyush4) has written script in Python using Mintscan. The [script](https://github.com/piyush4/bounty-6/blob/main/current_delegations.py) calculates the current delegations (the amount, validator name along with validator website addresses, if available) of ICF from mintscan and stores them in a CSV file.
 
Given that ICF delegations can change at any time, [@piyush4](https://github.com/piyush4) has written script in Python using Mintscan. The [script](https://github.com/piyush4/bounty-6/blob/main/current_delegations.py) calculates the current delegations (the amount, validator name along with validator website addresses, if available) of ICF from mintscan and stores them in a CSV file.
 

#### Delegation History

ICF delegation [policy from 03/2019 - 12/2022](https://github.com/interchainio/delegation).

[**Round 1**](https://github.com/interchainio/delegation/tree/master/delegations/1-gos): The purpose of the Interchain Foundation’s (ICF) first delegation was to help decentralize the network outside of the top validators and strengthen the entire network with trusted participants. The Foundation created a "replicable process" based on data available in the genesis block and qualified trusted participants via competition in [Game of Stakes to assess their capabilities](https://github.com/interchainio/delegation/tree/master/delegations/1-gos).

[**Round 2**](https://github.com/interchainio/delegation/tree/master/delegations/2-match-small) :
The second round of delegation consisted of approximately 1.35M ATOMs and went to validators with less than 250,000 ATOMs bonded. For a given validator with `X` total ATOMs bonded, where `X < 250,000`, the ICF delegated the lesser of `(0.5*X)` and `(250,000 - X)`.
For example, if Validator 1 has 10,000 ATOMs, the ICF delegated 5,000 ATOMs to Validator 1 (ie. `0.5*10,000`). If Validator 2 has 230,000 ATOMs, the ICF delegated 20,000 ATOMs to bring this Validator up to exactly 250,000 ATOMs (ie. `250,000 - 230,000`).

[**Round 3**](https://github.com/interchainio/delegation/tree/master/delegations/3-contributors): Delegations to contributors. 
The Foundation issued a [call](https://twitter.com/interchain_io/status/1137103291769327617) for delegation applications from June 7-June 17, 2019, and 46 validators applied.

> Contributions could include (but are not limited to):

* Creating a block explorer for the community to use
* Active engagement in the governance process
* Publishing articles about Cosmos (examples: Governance Proposal Overviews, How To Delegate Your ATOMs etc)
* Holding Cosmos meetups and community events
* Contributing open source code

Due to community discontent, as captured in this [06/2022 Report from Notional, Hypha Coop, and "Moonboy"](https://thoracic-boron-678.notion.site/ICF-Delegation-Report-b4b8c62295564990800fb1226d585e4b), policy was revised in fall/winter of 2022. The Foundation was allegedly delegating to validators who were relatively low contributors, and many were found to be ["dumping"](https://forum.cosmos.network/t/icf-delegation-recipients-who-sell-all/6739) token. 

* [ICF delegations cosmoshub-1, from 2-3 MultiSig **cstv](https://github.com/gaiaus/ICF/blob/main/stiftung/programs/delegation/ICF%20Delegations%20__cosmoshub1_cstv.csv)
* [ICF delegations cosmoshub-2, from 3-5 MultiSig **yfkz](https://github.com/gaiaus/ICF/blob/main/stiftung/programs/delegation/ICF%20Delegations__cosmoshub2_yfkz.numbers)
* [Snapshot of ICF delegations in 2022, prior to revised policy.](https://github.com/gaiaus/ICF/blob/main/stiftung/programs/delegation/2022_delegations.csv).

#### Cycle 1

[**Cycle
1** Delegation Policy](https://github.com/gaiaus/ICF/blob/main/stiftung/programs/delegation/cycle1_policy.pdf)

[**Cycle
1** Delegation List](https://github.com/gaiaus/ICF/blob/main/stiftung/programs/delegation/cycle1_delegations.pdf)

#### Cycle 2

[**Cycle
2** Delegation Policy](https://github.com/gaiaus/ICF/blob/main/stiftung/programs/delegation/cycle2_policy.pdf)

Delegation List Cycle 2 *TBD*
