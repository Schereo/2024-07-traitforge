# Notes

Entities are either forger or merger. 
The ability of an entity to forge can run out when the generation is full

## Description of files

1. DevFund.sol: 
   1. Devs can be added, removed and updated. 
   2. Allows to receive ether and sends parts of it to the owner. 
   3. Devs can also claim their part of the funds. 
   4. Definitely check the payout functions to make sure calculations are correct and that there are no underflows.

2. EntityForging.sol (Docs not up to date):
   1. Creating a new entity from a listed entity and
   2. The entropy of the child is calculated