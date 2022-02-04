# Diabolo Simple Vote

SimpleVote is voting process.

### Constructor

| Variable | Type | Description |
| ------ | ------ | ------ |
| proposalNames | string[] | The proposals names


The constructor set :

 - The proposals names : "proposalNames" (string[])

### Read Contract

##### votersAddresses()

This call returns all voters addresses.

##### votersAddress(uint256)

This call returns the voter address of index.

##### voters(address)

This call returns the vote status and vote of an address.

##### proposals(uint256)

This call returns the name and vote count of a proposal.

### Write Contract

##### vote(uint256)

This function vote to proposal and change voter status(You must approve the token lock contract address to use the amount)

