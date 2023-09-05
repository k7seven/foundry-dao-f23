# Foundry DAO Governance

This is a section of the Cyfrin Foundry Solidity Course.

*[⭐️ (6:05:45) | Lesson 14 | DAOs & Governance](https://www.youtube.com/watch?v=wUjYK5gwNZs&t=21945s)*

*Please note: ERC20 based voting is not always recommended, and I encourage you to explore other forms of governance like reputation based or "skin-in-the-game" based.*

[One of my favorite articles on money-based voting being bad](https://vitalik.ca/general/2018/03/28/plutocracy.html)

- [Foundry DAO Governance](#foundry-dao-governance)
- [Getting Started](#getting-started)
  - [Requirements](#requirements)
  - [Quickstart](#quickstart)
- [Usage](#usage)
  - [Test](#test)
  - [Estimate gas](#estimate-gas)
- [Formatting](#formatting)
- [Thank you!](#thank-you)

# Getting Started

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you did it right if you can run `git --version` and you see a response like `git version x.x.x`
- [foundry](https://getfoundry.sh/)
  - You'll know you did it right if you can run `forge --version` and you see a response like `forge 0.2.0 (816e00b 2023-03-16T00:05:26.396218Z)`


## Quickstart

```
git clone https://github.com/k7seven/foundry-dao-f23
cd foundry-dao-f23
forge install
forge build
```

# Usage

## Test

```
forge test
```

## Estimate gas

You can estimate how much gas things cost by running:

```
forge snapshot
```

And you'll see and output file called `.gas-snapshot`


# Formatting


To run code formatting:
```
forge fmt
```


# Thank you!

k77

[![k77 Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ksevenseven_eth)
