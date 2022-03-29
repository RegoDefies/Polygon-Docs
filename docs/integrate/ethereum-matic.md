---
id: ethereum-matic
title: Ethereum ↔ Polygon
keywords:
  - docs
  - matic
image: https://matic.network/banners/matic-network-16x9.png
description: Build your next blockchain app on Polygon.
---

# Ethereum ↔ Polygon

Plasma Secured Solution to transfer your assets from Ethereum to Polygon and vice-versa.

* Use [matic.js](https://github.com/maticnetwork/matic.js) to interact with the Polygon Plasma contracts.

### Flow

Here is the Flow with the deployement of your contracts on Polygon and Support for Ethereum↔Polygon.

1. User deploys ERC-20 token to Ethereum - XToken
2. Now share your contract address with [Polygon](https://t.me/joinchat/HkoSvlDKW0qKs\_kK4Ow0hQ). Here is an example request...

> Hello everyone, We are AwesomeDApp deployed on Polygon. Looking for a solution to transfer my assets from Ethereum to Polygon and vice-versa.\
> \
> A short description on my AwesomeDApp...\
> \
> Token\_Address on Ropsten-> "0x.."\
> Token\_Name-> "XToken"\
> Token\_Symbol-> "X"\
> Token\_Decimals-> "18"\
> \
> Requesting you to Map these tokens to Polygon Testnet Version.\
>

We will deploy a Child Contract for you on Polygon which can be flexible based on the requirements and Mapped to your tokens Ethereum ↔ Polygon.(Deployement on Polygon requires it native token Polygon, which can be deposit from Ethereum to Polygon or can be bought at Secondary Market Place.)

1. User can mint the Xtokens and Transfer on Ethereum. For example let's say 100XToken are mint and then transfer to other another account.
2. To avail these tokens on Polygon Chain, Call function deposit which will call for two transactions first approve and then depositERC20.
3. Now 100XTokens are available on Polygon Chain at the same address.
4. You can transfer 50 XToken from YourAddress to NewAddress. Again for transactions on Polygon similiar to ethereum, Polygon uses it own Native token.
5. If the users want to get back these Xtoken on Etheruem Chain, then call StartWithdraw which will withdraw from childTokenContract and Burn these tokens on Polygon Chain. To avoid any bad participation, A set of validation will take place. Once it is done the tokens will be available at Ethereum Chain.
6. Call processExits() to receive those tokens back to your EOA or your account address.
7. You should see the 50 XToken on the Ethereum mainnet at you Account Address.
