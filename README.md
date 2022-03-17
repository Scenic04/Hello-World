// SPDX-License-Identifier: GPL-3.0

pragma solidity ^0.8.10;

contract Helloworld{

     string public helloworld;

    function setHelloWorld(string memory _helloworld) public {
        
    }

    function viewHelloworld() public view returns(string memory){
        return helloworld;
    }
}    

