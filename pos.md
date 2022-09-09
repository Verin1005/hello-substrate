https://substrate.stackexchange.com/questions/368/how-to-change-consensus-engine-from-poa-to-pos/3372#3372

https://github.com/kaichaosun/subdev.cn
https://github.com/kaichaosun/substrate-stencil

To make a PoS chain based on node template, you need to make these changes step by step,

use BABE to produce blocks, since Aura is for test purpose or permissioned network.
use staking, session, authorship, offences, utility, im-online pallets to enable staking, rewards and punish operations.
use governance, treasury, democracy, membership, election pallets to make your own governance process, this is not required if you don't need onchain governance.
initialize your chain spec to include your bootnodes, genesis validators and so on.
use BabeCallFilter to open/close functions as you launch goes different stage.
similarly, use governance and sudo to enable functions slowly to reduce risks.
You could use my practice by following these recent commits.