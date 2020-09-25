**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/nacl/keypair/fromSeed"

# Module: "packages/util-crypto/src/nacl/keypair/fromSeed"

## Index

### Functions

* [naclKeypairFromSeed](_packages_util_crypto_src_nacl_keypair_fromseed_.md#naclkeypairfromseed)

## Functions

### naclKeypairFromSeed

▸ **naclKeypairFromSeed**(`seed`: Uint8Array): [Keypair](../interfaces/_packages_util_crypto_src_types_.keypair.md)

*Defined in [packages/util-crypto/src/nacl/keypair/fromSeed.ts:23](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/nacl/keypair/fromSeed.ts#L23)*

**`name`** naclKeypairFromSeed

**`summary`** Creates a new public/secret keypair from a seed.

**`description`** 
Returns a object containing a `publicKey` & `secretKey` generated from the supplied seed.

**`example`** 
<BR>

```javascript
import { naclKeypairFromSeed } from '@polkadot/util-crypto';

naclKeypairFromSeed(...); // => { secretKey: [...], publicKey: [...] }
```

#### Parameters:

Name | Type |
------ | ------ |
`seed` | Uint8Array |

**Returns:** [Keypair](../interfaces/_packages_util_crypto_src_types_.keypair.md)