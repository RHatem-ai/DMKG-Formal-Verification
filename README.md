# DMKG Formal Verification Using ProVerif and Tamarin

This repository provides the formal models, security verification results, and performance measurements for the Distributed Multi-Key Generation (DMKG) protocol.

## Formal Verification Tools

- **ProVerif:** Symbolic verification of cryptographic protocols.
- **Tamarin:** Symbolic verification using multiset rewriting rules.

## Security Properties

The following security properties are analyzed:

1. Z contribution secrecy
2. VMSS contributions secrecy
3. Final secret-key secrecy
4. PVSS transcript authentication
5. VMSS transcript authentication

## Repository Contents

- `ProVerif/Models/`: ProVerif specifications
- `ProVerif/Results/`: Verification outputs
- `ProVerif/Metrics/`: Execution time and memory measurements
- `Tamarin/Models/`: Tamarin specifications
- `Tamarin/Results/`: Verification outputs
- `Tamarin/Metrics/`: Execution time and memory measurements

## Experimental Evaluation

The repository includes execution-time measurements, peak memory consumption, and verification outcomes for individual security properties and global verification.

## Associated Publication

Formal Verification of Cryptographic Protocols: An Experimental Study of ProVerif and Tamarin on a Distributed Multi-Key Generation Protocol.
