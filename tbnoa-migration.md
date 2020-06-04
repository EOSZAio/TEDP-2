# References

* [Telos amend reference guide](https://docs.telos.net/developers/services/telos-amend/create-a-document)

# Actions performed

```bash
# Creare a new document
TITLE="Telos Blockchain Network Operating Agreement"
SUBTITLE=""
DOCUMENTNAME="tbnoa"
AUTHOR=""
SECTIONS="[ { "key": "a", "value": "https://web.ipfs.telosfoundation.io/QmSi757FX4R3TFvRteNAigHLJhtFMXo76Ugj8j4AB9RMqP" },
            { "key": "b", "value": "https://web.ipfs.telosfoundation.io/QmdsjEpeQ9JKceYKsmcCC1B37sPmyBhcNbUHMc1rJ9T8ox" },
            { "key": "c", "value": "https://web.ipfs.telosfoundation.io/QmS66FQar4oohK2jQSzoE1i3pChgwfi9cwWHJQkbqpuVye" },
            { "key": "d", "value": "https://web.ipfs.telosfoundation.io/QmbZJRZRGpBjfkLZEK5zDso4B4maTu1Wjj6CXf1Xp7RXkt" },
            { "key": "e", "value": "https://web.ipfs.telosfoundation.io/Qmcev211QLBse2Zqe6VhS9KP8ZWGFbWiFuM8TB39BwmrET" },
            { "key": "f", "value": "https://web.ipfs.telosfoundation.io/QmWYVJ1aG5MpwB1nnAYNePoK83CYGC4AtS6hLhYzNyP191" },
            { "key": "g", "value": "https://web.ipfs.telosfoundation.io/QmQL1QarVV5vEvSsqSNDN5YDKHw6RPp5optNAE6TXRkthS" },
            { "key": "h", "value": "https://web.ipfs.telosfoundation.io/QmcCYdC55zMaWpbKMNASZMEcEWiaN7i7nA2fnNHJfw2FXn" },
            { "key": "i", "value": "https://web.ipfs.telosfoundation.io/Qmc15rNPqMoujbmfsCipUunWWzPGoegQgsE7Xe8ZETf4VB" },
            { "key": "j", "value": "https://web.ipfs.telosfoundation.io/QmbQMqX65a9srJhX7vNFye8wP5pSTVguYsaBZwLjDXSzEr" },
            { "key": "k", "value": "https://web.ipfs.telosfoundation.io/QmPST4wNwwvtt3uLLNYSF1iHJ6jKCrnLgtyRZzzT7GVEi4" },
            { "key": "l", "value": "https://web.ipfs.telosfoundation.io/QmXDkB6LgDB9nGvh9vX3cbVj5UgSkmtyRq2spgumL2x1sj" },
            { "key": "m", "value": "https://web.ipfs.telosfoundation.io/QmR4Zc8RVynZbxrEbB7fPfxKNK3NMDqLpcnL27748c153i" },
            { "key": "n", "value": "https://web.ipfs.telosfoundation.io/QmSqaNBs1pPfdoe6bKRaW9s439AVqLP4jEtEcWtEL3btKR" },
            { "key": "o", "value": "https://web.ipfs.telosfoundation.io/QmdXJwD5JwKUjbwTLLcQp2ByY5TfyC7R8NXPtbiUDqHrKX" },
            { "key": "p", "value": "https://web.ipfs.telosfoundation.io/QmZRuaRwpsS9xvXAZVGs3Lx5aKmXGzHypQ62VyX9oSKN4V" },
            { "key": "q", "value": "https://web.ipfs.telosfoundation.io/QmWkRL7UBmpS69qjnXzig7ZFrxJSo35njSDEkECR163wLB" },
            { "key": "r", "value": "https://web.ipfs.telosfoundation.io/QmZqLvvXmqkW7AQ4XL5bFRLrrqb4tPPgcrdgwbtgUs4cYa" },
            { "key": "s", "value": "https://web.ipfs.telosfoundation.io/Qmbh1tM4mRCGxxCWBibT4ffMNXxeC7ejFSh5HHH54k1mgq" },
            { "key": "t", "value": "https://web.ipfs.telosfoundation.io/QmVs3Vtx3DgiztGnb1oGXLmHjeCYhHt7ksVhjjyCbP7onC" },
            { "key": "u", "value": "https://web.ipfs.telosfoundation.io/QmXJbYy9uEVktESPKoYpc4y4RAu9cZjwK6mx1U3rVeKbHx" },
            { "key": "v", "value": "https://web.ipfs.telosfoundation.io/QmUFJdpKCCLaruoYmGPzPJLSdWHz85uV1xGKP6gosQkQFH" },
            { "key": "w", "value": "https://web.ipfs.telosfoundation.io/QmTasg7R4SBHQ353QUmEaSBYRqn2zRaJ3ki3bTDckbnbfb" },
            { "key": "x", "value": "https://web.ipfs.telosfoundation.io/QmTjBNyskVN65qnkeiv74CeNu9moZXiEat9JGpga9GZHjp" },
            { "key": "y", "value": "https://web.ipfs.telosfoundation.io/QmeqTSK2VpPpL53KHx425cbYJxxpor1C3BNQW4Bnt3MNuS" },
            { "key": "z", "value": "https://web.ipfs.telosfoundation.io/Qmctmqbnu1Gx7RRw1PucHXrHnw4DgnjR81xkSLFQyM3zu4" },
            { "key": "aa", "value": "https://web.ipfs.telosfoundation.io/QmP4JBfBgA3rkBAsRVsywkZaLFPH3JtfHBwC798wyBwGD1" },
            { "key": "ab", "value": "https://web.ipfs.telosfoundation.io/QmazxHD7pQ8mkJE5HzddGKca99jpHWTuTqzrfCvgPjU1Ks" },
            { "key": "ac", "value": "https://web.ipfs.telosfoundation.io/QmVRfceDVBqHR7uPxd8B7HoQUqF3LnGUDhL3TGAXf3RnMG" },
            { "key": "ad", "value": "https://web.ipfs.telosfoundation.io/QmQ96z6aXnkHN9LztQtU98h8RGF7diLXUrN8uDo4Eg6gv8" },
            { "key": "ae", "value": "https://web.ipfs.telosfoundation.io/QmZHMnCLqXsjumghx9RehbXZiUgB9WWq86ag9T2eLxzRpP" },
            { "key": "af", "value": "https://web.ipfs.telosfoundation.io/QmQypxz1PqPpyruMDSZjsoHeN2ousvoVFcNamMQc6xoxZo" },
            { "key": "ag", "value": "https://web.ipfs.telosfoundation.io/Qme8XGRRNxcm123wDqz2bHjLNa2Bxm9tyBG9B8RSRvtG1u" },
            { "key": "ah", "value": "https://web.ipfs.telosfoundation.io/QmcZEvDJypk8ZCCAmcS9epcMPGhHV7iEkqT6zuEZZ6J5Yh" },
            { "key": "ai", "value": "https://web.ipfs.telosfoundation.io/QmeqhUBr1vEgwpEG3kdxW9RNQAibKZavQnAztFSTSf6n4Z" },
            { "key": "aj", "value": "https://web.ipfs.telosfoundation.io/QmcXPGzPR6y7HYbs91apYHzzvyCFYtrV9Lc5ndMc7qtVvt" },
            { "key": "ak", "value": "https://web.ipfs.telosfoundation.io/QmTo3SY6tUoLfuRXujaWzZ3qFNWhm5MR2zktRfnaJx7AET" },
            { "key": "al", "value": "https://web.ipfs.telosfoundation.io/QmRFeCu2BfmLJEnLS7J2j9vi7SGNh3vJY5DCngZukjuyLz" },
            { "key": "am", "value": "https://web.ipfs.telosfoundation.io/QmSkxP1i4HzbxQnpiWnDjr4gr193yXtJr4WhhjWqpWXwkr" },
            { "key": "an", "value": "https://web.ipfs.telosfoundation.io/QmSYk6EGqEgC4e9FL8keKHB9x6kVVSfSyc93SePUReaENY" },
            { "key": "ao", "value": "https://web.ipfs.telosfoundation.io/QmbtUxBQjdftWSdiR4EjTCpaZezvYCUB6BRbQaU7WFx7Hz" },
            { "key": "ap", "value": "https://web.ipfs.telosfoundation.io/QmcnRK93MpjarAsFxrkURRpHW6ZL4G14n6MzekBkMtSTgc" },
            { "key": "aq", "value": "https://web.ipfs.telosfoundation.io/QmesdVYG2SP4ZJnCV4qvayS8QwCJ54MwCNFP8yJEszRGJB" },
            { "key": "ar", "value": "https://web.ipfs.telosfoundation.io/QmYahWtSFnXvC2hdhM64AD6b3VkowmdpxaLaUPBGyFM67z" },
            { "key": "as", "value": "https://web.ipfs.telosfoundation.io/QmXSKApWscwp4FNzgE6GzX3LtXvfSFtY9Z6jRcQG6unN9N" },
            { "key": "at", "value": "https://web.ipfs.telosfoundation.io/QmPwZo32aryH74DYtWi2rkUq7zCh5dXJqHhL69mUNVdeq5" },
            { "key": "au", "value": "https://web.ipfs.telosfoundation.io/QmaMrxaQRLFwwwzxQi5epkHeUoRRQ9WNrvhJTBzJUHsJr5" },
            { "key": "av", "value": "https://web.ipfs.telosfoundation.io/Qmbtf3zKCmVyKFRv5tBFFRnqJt2jtQoqowXwot4CCZALr5" },
            { "key": "aw", "value": "https://web.ipfs.telosfoundation.io/QmRfpQR4b9vzAnPkNf27JSQ4viBgUTVtLBdBtnCzKMZhek" },
            { "key": "ax", "value": "https://web.ipfs.telosfoundation.io/QmcStUZe5fLi4H5LDYEz9azyDLJRs8oU3R7ztwzP9KsTga" } ]

"

cleos push action amend.decide newdocument '{ ... }' -p author
```

