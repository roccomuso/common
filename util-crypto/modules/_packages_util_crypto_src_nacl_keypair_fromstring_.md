**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/nacl/keypair/fromString"

# Module: "packages/util-crypto/src/nacl/keypair/fromString"

## Index

### Functions

* [naclKeypairFromString](_packages_util_crypto_src_nacl_keypair_fromstring_.md#naclkeypairfromstring)

## Functions

### naclKeypairFromString

▸ **naclKeypairFromString**(`value`: string): [Keypair](../interfaces/_packages_util_crypto_src_types_.keypair.md)

*Defined in [packages/util-crypto/src/nacl/keypair/fromString.ts:25](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/nacl/keypair/fromString.ts#L25)*

**`name`** naclKeypairFromString

**`summary`** Creates a new public/secret keypair from a string.

**`description`** 
Returns a object containing a `publicKey` & `secretKey` generated from the supplied string. The string is hashed and the value used as the input seed.

**`example`** 
<BR>

```javascript
import { naclKeypairFromString } from '@polkadot/util-crypto';

naclKeypairFromString('test'); // => { secretKey: [...], publicKey: [...] }
```

#### Parameters:

Name | Type |
------ | ------ |
`value` | string |

**Returns:** [Keypair](../interfaces/_packages_util_crypto_src_types_.keypair.md)