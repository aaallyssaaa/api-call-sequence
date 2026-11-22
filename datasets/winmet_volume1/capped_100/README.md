# WinMET Volume 1 - Per-family Cap 100

Source: https://zenodo.org/records/16414116

Each family retains at most 100 traces. Families with fewer than 100 traces retain all available traces.

Sampling: deterministic per-family reservoir sampling with random seed 42.

Each JSONL row contains exactly `family` and `api_sequences`.
All process API call sequences are preserved without truncation.

This is a sampling dataset, not a train/validation/test split.
