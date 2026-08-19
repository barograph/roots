# roots
Barograph — integrity roots

This repository publishes the daily integrity roots of the Barograph archive. Each file commits the chained Merkle root of the prior UTC day's archived observations: every recorded payload is hashed at ingestion, daily manifests roll those hashes into a Merkle root, and each day's root incorporates the previous day's, so no historical day can be altered without breaking every day that follows. Commits here serve as one of several independent public timestamps of those roots. Verification tooling and methodology documentation will be published alongside the archive.
