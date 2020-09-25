**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/u8a/toBn"

# Module: "packages/util/src/u8a/toBn"

## Index

### Functions

* [u8aToBn](_packages_util_src_u8a_tobn_.md#u8atobn)

## Functions

### u8aToBn

▸ **u8aToBn**(`value`: Uint8Array, `options`: [ToBnOptions](../interfaces/_packages_util_src_types_.tobnoptions.md) \| boolean): BN

*Defined in [packages/util/src/u8a/toBn.ts:28](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util/src/u8a/toBn.ts#L28)*

**`name`** u8aToBn

**`summary`** Creates a BN from a Uint8Array object.

**`description`** 
`UInt8Array` input values return the actual BN. `null` or `undefined` values returns an `0x0` value.

**`example`** 
<BR>

```javascript
import { u8aToBn } from '@polkadot/util';

u8aToHex(new Uint8Array([0x68, 0x65, 0x6c, 0x6c, 0xf])); // 0x68656c0f
```

#### Parameters:

Name | Type | Default value | Description |
------ | ------ | ------ | ------ |
`value` | Uint8Array | - | The value to convert |
`options` | [ToBnOptions](../interfaces/_packages_util_src_types_.tobnoptions.md) \| boolean | { isLe: true, isNegative: false } | Options to pass while converting |

**Returns:** BN