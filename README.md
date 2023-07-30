# ETH-AVAX-Module-4

# Degen Gaming ERC20 Token

This is a smart contract for the Degen Gaming ERC20 token deployed on the Avalanche network. The contract provides functionality for minting new tokens, transferring tokens, redeeming tokens for in-game items, checking token balances, and burning tokens.

## Contract Details

- Token Name: Degen Token
- Token Symbol: DEGEN

## Functions

`1) Minting new tokens`

The owner of the contract can mint new tokens by calling the `mint` function, specifying the recipient's address and the desired token amount.

 `2)Transferring tokens`

Players can transfer their tokens to others by calling the `transfer` function, specifying the recipient's address and the token amount to be transferred.

`3) Redeeming tokens`

Players can redeem their tokens for in-game items in the in-game store by calling the `redeem` function and specifying the token amount to be redeemed. Additional logic for item redemption should be implemented in the contract.

`4)Checking token balance`

Players can check their token balance at any time by calling the `balanceOf` function and providing their account address.

`5) Burning tokens`

Anyone can burn their own tokens by calling the `burn` function and specifying the amount of tokens to be burned.

## Deployment

The contract has been deployed on the Avalanche network for Degen Gaming.
<pre>
For the deployment on your own pc follow the steps: 
1)First write the contract on the remix.
2)Add a network account on Metamask.
3)Make sure that the required avax is present in your account.
4)When the metamask has enough avax then select the environment as "Injected Provider" in remix.
5)So finally at the last step deploy it.
6)To verify copy the address of deployment and paste it into "Snowtrace Fauji Testnet".
</pre>
