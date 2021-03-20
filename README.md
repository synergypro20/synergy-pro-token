# Synergy Pro Token
Token contract

**contract SafeMath**
* function safeAdd(uint a, uint b)
* function safeSub(uint a, uint b)
* function safeMul(uint a, uint b)
* function safeDiv(uint a, uint b)

**contract ERC20Interface:**
* function totalSupply()
* function balanceOf(address tokenOwner)
* function allowance(address tokenOwner, address spender)
* function transfer(address to, uint tokens)
* function approve(address spender, uint tokens)
* function transferFrom(address from, address to, uint tokens)

**contract ApproveAndCallFallBack**
* function receiveApproval(address from, uint256 tokens, address token, bytes data)

**contract SYPToken is ERC20Interface, SafeMath**
* function totalSupply()
* function balanceOf(address tokenOwner)
* function transfer(address to, uint tokens)
* function approve(address spender, uint tokens)
* function transferFrom(address from, address to, uint tokens)
* function allowance(address tokenOwner, address spender)
* function approveAndCall(address spender, uint tokens, bytes data)


## Build and Install

Instructions about how to build and install the Solidity compiler can be found in the [Solidity documentation](https://docs.soliditylang.org/en/latest/installing-solidity.html#building-from-source).

## Documentation
The Solidity documentation is hosted at [Read the docs](https://docs.soliditylang.org/en/v0.8.2/).


