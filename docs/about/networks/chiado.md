---
---

# Chiado Testnet

Chiado is the official testnet of Gnosis. It has the same execution layer, and it is the first network transitioned to Proof of Stake, in preparation for the Gnosis mainnet merge.


## Native Tokens

### Fee token

Name: `Chiado xDai`

Icon: <a href="/img/tokens/chiado-xdai.png"><img src="/img/tokens/chiado-xdai.png" style={{width: '100px', height: '100px', display: 'inline'}} /></a>


### GNO Token

Name: `Gnosis Token`

Ticker: `GNO`

Chiado Contract Address: [0xf907903Be10FC3a885d331C4E225794436a34c9f](https://blockscout.chiadochain.net/address/0xf907903Be10FC3a885d331C4E225794436a34c9f)  


## Contracts

mGNO (SBCTokenProxy): [0xe68d8cD2b90bFd08d2Bcf5047A2d9850DA2deFDc](https://blockscout.chiadochain.net/address/0x0) 

[Deposit Contract address](https://github.com/gnosischain/consensus-deployment-ansible/blob/master/chiado/custom_config_data/config.yaml#L21) (SBCDepositContractProxy): [0xcD0904AcBF79F228E2c0d6D749cC72019D411995](https://blockscout.chiadochain.net/address/0xcD0904AcBF79F228E2c0d6D749cC72019D411995) 

- See [how to deposit](/node/validator-deposits#chiado-deposit) GNO in testnet

SBCWrapper = [0x5159F5ef48310EBdb7daD09A97f4376Bb207A7FE](https://blockscout.chiadochain.net/address/0x5159F5ef48310EBdb7daD09A97f4376Bb207A7FE) 

## Bridges with Goerli

# AMB Bridges TokenBridge ARBITRARY_MESSAGE

[Home] Chiado: 0x0 at block 0

[Foreign] Goerli: 0x0 at block 0

## OmniBridge AMB:

[Home] Chiado Bridge Mediator: 0x0

[Foreign] Goerli Bridge Mediator: 0x0

	-> Claim Token


### How to Use:

Go to:[ https://abi.hashex.org/](https://abi.hashex.org/)

Copy the ABI from [https://etherscan.io/address/0x0#code](https://etherscan.io/address/0x0#code)


## Config Files

[https://github.com/gnosischain/consensus-deployment-ansible/blob/master/chiado/README.md](https://github.com/gnosischain/consensus-deployment-ansible/blob/master/chiado/README.md)

Consensus layer files:



* [config.yaml](https://github.com/gnosischain/consensus-deployment-ansible/blob/master/chiado/custom_config_data/config.yaml)
* [genesis.ssz](https://github.com/gnosischain/consensus-deployment-ansible/blob/master/chiado/custom_config_data/genesis.ssz)
* [bootnodes_consensus.txt](https://github.com/gnosischain/consensus-deployment-ansible/blob/master/chiado/custom_config_data/bootnodes_consensus.txt)

Execution layer files:



* [nethermind_genesis.json](https://github.com/gnosischain/consensus-deployment-ansible/blob/master/chiado/custom_config_data/nethermind_genesis.json)
* [bootnodes_execution.txt](https://github.com/gnosischain/consensus-deployment-ansible/blob/master/chiado/custom_config_data/bootnodes_execution.txt)


## Client images

Remember you must run one execution client

[https://github.com/gnosischain/nethermind-client](https://github.com/gnosischain/nethermind-client) 

And one consensus client

[https://github.com/gnosischain/lighthouse-client](https://github.com/gnosischain/lighthouse-client) 

[https://github.com/gnosischain/prysm-client](https://github.com/gnosischain/prysm-client) 

[https://github.com/gnosischain/lodestar-client](https://github.com/gnosischain/lodestar-client) 

[https://github.com/gnosischain/teku-client](https://github.com/gnosischain/teku-client) 

