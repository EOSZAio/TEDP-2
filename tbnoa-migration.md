# References

* [Telos amend reference guide](https://docs.telos.net/developers/services/telos-amend/create-a-document)

# Actions performed

```bash
# Creare a new document
TITLE="Telos Blockchain Network Operating Agreement"
SUBTITLE=""
DOCUMENTNAME="tbnoa"
AUTHOR=""
SECTIONS=""

cleos push action amend.decide newdocument '{ ... }' -p author
```

