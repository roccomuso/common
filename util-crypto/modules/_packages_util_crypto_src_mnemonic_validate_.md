**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util-crypto/src/mnemonic/validate"

# Module: "packages/util-crypto/src/mnemonic/validate"

## Index

### Functions

* [mnemonicValidate](_packages_util_crypto_src_mnemonic_validate_.md#mnemonicvalidate)

## Functions

### mnemonicValidate

▸ **mnemonicValidate**(`mnemonic`: string): boolean

*Defined in [packages/util-crypto/src/mnemonic/validate.ts:22](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util-crypto/src/mnemonic/validate.ts#L22)*

**`name`** mnemonicValidate

**`summary`** Validates a mnemonic input using [BIP39](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki).

**`example`** 
<BR>

```javascript
import { mnemonicGenerate, mnemonicValidate } from '@polkadot/util-crypto';

const mnemonic = mnemonicGenerate(); // => string
const isValidMnemonic = mnemonicValidate(mnemonic); // => boolean
```

#### Parameters:

Name | Type |
------ | ------ |
`mnemonic` | string |

**Returns:** boolean