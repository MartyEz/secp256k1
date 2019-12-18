Fork of : https://github.com/ethereum/go-ethereum/tree/master/crypto/secp256k1

Add a function to retrieve pubKey from privKey using the secp256k1 elliptic curve

`func GetPubkeyFromPrivkey(priv []byte) []byte`

Add a function to retrieve compressed pubKey from privKey using the secp256k1 elliptic curve

`func GetCompressedPubkeyFromPrivkey(priv []byte) []byte`

Tests are included in secp256_test.go