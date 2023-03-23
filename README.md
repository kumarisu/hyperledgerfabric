# hyperledgerfabric
- Network: is formed & managed by the multiple organizations that contribute resources to it.
- Channel: a mechenism by which components within a Fabric blockchain network communicate and transact privately.
  + include peer nodes, orderer nodes and applications
  + chanel ~ group
  + A peer may belong to serveral channels
  + Other definition: logic structure is formed by a collection of physical peers
    => Channel = pathway for communications between specific applications and peers.
- User: registered & enrolled with the organization's CA, then received back neccessary cryptographic material
- Peer: = network connection points for organizations
  + One peer join at least 1 channel
  + host instances of ledger & chaincode
  + in conjunction with orderers to sensure that the ledger is kept consistent and current on every peer in a channel
- Application
  + App <=> FG <=> Peer <=> channel <=> network
  
- Chaincode: 
    + is written using the chaincode APIs
    + is run to query or update the ledger
- Fabric gateway service: Default on peer from HF 2.4
  + Gateway SDKs (v1.x)
    - Support:
      + submit tx proposals (invokes chaincode)
      + request endorsement
      + receive events
      + forward endorsed txs to ordering service
  + Client Apps use SDK v2.3 => continue to run on v2.4
  + 

## Relationship
- Organization
  + Peer
    + Ledger  
    + Chaincode
  + Ordering service nodes

## sequence
- ClientA - UserA - CAA - PeerA



## Fabric Gateway
- from v2.4
- installed default on each peer

