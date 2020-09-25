**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/bn/min"

# Module: "packages/util/src/bn/min"

## Index

### Functions

* [min](_packages_util_src_bn_min_.md#min)

## Functions

### min

▸ **min**(...`items`: BN[]): BN

*Defined in [packages/util/src/bn/min.ts:21](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util/src/bn/min.ts#L21)*

**`name`** bnMin

**`summary`** Finds and returns the smallest value in an array of BNs.

**`example`** 
<BR>

```javascript
import BN from 'bn.js';
import { bnMin } from '@polkadot/util';

bnMin([new BN(1), new BN(3), new BN(2)]).toString(); // => '1'
```

#### Parameters:

Name | Type |
------ | ------ |
`...items` | BN[] |

**Returns:** BN