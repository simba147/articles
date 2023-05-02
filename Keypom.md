#  Streamlining Onboarding with Account Abstraction on NEAR Protocol (KEYPOM)

The onboarding process for Web3 applications has traditionally been riddled with friction points, making it difficult for users to navigate the space. Account abstraction aims to alleviate these challenges by simplifying the user experience and concealing complex blockchain operations. In this article, we introduce Keypom, a project leveraging NEAR Protocol's account model to provide seamless onboarding through account abstraction.


# Understanding Account Abstraction

Account abstraction is a concept that aims to simplify user interaction with Web3 applications by masking complex operations such as key management, token handling, and contract interactions. In essence, it reduces the friction points users face when onboarding to Web3 applications.


# NEAR Protocol's Account Model

NEAR Protocol's account model is unique in that it offers built-in support for [named accounts](https://docs.near.org/concepts/basics/accounts/model), enabling a more Web2-like experience. With NEAR, users can have a username, multiple "passwords" (keys), and even change their keys, similar to Web2 authentication. NEAR's wallet is inherently a smart contract, providing native support for features that other blockchains require additional infrastructure projects to achieve.


# Introducing Keypom

[Keypom](keypom.xyz) is a project that leverages NEAR's account model and linkdrops to provide a frictionless onboarding experience. The Keypom Protocol and toolkit consist of four main components:



* [Web App](https://keypom.xyz/): Create tickets, NEAR & fungible token drops, and NFT drops with no code directly on the website.
* [TypeScript React + Parcel Boilerplate App](https://github.com/keypom/keypom-airfoil): An open-source boilerplate for customizing the front end.
* [Javascript SDK](https://github.com/keypom/keypom-js): An SDK that abstracts the complexity of using the NEAR API JS SDK for interfacing with the[ v2.keypom.near ](https://nearblocks.io/address/v2.keypom.near#contract)contract directly.
* [Smart Contract](https://github.com/keypom/keypom): A forkable Rust contract that allows for the addition of customized functionality or inclusion into your own contract namespace.

Keypom is also pushing for [NEP-452](https://github.com/near/NEPs/pull/452), a standard for [linkdrops](https://github.com/near-examples/linkdrop-proxy) that aims to standardize the creation and claiming of linkdrops for universal compatibility with wallets and dApps across the ecosystem.

Moreover, Keypom has a budding developer ecosystem of people building applications/tooling leveraging account abstraction. Examples include [Linkdrop Plus ](https://near.org/cuongdcdev.near/widget/linkdrop_plus)(a decentralized front end for no code custom NFT linkdrops), [Sharddog](https://shard.dog/) (a bot resistant telegram service), and [OnboardDAO](http://onboarddao.org) (a telegram enabled DAO onboarding bot). Join the [Keypom Builder group here](http://nearbuilders.com/tg-keypom).


# The Power of Keypom

Keypom offers a range of unique features:



* [Function call drops](https://docs.keypom.xyz/docs/next/Tutorials/Basics/fc-drops): A function that takes an array of items, each representing a potential drop with an associated probability value. This simulates a random process, deciding if each item is dropped based on its probability. This is useful for implementing random item drops in games or reward systems in apps.
* [Trial accounts](https://docs.keypom.xyz/docs/next/TrialAccounts/introduction): Gift cards for dApps. Keypom allows for the creation of trial accounts that can be deleted and reclaimed if the user doesn't claim them within a specified time. This functions like traditional gift cards, specifying which stores (smart contracts and specific functions) can be accessed.
* [NFT & FT Drops](https://docs.keypom.xyz/docs/next/Tutorials/Basics/nft-drops): Keypom supports NFT & Fungible tokendrops, making it easier for users to claim a named account and a NFT and/or fungible token in the same action.
* NEAR airdrops: distribute any amount of NEAR to accounts regardless of drop type.


# Conclusion

Keypom is revolutionizing the onboarding process for Web3 applications by leveraging account abstraction and NEAR Protocol's account model. Its toolkit provides a seamless onboarding experience, making it easier for users to interact with Web3 applications and fostering mainstream adoption of blockchain technology.

Source: [https://www.youtube.com/watch?v=oHj-GjFi6g4](https://www.youtube.com/watch?v=oHj-GjFi6g4) 
