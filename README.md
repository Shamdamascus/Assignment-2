# Assignment-2

// SPDX-License-Identifier: MIT

pragma solidity ^0.8.0;

contract Assignments {
    string  str = "Hello solidity";
    uint8   stateVariable = 10;
    //task 1
    function printHelloSolidity() public view returns (string memory) {
        return str;
    }

    // task 2
    function returnStateVariable() public view returns (uint8) { 
        return stateVariable;
    }
    
    function returnLocalVariable() public pure returns (uint8) {
        uint8 localVariable = 20;
        return localVariable;
    }

}
