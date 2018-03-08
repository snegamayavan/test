pragma solidity ^0.4.0;
contract bank{
address public   owner; 
 
   string public name;
    uint256 public decimals;
    string public symbol;
    uint256 public totalSupply;
   
    mapping(address=>uint256) balance;
    mapping(address=>mapping(address=>uint256)) spender;
  
    function bank() public payable{
    
         owner=msg.sender;
            totalSupply = 5000;
           name = "MNW";
            symbol = "$";
            decimals = 0;
        balance[owner]=totalSupply;
    }
     function balanceOf(address owner) public constant returns(uint256){
     
      return balance[owner];   
}
modifier mod(){
    
    require (owner==msg.sender);
    _;
}
function mint(uint256 amount)public mod {
      
  if(amount<totalSupply &&  balance[owner]+amount<totalSupply)
    
      balance[owner]+=amount;
      else
      revert();
    }  
  
function transfer(address _to,uint256 _amount) public returns(bool){
    
balance[_to]+=_amount;    
  balance[owner]-=_amount;   
  
   return true;
}
function approve(address _spender,uint256 value)public returns(bool){
  spender[msg.sender][_spender]=value; 
   
    return true;
    
}
function allowance(address owner,address _spender)public view returns(uint256){
    return spender[owner][_spender];
    
}

function transferFrom(address _from,address _too,uint256 vvalue)returns(bool){
    require(balance[_from]>vvalue && vvalue>0 && spender[_from][_too] > vvalue);
    balance[_from]-=vvalue;
    spender[_from][_too]-=vvalue;
    balance[_too]+=vvalue;
    return true;
    
}
}


