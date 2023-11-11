# provenance
Yaypegs use the hash functions SHA-256. In order to validate the provenance or any image hash, you must use the same hashing algorithm.

This repository is a faithful record of representing each Yaypegs and their respective provenance record. This is a way in which Developers can prove that the order of the Token Image and metadata was set pre-mint, and was not manipulated. Also generate a fair random number post-mint to start the distribution of the NFTs from that number.

# METHODOLOGY

1. Shuffle: Once the creation of all the art assets is finished, we shuffle all 10,000 Yaypegs metadata files.
2. Hash Images: A hash was generated for each image using SHA-256 algorithm.
3. Concatenated: All the resulting hashes were concatenated into a single huge string in the specific order as listed below.
4. Hash Concatenated: The final proof was obtained by SHA-256 hashing the concatenated string.
5. Provenance Function: The final provenance record was saved in the smart contract through the provenance function.
6. Starting Index: We use the last 4 digits (not including the 0) of the Transaction Hash: 0xde11db9032df290a23fcbc3bf2ffaa4f7ff2b89608a0d28627fe30ed5cb90aba originated from executing the Set Provenance function in the contract, resulting in a stratating index of 7359. So we show that the initial number was not manipulated.
7. New Index: The start of the collection will be moved from the original shuffled metadata of token #1 to the new Starting Index #7359.

# SUMMARY

Starting Index -> 7359
Contract Address -> 0x7fda36c8daEDcc55B73E964c2831D6161eF60a75
Collection Proof Hash -> c9baeaba72444e7a23d095f2abae92fe665cf4845905de2894b31401e0d6b8b2
