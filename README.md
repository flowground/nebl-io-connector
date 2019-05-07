# ![LOGO](logo.png) Neblio REST API Suite **flow**ground Connector

## Description

A generated **flow**ground connector for the Neblio REST API Suite API (version 1.2.1).

Generated from: https://api.apis.guru/v2/specs/nebl.io/1.2.1/swagger.json<br/>
Generated at: 2019-05-07T17:43:12+03:00

## API Description

APIs for Interacting with NTP1 Tokens & The Neblio Blockchain

## Authorization

This API does not require authorization.

## Actions

### Returns address object

> Returns NEBL address object containing information on a specific address

*Tags:* `Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns address balance in sats

> Returns NEBL address balance in satoshis

*Tags:* `Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns total received by address in sats

> Returns total NEBL received by address in satoshis

*Tags:* `Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns total sent by address in sats

> Returns total NEBL sent by address in satoshis

*Tags:* `Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns address unconfirmed balance in sats

> Returns NEBL address unconfirmed balance in satoshis

*Tags:* `Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns all UTXOs at a given address

> Returns information on each Unspent Transaction Output contained at an address

*Tags:* `Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns block hash of block

> Returns the block hash of a block at a given block index

*Tags:* `Insight`

#### Input Parameters
* `blockindex` - _required_ - Block Index

### Returns information regarding a Neblio block

> Returns blockchain data for a given block based upon the block hash

*Tags:* `Insight`

#### Input Parameters
* `blockhash` - _required_ - Block Hash

### Returns raw transaction hex

> Returns raw transaction hex representing a NEBL transaction

*Tags:* `Insight`

#### Input Parameters
* `txid` - _required_ - Transaction ID

### Utility API for calling several blockchain node functions

> Utility API for calling several blockchain node functions - getInfo, getDifficulty, getBestBlockHash, getLastBlockHash

*Tags:* `Insight`

#### Input Parameters
* `q` - _optional_ - Function to call, getInfo, getDifficulty, getBestBlockHash, or getLastBlockHash

### Get node sync status

> Returns information on the node's sync progress

*Tags:* `Insight`

### Broadcasts a signed raw transaction to the network (not NTP1 specific)

> Broadcasts a signed raw transaction to the network. If successful returns the txid of the broadcast trasnaction.

*Tags:* `Insight`

### Returns transaction object

> Returns NEBL transaction object representing a NEBL transaction

*Tags:* `Insight`

#### Input Parameters
* `txid` - _required_ - Transaction ID

### Get transactions by block or address

> Returns all transactions by block or address

*Tags:* `Insight`

#### Input Parameters
* `address` - _optional_ - Address
* `block` - _optional_ - Block Hash
* `pageNum` - _optional_ - Page number to display

### Information On a Neblio Address

> Returns both NEBL and NTP1 token UTXOs held at the given address.

*Tags:* `NTP1`

#### Input Parameters
* `address` - _required_ - Neblio Address to get information on.

### Broadcasts a signed raw transaction to the network

> Broadcasts a signed raw transaction to the network. If successful returns the txid of the broadcast trasnaction.

*Tags:* `NTP1`

### Builds a transaction that burns an NTP1 Token

> Builds an unsigned raw transaction that burns an NTP1 token on the Neblio blockchain.

*Tags:* `NTP1`

### Builds a transaction that issues a new NTP1 Token

> Builds an unsigned raw transaction that issues a new NTP1 token on the Neblio blockchain.

*Tags:* `NTP1`

### Builds a transaction that sends an NTP1 Token

> Builds an unsigned raw transaction that sends an NTP1 token on the Neblio blockchain.

*Tags:* `NTP1`

### Get Addresses Holding a Token

> Returns the the the addresses holding a token and how many tokens are held

*Tags:* `NTP1`

#### Input Parameters
* `tokenid` - _required_ - TokenId to request metadata for

### Returns the tokenId representing a token

> Translates a token symbol to a tokenId if a token exists with that symbol on the network

*Tags:* `NTP1`

#### Input Parameters
* `tokensymbol` - _required_ - Token symbol

### Get Issuance Metadata of Token

> Returns the metadata associated with a token at time of issuance.

*Tags:* `NTP1`

#### Input Parameters
* `tokenid` - _required_ - TokenId to request metadata for

### Get UTXO Metadata of Token

> Returns the metadata associated with a token for that specific utxo instead of the issuance transaction.

*Tags:* `NTP1`

#### Input Parameters
* `tokenid` - _required_ - TokenId to request metadata for
* `utxo` - _required_ - Specific UTXO to request metadata for

### Information On an NTP1 Transaction

> Returns detailed information regarding an NTP1 transaction.

*Tags:* `NTP1`

#### Input Parameters
* `txid` - _required_ - Neblio txid to get information on.

### Withdraws testnet NEBL to the specified address

> Withdraw testnet NEBL to your Neblio Testnet address. By default amount is 1500000000 or 15 NEBL and has a max of 50 NEBL. Only 2 withdrawals allowed per 24 hour period.

*Tags:* `Testnet-Faucet`

#### Input Parameters
* `address` - _required_ - Your Neblio Testnet Address
* `amount` - _optional_ - Amount of NEBL to withdrawal in satoshis

### Returns address object

> Returns NEBL address object containing information on a specific address

*Tags:* `Testnet-Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns address balance in sats

> Returns NEBL address balance in satoshis

*Tags:* `Testnet-Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns total received by address in sats

> Returns total NEBL received by address in satoshis

*Tags:* `Testnet-Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns total sent by address in sats

> Returns total NEBL sent by address in satoshis

*Tags:* `Testnet-Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns address unconfirmed balance in sats

> Returns NEBL address unconfirmed balance in satoshis

*Tags:* `Testnet-Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns all UTXOs at a given address

> Returns information on each Unspent Transaction Output contained at an address

*Tags:* `Testnet-Insight`

#### Input Parameters
* `address` - _required_ - Address

### Returns block hash of block

> Returns the block hash of a block at a given block index

*Tags:* `Testnet-Insight`

#### Input Parameters
* `blockindex` - _required_ - Block Index

### Returns information regarding a Neblio block

> Returns blockchain data for a given block based upon the block hash

*Tags:* `Testnet-Insight`

#### Input Parameters
* `blockhash` - _required_ - Block Hash

### Returns raw transaction hex

> Returns raw transaction hex representing a NEBL transaction

*Tags:* `Testnet-Insight`

#### Input Parameters
* `txid` - _required_ - Transaction ID

### Utility API for calling several blockchain node functions

> Utility API for calling several blockchain node functions - getInfo, getDifficulty, getBestBlockHash, getLastBlockHash

*Tags:* `Testnet-Insight`

#### Input Parameters
* `q` - _optional_ - Function to call, getInfo, getDifficulty, getBestBlockHash, or getLastBlockHash

### Get node sync status

> Returns information on the node's sync progress

*Tags:* `Testnet-Insight`

### Broadcasts a signed raw transaction to the network (not NTP1 specific)

> Broadcasts a signed raw transaction to the network. If successful returns the txid of the broadcast trasnaction.

*Tags:* `Testnet-Insight`

### Returns transaction object

> Returns NEBL transaction object representing a NEBL transaction

*Tags:* `Testnet-Insight`

#### Input Parameters
* `txid` - _required_ - Transaction ID

### Get transactions by block or address

> Returns all transactions by block or address

*Tags:* `Testnet-Insight`

#### Input Parameters
* `address` - _optional_ - Address
* `block` - _optional_ - Block Hash
* `pageNum` - _optional_ - Page number to display

### Information On a Neblio Address

> Returns both NEBL and NTP1 token UTXOs held at the given address.

*Tags:* `Testnet-NTP1`

#### Input Parameters
* `address` - _required_ - Neblio Address to get information on.

### Broadcasts a signed raw transaction to the network

> Broadcasts a signed raw transaction to the network. If successful returns the txid of the broadcast trasnaction.

*Tags:* `Testnet-NTP1`

### Builds a transaction that burns an NTP1 Token

> Builds an unsigned raw transaction that burns an NTP1 token on the Neblio blockchain.

*Tags:* `Testnet-NTP1`

### Builds a transaction that issues a new NTP1 Token

> Builds an unsigned raw transaction that issues a new NTP1 token on the Neblio blockchain.

*Tags:* `Testnet-NTP1`

### Builds a transaction that sends an NTP1 Token

> Builds an unsigned raw transaction that sends an NTP1 token on the Neblio blockchain.

*Tags:* `Testnet-NTP1`

### Get Addresses Holding a Token

> Returns the the the addresses holding a token and how many tokens are held

*Tags:* `Testnet-NTP1`

#### Input Parameters
* `tokenid` - _required_ - TokenId to request metadata for

### Returns the tokenId representing a token

> Translates a token symbol to a tokenId if a token exists with that symbol on the network

*Tags:* `Testnet-NTP1`

#### Input Parameters
* `tokensymbol` - _required_ - Token symbol

### Get Issuance Metadata of Token

> Returns the metadata associated with a token at time of issuance.

*Tags:* `Testnet-NTP1`

#### Input Parameters
* `tokenid` - _required_ - TokenId to request metadata for

### Get UTXO Metadata of Token

> Returns the metadata associated with a token for that specific utxo instead of the issuance transaction.

*Tags:* `Testnet-NTP1`

#### Input Parameters
* `tokenid` - _required_ - TokenId to request metadata for
* `utxo` - _required_ - Specific UTXO to request metadata for

### Information On an NTP1 Transaction

> Returns detailed information regarding an NTP1 transaction.

*Tags:* `Testnet-NTP1`

#### Input Parameters
* `txid` - _required_ - Neblio txid to get information on.

## License

**flow**ground :- Telekom iPaaS / nebl-io-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
