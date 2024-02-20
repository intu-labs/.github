
<h1 align="center">
  <br>
  <p align="center">
<img src="Door_INTU_Grad_Trans.png" alt="drawing" width="200" style="margin:0 auto; display:block;"/>
</p>
  <br>
  INTU  <br>
</h1>
<h4 align="center">Get Users On-chain: Simple, Flexible, Powerful Tooling for Web3 User Accounts </h4>
<p align="center">
  <a href="#boom-key-features">Key Features</a> •
  <a href="#zap-use-cases">Use Cases</a> •
  <a href="#wave-introduction-and-faq">Introduction & FAQ</a> •
  <a href="#rocket-getting-started">Getting Started</a> •
  <a href="#cd-sdk">SDKs</a> •
  <a href="#question-support">Support</a>
</p>

## :boom: Key Features
* Broad compatibility with dApps and Blockchain Networks
* No APIs or service dependencies - :100: Decentralized by Default
* Dynamic Account Configurations
* Flexible Custody, Signing, and Account Recovery
* Customizable Architecture
* Decentralized, Leaderless, Trustless Account Generation

## :zap: Use Cases
* Simplified On-chain Onboarding: One-click, gasless mobile onboarding without subscriptions or services

* Progressive Self-Custody: Get your users into your application quickly, and evolve their account to self-custody when they're ready

* Familiar User Authentication with Web2 Methods: Include Social Log-ins, Biometrics, and e-mail as means of user authentication and authorization

* Policy Enforcement with Client Authority: End-user initialized actions but allow your application to enforce policies like KYC, spending limits, proof-of-humanity, etc

## :rocket: Getting Started
There's a few ways to get started with INTU's tooling. 
### SDK Getting Started Guide
Looking to install the SDK and dive right in? Look no further! 

:beginner: [Getting Started Guide](https://docs.intu.xyz/guides/quickstart-overview.html)

### Template: One-click No-Wallet Onboarding
A Head-start to getting users on-chain and in your application with nothing more than an e-mail, social log-in, passkey, or biometric auth. Start testing in under 10 minutes, and configure to meet your application's needs.

:repeat_one: [Rapid User Onboarding](https://docs.intu.xyz/guides/rapid-customer-onboard.html)

### Hybrid Custody with Co-signing
Run your own INTU Automated Co-Signer node to enable hybrid custody, policy enforcement, account recovery, and more. Migrate users from your own service to full self-custody when they're ready. 

:robot:[Automated Co-Signer](https://github.com/w3-key/intu_node_signer)

## :cd: SDK
*Links to SDK Public Repos here*

## :wave: Introduction and FAQ
INTU is Next-gen accounts for all of Web3: Static public addressing with dynamic authentication + authorization. 

Dynamic accounts evolve over time to meet user needs, without transferring assets between accounts, or updating smart contracts.

**INTU is not a service. You will not pay a subscription. You do not need an API key. Your product, and your end-user accounts will always work!**

As far as blockchains are concerned, they're verifying standard signatures (ECDSA) for an Externally-owned Account (EOA). This means it works on all EVM chains (and some others, too!) and with any smart contract account or application. 

However, behind the scenes you now have:
- Fully Decentralized Account Generation - No Private Key to lose, ever.
- Dynamic Private Keys across several participants or factors. Share ownership, transfer ownership, and reset your "password" for all of Web3. Add, Remove, Revoke, and Rotate shares as often as needed.
- Threshold Signatures with custom parameters

### What is INTU?
INTU's SDK handles all of the advanced cryptography, communication, and storage necessary for account creation and signing. 

INTU uses Smart Contracts (on any EVM chain) as default channel of communication, data storage, and ultimate source of truth.

INTU is compatible with common Web3 libraries, such as Ethers.js, and works with most wallets, such as Metamask. It can also be configured to work without a wallet.

When creating an INTU account, the SDK returns the new Public Address.

When using an INTU account, the SDK returns a signed transaction or message, which can then be broadcast to any destination network. 

The INTU SDK can be built directly into web-based, desktop, or mobile applications, with or without a wallet application. It can also be deployed for back-end services in Node.JS

INTU is not a wallet, not a dApp, not a Smart Contract Account, not a UI and not a service. INTU works with Account Abstraction (4337), custody services, and most other frameworks.

### What do I do with INTU?
:sparkles:GET USERS ON-CHAIN!:sparkles:



### What Can I Configure?
- Quantity of Participants
- Signing Thresholds
- Communication Channels
- Data Storage
- Hybrid Architecture Configurations
- Convenience vs Security vs Usability 

### How does this actually work?
**Decentralized Account Generation**: Secure Multiparty Computation (SMPC) + Verified Secret Sharing (VSS), built for asynchronous and public communication. Allows for safer account creation without private networks or hardware.

**Threshold Signatures**: Requires a pre-determined minimum of participants or factors to create valid signatures, such as 2-of-3. By default, these are ECDSA signatures, but can also support BLS and EDDSA. The user experience is similar to 2-Factor Authentication or 

**Encryption for On-chain Data Storage and Communication**: All communications and data storage are encrypted. INTU has devised a novel encryption scheme enabling the creation of ephemeral encryption keys with forward secrecy, without requiring end-users to store data or remember an additional password. 

##  :question: Support
INTU is always available to chat! We're happy to discuss building with our SDK, custom configurations, and use cases. 

Please visit our discord: 🏮 [_https://discord.gg/sc9SjTewph_](https://discord.gg/sc9SjTewph) 🏮

Or send us a quick note: :email: <dev@intu.xyz> :email:

### :book: Documentation

More detailed explanations of all things INTU can be found on our [documentation page](https://docs.intu.xyz).

### :tada: Demo
*link to demo video coming soon*

### :meat_on_bone: Whitepaper :fries:
If you're looking to understand the meat-and-potatoes of what's actually going on, check out our [whitepaper](https://docs.intu.xyz/in-depth/introduction-to-deoas/whitepaper.html).

### :memo: License
The MIT License (MIT)

Copyright (c) 2024 W3 CPI, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
