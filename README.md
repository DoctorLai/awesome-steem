# awesome-steem
![](https://steemyy.com/images/steem-crypto.png)
> A curated list of awesome Steem resources. The latest version is on [https://doctorlai.github.io/awesome-steem/](https://doctorlai.github.io/awesome-steem/)

- [awesome-steem](#awesome-steem)
  - [Steem source code](#steem-source-code)
  - [Frontends](#frontends)
    - [Generic](#generic)
  - [Block Explorers](#block-explorers)
  - [Common Operations for Steemians](#common-operations-for-steemians)
    - [Delegate Steem Power](#delegate-steem-power)
    - [Vote or Proxy a Witness](#vote-or-proxy-a-witness)
  - [Documentation](#documentation)
  - [Communication channels](#communication-channels)
  - [Introduction](#introduction)
  - [Infrastructure](#infrastructure)
  - [SDKs](#sdks)
  - [Tools / Utilities](#tools--utilities)
  - [dApps](#dapps)
  - [DeFi](#defi)
    - [Exchanges that support STEEM](#exchanges-that-support-steem)
    - [Exchanges that support SBD](#exchanges-that-support-sbd)
    - [Rent Steem Power](#rent-steem-power)
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
- [Steem Deep Wiki](https://deepwiki.com/steemit/steem) - AI Generated Documentation.

## Frontends

### Generic

- [Steemit](https://steemit.com) - This is the official frontend that is run by Steemit Inc. ([code](https://github.com/steemit/condenser))
- [Steemit Dev](https://steemitdev.com) - This is the testing/development/alpha frontend that is run by Steemit Inc.
- [Upvu](http://upvu.org/)
- [SteemPro](https://steempro.com) - By [@faisalamin](https://steemit.com/@faisalamin)
- [SteemCN](https://steemcn.xyz) - By [@ericet](https://steemit.com/@ericet)
- [Boylikegirl](https://boylikegirl.club/community) - By [@boylikegirl](https://steemit.com/@boylikegirl)
- [WhereIn](http://www.wherein.io/) - By [@iguazi123](https://steemit.com/@iguazi123)
- [SteemX.org](https://steemx.org/) - By [@bountyking5](https://steemit.com/@bountyking5)

## Block Explorers
- [Steem Block Explorer](https://steemblockexplorer.com/) - by [@penguinpablo](https://steemit.com/@penguinpablo)
- [SteemDB](http://steemdb.io/) - This is owned by [Steemit Inc](https://steem.com).
- [SteemWorld](https://steemworld.org/block/61000000) - This is owned by [@steemchiller](https://steemit.com/@steemchiller)
- [SteemYY](https://steemyy.com/block.php) - This is owned by [@justyy](https://steemit.com/@justyy)
- [Ecosynthesizer](https://ecosynthesizer.com/steem/blk/82824811) - This is owned by [@symbionts](https://steemit.com/@symbionts)
- [SteemScan](https://steemscan.com/block/82974704) - This is owned by [@future.witness](https://steemit.com/@future.witness)
- [Steem Explorer](https://joticajulian.github.io/steemexplorer/#/explorer) - This is open sourced and owned by [@jga](https://steemit.com/utopian-io/@jga/steem-explorer-based-on-steem-js-1539631316061)

## Common Operations for Steemians
### Delegate Steem Power
You can delegate Steem Power to a steem account using:
- [SteemYY Delegate Form](https://steemyy.com/sp-delegate-form/)
- [SteemIt Wallet](https://steemitwallet.com/@justyy)

### Vote or Proxy a Witness
You can vote or proxy a Steem Witness:
- [SteemYY Witness Voting Tool](https://steemyy.com/witness-voting/)
- [Steemit](https://steemit.com/~witnesses)

## Documentation
- [Steem Developer Portal](https://developers.steem.io)

## Communication channels
- [Discord](https://discord.gg/zegqKxMkez) - Steem Discord Group.
- [Twitter](https://twitter.com/steemit) - @steemit on Twitter.

## Introduction

*Documents & videos about Steem*

- [Developer Portal](https://developers.steem.io/) - The developer portal of Steem.
- [Steem Glossary](https://developers.steem.io/glossary/#glossary-chain-basics) - Understanding the common terms used by the Steem blockchain.
- [Steem Documentation](https://steemit.github.io/docs/) - The "Official" Documentation for the Steem Blockchain

## Infrastructure

*The Steem blockchain infrastructure*

- [Steem](https://steem.io) - Fast, scalable, powerful blockchain for Web3.0, ([code](https://github.com/steemit/steem)).
- [hivemind](https://github.com/steemit/hivemind) - Developer-friendly microservice powering social networks on the Steem blockchain. [Deep Wiki](https://deepwiki.com/steemit/hivemind)
- [Steem Backup Data Server](https://files.steem.fans/) - by [@ety001](https://steemit.com/@ety001)
- RPC/Seed Nodes:
  - [List of Seed Nodes](https://github.com/DoctorLai/simple-steem-docker/blob/main/steem-seed-nodes.txt)
  - [List of RPC Nodes](https://github.com/DoctorLai/simple-steem-docker/blob/main/steem-rpc-nodes.txt)
  - [Seed/RPC Nodes Testing](https://ecosynthesizer.com/steem/nodes) by [@symbionts](https://steemit.com/@symbionts)
  - [Steem Seed Nodes Check](https://steemworld.org/seed-nodes-check) by [@steemchiller](https://steemit.com/@steemchiller)
  - [Steem API Node Status](https://steemyy.com/node-status.php) by [@justyy](https://steemit.com/@justyy)
  - [Load Balancer Node](https://steemit.com/hive-102132/@justyy/open-sourcing-steem-load-balancer-and-introduce-steem-justyy-com) by [@justyy](https://steemit.com/@justyy)

## SDKs

*SDKs for common languages*

- JavaScript
  - [Steem-js](https://www.npmjs.com/package/@steemit/steem-js) - Official JavaScript library for Steem blockchain. You can test the library using [here](https://steemyy.com/steemjs/)
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
    - [SteemBlocks](https://steemblocks.com/) by [@dhaka.witness](https://steemit.com/@dhaka.witness)
    - [Steem Fans](https://steem.cool/) by [@ety001](https://steemit.com/@ety001)
- Account Recovery
  - [SteemIt](https://steemitwallet.com/recover_account_step_1)
  - [SteemWorld](https://steemworld.org/account-recovery) - by [@steemchiller](https://steemit.com/@steemchiller)
- Authentication / Wallet
  - [Steem Keychain](https://github.com/faisalamin9696/steem-keychain-extension) - A wallet browser extension for the Steem blockchain and cryptocurrency.
  - [Whale Vault](https://chromewebstore.google.com/detail/whalevault/hcoigoaekhfajcoingnngmfjdidhmdon) - This chrome extension supports multiple chains including STEEM.
  - [Steem Keys](https://steemyy.com/keys/) - View the Steem Active/Posting/Owner Keys by [@justyy](https://steemit.com/@justyy)
  - [Steemit Wallet](https://steemitwallet.com) - Official Steemit Wallet, ([code](https://github.com/steemit/wallet)) - [DeepWiki](https://deepwiki.com/steemit/wallet).
  - [steem.vip](https://vip.steem.vip) - Steem wallet by [@maiyude](https://steemit.com/@maiyude). ([code](https://github.com/maiyude2018/steem-web-wallet))
- Data Service / API
  - [SDS API Reference](https://sds1.steemworld.org/) - by [@steemchiller](https://steemit.com/@steemchiller)
- Witness
  - [Tutorial: How to Deploy a Steem Witness Node By Docker](https://steemit.com/witness/@ety001/how-to-deploy-a-steem-witness-node-by-docker) by [@ety001](https://steemit.com/@ety001)
  - [Witness Schedule](https://steemworld.org/witness-schedule) - Witness Block Producing Scheduler by [@steemchiller](https://steemit.com/@steemchiller).
  - [Witness Price Feed Publish](https://github.com/DoctorLai/pricefeed) - by [@justyy](https://steemit.com/@justyy)
  - [Simple Steem Docker Utility](https://github.com/DoctorLai/simple-steem-docker/) - by [@justyy](https://steemit.com/@justyy)
  - [Auto Switch Steem Witness Node](https://github.com/DoctorLai/SteemWitnessAutoSwitch) - by [@justyy](https://steemit.com/@justyy)
  - [Witness Monitor Map](https://joticajulian.github.io/steemexplorer/#/map) - This is open sourced and owned by [@jga](https://steemit.com/utopian-io/@jga/steem-explorer-based-on-steem-js-1539631316061)
  - Ranking Table
    - [Witness List](https://steemitwallet.com/~witnesses) - Steem Inc.
    - [Witness List](https://ecosynthesizer.com/steem/witnesses) - Witness List by [@symbionts](https://steemit.com/@symbionts).
    - [Witness List](https://steemyy.com/witness-ranking/) - Witness List by [@justyy](https://steemit.com/@justyy).
    - [Witness List](https://steemscan.com/witnesses) - Witness List by [@future.witness](https://steemit.com/@future.witness).
    - [Witness List](https://steemworld.org/witnesses) - Witness List by [@steemchiller](https://steemit.com/@steemchiller).
    - [Witnesses @ Ecosynthesizer](https://ecosynthesizer.com/steem/witnesses) by [@symbionts](https://steemit.com/@symbionts)
    - [Witnesses @ Steem Explorer](https://joticajulian.github.io/steemexplorer/#/witnesses) - This is open sourced and owned by [@jga](https://steemit.com/utopian-io/@jga/steem-explorer-based-on-steem-js-1539631316061)
- Account Registrations
  - [List of Account Signup Tools](https://signup.steemcn.xyz/) - by [@ericet](https://steemit.com/@ericet). This lists a few available account signup tools.
  - [SteemIt](https://signup.steemit.com/) Official Account Sign Up by Steemit.
  - [SteemYY](https://steemyy.com/reg.php) Free Account Registration by [@justyy](https://steemit.com/@justyy)
  - [SteemHunt](https://steemhunt.com/sign-up) Free Account Registration by [@steemhunt](https://steemit.com/@steemhunt)
  - [Steem Account Creator](https://steemworld.org/account-creator) - Requires RC or 3 STEEM, by [@steemchiller](https://steemit.com/@steemchiller)
  - [A Pussfi Project Steem-id](https://steem-id.com/) by [Puss Meme Team](https://puss.meme/)
  - [Account Creation Tools by @symbionts](https://joinblocks.org/steem) by [@symbionts](https://steemit.com/@symbionts)
  - [A service for creating Steem accounts with automatic VESTS delegation (accounts must be claimed before)](https://github.com/FutureShockco/steem-account-creation) by [@hightouch](https://steemit.com/@hightouch)
- Search
  - [Search Posts on Steemit](https://moecki.online/) - By [@moecki](https://steemit.com/@moecki)
  - [SteemHub](https://steemhub.tech/): A tool focused on statistics visualization. It helps users track and analyze performance through interactive charts and graphs. More info: [Steemit Post](https://steemit.com/steem-dev/@kafio/tool-for-getting-stats-the-first-tool-under-steemhub)

## dApps

*Some cool dApps built with Steem*

- Videos
  - [dTube](https://d.tube/)

- Social
  - [Onlyfun](https://app.onlyfun.city/) - Social Platform, Nft and Finance.
  - [SteemChat](https://steemchat.org) - Steem Chat (IM) by [@stmpak.wit](https://steemit.com/@stmpak.wit) witness.

- GameFi
  - [Steem Retro Games](https://steem-retrogames.com/) by [@time.foundation](https://steemit.com/@time.foundation) and [@italygame](https://steemit.com/@italygame).
  - [Steem Memory Game](https://memory-game.steemhub.tech/) by [@kafio](https://steemit.com/kafio)

## Chrome Extensions
- [Steem Keychain](https://github.com/faisalamin9696/steem-keychain-extension) - A wallet browser extension for the Steem blockchain and cryptocurrency.
- [Whale Vault](https://chromewebstore.google.com/detail/whalevault/hcoigoaekhfajcoingnngmfjdidhmdon) - This chrome extension supports multiple chains including STEEM.
- [Steemit Blog Formatter](https://chromewebstore.google.com/detail/steemit-blog-formatter/mokepjeindhmgelkmdgimghehgodpemg): This Chrome extension helps you format your Steemit posts like a pro, making your content cleaner and more professional. More info: [Steemit Post](https://steemit.com/steem-dev/@kafio/steemit-blog-formatter-format-your-posts-like-a-pro)
- [Steemit Notification Saver](https://steemit.com/freewriters/@kafio/saving-important-notifications-with-a-chrome-extension-steemit-notification-saver): A Chrome extension for saving important Steemit notifications, so you never miss anything crucial.

## DeFi
You can swap STEEM to SBD or vice versa in [STEEM internal market (zero fees)](https://steemitwallet.com/market).

### Puss Meme
[$PUSS](https://puss.meme) Is The First MemeCoin Of Steemit Platform On Tron Blockchain. In our digital world, fun, trust, security, and efficiency are vital. 
- [Whitepaper](https://puss.meme/whitepaper.pdf)
- [Token](https://sunpump.meme/token/TX5eXdf8458bZ77fk8xdvUgiQmC3L93iv7)

### Exchanges that support STEEM
*Make sure you put the memo when sending funds to the exchanges*

- [HTX](https://steemyy.com/out/htx): Spot: STEEM/USDT
- [Poloniex](https://steemyy.com/out/poloniex): Spot: STEEM/USDT, STEEM/BTC, STEEM/TRX
- [MEXC](https://steemyy.com/out/mexc): Spot: STEEM/USDT
- [Binance](https://steemyy.com/out/binance): Spot: STEEM/BTC, STEEM/USDT, STEEM/ETH, STEEM/USDC
- [Probit](https://steemyy.com/out/probit): Spot: STEEM/USDT, STEEM/BTC

### Exchanges that support SBD
- [HTX](https://steemyy.com/out/htx)

### Rent Steem Power
You can rent/lease Steem Power:

- [steemyy](https://steemyy.com/rent-sp.php)

### Swap Tools
*Swap STEEM or SBD to other coins/tokens.*

- [Tron(TRX/USDT/USDD) to STEEM](https://steemyy.com/tron2steem.php)
- [Steem/SBD to SUI](https://steemyy.com/steem2sui.php)
- [Steem/SBD to TRX](https://steemyy.com/steem2trx.php)
- [Steem/SBD to USDT](https://steemyy.com/steem2usdt.php)
- [Steem/SBD to BTS](https://steemyy.com/steem2bts.php)
- [Steem/SBD to ETH](https://steemyy.com/steem2eth.php)
- [Steem/SBD to SOL](https://steemyy.com/steem2sol.php)

## Services
*Online tools and APIs to simplify development.*

Here is the [STEEM dapps and services list](https://steemit.vercel.app/svcs) by [@joviansummer](https://steemit.com/@joviansummer)

### Steem DAO
*Steem DAO is dedicated to improve the Steem platform*

- [Decentralized Steem Fund](https://developers.steem.io/services/#services-dhf) - Propose and vote for projects that improves Steem and promote its growth. [See current proposals](https://steemitwallet.com/proposals)
- [DAO SteemWorld](https://steemworld.org/proposals)
- [DAO Proposals](https://ecosynthesizer.com/steem/proposals) by [@symbionts](https://steemit.com/@symbionts)
- [DAO Proposals](https://joticajulian.github.io/steemexplorer/#/proposals) - This is open sourced and owned by [@jga](https://steemit.com/utopian-io/@jga/steem-explorer-based-on-steem-js-1539631316061)

### Tokens
- [Peanut Community](https://app.nutbox.io/#/sub-community/home/?id=0xc54C1F0E7A75Fb405038891E316c973D26Bf0125) by [@iguazi123](https://steemit.com/@iguazi123)
- [Wormhole3: A Staking DAO based on the PoS (including DPoS, NPoS, etc.) blockchain](https://alpha.wormhole3.io/community-detail/cab1b9a9ee34) by [@iguazi123](https://steemit.com/@iguazi123)

### Steem Bots

#### Comment Bots
You can invoke bots when posting comments:
- *!ask PROMPT*: [invokes ChatGPT](https://helloacm.com/integrating-chatgpt-prompt-ai-to-steem-blockchain/) or [Grok](https://helloacm.com/chatgpt-writes-a-python-script-to-interact-with-grok-llm-from-x-ai-free-25-credit/), by [@justyy](https://steemit.com/@justyy)
- *!thumbup*: summons a Random Giphy, by [@justyy](https://steemit.com/@justyy)
- *!info*: displays current STEEM information, by [@justyy](https://steemit.com/@justyy)
- *!price*: displays something like [this](https://steemit.com/blog/@justyy/syk6df#@witnesstools/20250628t090101387z).

## Social Network
- [Facebook](https://www.facebook.com/steemnetwork)
- [X: steemit](https://x.com/steemit)
- [X: SteemNetwork](https://x.com/SteemNetwork)

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
