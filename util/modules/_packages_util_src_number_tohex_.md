**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/number/toHex"

# Module: "packages/util/src/number/toHex"

## Index

### Functions

* [numberToHex](_packages_util_src_number_tohex_.md#numbertohex)

## Functions

### numberToHex

▸ **numberToHex**(`value?`: number \| null, `bitLength`: number): string

*Defined in [packages/util/src/number/toHex.ts:23](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util/src/number/toHex.ts#L23)*

**`name`** numberToHex

**`summary`** Creates a hex value from a number.

**`description`** 
`null`/`undefined`/`NaN` inputs returns an empty `0x` result. `number` input values return the actual bytes value converted to a `hex`. With `bitLength` set, it converts the number to the equivalent size.

**`example`** 
<BR>

```javascript
import { numberToHex } from '@polkadot/util';

numberToHex(0x1234); // => '0x1234'
numberToHex(0x1234, 32); // => 0x00001234
```

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`value?` | number \| null | - |
`bitLength` | number | -1 |

**Returns:** string