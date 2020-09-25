**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/address/eq"

# Module: "packages/util-crypto/src/address/eq"

## Index

### Functions

* [addressEq](_packages_util_crypto_src_address_eq_.md#addresseq)

## Functions

### addressEq

▸ **addressEq**(`a`: string \| Uint8Array, `b`: string \| Uint8Array): boolean

*Defined in [packages/util-crypto/src/address/eq.ts:22](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/address/eq.ts#L22)*

**`name`** addressEq

**`summary`** Compares two addresses, either in ss58, Uint8Array or hex format.

**`description`** 
For the input values, return true is the underlying public keys do match.

**`example`** 
<BR>

```javascript
import { u8aEq } from '@polkadot/util';

u8aEq(new Uint8Array([0x68, 0x65]), new Uint8Array([0x68, 0x65])); // true
```

#### Parameters:

Name | Type |
------ | ------ |
`a` | string \| Uint8Array |
`b` | string \| Uint8Array |

**Returns:** boolean