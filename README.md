# SimpleStorage

SimpleStorage is a simple Solidity smart contract that allows users to set, get a value.

## Features

- *Set Value*: Allows setting a value.
- *Get Value*: Allows retrieving the current value.

## Contract Functions

## setValue

function setValue(uint256 _value) public
Sets the value to _value.

## getValue

function getValue() public view returns (uint256)
Returns the current value.


Usage
Deploying the Contract
Use a development environment like Remix or a local Ethereum development setup.
Copy the contract code into a new Solidity file (e.g., MyContract.sol).
Compile the contract.
Deploy the contract to your desired network.
Interacting with the Contract
Set Value: Call the setValue function with a desired value.
Get Value: Call the getValue function to retrieve the current value.

Example

    // SPDX-License-Identifier: MIT
     pragma solidity ^0.8.0;

    contract SimpleStorage {
    uint256 private storedData;

    // Function to set the value
    function set(uint256 x) public {
        storedData = x;
    }

    // Function to get the value
    function get() public view returns (uint256) {
        return storedData;
    }
}


## License

This project is licensed under the MIT License.
