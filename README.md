# HALCON_TYPE_OF_FUNCTIONS_MODULE_3
// SPDX-License-Identifier: MIT
pragma solidity 0.8.20;

import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/ERC20.sol";

contract Halcon is ERC20 {

    constructor() ERC20("DIVINE", "DIV") {}

    function mint(uint256 token) public {
        _mint(msg.sender, token);
    }


This is the whole functionality within the code itself and the generalization of how the code will run.

### Authors

Halcon, Divine Louielyn. 
8216021@ntc.edu.ph
