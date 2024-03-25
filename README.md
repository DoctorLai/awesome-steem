# awesome-steem
![](https://steemyy.com/images/steem-crypto.png)
> A curated list of awesome Steem resources.

- [awesome-steem](#awesome-steem)
  - [Steem source code](#steem-source-code)
  - [Frontends](#frontends)
    - [Generic](#generic)
  - [Block Explorers](#block-explorers)
  - [Documentation](#documentation)
  - [Communication channels](#communication-channels)
  - [Introduction](#introduction)
  - [Infrastructure](#infrastructure)
  - [SDKs](#sdks)
  - [Tools / Utilities](#tools--utilities)
  - [dApps](#dapps)
  - [DeFi](#defi)
    - [Exchanges that support STEEM](#exchanges-that-support-steem)
    - [Swap Tools](#swap-tools)
  - [Services](#services)
    - [Steem DAO](#steem-dao)
    - [Tokens](#tokens)
    - [Steem Bots](#steem-bots)
      - [Comment Bots](#comment-bots)
  - [Contribute](#contribute)

## Steem source code

Steem node implementation.

- [Steem on Github repository](https://github.com/steemit/steem) - This is where most of the development takes place.

## Frontends

### Generic

- [Steemit](https://steemit.com) - This is the official frontend that is run by Steemit Inc. ([code](https://github.com/steemit/condenser))
- [Upvu](http://upvu.org/)
- [SteemCN](https://steemcn.xyz) - By [@ericet](https://steemit.com/@ericet)
- [Boylikegirl](https://boylikegirl.club/community) - By [@boylikegirl](https://steemit.com/@boylikegirl)
- [WhereIn](http://www.wherein.io/) - By [@iguazi123](https://steemit.com/@iguazi123)

## Block Explorers
- [Steem Block Explorer](https://steemblockexplorer.com/)
- [SteemDB](http://steemdb.io/) - This is owned by [Steemit Inc](https://steem.com).
- [SteemWorld](https://steemworld.org/block/61000000) - This is owned by [@steemchiller](https://steemit.com/@steemchiller)
- [SteemYY](https://steemyy.com/block.php) - This is owned by [@justyy](https://steemit.com/@justyy)
- [Ecosynthesizer](https://ecosynthesizer.com/steem/blk/82824811) - This is owned by [@symbionts](https://steemit.com/@symbionts)
- [SteemScan](https://steemscan.com/block/82974704) - This is owned by [@future.witness](https://steemit.com/@future.witness)

## Documentation
- [Steem Developer Portal](https://developers.steem.io)

## Communication channels
- [Discord](https://discord.gg/zegqKxMkez) - Steem Discord Group.
- [Twitter](https://twitter.com/steemit) - @steemit on Twitter.

## Introduction

*Documents & videos about Steem*

- [Developer Portal](https://developers.steem.io/) - The developer portal of Steem.
- [Steem Glossary](https://developers.steem.io/glossary/#glossary-chain-basics) - Understanding the common terms used by the Steem blockchain.

## Infrastructure

*The Steem blockchain infrastructure*

- [Steem](https://steem.io) - Fast, scalable, powerful blockchain for Web3.0, ([code](https://github.com/steemit/steem)).
- [hivemind](https://github.com/steemit/hivemind) - Developer-friendly microservice powering social networks on the Steem blockchain.
- [Steem Backup Data Server](https://files.steem.fans/) - by [@ety001](https://steemit.com/@ety001)
- RPC/Seed Nodes
  - [Seed/RPC Nodes Testing](https://ecosynthesizer.com/steem/nodes) by [@symbionts](https://steemit.com/@symbionts)
  - [Steem Seed Nodes Check](https://steemworld.org/seed-nodes-check) by [@steemchiller](https://steemit.com/@steemchiller)
  - [Steem API Node Status](https://steemyy.com/node-status.php) by [@justyy](https://steemit.com/@justyy)
  - [Load Balancer Node](https://steem.senior.workers.dev/) by [@justyy](https://steemit.com/@justyy)

## SDKs

*SDKs for common languages*

- JavaScript
  - [Steem-js](https://www.npmjs.com/package/@steemit/steem-js) - Official JavaScript library for Steem blockchain.
- Python
  - [Steem-python](https://github.com/steemit/steem-python) - Official Python library for Steem blockchain.
  - [Steemhd](https://github.com/maiyude2018/steemhd) - This package allows generating mnemonics, seeds, private/public keys and addresses for different types of cryptocurrencies. By [@maiyude](https://steemit.com/@maiyude)
- Java
  - [SteemJ](https://github.com/marvin-we/steem-java-api-wrapper) - Java Wrapper by [@dez1337](https://steemit.com/@dez1337), however the project seems not maintained any more.

## Tools / Utilities

*Useful tools/utilities when building with Steem*

- All in One (sites that have many features)
    - [SteemWorld](https://steemworld.org) - by [@steemchiller](https://steemit.com/@steemchiller)
    - [SteemYY](https://steemyy.com) - by [@justyy](https://steemit.com/@justyy)
    - [SteemCryptic](https://www.steemcryptic.me/) by [@starlord28](https://steemit.com/@starlord28)
- Account Recovery
  - [SteemWorld](https://steemworld.org/account-recovery) - by [@steemchiller](https://steemit.com/@steemchiller)
- Authentication / Wallet
  - [Steem Keychain](https://github.com/DoctorLai/steem-keychain) - A wallet browser extension for the Steem blockchain and cryptocurrency.
  - [Whale Vault](https://chromewebstore.google.com/detail/whalevault/hcoigoaekhfajcoingnngmfjdidhmdon) - This chrome extension supports multiple chains including STEEM.
  - [Steem Keys](https://steemyy.com/keys/) - View the Steem Active/Posting/Owner Keys by [@justyy](https://steemit.com/@justyy)
  - [Steemit Wallet](https://steemitwallet.com) - Official Steemit Wallet, ([code](https://github.com/steemit/wallet)).
  - [steem.vip](https://vip.steem.vip) - Steem wallet by [@maiyude](https://steemit.com/@maiyude). ([code](https://github.com/maiyude2018/steem-web-wallet))
- Data Service / API
  - [SDS API Reference](https://sds1.steemworld.org/) - by [@steemchiller](https://steemit.com/@steemchiller)
- Witness
  - [Tutorial: How to Deploy a Steem Witness Node By Docker](https://steemit.com/witness/@ety001/how-to-deploy-a-steem-witness-node-by-docker) by [@ety001](https://steemit.com/@ety001)
  - [Witness List](https://steemitwallet.com/~witnesses) - Steem Inc.
  - [Witness List](https://ecosynthesizer.com/steem/witnesses) - Witness List by [@symbionts](https://steemit.com/@symbionts).
  - [Witness List](https://steemyy.com/witness-ranking/) - Witness List by [@justyy](https://steemit.com/@justyy).
  - [Witness List](https://steemscan.com/witnesses) - Witness List by [@future.witness](https://steemit.com/@future.witness).
  - [Witness List](https://steemworld.org/witnesses) - Witness List by [@steemchiller](https://steemit.com/@steemchiller).
  - [Witness Schedule](https://steemworld.org/witness-schedule) - Witness Block Producing Scheduler by [@steemchiller](https://steemit.com/@steemchiller).
  - [Witness Price Feed Publish](https://github.com/DoctorLai/pricefeed) - by [@justyy](https://steemit.com/@justyy)
- Account Registrations
  - [List of Account Signup Tools](https://signup.steemcn.xyz/) - by [@ericet](https://steemit.com/@ericet). This lists a few available account signup tools.
  - [SteemIt](https://signup.steemit.com/) Official Account Sign Up by Steemit.
  - [SteemYY](https://steemyy.com/reg.php) Free Account Registration by [@justyy](https://steemit.com/@justyy)
  - [SteemHunt](https://steemhunt.com/sign-up) Free Account Registration by [@steemhunt](https://steemit.com/@steemhunt)
  - [Steem Account Creator](https://steemworld.org/account-creator) - Requires RC or 3 STEEM, by [@steemchiller](https://steemit.com/@steemchiller)
- Search
  - [Search Posts on Steemit](https://moecki.online/) - By [@moecki](https://steemit.com/@moecki)

## dApps

*Some cool dApps built with Steem*

- Videos
  - [dTube](https://d.tube/)

- Social
  - [Onlyfun](https://app.onlyfun.city/) - Social Platform,Nft and Finance.

- TODO

## DeFi

### Exchanges that support STEEM
*Make sure you put the memo when sending funds to the exchanges*

- [HTX](https://justyy.com/out/htx)
- [Poloniex](https://justyy.com/out/poloniex)
- [MEXC](https://justyy.com/out/mexc)
- [Binance](https://justyy.com/out/binance)
- [Ionomy](https://justyy.com/out/ionomy)

### Swap Tools
*Swap STEEM to other coins*

- [Steem to TRX](https://steemyy.com/steem2trx.php)
- [Steem to USDT](https://steemyy.com/steem2usdt.php)
- [Steem to BTS](https://steemyy.com/steem2bts.php)
- [Steem to ETH](https://steemyy.com/steem2eth.php)
- [Steem to SOL](https://steemyy.com/steem2sol.php)

## Services
*Online tools and APIs to simplify development.*

Here is the [STEEM dapps and services list](https://steemit.vercel.app/svcs) by [@joviansummer](https://steemit.com/@joviansummer)

### Steem DAO
*Steem DAO is dedicated to improve the Steem platform*

- [Decentralized Steem Fund](https://developers.steem.io/services/#services-dhf) - Propose and vote for projects that improves Steem and promote its growth. [See current proposals](https://steemitwallet.com/proposals)

### Tokens
- [Peanut Community](https://app.nutbox.io/#/sub-community/home/?id=0xc54C1F0E7A75Fb405038891E316c973D26Bf0125) by [@iguazi123](https://steemit.com/@iguazi123)
- [Wormhole3: A Staking DAO based on the PoS (including DPoS, NPoS, etc.) blockchain](https://alpha.wormhole3.io/community-detail/cab1b9a9ee34) by [@iguazi123](https://steemit.com/@iguazi123)

### Steem Bots

#### Comment Bots
You can invoke bots when posting comments:
- *!ask PROMPT*: [invokes ChatGPT 3.5](https://helloacm.com/integrating-chatgpt-prompt-ai-to-steem-blockchain/), by [@justyy](https://steemit.com/@justyy)
- *!thumbup*: summons a Random Giphy, by [@justyy](https://steemit.com/@justyy)
- *!info*: displays current STEEM information, by [@justyy](https://steemit.com/@justyy)

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
