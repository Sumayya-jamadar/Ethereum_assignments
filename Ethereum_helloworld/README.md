# Smart Contract Hello World

This repository presents practices about:

- Setup a blockchain.
- Develop Ethereum smart contract.
- Deploy the contract and test it.

## Quick Demo


### steps to execute this project
commands:-
>cd smart_contract_helloworld/
>truffle build
>truffle migrate

>truffle console
>var hw;
>Main.deployed().then(function(d){hw=d;});
> hw.setUserName("summi")
>hw.printMessage.call()
