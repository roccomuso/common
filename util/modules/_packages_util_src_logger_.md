**Polkadot JS Common**

> [README](../README.md) / [Globals](../globals.md) / "packages/util/src/logger"

# Module: "packages/util/src/logger"

## Index

### Functions

* [format](_packages_util_src_logger_.md#format)
* [logger](_packages_util_src_logger_.md#logger)

## Functions

### format

▸ **format**(`value`: unknown): unknown

*Defined in [packages/util/src/logger.ts:43](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util/src/logger.ts#L43)*

#### Parameters:

Name | Type |
------ | ------ |
`value` | unknown |

**Returns:** unknown

___

### logger

▸ **logger**(`_type`: string): [Logger](../interfaces/_packages_util_src_types_.logger.md)

*Defined in [packages/util/src/logger.ts:102](https://github.com/polkadot-js/common/blob/bd1735ca/packages/util/src/logger.ts#L102)*

**`name`** Logger

**`summary`** Creates a consistent log interface for messages

**`description`** 
Returns a `Logger` that has `.log`, `.error`, `.warn` and `.debug` (controlled with environment `DEBUG=typeA,typeB`) methods. Logging is done with a consistent prefix (type of logger, date) followed by the actual message using the underlying console.

**`example`** 
<BR>

```javascript
const l from '@polkadot/util/logger')('test');

l.log('blah'); // <date>     TEST: blah
```

#### Parameters:

Name | Type |
------ | ------ |
`_type` | string |

**Returns:** [Logger](../interfaces/_packages_util_src_types_.logger.md)