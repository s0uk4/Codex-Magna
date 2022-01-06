# What is Celestia?

A protocol that aims to optimize for [[data availability]] in the creation of a base chain that can probabilistically verify the data contained in a block of transactions. Other networks would connect in the form of rollups in order to post their validity proofs, which would then be settled on the base-chain's consensus.

In the long run, something like Celestia could act as the base consensus layer for rollups that are using IBC to communicate, leading us to a shared security model ideal for chains deploying in the [[Cosmos]] ecosystem, but not limited to this ecosystem alone.

## Notes:

(why not just call it Faze, or Dimension, or whatever? Celestia is so overused)

In an ideal situation, a protocol like [[Evmos]] could offer a high degree of availability to Ethereum-based rollups by utilzing Celestia as the shared security base layer, therefore decreasing the data load on the parent rollup.

Originally LazyLedger
- exploring fraud proofs, then realized that there was a data availaibility layer that was needed.
- - mechanism is about scaling ethereum
	- looked at different consensus engines
		- ended on [[Tendermint]] because the consensus engine made the most sense
	- Celestia can deploy any consensus engine
- data availability is a problem that all rollups face
	- John and Mustafa coming from [[Ethereum]] side
What is data availability?


## Related to:
[[Cosmos]],[[Evmos]],[[protocol]],[[blockchain]]