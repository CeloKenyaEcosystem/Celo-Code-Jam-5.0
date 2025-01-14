# Celo Code Jam 5.0 & 5.1

#### Celo Code Jam Polpular Theme Tracks

The Code Jam Theme Tracks are specific categories or themes for participants to focus on while participating in the Code Jam event. Each track represents a different area of interest or challenge that participants can choose to tackle with their projects. The three tracks mentioned are as follows:

- __DeFi Track:__
 This track focuses on decentralized finance (DeFi) projects. Participants can create innovative solutions that leverage blockchain
  - Build decentralized web applications facilitating within DeFi.
    - Develop innovative solutions for lending, borrowing, and trading digital assets.

## List of Project Ideas

| Topic dApp Ideas                 | Description                                                                                                                                                              |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| __DeFi Lending Protocols__       | A lending protocol with built-in reputation scoring, allowing borrowers with a good track record to access lower interest rates.                                         |
|                                  | A decentralized prediction market where users can lend and borrow crypto based on the outcome of real-world events.                                                      |
| __Privacy-focused Solutions__    |                                                                                                                                                                          |
|                                  | A privacy-preserving DeFi wallet that allows users to conduct transactions without revealing their identities on the blockchain.                                         |
|                                  | A dApp for mixing cryptocurrencies to obfuscate transaction trails and enhance user privacy.                                                                             |
| __Cross-Chain Integration__      |                                                                                                                                                                          |
|                                  | A dApp for swapping tokens between different blockchains with a user-friendly interface and competitive rates.                                                           |
|                                  | A decentralized marketplace where users can buy and sell NFTs minted on various blockchains.                                                                             |
| __Automated Market Makers__      |                                                                                                                                                                          |
|                                  | An AMM with dynamic fees that adjust based on market volatility, ensuring optimal liquidity provision for users.                                                         |
|                                  | An AMM specializing in specific asset classes, like real estate or art, with customized algorithms to facilitate efficient trading.                                      |
| __Oracle Networks and Data Feeds__ |                                                                                                                                                                        |
|                                  | A decentralized oracle network that aggregates data from multiple sources to ensure high accuracy and tamper-proof data feeds for smart contracts.                       |
|                                  | A specialized oracle network providing real-time data on weather conditions for use in DeFi applications related to agriculture or insurance.                            |
| __Carbon-Neutral DeFi__          |                                                                                                                                                                          |
|                                  | DeFi platform that offsets the carbon footprint.                                                                                                                         |
|                                  | A gamified dApp that incentivizes users to adopt environmentally friendly DeFi practices through rewards and recognition systems.                                        |
| __Gamified DeFi Education Platform__ |                                                                                                                                                                      |
|                                  | Educate users about DeFi concepts through interactive games and challenges with real rewards.                                                                            |
| __Decentralized Escrow__         |                                                                                                                                                                          |
|                                  | Secure Escrow platform for facilitating trustless transactions between buyers and sellers.                                                                               |
| __Loyalty management systems__   | Build decentralized loyalty management systems for businesses.                                                                                                           |
| __Reward distribution system__   | Implement reward distribution systems for various use cases.                                                                                                             |
| __Gift cards__                   | Create and manage gift cards on the blockchain.                                                                                                                          |
| __Utility payments__             | Enable utility payments using blockchain technology integrated with existing systems.                                                                                    |
| __Online shop with loyalty feature__ | Build an online shop with integrated loyalty features.                                                                                                               |
| __Subscription models using Superfluid__ |Implement subscription models leveraging Superfluid technology.                                                                                                   |
  
## Code Jam Repo Process

 1. Fork this repo
    - Press the Fork button
 2. Create project branch
 3. Make your changes within new branch!
     - Copy the folder named __Project_Name__
     - Rename the copied folder with your project name
     - Modify project details within your project folder __Readme.md__
     - Project Name
     - Brief Description
     - Team members & roles
     - Code Jam track - __Should be DeFi. We will be adding more soon in our next Code Jam__
     - Project details
     - Demonstartion video _(*Required)_
     - Requirements _(*Required)_
     - Instructions to build & test _(*Required)_

 4. Add, commit, and push the changes

- Add the files you've changed and commit them with a descriptive message.

 5. Submit your pull request _(*Required)_
    - Submit to the maintainers for approval. Head over to the original repositories Pull Requests tab, you should see an automatic suggestion from GitHub to create a pull request from your new branch.
    - Utilize your project name as the title for your initial pull Requests
    - Provide a brief project description within the pull request comment

___Congrats, your officially a Celo Code Jam participant!___

## Submission Criteria

- Project must be DeFi related or any of the Build With Celo Tracks
- A verified smart contract deployed on Celo Mainnet
- Mobile-First
- Personal Finance focused
- A working prototype (demo video or deployed)
- A public GitHub repository
- Must be built for MiniPay

## Developer tools and resources

This section contains information about some of the key tools and resources that will help developers start building applications on Celo.

For a comprehensive list of resources and information, review [Celo Docs.](https://docs.celo.org/)

### Tutorials

- [Tutorial - Celo Developer Blog](https://docs.celo.org/blog)

### TOOLS

#### Boilerplates

- [celo-composer](https://github.com/celo-org/celo-composer#celo-composer)
  - Celo Composer allows you to quickly build, deploy, and iterate on decentralized applications using Celo. It provides a number of frameworks, examples, and Celo specific functionality to help you get started with your next dApp.

#### SDKs

- [ContractKit](https://docs.celo.org/developer/contractkit#what-is-contractkit)
  - Javascript package of Celo blockchain utilities
  - Manage connections to the Celo blockchain, accounts, send transactions, interact with smart contracts, etc.
  - A set of wrappers around the core protocol smart contracts to easily connect with contracts related to governance, validators, on-chain exchange, etc.
  - Includes [web3.js](https://web3js.readthedocs.io/en/v1.2.4/)
- [Celo Ethers.js Wrapper](https://github.com/celo-tools/celo-ethers-wrapper) (experimental)
  - A minimal wrapper to make [ethers.js](https://docs.ethers.io/v5/) compatible with the Celo network
- [use-react](https://github.com/celo-org/react-celo)
  - The easiest way to access Celo in your React applications 🔥. react-celo is a React hook for managing access to Celo with a built-in headless modal system for connecting to your users wallet of choice.
  - Now your DApp can be made available to everyone in the Celo ecosystem, from Valora users to self custodied Ledger users.
  - By default react-celo is styled so that you can drop it into your application and go, however it's fully customisable so you can maintain a consistent UX throughout your application.
- [DappKit](https://docs.celo.org/developer-guide/dappkit)
  - Easily connect to the [Valora](http://valoraapp.com/) wallet with your React Native mobile application
  - Valora manages user account, private keys and transaction signing, so you can focus on building your dapp
  - Learn more and see the code with the [Dappkit truffle box](https://github.com/critesjosh/celo-dappkit)
- [Python SDK](https://github.com/blaize-tech/celo-sdk-py)
- [Java SDK](https://github.com/blaize-tech/celo-sdk-java)
  - [Android with Java SDK](https://github.com/bcamacho/celo-android-java-sdk-test-example)
- [iOS SDK](https://github.com/heymateag/celoiossdk)

#### Infrastructure

- [Valora](https://valoraapp.com/) provides a clean, intuitive UI where users can send transactions and interact with smart contracts
- [Forno](https://stackedit.io/developer-guide/forno)
- Node access service so you can connect your dapp to the Celo blockchain without having to run node infrastructure
- [ODIS](https://stackedit.io/developer-resources/contractkit/odis.md)
- Oblivious decentralized identity service
- Lightweight identity layer that makes it easy to send cryptocurrency to a phone number
- Blockscout block explorers
- [Alfajores testnet](http://alfajores-blockscout.celo-testnet.org/) & [mainnet](http://explorer.celo.org/)
- [Stats.celo.org](http://stats.celo.org/) to check network activity and health

#### Networks

- [Alfajores Testnet](https://docs.celo.org/getting-started/alfajores-testnet)
- [Faucet](https://celo.org/developers/faucet) for free testnet CELO and cUSD
- [Forno](https://docs.celo.org/developer-guide/forno) supports connections to alfajores
- Requires Alfajores Celo wallet for mobile device testing (please request, <support@clabs.co>)
- [Baklava testnet](https://docs.celo.org/getting-started/baklava-testnet) for validators and testing protocol changes

#### Ethereum Tools

- Similarities between Celo and Ethereum means you can use many of the most popular Ethereum developer tools.
- Celo supports the EVM, so tools for writing smart contracts in Solidity (or any language that compiles to EVM bytecode) are compatible with Celo
- ERC20, NFT (ERC721) and other smart contract interface standards are supported, see [Celo for Ethereum Developers](https://docs.celo.org/developer-guide/celo-for-eth-devs)
- [Truffle](https://www.trufflesuite.com/)
- [OpenZeppelin](https://openzeppelin.com/)
- [Remix](https://remix.ethereum.org/)

#### Web wallets

- [celowallet.app](https://celowallet.app/)
- [Celo Terminal](https://github.com/zviadm/celoterminal/)

#### Community

- Telegram [Celo](), [Celo Kenya Developers]()
- Twitter  [Celo](), [Celo Kenya](), [Celo Nigeria](), [Celo Uganda]()
- Join our [Discord](https://chat.celo.org/)
- [Discourse Forum](https://forum.celo.org/)

We used the following Judging criteria to tally the points and award the winners of the Celo Code Jam

### The Judging Criteria Used

<ul>
  <li>Technology - Engineering skills demonstrated, and the quality code</li>
  <li>Design - Attention to aesthetics, interaction, and user interface</li>
  <li>Impact - A solution that meets a customer’s need has the potential to be a sustainable, impactful solution.</li>
  <li>Presentation - The clarity of written and oral presentation</li>
  <li>Inspiration - How much we love and are excited about the idea</li>
</ul>

Judges were asked to provide feedback on each category separately as well as give an overall score out of 100.
