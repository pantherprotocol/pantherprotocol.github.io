## Overview

###The Problem

Every transaction tells a story, whether we like it or not. That’s the problem institutional
investors are having with Decentralized Finance (DeFi), a movement that leverages
decentralized networks to transform old financial products into trustless and transparent
protocols that run without intermediaries (Ong). Despite their growing interest in
participating, the ecosystem’s lack of core privacy functions makes it difficult to conduct
large trades effectively and confidentially.

Today, DeFi applications are predominantly built on the Ethereum (Buterin) protocol (with a
market cap of over $200B USD as of February 2021) (Concourse Open Community).
Ethereum transaction history and balances are public by default. This poses a series of
challenges for money managing professionals and individuals alike who both value financial
privacy. Even though transactions conducted between parties are pseudonymous, the protocol
does not offer strong privacy guarantees due to the public decentralized nature of the ledger.

Current trading environments are risky, and the existing solutions for privacy (Béres et al.)
are inadequate given the rapid growth of public, permissionless DeFi applications. There is
the concern of being front run (Guo et al.) when executing trades and transactions, whereby
systematic traders track what is about to happen on the Ethereum blockchain and use that
advance information to profit (Daian et al.). Even more damaging for the fungibility of
stablecoins (Moin et al.) and utility tokens acting as monetary instruments are the common
practices of onchain transaction graph analysis; this renders some tokens tainted and impairs
their fungibility and properties as sound money. At the same time, existing
privacy-preserving currencies are price volatile, which makes them unsuitable for commerce.
This lack of transactional obfuscation puts a limit on the sophistication of trades and
transactions that are practical to carry out on Ethereum and poses major trade-offs for all
institutions wishing to carry on financial services onchain.

While Bitcoin and Ethereum are popular as stores of value, neither offer privacy or price
stability. Zcash offers privacy but is not compatible with DeFi. Stablecoins and other assets
may offer price stability, but they also lack privacy and other key features.
Meanwhile, current Ethereum mixers, services that allow individuals to preserve their privacy
by mixing their coins with others (Piotrowska et al.), only allow the User to act in a
constrained manner. Because denominations are in fixed amounts transactions are
cumbersome and do not allow payments of any size. These services are also difficult to
operate, easy to make privacy-destroying mistakes with, and have challenging User
interfaces.

###The Solution

Out of this problem space Panther emerges as a privacy-preserving, 1:1 tokenization layer for
Ethereum-based assets, as well as those on other peerchains. Panther tackles a number of
privacy issues by anonymizing transactions from the payment’s sender and homogeneously
standardizing the construction of payments and interactions within DeFi ecosystems. It
focuses on five key areas: privacy network effects, increased transaction speeds, correct User
behavior, usability, and interoperability:

- Privacy Network Effects - Tokenizing underlying collateral and transacting with
zAssets drives powerful liquidity network effects. To reinforce these, Panther
promotes minting and discourages burning using fee incentives, e.g. 0.25% mint and
0.1% burn fees, paid in the native Panther Token. This leads to a growing pool of
zAssets. As the number of zAssets locked and transacted increases, the ability to
anonymize transactions grows stronger and the protocol becomes more efficient
encouraging widespread adoption.
- Increased Transaction Speeds - As different peerchains compete for transaction speed
superiority, zAsset Users can move assets from one protocol to another to meet their
needs for transaction finality and speeds.
- Correct User Behavior - Utilizing native assets on public peerchains exposes Users to
a number of deanonymizing threats, such as address reuse, conspicuous transaction
fee amounts and human errors. zAssets enforce correct behavior to maximise privacy
at a protocol level bringing simple User experience along with high levels of privacy.
This in turn encourages transaction volume and enhances privacy network effects.
- Usability - Minting zAssets on peerchains with well adopted standards, such as
Ethereum’s ERC20 standard, allows Users to interact with the growing DeFi
ecosystem and network of accepting exchanges, stores and financial institutions using
these standards.
- Interoperability - By issuing the native assets of one peerchain on another as zAssets
Users are able to benefit from the unique advantages of different protocols. Examples
of the types of optimizations brought by different protocols are transactions per
second, affordability, decentralization, and composability.