**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/secp256k1/recover"

# Module: "packages/util-crypto/src/secp256k1/recover"

## Index

### Functions

* [secp256k1Recover](_packages_util_crypto_src_secp256k1_recover_.md#secp256k1recover)

## Functions

### secp256k1Recover

▸ **secp256k1Recover**(`message`: Uint8Array, `signature`: Uint8Array, `recovery`: number): Uint8Array

*Defined in [packages/util-crypto/src/secp256k1/recover.ts:13](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/secp256k1/recover.ts#L13)*

**`name`** secp256k1Recover

**`description`** Recovers a publicKey from the supplied signature

#### Parameters:

Name | Type |
------ | ------ |
`message` | Uint8Array |
`signature` | Uint8Array |
`recovery` | number |

**Returns:** Uint8Array