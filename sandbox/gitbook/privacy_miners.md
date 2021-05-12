##Privacy Miners

Privacy Miners are nodes running on Panther peerchains which provide zAsset liquidity to
Panther Pools in exchange for Panther Token paid in transaction fees and through rewards
granted by the Panther DAO. The privacy that Panther brings to each peerchain’s DeFi
ecosystem is directly proportional with the volume flowing through Panther Pools; in other
words, the greater the transaction volume from unique addresses, the larger the anonymity
set. As the early network is launched, the role of Privacy Miners will be critical to bootstrap
liquidity in Panther Pools. As the protocol scales organic transaction volume, it is expected
that privacy mining rewards will diminish naturally. At the same time, as volume increases
the cost of privacy decreases, creating a virtuous cycle.

In Panther there is a lower bound privacy threshold below which transactions will not be sent
on the network as they are not sufficiently obfuscated. In order to ensure minimum privacy
thresholds are met, transaction fees adjust dynamically. When there is not enough pool
liquidity, the transaction fees increase to encourage more deposits. The opposite happens
when there is excess liquidity in the pool.

In addition to the function of providing liquidity to Panther Pools, Privacy Piners also provide
relayer services. Relayer nodes services involve providing the native gas token, such as ETH
on the Ethereum peerchain, to newly created proxy addresses to pay for the transaction fees
connected with sending zAssets on that chain. This service protects the sender from
deanonymization. Privacy Miners are chosen by Verifiable Random Function (VRF) (Dodis
and Yampolskiy) from all available miners on that peerchain and rewards are paid
proportionally to the zAssets locked for mining across the peerchain.