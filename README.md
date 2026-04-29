# NestedIf.sol
NestedIf.sol
pragma solidity ^0.8.20;
contract NestedIf {
    function test(uint x) public pure returns(string memory){
        if(x>10){
            if(x>20) return "Large";
            return "Medium";
        }
        return "Small";
    }
}
