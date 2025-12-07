# Sultan Network

**High-performance Layer 1 blockchain with 64K TPS and zero gas fees.**

## Quick Links

| Resource | Link |
|----------|------|
| 🌐 Website | [sltn.io](https://sltn.io) |
| 📡 RPC Endpoint | `https://rpc.sltn.io` |
| 📥 Node Download | [sultan-node](https://github.com/Wollnbergen/DOCS/releases/latest/download/sultan-node) |

## Documentation

- [**Validator Guide**](VALIDATOR.md) - Become a validator and earn 26.67% APY
- [**RPC Server**](RPC_SERVER.md) - API endpoints and methods
- [**Rust SDK**](SDK.rs) - Build applications on Sultan

## Network Stats

- **Throughput**: 64,000 TPS (8-shard architecture)
- **Block Time**: ~2 seconds
- **Gas Fees**: $0.00 (zero gas)
- **Staking APY**: 26.67%
- **Validators**: 15+ globally distributed

## Run a Validator

```bash
# Download
wget https://github.com/Wollnbergen/DOCS/releases/latest/download/sultan-node
chmod +x sultan-node

# Run
./sultan-node \
  --validator \
  --validator-address YourName \
  --validator-stake 10000 \
  --enable-p2p \
  --bootstrap-peers /dns4/rpc.sltn.io/tcp/26656
```

See [VALIDATOR.md](VALIDATOR.md) for complete setup instructions.

## Architecture

- **Consensus**: Custom PoS with instant finality
- **Networking**: libp2p with gossipsub
- **Cryptography**: Post-quantum ready (Dilithium3)
- **Storage**: RocksDB with sharded state

---

*Sultan Network - Fast, Free, Decentralized*
