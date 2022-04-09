// SPDX-License-Identifier: GPL-3.0

pragma solidity >= 0.7.0 < 0.9.0;

contract LearnMapping {

    

    mapping(address => uint) save;

    function pairAddress(uint n, address a) public {

        save[a] = n;
        
    }

    function viewPair(address _a) public view returns(uint) {

        return save[_a];

    }
    
}

contract NestedMapping {

    mapping(address => mapping(address => uint)) Nest;

    function PairNest(address owner, address spender, uint i) public {

        Nest[owner][spender] = i;
    }

    function viewNest(address owner, address spender) public view returns(uint) {

        return Nest[owner][spender];

    }

}
