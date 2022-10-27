# Mood-Set-Dapp


Wrote a smart contract on Remix IDE and then connected it with injected metamask to deploy it to the goerli test Network.

Copied the deployed address of the goerli test network "0x52f2ab7fec6a861C8983E286fA5B87e2f521Ff46" in the Mood_Set.html file.

Then copied the ABI (Application Binary Interface) in the html file => 

* For setMood, we describe each field below:

name: setMood, self explanatory
type: function, self explanatory
outputs: should be [] because this does not return anything
stateMutability: This is nonpayable because this function does not accept Ether
inputs: this is an array of inputs to the function. Each object in the array should have internalType, name and type, and these are string, _mood and string respectively.


* For getMood, we describe each field below:

name: getMood, self explanatory
type: function, self explanatory
outputs: this has the same type as inputs in setMood. For internalType, name and type, this should be string, "", and string respectively
stateMutability: This is view because this is a view function
inputs: this has no arguments so this should be []


