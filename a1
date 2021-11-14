// SPDX-License-Identifier: GPL-3.0

pragma solidity >=0.7.0 <0.9.0;

/**
 * @title Storage
 * @dev Store & retrieve value in a variable
 */
contract Storage {

    string name;
    uint256 age;


    function setInfo(string memory _name,uint256 _age) public {
        name=_name;
        age=_age;
    }


    function getInfo() public view returns (string memory,uint256){
        return (name,age);
    }
}
