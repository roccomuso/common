**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/u8a/toBuffer"

# Module: "packages/util/src/u8a/toBuffer"

## Index

### Functions

* [u8aToBuffer](_packages_util_src_u8a_tobuffer_.md#u8atobuffer)

## Functions

### u8aToBuffer

▸ **u8aToBuffer**(`value?`: Uint8Array \| null): Buffer

*Defined in [packages/util/src/u8a/toBuffer.ts:18](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util/src/u8a/toBuffer.ts#L18)*

**`name`** u8aToBuffer

**`summary`** Creates a Buffer object from a hex string.

**`description`** 
`null` inputs returns an empty `Buffer` result. `UInt8Array` input values return the actual bytes value converted to a `Buffer`. Anything that is not a `UInt8Array` throws an error.

**`example`** 
<BR>

```javascript
import { u8aToBuffer } from '@polkadot/util';

console.log('Buffer', u8aToBuffer('0x123480001f'));
```

#### Parameters:

Name | Type |
------ | ------ |
`value?` | Uint8Array \| null |

**Returns:** Buffer