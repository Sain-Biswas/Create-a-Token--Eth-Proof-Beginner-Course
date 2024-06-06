# Project Submission Eth Proof Beginner Course

First we  have created public variables that store the details about the coins Token Name, Token Abbrv., Total Supply as tokenName, tokenAbbrv, totalSupply respectively.
    
Second we have created a public mapping of addresses to balances (address => uint) called balances.
    
Then we have created a mint function that takes two parameters: an address and a value. 
The function then increases the total supply by that number and increases the balance of the “sender” address by that amount

At last we have created a burn function, which works the opposite of the mint function, as it destroys tokens. 
It takes an address and value just like the mint functions. It then deduct the value from the total supply and from the balance of the “sender”.
The function also have conditionals to make sure the balance of "sender" is greater than or equal to the amount that is supposed to be burned.
