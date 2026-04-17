# Greeting.sol
This actually makes a lot of sense.
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract Greeting {
    function sayHello() public pure returns (string memory) {
        return "Hello Blockchain!";
    }
}
Add new feature
Remove unused code
Improve error handling
Optimize gas usage
Add input checks
