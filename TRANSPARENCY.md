# Public transparency contract

FR3K device connection events are stored privately in an append-only dual hash chain. Public proof material consists of cumulative Merkle roots, checkpoint hashes, Ed25519 signatures, signer public-key fingerprints, and optional external timestamp receipts.

Public records intentionally exclude raw MAC addresses, private IP addresses, exact private gateway locations, credentials and fine-grained private connection timelines.

A private event can later be proven to have existed under a published checkpoint with a Merkle inclusion proof without exposing unrelated events.
