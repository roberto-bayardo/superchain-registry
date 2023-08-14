# superchain-registry

The Superchain Registry repository hosts Superchain-configuration data in a minimal human-readable form.
This includes mainnet and testnet Superchain targets, and their respective member chains.

Other configuration, such as contract-permissions and `SystemConfig` parameters are hosted and governed onchain.

The superchain configs are made available in minimal form, to embed in OP-Stack software.
Full deployment artifacts and genesis-states can be derived from the minimal form
using the reference [`op-chain-ops`] tooling.

## Go Module

Superchain configs can be imported as Go-module:
```
go get github.com/ethereum-optimism/superchain-registry/superchain@latest
```
See [`op-chain-ops`] for config tooling and
 for smart-contract bindings.

[`op-chain-ops`]: https://github.com/ethereum-optimism/optimism/tree/develop/op-chain-ops
[`op-bindings`]: https://github.com/ethereum-optimism/optimism/tree/develop/op-bindings

## License

MIT License, see [`LICENSE` file](./LICENSE).