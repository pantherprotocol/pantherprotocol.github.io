##Panther Vaults

Panther Vault are autonomous, zero knowledge (Goldwasser et al.) self-custodial smart
contracts that allow Gatekeepers to act as decentralized custodians for collateral assets
created on any single peerchain. As long as a Gatekeeper has membership to the federation
they can freely mint and burn zAssets of any type.

Signing of mint and burn transactions are managed by Panther Vaults in a 2-of-2
multisignature scheme consisting of the:
1) Gatekeeper; and
2) Panther Vault.

By default, Gatekeepers sign burn/redeem requests with the protocol which will auto-sign
provided the Gatekeepers federation membership is valid and they are burning zAssets at a
1:1 ratio for the collateral. In the event a Gatekeeper behaves maliciously and refuses to
release collateral assets, Panther Token token holders can vote to revoke the Gatekeepers
membership. At the same time, zAsset holders can burn their assets through another
Gatekeeper to access the collateral. In this way, control of onchain collateral always remains
with Panther token holders.