# SOLES-Notary

SOLES blockchain notary platform for secure data storage and heirarchically permissioned data access

SOLES-Notary Project is a blockchain node implementation and set of tools for securely storing any type of data with permissioned access layers. Secure or encrypted data can be notarized, with full protocol for authentication layers and efficient encrypted data access by any number of key-holders. SOLES-Notary is based on the Tendermint Message Server Protocol and uses a Delegated Proof of Stake consensus protocol to add to verfify new blocks in a blockchain. SOLES-Notary is built around a model that includes an additional DHT data-storage mechanism alongside the nodes. We recommend a model with a (data-efficient) two-keyholder data encryption scheme for privata data, where any outside user can request data access from one or both keyholders, but SOLES-Notary can support encryption schemes with n keyholders.
