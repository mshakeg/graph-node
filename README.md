# graph-node

Quick start for running a graph-node against a Hedera Local, Testnet or Mainnet JSON RPC Relay

`.local` starts up a graph-node that points to the hedera local-node json rpc relay

`.testnet` starts up a graph-node that points to a testnet json rpc relay(either by hashio or arkhia)

`.mainnet` starts up a graph-node that points to a mainnet json rpc relay(either by hashio or arkhia)

Note: Postgres should ideally be run in a managed service e.g. AWS RDS and not in docker as done here