**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/is/bigInt"

# Module: "packages/util/src/is/bigInt"

## Index

### Functions

* [isBigInt](_packages_util_src_is_bigint_.md#isbigint)

## Functions

### isBigInt

▸ **isBigInt**(`value`: unknown): value is BigInt

*Defined in [packages/util/src/is/bigInt.ts:18](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util/src/is/bigInt.ts#L18)*

**`name`** isBigInt

**`summary`** Tests for a `BigInt` object instance.

**`description`** 
Checks to see if the input object is an instance of `BigInt`

**`example`** 
<BR>

```javascript
import { isBigInt } from '@polkadot/util';

console.log('isBigInt', isBigInt(123_456n)); // => true
```

#### Parameters:

Name | Type |
------ | ------ |
`value` | unknown |

**Returns:** value is BigInt