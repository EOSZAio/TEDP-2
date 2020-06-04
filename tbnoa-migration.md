# References

* [Telos amend reference guide](https://docs.telos.net/developers/services/telos-amend/create-a-document)

# Actions performed

```bash
# Creare current TBNOA document
TITLE="Telos Blockchain Network Operating Agreement"
SUBTITLE=""
DOCUMENTNAME="tbnoa"
AUTHOR="rorymapstone"
SECTIONS="[ { "key": "0", "value": "https://web.ipfs.telosfoundation.io/QmSi757FX4R3TFvRteNAigHLJhtFMXo76Ugj8j4AB9RMqP" },
            { "key": "1", "value": "https://web.ipfs.telosfoundation.io/QmdsjEpeQ9JKceYKsmcCC1B37sPmyBhcNbUHMc1rJ9T8ox" },
            { "key": "2", "value": "https://web.ipfs.telosfoundation.io/QmS66FQar4oohK2jQSzoE1i3pChgwfi9cwWHJQkbqpuVye" },
            { "key": "3", "value": "https://web.ipfs.telosfoundation.io/QmbZJRZRGpBjfkLZEK5zDso4B4maTu1Wjj6CXf1Xp7RXkt" },
            { "key": "4", "value": "https://web.ipfs.telosfoundation.io/Qmcev211QLBse2Zqe6VhS9KP8ZWGFbWiFuM8TB39BwmrET" },
            { "key": "5", "value": "https://web.ipfs.telosfoundation.io/QmWYVJ1aG5MpwB1nnAYNePoK83CYGC4AtS6hLhYzNyP191" },
            { "key": "6", "value": "https://web.ipfs.telosfoundation.io/QmQL1QarVV5vEvSsqSNDN5YDKHw6RPp5optNAE6TXRkthS" },
            { "key": "7", "value": "https://web.ipfs.telosfoundation.io/QmcCYdC55zMaWpbKMNASZMEcEWiaN7i7nA2fnNHJfw2FXn" },
            { "key": "8", "value": "https://web.ipfs.telosfoundation.io/Qmc15rNPqMoujbmfsCipUunWWzPGoegQgsE7Xe8ZETf4VB" },
            { "key": "9", "value": "https://web.ipfs.telosfoundation.io/QmbQMqX65a9srJhX7vNFye8wP5pSTVguYsaBZwLjDXSzEr" },
            { "key": "10", "value": "https://web.ipfs.telosfoundation.io/QmPST4wNwwvtt3uLLNYSF1iHJ6jKCrnLgtyRZzzT7GVEi4" },
            { "key": "11", "value": "https://web.ipfs.telosfoundation.io/QmXDkB6LgDB9nGvh9vX3cbVj5UgSkmtyRq2spgumL2x1sj" },
            { "key": "12", "value": "https://web.ipfs.telosfoundation.io/QmR4Zc8RVynZbxrEbB7fPfxKNK3NMDqLpcnL27748c153i" },
            { "key": "13", "value": "https://web.ipfs.telosfoundation.io/QmSqaNBs1pPfdoe6bKRaW9s439AVqLP4jEtEcWtEL3btKR" },
            { "key": "14", "value": "https://web.ipfs.telosfoundation.io/QmdXJwD5JwKUjbwTLLcQp2ByY5TfyC7R8NXPtbiUDqHrKX" },
            { "key": "15", "value": "https://web.ipfs.telosfoundation.io/QmZRuaRwpsS9xvXAZVGs3Lx5aKmXGzHypQ62VyX9oSKN4V" },
            { "key": "16", "value": "https://web.ipfs.telosfoundation.io/QmWkRL7UBmpS69qjnXzig7ZFrxJSo35njSDEkECR163wLB" },
            { "key": "17", "value": "https://web.ipfs.telosfoundation.io/QmZqLvvXmqkW7AQ4XL5bFRLrrqb4tPPgcrdgwbtgUs4cYa" },
            { "key": "18", "value": "https://web.ipfs.telosfoundation.io/Qmbh1tM4mRCGxxCWBibT4ffMNXxeC7ejFSh5HHH54k1mgq" },
            { "key": "19", "value": "https://web.ipfs.telosfoundation.io/QmVs3Vtx3DgiztGnb1oGXLmHjeCYhHt7ksVhjjyCbP7onC" },
            { "key": "20", "value": "https://web.ipfs.telosfoundation.io/QmXJbYy9uEVktESPKoYpc4y4RAu9cZjwK6mx1U3rVeKbHx" },
            { "key": "21", "value": "https://web.ipfs.telosfoundation.io/QmUFJdpKCCLaruoYmGPzPJLSdWHz85uV1xGKP6gosQkQFH" },
            { "key": "22", "value": "https://web.ipfs.telosfoundation.io/QmTasg7R4SBHQ353QUmEaSBYRqn2zRaJ3ki3bTDckbnbfb" },
            { "key": "23", "value": "https://web.ipfs.telosfoundation.io/QmTjBNyskVN65qnkeiv74CeNu9moZXiEat9JGpga9GZHjp" },
            { "key": "24", "value": "https://web.ipfs.telosfoundation.io/QmeqTSK2VpPpL53KHx425cbYJxxpor1C3BNQW4Bnt3MNuS" },
            { "key": "25", "value": "https://web.ipfs.telosfoundation.io/Qmctmqbnu1Gx7RRw1PucHXrHnw4DgnjR81xkSLFQyM3zu4" },
            { "key": "26", "value": "https://web.ipfs.telosfoundation.io/QmP4JBfBgA3rkBAsRVsywkZaLFPH3JtfHBwC798wyBwGD1" },
            { "key": "27", "value": "https://web.ipfs.telosfoundation.io/QmazxHD7pQ8mkJE5HzddGKca99jpHWTuTqzrfCvgPjU1Ks" },
            { "key": "28", "value": "https://web.ipfs.telosfoundation.io/QmVRfceDVBqHR7uPxd8B7HoQUqF3LnGUDhL3TGAXf3RnMG" },
            { "key": "29", "value": "https://web.ipfs.telosfoundation.io/QmQ96z6aXnkHN9LztQtU98h8RGF7diLXUrN8uDo4Eg6gv8" },
            { "key": "30", "value": "https://web.ipfs.telosfoundation.io/QmZHMnCLqXsjumghx9RehbXZiUgB9WWq86ag9T2eLxzRpP" },
            { "key": "31", "value": "https://web.ipfs.telosfoundation.io/QmQypxz1PqPpyruMDSZjsoHeN2ousvoVFcNamMQc6xoxZo" },
            { "key": "32", "value": "https://web.ipfs.telosfoundation.io/Qme8XGRRNxcm123wDqz2bHjLNa2Bxm9tyBG9B8RSRvtG1u" },
            { "key": "33", "value": "https://web.ipfs.telosfoundation.io/QmcZEvDJypk8ZCCAmcS9epcMPGhHV7iEkqT6zuEZZ6J5Yh" },
            { "key": "34", "value": "https://web.ipfs.telosfoundation.io/QmeqhUBr1vEgwpEG3kdxW9RNQAibKZavQnAztFSTSf6n4Z" },
            { "key": "35", "value": "https://web.ipfs.telosfoundation.io/QmcXPGzPR6y7HYbs91apYHzzvyCFYtrV9Lc5ndMc7qtVvt" },
            { "key": "36", "value": "https://web.ipfs.telosfoundation.io/QmTo3SY6tUoLfuRXujaWzZ3qFNWhm5MR2zktRfnaJx7AET" },
            { "key": "37", "value": "https://web.ipfs.telosfoundation.io/QmRFeCu2BfmLJEnLS7J2j9vi7SGNh3vJY5DCngZukjuyLz" },
            { "key": "38", "value": "https://web.ipfs.telosfoundation.io/QmSkxP1i4HzbxQnpiWnDjr4gr193yXtJr4WhhjWqpWXwkr" },
            { "key": "39", "value": "https://web.ipfs.telosfoundation.io/QmSYk6EGqEgC4e9FL8keKHB9x6kVVSfSyc93SePUReaENY" },
            { "key": "40", "value": "https://web.ipfs.telosfoundation.io/QmbtUxBQjdftWSdiR4EjTCpaZezvYCUB6BRbQaU7WFx7Hz" },
            { "key": "41", "value": "https://web.ipfs.telosfoundation.io/QmcnRK93MpjarAsFxrkURRpHW6ZL4G14n6MzekBkMtSTgc" },
            { "key": "42", "value": "https://web.ipfs.telosfoundation.io/QmesdVYG2SP4ZJnCV4qvayS8QwCJ54MwCNFP8yJEszRGJB" },
            { "key": "43", "value": "https://web.ipfs.telosfoundation.io/QmYahWtSFnXvC2hdhM64AD6b3VkowmdpxaLaUPBGyFM67z" },
            { "key": "44", "value": "https://web.ipfs.telosfoundation.io/QmXSKApWscwp4FNzgE6GzX3LtXvfSFtY9Z6jRcQG6unN9N" },
            { "key": "45", "value": "https://web.ipfs.telosfoundation.io/QmPwZo32aryH74DYtWi2rkUq7zCh5dXJqHhL69mUNVdeq5" },
            { "key": "46", "value": "https://web.ipfs.telosfoundation.io/QmaMrxaQRLFwwwzxQi5epkHeUoRRQ9WNrvhJTBzJUHsJr5" },
            { "key": "47", "value": "https://web.ipfs.telosfoundation.io/Qmbtf3zKCmVyKFRv5tBFFRnqJt2jtQoqowXwot4CCZALr5" },
            { "key": "48", "value": "https://web.ipfs.telosfoundation.io/QmRfpQR4b9vzAnPkNf27JSQ4viBgUTVtLBdBtnCzKMZhek" },
            { "key": "49", "value": "https://web.ipfs.telosfoundation.io/QmcStUZe5fLi4H5LDYEz9azyDLJRs8oU3R7ztwzP9KsTga" } ]"

cleos push action amend.decide newdocument '{ ... }' -p author
```

