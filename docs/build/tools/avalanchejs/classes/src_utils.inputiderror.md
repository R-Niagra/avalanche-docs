[avalanche](../README.md) › [src/utils](../modules/src_utils.md) › [InputIdError](src_utils.inputiderror.md)

# Class: InputIdError

## Hierarchy

  ↳ [AvalancheError](src_utils.avalancheerror.md)

  ↳ **InputIdError**

## Index

### Constructors

* [constructor](src_utils.inputiderror.md#constructor)

### Properties

* [errorCode](src_utils.inputiderror.md#errorcode)
* [message](src_utils.inputiderror.md#message)
* [name](src_utils.inputiderror.md#name)
* [stack](src_utils.inputiderror.md#optional-stack)

### Methods

* [getCode](src_utils.inputiderror.md#getcode)

## Constructors

###  constructor

\+ **new InputIdError**(`m`: string): *[InputIdError](src_utils.inputiderror.md)*

*Overrides [AvalancheError](src_utils.avalancheerror.md).[constructor](src_utils.avalancheerror.md#constructor)*

*Defined in [src/utils/errors.ts:135](https://github.com/ava-labs/avalanchejs/blob/598fbcc/src/utils/errors.ts#L135)*

**Parameters:**

Name | Type |
------ | ------ |
`m` | string |

**Returns:** *[InputIdError](src_utils.inputiderror.md)*

## Properties

###  errorCode

• **errorCode**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[errorCode](src_utils.avalancheerror.md#errorcode)*

*Defined in [src/utils/errors.ts:46](https://github.com/ava-labs/avalanchejs/blob/598fbcc/src/utils/errors.ts#L46)*

___

###  message

• **message**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[message](src_utils.avalancheerror.md#message)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1023

___

###  name

• **name**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[name](src_utils.avalancheerror.md#name)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1022

___

### `Optional` stack

• **stack**? : *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[stack](src_utils.avalancheerror.md#optional-stack)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1024

## Methods

###  getCode

▸ **getCode**(): *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[getCode](src_utils.avalancheerror.md#getcode)*

*Defined in [src/utils/errors.ts:53](https://github.com/ava-labs/avalanchejs/blob/598fbcc/src/utils/errors.ts#L53)*

**Returns:** *string*
