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
- Application
  + App <=> FG <=> Peer <=> channel <=> network
  
## Relationship
- Organization
  + Peer
  + Chaincode
  + Ordering service nodes

## sequence
- ClientA - UserA - CAA - PeerA



## Fabric Gateway
- from v2.4
- installed default on each peer

