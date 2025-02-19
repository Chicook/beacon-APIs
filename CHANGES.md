# Recent Changes


## Development Version

These endpoints have been added or updated since the last release.

There are likely to be descriptions etc outside of the list below, but new query parameters, changes to headers, new endpoints should be listed.

| Endpoint                                                                                                                                    | [Lighthouse](https://github.com/sigp/lighthouse) | [Lodestar](https://github.com/ChainSafe/lodestar) | [Nimbus](https://github.com/status-im/nimbus-eth2) | [Prysm](https://github.com/prysmaticlabs/prysm) | [Teku](https://github.com/ConsenSys/teku) |
|---------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|---------------------------------------------------|----------------------------------------------------|-------------------------------------------------|-------------------------------------------|
| [#317](https://github.com/ethereum/beacon-APIs/pull/317) `POST /eth/v2/beacon/blocks` and `POST /eth/v2/beacon/blinded_blocks`              |                                                  |                                                   |                                                    |                                                 |                                           |
| [#316](https://github.com/ethereum/beacon-APIs/pull/316) `/eth/v2/debug/beacon/states` added `historical_summaries` to response             |                                                  |                                                   |                                                    |                                                 |                                           |
| [#289](https://github.com/ethereum/beacon-APIs/pull/289) `/eth/v2/debug/beacon/states` added `deneb` state to response                      |                                                  |                                                   |                                                    |                                                 |                                           |
| [#289](https://github.com/ethereum/beacon-APIs/pull/289) `/eth/v1/beacon/blinded_blocks/{block_id}` added `deneb` blinded block to response |                                                  |                                                   |                                                    |                                                 |                                           |
| [#289](https://github.com/ethereum/beacon-APIs/pull/289) `/eth/v2/beacon/blocks/{block_id}` added `deneb` block to response                 |                                                  |                                                   |                                                    |                                                 |                                           |
| [#289](https://github.com/ethereum/beacon-APIs/pull/289) `/eth/v1/validator/blinded_blocks/{slot}` added `deneb` blinded block              |                                                  |                                                   |                                                    |                                                 |                                           |
| [#289](https://github.com/ethereum/beacon-APIs/pull/289) `/eth/v1/validator/blocks/{slot}` added `deneb` block                              |                                                  |                                                   |                                                    |                                                 |                                           |

The Following are no longer in the Standard API, removed since the latest version.

| Endpoint                                                                                                 | [Lighthouse](https://github.com/sigp/lighthouse) | [Lodestar](https://github.com/ChainSafe/lodestar) | [Nimbus](https://github.com/status-im/nimbus-eth2) | [Prysm](https://github.com/prysmaticlabs/prysm) | [Teku](https://github.com/ConsenSys/teku) |
|----------------------------------------------------------------------------------------------------------|--------------------------------------------------|---------------------------------------------------|----------------------------------------------------|-------------------------------------------------|-------------------------------------------|

## Version 2.4.0

__Note__ Clients can add notes about level of support for specific endpoints if there are caveats or aspects not implemented.

| Endpoint | [Lighthouse](https://github.com/sigp/lighthouse) | [Lodestar](https://github.com/ChainSafe/lodestar) | [Nimbus](https://github.com/status-im/nimbus-eth2) | [Prysm](https://github.com/prysmaticlabs/prysm) | [Teku](https://github.com/ConsenSys/teku) |
|----------|--------------------------------------------------|---------------------------------------------------|----------------------------------------------------|-------------------------------------------------|-------------------------------------------|
