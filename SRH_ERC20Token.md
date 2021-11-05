# **Create an ERC20 Token with underneath features.**

### I am going to make a new  crypto token on best of Ethereum Blockchain using Solidity Programming Language. Our new  token contain all the underneath features. (I have gone through and learnt this project from https://www.blockchain-council.org/ Blockchain Council's program of "Certified Blockchain Developer").


#### 1. The token name is SRHToken and symbol denoted by SRH.

#### 2. The creator of token must specify the initial token supply during the creation.

#### 3. The users (holders of token) may transfer the tokens from one account to another account.

#### 4. Debt or negative balance not permitted.

#### 5. There is one administrator who may or may not be the currency creator.

#### 6. Currency creator himself or someone else should be become admin.

#### 7. Anyone must be able to buy or sell SRHToken using ethers.

#### 8. Admin must set the buy or sell price, at any time.

#### 9. Admin is authorized person to transfer the administrator role to any other person (address).

#### 10. Admin has got authority to mint new SRHToken to anyone’s address.

#### 11. Admin has got the authority to freeze or unfreeze tokens of anyone’s account.

#### 12. SRHToken should be ERC20 complaint.

##  _There  are following six functions and two events in ERC20 Token compliant._

```Solidity

function totalSupply() public view returns (uint256)
function balanceOf(address _owner) public view returns (uint256 balance)
function transfer(address _to, uint256 _value) public returns (bool success)
function transferFrom(address _from, address _to, uint256 _value) public returns (bool success)
function approve(address _spender, uint256 _value) public returns (bool success)
function allowance(address _owner, address _spender) public view returns (uint256 remaining)


event Transfer(address indexed _from, address indexed _to, uint256 _value)
event Approval(address indexed _owner, address indexed _spender, uint256 _value)

```
