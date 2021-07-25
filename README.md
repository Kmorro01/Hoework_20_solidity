# Hoework_20_solidity
![image](https://user-images.githubusercontent.com/78707082/126886159-27097178-905c-44a2-a23d-fabc888eb643.png)
![image](https://user-images.githubusercontent.com/78707082/126886217-b2fe96d5-d193-4d63-a722-b37ec69fedd4.png)
![image](https://user-images.githubusercontent.com/78707082/126886238-4568d22d-a849-47b1-8886-ffedddb3b822.png)

pragma solidity ^0.5.0;

// lvl 1: equal split
//call contract, and name contract { begins
// create /address/ is the variable = /assigned value/
// string is a representationn of the addresses
// AssociateProfitSplitter {
 // @TODO: Create three payable addresses representing `employee_one`, `employee_two` and `employee_three`.
   
    address payable employee_one = 0xE39cA6392bfC86dFC47Ae67269525BbCBDefac82;
    bool employeeAccount =true;
    uint public balanceContract;
  
    
    address payable employee_two = 0x61Ebd51682B4C91570D4373780135B12a02Ea11E;
    bool employeeAccount =true;
    uint public balanceContract;
   
    
    addres payable employee_three = 0xF4842CffdA37C9bEDA88Defee697C215BB3C0eA2;
    bool employeeAccount =true;
    uint public balanceContract;
    
}

    
    constructor(address payable _one, address payable _two, address payable _three) public {
        employee_one = _one;
        employee_two = _two;
        employee_three = _three;
    }

    function balance() public view returns(uint) {
        return address(this).balance;
    }

    function deposit() public payable {
        // @TODO: Split `msg.value` into three
        uint amount = msg.value /3; 
       
    }
   //transfer amount form the contract to recipient 
   transfer amount = employee_one,employee_two,employee_three
=  function withdraw(uint amount, address recipient public {
    recipient.transfer(amount);
    balnceContract =address(this).balance;
    
    }
  function withdraw(uint amount, address recipient) public {
    recipient.transfer(amount);
    balnceContract =address(this).balance;
    }
  function withdraw(uint amount, address recipient) public {
    recipient.transfer(amount);
    balnceContract =address(this).balance;
    }


        // Your code here!

        // @TODO: Transfer the amount to each employee
        // Your code here!
        
        function deposit( public payable {
            balanceContract = address(this)balance;
        }
        

        // @TODO: take care of a potential remainder by sending back to HR (`msg.sender`)
        // Your code here!
        function transfer msg.value- amount *3 to msg.sender
        
    }

    function() external payable {
        // @TODO: Enforce that the `deposit` function is called in the fallback function!
        // Your code here!
        function deposit
    }
}



