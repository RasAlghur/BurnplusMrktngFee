## ABOUT

* This is a solidity smart contract that has Fees on Buy and Fees on Sell
* It uses openzeppellin for contract Ownership
* It already excluded the Owner, address(this), marketing Address and Burn Address from fees
* ownership is transfered to the dev address once contract is deployed
* before deploying, change contract Augument to MyToken and enter parameters
* Parameters to enter are for _devWallet _marketingWallet _totalSupply, _name, _symbol, _decimals
* you do not need to include decimals in _totalSupply. for example, if token totalSupply is 1 million and decimal is 9, you only need to enter ```1000000``` (1M) for _totalSupply witthout include the numbers of decimals
* for decimals, you can include the digit i.e if you want decimals to be Nine, just enter ```9``` or if you want eighteen ```18```
* contract cannot be modified once deployed