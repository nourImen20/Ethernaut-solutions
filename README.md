# Ethernaut-solutions
[Ethernaut CTF](https://ethernaut.openzeppelin.com/) solutions.

## Challenges
- [Level0. Hello Ethernaut](#level0-hello-ethernaut) 
- [Level01. Fallback](#level01-fallback) 
- [Level02. Fallout](#level02-fallout) 

    ...

# Level0. Hello Ethernaut
tx id : ` 0x4feb85ad00cda1d0976ebdb50ba46bf4df0d59912361be03d84f62c4ab778494 `

[Instance Contract](./challenges/Level0/Instance.sol)

# Level01. Fallback
tx id : ` 0x7c4be34befe92d23b13b2c5250a80ae90e302314df9470e4b1fec580a651eed9 `

*method:* 
1. to claim the contract's ownership: `contribute()` function, sendTransaction.
2. to withdraw all the contract's balance: `withdraw()` function.

[Fallback Contract](./challenges/Level1/Fallback.sol)

# Level02. Fallout
tx id : ` 0x122e64358aeb68ae6cb9d33a5bcae9f30bf7a47b8f3a3f8d11a2bfebe64cca62 `

*method:* to claim the contract's ownership: use `Fal1out()` function.

[Fallout Contract](./challenges/Level2/Fallout.sol)